# Shopping List

## Description

The goal of the assesment is to test your abilities to:

1. Handle asynchronous code (async/await/loading/error handling)
2. Handle state managment (context or local state)
3. Handle Gitflow (commits, pushes, etc)
4. CSS and HTML standards

## Technolgies

1. React

## Acceptance Critera

1. I am able to view all the groceries items in a list
2. I am able to add items to my Shopping List
3. I am able to remove an item from my Shopping List
4. I am able to favorite items in my shopping list and grocery list (indicated by having a Favorited icon next to the item)
5. I am able to increase and decrease the quantity of an item on my Shopping List only
6. I am able to add more custom items to my list of groceries (outside of the 10 provided you can add to that list)
7. View nutritional information about a grocery item

## Data Structure

When creating the data structure of the shopping list it should look exactly like this (array of objects):
You can utilize this data below as your mock data. Please just expand on the nutrition a little more.

```
[
    {
        id: 1,
        name: "Carrots",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 3
        }],
        selected: false
    },
    {
        id: 2,
        name: "Milk",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 7
        }],
        selected: false
    },
    {
        id: 3,
        name: "Butter",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 2
        }],
        selected: false
    },
    {
        id: 4,
        name: "Eggs",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 4
        }],
        selected: false
    },
    {
        id: 5,
        name: "Oranges",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 1
        }],
        selected: false
    },
    {
        id: 6,
        name: "Blueberries",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 19
        }],
        selected: false
    },
    {
        id: 7,
        name: "Apples",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 7
        }],
        selected: false
    },
    {
        id: 8,
        name: "Bread",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 5
        }],
        selected: false
    },
    {
        id: 9,
        name: "Coffee",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 4
        }],
        selected: false
    },
    {
        id: 10,
        name: "Pancakes",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 11
        }],
        selected: false
    },
]
