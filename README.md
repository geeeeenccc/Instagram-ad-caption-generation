# **Instagram-ad-caption-generation**

This project aims to generate engaging Instagram ad captions using a fine-tuned [Llama-3](https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct) model from Hugging Face.

## **Project Structure**

- **data/instagram_posts.json**: The dataset containing Instagram ad posts.
- **eda-of-ig-ad-dataset.ipynb**: Notebook for exploratory data analysis of the Instagram ad dataset.
- **finetuning-llama.ipynb**: Notebook for fine-tuning the Llama model on the Instagram ad dataset.
- **llama3-inference.ipynb**: Notebook for generating captions using the fine-tuned Llama model.
- **scraping_insta_posts.ipynb**: Script for scraping Instagram ad posts.

### **Requisites**

- Google colab to run the notebooks.
- A Python3 environment using T4 GPU as an accelerator.
- Required libraries are listed and installed while running the notebooks.

### **Dataset**

The dataset is stored in `data/instagram_posts.json`.

## **Usage**

### **Scraping Instagram Posts**

Run the `scraping_insta_posts.ipynb` notebook to scrape Instagram ad posts. This notebook includes:
- Setting up Instagram scraping
- Extracting posts and saving them to a JSON file

### **Exploratory Data Analysis**

Run the `eda-of-ig-ad-dataset.ipynb` notebook to perform exploratory data analysis on the Instagram ad dataset. This notebook includes:
- Data cleaning and preprocessing
- Visualizations and insights

### **Fine-Tuning the Model**

Run the `finetuning-llama.ipynb` notebook to fine-tune the Llama model on the Instagram ad dataset. This notebook includes:
- Loading and preprocessing the dataset
- Setting up the model and tokenizer
- Fine-tuning the model with the dataset
- Saving the fine-tuned model

### **Generating Captions**

Run the `llama3-inference.ipynb` notebook to generate captions using the fine-tuned Llama model. This notebook includes:
- Loading the fine-tuned model and tokenizer
- Generating captions based on input prompts
- Example usage and testing


## **Example Usage**

### **Generating Captions**

Here are some example images demonstrating how to generate captions using the fine-tuned Llama model:


![image](https://github.com/geeeeenccc/Instagram-ad-caption-generation/assets/101811004/0030930e-94cb-4251-820d-575a20f42121)


![image](https://github.com/geeeeenccc/Instagram-ad-caption-generation/assets/101811004/6a35a7c3-32f3-4430-b687-868b1b3f06cf)

## **Conclusion and Possible Improvements**

### **Conclusion**
In this project, I tried to demonstrate the potential of using machine learning to generate creative and engaging captions for Instagram ads. By fine-tuning the Llama model on a dataset of Instagram posts, we can leverage the model's capabilities to understand and mimic the style of successful ad captions.


### **Possible Improvements**
* Dataset Advancement: We can keep increasing the size and diversity of the dataset, which can help improve the model's performance. Also, including more examples from various industries and languages can make the model more versatile.

* Hyperparameter Tuning and Model Optimization: Experimenting with different model architectures, hyperparameters, and fine-tuning techniques can lead to better performance.

* User Interface: We can develop a more user-friendly interface, potentially as a web application. Integration with platforms like Instagram for direct posting could also be explored(For example we can use [InstaPy](https://github.com/InstaPy/InstaPy), tool that automates IG interactions).

* Real-Time Data or Automated Scraping:  Let's say, automatically gathering new data periodically can help keep our dataset updated with the latest trends in Instagram advertising.
