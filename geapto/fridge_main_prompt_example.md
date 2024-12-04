{
  "responseType": "itemQuery",
  "comment": "Could you clarify the brand and quantity for the milk?",
  "narrative": "An image of a carton of milk on a counter."
}

{
  "responseType": "itemOrder",
  "productList": [
    {
      "TypeName": "chicken breast",
      "FullName": "Organic Chicken Breast by Farmer's Market",
      "Brand": "null",
      "MeasurementType": "WeightOrVolume",
      "Quantity": {
        "Value": "2",
        "Unit": "kilogram"
      }
    },
    {
      "TypeName": "whole milk",
      "FullName": "Horizon Organic Whole Milk",
      "Brand": "Horizon",
      "MeasurementType": "Volume",
      "Quantity": {
        "Value": "1",
        "Unit": "liter"
      }
    }
  ],
  "comment": "Added Organic Chicken Breast and Horizon Organic Whole Milk to the shopping list.",
  "narrative": "An image of raw chicken and a milk carton together."
}

{
  "responseType": "ovenQuery",
  "comment": "The recommended settings are 350°F for 25 minutes. Start now?",
  "narrative": "An image of a frozen pizza with visible instructions."
}

{
  "responseType": "ovenBakeSetting",
  "ovenSetting": {
    "ovenCookType": "0x01",
    "ovenCookTemp": "0x16E",
    "ovenCookTime": "0x19"
  },
  "comment": "The oven is set to bake at 350°F for 25 minutes.",
  "narrative": "An image of a frozen pizza ready for baking."
}

{
  "responseType": "general",
  "comment": "This is a bottle of soy sauce. Do you need a recipe for a dish using soy sauce?",
  "narrative": "An image of a bottle of soy sauce with a visible label."
}

{
  "responseType": "instaCartOrder",
  "fullNameList": [
    "Organic Chicken Breast by Farmer's Market",
    "Horizon Organic Whole Milk"
  ],
  "comment": "The items have been added to your Instacart list.",
  "narrative": "An image of raw chicken and a milk carton together."
}

{
  "responseType": "recipeQuery",
  "comment": "Do you prefer a vegetarian or meat-based recipe for dinner?",
  "narrative": "An image of assorted vegetables and spices on a countertop."
}

{
  "responseType": "recipe",
  "recipeType": "MainCourse",
  "cuisineType": "Italian",
  "dietaryPreference": ["Vegetarian", "DairyFree"],
  "ingredients": "Pasta, olive oil, garlic, tomatoes, basil, salt, pepper",
  "comment": "Here's a vegetarian pasta recipe. It's been sent to the Flavorly AI platform.",
  "narrative": "An image of uncooked pasta with garlic and tomatoes."
}