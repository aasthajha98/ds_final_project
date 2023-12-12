# An Analysis of Prejudiced Speech and Sports

## Description

As the influence of sports expands in society, we question if it also influences policy via a lens of prejudice. Preliminarily we study the effect of a specific team's success on prejudiced speech and identify flags for further research into political implications. In this research, we analyze how prejudice changes as the US Women's Team proceeds through four stages of the US FIFA Women's World Cup in 2023. Through sentiment analysis models hate comments and comments with high toxicity on YouTube videos are 1. identified at higher rates when the team loses and 2. lower rates as the team wins during the tournament.

## Data

* raw_data.csv 
    * Output of Data_Collection.ipynb
    * Collection of comments from Youtube videos of the first four games played by the USWNT in the 2023 FIFA World Cup
* data_w_roberta_score.csv
    * Output of Text_Analysis_Roberta.ipynb
    * Collection of comments and their respective Roberta Scores and Hate Speech classification 
* final_data.csv
    * Output of Text_Analysis_Perspective.ipynb
    * Collection of comments with roberta scores and perspective scores 

### Code 

* Data_Collection.ipynb 
    * Description: Code for scraping Youtube API and collecting video comments
    * Input: API Key
    * Output: raw_data.csv
* Text_Analysis_Roberta.ipynb
    * Description: Code for using the Roberta API to categorize hate speech 
    * Input: raw_data.csv
    * Output: data_w_roberta_score.csv
* Text_Analysis_Perspective.ipynb
    * Description: Code for using Perspective API to calculate Toxicity and Identity Attack Scores
    * Input: data_w_roberta_score.csv 
    * Output: final_data.csv
* Data_Visuailzation.ipynb
    * Description: Code for creating visualizations of comment characteristics,
    * Input: final_data.csv
    * Output:
        * Figure 1.1 Hate Comment Count
        * Figure 1.2 Hate Comment Share 
        * Figure 1.3 Comment Classification Count 
        * Figure 4.1 Word Cloud Hate 
        * Figure 4.2 Word Cloud Good 
* Data_Visualization_Perspective.ipynb
    * Description: Code for creating visualizations of replies and likes, and visualizations of toxicity scores and identity attack scores
    * Input: final_data.csv
    * Output:
        * Figure 2.1 Like Count 
        * Figure 2.2 Reply Count 
        * Figure 3.1 Toxicity Histogram 
        * Figure 3.2 Identity Attack Histogram 
        * Figure 3.3 Violin Plot Toxicity 

## Proposal

* Document detailing background information and our project proposal 

## Paper

* Final report detailing our methodology and our findings. 

## Figures 

* Figure 1.1 Hate Comment Count
* Figure 1.2 Hate Comment Share 
* Figure 1.3 Comment Classification Count 
* Figure 2.1 Like Count 
* Figure 2.2 Reply Count 
* Figure 3.1 Toxicity Histogram 
* Figure 3.2 Identity Attack Histogram 
* Figure 3.3 Violin Plot Toxicity 
* Figure 4.1 Word Cloud Hate 
* Figure 4.2 Word Cloud Good 



## Authors

* Aastha Jha: aj935@georgetown.edu

* Amelie D'Hers: ald152@georgetown.edu

* Sunaina Kathpalia: sk2307@georgetown.edu
