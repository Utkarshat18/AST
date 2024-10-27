# React + Vite + FastAPI

This project is a simple web application using React with Vite for the frontend and FastAPI for the backend. It includes a form that evaluates certain rules based on user input and triggers alerts accordingly.

## Project Structure

- **Frontend**: Built with React and Vite.
- **Backend**: Built with FastAPI.

## Features

- **Form Component**: Collects user data including name, email, age, department, salary, and experience.
- **Rule Evaluation**: Evaluates predefined rules based on the form inputs and triggers alerts if conditions are met.
- **FastAPI Endpoints**: Provides endpoints for creating, combining, and evaluating rules.

## Getting Started

### Prerequisites

- Node.js and npm
- Python 3.7+
- FastAPI and Uvicorn

### Installation

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install frontend dependencies**:

   ```bash
   cd frontend
   npm install
   ```

3. **Install backend dependencies**:

   ```bash
   cd backend
   pip install -r requirements.txt
   ```

### Running the Application

1. **Start the frontend**:

   ```bash
   cd frontend
   npm run dev
   ```

2. **Start the backend**:

   ```bash
   cd backend
   uvicorn app:app --reload
   ```

### Usage

- Open your browser and navigate to `http://localhost:3000` to access the frontend.
- The form allows you to input data and will alert you if any rules are triggered based on your input.

### Code Overview

- **Form Component**: Handles user input and rule evaluation.
  - Code Reference: `src/Form.jsx` (startLine: 1, endLine: 105)

- **App Component**: Main entry point for the React application.
  - Code Reference: `src/App.jsx`
