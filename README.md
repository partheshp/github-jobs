# GitHub Jobs API Application

This is a simple web application that fetches and displays job listings from the GitHub Jobs API.

## Features

- Fetch and display job listings from GitHub Jobs API
- Filter job listings by location and job type (Full Time)
- Pagination support for browsing through job listings

## Technologies Used

- React.js for the frontend
- Node.js and Express for the backend
- Axios for making HTTP requests
- React Router for client-side routing

## Getting Started

### Prerequisites

- Node.js installed on your machine
- npm (Node package manager)

1. Clone the repository
  ```bash
  git clone https://github.com/partheshp/github_jobs.git
  ```
2. Navigate to the project directory
  ```bash
  cd github_jobs
  ```
3. Install backend dependencies
  ```bash
  cd backend
  npm install
  ```
4. Install frontend dependencies
  ```bash
  cd ../frontend
  npm install
  ```

### Running the application

1. Start the backend server
  ```bash
  cd backend
  npm start
  ```
2. Start the frontend development server
```bash
cd ../frontend
npm start
```
3. Open your browser and navigate to `http://localhost:3000`.

### Usage

* Use the search bar to enter job keywords.
* Filter jobs by location and whether the position is full-time.
* Use the pagination controls to navigate through the list of job results.
