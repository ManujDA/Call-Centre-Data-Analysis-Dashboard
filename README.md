
# Call Centre Data Analysis Dashboard

This project involves developing a Power BI dashboard for a telecom call centre to visualise and analyse operational performance. The primary goal is to deliver actionable insights that drive improvements in customer satisfaction, agent productivity and overall efficiency.


## How to Use the Dashboard
1. Download the Power BI `.pbix` file from the repository.
2. Open the file in Power BI Desktop.
3. Use the interactive filters to explore metrics by agent, time or call topic.
4. Analyse the visuals to identify trends and actionable insights.

## Stakeholder Requirements
The stakeholders outlined the following objectives for the dashboard:
   - Measure overall customer satisfaction levels.
   - Track total calls answered, abandoned and missed.
   - Analyse call durations and average speed of answer.
   - Assess agent performance through metrics such as calls answered, average handle time and issues resolved.
   - Identify trends in calls by time and topics.
   - Visualise call distributions and peak periods.
   - Provide insights to improve service quality and operational efficiency.

## Measures
The following measures were implemented using calculated metrics to derive meaningful insights:

1. **Total Calls Answered (%)**:
   - Calculated as the ratio of answered calls to the total number of calls received, providing insight into service efficiency.

2. **Calls Answered**:
   - A count of calls successfully handled by agents, highlighting operational effectiveness.

3. **Calls Missed**:
   - Tracks the number of calls not answered, signalling potential resource gaps or inefficiencies.

4. **Issues Resolved**:
   - Reflects the total number of customer issues successfully addressed, measuring agent productivity and problem resolution capacity.

5. **Month Name**:
   - Extracted from call timestamps to categorise and analyse trends over time, supporting seasonal or monthly performance evaluations.

## Dashboard Features and KPIs

![Call_Center](https://github.com/user-attachments/assets/5f34199b-7e45-46be-afae-2e1dbe51f6b1)

1. **Overall Performance Metrics**:
   - Total calls: 5,000
   - Calls answered: 4,054
   - Issues resolved: 3,646
   - Average answer speed: 67.52 seconds
   - Average call duration: 224.92 seconds

2. **Agent Performance Quadrant**:
   - Comparison of agents based on calls answered, issues resolved and average handle time.

3. **Call Analysis**:
   - Call distribution by time, topics and agents.
   - Identification of high-traffic periods and popular call topics.

4. **Customer Satisfaction**:
   - Overall rating of 3.4 out of 5.

5. **Visual Elements**:
   - Interactive bar charts for agent and topic analysis.
   - Time-series graphs to track call trends throughout the day.
   - Pie chart for call distribution.

## Insights
   - Jim resolved the most issues, making him a top performer.
   - Diane missed the most calls, highlighting a need for additional support or training.
   - "Streaming" and "Payment-related" calls are most frequent, indicating these areas may need enhanced support materials.
   - An overall satisfaction score of 3.40 suggests room for improvement, particularly in speed and resolution efficiency.
   - Peak call volumes occur mid-day, suggesting a need for increased staffing during these hours.

## Recommendations 
   - Provide additional training for agents with higher missed calls or lower issue resolution rates.
   - Introduce mentoring programs where top-performing agents like Jim can guide others.
   - Increase staffing during mid-day peak hours to handle higher call volumes effectively.
   - Reallocate resources to ensure balanced workloads across agents.
   - Develop targeted FAQs and scripts for frequent topics like "Streaming" and "Payment-related" issues.
   - Implement knowledge bases and AI-driven chat assistants to assist agents and customers.
   - Regularly gather and analyse customer feedback to identify pain points and opportunities for improvement.
   - Use feedback to refine training programs and operational strategies.
   - Use predictive analytics to forecast call volumes and adjust staffing dynamically.
   - Implement tools to monitor and reduce average answer and handle times.

## License
This project is licensed under the MIT License.
