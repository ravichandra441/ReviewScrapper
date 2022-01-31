# ReviewScrapper:
   This application is about creating a web scraper, in this case,
 a review scrapper right from scratch and then deploying it to the AWS cloud platform. 
 Text scrappers are extensively used in the industry today for competitive pricing, 
 market studies, customer sentiment analysis.Hence, web scrappers are applications/bots, 
 which automatically send requests to websites and then extract the desired information from the website output.
 
 3. Application Architecture:
 
 ![Architecture of  Review Scrapper](https://user-images.githubusercontent.com/55264211/151788906-44fb5ef6-c4fb-445f-9531-71d29acc5f8f.PNG)        
         
## 1. Prerequisites:
  The things needed before we start building a python based web scraper are:
  • Python installed.
  • A Python IDE (Integrated Development Environment): like PyCharm, Spyder, or any other IDE of choice
  • Flask Installed. (A simple command: pip install flask)
  • MongoDB installed.
  • Basic understanding of Python and HTML.
  • Basic understanding of Git (download Git CLI from https://gitforwindows.org/  
              
## 2. Python Implementation:
    Note: I have used PyCharm as an IDE for this documentation
    
   1. Let’s create a folder called ‘reviewScrapper’ on our local machine
    2. Inside that folder, let’s create two more folders called ‘static’ and ‘templates’ to hold the code for the UI of our application. 
        Inside ‘static’, let’s create a folder called ‘css’ 
    3. Let’s create a file called ‘flask_app.py’ inside the ‘reviewScrapper’ folder.
    4. Inside the folder ‘css’, create the files: ‘main.css’ and ‘style.css’. 
    5. Inside the folder ‘templates’, create three HTML files called: ‘base.html’,’index.html’, and ‘results.html’.
        • base.html→ It acts as the common building block for the other two HTML pages.
        • index.html→ Home page of our application.
        • results.html→ Page to show the reviews for the searched keyword.
     6. Now, let’s understand the flow:
        a) When the application starts, the user sees the page called ‘index.html’.
        b) The user enters the search keyword into the search box and presses the submit button.
        c) The application now searches for reviews and shows the result on the ‘results.html’page.
     7.Understanding flask_app.py:
        a) Import the necessary libraries.
        b) Initialize the flask app.
        c) Creating the routes to redirect the control inside the application itself. Based on the route path, the control gets transferred inside the application.
        d) After this, we’ll just run our python app on our local system, and it’ll start scraping for reviews.s as shown below:

## Home Page
     
  ![home page and search results review scrapper](https://user-images.githubusercontent.com/55264211/151788963-cb075a2b-c45f-49c6-b22c-ba8a0b5f7e0b.PNG)

