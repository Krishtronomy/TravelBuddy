## Description

### Purpose:
TravelBuddy is a Travel app which allows users to find locations of interest and explore what options are available near the location.
A user has the ability to sign in and post about locations they've visited and leave a description and/or review, which other users can then read and comment on.



### Functionality / Features:
- **Authentication:**
The application has the ability to sign up and login as a user, which then allows you to create your own posts and comment on other user's posts. 
- **Authorisation:** 
Users can edit or delete their own posts but not other people's posts. Any logged in user can comment on anyones post.
- **Posts**
Creating a post allows you to add a Title, Description, Image and also leave a rating.
- **Browsing**
The application has a main feed which users can scroll through to see posts in order of date.
- **Filtering**
The main feed can be filtered by created date or rating.
- **Search**
The application has a search functionality for looking up a location of interest which then displays options of places to visit in that location.

### Target Audience:
The target audience is for users who seek to log their travels in one place for their own records and also for other users to read, explore and comment on. It also serves as a means of people getting informed on which places are highly rated to visit.

### Tech Stack:
- React.js
- JavaScript
- HTML & CSS
- Ruby
- Ruby on Rails
- Heroku (Server Deployment)
- Netlify (Front End Deployment)


### Libraries/Packages:
* Material-UI:
  * A comprehensive suite of UI tools which was utilised to render most front-end UI components.

* Axios:
  * A promise based HTTP client for browser/node.js. This was used to obtain and manipulate api data from the traveladvisor API endpoint as well as to create API for rails backend and insert jwt bearer token. 

* Jest:
  * A JavaScript testing framework; focuses on simplicity. This was used to write our front-end tests.

* Framer-Motion:
  * A React-based motion library. This package was used to create a motionwrapper which wrapped around our app components for a smooth, reusable and recurring scroll animation.

* Google-Map-React:
  * A component written over a small set of the Google Maps API. This allows us to render any react component within the Google Map itself. Google-Map-React is fully isomorphic (renders on server and client side). Can render map components even if Google Maps API isn't loaded. Essentially, this library was used to create the map component within our app's explore page. This library is the backbone of one of the major functions of the TravelBuddy app. 

* React:
  * A free, open-sourcce front-end JavaScript library for building UI components. React was used as a major component of TravelBuddy's front-end. 

* React-Blob:
  * Simple react component that 'looks like liquid in space'. This component was used on the TravelBuddy homepage to add flair.

* React-Router-Dom:
  * This library was used for declarative routing within our react web app.

* SASS:
  * A CSS extension language which was used to help with stylings in our app.

* Windups:
  * A unique 'typewriter' like effect library for react. This was used on the TravelBuddy homepage to add another stylistic element for user engagement.


## Dataflow Diagram:
![dataflow diagram](./docs/dataflow%20diagram.png)

## Application Architecture Diagram:
![architecture diagram](./docs/architecture_diagram.png)

## User Stories:
![female face portrait](./docs/persona1.png)

- "As a person who loves travelling and exploring new places to visit, I want an easy to use Application that I can quickly use without first needing to do long tutorials on learning how to operate the application. 
- "As a user, I want to sign up easily without spending too much time, so I can get to posting about places I've visited"
- "As a user, I want to be able to Login/Logout whenever I want"
- "As a user, I want one single account to be able to create posts and comment on other peoples posts, so that I dont have to create multiple accounts or use multiple email addresses."
- "As a user, I want an easy to use application that allows me to log places I have travelled to, so I can keep a record of my travels and for other people to see"
- "As a user, I want to add a Title and Description to my posts, so it is clear what the post is about and I can be as informative about the location as possible"
- "As a user, I want to be able to edit or delete my post, so that I can adjust post details whenever required."
- "As a user, I want to attach pictures to my post, so I can visually display the location and share my experience, to engage other users."
- "As a user, I want to be able to leave a rating on a place I have visited, so it gives others visibilty on how I rated the location at a quick glance. 
- "As a user, I want a easy to click Navigation menu, so that I can easily switch between pages within the application"

![male face portrait](./docs/persona2.png)

