# Frontend Web Application (Mod7-A7a)

## Overview
This is a frontend web application that connects to a backend API. It allows users to view data, add new records, and update existing records. The project is built using HTML and JavaScript and communicates with a REST API hosted on Render.

## Table of Contents
- Installation
- Usage
- API Integration
- Contributing
- License

## Installation & Setup
### Prerequisites:
- Web browser (Chrome, Firefox, etc.)
- Git

### Steps:
- git clone https://github.com/Dylan1207/Mod7-A7a.git
- cd Mod7-A7a
- Open index.html in your browser.

## Usage Instructions
View Data - Displays all records from the database
Add Data - Add a new record (shows confirmation modal)
Edit Data - Select a record from dropdown and update it

## API Integration
The frontend connects to the backend API using fetch:
fetch("https://mod6-a6.onrender.com/api/v1/items")

### Endpoints used:
GET - retrieve data
POST - add data
PUT - update data

## Contributing
- Fork the repository
- Create a new branch
- Make changes
- Submit a pull request

## License
This project is licensed under the MIT License.