[![Build Status](https://travis-ci.com/sai-github/flexbox-music-app.svg?branch=master)](https://travis-ci.com/sai-github/flexbox-music-app)

# Responsive Design with Flexbox

This repo is excersie for the [online cource on educative](https://www.educative.io/courses/understanding-flexbox-everything-you-need-to-know) by [Ohans Emmanuel](https://twitter.com/OhansEmmanuel)

### Running the application

You can have the app running on your local machine by following below steps (we use node and npm)

- `npm run install` , To download all the dependencies from `npm`
- `npm run serve` , To open the application on default browser

### To know the details on how the app is running

I tried to do the heavy lifting that recent frameworks like angular provide (not everything though)

- I used `node-sass` to convert my `scss` to `css` and then `autoprefixer` to add all the vendor prefixes
- I used `uglifyjs` to uglify `js` code and later moved all the content to `dist` directory, so we can get the build from it.
- I used `onchange` to watch for changes and `live-server` to run it in browser

### What did we do with flexbox

- The point of this exercise is to create the layouts using `flexbox` and explore the possibilities with flexbox
- You can clone and see the commits `initial layout for project` and `makes mobile friendly`. The first one is desktop version and it the later one we make it to mobile friendly

### What it looks like

![Look on different devices](readme-assets/screens.png)

### Reference and about the course

- The course on educative covers all the things you require to get started with flexbox
- It also helps in making you use flexbox in right way. Special thanks to the writer [Ohans Emmanuel](https://twitter.com/OhansEmmanuel)
- It points to different resources to learn more on flexbox (ex: [Solved-by-flexbox project](https://github.com/philipwalton/flexbugs))
- The content of the course is also avilable in a repo [here](https://github.com/ohansemmanuel/Understanding-Flexbox)

### CI with Travis

- We set up travis with configs as in `.travis.yml`.
