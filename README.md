# GPT3 Web Site

## Introduction

> This web site was made with react to build a web site to show the features of GTP3 AI

## Technologies used
<p align="left">
 <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/>
<img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> 

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> 
<img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" alt="typescript" width="40" height="40"/> 
 </p>

## What I learned with this project?
- Best practise to organize my project
- To have a archive to import all of components and export it. An example of this
  ```javascript
    import blog01 from '../../assets/blog01.png';
    import blog02 from '../../assets/blog02.png';

    export {
        blog01,
        blog02,
    };

    // or export directly

    export { default as Blog } from './blog/Blog';
    export { default as Features } from './features/Features';
 
  ```
- Tricks to create a component easily with a VSCode extension named [React Extension Pack](https://marketplace.visualstudio.com/items?itemName=jawandarajbir.react-vscode-extension-pack)
  - To create a component easily, run this command in the archive .jsx
    ```
    rafce + tab
    ```
    <img src="src/assets/command-rafce.gif" alt="typescript"/>
## Presentation of the application

- This is a image that show the full site
<img src="src/assets/full-page.png">

## How to run?

- Clone this repository
- Run this command on the terminal to install all of dependencies
  ```
  npm i
  ``` 
- Then, run this command
    ```javascript
    npm run start
    ```
