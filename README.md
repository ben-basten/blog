[![Netlify Status](https://api.netlify.com/api/v1/badges/6d4ad44a-95a5-4b2b-b0e4-f9a8c55ee681/deploy-status)](https://app.netlify.com/sites/syntax-cauliflower/deploys)
# Blog

Personal blog and project portfolio.

## Running development server

* `hugo server` - runs the Hugo server
* `hugo server -D` - runs the Hugo server with drafts. 
  * If the front matter of a Markdown file contains `draft: true`, the post has been marked as a draft and you will be able to see the work in progress.

## Compiling for production

1. `hugo` - add `--minify` option for minified output
2. Static HTML can be found in the `public/` folder

## Creating new content

* Blog post: `hugo new posts/sampleTitle.md`
* Portfolio entry: `hugo new projects/projectTitle.md`
* Standalone page: `hugo new aboutMe.md`