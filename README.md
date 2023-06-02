# Phase-3-Active-Record-Code-Challenge-Product-Review

# Overview
This assignment requires one to create a Ruby application that models an e-commerce domain with three models: User, Review, and Product. I used Active Record to create migrations for your database schema and Active Record associations to model the relationships between your models. I have three models: User, Review and Product.

# Entity Relationship Diagram
For this code challenge, a Product has many Users, a User has many Products, and a Review belongs to a User and to a Product. Product-User is a many-to-many relationship.

https://staruml.io/
# Topics Tested
This code challenge focused on testing the following topics:

ActiveRecord Migration
ActiveRecord Associations
Class and Instance Methods
ActiveRecord Querying
Project Setup
Clone the repository using git clone https://github.com/beatricemwenje/Phase-3-Active-Record-Code-Challenge-Product-Review
Run bundle install to install the required dependencies.
Run rake db:create to create the database.
Run rake db:migrate to migrate the database schema.
Console
To run the console, run rake console in the terminal. This will open the console and allow you to interact with the database.

# Deliverables
Create the required classes and their respective methods.
Set up your application so it runs from the configured run file.
Create instances of the classes on the run file and try out the methods you just created.
Use the notation # for instance methods, and .(dot) for class methods.
Feel free to build out any helper methods if needed.
Migrations
Before working on the rest of the deliverables, create migrations for the users, products and reviews tables. Use seeds.rb file to create instances for all models.




