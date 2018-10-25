# Colorado-County-Voting-Classification

## Goal:

- To classify counties in Colorado based on their voting history from 2012 to 2016.

## Data:

- Elections results from top of the ticket even year elections going back to 2012. Top of the ticket elections include President, Governor, Senate and Congressional elections. I pulled the data from the Colorado Election Results Archives on the [Colorado Secretary of State's website](https://www.sos.state.co.us/pubs/elections/Results/Archives.html). 

## Modeling

- I did not have a target lable to be able to train a model on I used a unsupervised learning model. I tested different KMeans and DBSCAN models. I ended up choosing a KMeans model with K=6 for my best results. 

## Results:

- I choose the KMeans with K=6 because I was able to isolate the "swing" counties in the middle of the voting patterens. Below is the map of Colorado with each counties labels. You can view the rest of the graphs for each race at my [Tableau Public Profile](https://public.tableau.com/profile/cbjohnson30#!/vizhome/County_Vote_History/Countywith6)

![Colorado Map](https://github.com/CBJohnson30/Colorado-County-Voting-Classification/blob/master/Images/County%20with%206.png)



