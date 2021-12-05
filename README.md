# 2020 Formula 1 Overtaking
# Motivation
Over the last five years I have really gotten interested in Formula 1 and learning as much as I could about it. So much of the sport nowadays is based on collecting as much data as possible, and running simulations on that data, and generating more data from that, that it only made sense to use it as the topic for a data related project. Formula 1 is also very interesting to look at as a sport because by no means is the ability of the driver directly related to the results that they get. The performance of the car usually has a larger impact on the outcome of a race. This makes comparing drivers to each other very difficult. As the cars have been getting faster and faster over the years, it has been getting more and more difficult to overtake during races. I was curious to see which drivers were still able to consistently make overtakes happen.
# Data Process
I was able to find the [Ergast Developer API](http://ergast.com/mrd/) website which has a download link for a folder full of csv files of Formula 1 data, going all the way back to the 1950's. I mainly used the results.csv file from this folder, only using the others to crossreference what some of the data meant. I then cut down the data to just include rows from the 2020 season. I then just cleaned up a couple of datapoints, that were set to 0, using other sources online to get the right data. That was it for the work I had to do in Excel.
# Visualization
![2020 Formula 1 Grid Position vs. Finishing Position](https://github.com/IBancroft/Personal-Dataset/blob/main/drivers2.png?raw=true)

This graph shows the total finishing positions of every driver in 2020, graphed against the total of their starting positions. The diagonal line is a reference for where finishing where they started would put them. So the drivers on the right of the line tend to finish higher than where they started and those to the left, tend to finish below where they start a race. The drivers with the highest and lowest differences between their starting and finishing positions are the labeled ones. It's no surprise to see that Raikkonen, who has driven more F1 races than anyone else in history, is able to make up the most places during races. It is surprising to see that Verstappen, considered to be one of the best young drivers, is losing the most places during races. Looking into the data though, it seems that most of these places were lost due to not being able to finish multiple races. This graph also shows that those starting in the lower positions tend to finish higher, and the drivers who typically start higher tend to finish lower.
# Analysis
![2020 Formula 1 Total Position Change](https://github.com/IBancroft/Personal-Dataset/blob/main/boxDrivers.png?raw=true)

I noticed some interesting facts by looking at Tukey's 5 numbers for all the drivers total positions gained or lost throughout the season, so I made a boxplot of it. The first quartile is at -13, but the third quartile is at 5. This means that the drivers that tend to lose more places than they gain during races tend to be losing more places than those that are gaining places. This can also be seen in the mean being -3.2 and the minimum being further away from zero than the maximum is. 

