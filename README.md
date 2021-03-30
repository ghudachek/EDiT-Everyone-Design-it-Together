# EDiT-Everyone-Design-it-Together
# PROJECT 4 README <!-- omit in toc -->
- [Overview](#overview)
- [MVP](#mvp)
  - [Goals](#goals)
  - [Libraries and Dependencies](#libraries-and-dependencies)
  - [Client (Front End)](#client-front-end)
    - [Wireframes](#wireframes)
    - [Component Tree](#component-tree)
    - [Component Architecture](#component-architecture)
    - [Time Estimates](#time-estimates)
  - [Server (Back End)](#server-back-end)
    - [ERD Model](#erd-model)
- [Post-MVP](#post-mvp)
- [Code Showcase](#code-showcase)
- [Code Issues & Resolutions](#code-issues--resolutions)

<br>

## Overview

**EDiT** is a DIY(or do it together!) blogging site where users can add DIY projects they've done or search for a product they'd like to do. There will be categories such as: home decor, clothing, general crafts, DIY for kids. The goal of the site is to have people inspire one another and give each other ideas on repurpsoing items or just giving somone ane easy place to look up a fun weekend activity.


<br>

## MVP

The **EDiT** MVP is to have a full CRUD functioning for users on posts(the DIY projects), a landing page, login/create account page,account page, and a home page where veiwers can see the projects. 

<br>

### Goals

- Landing page- similar to home page- the first impression of the site
- Login/create accounts- users C in CRUD
- Account page- for editing and or seeing your projects posted
- Home page- all project posts R in CRUD
- Edit project page- a user can change/update/destroy their projects UD of CRUD

<br>

### Libraries and Dependencies

|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|      React       | Front end |
|   React Router   | to make routed enpoints for each page |
| Rails | creating backend-databases, models, and controllers |
|     Heroku     | for deploying the backend|
|  Netlifiy  | to deploy the frontend |

<br>

### Client (Front End)

#### Wireframes

> Use the Wireframes section to display desktop, tablet and mobile views. No hand-drawn wireframes. Use a tool like wireframe.cc, Whimsical or AdobeXD

![Dummy Link](url)

- Desktop Landing

![Dummy Link](url)

- Desktop Hero

![Dummy Link](url)

- Resource Index

![Dummy Link](url)

- Resource Show

![Dummy Link](url)

- Tablet Resource Index

![Dummy Link](url)

- Mobile Resource Index

#### Component Tree

> Use this section to display the structure of how your React components are being rendered. This should show the parent to child relation between you components. In other words, show which components are rendering the other components. Include a link to your component tree

[Component Tree Sample](https://gist.git.generalassemb.ly/davidtwhitlatch/414107e2560ae0bb65e233570f2fe056#file-component-tree-png)

#### Component Architecture

> Use this section to define your React components and the data architecture of your app. This should be a reflection of how you expect your directory/file tree to look like. 

``` structure

src
|__ assets/
      |__ fonts
      |__ graphics
      |__ images
      |__ mockups
|__ components/
      |__ Header.jsx
|__ services/

```

#### Time Estimates

> Use this section to estimate the time necessary to build out each of the components you've described above.

| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Add Contact Form    |    L     |     3 hrs      |     2 hrs     |    3 hrs    |
| Create CRUD Actions |    H     |     3 hrs      |     1 hrs     |     TBD     |
| TOTAL               |          |     6 hrs      |     3 hrs     |     TBD     |


<br>

### Server (Back End)

#### ERD Model

> Use this section to display an image of a computer generated ERD model. You can use draw.io, Lucidchart or another ERD tool.

[ERD Sample](https://drive.google.com/file/d/1kLyQTZqfcA4jjKWQexfEkG2UspyclK8Q/view)
<br>

***

## Post-MVP
- Adding a save ability - users save/favorite projects- this gives them a saved location on their account page where they can veiw saved projects
- An updated Account page: users account pages will not just be for them to update their info but will also be a page they can decorate and other users can come to to learn more about them or follow to keep up with their DIYs (similar to etsy layout).
- A comments section: giving users the ability to comment on projects 
- Live Videos/ time slots to actually DIY together.
***

## Code Showcase

## Code Issues & Resolutions
