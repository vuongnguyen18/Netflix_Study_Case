# NETFLIX TV SHOWS AND MOVIES ANALYSIS

**Data & Strategy Analysis**

**By: Vương**

![Netflix Banner](images/banner.png)

---

## PROJECT PURPOSE

As a competitor to Netflix, I firmly believe that understanding their trends in movies and series is crucial to understanding their customers. Netflix has its own dedicated Data Department to execute and secure its dominance in the minds of viewers. Therefore, analyzing their content over the years can provide valuable insights into their strategy and customer preferences.

---

## TABLE OF CONTENTS

### Short-Term Strategy
- Content Type Distribution
- Content Growth Trends
- Key Directors and Genres (Figures 1–4)
- Top Casts and Audience Appeal (Figure 5–6)

### Next Few Years Strategy
- Director-Genre Alignment (Figure 7)
- Cast-Genre Alignment (Figure 8)
- Time Gap Reduction Strategy (Figure 9–10)
- Duration Analysis
- Movie Length and TV Show Seasons (Figure 11–12) trend Over Years

### Long-Term Strategy
- Focus on Underserved Markets
- Collaborate with Local Directors
- Explore Niche Genres (Figure 13–14)
- Time Series Analysis
- Monthly/Yearly Content Trends (Figure 15)

### Recommendation System
- TF-IDF Content-Based Filtering
- Embedding-Based Semantic Filtering

---

## SHORT-TERM STRATEGY

Movies dominate Netflix's overall content library, comprising **69.6%**, while TV shows account for **30.4%**. In the initial stage, we can acquire the copyrights for movies and TV shows following a similar ratio to ensure we secure a portion of Netflix's market share across both content types.

**Figure 1. Distribution of Content Types on Netflix**  
![Figure 1](images/fig1_content_type.png)

Although movie production increased significantly—especially between 2016 and 2019—it also experienced a sharp decline after 2020. In contrast, TV show production has shown more stable and steady growth over time.

By investing in both movies and TV shows, we can balance rapid growth potential with long-term stability, reducing overall risk.

**Figure 2. Content Type Trends**  
![Figure 2](images/fig2_trends.png)

---

## INITIAL APPROACH

**Figure 3. Top 15 Directors by Number of Titles Produced**

| ID | Name                  | Count | Country         |
|----|-----------------------|-------|-----------------|
| 0  | Rajiv Chilaka         | 19    | India           |
| 1  | Raúl Campos           | 18    | Mexico          |
| 2  | Marcus Raboy          | 16    | United States   |
| 3  | Suhas Kadav           | 16    | India           |
| 4  | Jay Karas             | 14    | United States   |
| 5  | Cathy Garcia-Molina   | 13    | Philippines     |
| 6  | Martin Scorsese       | 12    | United States   |
| 7  | Jay Chapman           | 12    | United States   |
| 8  | Youssef Chahine       | 12    | Egypt           |
| 9  | Steven Spielberg      | 11    | United States   |
| 10 | Don Michael Paul      | 10    | United States   |
| 11 | David Dhawan          | 9     | India           |
| 12 | Troy Miller           | 8     | United States   |
| 13 | Yılmaz Erdoğan        | 8     | Turkey          |
| 14 | Quentin Tarantino     | 8     | United States   |

**Figure 4. Top 15 Popular Genres of 2021**  
![Figure 4](images/fig4_top_genres.png)

---

## TOP CASTS

**Figure 5. Top 15 Casts by Number of Titles Attended**

| ID | Cast                  | Count | Country                  |
|----|-----------------------|-------|--------------------------|
| 0  | Anupam Kher           | 43    | India                    |
| 1  | Shah Rukh Khan        | 35    | India                    |
| 2  | Julie Tejwani         | 33    | India                    |
| 3  | Takahiro Sakurai      | 32    | Japan                    |
| 4  | Naseeruddin Shah      | 32    | India                    |
| 5  | Rupa Bhimani          | 31    | India                    |
| 6  | Akshay Kumar          | 30    | India                    |
| 7  | Om Puri               | 30    | India                    |
| 8  | Yuki Kaji             | 29    | Japan                    |
| 9  | Amitabh Bachchan      | 28    | India                    |
| 10 | Paresh Rawal          | 28    | India                    |
| 11 | Boman Irani           | 27    | India                    |
| 12 | Rajesh Kava           | 26    | India                    |
| 13 | Vincent Tong          | 26    | Hong Kong, Canada, US    |
| 14 | Andrea Libman         | 25    | United States, Canada    |

**Figure 6. Audience Category Distribution**  
![Figure 6](images/fig6_audience.png)

---

## NEXT FEW YEARS STRATEGY

**Figure 7. Most Popular Casts Team**  
![Figure 7](images/fig7_cast_genre.png)

---

## TIME GAP ANALYSIS

**Figure 8. Audience Category Over Years**  
![Figure 8](images/fig8_audience_over_years.png)

---

## DURATION ANALYSIS

**Figure 9. Duration (Movie) and Seasons (TV Show) Distribution**  
![Figure 9](images/fig9_duration.png)

**Figure 10. Duration (Movie) and Seasons (TV Show) Over Years**  
![Figure 10](images/fig10_duration_over_years.png)

---

## LONG-TERM STRATEGY

**Figure 11. Netflix Product Distribution**  
![Figure 11](images/fig11_product_distribution.png)

**Focus on Underserved Markets**  
**Collaborate with Local Directors**

**Figure 12. Bottom 15 Popular Genres on Netflix**  
![Figure 12](images/fig12_bottom_genres.png)

**Figure 13. Bottom 15 Genres Trends on Netflix**  
![Figure 13](images/fig13_bottom_genres_trends.png)

**Explore Niche Genres**: Experiment with underrepresented genres to differentiate our content offering.

---

## TIME SERIES ANALYSIS

**Figure 14. Month and Year Added Heatmap**  
![Figure 14](images/fig14_heatmap.png)

**Monthly Peaks**:  
- July – highest in 2020 (257 titles)  
- December – consistently high across 2018–2020  
- October and November – also strong, especially in 2019

**Recommendation**: Plan major releases between July and December.

---

## RECOMMENDATION SYSTEM

**Overview of 2 Recommendation Systems:**

- **TF-IDF Content-Based Filtering**: Simple keyword-based similarity.
- **Embedding-Based Semantic Filtering**: Uses SentenceTransformer for deeper semantic understanding.

**Figure 16. Example of Recommendation Return**  
![Figure 16](images/fig16_recommendation.png)

We’ll start with a basic recommendation system to suggest popular and similar content to users. Over time, we plan to make it more advanced and accurate by using user behavior, viewing habits, and smarter algorithms.

---

**Dataset**: `netflix_data_study_case.csv` (8,807 titles)  
**Tools used**: Python, pandas, matplotlib, seaborn  
**Analysis date**: March 2026

**Ready to compete.**  
Made with ❤️ by Vương
