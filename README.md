# Recipe
Here's what happens when you run the code:

1. The program starts by displaying a menu with three options: 
   - Create a new recipe
   - View recipes
   - Exit

2. If the user selects option 1, they are prompted to enter the details of a recipe. They provide the recipe name, the number of ingredients, and the details of each ingredient (name, quantity, unit, calories, food group). They also enter the number of steps and provide a description for each step. The recipe is then created and added to the list of recipes.

3. If the user selects option 2, they can view the existing recipes. The program displays a sorted list of recipe names and prompts the user to select a recipe. If a valid selection is made, the program displays the recipe's details, including the ingredients, steps, total calories, and a warning if the recipe exceeds 300 calories.

4. If the user selects option 3, the program exits and terminates.

The program continues to loop through the menu options until the user chooses to exit (option 3).























Changes from the lecture comment


1. Allow Multiple Recipes:
   - Modify the application to allow the user to enter an unlimited number of recipes. You need to create a data structure (such as a list or an array) to store multiple recipes.
   - Each recipe should have a unique name provided by the user.

2. Display a List of Recipes:
   - Implement a feature to display a list of all the recipes to the user.
   - The list should be sorted in alphabetical order by recipe name.

3. Select Recipe to Display:
   - Allow the user to choose a recipe from the list to display its details.
   - When the user selects a recipe, display the recipe's details, including ingredients, steps, and any additional information.

4. Additional Ingredient Information:
   - Extend the functionality of entering ingredient details to include the number of calories and the food group to which each ingredient belongs.
   - Modify the data structure that stores ingredient information to accommodate the new properties.

5. Calculate Total Calories:
   - Implement a calculation to determine the total calories of all the ingredients in a recipe.
   - Sum up the calories of each ingredient in a recipe and display the total calories to the user.

6. Notify Excessive Calories:
   - Add a notification mechanism to inform the user when the total calories of a recipe exceed 300.
   - Display a warning message to the user when a recipe's total calories exceed the limit.



