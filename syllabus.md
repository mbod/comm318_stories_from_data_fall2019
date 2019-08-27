## COMM318: _Stories from data_: Introduction to programming for data journalism

**Fall 2019: T/Th 12:00-1:30pm**  
**Room: 108 ASC**  

**Professor**: Dr. Matt O'Donnell
**Email**: mbod@asc.upenn.edu
**Office hours**: ASC 404 **Wed 1-2pm & Thur 11-12**

**TA**: Roopa Vasudevan
**Email**: roopa.vasudevan@asc.upenn.edu

**Doctoral student assistant**: Jennifer Henrichsen
**Email**: jennifer.henrichsen@asc.upenn.edu


## Course Description, Goals and Objectives

Today masses of data are available everywhere, capturing information on just about everything and anything. Related but distinct data streams about newsworthy events and issues -- including activity from social media and open data sources (eg: The Open Government Initiative) -- have given rise to a new source for and style of reporting sometimes called Data Journalism. Increasingly, news sites and information portals present visually engaging, dynamic, and interactive stories linked to the underlying data (e.g. The Guardian DataBlog, LA Times Data Desk). This course offers an introduction to Python programming for data analysis and visualization. Students will learn how to collect, analyze, and present various forms of data. Second, because numbers and their visualizations do not speak for themselves but require context, interpretation, and narrative, students will practice making effective stories from data and presenting them in blogs, articles and other formats. 

No prior programming experience is required. Through this course students will gain skills writing Python programs to handle large amounts of data and become familiar with some of the key techniques used by data scientists, which is currently one of the most in-demand jobs.

* This course will provide an introduction to Python programming for collecting, cleaning, describing and analyzing a range
of publicly available datasets, including demographic (e.g., age, race, education levels by geographic area),
medical (e.g. vacination, ER intakes for certain conditions like flu, measles, etc),
financial (e.g., spending on infrastructure, education, other initatives, income distribution, etc.), event (e.g., crime data, road accidents) and
transportation (e.g., usage statistics for public transportation and private schemes, e.g. bike shares).

* Each week one session will be in lecture form and provide background for the theory and techniques and the second will be a lab session
in which students will work through programming exercises using Jupyter notebooks (a web-based programming environment well suited for data science and class-based assignments).

* By completing this course students will:
	* gain an understanding of how data can be used to support the reporting and making of news and other types of storytelling
    * practice skills of making stories by collecting, transforming, visualizing and analyzing publicly available data
	* explore the range of various kinds of data now available through initiatives such as Open Government Data initiative (data.gov) and a range of other available and curated data archives
	* be exposed to a range of techniques from data journalism, data science and information visualization and understand how they can be used to tell news/media stories
	* gain a basic level of programming proficiency in the Python programming language and have completed a number of programming exercises to collect, clean, analyze, visualize and interpret such data

## Resources

* Readings on data journalism and resources for learning Python programming and data analysis will be made available on the class Canvas site and the course github repository.


## Assessment


1. **Peer graded reviews of data journalism examples (10%)**
    * A series of data driven articles and associated data repos will be assigned for evaluation and group discussion during lab sessions. You will be asked to write a short response to each which will be graded by others in your group.
2. **Attend weekly lab sessions and complete the assigned readings and exercises (40%)**
    * Thursday class sessions will usually be programming labs. Students are required to bring a laptop that can connect to the ASC network. Please contact the me if this is difficult and we can see if a machine can be made available for use in lab.
	* We will be using Jupyter notebooks to learn Python, which are part of a web-based interactive programming environment. You must have a github account to access the server. If you do not have an account go to https://github.com/join and set one up. Assignments will be completed in this environment and submitted to the instructor. Details of using this system for assignments will be covered in the first lab session.
	* Assignments will usually be due at 5pm on the Tuesday following lab session (but this may vary). These assignments are intended to help students practice the programming concepts and structures introduced in lab and build confidence. They should not be difficult or take excessive time but they do build from week to week so it is _very_ important to keep up.
