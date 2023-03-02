# core-code-from-scratch-14-02

## ---Node.JS Core Understanding---

Q/A:

## 
1. What is Node.JS?

// Node.js takes what JS does on websites to use it in new enviorments,
out of browsers and websites, to create new apps and programs.

   1.1 What is NPM?

// Basically, NPM it's library that contains packages to employed in the
apps to boost the developement and effiency of the program

## 
2. What problem does Node.JS solve (Is there any problem that can be solved with Node.JS 🤔)?

// Node.js solves a mainly problem related with JS. JS is not able to process more than 1
subprocess at the same time. What Node.js does, is that it takes those subprocesses shortering
timeloadswaiting to get back previous requestes have been made because Node.js do not waste
time nor resources making returning the requestes.


## 
3. What is the V8 Javascript Engine?

// Chrome V8 or just V8 it's a javascript motor. Nowadays V8 it's able to run JS code in and
out of the browsers making possible the "scripting" by the servers

## 
4. Is Node.JS really necessary in the Development ecosystem?


// It0s not completely necessary, but it's a great choise because it offers the the potential
for a quick development; it offers a competitive web structure.

   4.1 Why not use PHP or Golang?


// Basically because of the benefits it offers, like:
Language Sharing Across the Stack
Rapid Development
The Node Package Manager
Single-Threaded Event Loop Architecture 


## 
5. What is the difference between Node.JS and any other browser?

// The difference is that Node.js workls independent of the motor browsers. In other words
Node.js does not need any browser to work properly.

   5.1 Are Node.JS and a browser the same?


// It's not the same but compile all js language the same. Both work with the V8 but Node.js
it's not the same of a browser.


## 
6. What is NVM and Why is it useful for Node.JS developers?


// It's the acronym of Node Version Manager (NVM) and, as the name implies, this is a tool
for the developes. NVM allows the developer manage the Node version on our devices.


---
## ---Node.JS Module System---

Q/A:
##
1. What is a Javascript Module?

// An script it's a module. Simple as that. JS Modules exist and works in order to provide 
a sequences of information that will simplify the work during the debugging of the code.

##
2. Why are Javascript Modules necessary?


// At the beggining of JS it wasn't necessary because the interactions of the web pages
was not so demanding or not so complex. Nowadays, modules are necessary because it stores 
repetitive proccess which can be reused at any time is needed.

##
3. What module standards are available in Node.JS?

// CommonJS is the module standard available in Node.js

##
4. What are the differences between ESModules and CommonJS modules?


// The main differences are the use of both. ESModules started working exclusively in web 
projects, now CommonJS it's the module that Node.js includes as default and the way to access
to each one are onje of the mainly differences. CommonJS needs the npm to load from a repository

##
5. Which types of modules exist in Node.JS?

// 1. Core Modules
   2. Local Modules
   3. Third Party Modules

---
## ---Node.JS practice---

* [Practice](https://github.com/corecodeio/devguide-fundamentals-2022-04/blob/main/src/technologies/2022/week12/exercises/e00/HELLO_WORLD.md)

Q/A:
##
Why do we run the npm init command and not node init to create a new Node.JS project?


// Because the command node init doesn not exist. npm it's te correct command to create a
Node.js project

##
When you entered the npm init command and answered the questions you saw in the terminal, a new file called packacke.json was generated.

What does this file do?

// This asve the basic configuration of the project. It also contains the questions have been
made during the creation

##
Why is this file generated?

// It was generated because it's part of the initialization of the main project 

---
## ---Knowledge Base---
- [Node.JS Learn](https://nodejs.dev/learn)
- [What exactly is Node.JS](https://www.freecodecamp.org/news/what-exactly-is-node-js-ae36e97449f5/)
- [What is Node.js? The JavaScript runtime explained](https://www.infoworld.com/article/3210589/what-is-nodejs-javascript-runtime-explained.html#:~:text=is%20not%20easy.-,Node.,I%2FO%20requests%20to%20return.)
- [What is Chrome V8?](https://www.cloudflare.com/learning/serverless/glossary/what-is-chrome-v8/#:~:text=Chrome%20V8%20is%20a%20JavaScript,makes%20server%2Dside%20scripting%20possible.)
- [MDN Modules](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Modules)
- [Modules Introduction](https://javascript.info/modules-intro)
- [What is a Javascript Module?](https://www.freecodecamp.org/news/javascript-modules-explained-with-examples)
- [Node.JS CommonJS Modules](https://nodejs.org/api/modules.html)
- [Node.JS Module Types](https://www.tutorialsteacher.com/nodejs/nodejs-modules)
