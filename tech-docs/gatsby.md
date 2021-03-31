# Working with Gatsby on a Mac

The instructions below are based on the instructions from the Gatsby site. This is just a parsed down version.
- [https://www.gatsbyjs.com/docs/tutorial/part-zero/](https://www.gatsbyjs.com/docs/tutorial/part-zero/)

## Prereqs
- Install Node.js
- Set default Node.js version (.e.g) `nvm use 15`
- Install Git

## Using the Gatsby CLI
**Install the Gatsby CLI via npm**
- Check if you have the Gatsby CLI already installed by running `gatsby --version`
- If not installed, run `npm install -g gatsby-cli`
- For help, run `gatsby --help`

## Creating a Gatsby Site
1. Open your terminal and navigate to the folder where you want to create a new gatsby project.
2. Run the following: `gatsby new hello-world https://github.com/gatsbyjs/gatsby-starter-hello-world`<br />*Note: In this example, "hello-world" is the project name, but you can name it anything you want.
3. Change into the directory you just created. `cd hello-world`

To create a new Gatsby site based on any existing Gatsby starter, use the following
`gatsby new [SITE_DIRECTORY_NAME] [URL_OF_STARTER_GITHUB_REPO]`

## View the site locally
1. Start the development mode: `gastby develop`
2. Open a new tab in your browser and navigate to `http://localhost:8000/`.

## WHAT'S IN THE CODE

Back to the Hello World project, inside `/src/pages` is an `index.js` file.

The code this file creates a component that makes up the "Hello World" home page.

**Make changes to the home page**
Change the text and save the file. You sould see the page update immediately in the browser (if you still have the site running).
*Note: Gatsby uses **hot reloading**.


