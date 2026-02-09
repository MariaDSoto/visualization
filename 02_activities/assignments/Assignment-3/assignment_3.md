# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
Option 1:
https://data.ontario.ca/dataset/ontario-public-library-statistics/resource/c264e3ff-b076-48bb-affd-c3597a416ee3
Option 2:
https://data.ontario.ca/dataset/ontario-public-library-statistics-all-population-groups/resource/700697ae-54bb-410c-98f3-39ca5ed06262

Figure 1: "Library_Engagement_GTA"

    > What software did you use to create your data visualization?
Python

    > Who is your intended audience? 
Library Stakeholders, so the intended use is for comparison and evaluation

    > What information or message are you trying to convey with your visualization? 
The goal is to compare and identify libraries that have a larger percentage of active cardholders in comparison to the total resident population they serve. 

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
I considered the following aspects for my design:
Aesthetic: I limited my figure to areas in the GTA to avoid overcrowding, I used the same font and different colours.
Substantive: I wanted to ensure that there weren't any areas that maybe had a larger percentage simply because it was a smaller community, which is why I listed the size of the resident population next to the name of each library
Perceptual: I hope that it is clear that I am trying to bring attention to the percentage of active users. I didn't overcrowd my figure my including the percentage of inactive users. 
Perceived factual basis by Kennedy et al. (2016), as I ensured to use a two-dimensiona image in a clean layout, i used a bar chart and included the data source on the bottom of my figure.  
I also did some adjustments to ensure accessibility

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
First, I used a tool that is reproducible, and I cited my source. I also included comments on my code. 
    
    > How did you ensure that your data visualization is accessible?  
I used colours based on the Viridis colour palette, I used Arial 12 as my font to ensure readability.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
The residents in the GTA area
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
I chose to limit my scope to the GTA area, as it is more densily populated and given the number of libraries available in the dataset I wanted to narrow my focus. Additionally, I considered 
that libraries outside the GTA may also be impacted by how accessible they are. 
    
    > What ‘underwater labour’ contributed to your final data visualization product?
The people that collected the data, those who are clearly maintaining it and updating the information. The people who manage to website. The people that created the packages I used to create the figure. 
From my side, I also had to transform and filter the data to fit my needs. 
- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
 
Figure 2: Typeof_Materials_Circulated_GTA

    > What software did you use to create your data visualization?
Python

    > Who is your intended audience? 
Library Stakeholders, so the intended use is for comparison and evaluation

    > What information or message are you trying to convey with your visualization? 
The goal was to compare the sort of materials that were most circulated per library. I specifically wanted to highlight the contrast between digital vs non-digital materials

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
I considered the following aspects for my design:
Aesthetic: I limited my figure to areas in the GTA to avoid overcrowding, I used the same font and different colours. I payed attention to the spacing between bars to ensure that the figure didn't look
too busy
Substantive: I turned my variables into percentages so that all libraries were easily observable, and the variables of interest were in a comparable scale.
Perceptual: There is a legend that clearly depicts what each bar means and the percentage y-axis is easily readable. 
Perceived factual basis by Kennedy et al. (2016), as I used a two-dimensional image in a clean layout, a bar chart and included the data source on the bottom of my figure.  
I also did some adjustments to ensure accessibility

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
First, I used a tool that is reproducible, and I cited my source. I also included comments on my code. 
    
    > How did you ensure that your data visualization is accessible?  
I used colours based on the Viridis colour palette, I used Arial 12 as my font to ensure readability.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
The residents in the GTA area. An interesting observation from both of my figures is that the library with the most active cardholders is also the one where
digital materials are circulated more often than physical ones. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
I considered the message I wanted to communicate, and knew that I wanted to limit the scope of the figure. Therefore, I focused on the GTA area. Additionally, as mentioned earlier I transformed my data to percentages
to communicate what I intended to. 
    
    > What ‘underwater labour’ contributed to your final data visualization product?
The people that collected the data, those who are clearly maintaining it and updating the information. The people who manage to website. The people that created the packages I used to create the figure. 
From my side, I also had to transform and filter the data to fit my needs. 
 
 
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
* Submission Due Date: `23:59 - 02/02/2026`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [X] Create a branch called `assignment-3`.
- [X] Ensure that the repository is public.
- [X] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [X] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
