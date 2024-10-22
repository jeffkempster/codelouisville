# Code Louisville Python Data Science (May-July 2018)
## Jeff Kempster
#### jeffkempster@gmail.com

### Installing the Project
- git clone https://github.com/jeffkempster/codelouisville.git 
- This project was coded in Python 3 (version 3.6.4) on a MacBook Pro with MacOS High Sierra 10.13.6
- You should only need to Install Anaconda to use the jupyter notebook

### I use the following tools and frameworks with this project
- Anaconda - https://www.anaconda.com/download
- Jupyter Notebook - http://jupyter.org/install
- SQLite3 - https://www.tutorialspoint.com/sqlite/sqlite_installation.htm
- Pandas - https://pandas.pydata.org/
- Matplotlib.pyplot - https://matplotlib.org/users/installing.html
- **Markdown Cheatsheet** - https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

### Using the Notebook
- Open your terminal
- cd (change directory) to the cloned folder
- Run Jupyter Notebook by typing jupyter notebook at the terminal prompt
- Open the file Disney Wait Times.ipynb
- The repo contains csv files with wait time data for nine attractions
- From the Cell Menu choose Run All

### The Fun Part
If you are a Disney fan like me, you will want to know the burning question.  When is the best time to visit Disney World in Florida.  More specifically... What is the best time of year to visit Disney World? Based on 2017 data, what rides have the least wait time?  Does adding more ride capacity reduce the wait times?

This project contains wait time data for 9 attractions at Walt Disney World.  The Jupyter notebook will perform the following:
- Create a sqlite database
- Create tables to load wait time data
- Loop over each of the 9 CSV files provided by Touring Plans and import the data
- Analyze the data import itself
- Analyze specific questions about wait times

**Please refer to more specific information and details in the notebook**
