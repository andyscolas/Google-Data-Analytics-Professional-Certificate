# Google-Data-Analytics-Professional-Certificate

The Objective of this Project is to find out how annual members and casual riders use Cyclistic bikes differently.
Knowing how each bike is used will help the Cyclistic marketing analytics team find the best path to take for their marketing strategy.

For the purposes of this case study,
The datasets are made available by Motivate International Inc. Cyclistic is a fictional company used for the purpose of this Study. The data set being used here will be from September 2020 to August 2021.

Both the Data and License agreement can be found here : https://www.divvybikes.com/system-data

Using R, I started off with uploading and renaming the 12 months of datasets into new objects. Afterwards renamed some of the mis-match columns names to make it consistent with the other Months. Onces all sets followed a single format I created a new object with all datasets under said object.

 Removed lat and long fields as they are not needed for this project. Correct the "member" and "Subscriber" issue under
"member_casual" column where Subscriber will also be seen as member. Similar issues came up with "Customer" and "casual" as well, which was also corrected to be seen as casual.

Removed trip duration that was showing up as negative. Add columns that listed date, month and day. Add ride_length column to calculate all trips in seconds. Downloaded summieze version of file for tableau based on trips taken per-day in seconds. Using google sheets, converted seconds into hours.

Sites used for coding assistants

https://grow.google/dataanalytics/#?modal_active=none

https://www.statmethods.net/input/dates.html

https://stat.ethz.ch/R-manual/R-devel/library/base/html/difftime.html

https://docs.google.com/document/d/1TTj5KNKf4BWvEORGm10oNbpwTRk1hamsWJGj6qRWpuI/edit

Tableau data VIZ: https://public.tableau.com/app/profile/andy.colas/viz/GoogleDataAnalyticsCapstoneprojectCyclisticDivvyBikes/Dashboard1#1

Based on my Analysis a few patterns did come up.
First was the fact that “Casual” riders never peaked higher than around 66k hours during any time of the week in the 12 months resechered. Next is the fact that even if Members peak during the weekend, Casual riders have a very consistent use. With this information in mind, it is clear that Casual riders are using our bikes for standard daily tasks for your average person. Going to work, Going to Class, Going grocery shopping, all things that can be quicker and easier with a bike based on where one lives. Whereas our Members usage is focused on Weekend use, every weekend. Seeing as most classes are not held during the weekend, most people are off during the weekend, and minimal activity is seen during the week so grocery shopping is not an option. Recreational use is our clear winner here.

To summarize Members are using our bikes mostly on the weekend with minimal activity during the week for what can only be surmised as Recreational use. Anything from working out to visiting locations for one's own enjoyment. Whereas Casual bikers have a near constant flow of use throughout the week never peaking, as if on a schedule. Clear use, not based on Enjoyment but for convenience in their daily lives.
