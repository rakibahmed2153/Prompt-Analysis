AI Prompt Study Analysis

This repository contains the analysis of gender-based differences in prompt strategies in Generative Human-AI Interaction. The project includes data exploration, statistical analysis, and visualization of participant responses to better understand how prompt design and interaction strategies differ across groups.

📂 Project Structure

aiPromptStudyAnalysis.ipynb — Main Jupyter Notebook with data cleaning, exploratory data analysis (EDA), visualizations, and statistical testing.

responses.csv — Dataset of collected participant responses.

requirements.txt — List of dependencies required to run the notebook.

⚙️ Installation

Clone the repository and install dependencies in a virtual environment:

git clone https://github.com/yourusername/ai-prompt-study-analysis.git
cd ai-prompt-study-analysis

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows

# Install dependencies
pip install -r requirements.txt

🚀 Usage

Open Jupyter Lab or Notebook:

jupyter lab


Open aiPromptStudyAnalysis.ipynb.

Run the notebook cells to reproduce the analysis.

📊 Features

Data Cleaning & Preprocessing — Standardizes participant responses for analysis.

Exploratory Data Analysis (EDA) — Visualizations with Matplotlib, Seaborn, and WordClouds.

Statistical Analysis — Gender-based comparisons using scipy, statsmodels, and scikit-learn.

Natural Language Processing (NLP) — Sentiment analysis, lexical diversity, topic modeling (nltk, textblob, pyLDAvis, sentence-transformers).

Visualization Tools — Interactive plots and word clouds for insights.

📦 Requirements

The main Python dependencies include:

pandas, numpy, matplotlib, seaborn

scikit-learn, scipy, statsmodels

nltk, textblob, sentence-transformers, pyLDAvis, wordcloud, lexical_diversity, language-tool-python

jupyterlab for interactive notebook execution

(See requirements.txt for the full list.)

📑 Data

responses.csv: Raw participant responses used in the analysis.

Data preprocessing is handled inside the notebook.

⚠️ Note: The dataset may contain sensitive research data. Please handle with care according to ethical research guidelines.

📜 License

This project is licensed under the MIT License — see the LICENSE file for details.

✨ Acknowledgments

Research inspired by ongoing studies in Generative Human-AI Interaction.

Built with Python and open-source NLP/ML libraries.
