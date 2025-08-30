# Project Overview

This project was aimed at building a supervised ML pipeline through fine-tuning of a pretrained Transformer (DistilBERT) to classify Google location reviews into policy-driven categories (e.g., relevant, spam, ad, irrelevant, rant/no-visit).

# Setup Instructions

You don’t need to set up anything locally. To reproduce the results or use the pre-trained model, simply open the Jupyter Notebook on Google Colab through the steps below:

1. Click on the `filtering_reviews_model.ipynb` file in the repository.
2. Click on the **'Open on Colab'** button that appears at the top of the file.
3. Follow the instructions listed in the file.

# Data Files and API Key

We have uploaded the necessary data files that were scraped from Google using the Apify platform. However, due to privacy concerns, the API key used for scraping was not uploaded.

If you'd like to rerun the scraping process yourself, you can follow these steps:

1. Visit [Apify](https://www.apify.com/) and create an account if you don't have one already.
2. Once signed in, go to the [API key section](https://www.apify.com/settings) of your Apify account to retrieve your personal API key.
3. Open the notebook in Google Colab.
4. In the left panel, click on the **Secrets** button.
5. Click on **Add New Secret**.
6. Enable **Notebook Access**, then enter `APIFY_API_KEY_` in the **Name** field and paste your API key in the **Value** field.

This will allow the notebook to access your API key and use it for replicating the scraping process.
