# Lesson to refactor CSS to SCSS

## Set up the project

- Download the repo (don't clone).
- Unzip the file and rename the resulting folder `yourname-sass` and the move it into your `/icj` folder.
- Open the folder in VS Code (either through Terminal or **Open Folder** in VS Code).
- Go to github and create a new repo also called `yourname-sass`. DO NOT include the README.
- The resulting directions in Github should be performed in your VS Code terminal, with one exception:
  - Use `git add .` to add all the files instead of just the README.
- Push to Github to make sure they are connected. When you refresh your github repo, you should see all the files.

## npm setup

- run `npm install` in your terminal to set up the development environment.
- run `gulp` to start your development server.

## Structure of the project

The `docs` folder is our publishing folder, where our site lives. Inside of it are our two HTML files, and then folders for our published CSS and our media files.

```
docs
├── css
│   ├── new-styles.css
│   ├── old-styles.css
├── media
│   ├── harvey-dale.jpg
index.html
shows.html
```

> need more notes here.

```
src
  ├──scss
     ├── new-styles.scss
```

## Ways we will refactor

- Create variables for colors
- nest .nav and .main inside .container
- nest children of .nav and .main inside them
- Extrapolate padding-left in .main as a direct child descendant for allfv: `> * {padding-left: 30px;}`

## Make new styles

note them here
