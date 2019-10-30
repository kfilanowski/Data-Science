# Data-Science

# Author: Kevin Filanowski

This project was one of self-learning, mostly through material from [CodeCademy's Data Science path](https://www.codecademy.com/learn/paths/data-science).
It is completed in [Jupyter](https://jupyter.org/), a web-based interactive development environment.

# Heart_Disease_Playground
This project involvew experimenting with knowledge gained through codecademy and self studies to attempt to successfully 
find some type of model that I felt satisfied with. I chose a set of [data from Kaggle](https://www.kaggle.com/ronitf/heart-disease-uci)
to play around with. 

During experimentation, my best result and the result I ended up concluding with was using K-nearest neighbors.
I began optimizing what value of k ended up being the best through repeated experiments evaluating from k=1 to k=all attributes.
After finding the optimal value for k, I ran 10,000 sets (repeated experiments) to be very sure of the results. 

At it's worst, the model is a little better than guessing, at around 55.74% as absolute minimum. 
On average, the model is 81.90%, and at it's best, we're looking at upwards of 96.72% success! 

I believe reason for this variance is because I randomized the train and validation data every time, 
so some statistical luck is involved. In addition, there are only 300 records of the data,
so there will be a good bit of variance regardless.

Overall, this was a result I felt fairly happy with.
