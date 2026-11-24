# Grammy Categories: What the Nomination Record Says About Restructuring

A data storytelling project built for a business audience: the Recording Academy's Awards & Categories Committee, deciding whether and how to restructure Grammy categories again after the 2011 cut from 109 to 78.

**[View the full notebook with all charts](https://GH_USER.github.io/grammy-categories-data-visualisation/)**

## Business question

Is the Grammy category structure still growing, or has it stabilised since 2011, and which categories, genres and artists should the Committee weigh most heavily in its next review?

## Approach

- **Data:** [Grammy Awards dataset on Kaggle](https://www.kaggle.com/datasets/unanimad/grammy-awards), 4,810 nomination records from 1958 to 2019
- Data inspection, cleaning and a validation checkpoint before any insight is reported
- Every chart follows a consistent design system based on Knaflic's *Storytelling with Data* principles

## Insights

1. Category count has been climbing again since the 2011 cut.
2. Category naming churn in the 2010s is back above its 2000s low, echoing the pattern before the last review.
3. Missing artist data is structural (craft and technical categories), not random.
4. The genre mix has shifted: rap and hip-hop categories are rising, classical is falling.
5. A small group of acts dominates nomination volume.
6. Versatility (distinct categories per artist) tells a different story from volume. Beyoncé leads with 10 distinct categories.

**Recommendation:** a standing category review every 3 to 5 years instead of one-off corrections, using category churn as the trigger, genre allocation as the rebalancing lens and artist versatility as the guide for consolidated categories.

## Tech stack

Python, pandas, NumPy, Matplotlib

## Notes

The dataset is not included in this repo; download it from the Kaggle link above.
Completed as an individual project for M512 Data Visualisation & Communication, MSc Data Science, AI and Digital Business, Gisma University of Applied Sciences.
