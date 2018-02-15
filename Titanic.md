


## Overview
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. Titanic sank after colliding with an iceberg,
killing 1502 out of 2224 passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of
people were more likely to survive than others, such as women, children, and the upper-class.

Here I am using given dataset for my analysis and find out what sorts of people were likely to survive and which passengers survived
the tragedy.

### Summary :
1.	Overall, the investigation provided us with some interesting insight based on factors of survivors on the Titanic. 
Quite a few more people died than those who survived. I am seeing that 549 pasengers died and 342 survived from the given dataset.

2.	There was very strong data supporting that a higher class indicated a higher proportion of survivors. The class of the passengers
had an effect on their survival rate. 3rd class passengers did not survive well as their 1st and 2nd class passengers.

3.	Gender also played a close role. "Women and children" had chances to survive more than men. So the Class of passenger and the women
with children influenced or helped the survival rate.

### Design: 

1. I use bar charts to compare data across categories. I create a bar chart by placing a dimension on the rows shelf and a measure on the columns shelf, or vice versa for the project. A bar chart uses the Bar mark type.

2. I used filters to view data in the bar chart or packed bubble chart, I can filter out the data.A text table uses the text mark type. 

3. I used highlight tables to compare categorical data using color and used color palette to diverging. Changed the color palette and to make the colors more distinct.

4. I used packed bubble charts to display data in a cluster of circles. Dimensions define the individual bubbles, and measures define the size and color of the individual circles.

5. I used “Viz in Tooltip” to users hover over a mark, the tooltip displays relevant data and details from another visualization filtered to that mark. Also I used advanced highlight actions using the Actions dialog box. There I can specify source and target sheets and the fields I want to use for highlighting.

    •	Hover - Rest the pointer over a mark in the view to run the action.
      This option works well for highlight and filter actions within a dashboard.
  
    •	Select - Click a mark in the view to run the action.
      This option works well for all types of actions.

#### Feedback:

I received the following Feedbck:

1- (slide 1) I recommend replacing the survived sequential palette to a color legend with only 2 colors for survived and not survived. Please note we use the sequential palette when we have a range of data. I also recommend replacing binary values such as 0,1 on legends with descriptive values like “Survived,” “Not Survived.”

2- I would also recommend replacing "Pclass" with a full word like "Ticket Class" to make it more clear. It is a good practice to avoid abbreviations as much as possible.

3- Our color palette on slide 4 is not color-blind friendly. The following chart shows some of the indistinguishable colors for people with this disorder. You can find the colorblind palette in the color legends by going to edit colors then in the opened window by clicking on the dropbox; you can see a colorblind option.

4- I don't recommend using abbreviations in the legends like "parch." Instead, we can replace them with the full words to make the visualization more clear and less confusing.

5- (slide 4) I don't recommend using "number of records" as a label. Instead, we can replace "records" with our target attribute like "passengers". This can make the visualization more clear.

Based on the Feedback,
1- I replaced the binary values 0 and 1 on legends with descriptive values like “Survived,” “Not Survived.”.  Ubdecided to change the plot's type or any other modifications that you have made.
Note: Agter published onthe Tableau Public, I noticed, that the "Survied" and "Not Survived" it is not showing on the public url. Please help on this.

2- I replaced "Pclass" with a full word like "Ticket Class" to make it more clear.

3- According the feedback, I change the color palette to colorblind palette in the color legends for those slides.

4-  According to the feedback, I replaced the "parch" to Parents and Children, "Sib Sp" to Sibblings to make the visualization more clear and less confusing.

5- Also, I change the "number of records" label to "Passengers".


####	Resources: 

https://www.kaggle.com/c/titanic-gettingStarted

https://public.tableau.com/en-us/s/resources

http://onlinehelp.tableau.com/current/pro/desktop/en-us/help.html

#### Data Files : titanic-data
https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59d54e6d_titanic-data/titanic-data.csv&sa=D&ust=1517870342478000&usg=AFQjCNFUDJ4ehOrIRdtY7irQwfcHH2jNew


# Data Story of Titanic:

Initial Story - https://public.tableau.com/profile/skandarajan.rajaratnam#!/vizhome/DataStoryinTableau-Initial/TitanicStory

Final Story -   https://public.tableau.com/profile/skandarajan.rajaratnam#!/vizhome/DataStoryinTableau-Final/TitanicStory
