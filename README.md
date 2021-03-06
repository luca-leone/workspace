## Workspace for Modern Javascript Development

A minimal **workspace** designed to develop JavaScript applications with the **Latest ECMAScript** features in order to making them suitables both for **browser** and for **Node.js** environment.

It is based on **[Babel](https://babeljs.io/)** which compiles **Modern JavaScript** to ECMAScript 5 and uses **[GulpJS](https://gulpjs.com/)** to automate and enhance the workflow. **Configuration files** for **compiler**, **code linter**, **bundler** and **IDE settings** are provided. 

It's recommended to use **[Visual Studio Code](https://code.visualstudio.com/download)** for better development experience. Code **linter** is based on **Google's style** recommendations with some little changes that can be found in **.eslintrc** within "rules" object.

One of most relevant features is "**hot reload**": keeping compiler running, a new versions of the files that you edited will be provided within dist at runtime.

This workspace is suitable for everyone are looking for a minimal and ready to use JavaScript development envirnoment. It's is perfect to develop JS libraries but can be also used as starting tool for any particular needs. It can be customized in according to developers needs adding other software as such as Express, broserify or sass compiler.


## Table of contents

- [Download](#download)
- [Requirements](#requirements)
- [Install dependencies](#install-dependencies)
- [Get started](#get-started)
- [What's included](#whats-included)
- [ECMAScript features](#ECMAScript-features)
- [Creator](#creator)
- [Copyright and license](#copyright-and-license)


## Download

- [Download the latest release.](https://github.com/luca-leone/workspace/archive/master.zip)
- Clone the repo: `git clone https://github.com/luca-leone/workspace.git`


## Requirements

- Download and install Node.js. **[Node.js v4+](https://nodejs.org/en/)** is required.
- Use a **package manager** as such as **[npm](https://www.npmjs.com/)**. It is provided together with Node.js . Alternatively **[yarn](https://yarnpkg.com/lang/en/)** is also considered a good choice.


## Install dependencies

* `npm install`


## Get started

- Let's start opening **src** folder and creating new js files. **Index.js** within src is app's **entry point** and must always exist. Every compiled file shows a **commented header** which takes info from **package.json** . Feel free to replace default info with the new ones.

- Start compiler: `npm run build` 


## What's included

Within the download you'll find the following directories and files

```
workspace/
  |-- node_modules/
  |
  |-- src/
  |     └── index.js 
  |
  |-- .babelrc
  |-- .eslintignore
  |-- .eslintrc
  |-- .gitignore
  |-- .jshintrc
  |-- gulpfile.js
  |-- index.js
  |-- jsconfig.json
  |-- package-lock.json
  |-- package.json
  |-- LICENSE
  └── README.md
```


## ECMAScript features

* decorators
* classes
* class properties
* constants
* arrow functions
* block scoped functions
* block scoping
* computed properties
* destructuring
* duplicate keys
* for of
* function name
* literals
* modules umd
* object super
* parameters
* shorthand properties
* spread
* sticky regex
* template literals
* typeof symbol
* unicode regex
* transform regenerator


## Creator

**Luca Leone**

- <https://twitter.com/lucaleone__>
- <https://github.com/luca-leone>


## Copyright and license

Copyright 2018 **Luca Leone**. Code released under the [MIT License](https://github.com/luca-leone/workspace/blob/master/LICENSE).