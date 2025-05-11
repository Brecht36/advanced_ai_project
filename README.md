# Project setup
- First thing you need to do is go to the ollama website and press the download button https://ollama.com/
- When it is completely downloaded open a command prompt and type <code>ollama pull llama3</code> to download the LLM model.

These were the setup steps

## Project overview
The project needs an image of food as input and will output a recipe on how to make this food.

- Run the __final_recipe_maker.ipynb__ to generate a recipe for the food that is the image inside the __input_image__ file (which you can change of course)
- *Optional: (Run the __classification_model_data.ipynb__ file to train the model, for this you also need to download this dataset: https://www.kaggle.com/datasets/dansbecker/food-101 and put it in a folder called __data__, __this in only needed if you would want to make changes to the model, since the model is already downloaded__)*
