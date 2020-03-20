# book_review_app

HarvardX (edX.org): Web Programming with Python and JavaScript

Alice Huang, August 2019

## Book Review Website

This is a book review website based on a database of 5000 books. The website
enables users to create an account so they can utilize its features, which
include searching for books using different keywords, browsing reviews, and
writing their own reviews. The site also uses the Goodreads API to access
broader rating data on the books. 

## Tools
  * Flask
  * Python
  * HTML/CSS
  * Bootstrap
  
## Demo
  [Video Demo](https://www.youtube.com/watch?v=0OGOoCEY1hc&feature=youtu.be)

## Files

import.py - python code to import the books csv into the database
templates/----.html - all the pages of the website
  * index.html - entry point to the website
  * register.html - lets users create an account
  * login.html - login page
  * hello.html - page user sees after creating an account
  * hello2.html - page user sees after logging in
  * layout.html - template for all html pages
  * match.html - shows all matches for a keyword search of the books
  * search.html - search by isbn #, title, or author
  * details.html - shows specific info for a book
  * error.html - custom error page linked to by a few other pages
  * review.html - place for user to enter ratings/reviews for books
  * submit.html - page user sees after submitting a review
static/styles.css - main custom styles on top of Bootstrap styles



