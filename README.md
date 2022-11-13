# Naive-Bayes-Recipe-Classification

<div align = "justify">

A Project performed in in a team of three:<br>
•	Shubham Jaisawal 1902060 <br>
•	Nimit Jhunjhunwala 1902061 <br> 
•	Shrey Kadam 1902065 <br>

This project simply helps in binary classfication (Vegetarian and Non-Vegetarian) of a dish (food) based on it's ingredients using the Naive Bayes Classification Algorithm.<br>

### Dataset Details<br>
[Dataset: Food Recipes](https://www.kaggle.com/datasets/sarthak71/food-recipes)<br>
This dataset contains more than 8000 food recipes with cuisines from across the globe (with major focus on Indian Dishes). One can find the food recipes, approximate cooking and preparation times, cooking instructions, ingredients used (not the quantity), Recipe Author and Ratings.<br>

#### Dataset Preview:
![Dataset Preview](https://github.com/NimitJhunjhunwala/Naive-Bayes-Recipe-Classification/blob/main/dataset%20preview.png)

### Processing Details
•	Columns were dropped except 'recipe_title', 'diet', and 'ingredients'. <br>
•	Null Rows (Rows with NaN values) and rows which could not be classified in a binary group were dropped. <br> 
•	Diet column values were modified into 'Vegetarian' and 'Non-Vegetarian' after a careful analysis of the data. <br>
•	Vegetarian and Non-Vegetarian data was separated into different dataframes and data was prepocessed (conversion into list, separating each item in the list, etc) before passing them into the algorithm function. <br>

### Snippets of output

 <div align = "center">
 
 ![Classification Output](https://github.com/NimitJhunjhunwala/Naive-Bayes-Recipe-Classification/blob/main/classification%20result.png) 
 </div>

</div>
