# Introduction

This github pages site is based on a  simple, plaintext recipe database called Chowdown. You see find more info on deploying the webpage at [chowdown.io](http://chowdown.io) and its [github repository](https://github.com/clarklab/chowdown).


# Writing a Recipe

The recipes are stored in the collection "Recipes" (the folder /_recipes).

They are written in Markdown and contain a few special sections:

- The frontmatter, which contains:
 - Title, Image, and Layout (which is "recipe")
 - Ingredients (a list of things in the dish)
 - Directions (a list of steps for the dish)
- Body content (for intros, stories, written detail)

If you need help with Markdown, here's a [handy cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

# Writing a component recipe

A component recipe is a special recipe made up of other recipes. To make a new component recipe:

- place your smaller, single recipes into the /_components folder
- make a new recipe like normal in the /_recipes folders
- in the frontmatter of this new recipe, include your recipes from the /_components folder (instead of the usual Ingredeints list)
