# Blog API (Overview)

## Blog API Full Application Overview

This repository serves as a full overview of the Blog API project within "The Odin Project".

This project is a fullstack project divided into two clients (reader and author applications) and a backend API server.

It is the sixth project of the "NodeJS" course within "The Odin Project" and is used to practice the implementation of a RESTful application.

You can find more information about the project [here](https://dantesblog.netlify.app/articles/3).

## Repositories

- Reader Application: https://github.com/Dur4nt3/blog_project_reader

- Author Application: https://github.com/Dur4nt3/blog_project_author

- API Backend: https://github.com/Dur4nt3/blog_project_api

## Websites

- Reader Application: https://dantesblog.netlify.app/

- Author Application: https://dantesblogauthor.netlify.app/

- API Backend: https://dantesblogapi.up.railway.app/

*Note: you can use the API backend to test some queries if you're interested.*

## Usage

As mentioned, this project has 3 parts: reader client, author client and API server.

Within the reader app you can read articles and signup to be able to comment on articles.

within the author app you can signup to write and publish articles.
It should be noted, signing up as an author requires a secret key.
I've done this to moderate what articles are being published.
On the off-chance you're actually interested in writing an article, you can contact me (email in profile) and ask for the key.

*Note: the key is an ENV variable, I can simply rotate it at will to keep it secret and secure.*

Finally, the API server, which is the gateway for the entire application.
The API server handles authentication and authorization, creating, reading, updating and deleting resources.

## Skills Demonstrated

- REST API

- RESTful Application

- API Architecture

- JSON Web Tokens

- CORS

- react-markdown


