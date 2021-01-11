# SPMDB
Story Pitch Management Database

## Project Description

Ever wanted to play Battleship with your friends, but wished the game had more of a Cthulu-esque flavor? Well, welcome to BattleSquids! This is an evolution of Battleship where ships are squids that "ink" opposing squids.Player which will ink the opposing squids first, will win the game.

## Technologies Used

* AWS RDS DB, with a PostgreSQL Engine
* Hibernate backend, with JDBC connection to db
* Javalin application for routing to controller methods
* HTML, CSS and JS frontend

## Testing

* JUnit
* Selenium

## Features

List of features ready:
* Register account.
* Login and logout of account.
* Create pitch as an author.
* Approve or reject pitch as an editor.
* Create draft as an author.
* Approve or reject draft as an editor.

## Getting Started
   
git clone https://github.com/theVTOQ/SPMDB

### Backend:
Use Maven update to build the project
Run Tomcat 9 Server set to use localhost:8080

### Frontend:
Navigate to http://localhost:4200 on web browser

## Usage
* As an end-user, register for an account if not registered; login if registered.
* As an author, create an invite
* As an editor, approve or reject an invite
* As an author, create a draft
* As an editor, approve or reject an invite

## Contributors

Jason Zelonka (Repo owner), Do Yeun Kim, Muhammad Aown, and Shaker Funkhouser
