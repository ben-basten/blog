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

_Note: sticking to the hyphenated file naming convention will automatically generate the correct blog title by replacing the hyphens with spaces._

* Blog post: `hugo new posts/Sample-Title.md`
* Portfolio entry: `hugo new projects/Project-Title.md`
* Standalone page: `hugo new About-Me.md`