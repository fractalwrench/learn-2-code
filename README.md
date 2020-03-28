# Learn to Code
This contains a step-by-step guide for learning to code web applications in JavaScript, with an emphasis on [Version Control](https://www.atlassian.com/git/tutorials/what-is-version-control) and [ReactJS](https://reactjs.org/).

# Contents
See [Cheatsheets](CHEATSHEETS.md) for a brief reminder of the key concepts.

## Prerequisites
The following should be installed on your computer/setup:

- A [GitHub](https://github.com/) account, used for version control
- [VSCode](https://code.visualstudio.com/), used for editing text files

## Using the command line
See the cheatsheet [here](CHEATSHEETS.md#using-the-command-line).

The command line allows a user to enter text commands which are used during software development.

There are a lot of commands to master, but for now it's only important to learn how to navigate directories. You can learn this prerequisite knowledge by running through the [following tutorial](https://www.codecademy.com/learn/learn-the-command-line/modules/learn-the-command-line-navigation
).

## Version Control with Git
See the cheatsheet [here](CHEATSHEETS.md#version-control-with-git).

You should start with the following [Codecademy tutorial](https://www.codecademy.com/learn/learn-git), which explains the fundamentals of Git.

After you've completed this tutorial you're nearly ready to get stuck into learning JavaScript. We'll continue to use Git during this process so that all your work can be peer-reviewed.

You should test out GitHub's interface by following [their tutorial](https://guides.github.com/activities/hello-world/).

## JavaScript Fundamentals

See the cheatsheet [here](CHEATSHEETS.md#javascript-fundamentals).

Setup an empty git repository on GitHub called `your-name-javascript`.

Start the [following tutorial](https://www.codecademy.com/learn/introduction-to-javascript). For each section, you should:

1. Create a new JavaScript file in the git repository. For example, the first two concepts would have these two files:

    `your-name-javascript/introduction/console.js`
    `your-name-javascript/introduction/comments.js`

2. Write the completed exercise in the file, and make sure to add [comments](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Lexical_grammar#Comments) explaining what the functionality is, how it works, and any of your own supplementary notes. For example, the entry for `console.js` may look something like the following:

    ```js
    // this logs an arbitrary string message to the browser's console.
    console.log("Hello World");
    ```

3. Checkout a new branch using git, add the file, and commit it.

    ```sh
    git checkout master
    git pull # pulls any merged changes which don't exist yet
    git checkout -b introduction-console # create new branch
    git add introduction/console.js
    git commit -m "introduction: the console and how it works"
    git push -u origin introduction-console # pushes branch to Github
    ```

4. Create a pull request on Github from the new branch to `master`, and request a reviewer to approve the changeset.

5. If the reviewer approves the changeset, merge the changes into master. Otherwise alter the changeset as necessary and re-request review.

## ReactJS
See the cheatsheet [here](CHEATSHEETS.md#react-js).

## Computer science and algorithms
