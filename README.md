# CS50-Final-Project
CS50 Final Project for Tyler Tarsi, Aaron Kruk, and LJ Barlow.

Concentration data taken from Harvard Open Data Project. Link: https://github.com/Harvard-Open-Data-Project/harvard-data/blob/master/concentrations-and-class-enrollment/Concentration%20Data.csv

HTML/Flask Skeleton taken from CS50 Finance.

Used Charts.js and modified it to have a more viewer friendly legend.


Our About page on our website gives more insight on our project. It describes what we are trying to answer: the question of whether or not
student athletes concentrate more heavily in certain concentrations, and if so, is it because of time constraints on courses. It also describes
how we formulated the website and how we are giving the framework needed for one to answer the question.

Our Team page gives an introduction to each of our team members and has a bio about for of us. It has pictures of each of
us and a link to our respective pages on GoCrimson.

Our Raw Data page has our data in 2 HTML tables. We used a JSON file and transferred it to a pandas dateframe. Then, in python,
we converted the dataframe to an HTML table, and copy and pasted the table into our HTML template. We thought it was important to include this data, because (to our knowledge) it has never been studied before. (besides the Harvard Open Data Project full student population concentrations)

The Homepage shows the data visualization and is interactive. To create the data visualization, we used Charts.js which
is a JavaScript library used to create charts and other data visualization. We have two donut charts: the one on the left has every concentration and the
number of students committed to that concentration. The donut chart on the right is the same thing but for student-athletes.

To obtain the data, we used a data scraping algorithm to go through each athletic website and retrieve the concentration data
for each athlete on each team. We also used a data scraping algorithm to get data for every course time from the registar. Please read more about these implementation details in our "DESIGN.md" file.


Our final presentation can be seen at: https://www.youtube.com/watch?v=y_JjeK6I0P8&feature=youtu.be
