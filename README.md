![](https://img.shields.io/badge/Microverse-blueviolet)

# Hello-Rails-Backend

This app uses a Rails back-end as an API to display a random greeting message

Enjoy your Greeting!

## Built With

- Ruby: version 3.02
- Ruby on Rails
- Terminal
- IRB
- Rubocop (linters)
- PostgreSQL

## Milestones

### Rails API
- [x] Milestone 1: Create a new Rails API app called 'hello-rails-back-end'
- [x] Milestone 2: Initialize the project with Git 
- [x] Milestone 3: PostgreSQL database is set up 
- [x] Milestone 4: Create a table for storing messages and create 5 different greetings
- [x] Milestone 5: Create an API endpoint that selects a random greeting from the table
        - Create controller with an action and Rails route 


## Getting Started

To get a local copy up and running follow these simple example steps.


## Pre-requisites
Make sure you have Ruby and Rails installed on your computer. If not, you can follow this [tutorial](https://guides.rubyonrails.org/getting_started.html#creating-a-new-rails-project) to install them.

If you don't have PostgreSQL installed, you can follow this [tutorial](https://www.postgresql.org/download/) to install it.
  
## Usage
In your terminal, navigate to your current directory and run this code

`git clone https://github.com/steveWDamesJr/hello-rails-backend.git`

Then run:

`cd hello-rails-backend`

Open the project in your favorite code editor. `code .` for VS Code.

  - Use the command `bundle install` or just simply `bundle` to install all project dependencies.
  - Run `rails db:create db:migrate` to create the database and run migrations.
  - You might need to supply a username and password for your PostgreSQL database if you run into an error with the previous step.
  - Simply navigate to `config/database.yml` and add your username and password to the `username` and `password` fields.
  
Start terminal

`rails s`

- Then click on `http://127.0.0.1:3000`

Enjoy as your app opens in the web browser 


## Run Linters:

### To run rubocop we use:

`rubocop`

### To autocorrect offenses with rubocop we use:

`rubocop --auto-correct-all` or
`rubocop -A`


## Testing

   Within the projects working directory run test using the following command:
  `bin/rails test test` and the name of the `.rb` directory you want to test, in the terminal.


## Author

👤 **STEVE W DAMES JR**

- GitHub: [@githubhandle](https://github.com/steveWDamesJr)
- Twitter: [@twitterhandle](https://twitter.com/Steve88312331)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/steve-w-dames-jr/)


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/steveWDamesJr/hello-rails-backend/issues).


## Show your support

Give a ⭐️ if you like this project!


## Acknowledgments

- Hat tip to anyone whose code was used


## 📝 License

This project is [MIT](./MIT.md) licensed.
