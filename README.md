# Pospay Analysis

Welcome to the Pospay Analysis project! This project involves sentiment analysis of user reviews for the Pospay application, which was developed by Pos Indonesia. The data for this analysis was scraped from the Google Play Store using the Google Play Scraper library. Please leave your feedback [here](https://forms.gle/SZrjQDDvo4t45fFc9), so I could upgrade my knowledge and this project, thanks.

## Project Overview

The project includes the following steps and components:

- Data Collection: Scrapping user reviews data from the Google Play Store using the Google Play Scraper library.
- Data Selection: Randomly sampling the data for analysis.
- Data Exploration: Analyzing the dataset, checking for missing values, exploring columns, and understanding the data.
- Data Visualization: Creating visualizations to understand data trends.
- Time Series Analysis: Analyzing the daily review trends over multiple years.
- Score Comparison: Comparing user ratings and scores.
- Label Comparison: Comparing label counts.
- Sentiment Analysis: Performing sentiment analysis using Support Vector Machine (SVM) classification.
- Model Evaluation: Evaluating the SVM model using confusion matrix.
- Word Cloud Visualization: Creating word clouds from cleaned reviews data.

## Challenges Faced

During the course of this project, I encountered several challenges that tested my problem-solving skills and determination:

1. **Manual Labeling:** One of the significant challenges I faced was the manual labeling of the data. I chose not to use automated labeling tools for specific reasons. This decision was driven by the following considerations:

    - **Precision and Control:** Manual labeling allowed for a higher degree of precision and control over the labeling process. 

    - **Data Quality:** Automated labeling tools may not always capture the subtleties and complexities of human language.
      
    - **Limited Dataset Size:** Since the dataset was relatively small due to sampling, manual labeling was feasible and provided an opportunity for a thorough examination of each review.

    - **Challenges and Limitations:** However, manual labeling was not without its challenges. Some of the limitations and difficulties I encountered included:
        - **Time-Consuming:** The manual labeling process was time-consuming and it required careful attention to detail.
        - **Subjectivity:** Labeling sentiment is subjective, and different individuals may interpret reviews differently. To mitigate this, I maintained consistency in labeling by adhering to predefined criteria.

2. **Custom Stopwords and Normalization Dictionary:** To ensure the data was as clean as possible, I created custom resources, including a stopwords list and a normalization dictionary. These resources were used to enhance data quality:

    - **Stopwords List:** The custom stopwords list helped remove common words that do not carry significant meaning in the analysis. However, curating the list involved thorough research and consideration of context to ensure relevant stopwords were included.

    - **Normalization Dictionary:** The normalization dictionary contained mappings for common variations of words, such as slang or abbreviations, to their standardized forms. This step aimed to improve the consistency of the text data.

Despite these challenges and the additional effort required for manual labeling and resource creation, I believe that overcoming them contributed to the robustness and accuracy of the sentiment analysis in this project. It also reinforced the importance of manual curation and customization in natural language processing tasks.

## Jurnal Publication

The sentiment analysis of the Pospay application was published in a journal titled "ANALISIS SENTIMEN ULASAN APLIKASI POSPAY DENGAN ALGORITMA SUPPORT VECTOR MACHINE," which can be accessed [here](https://ejournal.upbatam.ac.id/index.php/jif/article/view/6611).

## Acknowledgments

I would like to express my gratitude to my mentor, Mr. Taufik Ridwan, for his invaluable guidance and support throughout this project.

## Contact Information

- LinkedIn: [Dea Safryda Putri](https://www.linkedin.com/in/dea-safryda-putri-b5ab58231/)
- Email: deasafrydaputri@gmail.com
- Instagram: [dsafryda_](https://www.instagram.com/dsafryda_/)

## How to Access and Collaborate

To access or collaborate on this project, you can make a copy of it by following these steps:

1. Fork this repository by clicking the "Fork" button at the top-right corner of the page.
2. Clone your forked repository to your local machine.
3. Make changes, contributions, or improvements as needed.
4. Push your changes to your forked repository.
5. Create a pull request to propose changes to the original repository.

If you have any questions or inquiries related to this project, please feel free to reach out to me through LinkedIn, email, or Instagram.

Thank you for your interest in the Pospay Analysis project!
