# RecipeXpert-Culinary-Companion
Repository Description: A Java-based Recipe Management System implementing OOP principles. Allows users to upload, view, and save recipes with ingredients and descriptions.
It includes the following classes:

## 1. CookingItem (Abstract Class)
- Abstract class representing a cooking item.
- Attributes:
  - `name`: Name of the cooking item.
- Methods:
  - `displayDetails()`: Abstract method to display details of the cooking item.

## 2. Ingredient (Concrete Class)
- Subclass of `CookingItem`.
- Represents an ingredient with quantity and unit.
- Attributes:
  - `quantity`: Quantity of the ingredient.
  - `unit`: Unit of the ingredient.
- Methods:
  - `displayDetails()`: Displays details of the ingredient.

## 3. Recipe (Concrete Class)
- Subclass of `CookingItem`.
- Represents a recipe containing ingredients and description.
- Attributes:
  - `description`: Description of the recipe.
  - `ingredients`: List of ingredients in the recipe.
- Methods:
  - `displayDetails()`: Displays details of the recipe.
  - `addIngredient(Ingredient ingredient)`: Adds an ingredient to the recipe.
  - `saveRecipeToFile()`: Saves the recipe to a text file.

## 4. RecipeManager (Main Class)
- Manages the recipe management system with user interaction.
- Allows users to upload new recipes, view existing recipes, and quit the program.

### Usage
1. Compile and run the `RecipeManager` class.
2. Choose options to upload new recipes, view existing recipes, or quit the program.

### Example

Choose an option:

1. Upload a new recipe
2. Look at existing recipes
3. Quit
   
Enter your choice: 1

Enter the recipe name: Spaghetti Bolognese

Enter the recipe description: A classic Italian pasta dish with a rich meat sauce.

Enter the number of ingredients: 4

Enter ingredient name: Spaghetti

Enter quantity: 200

Enter unit: grams

Enter ingredient name: Ground beef

Enter quantity: 300

Enter unit: grams

Enter ingredient name: Onion

Enter quantity: 1

Enter unit: piece

Enter ingredient name: Tomato sauce

Enter quantity: 400

Enter unit: milliliters

Recipe added successfully!

Choose an option:

1.Upload a new recipe
2.Look at existing recipes
3.Quit

Enter your choice: 2

Existing recipes:

Spaghetti Bolognese

Enter the recipe number you want to view: 1

Recipe: Spaghetti Bolognese

Description: A classic Italian pasta dish with a rich meat sauce.

Ingredients:

200.0 grams of Spaghetti

300.0 grams of Ground beef

1.0 piece of Onion

400.0 milliliters of Tomato sauce



Feel free to modify and extend this project as needed.
