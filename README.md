# ixati website
Source code for ixati's website

## Directory Structure
Files used for hosting the site are stored in the root of the project directory.

`src` contains all the source files used to build the site

## Getting Started
From the command line, run `npm run serve` to build the site and start a server on localhost. It should open the site in your browser.

Use `npm run dev` to do the same as above, but see your changes live-reloaded.

## NPM Scripts
Run these from the command line
```text
npm run dev             Use when building the site. starts 'watch' and 'server'
npm run serve           Starts a 'live-reload' server for testing the site locally.
                        Will automatically reload any changes.
npm run build           Build all assets in 'src', dumping the output to the project root
npm run build:html      Build HTML from source templates. Uses 'pug' template language
npm run build:css       Use 'catw' to concatenate all stylesheets in 'src/css' into a single CSS file
npm run build:img       Minify images and move them to project root
npm run build:fonts     Move fonts to project root
npm run watch           Watch for file changes in 'src/', build them when a change occurs.
                        Runs 'watch:html' and 'watch:css'
npm run watch:html      Watch 'html' files
npm run watch:css       Watch 'css' files
```

## TODO
- [ ] Add Markdown parser
- [ ] Pass YAML front matter
