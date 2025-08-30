# Project Overview

This project was aimed at building a supervised ML pipeline through fine-tuning of a pretrained Transformer (DistilBERT) to classify Google location reviews into policy-driven categories (e.g., relevant, spam, ad, irrelevant, rant/no-visit).

# Setup Instructions

You don’t need to set up anything locally. To reproduce the results or use the pre-trained model, simply open the Jupyter Notebook on Google Colab through the steps below:

1. Download our latest release, along with the training and sample test datasets.
2. Open **Filtering_Reviews_Model.ipynb** on Google Colab.
3. Connect to a runtime environment.
4. Upload the training and sample test datasets to the current directory (/content/).
5. Run all the cells. 
6. The model will train itself with the training dataset. This process should take less than 5 minutes.
7. Once ready, proceed and go through the predict and count sections. Results will be printed to the screen.

# Data Files and API Key

We have uploaded the necessary data files that were scraped from Google using the Apify platform. However, due to privacy concerns, the API key used for scraping was not uploaded.

If you'd like to rerun the scraping process yourself, you can follow these steps:

1. Visit [Apify](https://www.apify.com/) and create an account if you don't have one already.
2. Once signed in, go to the [API key section](https://console.apify.com/actors?tab=recently-used) of your Apify account. 
3. Click on the **API** button on the top right corner and copy your API key to clipboard.
4. Open the notebook in Google Colab.
5. In the left panel, click on the **Secrets** button.
6. Click on **Add New Secret**.
7. Enable **Notebook Access**, then enter `APIFY_API_KEY` in the **Name** field and paste your API key in the **Value** field.

This will allow the notebook to access your API key and use it for replicating the scraping process.
