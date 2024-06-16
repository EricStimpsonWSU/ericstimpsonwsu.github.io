# ericstimpsonwsu.github.io
Home of my research blog, proof of concepts demos, and links to demos and other content in research repositories.

## Setting Up GitHub Pages
The site is published at https://ericstimpsonwsu.github.io from the main/root

## Setting Up Jekyll with GitHub Actions
We’re using GitHub Actions to build our site with Jekyll. We created a .github/workflows/jekyll.yml file to define our GitHub Actions workflow. This workflow runs every time we push to the main branch of our repository, and it builds and deploys our Jekyll site to GitHub Pages. We also created an index.md file in the root of our repository to serve as the main page of our blog.

## Creating a Default Layout
We created a _layouts/default.html file to serve as a template for our pages. This file includes placeholders for the title and content of each page, as well as the MathJax script for rendering LaTeX syntax. We can customize this file to add a header or footer, include a navigation menu, or apply CSS styles.

## Creating a Blog Post with MathJax
To create a blog post with a LaTeX math equation, create a new file in the _posts directory. The name of the file should follow the format YEAR-MONTH-DAY-title.md. Write the blog post in Markdown and include LaTeX math equations using the $$ syntax. To enable MathJax to render the equations, the MathJax script was added to the <head> section of the _layouts/default.html file.
