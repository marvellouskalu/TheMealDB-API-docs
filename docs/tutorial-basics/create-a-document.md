---

id: meals-by-first-letter
title: Search Meals by First Letter
description: How to search meals by first letter
slug: /search-by-first-letter
sidebar_position: 2
---

# Search Meal by First Letter
This object lets a user retrive information about a particular meal from the API by using the search by **first letter** query


```bash
Endpoint:

`GET` https://www.themealdb.com/api/json/v1/1/search.php?f={"first letter of meal"} 

```

Replace `first letter of meal` with the letter of your choice

### Request Example
```bash

 https://www.themealdb.com/api/json/v1/1/search.php?f=b

```

### Json Reponse
```bash
{
  "meals": [
    {
      "idMeal": "52767",
      "strMeal": "Bakewell tart",
      .
      .
    },
    {
      "idMeal": "52792",
      "strMeal": "Bread and Butter Pudding",
      .
      .
    },
    {
      "idMeal": "52803",
      "strMeal": "Beef Wellington",
      .
      .
    },
    {
      "idMeal": "52807",
      "strMeal": "Baingan Bharta",
      .
      .
    }
  ]
}

```
### Attributes
The request to list all meals by first letter returns a response of all meals in the API whose values for the key `strMeal` begins with the letter `b`.
All attributes of this reponse is similar to that gotten by the [get meal by name response](http://localhost:3000/docs/search-name#attributes)

