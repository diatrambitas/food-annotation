# Spice
The Spice section refers to any dried part of a plant, other than the leaves, used for seasoning and flavoring a recipe. Every other part of the plant, including dried bark, roots, berries, seeds, twigs, or anything else that isn't the green leafy part, is considered a spice. The spices are used only in dried form. Examples of spices: cloves, pepper, or cumin, nutmeg, chilli flakes, turmeric, cardamom, ginger cayenne, black pepper, dried garlic etc.

	Example:
 ![image](https://user-images.githubusercontent.com/28726658/160099486-f88eb959-a22d-42fc-ad91-47ecddc39a2c.png)

# Meat
This entity represents any mention of the animal flesh that is eaten as food. It refers to the meat belonging to the following categories: Red meat (veal, pork, beef, lamb, goat etc.), Poultry, commonly referred to as white meat (chicken, turkey) and Seafood (fish, lobster, crab etc.).  It also includes processed meat products e.g. ham, bacon, sausages, salami, corned beef, jerky etc.

	Example:
![image](https://user-images.githubusercontent.com/28726658/160099524-108d9d1b-3423-4498-8d48-8097b09ffe48.png)

 

If meat part is specified, extract the entire as an entity, e.g., chicken breast, sirloin.
If meat is part of a recipe, e.g., meatballs, do not extract.
Double annotate meat if quantity is specified, e.g. 1/2 tuna

# Herb
Herbs are a widely distributed and widespread group of plants, with savory or aromatic properties that are used for flavoring and garnishing food. Culinary use typically distinguishes herbs from spices. Herbs generally refer to the leafy green or flowering parts of a plant (either fresh or dried), while spices are usually dried and produced from other parts of the plant. Examples of herbs: sage, basil, mint, parsley, dill, thyme, oregano etc.

Double annotate if the herb is also a vegetable e.g., chives.
	
	Example:
 ![image](https://user-images.githubusercontent.com/28726658/160099556-158526fc-bafa-423a-a8cd-a4316ad32257.png)
![image](https://user-images.githubusercontent.com/28726658/160099575-d848bf52-179f-4184-9df5-3102be9e4dd8.png)

 

# Dairy
This entity refers to the products that are obtained primarily from or contain milk of mammals such as cattle, goats, sheep, etc. Dairy products include a variety of foods such as cheese, butter, yogurt, feta cheese, cream cheese, buttermilk etc.

If type of cheese is specified, extract as one entity e.g., cream cheese, blue cheese.

	Example:
![image](https://user-images.githubusercontent.com/28726658/160099598-b3708fd3-f44f-4ad0-9b6a-65d69d8fca3b.png)

 

# Fruit
A fruit usually refers to any sweet-tasting plant that develops from a flower and contains seeds. Fruit is often used in sweet dishes, such as puddings, pies, and jellies. It can also be found in salads or appetizers. A few examples include apples, lemons, oranges, strawberries etc.

	Example:
![image](https://user-images.githubusercontent.com/28726658/160099612-0184991f-916e-4423-b60d-781743e0fe9d.png)

 


# Vegetable
Vegetables are usually herbaceous plants (such as the cabbage, bean, or potato) grown for an edible part that is most often eaten as part of a savoury dish. 

Extract as vegetable if in leaf form but if in dried or powder form, extract as spice.

E.g.,
Garlic is a vegetable, but dried garlic is a spice.
Ginger is a vegetable and dried or powdered ginger is spice.

	Example:
![image](https://user-images.githubusercontent.com/28726658/160099675-73d4bcc2-090f-42ed-9521-a8d77ffaeefe.png)

 

# Quantity
In recipes, the quantities of ingredients are measured by weight (pounds, ounces), volume (cups, teaspoons), or count (2 eggs, 4 pork chops). 

Extract the number along with the measurement.
In recipes, yield is extracted as quantity as well e.g., 20 servings.  
	
	Example:

 ![image](https://user-images.githubusercontent.com/28726658/160099698-3028723b-7e9e-471b-a732-1120dafc9622.png)


# Temperature
This entity includes the required temperature for a food to be cooked, mentioned in the recipe. Do not include the word degree after F or C.

Extract low heat, medium heat, high heat as measures of temperature as well.

	Example:

 ![image](https://user-images.githubusercontent.com/28726658/160099715-05fdec85-cd24-48e9-9caf-a7e3585be9ba.png)

# Cook time
The cooking time written in the recipe refers to the time (seconds or minutes) necessary for the food to be cooked or prepared.

If cooking time is a range, it should be extracted as one e.g., 30 to 60 seconds, or 3-4 minutes.

Example:
![image](https://user-images.githubusercontent.com/28726658/160099735-da66fe9f-4382-4cdf-a0d2-1b78fbe07dc1.png)

 
