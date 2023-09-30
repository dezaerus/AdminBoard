# Admin Dashboard Full Stack App

Welcome to the Admin Dashboard Full Stack App! This application provides a comprehensive admin interface with powerful features for managing and visualizing data. Below, you'll find information on the technologies used for both the frontend and backend.

## Frontend

### Technologies Used
- **@emotion/react**: A popular library for styling React components.
- **@emotion/styled**: Styled components for @emotion/react.
- **@mui/icons-material**: Material-UI icons for enhancing the user interface.
- **@mui/material**: Material-UI components for a consistent and responsive design.
- **@mui/x-data-grid**: A powerful data grid component for displaying and manipulating data.
- **@nivo/bar**: Nivo bar chart component for visualizing data in a bar chart.
- **@nivo/core**: Core library for Nivo chart components.
- **@nivo/geo**: Nivo geo chart component for displaying geographical data.
- **@nivo/line**: Nivo line chart component for visualizing trends over time.
- **@nivo/pie**: Nivo pie chart component for displaying data in a pie chart.
- **@reduxjs/toolkit**: A toolset for efficient Redux development.

### Sample Screenshots

#### Dark Mode
![Dashboard](https://raw.githubusercontent.com/dezaerus/AdminBoard/master/1.png)
![Products](https://github.com/dezaerus/AdminBoard/blob/master/Screenshot%20(11).png?raw=true)
#### Light Mode
![Dashboard](https://github.com/dezaerus/AdminBoard/blob/master/Screenshot%20(22).png?raw=true)

#### Mobile Screenshot
![Mobile Dashboard](https://github.com/dezaerus/AdminBoard/blob/master/Screenshot%20(20).png?raw=true)
![Mobile Data Grid](https://github.com/dezaerus/AdminBoard/blob/master/Screenshot%20(19).png?raw=true)


## Backend

### Technologies Used
- **body-parser**: Middleware to parse incoming request bodies in Express.
- **cors**: Middleware for enabling Cross-Origin Resource Sharing in Express.
- **country-iso-2-to-3**: Library for converting country codes from ISO-2 to ISO-3.
- **dotenv**: Loads environment variables from a .env file.
- **express**: A fast, unopinionated, minimalist web framework for Node.js.
- **helmet**: Middleware to secure Express apps by setting various HTTP headers.
- **mongoose**: MongoDB object modeling tool for Node.js.
- **morgan**: HTTP request logger middleware for Express.
  
# Getting Started Guide

Let's simplify the process and get everything set up in one go:

## 1. Clone the Repository
- git clone [repository_url]

## 2. Set up the Frontend
- cd client npm install

- Create a .env.local file in the client directory.

- add REACT_APP_BASE_URL=[React_base_url] to .env then start react app.

## 3. Set up the Backend
- cd …/server npm install

- Create a .env file in the server directory

- Add PORT=[port_number] MONGO_URL=[mongo_db_url] to .env then run index.js with node