3. **Complete a project that uses the techniques and theory covered in class to carry out a data analysis of a specific research question agreed upon with the instructor (50%)**
    * The goal of this project is to create:
        1. an engaging data-driven online article 
        2. a data and analysis repository on `github.com`  

      similar those produced by data journalists (e.g. the `LA Times Data Desk`), for example:
      * github repo: https://github.com/datadesk/notebooks
      * article: https://www.latimes.com/local/lanow/la-me-ln-homeless-housing-hhh-20190320-story.html
          

    * The steps in the project are:
    
         1. Decide upon a tractable research question that involves analysis of available data sources (e.g. data.gov)
           
         2. Identify, retrieve and prepare relevant data

         3. Explore, describe and analyze the dataset
      
         4. Visualize data
            
         5. Setup a github repository to make your data and analysis publicly available

         6. Interpret findings

         7. Write a web-based article to communicate the stories discovered in your data


       These steps will be scheduled throughout the course allowing for the instructor to help you find a manageable problem, acquire the necessary data and be able to carry out the appropriate computational analysis.

     * More details of the kinds of projects that would be appropriate and manageable will be discussed during the first few weeks of class.




## Note about learning programming

A central goal of this class is to help students begin to develop programming skills that they can use to approach questions of interest using the various datasets and data sources available in the era of 'big data'. But like learning any new skill, such as a new language, it takes time and can be frustrating at first. This course does not require students to have any programming background. Realistically it is not possible to become a fully proficient programmer in just one semester. However, the lab sessions and assignments are focused on helping you begin this process and to become comfortable with reading, understanding and modifying Python code examples that you can find on the web etc.



## Course Schedule

* **N.B.** - This is a tentative schedule that is subject to change

### Week 1 - Overview
* Tue 08/27/19 - **Course overview** + JupyterHub setup
* Thur 08/29/19 - **Introduction to notebooks, Markdown & Python**


### Week 2 - Python basics + stories in simple data
* Tue 09/03/19 - Lists, dictionaries, functions and loops. Finding stories in simple data.
* Thur 09/05/19 - Lab session

### Week 3 - Working with _Open Data_
* Tue 09/10/19 - data initiatives & repositories e.g. data.gov
* Thur 09/12/19 - Lab session - git & github repos

### Week 4 - Understanding basic data structures as the components of stories
* Tue 09/17/19 - Tabular data - rows, columns. Looking for stories.
* Thur 09/19/19 - Lab session - Working with Pandas #1


### Week 5 - Working with data tables - Finding story dimensions in numbers.
* Tue 09/24/19 - Selecting and transforming columns, subsetting & grouping. Data is messy - cleaning it up!
* Thur 09/26/19 - Lab session - Working with Pandas #2

### Week 6 - Data visualization (Part 1) - Supporting stories with plots
* Tue 10/01/19 - Aggregating & summarizing. Creating simple plots. Thinking about good visualizations.
* Thur 10/03/19 - Lab session 


### Week 7 - What is data journalism and what can it do?
* Tue 10/08/19 - Guest lecture: Jennifer Henrichsen
* Thur 10/10/19 - FALL BREAK

### Week 8 - Data visualization (Part 2)
* Tue 10/15/19 - Using Python visualization libraries. Principles of good infomation visualization.
* Thur 10/17/19 - Lab Session

### Week 9 -  Data art (Part 1) - data stories beyond the newspaper
* Tue 10/22/19 - Guest lecture: Roopa Vasudevan
* Thur 10/24/19 - Lab session - data art (processing) - part 1

### Week 10 - Data art (Part 2) 
* Tue 10/29/19 - Lab session - data art (processing) - part 2 
* Thur 10/31/19 - Project planning and disucssion

### Week 11 - Finding data in the _wild_ using web scraping
* Tue 11/05/19 -  Web scraping concepts, HTML + CSS
* Thur 11/07/19 - Lab session - using `requests` + `BeautifulSoup`


### Week 12 - Putting data on the map
* Tue 11/12/19 - Working with geo data
* Thur 11/14/19 - Lab session


### Week 13 - Interactive visualizations
* Tue 11/19/19 - Adding movement to your data stories
* Thur 11/21/19 - Lab session


### Week 14 - Review & Working on projects (1)
* Tue 11/26/19 - Lab session
* Thur 11/28/19 - THANKSGIVING


### Week 15 - Review & Working on projects (2)
* Tue 12/03/19 - Lab session
* Thur 12/05/19 - Lab session
