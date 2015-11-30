# Open Transport website source

Hugo template files and content for Open Transport website

## Local development

1. Install Hugo: http://gohugo.io/ (easy to install since it's a Go binary)
2. Clone this repo
3. CD to repo and install build dependencies : `npm install`
3. Run `npm start` to build and minify css/js, run server and watch. Alternatively you can run `npm run build` + `hugo server --watch`

## Deployment

**Be careful when pushing to Master**

The site is hosted with Netlify: https://www.netlify.com/

To deploy a new version you simply push the updated repo to Master. The site will be built on Netlify and deployed to their CDN. Takes about 10 seconds to be globally live.

*If you're making major revisions that require review, you will be better creating a new branch and pushing that instead.*

## Editing content

The content lives in Markdown files in the 'Content' folder. These can be created and edited directly on Github if you don't want to download the repo and use Git.
