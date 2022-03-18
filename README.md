## Smart Todo Project
Contributors:
[Connor Mullin](https://github.com/CJM1994),
[Sha Faqiri](https://github.com/ShahrukhFaqiri),
[Manuel Zuniga](https://github.com/Nachosonfriday).

=========

Smart Todo is an API-based single-page todo app. It was used to practice our HTML, CSS, JS, jQuery and AJAX front-end skills, and our NodeJS, SQL, and Express back-end skills.

It uses 4 different API's to search and categorize user inputs into preset categories on the page. The user is able to login or register, edit their name, and move items between categories. It stores the user's entries in to a database that can be retrieved afterwards.

APIs used include:\
Google Places API\
The Movie Database API\
SerpApi - Google Search API\
Google Books API\

## Getting Started

1. Create the `.env` by using `.env.example` as a reference: `cp .env.example .env`
2. Update the .env file with your correct local information 
  - username: `labber` 
  - password: `labber` 
  - database: `midterm`
3. Install dependencies: `npm i`
4. Fix to binaries for sass: `npm rebuild node-sass`
5. Reset database: `npm run db:reset`
  - Check the db folder to see what gets created and seeded in the SDB
7. Run the server: `npm run local`
  - Note: nodemon is used, so you should not have to restart your server
8. Visit `http://localhost:3000/`

## Dependencies

- node
- jquery
- body-parser 
- cookie-session
- ejs
- express
- pg
- request
- request-promise-native

## Finished Product

Add and check off items!
!["Adding and checking off items"](https://github.com/ShahrukhFaqiri/Smart_ToDo_App/blob/master/docs/adding%E2%81%84checking.gif)

Use Dropdown Menus to change catagories
!["Drop down image"](https://github.com/ShahrukhFaqiri/Smart_ToDo_App/blob/master/docs/dropdown.png)

Log in and out or register a new user. All user data and todo data is persistent and stored in a SQL database
!["Login and logout"](https://github.com/ShahrukhFaqiri/Smart_ToDo_App/blob/master/docs/login%E2%81%84logout.gif)

=======
1. [Create](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) a new repository using this repository as a template.
2. Clone your repository onto your local device.
3. Install dependencies using the `npm install` command.
3. Start the web server using the `npm run local` command. The app will be served at <http://localhost:3000/>.
4. Go to <http://localhost:3000/> in your browser.
