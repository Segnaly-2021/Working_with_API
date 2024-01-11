This is a getting-started project using API call and plotly library for dynamic visualization.

Just like GUI enables people to interact with applications, API allows applications to interact to each other.
These interactions can take many different forms, such as security purpose(Authentication and Authorization), 
sharing functionality, data retrieval, etc. 

In this project, we focused on building interactive plot based on data requested from GitHub using an API call. 
The dataset includes the top 30 Python projects with at least 10,000 stars formatted in json format. Therefore, 
each project is stored in a dictionary with **80 features(keys)**, such as:

* **Name**, which is the name of the project
  
* **Owner**, which denotes the project owner
  
* **Stars**, which is the number of stars
  
* **Repository**, which gives the link of the project repository
  
* **Description**, which describes the project
* ...

To get an idea of the most popular Python project on GitHub, we used Plotly to plot a bar chart of the number of stars of each project.
The graph shows that the **public-apis** project is currently the most popular Python project hosted on GitHub.

To push it a little bit further, we customized the plot by adding the **Owner** and the **Description** of a project to the **tooltips**. 
The latter is the message that pops up whenever we put the cursor on a bar to show the information the bar represents.

Finally, the main reason why we worked with Plotly is that it allows interactive visualization. 
To use it, we associated each project name on the x-axis with its repository link so that clicking 
on the name will directly take you to the GitHub repository.
  

