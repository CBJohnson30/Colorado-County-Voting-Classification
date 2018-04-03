# Colorado-County-Voting-Classification

## Goal:

- To classify counties in Colorado as Republican, Democrat or a swing county. 

## Data:

- Elections results from top of the ticket even year elections going back to 2012. Top of the ticket elections include President, Governor, Senate and Congressional elections. I pulled the data from the Colorado Election Results Archives on the [Colorado Secretary of State's website](https://www.sos.state.co.us/pubs/elections/Results/Archives.html). 

## Modeling

- I did not have a target lable to be able to train a model on I used a unsupervised learning model. More specificly a K-Means model. I chose those model because I am able set the number to clusters it will look for to 3. One for each Republican, Democrat or a swing counties. Then I will have to do a little plotting to determine what the numerical value for each cluster means.

## Results:

- I was able to classify each county into one of 3 labels. Below is a map of Colorado colored according to its label.
In the [IPython Notebook](https://github.com/CBJohnson30/Colorado-County-Voting-Classification/blob/master/historical_voter_patterns.ipynb) there are more graphs that more closely look at each election indivudialy. 

![Colorado Map](https://github.com/CBJohnson30/Colorado-County-Voting-Classification/blob/master/Images/County.png)



