# Module-7-Challenge - Web Application for an ETF Analyzer
This application analyzes a fintech ETF consisting of four stocks: GOST, GS, PYPL, and SQ. The code is written in Jupyter Notebook and the application is launched through **voila** as a web application.

The Starter Code was provided along with the database containing the tables of stock data.

---

## User Story
Build a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF.

---

## Acceptance Criteria  
The application must meet the following acceptance criteria:  

* Analyze a single asset in the ETF

* Optimize data access with Advanced SQL queries

* Analyze the ETF portfolio

* Deploy the notebook as a web application

---

## The Application  

The application follows these stages: 
    
### Analyze a single asset in the ETF
    
* Extract the PYPL stock table from the database using SQL   
* Using hvPlot, create an interactive visualization for the PYPL daily returns 
* Using hvPlot, create an interactive visualization for the PYPL cumulative returns.

### Optimize data access with Advanced SQL queries
* Access the closing prices for PYPL that are greater than 200
* Find the top 10 daily returns for PYPL

### Analyze the ETF portfolio
* Write a SQL query to join each table in the portfolio into a single DataFrame
* Create a DataFrame that averages the “daily_returns” columns for all four assets
* Calculate and display the annualized returns for the portfolio
* Calculate the cumulative returns of the ETF portfolio
* Using hvPlot, create an interactive line plot that visualizes the cumulative return values of the ETF portfolio

### Deploy the notebook as a web application

* Use viola to deploy the notebook as a web application
---

## Technologies
The application is developed using:  
* Language: Python 3.7,   
* Packages/Libraries: Pandas, hvplot.pandas, viola, sqlalchemy, numpy
* Development Environment: VS Code and Terminal, Anaconda 2.1.1 with conda 4.11.0, Jupyterlab 3.2.9  
* OS: Mac OS 12.1

---
## Installation Guide
Following are the instructions to install the application from its Github respository.  

### Clone the application code from Github as follows:
copy the URL link of the application from its Github repository      
open the Terminal window and clone as follows:  

    1. $cd to_your_preferred_directory_where_you want_to_store_this_application  
    
    2. $git clone URL_link_that_was_copied_in_step_1_above   
    
    3.  $ls     
        Module-7-Challenge    
        
    4. $ cd Module-7-Challenge     

At this point you will have the the entire application files in the current directory as follows:

    * README.md                   (this file that you are reading)  
    * voila output.html           (voila output file)  
    * voila output                (voila folder)  
    * etf_analyzer.ipynb          (the application jupter lab notebook)  
    * etf.db                      (etf database - came with starter code)  

---

## Usage
The following details the instructions on how to run the application.  

### Setup the environment to run the application
Setup the environment using conda as follows:

    5. $conda create dev -python=3.7 anaconda  
    
    6. $conda activate dev  
    
    7. $jupyter lab  

---

### Run the Application
THIS ASSUMES FAMILIARITY WITH JUPYTER LAB. If not, then [click here for information on Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/).  

After step 7 above, this will take you to the jupyter lab window, where you can open the application notebook **risk_return_analysis.ipynb** and run the application.  

**NOTE**:
>Your $ prompt will look something like __(dev) ashokpandey@Ashoks-MBP loan_qualifier_app$__ ,  with:  
    - '(dev)' indicating the activated 'dev' environment,   
    - ' ashokpandey@Ashoks-MBP ' will be different for you as per your environment, and   
    - 'loan_qualifier_app' directory is where app.py is located.  
    - '$' sign is the dollar prompt  

---

## Contributors
Ashok Pandey - ashok.pragati@gmail.com   
www.linkedin.com/in/ashok-pandey-a7201237

---

## License
The source code is the property of the developer. The users can copy and use the code freely but the developer is not responsible for any liability arising out of the code and its derivatives.

---