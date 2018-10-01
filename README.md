# **NODE + EXPRESS SERVER**

> WORK IN PROGRESS

---

## **What this boilerplate contains**

<img src="./__repo_readme_assets__/logo-node.png" height="55" alt="logo placeholder">&nbsp;&nbsp;
<img src="./__repo_readme_assets__/logo-express.png" height="55" alt="logo placeholder">&nbsp;&nbsp;

- [x] Node 10.9.0
- [x] Express 4.16.3

---

## **Set up project**

Before cloning the repo **be sure** to install:

- [Node](http://nodejs.org/download/) (version >= 9.10.x)
- [Yarn](https://yarnpkg.com/en/docs/install) (version >= 1.9.x)
- [Npm](https://www.npmjs.com/) (version >= 6.3.x)

Then:

- Choose a folder for your project and move into it `cd [folder path]`
- Clone the repo into your project's folder `git clone [repository url]`

---

## **Installation**

To install the project and all dependencies, run:

```bash
# install dependencies
npm install
```

or

```bash
# install dependencies
yarn
```

in the directory of your project.

---

## **Starting the project**

##### run the server

```bash
npm start
# or
yarn start
```

---

# **Editor setup**

Recommended to setup [eslint](https://eslint.org/) in your editor and turn on `autoFixOnSave`.
Please make sure the husky pre-commit hook is running before you submit a pull request or you can manually run it with `yarn lint`.

#### Eslint

To check the Javascript / React [.js / .jsx] syntax I use [Eslint](http://eslint.org/). The rules to detect errors are written in a `.eslintrc` file included in the root directory of the project (best practice is to use `airbnb linter`).

#### Prettier

This is a opinionated formatter that was widely adopted by the Javascript community rather quickly, there is no need to nitpick over syntax in PR's since [prettier](https://prettier.io) decides the format of your code.



---

## **Todo**

- [x] Run basic server
- [x] Simple auth
- [ ] Store auth session
- [ ] Store server log
- [ ] Refactory with best practices and performance
- [ ] Create simple auth api

---

### **Troubleshootings**

This is just a personal project created for study / demonstration purpose only, it may or may not be a good fit for your project(s).

---

> GitHub [@ibbatta](https://github.com/ibbatta) &nbsp;&middot;&nbsp;
> Twitter [@battago](https://twitter.com/battago)
