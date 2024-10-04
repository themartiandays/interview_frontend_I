
# React Calendar Widget

## Overview
Your task is to create a **calendar widget** using **React**. This calendar should allow users to **navigate between months and years**, providing basic functionality similar to the calendar widgets used in date-picking scenarios. You are expected to build the calendar from scratch, without using third-party calendar libraries.

## Requirements
- **Basic Structure**: 
  - The calendar should display days for a given month.
  - The week should start from **Sunday**.
  - Days should be organized in rows, representing weeks.

- **Functionalities**:
  - **Change Month**: Users should be able to move to the **previous** or **next month** using buttons (e.g., "Previous" and "Next").
  - **Change Year**: Users should be able to move to the **previous** or **next year**.
  - **Current Date Highlighting**: The current day should be visually highlighted if it is in the displayed month.

- **Optional Features (Bonus)**:
  - Allow selecting a specific date, with a visual indicator for the selected date.
  - Indicate weekends (e.g., Saturdays and Sundays) with a distinct style.
  - Implement a dropdown to quickly navigate to a specific year.

## Technical Requirements
- Use **React** to build this calendar widget.
- **Do not use third-party libraries** for creating the calendar (e.g., `react-calendar`, `moment.js`, etc.). However, you may use small utility libraries for date manipulation if needed (e.g., `date-fns`).
- The application should be written in **JavaScript** or **TypeScript**.
- **CSS** (or any CSS-in-JS solution) should be used to style the calendar.

## Getting Started
1. **Folder Structure**: 
   - You can set up the project using `create-react-app` or any other boilerplate you prefer.
   - Ensure to organize components logically.

2. **Basic Components**:
   - Create components that might include:
     - **Calendar**: Main component that holds the overall logic.
     - **Header**: Shows current month and year and provides buttons for navigation.
     - **DaysGrid**: Displays all days of the month.
     - **DayCell**: Represents each day, which can be clickable to select a date.

3. **Navigation Logic**:
   - Implement logic to manage the state for the **current month** and **year**.
   - Use **React hooks** to manage state (`useState` for state management, `useEffect` if side effects are needed).
   - Handle month/year changes with functions that update the relevant state variables.

## Example Walkthrough
1. **Month Navigation**: 
   - Add buttons to go to the previous and next month.
   - Update the calendar display based on the selected month.

2. **Year Navigation**: 
   - Add buttons to go to the previous and next year.
   - Update the displayed days based on the selected year.

3. **Date Highlighting**:
   - Highlight the **current date** in a unique color or style if it’s within the displayed month.
   - Implement **different styles** for weekends.

## User Interface Expectations
- The **header** should display the current **month and year**.
- Include **buttons** for navigating between months and years.
- Days should be arranged in a **7-column grid** format, representing weeks.

## Optional Features (Bonus)
- Adding a **date selection** feature where clicking a day highlights it as the selected date.
- Implementing **animations or transitions** when changing months/years.
- Providing a **dropdown menu** to jump to a specific year quickly.

## Evaluation Criteria
- **Code Structure**: How well is the code organized? Are components reusable?
- **Functionality**: Does the calendar correctly navigate between months and years?
- **State Management**: Proper use of **React hooks** to manage the state.
- **Styling**: Is the calendar visually appealing and easy to understand?
- **Code Quality**: Is the code clean, easy to follow, and properly commented?
- **User Experience**: How intuitive and responsive is the calendar?

## How to Submit
- Push your code to a GitHub repository and share the link.
- Alternatively, you can use a tool like **CodeSandbox** to create and share a live version of the calendar.

## Notes
- This task is designed to evaluate your **understanding of React** concepts, such as components, hooks, and state management.
- We are also interested in seeing your **approach to problem-solving**, especially how you handle date manipulation and navigation.
- Aim for clean, modular code that is easy to read and extend.

Good luck, and have fun building your calendar widget!

