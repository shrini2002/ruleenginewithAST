Rule Engine Application
Overview
This application is a rule engine that determines user eligibility based on attributes such as age, department, salary, and experience. It uses an Abstract Syntax Tree (AST) to represent and manage conditional rules, allowing for dynamic rule creation, combination, and evaluation.
Features
Create Rules: Define rules using a string format that gets converted into an AST.
Combine Rules: Combine multiple rules into a single AST for more complex evaluations.
Evaluate Rules: Check if the given data meets the criteria defined by the AST.
Tech Stack
Backend: Node.js, Express.js
Database: MongoDB
Getting Started
Prerequisites
Node.js and npm installed
MongoDB installed and running
Installation
1.Clone the Repository
git clone "https://github.com/shrini2002/ruleenginewithAST.git"
cd rule-engine
2.Install Backend Dependencies
npm install
3.Start MongoDB
Ensure that MongoDB is running on your local machine:
mongod
4.Start the Backend Server
nodemon server.js

