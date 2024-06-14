# POE
This project is a Recipe Application built using C# and WPF, designed to allow users to manage and display recipes with various functionalities.

Features
Enter Recipe Details: Users can enter details for a recipe including its name, ingredients (name, quantity, unit, calories, and food group), and preparation steps.

Display Recipe: The application displays a list of all entered recipes sorted alphabetically by name. Users can select a recipe to view its details including ingredients and steps.

Calculate Total Calories: The software calculates and displays the total calories for each recipe. It also notifies the user if the total calories of a recipe exceed 300.

Scaling Recipe: Users can scale a recipe by a factor of 0.5 (half), 2 (double), or 3 (triple), adjusting all ingredient quantities accordingly.

Reset Recipe: Allows users to reset all ingredient quantities back to their original values.

Clear Data: Provides an option to clear all entered data to start entering a new recipe.

Graphical User Interface: The application has a user-friendly GUI built using Windows Presentation Foundation (WPF), providing an intuitive interface for interaction.

Unit Testing: Includes unit tests to ensure accurate calculation of total calories.

Requirements
Development Environment: Visual Studio 2022 or later.
Framework: .NET Framework 4.7.2 or later.
NuGet Packages: Any additional packages used in the project.
Installation
Clone the repository from GitHub: Link to your GitHub repository.

Open the solution file (RecipeApplication.sln) in Visual Studio.

Restore NuGet packages if necessary.

Build the solution (Ctrl + Shift + B) to restore dependencies and compile the project.

Usage
Running the Application:

Set the startup project to RecipeApplicationGUI if not already set.
Press F5 or click on the Start button in Visual Studio to run the application.
Entering Recipe Details:

Enter the recipe name, ingredients (name, quantity, unit, calories, food group), and steps using the provided text boxes and buttons.
Displaying Recipes:

Click on the "Display Recipes" button to view a list of all entered recipes. Select a recipe to view its details.
Scaling Recipe:

Enter a scale factor (0.5, 2, or 3) in the appropriate field and click the "Scale Recipe" button to adjust ingredient quantities accordingly.
Resetting Recipe:

Click the "Reset Recipe" button to revert all ingredient quantities to their original values.
Clearing Data:

Click the "Clear Data" button to remove all entered recipes and start with a clean slate.
Testing
Unit tests are included in the project to verify the functionality of calculating total calories. Run the unit tests using the Test Explorer in Visual Studio.
Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request with your proposed changes.
