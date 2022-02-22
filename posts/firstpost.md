---
title: Installing open-wc on MacOS.
description: This is a post on My Blog about agile frameworks.
date: 2022-02-22
tags:
  - opensource
  - npm
  - node
layout: layouts/post.njk
---

In order to install open-wc we need to install some software, namely NodeJS/npm, and yarn.  We will start with NodeJS. First, navigate to https://nodejs.org/en/ and install the LTS version, at the time of writing that is 14.17.5.  Once the installer finishes downloading, open it and follow the prompts.  If npm is already installed on your machine preform the `npm install -g npm@latest` to install the latest version of NPM

Upon completion of installing Node, open Terminal and type in the following commands: `node -v` and `npm -v` to verify that your installation was successful.  

To install yarn, open terminal type the following command: `curl -o- -L https://yarnpkg.com/install.sh | bash `.  Upon the completion of the command preform the following command to verify installation: `yarn -v`.

With our dependencies installed, let’s create a test project called “hello-world”.  Let’s change directories such as Documents.  Open termainal and type `cd Documents`.  Type ‘pwd’ to verify the output is `/Users/<Your User Name>/Documents`.  Then type `npm init @open-wc` and select the following options: Scaffold a new project, Web Component, enable Linting, Testing, and Demoing, do NOT use typescript, name it hello-world, select yes to write files to your hard drive, and Yes with Yarn.

To verify the project worked, type the following commands `cd hello-world` and then `npm start`.  If your web browser opens, then your job is done.  To stop the project, return to terminal and hit ‘control’ + ‘c’