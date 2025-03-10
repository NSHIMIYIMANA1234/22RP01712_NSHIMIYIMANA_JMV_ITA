API Development Assignment - README

Introduction

This assignment involves developing APIs to manage various data entities such as student information, products, and categories for an online store using PHP and Laravel frameworks. Below is a structured outline of the activities and steps required to implement the necessary functionalities.

Activity 1: Student Information Representation (XML and JSON)

Create XML and JSON Structures for Student Information

Develop XML and JSON representations of a student containing the following details:

Name

Age

Gender

List of Subjects (Each subject includes: Subject Name and Grade)

XQuery Expressions

Write XQuery expressions to perform the following tasks:

Retrieve the student's name and age.

Retrieve the names of subjects the student is enrolled in.

Activity 2: Simple API for Managing Products (PHP)

API Functionality

Develop an API with the following endpoints for managing products:

GET /products: Retrieve all products.

GET /products/{id}: Retrieve a specific product by ID.

POST /products: Add a new product.

PUT /products/{id}: Update an existing product by ID.

DELETE /products/{id}: Remove a product by ID.

Product Data Model

Each product should include the following attributes:

ID

Name

Description

Price

The product data will be stored in an array within PHP, and the API should return responses in JSON format.

Activity 3: Online Store Category Management API (Laravel)

Database Setup

Set up a MySQL database named online_store.

Create a categories table with the following columns:

id

name

lft

rgt

created_at

updated_at

Nested Set Model

Implement the Nested Set Model using Laravel’s Eloquent ORM to manage hierarchical categories.

API Routes

Develop the following API routes for category management:

GET /categories: Retrieve all categories in XML format.

GET /categories/{id}: Retrieve a specific category by ID in XML format.

POST /categories: Create a new category (accepts XML with name and parent_id fields).

PUT /categories/{id}: Update an existing category (accepts XML with name).

DELETE /categories/{id}: Delete a category and return a success message in XML format.

Error Handling & Validation

Implement proper error responses in XML format for invalid requests.

Utilize Laravel routing, controllers, and models for API logic.

Unit Testing

Write unit tests to verify the functionality of each API endpoint.

Activity 4: Develop APIs for Your Project - Laravel Bank System

Overview

This banking system, built with Laravel, enables essential banking operations such as account creation, deposits, and withdrawals.

Requirements

Ensure the following are installed:

PHP (version 8.0 or higher)

Composer

MySQL (or an alternative database system)

Laravel (version 9 or higher)

Node.js and NPM (for frontend asset management)
