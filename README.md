# INTRODUCTION
- Trello is a simple web application in which a user can maintain its to do tasks.
- The website consists of simple board and the board consists of different cards.
- The cards are fully customizable as the user can edit the title, description, date of the card and even add different labels of different colors to the task.
- Cards can be dragged and dropped from one board to another and it can also be deleted.

# ARCHITECTURE
- As we know that components are the building blocks of any react app; so there are mainly five components in my web application.
- Those five components are :- Board, Card, Dropdown, Editable, Modal.
- Board is the component which will be stored in an array and this array will be rendered from main app.js file.
- Card is the components which is used to render the task lists and its fully customizable.
- Dropdown is a simple component which renders the delete div for card and board.
- Editable component is used to add new cards in the board.
- Modal component is used to edit a single card in terms of title, description and many more.

Deployed Website [Live Demo](https://assignment-zuddl.vercel.app/).

![Screenshot](https://github.com/kumaradityaraj/assignment-zuddl)

![Screenshot] (https://github.com/kumaradityaraj/assignment-zuddl)

# Changes In API
- There are four main operations in any API and that is known as CRUD which is CREATE, READ, UPDATE, DELETE.
- We will send an update request in the database to rename the board name. The request may be PUT, PATCH, etc.
- For users to comment on task we can give a unique id to every card and a description column; the user can add description anytime.
