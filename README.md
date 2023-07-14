Problem Statement. Develop a recipe optimization algorithm that takes into account user preferences and gets customised recipes based on those preferences.
Sub problems.
1.	Recipe information.
	Sub problem. a user may be unskilled in cooking or not or able to read the instructions for the recipe.
	Sub solution. The recipe optimizer could translate the instructions for the recipe into the user’s preferred language. 
2.	User input.
	Sub problem. A user with food restrictions may not be able to find recipes they can eat.
	Sub solution. The recipe optimization could also prompt the user for their food restrictions and then filter the recipe database to only include compatible recipes.
1.	Generating customised recipes.
	The function that generates customised recipes and integrates all the sub- solutions and generates customised recipes.
2.	Filtering recipes by complexity.
	Function to filter the recipe database based on the user’s available time.
	Input time available recipe database
	Output. Filtered recipes that are relatively easy to make within the given time. 
3.	Getting user preferences.
	Function to prompt the user for the food restrictions and store their preferences 
Defining the valuables.
1.	Translating recipe.
	Recipe: recipe object or data structure representing a single recipe.
	Target language: a string representing the user’s preferred language.
2.	Filtering recipes by complexity.
	Time available: a numeric value representing the user’s available time.
	Filtered recipes: list to store recipes that are compatible with the user’s preferences.
 
FUNCTIONS NECESSARY

def generateCustomizedRecipes(userPreferences, recipeDatabase):
    # Implementation logic for generating customized recipes
    # based on user preferences
    customizedRecipes = []
    # Your implementation here
    return customizedRecipes


def translateRecipe(recipe, targetLanguage):
    # Implementation logic for translating the recipe
    # instructions into the target language
    translatedRecipe = {}
    # Your implementation here
    return translatedRecipe


def filterRecipesByComplexity(timeAvailable, recipeDatabase):
    # Implementation logic for filtering the recipe database
    # based on the user's available time
    filteredRecipes = []
    # Your implementation here
    return filteredRecipes


def getUserPreferences():
    # Implementation logic for prompting the user for their
    # food restrictions and storing their preferences
    userPreferences = {}
    # Your implementation here
    return userPreferences
