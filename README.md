# Applicant Behavior Analysis — Internee.pk

## Objective
Enhance the user experience by analyzing how applicants interact with 
Internee.pk's application process, identifying drop-off points to improve 
conversion rates.

## Project Summary
Simulated 50 applicant sessions through a 5-stage application funnel 
(Landing Page → Clicked Apply → Started Form → Uploaded Resume → Submitted) 
and analyzed conversion and drop-off rates at each stage using Python (pandas).

## Key Insights
- Overall conversion rate from landing page to submission: 22%
- Biggest bottleneck: 48% of applicants who started the form dropped off 
  before uploading their resume — the largest percentage loss of any stage
- 28% of visitors never clicked "Apply" after landing on the page

## Recommendation
Prioritize simplifying the resume upload process (e.g., clearer file 
requirements, progress indicators) to reduce the largest point of friction 
and improve the overall 22% conversion rate.

## Tools Used
Excel (data prep), Google Colab, Python, pandas, Matplotlib

## Files
- `user_behavior_data.csv` — raw simulated session data
- `user_behavior_analyzed.csv` — data with exit point analysis
- `funnel_analysis_results.csv` — stage-by-stage funnel summary
- `user_behaviour.png` — funnel visualization
- `user_behaviour_ipyng.ipynb` — notebook with code and analysis
