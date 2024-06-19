# CS411 Project Proposal

## Author
- Tianyi Gao

## Project Idea 1: Personalized Fitness and Nutrition Dashboard
### Description
This web application will help users track their fitness and nutrition goals. Users can log their meals, track their calorie intake, and receive personalized diet and workout recommendations. The application will integrate the MyFitnessPal API to fetch nutritional information and offer insights based on user input.

### APIs to Use
- **MyFitnessPal API**: To fetch food information and nutritional data.
- **Google Maps API**: To locate nearby gyms or fitness centers.

### Database Utilization
- Store user profiles, meal logs, workout logs, and personalized recommendations.

### Third-Party Authentication
- Implement login using Google OAuth.

### Decoupled Architecture
- **Front End**: Built with Angular, containing components for user input (meal log, workout log) and display (nutrition info, workout recommendations).
- **Back End**: Developed with Node.js, handling API requests to MyFitnessPal and managing user data.

## Project Idea 2: Healthy Recipe Finder
### Description
This web application allows users to search for healthy recipes based on their dietary preferences and restrictions. Users can input specific ingredients or nutritional goals, and the app will use the MyFitnessPal API to find suitable recipes and provide detailed nutritional information.

### APIs to Use
- **MyFitnessPal API**: To fetch food and nutritional information.
- **Edamam Recipe API**: To find recipes based on ingredients and dietary restrictions.

### Database Utilization
- Store user preferences, favorite recipes, and search history.

### Third-Party Authentication
- Implement login using Facebook OAuth.

### Decoupled Architecture
- **Front End**: Built with Angular, featuring components for searching recipes and displaying nutritional info.
- **Back End**: Developed with Node.js, handling API requests to MyFitnessPal and Edamam, and managing user data.
