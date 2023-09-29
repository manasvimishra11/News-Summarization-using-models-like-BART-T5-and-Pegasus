<h1>News-Summarization-using-models-like-BART-T5-and-Pegasus</h1>

This Python script is designed to automate the process of generating text summaries for a dataset of news articles and evaluating the quality of these summaries using various metrics. The script utilizes pre-trained language models, including BART, T5, and PEGASUS, for text summarization and calculates ROUGE scores, METEOR scores, and ROUGE-P scores to assess the performance of the summarization models.

<h2>Features</h2>

<h3>1. Data Loading </h3>The script provides functions to load news articles and their corresponding summaries from a specified dataset folder.

<h3>2. Text Summarization</h3> It uses three pre-trained models (BART, T5, PEGASUS) to generate summaries for randomly selected articles from the dataset.

<h3>3. Evaluation Metrics</h3> The script calculates the following evaluation metrics for each generated summary:

<li>ROUGE scores (ROUGE-1)</li>
<li>METEOR scores</li>
<li>ROUGE-P scores</li>
<h3>4. Dataset Analysis </h3>The script also performs basic analysis of the dataset, including word frequency analysis and summary length distribution visualization.

<h2>Usage</h2>
<li>Set the dataset_folder, news_articles_folder, summaries_folder, num_articles, and num_articles_to_select variables in the script to specify your dataset location and desired parameters.</li>

<li>Ensure you have the required Python libraries installed, such as Transformers, NLTK, Matplotlib, and WordCloud. You can install these libraries using pip install.</li>

<li>Run the script using a Python interpreter.</li>

<h2>Dependencies</h2>
The script relies on the following Python libraries and pre-trained models:

<li>Transformers (Hugging Face)</li>
<li>NLTK (Natural Language Toolkit)</li>
<li>Matplotlib</li>
<li>WordCloud</li>

Make sure to install these dependencies using pip install before running the script.

<h2>Results</h2>
The script will generate summaries for a random selection of articles and calculate average ROUGE scores, METEOR scores, and ROUGE-P scores for each of the three summarization models (BART, T5, PEGASUS). The results will be displayed in the console output.

<h2>Author</h2>
Manasvi Mishra & Aqsa Kazi
