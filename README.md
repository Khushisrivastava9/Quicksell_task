# Kanban Board App

## Overview
I’ve just completed building an **interactive Kanban board** application using **React JS**. The app fetches data from the provided API and allows users to group tickets by **Status**, **User**, or **Priority**. It also includes sorting options by **Priority** and **Title**, making it easy to organize and view tasks.

The UI is fully responsive and closely matches the provided design, with a clean layout and intuitive card-based structure. I’ve made sure the user’s view preferences are saved even after a page reload. I also stuck to the requirement of using **pure CSS** for styling, avoiding external libraries like Bootstrap or Tailwind to ensure full control over the design.

In terms of functionality, the application seamlessly handles the dynamic grouping and sorting of tickets, ensuring a smooth and interactive user experience.
## Features

- **Data Interaction:**

  - Fetches ticket data from the Quicksell API.
  - Displays the fetched data on a Kanban board.

- **Grouping Options:**

  - Group tickets by Status, User, or Priority.

- **Sorting Options:**

  - Sort tickets by Priority or Title.

- **Priority Levels:**

  - Tickets are categorized with priority levels ranging from Urgent (4) to No Priority (0).

- **Styling:**

  - Visually appealing and responsive design.
  - Pure CSS is used for styling.

- **Icons:**

  - Icons are integrated for various elements of the application using react-icon.

- **State Persistence:**
  - Saves the user's view state (grouping and sorting options) even after a page reload using local storage.

## Setup

1. **Clone the Repository:**

   ```bash
   cd https://github.com/Khushisrivastava9/Quicksell_task
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd kanban-board-app
   ```

3. **Install Dependencies:**

   ```bash
   npm install
   ```

4. **Run the Application:**

   ```bash
   npm start
   ```

5. **Access the Application:**
   Open your browser and go to `http://localhost:3000`.
