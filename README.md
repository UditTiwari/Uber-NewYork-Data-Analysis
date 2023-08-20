
# Uber NewYork EDA

Hey there! So, I've been working on this cool Jupyter Notebook that dives deep into Uber pickup data in New York City. You know, just to understand the trends and stuff. If you're interested, you can check out the original notebook right here on Google Colab.

Alright, let's break it down:

First things first, I've used Python along with some really handy libraries like Pandas, NumPy, Seaborn, Matplotlib, and Folium. These tools help me play around with the data, make it look pretty, and even do some fancy location-based analysis.

Speaking of data, I started off by loading Uber pickup data for the first half of 2015 from a CSV file. Just wanted to know what I'm working with. And of course, no one likes duplicates or missing values, so I cleaned up the data to make sure it's all good.

Now, let's get into the fun part - the analysis:

Monthly Analysis: I figured out which month had the highest number of Uber pickups in NYC. To make it more visual, I made bar plots that show how pickups are distributed across different months.



Hourly Analysis: Ever wondered when the rush hours are? I did! I explored the hourly rush for Uber pickups on each day of the week. Then, I created a cool point plot to visualize how the rush changes during different hours on different days.

Active Vehicles Analysis: I got my hands on data about active Uber vehicles for different base numbers. To make sense of it, I designed a box plot that shows how many active vehicles each base number has.

Merging Files: At one point, I needed more data for a comprehensive analysis. So, I merged multiple CSV files into one big dataset. Made things a lot easier.

Spatial Analysis: This is where it gets exciting! I wanted to know where the action is happening in NYC. So, I used Folium to create a heatmap that highlights the areas with the most Uber pickups. Looks pretty cool on a map!

Hourly and Weekday Analysis: For an even deeper dive, I explored rush patterns on an hourly and weekday basis. Created a heatmap-style pivot table that shows the intensity of pickups during different hours and days.

Automation: Don't want to repeat steps all the time, right? So, I crafted a function that generates pivot tables with fancy color gradients. Makes things look professional.

And that's the gist of it! This notebook is like a treasure trove of insights about Uber pickups in NYC. So, if you're into data analysis and curious about urban transportation trends, give it a look!



# Calculating the number of pickup monthwise

![App Screenshot](https://ibb.co/nRSnqf0)
![App Screenshot](https://ibb.co/jMsBcNQ)

#Find out Hourly Rush in New york city on all days
![App Screenshot](https://ibb.co/XJnptwk)



