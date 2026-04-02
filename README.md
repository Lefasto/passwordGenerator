# Password Generator

A small vanilla JavaScript app that generates strong random passwords at the click of a button. It is a simple learning project built with HTML, CSS, and JavaScript.

## Features

- Generates two random passwords at once
- Uses upper-case letters, lower-case letters, numbers, and symbols
- Produces 15-character passwords by default
- Runs entirely in the browser with no dependencies

## How It Works

The app keeps a list of allowed characters and builds each password by selecting random entries from that list. When you click **Generate password**, both output fields are cleared and filled with fresh passwords.

## Getting Started

1. Open `index.html` in your browser.
2. Click **Generate password**.
3. Copy one of the generated passwords and use it wherever you need a secure login.

## Project Structure

- `index.html` - page structure and UI
- `index.css` - styling
- `index.js` - password generation logic

## Customize It

You can easily adjust the project to fit your needs:

- Change the password length in `index.js`
- Add or remove characters from the allowed character list
- Update the colors, spacing, or typography in `index.css`

## Notes

This project is intentionally minimal and is meant for learning and experimentation. It is a good starting point if you want to add copy-to-clipboard support, password length controls, or checkbox options for symbols and numbers.
