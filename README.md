# Promptopia app

Promptopia Application

## Description

This is an app allowing user to create, share and browse AI prompts for any AI-powered platform.. The app is built using Next.js, Mongoose ODM, MongoDB and Google OAuth authentication.

## Features
- Browse the list of prompts created by other users
- Search for prompts by tag, description, or author
- Copy the prompt your liked to your clipboard
- Check other user's profile page with their prompts
- Login using Google OAuth
- Create a new prompt with a description and tag
- Check the list of prompts you created on your profile page
- Edit your existing prompt's details

## Technologies
- React
- Next.js framework
- Mongoose ODM database library
- MongoDB database
- OAuth authentication

## Installation
1. Clone the repository to your local machine.
2. Install the dependencies using `npm install`.
3. Set up a MongoDB database.
4. Set up a OAuth client ID and secret.
5. Configure the environment variables in `.env` file with all the necessary configuration variables (check `.env.example`).
6. Run the app using `npm run dev`.

## Endpoints
- `/` - Home page
- `/profile` - Profile page (only available for logged in users)
- `/create-prompt` - Create prompt page (only available for logged in users)
- `/update-prompt?id={prompt._id}` - Update prompt page (only available for logged in users)

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.