# Peer-Graded Assignment: Part A - Building a dashboard with IBM Cognos Analytics 
**Estimated time needed:** 45 minutes

In this assignment, you will create some visualizations and add them to dashboards using IBM Cognos Analytics.

## Software Used in this Assignment
In this assignment you will use the free trial version of IBM Cognos Analytics Tool.

## Prerequisites

You need access to Cognos Analytics. This &lt;a href&#x3D;&quot;https://author-ide.skills.network/render?token&#x3D;eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJtZF9pbnN0cnVjdGlvbnNfdXJsIjoiaHR0cHM6Ly9jZi1jb3Vyc2VzLWRhdGEuczMudXMuY2xvdWQtb2JqZWN0LXN0b3JhZ2UuYXBwZG9tYWluLmNsb3VkL0lCTVNraWxsc05ldHdvcmstRFYwMTMwRU4tQ291cnNlcmEvbGFicy9fL2xhYnMvdjIvSGFuZHMtb25fTGFiJTNBX0dldHRpbmdfU3RhcnRlZF93aXRoX0NvZ25vc19BbmFseXRpYy5tZCIsInRvb2xfdHlwZSI6Imluc3RydWN0aW9uYWwtbGFiIiwiYWRtaW4iOmZhbHNlLCJpYXQiOjE3MDA2NzQ2OTF9.-8k2wp67jKc8W0wbRLVZq2evpcEZKKpnsxu-RSs4iCQ&quot; target&#x3D;&quot;_blank&quot;&gt;Cognos lab &lt;/a&gt; will guide to get your access to Cognos Analytics, and also get you started with how to use it to analyze the data.


## Dataset Used in this Assignment
The dataset you are going to use in this assignment comes from the following source: https://stackoverflow.blog/2019/04/09/the-2019-stack-overflow-developer-survey-results-are-in/ under a **[ODbL: Open Database License](https://opendatacommons.org/licenses/odbl/1-0/)**.

We are using a modified subset of that dataset for the assignment, so to follow the assigment instructions successfully, please use the dataset provided with the assignment, rather than the dataset from the original source.

## Guidelines for the Submission
1. Download the 2 files &lt;a href&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/LargeData/m5_survey_data_demographics.csv&quot; target&#x3D;&quot;_blank&quot;&gt;m5_survey_data_demographics.csv&lt;/a&gt; and &lt;a href&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/LargeData/m5_survey_data_technologies_normalised.csv&quot; target&#x3D;&quot;_blank&quot;&gt;m5_survey_data_technologies_normalised.csv&lt;/a&gt;. Upload these 2 CSV files as data assets to your project Cognos Analytics.

2. Create 3 dashboards **(3 separate tabs under a single dashboard)** as follows:

    - One dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to **Current Technology Usage**.

    - One dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to **Future Technology Trend**.

    - One dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to **Demographics**.

    &lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/labs/module%205/Peer%20Graded%20Assignment%20-%20%20Building%20a%20dashboard%20with%20Cognos%20Dashboard%20Embedded/images/2.png&quot; width&#x3D;&quot;533&quot; height&#x3D;&quot;300&quot;&gt;
        
&lt;br&gt;

3. On the **Current Technology Usage** dashboard tab, use the data asset **m5_survey_data_technologies_normalised.csv** and capture the following metrics as visualizations: 
    
    - In the first rectangle **(Panel 1)**:
        - Capture **Top 10 LanguageWorkedWith**. 
        - Visualize as a **Bar chart**.
        - Utilize **Bars**, **Length**, **Color** fields of Bar chart.
        - Include **Show value labels** feature.
        - Include a proper **Chart title**.  
        
    - In the second rectangle **(Panel 2)**:
        - Capture **Top 10 DatabaseWorkedWith**.
        - Visualize as a **Column chart**.
        - Utilize **Bars**, **Length**, **Color** fields of Column chart.
        - Include **Show value labels** feature.
        - Include a proper **Chart title**.

    
    - In the third rectangle **(Panel 3)**:
        - Capture **PlatformWorkedWith**. 
        - Visualize as a **Word cloud chart**.
        - Utilize **Words**, **Size**, **Color** fields of Word cloud chart.
        - Include a proper **Chart title**.
		


    
    - In the fourth rectangle **(Panel 4)**:
        - Capture **Top 10 WebFrameWorkedWith**.
        - Visualize as a **Hierarchy bubble chart**.
        - Utilize **Bubbles**, **Size**, **Color** fields of Hierarchy bubble chart.
        - Include a proper **Chart title**.

&lt;br&gt;

