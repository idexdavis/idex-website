# The Website Page for iDEX!

This project is a static website for iDEX student organization at UC Davis. It demonstrates the purpose of iDEX by utilizing the gorgeous design system powered by [argon design system](https://github.com/creativetimofficial/argon-design-system).



## Introduction

Currently, this website is hosted on `Microsoft Azure`. Considering the nature of static website and budget, this website is stored in a blob storage and delivered by Azure Version Premium CDN.



## To-Do

- [ ] Create simple 404 page.
- [ ] Direct naked domain (root domain) correctly.
- [ ] Create a `Activity` page.
- [x] Add social media icon and link to all pages.



## Deploy

`VS Code` is recommended, but not required. If you are using `VS Code`, you can just open up `idexwebsite.code-workspace` to edit files.

### Prerequisite

* Clone this project down.

  ``` 
  https://github.com/idexdavis/idex-website.git
  ```

* Install `npm` which come with `Node.js` via the link below

  ```
  https://www.npmjs.com/get-npm
  ```



### Setup

If you just clone this project down, you need to use `npm` to install all components required by `argon design system`. **This step is not required any more once you have all components installed.** 

* Firstly, `cd` to the root directory of this project stored in your local machine.

* Then, execute the command below to install the required components

  ```bash
  npm install
  ```
  *For MacOS users: You may want to execute the command below in terminal to install npm globally.* 
  ```bash
  sudo npm install gulp -g
  ```

  **Note: Please be patient during the installation of required components. `npm` may throw some vulnerability warnings during installation, please ignore that. Do not run suggested fix action without thorough consideration.**



### Local Deploy

Once the required components are all installed, you can follow the instructions below to deploy this project locally.

* `cd` to `build` folder. Command below assuming you are in the root directory of this project.

  ```bash
  cd build
  ```

* Run `gulp` to build.

  ``` bash
  gulp
  ```

Waiting for `gulp` to complete its work. You may see the local link and port. The default link of `gulp` for local view is `http://localhost:3000`, it may varies depend on your own settings. You can copy the link to your browser to examine the website. **Chrome is recommended. Sometimes, the `Disable Cache` check box in `Developer Tools` of Chrome is required to be checked to reload certain assets.**



### Develop

All main files are located in the `build` folder. 

`index.html` is the home page. `offer.html` introduces some techniques may used in iDEX events. `team.html` gives out a brief view of our management team members. `assets/img` contains all images used in this project. Please be organized when adding new images.



## Contributions

*Contributions from anyone are all appreciated!*

* Fork this project first.
* Create your own branch in the forked project.
* Commit your changes to the forked project.
* Make a `Pull Request` to the `develop` branch and wait for review from **Technical Team Executives**.

**Note: All technical team staff may not have the access of directly pushing changes to `master` branch of this project. You may need to follow the fork process listed above. One of two technical team executives need to review the pull request, checking the existence of certain serious problems. Once one of executives approve for the merge to `develop` branch, both two executives need to recheck the content and modifications, in order to merge the `develop` branch to `master` branch and publish it.**



## Documentations

In order to develop for this project, you may need to get familiar with `argon design system`.

[Link for documentations of argon design system](https://demos.creative-tim.com/argon-design-system/docs/getting-started/overview.html)

[Link for online demos of argon design system](https://demos.creative-tim.com/argon-design-system/index.html)
