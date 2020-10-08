# Better Coffee: Dundalk or Catonsville?

## Overview
Choosing a location to live is based on many factors, such as school districts, affordability, and location to work. Another important factor for a lot of people is living in a place where they can get a quality cup of coffee for a value. This project focuses on two areas located in Baltimore County, MD: Dundalk and Catonsville. I am intestered in which area has the better coffee shops. I am also interested in to see which area has the more expensive coffee and does a more expensive price of coffee really mean a better coffee shop?

## Method
I used Yelp's Fusion API to retrieve and create multiple data files with information about the coffee shops and areas.

To answer my questions about coffee, I created a technical notebook where my analysis was performed.  

## Sources
The datasets came from [Yelp's Fusion API](https://www.yelp.com/fusion).

I also referenced these websites to help my python code:  
[The Flatiron School's Python API Intro - Yelp](https://learn.co/lessons/python-api-intro-yelp)

I used the getpass function from [geeksforgeeks.org](https://www.geeksforgeeks.org/getpass-and-getuser-in-python-password-without-echo/).


## How to navigate my Github Repo
The data can be found in the "Data" directory. There are two raw data files, one for Catonsville and one for Dundalk.
There are three cleaned data files, Catonsville, Dundalk, and one for Dundalk with no headers. The Clean Dundalk file with no headers was created so that I could create an additional combined data file with both areas data and only 1 header.  

There are also two Jupyter notebooks. One notebook named "Data_Retrieval" shows how I was able to pull and wrangle the data. The one labeled "Technical Notebook" is where I performed my analysis on the data.