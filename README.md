
  
# <div align="center"> Todos Local Storage App

![Screenshot 2023-10-28 105250](https://github.com/anshul-132002/ToDos_LocalStorage/assets/128448038/077a2326-4797-4dbe-baa0-e6b0c33dd632)

## Overview

This React application is a to-do list manager that uses local storage for data persistence. It allows users to add, update, mark as complete, and delete to-do items.

## Features

- Add new to-do items with a title and description.
- Update existing to-do items.
- Mark to-do items as completed or uncompleted.
- Delete to-do items.
- Data is stored in local storage for persistence.

## Usage

1. **Clone the Repository:**

   ```bash
   git clone <repository-url>
   cd todos_localstorage

## Install Dependencies:

Make sure you have Node.js and npm installed. If not, download and install them from nodejs.org.

1. **Install the project dependencies :**
   ```bash
    npm install
   ```

2. **Run the Application:**
   Start the development server:

   ```bash

   npm run dev
   
## Implementation

- Built using React and relies on useState and useEffect hooks for state management.
- New to-do items are stored in local storage with unique IDs generated using Date.now().
- Updates, completions, and deletions of to-do items are reflected in local storage.
- On page load, the app retrieves to-do items from local storage and displays them.


## Author

[Anshul Shrivas] `<https://github.com/anshul-132002>`
