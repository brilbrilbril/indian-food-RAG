# indian-food-RAG
Brillyando Magathan Achmad

1. This chain will make the marketing process to be more personalized like spicy or not, vegetarian or not, and good for diet or not because more interactive and detailed description will be given to user based on their query or desire.

2.
- I used prompt formatting as follows:
"You are a food recommender tasked with assisting people with food suggestions"
"You will be given a number of images of indian foods and corresponding descriptions."
"Use this information to provide assistance with foods."
f"User-provided question: {data_dict['question']}"
"Images and their descriptions:"

The reason was to give a role to LLM as food recommender or food expert, allowing system to customize output, retrieve and generate relevant context, which is indian food.

- The chain I used was build retriever (fetch indian food images and its description) -> LLM modified and refined the description based on user's query and image description

The reason is to make sure that LLM get the context and have the ability to provide more personalized output or result based on query and database (image and description)

3. This approach definitely adds significant value to product marketing and personalization. In term of marketing, the descriptive text will boost user's mood and interest. It will highlight the taste, occasions, ingredients, and nutrition, make the food more appealing. Not only that, the LLM can consider user's preferences such as spice level, good for diet, vegetarian/non vegetarian, and many more, according to user's query.
