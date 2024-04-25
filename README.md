# Loan Calculator Web Application

This is a web application developed using Angular that allows users to calculate loan payments with simple interest. It provides an intuitive user interface for inputting loan details and displays the calculated results along with a graphical representation.

## Features

- Simulate loans for different loan types (Car, Home, Personal).
- Input loan amount, interest rate, and loan term.
- Display the calculated loan details, including the total amount to be paid and the interest to be paid.
- Visualize the loan details using a bar graph.
- Responsive design for various screen sizes.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js: Make sure you have Node.js installed on your system.
- Angular CLI: You need the Angular CLI to run and build the project. You can install it using npm.

## Installation

1. Navigate to the project directory:

   ```bash
   cd loan-calculator-app
   ```

2. Install the project dependencies:

   ```bash
   npm install
   ```

## Usage

1. Start the JSON server to simulate a backend:

   ```bash
   npm run start-json-server
   ```
2. Start the development server:

   ```bash
   ng serve
   ```

3. Open your web browser and visit [http://localhost:4200/](http://localhost:4200/) to access the loan calculator application.

4. Use the application to input loan details, select a loan type, and click the "Simulator" button to calculate the loan payments.

## Development

The application's source code is organized into components, services, and styles. Here is an overview of the project structure:

- **Components**: The application has the following components:
  - `app-home`: Represents the home page.
  - `app-loan-calculator`: Contains the loan calculation form and results.
  - `app-navbar`: The navigation bar component.
  - `app-footer`: The footer component.
  - `app-graph-bar`: A reusable component for displaying bar graphs.

- **Services**: The `LoanCalculatorService` handles loan simulations and communicates with the backend API (not included in this project).

- **Styles**: The application uses SCSS for styling, and styles are organized in separate component-specific CSS/SCSS files.

- **Models**: The `Graph` model defines the structure of data for the bar graph.
