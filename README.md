# Testing GPT with a custom context


## Setup

1. Create a `.env` file and add the `OPENAI_API_KEY` into it. You can get your openai api key from the developer portal [here](https://platform.openai.com/account/api-keys).

2. Copy any data you need the model to use as the context in to the data folder. Example of a menu is provided.

3. Run the script by using `python main.py`


## Example answers

The data was extracted from the following image and loaded into the context of the model.

<img src="/public/img.jpg" alt="image of a simple subway menu">



```
What do you want to ask?: What is in the tuna wrap? 
The Tuna Wrap contains 820 Calories, 54g Fat, 53g Carbs, and 33g Protein.
```

```
What do you want to ask?: Which one has the highest carbs?
Meatball Marinara Wrap - 78g Carbs
```

```
What do you want to ask?: Is the boss healthy?
It depends on what your definition of "healthy" is. The Boss wrap has 580 calories, 31g of fat, 49g of carbs, and 29g of protein. Depending on your dietary needs and goals, this wrap could be considered healthy.
```

```
What do you want to ask?: What is the healthiest one?
The healthiest one is the Turkey Wrap, with 430 Calories, 10g Fat, 54g Carbs, and 32g Protein.
```