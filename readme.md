# Virtua Frontend Test
Recruitment test for frontend candidates. Good luck! :)

## Rules
* Fork this repository, so it can stay on Github
* Commit your changes after every task
* When you finish, send us link to your repository and wait for an answer

## Prerequisites
- [Node.js](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/get-npm)


## Installation
Bring up a terminal, then go to your project root directory and install local dependencies:

```npm install```

To start local dev environment, type in the following command in your terminal:

```npm run dev```

You should now see the project page on http://localhost:1234, with a few random images loaded from unsplash.com page :)

## Tasks
The project is based on **PARCEL** builder, which documentation you can read here: https://v2.parceljs.org/

Use **SCSS** to write your styles in /src/styles directory.
Add your **JS** code to /src/js/index.js file.
Use **PUG** (https://pugjs.org/) to create any HTML structure you need.

------------


### Task 1 - Slider
The goal of this task is to find and use best npm slider package to create a slider/carousel animation.

Inside a **slider.pug** file you would find necessary data stored as an array variable **['nature', 'computer', 'people', 'fashion', 'science', 'animals', 'space']**. By using those values create a html structure.

Your slider would display an **image** as a background and **content** where heading is value and content is just text:

***Lorem ipsum dolor sit amet, consectetur adipiscing elit***

Remember to run your slider from index.js file initially.

![Screenshot 1](design/gifs/slider.gif)

------------

### Task 2 - Newsletter

The goal of this task is to create **PUG** structure for newsletter by fallowing designs.

Newsletter should show up after **6000ms timeout** in kind of nice and smooth animation.

Add simple **HTML5** and **JS** validation to your newsletter form you just created. All form inputs should be required. Please notice checkboxes and radio buttons have custom look.

![Screenshot 2](design/gifs/newsletter.gif)

### Task 3 - Requests Mock

By following task you should create an API mocks to simulate saving and checking database records.

We encourage to use **json-server** package but you can install and setup whatever you want. Find out documentation here https://github.com/typicode/json-server

To run Database use:

```npm run db```

The goal is to create ability to save newsletter form data as a database record in txt/json file. Remember, inside database user can not save same email address twice.

Use **XMLHttpRequest** to create a necessary request, also remember to manage a response as messages displayed in top of form.

![Screenshot 2](design/gifs/subscription.gif)

------------

Remember to use **RWD** for a mobile views!

## Send us your repo!
After finishing all tasks, send us link to your repo at [jobs@wearevirtua.com](mailto:jobs@wearevirtua.com).
