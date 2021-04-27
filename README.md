# EDiT-Everyone-Design-it-Together
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

**EDiT** is a DIY(or do it together!) blogging site where users can add DIY projects they've done or search for a product they'd like to do. There will be categories such as: home decor, clothing, general crafts, DIY for kids. The goal of the site is to have people inspire one another and give each other ideas on repurpsoing items or just giving somone an easy place to look up a fun weekend activity.


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
|      React       | Create frontend |
|   React Router   | To make routed enpoints for each page |
| Rails | Creating backend: databases, models, and controllers |
|     Heroku     | To deploy the backend|
|  Netlify  | To deploy the frontend |

<br>

### Client (Front End)

#### Wireframes

![Dummy Link](url)

- Desktop

![Dummy Link](url)

- Mobile


#### Component Tree

[Component Tree Sample](https://gist.git.generalassemb.ly/davidtwhitlatch/414107e2560ae0bb65e233570f2fe056#file-component-tree-png)

#### Component Architecture
``` structure
src
|__ assets/
      |__ fonts
      |__ graphics
      |__ images
      |__ css/
          |__Home.css
|__ components/
      |__ Home.jsx
|__ services/
      |__ Search.jsx

```

<br>

### Server (Back End)

#### ERD Model

[ERD Sample](https://drive.google.com/file/d/1geOSP9GNf3O9jm58iQ5C96nUUIhHNvy0/view?usp=sharing)
<br>

***

## Post-MVP
- Adding a save ability - users save/favorite projects- this gives them a saved location on their account page where they can veiw saved projects
- An updated Account page: users account pages will not just be for them to update their info but will also be a page they can decorate and other users can come to to learn more about them or follow to keep up with their DIYs (similar to etsy layout).
- A comments section: giving users the ability to comment on projects 
- Allowing users to uplaod photos (not urls)--would require AWS
- Live Videos/ time slots to actually DIY together.
***

