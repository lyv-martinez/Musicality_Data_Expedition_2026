# How to run the data expedition: Testing musicality - from demonstration to data analysis 

### A few days prior to class:
Have the students download R, read all the papers, and remind them to bring their laptops and earbuds. 
Also send the empty Rmarkdown file, online excel sheet, online word document so they have easy access to everything they need on the day of class.

### Start of class:
We started off class with playing music at a low volume, to set the tone as students settled in. 

### Presentation:
We led off class with a 15 minute presentation. We first asked the students to describe "what is music?" in their own words. We then went into individually explaining rhythm, pitch, and their intersection.

### Pitch and Rhythm Tests
We gave the student about 15 minutes to do these tests:

Pitch (1x): https://www.nidcd.nih.gov/tunestest/take-distorted-tunes-test

Rhythm (3x): https://www.concerthotels.com/got-rhythm

We then let them choose their groups, open the homework document, make a copy of it, and share it with their group members. For 10 minutes they worked in these groups to come up with hypotheses to these questions:

* Can practice improve rhythm?
* Is there a relationship between rhythm and pitch?
* Can we predict who has musical experience from their rhythm/pitch ratio?

### Live Coding:
This section took a little over an hour to complete. We shared an Rmarkdown file with all the students, so that we're all working with the same format. This R tutorial only used the packages 'ggplot2' and 'viridis'. We had them create 3 different models to answer the three questions above.

For each model they analyzed the p-value to determine if the results were significant or not (<0.05). The first model the students learned how to turn continuous data into categorical data, color their plot points by category, jitter the points so that no two points are overlapping, create boxplots, and create a linear regression (line-of-best-fit). During the second model they learned about confidence intervals and how to create a scatter plot. And lastly, the third model taught them how to preform a binomial model when working with binary data and creating an S shaped line-of-best-fit on their graph. 

### Discussion:
We decided to make the discussion piece the last part of class (ca. 20 minutes), in order to make sure we had an ample amount of time to code and move at the students pace. 
We had the students read these four papers before class:
* https://academic.oup.com/beheco/article/19/5/1034/250191
* https://www.sciencedirect.com/science/article/pii/S001002779900061X
* https://www.sciencedirect.com/science/article/pii/S0960982223003871
* https://link.springer.com/article/10.1007/s10071-024-01875-5
  
Dr. Johnsen assigned 2 students to lead the discussion prior to this module, so we were just their to facilitate and guide them through the main points of the papers and bring up other interesting questions and examples. For example the dog on America's Got Talent that is able to match its owners pitch!

We then ended class by asking if their definition of music has changed from their original thoughts at the beginning of class.