4. On the **Future Technology Trend** dashboard tab, use the data asset **m5_survey_data_technologies_normalised.csv** and capture the following metrics as visualizations: 
    
    - In the first rectangle **(Panel 1)**:
        - Capture **Top 10 LanguageDesireNextYear**.
        - Visualize as a **Bar chart**.
        - Utilize **Bars**, **Length**, **Color** fields of Bar chart.
        - Include **Show value labels** feature.
        - Include a proper **Chart title**.
    
    - In the second rectangle **(Panel 2)**:
        - Capture **Top 10 DatabaseDesireNextYear**.
        - Visualize as a **Column chart**.
        - Utilize **Bars**, **Length**, **Color** fields of Column chart.
        - Include **Show value labels** feature.
        - Include a proper **Chart title**.
    
    - In the third rectangle **(Panel 3)**: 
        - capture **PlatformDesireNextYear**.
        - Visualize as a **Tree map chart**.
        - Utilize **Area hierarchy**, **Size**, **Heat** fields of Tree map chart.
        - Include **Contrast label color** feature.
        - Include a proper **Chart title**.
    
    - In the fourth rectangle **(Panel 4)**:
        - Capture **Top 10 WebFrameDesireNextYear**.
        - Visualize as a **Hierarchy bubble chart**.
        - Utilize **Bubbles**, **Size**, **Color** fields of Hierarchy bubble chart.
        - Include a proper **Chart title**.

&lt;br&gt;

5. On the **Demographics** dashboard tab, use the data asset **m5_survey_data_demographics.csv** and capture the following metrics as visualizations:

   - Use **Filters for this tab** feature to filter out entries of other types except **Man** and **Woman** from the data point **Gender**.
    
    - In the first rectangle **(Panel 1)**:
        - Capture **Respondent classified by Gender**.
        - Visualize as a **Pie chart**.
        - Utilize **Segments**, **Size** fields of Pie chart.
        - Include **Dispay %** feature.
        - Include a proper **Chart title**.
    
    - In the second rectangle **(Panel 2)**:
        - Capture **Respondent Count for Countries**. 
        - Visualize as a **Map chart**.
        - Utilize **Regions-Locations**, **Regions-Location color** fields of Map chart.
        - Include a proper **Chart title**.
    
    - In the third rectangle **(Panel 3)**: 
        - Capture **Respondent Count by Age**.
        - Visualize as a **Line chart**.
        - Utilize **x-axis**, **y-axis** fields of Line chart.
        - Include **Show value labels** feature.
        - Include **Show markers** feature.
        - Include a proper **Chart title**.
    
    - In the fourth rectangle **(Panel 4)**:
        - Capture **Respondent Count by Gender, classified by Formal Education Level**.
        - Visualize as a **Stacked bar chart**.
        - Utilize **Bars**, **Length**, **Color** fields of Stacked bar chart.
        - Include **Show value labels** feature.
        - Include a proper **Chart title**.

&lt;br&gt;

6. To generate the GitHub link for the dashboard, please follow the instructions provided below:
    
    - On the application toolbar of your **dashboard page**, click **Share** icon.
	
		&lt;i&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/labs/module%205/Peer%20Graded%20Assignment%20-%20%20Building%20a%20dashboard%20with%20Cognos%20Dashboard%20Embedded/images/6.1_new.png&quot; height&#x3D;&quot;500/&quot;&gt;		
    &lt;br&gt;

    - Navigate to the **Export tab**, choose **Landscape** orientation, and click the **Export** button.

		&lt;i&lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/labs/module%205/Peer%20Graded%20Assignment%20-%20%20Building%20a%20dashboard%20with%20Cognos%20Dashboard%20Embedded/images/6.2_new.png&quot; height&#x3D;&quot;500/&quot;&gt;		
    &lt;br&gt;
	

    - To save your dashboard as PDF, select Destination as **Save as PDF**, and click **Save**.
	
	  &lt;img src&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/labs/module%205/Peer%20Graded%20Assignment%20-%20%20Building%20a%20dashboard%20with%20Cognos%20Dashboard%20Embedded/images/6.3_new.png&quot; height&#x3D;&quot;500/&quot;&gt;


   - Later upload the PDF file to GitHub by following the instructions in the reading &lt;a href&#x3D;&quot;https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Module2/GitHub1_Getting_Started.md.html?origin&#x3D;www.coursera.org&quot;&gt;Getting Started with GitHub &lt;/a&gt;.
   
	
   - Further in  the MySubmission tab of the assignment paste the GitHub  link of the Dashboard in the URL  textbox.

## Grading Information
For your assignment to be graded in a subsequent step in this module, you will be required to submit the permanent link of read-only view of the dashboard you got in Task 6.

&lt;ins&gt;The **main grading criteria** will be:&lt;/ins&gt;
- Have you provided GitHub link which opens your valid Cognos dashboard?
- Have the correct tabs been created?
- Have you created the required number of visualizations for each tab of the dashboard?
- Have you captured the correct metrics, chart types, chart features and titles for each visualization?
- Are the results correct?

&lt;ins&gt;You **will not be judged** on:&lt;/ins&gt;
- Your English language, including spelling or grammatical mistakes.

## Author(s)
- [Sandip Saha Joy](https://www.linkedin.com/in/sandipsahajoy/)


## &lt;h3 align&#x3D;&quot;center&quot;&gt; © IBM Corporation 2023. All rights reserved. &lt;h3/&gt;