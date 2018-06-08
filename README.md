### About

This is a boilerplace that uses:

* [hyperapp](https://github.com/hyperapp/hyperapp)
* [w3-css](https://www.w3schools.com/w3css/default.asp)

Features include:

* hot-reloading dev server
* production build with
    * uglify
    * removal of unused CSS
* auto-formatting

### Why

I like no-nonsense UI libraries that are useful with as little as dropping a script tag in an HTML file. I like 'em even more when they are small. Hyperapp is right up my alley, and I think it's a ton of fun.

I chose w3-css for this because it's feature-packed but not too heavy, simple to use, and looks clean. I want enough in a CSS lib that I can _almost_ get away with just tossing in class names.

Sometimes I want to start hacking right away. After a few too many ~500 LOC html files with bloated script tags, I took inspiration from [minimal-react-webpack-babel-setup](https://github.com/rwieruch/minimal-react-webpack-babel-setup) and made a basic build setup, with a few tweaks for prod builds.

### Usage

* `npx degit jcpst/template-hyperapp-1 my-new-project`
* `cd my-new-project`
* `npm start`

Then hack away! 

Format with: `npm run format`