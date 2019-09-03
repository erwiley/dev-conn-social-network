# Developer Connector <EW>

A full stack application built on React, Redux, Express, Node, MongoDB(mlab). Visit the finished website https://devconnsoc.herokuapp.com/

## About

Developer Connector is a social platform for Software Developers to showcase their skills. Users can create profiles that will display development skills, educational and work experience, display recent GitHub repositories, create/like/unlike posts, and add comments to posts. The app also has extensive validation and error reporting.

## Functionality

**1. Authenticate**

Users can Sign up or Login by clicking buttons on the navbar or on the landing page. Only users that have signed in can view the public Post Feed and use his/her own Dashboard. When Signing up, if users want a profile image, they can use a Gravatar email.

**2. Developers profiles**

Users can view all the developer profiles with no need to login by clicking the _Developers_ button on the navbar. If they are interested in someone's profile, they can clcik *View Profile* button on some profile to view the detailed information.

**3. Dashboard**

After Login, users can create/edit the Profile, add/delete experiences and add/delete educations on the Dashboard.

**4. Personal Profile**

After Login, new users can create their own Profile including a handle, status, company, website, social networks and etc. If users want to show their latest Github repos, they can fill in their GIthub username in the corresponding input field, then the app will automatically retrieve 5 latest repos and listed in the personal profile page. Users can edit their profile later. The profile will be listed in the public profiles page and can be viewed by all users.

**5. Add Experience**

After Login, users can add experience by clicking _Add Experience_ button on the dashboard.

**6. Add Education**

After Login, users can add education by clicking _Add Education_ button on the dashboard.

**7. Post Feed**

After Login, users can click *Post Feed* button on the navbar to view all the posts submitted by other developers. Users can create/delete their own posts,  like/unlike other developers' posts and also comment on posts.

## Back End

- Backend API built with Node.js & Express
- Routes/endpoints protected with JWT (JSON Web Tokens)
- MongoDB database using Mongoose and mLab.com

## Front End
- Single Page Application created with React Framework
- Using Redux for app state management
- CSS styling with Bootstrap 4

## Web Hosting
- Deployed to Heroku.com 
