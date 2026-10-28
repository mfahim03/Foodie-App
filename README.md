# Foodie

A React Native recipe app built with Expo for Expo Go and Snack. The entry point is `App.js`.

## Run locally

```sh
npm install
npx expo start
```

## Peer review answers

**Public GitHub repository:** https://github.com/mfahim03/Foodie-App
**Snack project:** https://snack.expo.dev/@git/github.com/mfahim03/Foodie-App

1. **Imported into Snack from GitHub?** Yes. The public repository was imported into Snack using Import Git Repository. The project targets Expo SDK 54 for compatibility with iPhone Expo Go.
2. **At least 10 horizontal recipe categories?** Yes. The bar includes All, Breakfast, Lunch, Dinner, Dessert, Vegetarian, Vegan, Quick & Easy, Healthy, Snacks, Seafood, Favorites, and My Food.
3. **Complete recipe details?** Yes. Recipe detail screens show ingredients, step-by-step instructions, preparation time, servings, calories, and difficulty.
4. **Category filtering?** Yes. Selecting a food category filters the feed to matching recipes.
5. **Favorite toggle?** Yes. The heart toggles a recipe in and out of Favorites.
6. **Favorites display?** Yes. Favorites is pre-populated with Crispy salmon bowl and updates when hearts are toggled.
7. **My Food and Add New Recipe?** Yes. Both appear in the horizontal bar; My Food also has an Add New Recipe action.
8. **Recipe input and Save Recipe?** Yes. The form supports a recipe name, photo library upload, ingredients, step-by-step instructions, plus category and recipe metadata. Save Recipe publishes it.
9. **New recipe in My Recipes?** Yes. Saving returns to the new recipe detail and adds it to My Food.
10. **My recipe details?** Yes. Selecting a personal recipe opens its image, name, ingredients, instructions, and metadata.
11. **Edit and Delete?** Yes. Each My Food card has working Edit and Delete actions.
12. **Back button?** Yes. Detail and form screens have a Back button; the detail photo also has a back arrow.

Recipes and favorites are held in app state for the current session. The project does not currently connect to a backend or persist changes after the app restarts.
