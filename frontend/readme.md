# Anythink Frontend

The Anythink Frontend is an SPA written with [React](https://reactjs.org/) and [Redux](https://redux.js.org/)

## Getting started

Make sure your server is up and running to serve requests.

## Pages overview

- Home page (URL: /#/ )
  - List of tags
  - List of items pulled from either Feed, Global, or by Tag
  - Pagination for list of items
- Sign in/Sign up pages (URL: /#/login, /#/register )
  - Use JWT (store the token in localStorage)
- Settings page (URL: /#/settings )
- Editor page to create/edit articles (URL: /#/editor, /#/editor/slug )
- Item page (URL: /#/item/slug )
  - Delete item button (only shown to item's author)
  - Render markdown from server client side
  - Comments section at bottom of page
  - Delete comment button (only shown to comment's author)
- Profile page (URL: /#/@username, /#/@username/favorites )
  - Show basic user info
  - List of items populated from seller's items or user favorite items
## Setting up the Enviroment

Download docker from the Officical site and install it in your system

Check the version of docker using `docker -v` in the command prompt

Then use the `docker-compose up` to install the necessary pacakges required for the project

If you are facing any issues kindly check the docker is running or not. It's better to run the compose command after opening the docker

Also, try different methods to start the docker

For the first time, it takes some time to load the necessary requirements to the project

Finally the project compiled and running successfully.
