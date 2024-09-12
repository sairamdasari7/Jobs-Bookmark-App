# Job Bookmarking App

## Live Server:

    - 

## Overview

The Job Bookmarking App is a React-based web application that allows users to browse job listings, bookmark their favorite jobs, and view their bookmarked jobs. The app features a responsive design with professional styling for a clean user experience.

## Features

- **Job Listings**: Fetch and display job listings from an external API.
- **Bookmark Jobs**: Users can bookmark their favorite jobs.
- **View Bookmarks**: View and manage bookmarked jobs.
- **Responsive Design**: The app is responsive and adjusts to various screen sizes.
- **Clear Bookmarks**: Option to clear all bookmarked jobs.

## Technologies Used

- React
- Axios
- CSS
- Local Storage

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/sairamdasari7/Jobs-Bookmark-App.git
2. **Navigate to the project directory**:

    ```bash
    cd job-bookmarking-app

3. **Install the dependencies**:

    ```bash
    npm install

## Usage

1. **Start the development server**:

    ```bash
    npm start

2. **Open your browser and go to** : http://localhost:3000.

3. **Browse Job Listings**:
    - View job details and click "Bookmark" to save jobs to your bookmarks.

4. **Manage Bookmarks**:

    - Switch to the "Bookmarks" tab to view your saved jobs.
    -Click "Clear Bookmarks" to remove all bookmarked jobs.


## File Structure:

    - src/
        - components/
            - Jobs.js: Component for displaying job listings.
            - Bookmark.js: Component for displaying bookmarked jobs.
        - App.js: Main component handling tab switching and bookmark management.
        - App.css: CSS file for styling the application.
        - index.js: Entry point for the React application.

## CSS Styling:

    The CSS is designed to provide a professional and responsive layout. It includes:
        
        - Global Styles: Base styles for body and main content.
        - Responsive Design: Adjustments for extra small, small, medium, and large devices.
        - Button Styles: Professional colors for primary actions and special buttons.

## API:

    The app fetches job listings from the following API endpoint:

        - https://testapi.getlokalapp.com/common/jobs?page=<page>

## License:

    This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements:

    - React Documentation
    - Axios Documentation
    - CSS Tricks for responsive design
