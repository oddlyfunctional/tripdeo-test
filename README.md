# Goal

You must build a dogs Pinterest clone. You can use whatever gems or libraries you prefer, and whatever version of Rails or Ruby you're more comfortable with.

In this application, users can post dogs and add dogs to their wishlists. The app should contain these views:

- A list with all dogs (each card whould contain the dog's name and picture and the author's avatar, with a link to his profile);
- A user's profile with his wishlist;
- A page for posting a new dog.

## User stories

- As a unauthenticated user I can sign up providing my email, password, name and avatar;
- As a unauthenticated user I can sign in;
- As an authenticated user I can add a dog to my wishlist only once;
- As an authenticated user I can access any user's page and check his wishlist;
- As an authenticated user I can post a new dog (name and picture required) and it is automatically added to my wishlist.

You don't need to implement a whole CRUD application (you can ignore updating and deleting).

## Requirements

- Validations must be enforced both in the front-end and the back-end;
- The front-end should be JavaScript-rendered, preferably with React;
- All database readings and updates must be done through an API, using the Fetch API.

## Nice to have

- Use front-end routing and make it work on browser refreshes;
- Demonstrate that you're familiar with modern JS;
- Demonstrate that you can write automated tests both in the back-end and the front-end (no need to TDD everything);
- Authenticate the user via JWT (no cookies!);
- Add some CSS animations (your call! It can be on hovers, on page transitions, whatever you prefer);
- Use frequent commits;
- Make it reasonably pretty (you can use Bootstrap or whatever CSS foundation you prefer);
- Deploy your application on Heroku!


***Good luck!***
