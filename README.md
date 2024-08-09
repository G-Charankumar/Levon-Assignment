# Responsive Dashboard Application

## Overview
This project is a fully responsive dashboard application developed using ReactJS. The dashboard is designed to provide a seamless user experience across desktop, tablet, and mobile devices. It features dynamic data visualization, interactive components, and a user-friendly interface.

## Features
- **Responsive Design:** Optimized for various screen sizes, including desktops, tablets, and mobile devices.
- **Web Dashboard:**
  - **Header:** Navigation links, user profile, and notification icons.
  - **Sidebar:** Links to different dashboard pages (Overview, Analytics, Settings).
  - **Main Content Area:** Grid of interactive widgets displaying various metrics and charts.
  - **Footer:** Brief information about the application.
- **Mobile Dashboard:**
  - **Collapsible Sidebar:** Hidden by default, accessible via a hamburger menu.
  - **Optimized Main Content:** Vertical scrolling with stacked widgets.
- **Interactive Widgets:**
  - Line chart showing user activity over time.
  - Bar chart displaying sales data.
  - Pie chart depicting user demographics.
  - Recent activity feed.
- **Data Integration:**
  - Fetches data from a mock API and dynamically populates the widgets.
  - Real-time data updates and error handling.
- **State Management:** Utilizes Redux for global state management.
- **Form Handling:** Settings page with forms for updating user preferences, including validation.
- **Dark Mode:** Toggle feature for switching between light and dark themes.
- **Performance Optimization:** Lazy loading, code splitting, and other optimization techniques.

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/G-Charankumar/Levon-Assignment.git
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Run the application:**
    ```bash
    npm start
    ```

4. **Build the application:**
    ```bash
    npm run build
    ```

## Usage
- **Desktop:** The dashboard will display with a full layout including the header, sidebar, main content, and footer.
- **Mobile:** The sidebar will be collapsible, and the main content will be optimized for vertical scrolling.
- **Dark Mode:** Use the toggle switch in the header to switch between light and dark themes.
