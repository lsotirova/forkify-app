# Recipe App

This is a simple Recipe App that allows you to search for recipes, view detailed information about a selected recipe, and manage your bookmarks. You can also add your own recipes to the app.

## How to Use

### Recipe Search

1. Enter your search query in the search bar and click the "Search" button.
2. The app will display a list of recipes matching your search query.
3. Click on a recipe to view its details.

### Recipe Details

1. Click on a recipe from the search results to view its details.
2. You can adjust the number of servings for the recipe.
3. You can bookmark the recipe by clicking the bookmark icon.

### Bookmarks

1. Click on the "Bookmarks" button in the navigation menu to view your bookmarked recipes.
2. You can remove a bookmark by clicking the bookmark icon on the recipe details page.

### Add Your Recipe

1. Click on the "Add Recipe" button in the navigation menu.
2. Fill in the required information for your recipe, including title, URL, image URL, publisher, prep time, and servings.
3. You can also add ingredients for the recipe.
4. Click the "Upload" button to add your recipe to the app.

## Code Structure

The app is organized into several JavaScript files:

- `model.js`: Contains the application's data model and functions for loading recipes, search results, and managing bookmarks.

- `controller.js`: Manages the application's control flow and event handlers. It controls the interactions between the model and views.

- `helpers.js`: Contains utility functions, including AJAX requests and timeout handling.

- `addRecipeView.js`: Handles the view and user interactions for adding a new recipe.

- `bookmarksView.js`: Manages the view for displaying and rendering bookmarked recipes.

- `paginationView.js`: Manages the view for rendering pagination buttons.

- `previewView.js`: Handles the view for rendering recipe previews.

- `resultsView.js`: Manages the view for rendering search results.

- `searchView.js`: Handles user interactions and events related to the search feature.

- `view.js`: Contains the base View class used for rendering and updating views with data.

## Getting Started

To run the app, make sure you have the necessary dependencies installed. You can start by opening the HTML file in a web browser. Please note that this app does not have a backend, so it relies on the provided API for recipe data.

This app provides a user-friendly interface for searching, viewing, and managing recipes. You can also add your own recipes to the collection. Enjoy exploring and cooking delicious dishes!
