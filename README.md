# Hello world


## Description

> This is a simple app that display random greetings. It was built with React and Rails

## Getting Started

To get a local copy for this project and running follow these simple example steps.

### Prerequisites

- You need to have git installed in your machine.
- Install a recent version of Postgres.
- Already install Rails
- Already insatll React


## Setup

### Creating the hello-rails-react

- use PostgreSQL database 

```bash
$   rails new rails-react-tutorial --webpack=react -d=postgresql

$   cd rails-react-tutorial # Move into the application directory
```

- Now run these commands to install everything.

```bash
$   bundle install
$   rails webpacker:install
$   rails new rails-react-tutorial --webpack=react -d=postgresql
$   rails webpacker:install:react
$   rails generate react:install
$   yarn install
```

### Clone this repository

```bash
$ https://github.com/fobadara/hello-rails-react.git
$ cd hello-rails-react
```

### Create the database

```bash
$   rails db:create   # or
$   rake db:create
```

### Install linter and 

- Rubocop gem

```bash
$  bundle init
$  bundle install
```
- Stylelint package

```bash
$  npm init -y
$  npm install
$  npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x

```

- Run linter

```bash
$  rubocop .
$  npx stylelint "**/*.{css,scss}" 
```

- In auto-correct mode, RuboCop will try to automatically fix offenses:

```bash
$  rubocop -A # or
$  rubocop --auto-correct-all
$  npx stylelint "**/*.{css,scss}" --fix 
```


### Starting up the Web Server

- We can now run:

```bash
$   rails s # or
$   rails server -p3000 # to visit http://localhost/
```
- To see React-Router working:

```bash
$  ./bin/webpack-dev-server # enables auto-webpacking
```

- To restart the server

```bash
$  sudo service postgresql restart 
```

#### Listing Existing Routes

- You can now visit `http://localhost:3000` to view your new website!



#### Generate controllers

```bash
  $  rails generate controller static index  
  $  rails generate controller api/messages index                 
```

#### Generate a new React component

```bash
  $  rails generate react:component Greeting greeting:string 
  $  rails generate react:component App
```

#### NPM


- Redux Thunk

```bash
  $  Redux Thunk                  
```

- Logger for Redux

```bash
  $  npm i redux-logger                
```

- React Redux Loading Bar

```bash
  $  npm i react-redux-loading-bar            
```


#### Generate Schema

- To push the Migration into the database

```bash
  $   rails db:migrate
```
- We use the seeds.rb file to records in the database
- To drop, create a table and to migrate and send the seed into the database:

```bash
  $   rails db:drop db:create db:migrate db:seed  
```

- To check available routes

```bash
  $   rails routes  
```

## Built With

This project was built with:

-  ![Ruby](https://img.shields.io/badge/-Ruby-000000?style=flat&logo=ruby&logoColor=red)
-  ![Ruby on Rails](https://img.shields.io/badge/-Ruby_on_Rails-000000?style=flat&logo=ruby-on-rails&logoColor=blue)
- ![React](https://img.shields.io/badge/-React-000000?style=flat&logo=react)

## Authors

👤 **Abdulfatai Badara**

- GitHub: [github.com/fobadara](github.com/fobadara)

- Twitter: fob90s@twitter.com


## 🤝 Contributor


Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/fobadara/hello-rails-react/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Credit to [Gregoire Vella on Behance](https://www.behance.net/gregoirevella), the author of the original [design guidelines](https://www.behance.net/gallery/19759151/Snapscan-iOs-design-and-branding?tracking_source=)


## 📝 License

This project is [MIT](./MIT.md) licensed.
