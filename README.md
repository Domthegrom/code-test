# Shopping List

## Description

The goal of the assesment is to test your abilities to:

1. Making an API call and retrieve data. 
2. Handle asynchronous code (async/await/loading/error handling)
3. Handle state managment (context or local state)
4. Handle Gitflow (commits, pushes, etc)
5. CSS and HTML standards

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

```[
    {
        id: 1,
        name: "Carrots",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 3
        }]
    },
    {
        id: 2,
        name: "Milk",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 7
        }]
    },
    {
        id: 3,
        name: "Butter",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 2
        }]
    },
    {
        id: 4,
        name: "Eggs",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 4
        }]
    },
    {
        id: 5,
        name: "Oranges",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 1
        }]
    },
    {
        id: 6,
        name: "Blueberries",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 19
        }]
    },
    {
        id: 7,
        name: "Apples",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 7
        }]
    },
    {
        id: 8,
        name: "Bread",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 5
        }]
    },
    {
        id: 9,
        name: "Coffee",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 4
        }]
    },
    {
        id: 10,
        name: "Pancakes",
        favorite: false,
        quantity: 0,
        nutrition: [{
            sugars: 11
        }]
    },
]
