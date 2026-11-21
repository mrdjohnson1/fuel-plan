# 30-50-20 Meal Plan

A phone-friendly meal plan app: 3,400 calories a day at 30% protein, 50% carbs and 20% fat, across 4 meals, with a grocery list for every meal.

## What's inside

- **Your Plan:** the daily layout, carb add-ons, fuel meals, school lunch packing tips and a shopping list
- **7 meal plans:** Crockpot, Road, No-Cook Power Bowls, Quick and Easy Recipes, Burritos, Fish Crockpot Meals and More Recipes
- **Your numbers on every meal page,** with the carb add-on included
- **A grocery list for every meal,** with checkboxes that remember what you've bought on each device
- **Meal builder** and **search** across every recipe, food and nutrient
- **Works offline** after the first visit, and can be added to a phone's home screen

## Files

| File | What it does |
| --- | --- |
| `index.html` | The app (all content is inside this file) |
| `manifest.webmanifest` | App name, colors and icon for "Add to Home Screen" |
| `sw.js` | Lets the app open without a connection after the first visit |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | Home screen icons |
| `icon.svg` | The icon artwork |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Updating the app

Upload a new `index.html` over the old one. To make phones pick up the change right away, also change `fuel-plan-v1` in `sw.js` to the next number (for example `fuel-plan-v2`).

Talk with your doctor before adding supplements.
