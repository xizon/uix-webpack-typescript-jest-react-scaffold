# uix-webpack-typescript-jest-react-scaffold
  
[![npm version](https://img.shields.io/npm/v/uix-webpack-typescript-jest-react-scaffold?style=for-the-badge)](https://www.npmjs.com/package/uix-webpack-typescript-jest-react-scaffold)
[![license](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=for-the-badge)](LICENSE)

A scaffold boilerplate including TypeScript, React, Jest and ESLint.



## File Structures


```sh
/
├── README.md
├── LICENSE
├── tsconfig.json
├── babel.config.js
├── package-lock.json
├── package.json
├── dist/
├── src/
├── test/  
├── public/  
│   ├── index.html    
│   └── assets/
├── build/  
│   └── config.js
└──
```

## Installation And Test

You will need to have [node](https://nodejs.org/) setup on your machine. That will output the built distributables to `./dist/*` .


**Step 1.** Use NPM (Locate your current directory of project, and enter the following command.) or download the latest version from [Github](https://github.com/xizon/uix-webpack-typescript-jest-react-scaffold). For nodejs you have to install some dependencies.

```sh
$ sudo npm install uix-webpack-typescript-jest-react-scaffold
```

Or clone the repo to get all source files including build scripts: 

```sh
$ git clone git://github.com/xizon/uix-webpack-typescript-jest-react-scaffold.git
```


**Step 2.** First, using an absolute path into your `"uix-webpack-typescript-jest-react-scaffold/"` folder directory.

```sh
$ cd /{your_directory}/uix-webpack-typescript-jest-react-scaffold
```


**Step 3.** Before doing all dev stuff make sure you have `Node 10+` installed. After that, run the following code in the main directory to install the node module dependencies.

```sh
$ sudo npm install
```


**Step 4.** Commonly used commands:

Debug application. It can be checked separately as TypeScript without compiling and packaging behavior.

```sh
$ npm run check
```


**Step 5.** When you’re ready to deploy to production, create a minified bundle with:

```sh
$ npm run build
```

**Step 6.** When you have done, this will spin up a server that can be accessed at

```sh
http://localhost:8080
```


<blockquote>
<h3>💡 Note:</h3>
 
**If you upgrade the version of Node, please execute the following code:**

```sh
$ sudo npm install
$ sudo npm rebuild node-sass
```
</blockquote>


## Supported development environment

- React 17 +
- TypeScript 4.x.x + 
- Babel 7.x.x + 
- Webpack 5.x.x
- Jest 27.x.x


## Licensing

Licensed under the [MIT](https://opensource.org/licenses/MIT).


