# Contact List App
The Contact List App is a simple web application that allows users to manage their contact list. It was built using Sinatra, React, and a PostgreSQL database.

## Features
Users can view a list of their contacts
Users can add new contacts
Users can edit existing contacts
Users can delete contacts

## Technologies Used
- Sinatra - A web framework for Ruby
- React - A JavaScript library for building user interfaces
- PostgreSQL - A powerful open source relational database system
  Setup

## Endpoints
- get all addresses
get http://localhost:4253/addresses
- get address by id
get http://localhost:4253/addresses/:id
- add address
post http://localhost:4253/addresses
- edit address
patch http://localhost:4253/addresses/:id

- get categories
get http://localhost:4253/categories
- add category
post http://localhost:4253/categories
- edit category
patch http://localhost:4253/categories/:id
- delete category
delete http://localhost:4253/categories/:id

- get contacts
get http://localhost:4253/contacts
- add contact
post http://localhost:4253/contacts
- edit contact
patch http://localhost:4253/contacts/:id
- delete contact
delete http://localhost:4253/contacts/:id



#### To run the Contact List App on your local machine, follow these steps:

- Clone this repository to your local machine.
- Run bundle install to install the required Ruby gems.

 #### Run the following command to set up the database:

  - rake db:migrate
  - Run npm install to install the required React packages.
  - Start the Sinatra server by running ruby app.rb.
  - In a separate terminal window, start the React development server by running npm start.
  - Open your web browser and navigate to http://localhost:3000 to view the Contact List App.
## Usage
 - To use the Contact List App, follow these steps:

- View your list of contacts by clicking on the "Contacts" link in the navigation bar.
- To add a new contact, click on the "Add Contact" button and fill in the required fields.
- To edit an existing contact, click on the "Edit" button next to the contact you want to edit and make your changes in the form that appears.
- To delete a contact, click on the "Delete" button next to the contact you want to delete.

