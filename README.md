# Overview
It is a REST API built with Ruby on Rails 6 and PostgreSQL as a database. It allows you to store restaurants instances and their reviews.

# Authentication and Authorization
I used 'simple_token_authentication' to create simple tokens assigned to users and 'pundit' for authorization, in order to allow them to identify themselves when trying to create a new restaurant or review, update an existing one or delete one that belongs to them.

# Responses
Any HTTP request will come back as a json, either data or error messages. For that, I used 'jbuilder' to make json files easy to code.
