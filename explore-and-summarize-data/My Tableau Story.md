

# My Tableau Story
    Olive KMG
    January 2019
    

### Summary

My visualisation is based on a baseball data set containing 1,157 baseball players including their handedness (right or left handed), height (in inches), weight (in pounds), batting average, and home runs. I look at how the plavers physical characteristics specifically handedness, height and weight  influence their performance (batting average and home runs).  From the visualisation we see that its advantageous to be left since most lefties have both the capacity for great homeruns and greater batting average. We also see that not including extreme cases  of height and weight where one may be obese, weight and height have no direct influence on the HR and Avg as performance indicators. 


### Design Choices

i) The first visual - see Players and Performance is a general view  to show the differences in performance among players. I choose to use horizontal bars  which are good for comparison and they give a good layout.  To clarify the differences in handedness more I added handednes as a categorical variable  to color and add Number of records to shape.  The circles clearly bring out the individual aspect of the data.  The handedness legend explains the color difference and the name filter allows interactivity with the data.

ii) the second visual in my story - performance based on handedness has 2 worksheets. The first is a barchart to show the percentages of Right, Left and both categorical variables in the total number of players. Since its one variable only one color is sufficient. Further choices can be done with the filter.

The second sheet  the goal is to see how handedness relates with HR and Avg.  So we have three variables  A scatter plot compares the first two quantitative variables and handedness is used in the visual encoding as color.  To enrich the plot, the name variable is added to the tooltip.  To emphasize performance difference in handedness, Avg is added to the label visual encoding. The legend and the filters  explain and allow interactivity. The result is both clear and beautiful.  

iii) Player performance vs Height
Being  both quantitative variables - a scatter plot is a good fit, we get the correlation of the variables. To bring out the difference in height vs performance, height is added to the color mark and an orange-blue diverging color palette is used.  Its a rich blend if deep blue , orange and deep brown. Height is again added to size  to adjust the size of the circles.  Adding names to the tooltip enhances the information in the hover.  Annotations are added to clarify my story.  This same procedure is done for player performance vs weight but a different color palette is chosen.

The first udacity feedback  was encouraging; and advised that I add a title and remove abbreviations.  I was glad to be reminded about the abbreviations but surprised about the title because it was already there.  So I adjusted the view  from standard to entire view and reposted thinking the problem was with  my reviewers screen, see - Tableau Public workbooks no.2. 

From views  from the Tableau community I noticed that I had not given them enough information when I requested feedback.   So I did that.  From their comments I realised more that I needed to remove abbreviations. I made the necessary corrections.  With further emphasis from the 1st udacity reviewer -feedback 2, finally - I noticed that although I had the title in place I needed to switch it on to have it appear in the story.  Chris's advise about sorting the handedness scatterplots, allowed me to look deeper into my analysis and make better deductions that led me to my final plot, Tableau Public workbooks no.3.



### Feedback

![feedback1-udacity](https://screenshotscdn.firefoxusercontent.com/images/0285e2bb-3430-4465-932a-cfb8150337a6.png)
![feedback2-tableaucomm](https://screenshotscdn.firefoxusercontent.com/images/5593ce5e-390f-498a-9c84-32b0b97a5206.png)
![feedback3-tableaucomm](https://screenshotscdn.firefoxusercontent.com/images/c54ec544-a4c0-4dd5-8232-eb1a83d9cb34.png)
![feedback4-tableaucomm](https://screenshotscdn.firefoxusercontent.com/images/128fe19c-568a-4c6a-bbd5-96f1a2d8ce16.png)
![last-comment-udacity](https://screenshotscdn.firefoxusercontent.com/images/9e694ca1-4a62-4895-91bf-aa970da3aef4.png)

Tableau Public workbooks no.1
https://public.tableau.com/profile/olive.mg#!/vizhome/LastProject-2019/Story1?publish=yes

Tableau Public workbooks no.2
https://public.tableau.com/profile/olive.mg#!/vizhome/TheBaseballStory-2019/TheBaseballStory?publish=yes

Tableau Public workbooks no.3(final) 
https://public.tableau.com/profile/olive.mg#!/vizhome/AglimpseintoBaseball-Review-3/TheBaseballStory?publish=yes



### Resources:
https://www.tableau.com/learn/tutorials/on-demand/story-points?product=tableau_desktop&version=tableau_desktop_2018_2&topic=dashboardsstories
https://www.tableau.com/learn/tutorials/on-demand/getting-started-dashboards-and-stories
https://en.wikipedia.org/wiki/Portal:Baseball
https://en.wikipedia.org/wiki/Home_run
https://en.wikipedia.org/wiki/Batting_average_(baseball)
https://community.tableau.com/thread/132567
Was glad to find this at the end of my work- https://www.newsweek.com/science-why-lefties-make-better-baseball-players-92783




```python

```
