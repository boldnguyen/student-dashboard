# Student-Dash 
A single page website has been built to showcase a data dashboard that analyses 1,000 students exam performance in Math, Reading & Writing. The dashboard is very important to understand how the students are performing, to determine best practices that can be shared with new students about to take the same exam and for teachers to help plan future curriculum. 

The page uses the D3.js library with the DC.js and crossfilter.js libraries to present the data via a series of scatter plots, pie charts, bar charts and line charts. The graphical arrangement has been designed allow the user to quickly understand a summary of student performance and then backed up with interesting data analysis to reach meaningful hypothesis. Furthermore, there is sufficient data to perform correlation testing to further understand the significance of the exam results.
 
Intriguingly, the user can opt to adapt their view of student data by all, individual or custom data element selection via dropdown list function. 

***
Link to the [live](https://boldnguyen.github.io/student-dashboard/ ) website hosted in GitHub Pages 

Link to [GitHub](https://github.com/boldnguyen/student-dashboard) Repo

***

![](static/images/student-image.jpg)

## Table of Contents

1. [UXD Considerations](#uxd-considerations)
    * [User & Business Objectives](#user-&-business-objectives) 
    * [Wireframes](#wireframes)
    * [User Stories](#user-stories)
    * [CSS Framework](#css-framework)
    * [Colour Palette](#colour-palette)
    * [Typography](#typography)
    * [Icon Graphics](#icon-graphics)
    * [Navbar Design](#navbar-design)

2. [Technologies Applied](#technologies-applied)
    * [Languages](#languages)
    * [Libraries](#libraries)
    * [Tools](#tools)

3. [Features](#features)
    * [Features left to implement](#features-left-to-implement)  

4. [Tests](#tests)

5. [Deployment](#deployment)
    * [How to run this project locally](#how-to-run-this-project-locally) 

6. [Credits](#credits)
    * [Content](#content)
    * [Media](#media)
    * [Assets](#assets)
    * [Acknowledgements](#acknowledgements)

## UXD Considerations
Student-Dash has been designed to allow the user to analyse student exam results data through selecting dropdown box options, hovering their cursor over data legend, clicking on charts or just observing the default data summary. 

Furthermore, the user is able to understand potential influences on exam results, such as gender participation, parental education, ethnic groupings, food consumption habits and students’ exam preparation.  

In summary, the user will have a good understanding of how all 1,000 students performed in their respective exams for Maths, Reading and Writing. The dashboard is both intuitive and interactive,  enabling the user to take full control of the source data via the carefully selected manual and automated navigation functions. 

### User & Business Objectives

#### User
- The user can access all the data via a single data dashboard
- To be able to view all data at the same time, across different graphical representations
- Commentary of the overall analysis to be clear and insightful
- Require the ability to drill down into the detail of the sample data through use of data filters
- To quickly establish any correlation in exam results for Math, Reading & Writing subjects

#### Business
- Produce a data dashboard that is generic in design and applies to diverse sample data sets 
- Dashboard must render on all available software platforms 
- Background imagery to support brand of business &/or learning organisations
- Dashboard has capability to work with API data
- Social media links access to further promote 'data-dashboard' products

#### Next Stage Generation
- Increase graphics density through creating a menu bar to allow user to select preferred graphical view
- Increase volume of API source data to increase data analysis capability and have results of analysis in a single view 
- Explore new social media channels to promote 'data-dashboard'

### User Stories
* It's important for a data set of 1,000 line items to be viewed from within a dashboard design
* The dashboard must be simple in design and intuitive to help with site navigation
* The dashboard to be viewed on a single page only
* A link to the source data is important
* User should be able to filter data with the use of a dropdown box tool
* View of analysis by gender, ethnicity, parents education, funded lunches and exam preparation is required
* Regression analysis on Math, Reading & Writing required to understand correlation in these subjects, when compared
* To understand the normal distribution curve through a plotted line graph for Math, Reading & Writing
* A reset filter button made available to return charts and graphs back to orignal position, following bespoke analysis activity

### CSS Framework
Bootstrap was the chosen framework for styling my project. I used the Bootstrap grid extensively to support responsiveness on mobile, tablet and desktop devices.

### Icon Graphics
Font Awesome 5 icon graphics were used in conjunction with Bootstrap 4, primarily to support information page footer & student gender population summary

Page                   | Function                | Font  
-----------------------|-------------------------|-------
index.html             | gender summary          | `fas fa-female`
index.html             | gender summary          | `fas fa-male`
index.html             | social media - footer   | `fab fa-github`
index.html             | social media - footer   | `fab fa-linkedin`    

### Navbar Design
For all device views, the navbar offers a blue navbar design, built up with 5 shades of blue to create a `linear-gradient` design, or tubuler effect. A reset button feature is positioned to the right of a headline narrative and is subject to a pseudo-hover class. The reset filter button changes colour upon the user hovering their cursor.   

## Technologies Applied
The following technologies were used in the design and build of this project.

### Languages
•	[HTML](https://html.spec.whatwg.org/multipage/) used as the markup language

•	[CSS3](https://www.w3.org/Style/CSS/) used to style the HTML

•	[JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) used mostly for DOM manipulation

### Libraries
•	[Font Awesome](https://fontawesome.com/) to provide the icon set for Re-Boot website

•	[Google Fonts](https://fonts.google.com/) provided the fonts `Open-Sans` & `sans-serif` used throughout the project

•	[jQuery](https://jquery.com/) is used to manipulate the DOM, for example buttons, and showing / hiding elements

•	[DC.js](https://cdnjs.cloudflare.com) is used to manipulate the DOM, for example buttons, and showing / hiding elements

•	[D3.js](https://cdnjs.cloudflare.com) is used to manipulate the DOM, for example buttons, and showing / hiding elements

•	[D3-queue.js](https://cdnjs.cloudflare.com) Primarily used to load the dataset fully before running any other files

•	[Crossfilter.js](https://cdnjs.cloudflare.com) Helped enable dynamic interaction of charts and data

•	[Bootstrap](https://www.bootstrapcdn.com/) to enable ease of website responsiveness and simplify coding structure

•	[Bootswatch](https://stackpath.bootstrapcdn.com/bootswatch/4.5.0/yeti/bootstrap.min.css) used to assist in the creation of the responsive grid structure for the site and also to provide some basic CSS styling



## Features
### Feature 1 - Enter button on homepage `index.html`

•   User is presented with an enter click button on homepage to enable navigation to the data dashboard

### Feature 2 - Headline title bar with reset data button

•	Headline bar informs signposts user to the dashboard and when clicked, the user will return to the top of the dashboard. In addition, a reset button is available for the user to click to return all data & charts to their default values

•	For ease of navigation, the headline bar is fixed at the dashboard top to help the user quickly find the rest button or automatically move to the top, whilst scrolling through to the bottom  

### Feature 3 - Introduction

•	Information to the user that provides a basic instruction on how to use the dashboard, brief background on data used and a link to source of original data sample via www.kaggle.com 

### Feature 4 - Filter by student

•	Single student exam performance can be reviewed by clicking on the ID code that appears in a dropdown box. Student ID range from 1 to 1000. Their respective exam performance can then be viewed in the array of graphical analysis

### Feature 5 - Filter by gender

•	Total student population contained within data sample can be viewed via a female / male lens. A dropdown box has been designed to create a filter on gender type, together with a total gender count

•   Furthermore, the user will receive an instant percentage split on gender activity, on both unfiltered and filtered data analysis    

### Feature 6 - Composite line graph 

•	Math, reading and writing exam results for 1,000 students appear in the form of a line graph. This chart can be viewed in multiple dimensions, depending on how the user has configured dropdown boxes and data filters. By hovering the cursor over the legend, the user will receive a bespoke view of a single subject. Furthermore, the user can hover over the data plot to understand an individual student exam score 

### Feature 7 - Scatter chart x3 

•	3 scatter plot charts have been designed to initiate regression analysis of all exam subjects. Combinations include math vs reading, reading vs writing & math vs writing. Again, these charts can be viewed in multiple dimensions, depending on how the user has configured dropdown boxes and data filters. The user will certainly get a quick and clear view of how the exam subjects correlate with each other 

### Feature 8 - Bar chart x2 

•	Ethnicity origin and the distribution over 5 groups’ is the focus of the 1st bar chart. The view of the chart can be altered by either clicking on a selected bar(s) &/or the user can configure the bar chart through work completed to configure other dropdown boxes and data filters

•	Parents educational background distributed over 6 levels of academia is the focus of the 2nd bar chart. The same functionality exists, as with 1st bar chart. The user can look to create some interesting data configurations to see if either ethnicity &/or students parental education has any bearing upon the students’ exam results  

### Feature 9 - Pie chart x2 

•	Lunch funding is the focus of the 1st pie chart. The influence of a standard lunch allowance or reduced/free lunch allowance can be evaluated by either clicking on a selected pie section(s) &/or the user can configure the pie chart through work completed to configure other dropdown boxes and data filters

•	Student preparation for their exams is the focus of the 2nd pie chart. The options are binary, either the student did or did not prepare for their exams. The same functionality exists, as with 1st pie chart. The user can look to create further interesting data configurations to see if either lunch funding &/or students exam preparation has any bearing upon the students’ exam results  

### Feature 10 - Collapse / re-open articles 

•	All articles can collapse and re-open, by clicking a blue chevron icon positioned at the top right corner of each article. The chevron becomes inverted upon collapse of the article 

•	Valuable screen space is freed up by closing articles that may not feature in a given data analysis configuration

### Feature 11 - Footer 

•	Provides a social media link to LinkedIn and a link to my GitHub page. Fonts (icons) secured from bootstrap / font awesome. The links are wired to the website designers’ respective social media sites. A `.hover` pseudo class has been used to provide a background colour change (white `#FFFFFF` to corporate colour code) and font colour change too.   

### Feature 12 - 404 alert page

•	Provides a friendly sign post for the user in the event an incorrect link has been clicked and the user has the option to click back into a correct link

### Features left to implement
#### Amalgamate graphs

•	Scatter plots to move from 3 to 1 by creating a dropdown box to control data plots on show, per exam subject. Bar chart & Pie Chart data to possible merge by creating bar charts with multiple axis. This will provide the user an increased richness of data analysis, through reduced number of graphs

#### Exam Performance Summary

•  	Automate an exam performance summary by publishing an overall average exam score, per subject and a score range, per subject. The scope can be increased by publishing individual student results, once the student selector dropdown box had been clicked and with crossfilter, the exam summary data could be viewed at a demographic level i.e. ethnicity, exam preparations, etc 



Special thanks to Matt Rudge, Timmy O'Mahony & Brian O'Grady (all Code Institute) for their time, training delivery and generating good confidence to coding.

*This is for educational use.* 
