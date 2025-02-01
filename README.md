# Sass template for ICJ lesson

This repo is a template used in the [Intro to Coding for Journalists book](https://utdata.github.io/icj-class/) chapter on Sass.

It is possible run this code in Github Codespaces or run locally if you have Node.js installed.

## Using through Github Codespaces

1. Go to the [icj-sass-template](https://github.com/utdata/icj-sass-template) repo.
2. Use the Template to create your own version of the repo.
3. Under **<> Code** menu choose codespaces and create one.
4. Once the virtual machine is set up, it needs to go through an additional step to install all the npm packages.
5. After that is done, install gulp:

    ```bash
    npm install -g gulp
    ```

6. Run `gulp dev` to run Sass and start the development server.

For further directions, see the Sass lessons in the [ICJ class](https://utdata.github.io/icj-class/) book.

## Project setup with degit

If you instead want to use this template on your local machine, You need to have Node.js installed and be familiar with how to use it. You'll want to have two npm packages installed globally:

```bash
npm install -g gulp degit
```

An easy way to download and use a repo as a template is [degit](https://www.npmjs.com/package/degit), which ICJ students should have installed when they set up Node. It downloads the contents of a repo but without the `.git` folder.

1. Create your local project folder.
2. In a terminal from inside that folder, run `degit utdata/icj-sass-template`.
3. Run `npm install` to install dependences.
4. Run `gulp dev` to run Sass and start the development server.

You'll need to initiate your own local and Github repos to save your work.

For further directions, see the Sass lessons in the [ICJ class](https://utdata.github.io/icj-class/) book.
