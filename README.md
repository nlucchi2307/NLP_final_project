# NLP_final_project

# 📣 Sentiment vs. Statistics: Presidential Rhetoric and the Economy

**Does U.S. presidential rhetoric follow real economic trends or political strategy?**  
This project combines sentiment analysis, economic indicators, and machine learning to explore how presidential speeches relate to macroeconomic conditions.

## 📚 Overview
- We analyze U.S. presidential speeches (1789–2025) and test whether their tone reflects real economic conditions.
- Economic data includes GDP, unemployment, inflation, and consumer sentiment (FRED & University of Michigan).
- We build a custom **Economic Health Index** and compare it to **Presidential Sentiment Scores**.

## 🛠 Methods
### 🔤 Text Mining
- Preprocessing: tokenization, lemmatization, stopword removal
- Sentiment analysis and emotion tagging (optimism, concern, etc.)
- Word clouds and Flesch readability index to track rhetorical changes over time

### 📊 Economic Comparison
- Built a composite index of economic health using scaled GDP, unemployment, and inflation
- Compared presidential tone with consumer sentiment and economic reality
- Calculated correlations and visualized divergences across key historical periods

### 🌳 Machine Learning
- Decision tree models to classify speech framing (e.g., crisis, leadership)
- Models trained on:  
  - Textual features only (1789–2025)  
  - Text + economic indicators (1950–2024)
- Accuracy dropped when adding economic variables → speech tone is largely independent of economic conditions

## 💡 Key Findings
- Presidential rhetoric remains **consistently optimistic**, with **little correlation** to economic reality
- **Public sentiment tracks the economy**, not political tone
- Economic indicators added **noise** to the classification model, reducing performance

## 📂 Files
- `speeches_scraping.ipynb`: scraping presidential speeches, 
- `speeches_analysis.ipynb`: preprocessing, sentiment scoring, analysis of economic indicators


## 👥 Authors
Text Mining Final Paper @ BSE (2024-2025)  
Maria Aleman, Marta Sala, Noemi Lucchi
