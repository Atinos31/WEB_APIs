# Working with APIs
#### Self contained program that generates a visualization based on the data that it retrieves.
* A program to automatically download information about the most starred python projects on GitHub & then creates  an informative visualization of these projects.
* Web application Programming Interface that requests specific information from a website rather than entire pages and then use that information to generate visualization
* The program uses current data and its always up to date

## Git & Github
The visualization is based on information from github," a site that allows programmers to collaborate on coding projects.
1. Use GitHub's API to request information about python projects on the site & then generate an interactive visualization of the relative popularity of these projects using Plotly.

## Steps
#### Using the web API
1. Requesting data using an API call
 * GitHub's API lets you request a wide range of information through API calls . To see what an API call looks like , copy and paste this url into your browser's adress bar and press ENTER:
   *  https://api.github.com/search/repositories?q=language:python&sort=stars
   This call returns the number of python projects currently hosted on GitHub as well as information about the most popular repositories.
2. Installing Requests
    * The request package allows a Python program to easily request information from the website & examine the response.
       * $ python3 -m pip install  --user requests
3. Processing an API response
4. Working with the response dictionary
   * GitHub API returns lots of information about each repository: there are 78 keys in repo_dict.
5. Summarizing the top repositories
6. Monitoring API limits
#### Visualization repositories using plotly
1. Refining ploty charts
2. Adding custome tooltips
3. Adding clickable links to the graph
4. Plotly & Github API
