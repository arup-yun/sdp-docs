# docs.sdp.arup.com

This repo holds the source documentation for the SDP platform published at https://docs.sdp.arup.com . This is a statically generated [VuePress](https://vuepress.vuejs.org/) site. 

This site inherits from the https://github.com/arup-group/speckle.arup.com site which also uses Vuepress

## Updating the site

When updating a new file, remember the following:

* H2 headers (`## Header title`) will be pulled into the table of content in the sidebar (H1 and H3 to H6 will not)
* you **must** have a blank link after your headers or they will be ignored
* put any images or other files into the `images/` folder next to the file your editing, and refer to them with `![alt text](./images/your-image-name.png)`

When adding a new file into one of the subfolders, 

* add an entry into the `sidebar.js` file in that folder (unless you don't want the page to show up in the sidebar).
* add a YAML header to the page with at least `title: Your page's title`. This title will appear in the sidebar

Prior to pushing to the github repo:

* check that the site works properly by running `npm run dev` from the repo's root folder. The site will be servered to [](http://localhost:8080/).
* check that the site builds without errors by running `npm run build`.

## Building

To build it, run the command `npm run build`. The static files are generated at `docs/.vuepress/dist`.