# FUTURE_DS_03
# College Event Feedback Analysis
## **Project Overview**
The goal of this project is to:
- Collect student feedback on college events (seminar, workshop, cultural, sports) using Google Forms.
- Analyze quantitative and qualitative data.
- Visualize insights using charts and word clouds.
- Use sentiment analysis to understand student opinions and suggestions.

## **Data Collection**
- Feedback collected through a **Google Form**.
- Number of responses: ~50–60.
- Questions included:
  - Department
  - Year of Study
  - Event Type
  - Overall Rating
  - What did you like about the event?
  - What can be improved in future events?
  - Would you recommend this event to others?

**Google Form Link:**  
[Click here to open the Feedback Form](https://docs.google.com/forms/d/e/1FAIpQLSd1Vb_ktkC7AuczObOSx5UiYJ4X75AQljlFZhnK6dXTKhfsZg/viewform?usp=header)

## **Tools & Libraries Used**
- **Google Forms** – For data collection
- **Google Colab** – For Python analysis
- **Python Libraries**:
  - `pandas` – Data cleaning and manipulation
  - `seaborn` / `matplotlib` – Data visualization
  - `textblob` / `VADER` – Sentiment analysis
  - `wordcloud` – Visualize common words
    
## **Project Steps**
1. Exported Google Form responses as CSV.
2. Uploaded CSV to Google Colab.
3. Cleaned and standardized data columns.
4. Handled missing values.
5. Performed sentiment analysis on textual feedback.
6. Created visualizations:
   - Department-wise responses
   - Event Type distribution
   - Average rating per event type
   - Recommendation analysis
   - Likes and improvements word clouds
7. Saved cleaned dataset and charts for presentation.

## **Key Insights**
- Highest-rated event type: **Cultural events**
- Most liked aspects: organization, engagement, fun activities
- Common improvements: better time management, more interactivity
- High recommendation rate → overall satisfaction is good
- Sentiment analysis helps highlight what students liked and areas for improvement.
  
## **Project Files**
- `College_Event_Feedback_Analysis.ipynb` → Google Colob notebook with analysis
- `College_Event_Feedback_Cleaned.csv` → Cleaned dataset
- `Feedback_Form_Link.md` → Google Form link
- Charts / WordCloud images → optional folder for visualizations
  
## **Conclusion**
This project demonstrates a **data-driven approach to evaluating college events**.  
It combines **quantitative ratings**, **qualitative feedback**, and **sentiment analysis** to provide actionable insights.


A data driven project that analyzes student feedback from Google Forms to uncover satisfaction trends. It uses Sentiment Analysis and Statistical Visualization to transform raw survey cooments into actionable improvements for future college events.
