# Instagram-ad-caption-generation

This project aims to generate engaging Instagram ad captions using a fine-tuned Llama model.

## Project Structure

- **data/instagram_posts.json**: The dataset containing Instagram ad posts.
- **images/**: Folder containing example usage images.
- **eda-of-ig-ad-dataset.ipynb**: Notebook for exploratory data analysis of the Instagram ad dataset.
- **finetuning-llama.ipynb**: Notebook for fine-tuning the Llama model on the Instagram ad dataset.
- **llama3-inference.ipynb**: Notebook for generating captions using the fine-tuned Llama model.
- **scraping_insta_posts.ipynb**: Script for scraping Instagram ad posts.

### Requisites

- Google colab to run the notebooks.
- A Python3 environment using T4 GPU as an accelerator.
- Required libraries are listed and installed while running the notebooks.

### Dataset

The dataset is stored in `data/instagram_posts.json`.

## Usage

### Scraping Instagram Posts

Run the `scraping_insta_posts.ipynb` notebook to scrape Instagram ad posts. This notebook includes:
- Setting up Instagram scraping
- Extracting posts and saving them to a JSON file

### Exploratory Data Analysis

Run the `eda-of-ig-ad-dataset.ipynb` notebook to perform exploratory data analysis on the Instagram ad dataset. This notebook includes:
- Data cleaning and preprocessing
- Visualizations and insights

### Fine-Tuning the Model

Run the `finetuning-llama.ipynb` notebook to fine-tune the Llama model on the Instagram ad dataset. This notebook includes:
- Loading and preprocessing the dataset
- Setting up the model and tokenizer
- Fine-tuning the model with the dataset
- Saving the fine-tuned model

### Generating Captions

Run the `llama3-inference.ipynb` notebook to generate captions using the fine-tuned Llama model. This notebook includes:
- Loading the fine-tuned model and tokenizer
- Generating captions based on input prompts
- Example usage and testing


## Example Usage

### Generating Captions

Here are some example images demonstrating how to generate captions using the fine-tuned Llama model:


![image](https://github.com/geeeeenccc/Instagram-ad-caption-generation/assets/101811004/0030930e-94cb-4251-820d-575a20f42121)


![image](https://github.com/geeeeenccc/Instagram-ad-caption-generation/assets/101811004/6a35a7c3-32f3-4430-b687-868b1b3f06cf)


