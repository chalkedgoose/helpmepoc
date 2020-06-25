# Help Me POC
Staging app: https://gallant-ride-34b413.netlify.app/

[![gitlocalized ](https://gitlocalize.com/repo/4905/whole_project/badge.svg)](https://gitlocalize.com/repo/4905/whole_project?utm_source=badge)

Welcome to the contribution guide for Help Me POC. There will be a few things needed to setup before you can contribute.
## Setup

1. Get [NodeJs](https://nodejs.org/en/) and install it for your machine (follow the guides for the OS you use)

2. Get [Yarn](https://classic.yarnpkg.com/en/) as VuePress recommends using it.

3. Get [Git](https://git-scm.com/) for your OS, as we're going to use this for version control, and getting the project from Github itself.

4. Get a text editor; I suggest VSCode as it has lot of nice features built in like a Command Line Interface (which we'll be looking at in the next step).

5. Open up a Command Line Interface (or a terminal on Mac/Linux) in any location you want to store the project.If you have VSCode, go to Terminal on the top navigation bar, and click new Terminal to open one up. Inside, you can enter the following command:
``` git clone https://github.com/CSumm/helpmepoc.git```
This will get all the recent changes to the project onto your local machine.

6. Once Node and Yarn are installed, you can enter the following command:
```yarn install```
This will install all the stuff (dependencies) we need to get the project fully working.

7. To run the project in your browser,write ```yarn docs:dev```. What it does it runs a local server on your machine at port 8080. You can click the link in your terminal and it will open automatically!

8. Extra for pros: there's also yarn docs:build to do a production build of the documentation which we'll need to host it. We'll flesh this out once basics are fixed up.

## Modifying and editing
To edit and modify, most of the time you'll be looking under the contribution and resources folder. There's README.md files in both. Once you made some changes to Resources' readme, feel free to put an image link to your profile or personal dev page (you can just put an image alone if you have neither).

For those who are looking into adding languages to the docs, look into [VuePress Internationalization](https://v1.vuepress.vuejs.org/guide/i18n.html#default-theme-i18n-config). This will be a work in progress so we can always bounce ideas off each other.

#### Remember: when making changes, you'll need to push those changes to Github. There's a way to drag and drop files on the browser site or do it via command line or Github Desktop. MAKE SURE to be on or [create a new branch](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging) other than Master.

## Todo
We're hoping to put this live onto a paid domain name, so we would like to get a sponsorship widget or Vue component inside of the Contribution page. If you are up for it, feel free to clone the repo and create a feature branch for it.
