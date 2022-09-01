# SmartFridge - Reduce Food Waste

Eliminate Food Waste - Promote Better Health - Meal Planner - Quality Life

## Inspiration
In the United States, food waste is estimated at between 30-40% of the food supply (figure from the FDA). Our biggest inspiration stems from our concern about the environment and how we can make simple lifestyle changes be more responsible about our consumption. SmartFridge app is a solution that makes meal-planning convenient, intuitive and sustainable. We create a logistic app that lets users monitor their food resources with ease. By scanning users' food inventory at home via picture input, the app will classify its users' food into categories, come up with suggested cooking recipes depending on the available food, prioritize food that will go bad soon, and send out alerts once the user's fridge is running low or going to expire. With the aforementioned features, SmartFridge app is the all-in-one solution for people to keep track of their fridge, have a more diverse meal plan, and reduce personal food waste.

## What it does
SmartFridge has 5 main tabs, which are "Scan", "Ingredient", "Meal Plan", "Shopping List", and "Profile" tabs. 
- **Scan**:  Scan images of food ingredients and add to inventory. Integrate image processing functionality through TensorFlow.js to optimize user input step.
- **Ingredient**: Let user easily monitor available food in their home kitchen.
- **Meal Plan**": Suggest recipes that match existing ingredients, bookmark favorite recipes, manage weekly meal plan.
- **Shopping List**: Auto-populated with ingredients user still need for meal plan. Integrate Google Map API to navigate closed-by grocery stores.
- **Profile**: Summary status of fridge like remaining capacity, prediction of number of days until next shopping trip, number of items expiring very soon, manage ingredients used in the week's meal plan.

## How we built it
We built a cross-platform mobile-app using React Native and Expo. We also used spoonacular API to suggest user with cooking recipes, Google Map API to locate nearby stores, and TensorFlow.js for image processing. The back-end of the app is managed through SQLite and Redux. Its main function is to record the food resources of the users and interact between different components of user interaction.

## What we learned
React Native, JavaScript, Expo, spoonacular API, Google Map API, SQLite, Redux, TensorFlow.js

## What's next for SmartFridge - reduce food waste
There are still many functionalities we want to add or optimize. We will need to make improvement to our front-end for a better user interface, and build our own cloud database to store more high-quality recipes and data about our users' preferences.