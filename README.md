# Hugo & Tailwind 4.* (now 4.0.14)

## A barebone Hugo & Tailwind CSS starter kit

**Install to VS Code with:**  
`git clone https://github.com/4044ever/Hugo-Tailwind-4.x optinal-foldername`  
`npm install`

**To start developing:**  
`hugo server`

**To generate the site HTML:**  
`hugo`

To get out of server mode you need to do **Ctrl+c** 

> **Disclaimer:** This is my personal try with Hugo and Tailwind 4.0.* To me it looks like all functions work, classes get updated, a correct `/public/` folder with purged, minified style*.css gets created. Seems production ready, you can build a theme around it. Leave a comment if you see errors or improvements. 

> **Hugo Note:** Tested up to/with [Hugo 0.145 extended](https://github.com/gohugoio/hugo/releases/tag/v0.145.0). So far all new Hugo version worked for me.

## So what changed?
* I finally updated to the latest TailwindCSS 4.0.14
* I removed `concurrently` and just use `hugo server`, does not really makes a difference though
* Removed `autoprefixer` and `postcss`, seems they are no longer required
