# Manoa Notes

## Table of contents

* [Overview](#overview)
* [User Guide](#user-guide)
* [Team](#team)

## Overview

The goal of Manoa Notes is to provide students a place where they can meet or discuss with others who previously took a course. Those who have completed a course can also post their notes for other students to see. In addition, they will be able to answer questions on the forum, which will form a community where students can be helped in the future as well. It will eventually incorporate various technologies such as:

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code.
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [React Bootstrap](https://react-bootstrap.github.io/) CSS Framework for UI design.

It will also provide code that implements design concepts including but not limited to the following:

* Two primary collections (Profiles and Courses) as well as two "join" Collections (CoursesTaken and CourseInterests) that implement many-to-many relationships between them.
* Top-level index pages (Profiles and Courses) that show how to manipulate these four collections in various ways.
* Initialization code to define default Profiles and Courses and relations between them.
* Use of Meteor Methods to illustrate how to simplify implementation of multiple collection updates.
* Use of indexes to enforce uniqueness of certain fields in the collections, enabling them to serve as primary keys.
* Authentication using the built-in Meteor accounts package along with Sign Up and Sign In pages.
* Authorization examples: certain pages are public (Profiles and Courses), while other pages require login (AddNote, EditProfile).

## User Guide

This section provides a walkthrough of the planned Manoa Notes user interface and its capabilities. It will be heavily based on the [Bowfolios template](https://bowfolios.github.io) which was provided in the ICS 314 Software Engineering class. Some pages that we will most likely be using include:

### Landing Page

The landing page is presented to users when they visit the top-level URL to the site.

![](https://bowfolios.github.io/images/landing-page.png)

### Index pages (Projects, Profiles, Interests)

Bowfolios provides three public pages that present the contents of the database organized in various ways.

The Profiles page shows all the current defined profiles and their associated Projects and Interests:

![](https://bowfolios.github.io/images/profiles-page.png)

The Projects page shows all the currently defined Projects and their associated Profiles and Interests:

![](https://bowfolios.github.io/images/projects-page.png)

Finally, the Interests page shows all the currently defined Interests, and their associated Profiles and Projects:

![](https://bowfolios.github.io/images/interests-page.png)


### Sign in and sign up

Click on the "Login" button in the upper right corner of the navbar, then select "Sign in" to go to the following page and login. You must have been previously registered with the system to use this option:

![](https://bowfolios.github.io/images/signin-page.png)

Alternatively, you can select "Sign up" to go to the following page and register as a new user:

![](https://bowfolios.github.io/images/signup-page.png)

### Home page

After logging in, you are taken to the home page, which presents a form where you can complete and/or update your personal profile:

![](https://bowfolios.github.io/images/home-page.png)

### Add Project page

Once you are logged in, you can define new projects with the Add Project page:

![](https://bowfolios.github.io/images/add-project-page.png)

## Team
Manoa Notes is designed, implemented, and maintained by [Alex Bozyck](https://abozb01.github.io/), [Marc Ivan Manalac](https://marcivanmanalac.github.io/), [Linda Nguyen](https://lindanguyen25.github.io), [AJ Patalinghog](https://aj-patalinghog.github.io), and [Joshua Aaron Subia](https://josh-subia.github.io/).
