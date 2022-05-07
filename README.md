# Online-Shopping-Back-End
E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. This is a back end for an e-commerce site. It's using Express.js API and MySQL database.

## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Table of Contents 
1. [About the Project](#About-The-Project)
1. [Project Links](#Project-Links)
1. [Deployed App](#Deployed-App)
1. [Installation](#Installation)
1. [Project Team](#Project-Team)
1. [Questions](#Questions)

## About The Project
GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## Project Links
[Repo Link](https://github.com/Kawilder/Online-Shopping-Back-End) <br>
[Video Link](https://drive.google.com/file/d/1bIEijBUCrGDN7bnMvQwbOsT56-Z3ZCOZ/view)

## Instructions
git clone https://github.com/Kawilder/Online-Shopping-Back-End.git <br>
Populate your own .env file <br>
open up the terminal and run these commands. <br>
`npm i` <br>
`mysql -u root -p` <br>
`source db/schema.sql` <br>
`npm run seed` <br>
`npm start`

## Project Team
[Kevin Wilder](https://github.com/Kawilder) <br>

## Questions
<details>
    <summary>Contact</summary>
    kevin_wilde564@yahoo.com
</details>