# Covid-19-Tracker
Gives information about the Covid-19 for educational purposes and various statistics.
This is the class hackatho project which deals with data manipulation using the Data Structures.
Our team comprises of:
Priyam Gupta                  19BCS089
Anany Talwad                  19BEC004
Kshirsagar Uddesh Shyam       19BEC021
Mane Param Dattatraya         19BEC022
Prashant Sharma               19BEC034
Sanda Nihar Purshottam        19BEC038
Satyam Kumar                  19BEC040

The Python modules used here are
Libraries and Modules Used: 
1.	Kivy - Kivy is a free and open source Python library for developing mobile apps and other multitouch application software with a natural user interface. It is distributed under the terms of the MIT License, and can run on Android, iOS, GNU/Linux, OS X, and Windows. For the research the package includes App, Label, GridLayout, Text Input, SoundLoader, runTouchApp, Button, Popup, Config, Window.
2.	Time – Time module handles the time related tasks, to use functions which are defined in this module we have to first import this module in our code.
3.	pandas - In computer programming, pandas are a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series. It is free software released under the three-clause BSD license. From pandas we imported the ExcelWriter and ExcelFile.
4.	pprint - Data pretty printer. The pprint module provides a capability to “pretty-print” arbitrary Python data structures in a form which can be used as input to the interpreter. If the formatted structures include objects which are not fundamental Python types, the representation may not be loadable.
5.	openpyxl - openpyxl is a Python library to read/write Excel 2010 xlsx/xlsm/xltx/xltm files.
6.	matplotlib - Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy.
7.	pathlib - From this library we imported path. Pathlib module in Python provides various classes representing file system paths with semantics appropriate for different operating systems.
8.	easygui - EasyGUI is a module for very simple, very easy GUI programming in Python. EasyGUI provides an easy-to-use interface for simple GUI interaction with a user. From this we imported choicebox. Choicebox provides a way for a user to select from a list of choices. The choices are specified in a sequence (a tuple or a list).
9.	Heapq - Heapq is a Python module which provides an implementation of the Min heap.
10.	random - Generate pseudo-random numbers.
11.	xlrd - xlrd is a module that allows Python to read data from Excel files.

Algorithm of Programs (IDEA):
1.	In first problem, we used two for loops, one to get into the country and other to get into the dates of confirmed or recovered or death cases. We also used df.loc() function from the pandas library to access the location we wanted.
2.	In second problem, first we find the total number of confirmed cases of every state then we put them sequence wise into the one list then we created the another list and we putted the index numbers of the top five sates in that newly created list after that we increment those indexes by one because we have to compare those indexes with the serial numbers in the data file agedata.xlsx and printed the corresponding state.
3.	In third problem, We have the date wise column in the data file, first we calculate the total sum of all the date columns and placed those each column sum into one list then we merge the total sum of seven columns and forms the another list which consist of week wise sums and then took the average by dividing with seven and printed the result.

The References and the Data Files used ared take from the given below links:
•	https://github.com/CSSEGISandData/COVID-19
•	https://www.worldometers.info/coronavirus/country/us/
•	https://covid19tracker.health.ny.gov/views/NYS-COVID19-Tracker/NYSDOHCOVID-19Tracker-Fatalities?%3Aembed=yes&%3Atoolbar=no&%3Atabs=n
•	https://www.mass.gov/doc/covid-19-dashboard-april-25-2020/download
•	https://www.latimes.com/projects/california-coronavirus-cases-tracking-outbreak/
•	https://coronavirus.illinois.gov/s/
•	https://txdshs.maps.arcgis.com/apps/opsdashboard/index.html#/ed483ecd702b4298ab01e8b9cafc8b83
•	https://coronavirus.maryland.gov/
•	https://www.doh.wa.gov/Emergencies/Coronavirus
•	https://coronavirus.ohio.gov/wps/portal/gov/covid-19/dashboards/key-metrics/caseshttps://coronavirus.ohio.gov/wps/portal/gov/covid-19/dashboards/key-metrics/cases
•	http://ldh.la.gov/Coronavirus/
•	https://www.michigan.gov/coronavirus/
•	https://portal.ct.gov/-/media/Coronavirus/CTDPHCOVID19summary4252020.pdf?la=en
•	https://www.geeksforgeeks.org/
•	https://towardsdatascience.com/


