# Calories Tracker
## Table of Content:

- [About The App](#about-the-app)
- [Screenshots](#screenshots)
- [Technologies](#technologies)
- [Setup](#setup)
- [Approach](#approach)
- [Status](#status)

## About The App
This app allows a user to record and save their daily meals and calories. It automatically calculates the total calories and allows for listing the meals by ascending/descending calories.
## Screenshots
![image](https://github.com/arjuntrivedi/calories-tracker-app/assets/72959325/4f25ea92-e4bd-4e27-9729-3c46e5f6e5fd)

## Technologies
I used `html`, `css`, `JavaScript`, `localStorage`, and `React.js`

## Setup
- Download or clone the repository
- Run `npm install` to run the app in the development mode.
- Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
- run `npm build` to deploy the app

## Approach
1. **Requirements:** I started with the idea of creating a comprehensive tool to assist users in managing their daily calorie intake, originating from my own needs. 
2. **Design:** I used React to develop the app due to its efficiency and the ease of creating reusable UI components. When designing the system, I created multiple JavaScript classes that each corresponded to one UI component (list of meals, delete-all button, ordering filter, etc..)
3. **Implementation:** Throughout the system, I used React Hooks such as `useState` and `useEffect` to add state to functional components.

## Status
The Calories Tracker app is still in progress. I plan to switch from local storage to a database such as MongoDB to prevent data loss when clearing the cache. I also plan to develop an authentication system for individual user profiles to make the project deployable. 

