# SQL Learning Journey
This repository contains my SQL practice and learning progress to become a Data Analyst.

## Goals
- Document my journey of learning SQL and other tools to become a Data Analyst.
- Share my learning process in a way that is clear and easy to follow.
- Help others who want to follow in my footsteps.
- Demonstrate the skills I acquire along the way.

## Projects


## Structures 


## SQL-Challenges

### Lesson-01-SELECT
A SELECT statement is a digital search request used to look up and display specific information from a database without changing or deleting anything. Think of it like using search filters on a shopping website to show only the exact items you want to see.


/*
  ## 1. Business Challenge 1 Marketing Campaign
Department: Marketing

### Problem:
Marketing wants to send a promotional email to every customer. The email should start with the customer's first name and will be sent to their email address. 

### My analysis:
Marketing needs the customer's first name to personalize the email and the email address to send the campaign.
*/

### SQL Solution

SELECT first_name, email

FROM customer;


### Expected Result

The query returns the first name and email address of every customer. This information can be used by the Marketing department to send promotional emails.

---

## 2. Business Challenge 2 Customer Service
Department: Service desk

### Problem:
A customer calls customer service. The agent wants to verify the customer's identity before discussing the account. 

### My analysis:
I need the customer data. The “customers” table contains the customers’ IDs, as well as their first and last names.

### SQL Solution

SELECT first_name, last_name, customer_id 

FROM customer; 

### Expected Result

The query returns each customer's first name, last name, and customer ID. This information helps the customer service agent verify the customer's identity before discussing the account.


## Reflection

Today I learned that before writing SQL I should understand what the business really needs. Only then should I choose the table and the columns.


## Topics
- SELECT STATEMENTS
- WHERE
- JOINs
- GROUP BY
- Subqueries
- Etc.

## Tools
- PostgreSQL
- pgAdmin
- GitHub
