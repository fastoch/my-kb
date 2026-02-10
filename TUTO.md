# Resources

- Docusaurus v3.5 - Install, Customize, and Deploy: https://www.youtube.com/watch?v=QfqLQwPxFWw
- Official website: https://docusaurus.io/

Latest version of Docusaurus is 3.9 (February 2026)

# What is Docusaurus?

It's an open-source tool for building documentation websites using React and Markdown.  
It's SEO-friendly because it pre-renders your HTML pages, which enhances the search engine ratings for your website.  

Docusaurus offers very useful plugins such as: 
- translation of your docs into multiple languages
- document versioning
- very efficient content search functionality

# Why I'll be using it

The goal is to have a free online solution for hosting my personal knowledge base (markdown files).  

To achieve that, I need to:
- Put all my notes in a Git repo (GitHub/GitLab).
- Add Docusaurus to generate a documentation website with built‑in search.​
- Deploy my Docusaurus setup to GitHub Pages or Netlify for zero‑cost hosting

# Docusaurus-based websites 

- The React Native website was built using Docusaurus
- The JEST (JavaScript Testing Framework) website was also built using Docusaurus

# Pre-requisites

- install Node.js
- run `node -v` to confirm installation completed successfully

# Local Docusaurus setup

- `cd` into the directory where you want to have your Docusaurus project set up
- initialize your Docusaurus project by running `npx create-docusaurus@latest my-project classic`
- `cd` into the newly created project folder
- run `npm start` to start the local development server
- your website is now running at http://localhost:3000/
- open the project folder from your favorite IDE

# Understanding the structure of a Docusaurus project

By default, we have a blog folder and a docs folder.  
These folders will host our blog posts and our documents, in Markdown or MDX format.  
MDX is a superset of Markdown, which allows us to use JSX and other React features in our Markdown files.  

## Create a blog post

We can copy an existing blog post from the blog folder and paste it into the same folder.  
The blog post will be automatically added to the blog index page.  

Then, we can customize this post by editing the Markdown file:
- The file name contains the posting date
- The slug inside the Markdown file is used to generate the blog post URL
- The title inside the Markdown file is used to generate the blog post title
- authors and tags specified in the markdown file are defined in the `authors.yml` and `tags.yml` files

## Truncate comment

Inside the .md and .mdx files of the blog folder, we use a special comment to truncate the content of the blog posts.  
On the http://localhost:3000/blog page, we don't want to show the whole content of our blog posts.  



18/89

# Deploy to GitHub pages



