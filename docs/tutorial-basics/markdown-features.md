---

id: random-search
title: Single Random Meal
description: Get a single random meal from the API
slug: /random-search
sidebar_position: 4
---

# Get Single Random Meal
This object lets a user retrive a single information from the API in a random manner.


```bash
Endpoint:

`GET` https://www.themealdb.com/api/json/v1/1/random.php

```



### Request Example
```bash
 https://www.themealdb.com/api/json/v1/1/random.php 
```

### Json Reponse
```bash

{
  "meals": [
    {
      "idMeal": "53062",
      "strMeal": "Walnut Roll Gužvara",
      "strDrinkAlternate": null,
      "strCategory": "Dessert",
      "strArea": "Croatian",
      "strInstructions": "Mix all the ingredients for the dough together and knead well. Cover the dough and put to rise until doubled in size which should take about 2 hours. Knock back the dough and knead lightly.\r\n\r\nDivide the dough into two equal pieces; roll each piece into an oblong about 12 inches by 8 inches. Mix the filling ingredients together and divide between the dough, spreading over each piece. Roll up the oblongs as tightly as possible to give two 12 inch sausages. Place these side by side, touching each other, on a greased baking sheet. Cover and leave to rise for about 40 minutes. Heat oven to 200ºC (425ºF). Bake for 30-35 minutes until well risen and golden brown. Bread should sound hollow when the base is tapped.\r\n\r\nRemove from oven and brush the hot bread top with milk. Sift with a generous covering of icing sugar.",
      "strMealThumb": "https://www.themealdb.com/images/media/meals/u9l7k81628771647.jpg",
      "strTags": "Nutty",
      "strYoutube": "https://www.youtube.com/watch?v=Q_akngSJVrQ",
      "strIngredient1": "Flour",
      "strIngredient2": "Caster Sugar",
      "strIngredient3": "Yeast",
      "strIngredient4": "Salt",
      "strIngredient5": "Milk",
      "strIngredient6": "Eggs",
      "strIngredient7": "Butter",
      "strIngredient8": "Walnuts",
      "strIngredient9": "Butter",
      "strIngredient10": "Brown Sugar",
      "strIngredient11": "Cinnamon",
      "strIngredient12": "Milk",
      "strIngredient13": "Icing Sugar",
      "strIngredient14": "",
      "strIngredient15": "",
      "strIngredient16": "",
      "strIngredient17": "",
      "strIngredient18": "",
      "strIngredient19": "",
      "strIngredient20": "",
      "strMeasure1": "450g",
      "strMeasure2": "55g",
      "strMeasure3": "2 parts ",
      "strMeasure4": "1/2 tsp",
      "strMeasure5": "6 oz ",
      "strMeasure6": "2 Beaten ",
      "strMeasure7": "30g",
      "strMeasure8": "140g",
      "strMeasure9": "85g",
      "strMeasure10": "85g",
      "strMeasure11": "1 tsp ",
      "strMeasure12": "To Glaze",
      "strMeasure13": "To Glaze",
      "strMeasure14": " ",
      "strMeasure15": " ",
      "strMeasure16": " ",
      "strMeasure17": " ",
      "strMeasure18": " ",
      "strMeasure19": " ",
      "strMeasure20": " ",
      "strSource": "https://www.visit-croatia.co.uk/croatian-cuisine/croatian-recipes/",
      "strImageSource": null,
      "strCreativeCommonsConfirmed": null,
      "dateModified": null
    }
  ]
}
```
### Attributes
Whenever the page is refreshed, a new random meal is displayed. All attributes of this reponse is similar to that gotten by the [get meal by name response](http://localhost:3000/docs/search-name#attributes)
