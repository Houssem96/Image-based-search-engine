# Image-based-search-engine
It's an academic project which aims to develop an application that search similar images to the image request. The search is based on eh  index calculations (Edge histogram descriptor).

# Packages required
Python 3.6 or higher
pymongo
sklearn

# Files 
insert.py:  inject the edge histogram (eh) files in the Mongodb with their indexes and after performing a clustering of the images based on edge histogram (eh) calculations. 
app.py: the web application (http://localhost:5000) using Flask micro framework.
templates/index.html : html file presenting the content of the webpage (search engine)

# How to run the project :

1. Open MongoDB and create a new database
2. Change the path of the input files (eh)
3. Run insert.py 
4. Run app.py (flask run)
5. Open your navigator on: http://localhost:5000 in your browser and check your search engine how it works 

I hope you will enjoy this 
