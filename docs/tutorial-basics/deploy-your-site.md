---
id: all-meal-categories
title: List all Meals Categories
description: Get a list of all meal categories from the API
slug: /meal-categories
sidebar_position: 5
---

# List all Meal Categories
This object lets a user retrive information about all Meal categories from the API.


```bash
Endpoint:

`GET` https://www.themealdb.com/api/json/v1/1/categories.php

```



### Request Example
```bash
 https://www.themealdb.com/api/json/v1/1/categories.php 
```

### Json Reponse

```bash
{
  "categories": [
    {
      "idCategory": "1",
      "strCategory": "Beef",
      "strCategoryThumb": "https://www.themealdb.com/images/category/beef.png",
      "strCategoryDescription": "Beef is the culinary name for meat from cattle, particularly skeletal muscle. Humans have been eating beef since prehistoric times.[1] Beef is a source of high-quality protein and essential nutrients.[2]"
    },
    {
      "idCategory": "2",
      "strCategory": "Chicken",
      "strCategoryThumb": "https://www.themealdb.com/images/category/chicken.png",
      "strCategoryDescription": "Chicken is a type of domesticated fowl, a subspecies of the red junglefowl. It is one of the most common and widespread domestic animals, with a total population of more than 19 billion as of 2011.[1] Humans commonly keep chickens as a source of food (consuming both their meat and eggs) and, more rarely, as pets."
    },
  ]
}
```
### Attributes

| Attribute               | Description                                          | Example |
| :----------------       | :------:                                             | ----: |
| idCategory              |   The id of the category. Usually an integer           | 10 |
| strCategory             |   Name of category                                   | Starter|
| strCategoryThumb        |  Image of the category                               | A link to the image  |
| strCategoryDescription  |  Detailed description of the category                | Beef |
