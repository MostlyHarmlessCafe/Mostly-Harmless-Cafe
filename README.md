# Mostly Harmless Cafe

## Contributing recipes

Clone the repo:

`git clone https://github.com/deadbody/deadbody13.github.io`

Create your entry with `hugo new content/post/recipe-title.md` (if you don't have Hugo, install it, it should be in most mainstream repos).

Modify the frontmatter to include the following information (anything with a `< >`, remove the brackets)

```
deadbody13.github.io/content/posts/<recipe-title>.md
---
title: "<Recipe Title>"
date: 2023-06-17T16:39:03-04:00
draft: false
credits:
- <person-1>
- <person-2>
tags:
- <tag-1>
- <tag-2>
---
```

### Tags

Tags are used to categorize the food and drinks and sort them into their respective pages. All posts should generally include either a food or drink tag and any other tags that you think should apply.

The current tags are:
- food (include with all food posts)
    - burgers
    - chicken
    - pasta
    - sauce
- Drinks (include with all drinks)
    - alcoholic
    - non-alcoholic
 
If you don't see a tag here that you think should be included with your recipe, go ahead and list it in the front-matter like all the other tags. If I see enough food/drink items for a particular tag (like `baking`, `desserts`, etc.) I'll add it to the menu and it's better to include too many tags than not enough.

### Crediting Yourself or Others

Credits are... for giving credit. If you want to credit yourself or another person list them here (i.e. `- deadbody13`)

### Previewing

To see if your entry is showing up and how it looks, go to the base of the clones repo and run `hugo server -D` and follow the link it provides. Should be something like `https://localhost:1313/`. This isn't going to actually make the build itself, it's just going to show a preview of what it will look like when it's live. Don't worry about building it though, just contribute the markdown file with the recipe on it.

**Furthermore, **please don't just copy recipes from your favorite cookbooks, at least do something to them to make them unique**. As much as I love using Papa Josh Weissman's recipes I'm not going to post them here unless I made some significant modification to them to make them more "mine".

### Furthermore

Try not to include stories, epiphanies on life, embarrassing moments from high school, that time you scraped your knee, or other stuff that people may feel the need to scroll past to get to the recipe itself.

## Organization

Entries should have at least an `## Ingredients` (unordered) and `## Instructions` (ordered) section. You can also include a section at the end `### Optional` (unordered).

## Contributing to the Website

Have something you think would make the website better (styling, layouts, etc.)? Submit a PR and we'll look into it.

## Credits for Website

[Spicy Forth](https://github.com/SpicyForthProgrammer) - graphics design, web hosting

[Fonts](https://indestructibletype.com/Home.html) are from Owen Earl from IndestructibleType*.
