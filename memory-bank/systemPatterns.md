# System Patterns

## Content Organization

The cookbook's content is organized by **Meal Type**. This structure was chosen for its intuitive and traditional approach to recipe categorization.

The primary chapters are:

- `index.qmd`
- `breakfast.qmd`
- `sauces_marinades.qmd`
- `main_courses.qmd`
- `side_dishes.qmd`
- `desserts.qmd`
- `drinks.qmd`

The bibliography file is `references.bib`.

## Recipe Formatting

- **Measurement Formatting**: All ingredients should list the metric measurement first, followed by the imperial equivalent in parentheses. For example: `500g (1.1 lbs)`. Values can be rounded to make measurements easier, as long as it doesn't substantially change the recipe.
- **Temperatures**: All temperatures should be provided in both Fahrenheit and Celsius, with the primary unit first followed by the conversion in parentheses. For example: `400°F (200°C)`.
- **Butter**: Butter measurements should include both grams and the equivalent in tablespoons. For example: `113g (8 tbsp)`.
- **Spice Measurement**: All spices should be measured in grams.
- **Notification**: When performing these conversions, I will inform you of the changes I am making.

## Ingredient Subsection Strategy

To improve the readability and consistency of recipes, the ingredients list should be broken down into logical subsections where appropriate.

Common subsections include:

- `#### Spices`
- `#### Garnishes`
- `#### For the Sauce`
- `#### For the Marinade`
- `#### For the Dough`
- `#### For the Topping`
- `#### For Brushing`

## Scalable Ingredient Tables

For recipes that are frequently scaled (like drinks or party batches), use a Markdown table to present ingredient quantities for 1, 2, and 3 batches side-by-side. This reduces cognitive load during preparation.

| Ingredient | 1 Batch | 2 Batches | 3 Batches |
| :--- | :--- | :--- | :--- |
| **Item** | Amount | Amount | Amount |
