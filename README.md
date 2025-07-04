# My Week-6
# Contact Book App

A simple web app to manage your contacts. You can add, edit, and delete contacts, including uploading profile images.

## Features

- Add new contacts with avatar images
- Edit and delete existing contacts
- View all contacts in a table

## Installation

1. Clone this repository.
2. Make sure you have a local web server (e.g., VS Code Live Server).
3. Add a `config.js` file with your API settings:
    ```js
    const rootPath = "https://mysite.itvarsity.org/api/ContactBook/";
    const apiKey = "your-api-key";
    ```
4. Open `index.html` in your browser via the local server.

## Usage

- Click "Add Contact" to add a new contact.
- Click a contact to edit or delete.

## API Endpoints

- `controller/get-contacts/` - Get all contacts
- `controller/insert-contact/` - Add a new contact
- `controller/edit-contact/` - Edit a contact
- `controller/delete-contact/` - Delete a contact

## contact

- created by Mmakoma@65
