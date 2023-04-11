This simple website was made by Joshua Ker as a solution to The Odin Project's project: Recipes.
This project exercise utilized the following skills:
- git add & commit
- git push
- various other terminal commands
- basic html formatting
    - ordered and unordered lists
    - headers
    - local image sourcing
    - relative link paths

As a personal shortcut, I wrote a simple python scripting to add list item brackets around 
steps and ingredients found off online recipes.

The script was:
```
x = ''' content here '''
y = []

#if there are additional lines between the steps, strip out the blank lines
for i in x.split("\n"): 
    if i != "":
        y.append(i)

#add line item brackets
for i in y:
    print(f"<li>{i}</li>")'''
```

sources for images and recipes:
- https://www.abeautifulplate.com/the-best-homemade-margherita-pizza/
- https://damndelicious.net/2022/08/12/the-best-ever-cheeseburger/
- https://www.allrecipes.com/recipe/23600/worlds-best-lasagna/
- https://eu.ooni.com/blogs/recipes/margherita-pizza
- https://wikipedia.org