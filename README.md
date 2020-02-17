<hr />
<h1 align="center">
  FrontEnd Developer | ReactJS Basic Course
</h1>
<p align="center">
<img src="images\headings\1183672.png"/>

</p>

<h2 align="center">

An Introduction to React

</h2>
<hr />

# Introduction

In this course, we will walk through everything you need to know to develop applications with React. From the beginner through testing and deployment of our first app.
This repository contains the source code and extra content for the course. Course literature is available through ordinary channels.

## Parts in the course

<!-- prettier-ignore -->
| <a href='./part-01'><img src='./part-01/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-01'>What is React?</a><h4> | <a href='./part-02'><img src='./part-02/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-02'>What is JSX?</a><h4> | <a href='./part-03'><img src='./part-03/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-03'>Our First Components</a><h4> | <a href='./part-04'><img src='./part-04/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-04'>Complex Components</a><h4> | <a href='./part-05'><img src='./part-05/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-05'>Data-Driven</a><h4> |
| :---: | :---: | :---: | :---: | :---: |
| <a href='./part-06'><img src='./part-06/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-06'>State</a><h4> | <a href='./part-07'><img src='./part-07/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-07'>Lifecycle Hooks</a><h4> | <a href='./part-08'><img src='./part-08/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-08'>Packaging and PropTypes</a><h4> | <a href='./part-09'><img src='./part-09/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-09'>Styles</a><h4> | <a href='./part-10'><img src='./part-10/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-10'>Interactivity</a><h4> |
| <a href='./part-11'><img src='./part-11/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-11'>Pure Components</a><h4> | <a href='./part-12'><img src='./part-12/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-12'>create-react-app</a><h4> | <a href='./part-13'><img src='./part-13/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-13'>Repeating Elements</a><h4> | <a href='./part-14'><img src='./part-14/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-14'>Fetching Remote Data</a><h4> | <a href='./part-15'><img src='./part-15/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-15'>Introduction to Promises</a><h4> |
| <a href='./part-16'><img src='./part-16/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-16'>Displaying Remote Data</a><h4> | <a href='./part-17'><img src='./part-17/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-17'>Client-side Routing</a><h4> | <a href='./part-18'><img src='./part-18/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-18'>Introduction to Flux</a><h4> | <a href='./part-19'><img src='./part-19/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-19'>Data Management with Redux</a><h4> | <a href='./part-20'><img src='./part-20/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-20'>Redux actions</a><h4> |
| <a href='./part-21'><img src='./part-21/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-21'>Redux Middleware</a><h4> | <a href='./part-22'><img src='./part-22/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-22'>Introduction to Testing</a><h4> | <a href='./part-23'><img src='./part-23/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-23'>Implementing Tests</a><h4> | <a href='./part-24'><img src='./part-24/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-24'>Testing the App</a><h4> | <a href='./part-25'><img src='./part-25/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-25'>Better Testing with Enzyme</a><h4> |
| <a href='./part-26'><img src='./part-26/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-26'>Integration Testing</a><h4> | <a href='./part-27'><img src='./part-27/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-27'>Deployment Introduction</a><h4> | <a href='./part-28'><img src='./part-28/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-28'>Deployment</a><h4> | <a href='./part-29'><img src='./part-29/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-29'>Continuous Integration</a><h4> | <a href='./part-30'><img src='./part-30/cover.jpg' width='140px;' /></a><h4 align='center'><a href='./part-30'>Wrap-up and More Resources</a><h4> |

## 👩‍🏫 How to use this repository

Each part contains a full React application, following the same procedure used to create the course. Most parts can be run using the same basic steps (and for the part that require a bit more work, please attend our live workshops).

The steps to install and run any of the course projects is as follows:

```bash
# install the dependencies
yarn install

# start the project
yarn start
```

or with Node Package Manager

```bash
# install the dependencies
npm install

# start the project
npm start
```

Since all of the days are built using the fantastic [create-react-app](https://github.com/facebookincubator/create-react-app) tool, all of the commands are available from that project in every day.

---

# Fullstack React Book

<a href="https://fullstackreact.com">
<img align="right" src="images/readme/fullstack-react-hero-book.png" alt="Fullstack React Book" width="155" height="250" />
</a>

This ReactJS course was written and developed based on the [Fullstack React](https://fullstackreact.com) book. In the book they cover many more projects similar to ours. The book will walk through each line of code, explain why it's there and how it works.

<div style="clear:both"></div>
