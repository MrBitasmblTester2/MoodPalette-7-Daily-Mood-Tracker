# MoodPalette-7-Daily-Mood-Tracker

Description
A simple and visually appealing web app that allows users to log their daily moods and view them as a colorful calendar heatmap.

## Tech Stack
- React

## Requirements
- Mood selection interface (Use emoji or color buttons for mood selection)
- Calendar heatmap display (Map moods to colors and show them on a monthly grid)
- Local storage persistence (Save moods locally so data stays after refresh)

## Installation
Clone the repository:
bash
git clone https://github.com/<your-username>/MoodPalette-7-Daily-Mood-Tracker.git
cd MoodPalette-7-Daily-Mood-Tracker

Install dependencies:
bash
npm install

No additional environment variables are required.

## Usage
Start the development server:
bash
npm start

Open your browser and navigate to http://localhost:3000. Select your mood for each day and watch it appear on the colorful calendar heatmap.

## Implementation Steps
1. Initialize a new React application using Create React App (`npx create-react-app`).
2. Create a `MoodSelector` component with emoji or color buttons for mood input.
3. Create a `CalendarHeatmap` component that maps logged moods to a colored month grid.
4. In each component, read and write daily mood entries from `localStorage` to ensure persistence after refresh.
5. Define a mood-to-color mapping and apply it to the calendar cells.
6. Style components using CSS modules or styled-components for a clean, responsive UI.
7. Test data persistence by logging moods, refreshing the page, and verifying the heatmap updates correctly.
8. Build for production with `npm run build` and deploy to your preferred static host.