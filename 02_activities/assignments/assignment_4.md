# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
 
 
  Please find below link to dataset used
  Ontario consumer price index
  Ministry: Agriculture, Food and Rural Affairs 
  https://data.ontario.ca/dataset/29a55543-3e27-4d7a-8ce5-7b669305b2d8/resource/cfeca07a-7752-4e54-b109-fe20467413a2/download/cpi.xlsx
  The Consumer Price Index measures changes in the cost of selected food items over time like: food purchased from stores fresh or frozen beef fresh or frozen pork fresh or frozen chicken... 
    
    
    > What software did you use to create your data visualization?
 - I did all visualizations in Python only. I made three different vizualizations.
 
    > Who is your intended audience? 
 - Intended audience could be government officials and/or ontario residents who will review and decide on future actions.

    > What information or message are you trying to convey with your visualization? 
 - Trends of the CPI over time 1979-2023 showing a consistent increase in CPI.
 
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
 - Substantive: Clearly showing the trend over time with minimal distractions. No Chartjunk and focus on temporal trends.
 - Perceptual: Using distinct colors for different categories ensures visual clarity.
 - Aesthetic: The charts are clean and simple showing both axes, gridlines, title and legend. Minimalistic charts with clean lines following design consistency.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
 - I have used widely available Python libraries like Matplotlib and Seaborn. As teh code is shared in markdown file it ensures code transparency and reproducibility.

    > How did you ensure that your data visualization is accessible?  
 - Inclusive color schemes with good contrast
 - Readable text
 - Well placed legend.

    > Who are the individuals and communities who might be impacted by your visualization?  
 - The visualizations provide insights into CPI trends in Ontario for economic decision-making. By clearly displaying historical CPI data the charts support informed discussions on economic policies.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
 - The 'Date' and 'CPI' data was used as the primary attributes to show the trend of CPI over time. This feature selection ensured the visualization shows the time-series data relevant to the analysis.

    > What ‘underwater labour’ contributed to your final data visualization product?
 - The underwater labour involved preparing the dataset, coding the chart, and fine-tuning
 - Data Cleaning: First, we had to clean the data. This involved removing any irrelevant rows or columns and ensuring that only the necessary data points were used. 

 - Data Filtering: Then I filtered the data to include only the relevant columns for plotting.

 - Chart Customization: Once the data was prepared I customized the chart to enhance its readability and visual appeal.

    - Choosing color schemes that are accessible to all types of individuals.
    - Setting options for font size, color, and style to make the chart’s labels and legend easy to read.
    

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
