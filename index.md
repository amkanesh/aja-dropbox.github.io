## Table of contents

* [Overview](#overview)
* [Deployment](#deployment)
* [User Guide](#user-guide)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Links](#links)
* [Team](#team)

## Overview

Our platform, Kalo Stems, will allow UH students to connect with career opportunities that are tailored to their interests and skills. Students will be able to specify their background and aspirations, allowing companies to view students who are the best fit for their opportunity. Kalo Stems bridges the gap between academia and industry, allowing students long-term professional success. This application will illustrate various technologies useful to ICS software engineering student, including: 

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://react.dev/) for component-based UI implementation and routing.
* [React](https://react-bootstrap.github.io/) Bootstrap CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

## Deployment
View our website application here: [Kalo Stems](http://146.190.131.126/)

## Activity Badges
[![ci-kalo-stems](https://github.com/kalo-stems/kalo-kode/actions/workflows/ci.yml/badge.svg)](https://github.com/kalo-stems/kalo-kode/actions/workflows/ci.yml)

## User Guide
This section provides a walkthrough of the Kalo Stems user interface and its capabilities.

### Landing Page
The landing page is presented to users when they visit the top-level URL to the site. It provides our motto and some previews of our application.

*We intend to enhance the UI design over the course of our project.*

## Developer Guide
This section provides information of interest to Meteor developers wishing to use this code base as a basis for their own development tasks.

### Installation
First, [Install Meteor](https://docs.meteor.com/install.html).

Second, visit the [Kalo Stems application github page](https://github.com/kalo-stems/kalo-stems.github.io), and click the "Use this template" button to create your own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo. However you do it, download a copy of the repo to your local computer ("clone" the file to your computer!).

Third, cd into the bowfolios/app directory and install libraries with:
```angular2html
$ meteor npm install
```

Fourth, run the system with:
```angular2html
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

### Application Design
Kalo Stems is based upon [meteor-application-template-react](https://ics-software-engineering.github.io/meteor-application-template-react/) and [meteor-example-form-react](https://ics-software-engineering.github.io/meteor-example-form-react/).  Please use the videos and documentation at those sites to better acquaint yourself with the basic application design and form processing in Kalo Stems.

### Data Model
This is our prototype Data Model in which we hope to base our collections off of. This is a design choice that we are currently working in progress.

## Development History 
The development process for Kalo Stems conformed to [Issue Driven Project Management](http://courses.ics.hawaii.edu/ics314f19/modules/project-management/) practices. In a nutshell:

* Development consists of a sequence of Milestones.
* Each Milestone is specified as a set of tasks.
* Each task is described using a GitHub Issue, and is assigned to a single developer to complete.
* Tasks should typically consist of work that can be completed in 2-4 days.
* The work for each task is accomplished with a git branch named "issue-XX", where XX is replaced by the issue number.
* When a task is complete, its corresponding issue is closed and its corresponding git branch is merged into master.
* The state (todo, in progress, complete) of each task for a milestone is managed using a GitHub Project Board.

## Continuous Integration
Kalo Stems uses [Github Actions](https://docs.github.com/en/free-pro-team@latest/actions) to automatically run ESLint and TestCafe each time a commit is made to the default branch.  You can see the results of all recent "workflows" at [https://github.com/kalo-stems/kalo-stems.github.io/actions](https://github.com/kalo-stems/kalo-stems.github.io/actions).

## Links
* [GitHub Organization](https://github.com/kalo-stems)
* [Team Contract](https://docs.google.com/document/d/1pQhVukBdsgP-iYddv36u0Z7tSdybe16vppzxzfB3U6Q/edit?usp=sharing)
* [Slideshow](https://www.canva.com/design/DAGBZoxKtCk/fQQk6ZFbjSCNc1vgeSsEIQ/edit)

## Team
AJA Dropbox Tool is designed and implemented by [Aaron Ancheta](https://aaron-ancheta.github.io/), [Adrienne Kaneshiro](https://amkanesh.github.io/), and [Jaira Pader](https://jairabp.github.io/).
