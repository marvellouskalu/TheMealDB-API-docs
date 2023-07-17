---
id: filter-all
title: Filter all Categories, Area and Ingredient
description: How to filter all Categories, Area and Ingredient
slug: /filter-all
sidebar_position: 7
---

# Filter by Category

This object lets a user filter information about available categories from the API.


```bash
Endpoint:

`GET` www.themealdb.com/api/json/v1/1/filter.php?c=Seafood

```


### Request Example
```bash

 www.themealdb.com/api/json/v1/1/filter.php?c=Seafood

```

### Json Response

```bash
{
  "meals": [
    {
      "strMeal": "Baked salmon with fennel & tomatoes",
      "strMealThumb": "https://www.themealdb.com/images/media/meals/1548772327.jpg",
      "idMeal": "52959"
    },
    {
      "strMeal": "Cajun spiced fish tacos",
      "strMealThumb": "https://www.themealdb.com/images/media/meals/uvuyxu1503067369.jpg",
      "idMeal": "52819"
    },
    {
      "strMeal": "Escovitch Fish",
      "strMealThumb": "https://www.themealdb.com/images/media/meals/1520084413.jpg",
      "idMeal": "52944"
    }
  ]
}
```

### Attributes

| Attribute                  | Description                                          | Example |
| :----------------          | :------:                                             | ----: |
| strMeal                    |   Name of meal under this category                   | Escovitch Fish |
| strMealThumb               |   Image of meal. Usually a link                      | Link to Image     |
| idMeal                     |  Id of meal. Usually an interger                     | 52944 |


## Filter by Main Ingredient

This object lets a user filter information about all available meal by main ingredient from the API.


```bash
Endpoint:

`GET` https://www.themealdb.com/api/json/v1/1/filter.php?i=chicken_breast

```



### Request Example
```bash

 https://www.themealdb.com/api/json/v1/1/filter.php?i=chicken_breast


```

### Json Response

```bash
{
  "meals": [
    {
      "strMeal": "Chick-Fil-A Sandwich",
      "strMealThumb": "https://www.themealdb.com/images/media/meals/sbx7n71587673021.jpg",
      "idMeal": "53016"
    },
    {
      "strMeal": "Chicken Couscous",
      "strMealThumb": "https://www.themealdb.com/images/media/meals/qxytrx1511304021.jpg",
      "idMeal": "52850"
    },
    {
      "strMeal": "Chicken Fajita Mac and Cheese",
      "strMealThumb": "https://www.themealdb.com/images/media/meals/qrqywr1503066605.jpg",
      "idMeal": "52818"
    }
  ]
}
```
### Attributes

| Attribute                  | Description                                          | Example |
| :----------------          | :------:                                             | ----: |
| strMeal                    |   Name of meal with this ingredient                  | Chicken Fajita Mac and Cheese |
| strMealThumb               |   Image of meal. Usually a link                      | Link to Image     |
| idMeal                     |  Id of meal. Usually an interger                     | 52818 |


## Filter by Area

This object lets a filter information about all available meal by area from the API.


```bash
Endpoint:

`GET` https://www.themealdb.com/api/json/v1/1/filter.php?a=Canadian
```



### Request Example
```bash

 https://www.themealdb.com/api/json/v1/1/filter.php?a=Canadian

```

### Json Response
```bash
{
  "meals": [
    {
      "strMeal": "BeaverTails",
      "strMealThumb": "https://www.themealdb.com/images/media/meals/ryppsv1511815505.jpg",
      "idMeal": "52928"
    },
    {
      "strMeal": "Breakfast Potatoes",
      "strMealThumb": "https://www.themealdb.com/images/media/meals/1550441882.jpg",
      "idMeal": "52965"
    },
    {
      "strMeal": "Canadian Butter Tarts",
      "strMealThumb": "https://www.themealdb.com/images/media/meals/wpputp1511812960.jpg",
      "idMeal": "52923"
    }
  ]
}

```
### Attributes

| Attribute                  | Description                                          | Example |
| :----------------          | :------:                                             | ----: |
| strMeal                    |   Name of meal with this ingredient                  | Canadian Butter Tarts |
| strMealThumb               |   Image of meal. Usually a link                      | Link to Image     |
| idMeal                     |  Id of meal. Usually an interger                     | 52923 |
