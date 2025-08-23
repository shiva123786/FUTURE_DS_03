# Project: Student Event Feedback Analysis 📊

## Project Overview
This project addresses the challenge of making student feedback for college events meaningful and actionable. Using data from a Google Forms survey, I developed a complete analytics workflow to analyze satisfaction trends and provide clear recommendations for event organizers. This was a hands-on project that demonstrated key skills in data cleaning, NLP, and business reporting.

---

## Problem Statement
College events, such as tech fests and workshops, generate a large volume of student feedback. The goal of this project was to transform this raw survey data into strategic insights by answering the following questions:
* What is the overall level of student satisfaction?
* Which specific elements of the event (e.g., speakers, venue, organization) were most successful or problematic?
* How can we use this feedback to suggest concrete improvements for future events?

---

## Methodology
The analysis was performed in a **Google Colab** environment, ensuring a reproducible and shareable workflow. The steps included:
1.  **Data Collection & Cleaning**: I simulated data from a Google Forms export, including ratings and text comments. The data was cleaned to handle missing values and standardize text for analysis.
2.  **Quantitative Analysis**: I analyzed the numerical ratings (1-5 scale) to calculate the overall average satisfaction score and identify the most common rating.
3.  **Qualitative Analysis (NLP)**: I used the **NLTK VADER** library to perform sentiment analysis on the open-ended comments, classifying each as Positive, Negative, or Neutral.
4.  **Visualization & Reporting**: The findings were visualized using various charts (bar chart, pie chart, word clouds) and summarized in a mini-report that includes key recommendations.

---

## Key Findings & Recommendations
Based on the analysis, I was able to deliver the following insights to the event organizers:
* **High Overall Satisfaction**: The event had a high average rating of **4.25/5**, supported by a strong positive sentiment in the student comments.
* **Key Strengths**: Feedback analysis highlighted the **speakers** and **event organization** as the most successful aspects, suggesting a positive experience for most attendees.
* **Areas for Improvement**: The negative feedback pointed to specific logistical issues, including the **venue being crowded** and **long queues**. These are clear areas for improvement in future planning.

### Recommendations:
* **Replicate Success**: Continue to invest in high-quality speakers and maintain a well-organized event structure.
* **Address Logistics**: Investigate larger venues and implement a more efficient check-in process to enhance the attendee experience.
* **Encourage Specific Feedback**: Revise the survey to include more granular rating questions to gather precise insights on different event components.

---

### Student Satisfaction: Rating Analysis:
The quantitative analysis of the student ratings showed a high level of satisfaction. The average rating for the event was **4.25/5**, with a significant number of responses being a perfect 5. The bar chart below visualizes the distribution of these ratings.
<img width="849" height="577" alt="image" src="https://github.com/user-attachments/assets/98c381ea-d873-48b8-a7f4-de339fe1d853" />

## Tools & Libraries
* **Google Colab**: The online platform used for the analysis.
* **pandas**: For data manipulation and cleaning.
* **nltk.sentiment.vader**: The primary tool for sentiment analysis.
* **matplotlib / seaborn**: For creating visualizations.
* **wordcloud**: For generating word clouds to visualize key themes.

---

## Final Deliverables
* A clean, well-commented **Google Colab (.ipynb)** link showing the complete analysis.
* A mini-report summarizing all the key findings and recommendations.




