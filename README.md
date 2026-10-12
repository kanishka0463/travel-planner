# Travel Planner

A collaborative React application for exploring destinations and planning trips.

## Overview

Travel Planner is a frontend web application developed using React.js to make travel planning easier and more organized. It allows users to explore travel destinations, view destination details, create trips, organize day-wise itineraries, estimate travel expenses, and access saved trips through a simple user interface.

This mini-project was developed collaboratively to gain practical experience with React.js, component-based development, state management, dynamic lists, forms, calculations, and routing.

## Features

- **Home:** Provides an introduction to the application and its main features.
- **Explore Destinations:** Browse available travel destinations.
- **Destination Cards:** Display destination information in a card-based layout.
- **Destination Details:** View information about individual destinations.
- **Search and Filter:** Find destinations using the available search and filtering options.
- **Plan a Trip:** Create trips and organize travel plans.
- **Day-wise Itinerary:** Arrange places and activities by day.
- **Budget Calculator:** Estimate travel expenses across different categories and calculate the total estimated budget.
- **Saved Trips:** Access saved travel plans.

## Technologies Used

- **React.js:** Builds the user interface using reusable components.
- **JavaScript:** Implements application logic and interactive functionality.
- **HTML:** Structures the application content.
- **CSS:** Styles the pages and components.
- **React Router:** Enables navigation between application pages.
- **Vite:** Provides the development server and build tools.
- **Git and GitHub:** Support version control and collaborative development.

## Application Navigation

The application includes the following pages:

| Page | Description |
|---|---|
| Home | Main landing page |
| Explore | Browse available destinations |
| Plan a Trip | Create and organize trips |
| Saved Trips | View saved travel plans |
| Budget Calculator | Estimate and summarize travel expenses |

## Budget Calculator

The Budget Calculator helps users estimate their trip expenses by organizing costs into five categories:

1. Accommodation
2. Food
3. Transportation
4. Activities
5. Other expenses

Users can enter the estimated amount for each category, and the application calculates the total estimated budget automatically.

The `BudgetSummary.jsx` component uses React's `useState` Hook to manage expense values. Event handling updates the relevant category when an input changes, and JavaScript's `reduce()` method calculates the total of all expense amounts. The final amount is formatted in Indian Rupees (INR).

## React Concepts Demonstrated

This project provides practical experience with the following concepts:

- **Components:** Dividing the application into reusable UI elements.
- **JSX:** Writing HTML-like syntax within JavaScript.
- **State Management:** Managing and updating changing data using React Hooks.
- **Event Handling:** Responding to user interactions.
- **Controlled Inputs:** Keeping form input values synchronized with React state.
- **Dynamic Lists:** Rendering destination cards, expense fields, and other lists dynamically.
- **Array Methods:** Using methods such as `map()`, `reduce()`, and `Object.values()` to process data.
- **Routing:** Navigating between pages using React Router.
- **Component Integration:** Combining individual components into a complete application.

## Getting Started

Follow these steps to run the project locally.

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm
- Git

### Installation

**1. Clone the repository**

```bash
git clone <repository-url>
```

Replace `<repository-url>` with your GitHub repository URL.

**2. Navigate to the project directory**

```bash
cd travel-planner
```

**3. Navigate to the frontend directory, if your project uses this structure**

```bash
cd frontend
```

**4. Install dependencies**

```bash
npm install
```

**5. Start the development server**

```bash
npm run dev
```

**6. Open the application**

Open the local URL displayed in your terminal, usually:

```text
http://localhost:5173
```

## Project Structure

The exact folder structure may vary depending on the implementation. A typical structure for this project is:

```text
travel-planner/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar.jsx
│   │   │   └── BudgetSummary.jsx
│   │   ├── pages/
│   │   │   └── SavedTrips.jsx
│   │   ├── App.jsx
│   │   ├── App.css
│   │   └── main.jsx
│   ├── index.html
│   ├── package.json
│   └── vite.config.js
└── README.md
```

This is an illustrative structure. Update it to match the actual files and folders in your repository.

## Live Demo

Explore the deployed application:

[Travel Planner](https://travel-planner-eta-one.vercel.app/)

## Team Collaboration

This project was developed as a group mini-project. Team members collaborated on different application components and features, integrating their work into a single React application.

Git and GitHub were used for source-code management and collaboration.

## Learning Outcomes

Through this project, we gained practical experience in:

- Developing a frontend application using React.js.
- Building reusable components and organizing project files.
- Managing user input and application state.
- Implementing dynamic lists and interactive forms.
- Performing calculations using JavaScript.
- Navigating between pages using React Router.
- Collaborating through Git and GitHub.
- Integrating individual contributions into a shared application.

## Future Enhancements

Potential improvements include:

- Integrating a travel destination API for updated destination information.
- Adding user authentication and individual accounts.
- Implementing persistent storage for trips and budgets.
- Adding maps and location-based recommendations.
- Providing more detailed budget comparisons and expense visualizations.
- Improving mobile responsiveness and accessibility.

## Conclusion

Travel Planner demonstrates how React.js can be used to build an interactive travel planning application. It combines destination exploration, trip organization, itinerary planning, saved trips, and budget estimation in one interface while providing practical experience with modern frontend development and collaborative software engineering.

## License

This project was developed for academic and learning purposes. Add a license file if you intend to distribute the project under a specific open-source license.
