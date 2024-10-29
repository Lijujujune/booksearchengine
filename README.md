# 21 MERN: Book Search Engine

A book search application that allows users to search for books and save favorites. The application uses MongoDB, Apollo Server, and GraphQL, with data retrieved from the Google Books API.

## Table of Contents

	•	Description
	•	Features
	•	Technologies
	•	Installation
	•	Usage
	•	License

## Description

This application allows users to search for books using the Google Books API. Authenticated users can save books to their account to view later. The application includes features like user authentication, a search function, and a book-saving option, all built using a GraphQL API to replace traditional RESTful calls.

## Features

	•	User Authentication: Sign up and log in to save favorite books.
	•	Book Search: Use the Google Books API to search for books.
	•	Book Management: Save and delete books from your saved list.
	•	GraphQL API: Refactored API using Apollo Server and GraphQL to streamline requests and responses.
	•	State Persistence: Save data to MongoDB and manage user sessions with JSON Web Tokens (JWT).

## Technologies

	•	Frontend: React, Apollo Client, React Bootstrap
	•	Backend: Node.js, Express, MongoDB, GraphQL, Apollo Server
	•	Database: MongoDB Atlas
	•	Deployment: Render

 ## Installation

### bash
git clone https://github.com/your-username/book-search-engine.git
cd book-search-engine

### Install dependencies for both client and server:
cd client
npm install
cd ../server
npm install

## Usage

	1.	Search for books using the search bar.
	2.	Sign up or log in to save books to your personal list.
	3.	Save or delete books from your saved list in your profile.

## License

This project is licensed under the MIT License.