- "As a user, I want to be able to search for places that have alot of nature, so that I can explore the outdoors"
- "As a user, I want to be able to search for activities around a location, so that I can plan my itenerary around the location"
- "As a user, I want to be able to add a profile picture, so that I can express my character and let others know I am"
- "As a user, I want the option to search for a place I want to go and find what options are available in that location, so that I can make an informed decision on where to visit"
- "As a user, I want to view posts from other users and be able to comment on them, so that I can see what other people are recommending for places to visit"

### User Stories - Revision and Refinement:
1. Jerome would like the ability to search for types of places using a keyword i.e. nature. We can instead have a drop down filter with pre-selected categories of location types to choose from for filtering locations.
2. Amber would like to create posts and share them with the public to see. We can have an option to make the post 'public' or 'private' upon creation of the post to allow the user to choose.
3. Jerome would like the ability to comment on others posts. We can have an option which allows the Author of the post to either allow or not allow comments, giving the user a choice.
4. Amber would like the ability to add photos to her posts. We can allow for multiple photo uploads and display them in a carousel style which can then be swiped/clicked through.

## Wireframes:
### Login:
![login desktop](./docs/wireframes/login_desktop.png)
![login tablet horizontal](./docs/wireframes/login_tablet_hor.png)
![login tablet vertical](./docs/wireframes/login_tablet_vert.png)
![login mobile](./docs/wireframes/login_mobile.png)
![login user stories](./docs/wireframes/login_user_stories.png)

### Home:
![home desktop](./docs/wireframes/home_desktop.png)
![home tablet horizontal](./docs/wireframes/home_tablet_hor.png)
![home tablet vertical](./docs/wireframes/home_tablet_vert.png)
![home mobile](./docs/wireframes/home_mobile.png)
![home user stories](./docs/wireframes/home_user_stories.png)

### Explore:
![explore desktop](./docs/wireframes/explore_desktop.png)
![explore tablet horizontal](./docs/wireframes/explore_tablet_hor.png)
![explore tablet vertical](./docs/wireframes/explore_tablet_vert.png)
![explore mobile](./docs/wireframes/explore_mobile.png)
![explore user stories](./docs/wireframes/explore_user_stories.png)

### Travels:
![travels desktop](./docs/wireframes/travels_desktop.png)
![travels tablet horizontal](./docs/wireframes/travels_tablet_hor.png)
![travels tablet vertical](./docs/wireframes/travels_tablet_vert.png)
![travels mobile](./docs/wireframes/travels_mobile.png)
![travels user stories](./docs/wireframes/travels_user_stories.png)

### Profile:
![profile desktop](./docs/wireframes/profile_desktop.png)
![profile tablet horizontal](./docs/wireframes/profile_tablet_hor.png)
![profile tablet vertical](./docs/wireframes/profile_tablet_vert.png)
![profile mobile](./docs/wireframes/profile_mobile.png)
![profile user stories](./docs/wireframes/profile_user_stories.png)

## TrelloBoard:
Link to Trello:
https://trello.com/b/MiI00w51/travelbuddy


#### Planning
Initial Brainstorming session discussing ideas, tools, tech stack and workflow using a shared google doc:
![google doc](./docs/brainstorm.png)

Screenshots of Trello throughout the project:
![trello board](./docs/trello1.png)
![trello board](./docs/trello2.png)
![trello board](./docs/trello3.png)
![trello board](./docs/trello4.png)
![trello board](./docs/trello5.png)
![trello board](./docs/trello6.png)
![trello board](./docs/trello7.png)

### Trello Part 2
![trello board](./docs/trello8.png)
![trello board](./docs/trello9.png)
![trello board](./docs/trello10.png)
![trello board](./docs/trello11.png)
![trello board](./docs/trello12.png)

### Website Final Version:
![home page](./docs/website/Home.png)
![explore page](./docs/website/Explore.png)
![travels page](./docs/website/Travels.png)
![profile page](./docs/website/Profile.png)
![login page](./docs/website/Login.png)

### Testing:

#### Development Testing:
![spreadsheet](./docs/dev-testing.png)

#### Production Testing:
![spreadsheet](./docs/prod-testing.png)
