# Paul Golder Data Analytics Idividual Formative assignement

**Data Analytics Idividual Formative assignement** is a jupyter notebook built to meet the requirements for the Individual Formative assignement as part of the Code Institute Data Analytics and AI Boot Camp.
# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* Dateset was obtained from Kaggle and was the [Retail Data Set](https://www.kaggle.com/datasets/manjeetsingh/retaildataset)
* As part of the project this was analysed and described.
* It started as 3 files - one of Weekly Sales data by store and department, another of Store size and classifications and a third outlining promotional discounts, CPI, Unemployment and Temperature.


## Business Requirements
* Descriptive Statistics: Display basic statistics such as average sales per store and department.  
* Trend Analysis: Plot sales trends over time for different stores and departments.  
* Impact Analysis: Visualise the impact of markdowns on sales during holidays versus non-holiday periods.  
* Comparative Analysis: Compare sales performance across different stores and regions.  


## Hypothesis and how to validate?
* Hypothesis -
1. Store Sales Varied by Size of store
2. Store were grouped into types based on an identifyable characteristic
3. Holiday Sales varied from Non-holiday sales
4. Total Sales were influenced by Markdown(discounted sales)

## Project Plan
* Project was managed using a github Kanban board
* [Link to Relevant Kanban board on github](https://github.com/orgs/Golder-Development/projects/1)
* Ideas and enhancements were added to the project plan and reviewed across the delivery with regards to deliverability. Some were then identified as potential future developments and enhancements

## The rationale to map the business requirements to the Data Visualisations
* Initially the aim of the visualisations was to help identify characteristic of the data that may support the hypothesis.
* Scatter graphs were used to look for corrollations 
* Line graphs were used to look at trends over time
* Bar graphs were used to look at the prevelance of different identifyable characteristics.
* Box and Whisker graphs were used to show the spread and relationships of results

## Analysis techniques used
* Data was reviewed for cleanliness, the degree of skew and kurtosis for major measures was calculated to provide the analyst with a top level understanding of the shape of the data.  This information would be more important if the project was to be moved forward to machine learning, as most data was not Normally distributed and would require transformations to improve modelling.
* Data analysis was started by looking at each of the core files provided to identify cleanliness of data, variability of measures and potential areas of commonality between Data sets. Following this data was combined based on learnings and summarised to Store level as although sales data was available at Department level the volume of departments (60-80) and lack of further distinguishing elements made informed learnings limited.  This was Highlighted as a future development opportunity.
* The Data had no regional element so no Geographical Analysis could be undertaken, the Unemployment, CPI and Temperature data was not used in analysis during this project and potentially present future opportunities for learnings.
* ChatGpt was used on several occasions to help error check code - usually with the request "Please identify what is wrong with this code" - the returned code was then reviewed and used.

## Unfixed Bugs
* Several early bugs occupied unnecessary effort and work rounds were implemented.  These were 
1. Using the kaggle API to directly import data and enable easy and speedy refresh - this was an aspect of data acquisition that had not previously been achieved and the decision was made this could be a future development option. Instead files were download, unzipped and uploaded into the IDE.
2. Issue syncing respository, due to an error of creating the project under a new personal organisation called "Golder-Development" rather than the developers personal "Hysnap" account several hrs were lost due to an inability to sync from GitPod to the new Organisation.  This was originally done with a view to making it more usable as an example of work for prospective employers. The work round implemented was to create a fork under the "Hysnap" account and sync to that and at project end copy the repository over to the new organisation for future sharing.
3. A desire to provide improved axis labels for colormaps was shelved as a future improvement after limited investigation.
4. The directory changing code at the top of the workbook led to several frustrating instances, so in the end it was hardcoded to the correct value to remove this issue.

## Development Roadmap
* The project lacked a clear understanding of the meaning of the data, for example were the department numbers unique per store or did a dept 72 at store 1 represent the same dept as the dept 72 at store 3.  
* The lack of clarity provided in the data documentation regarding the exact measure represented by MarkDown meant investigation into the scale of the measure and educated guesses had to be made wrt to its relevance.
* The Temperature, CPI and unemployment stat were also not clearly defined in the original documentation and had to be investigated.  They were and the decision to move their inclusion to future developments was made.
* I intend to improve my understanding of Plotly.express and look to focus more on Modules for analysis, during this project I did quite a bit of cut and pasting following by manual alteration, were in the future I wish to be creating modules that can be used to auto format and display visualisation.
* I would have liked to 

## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.

## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

## Acknowledgements (optional)
* I would like to thank Vazi and Niel for their support prior and during this project to improve my understanding.
* I would like to thank all members of the WMCA Data Analytics and AI cohort for their support and raising issues that have helped me understand better.
