I made some changes in the repo with the help of Claude, but (I think it's important to mention it) all the code was written by myself and it's also the case for the summmaries I added. These summaries attempt to explain the theory I used it for the practicals.
We can summarize what I've learnt this way : 


TP1 : We started with linear regression to introduce the idea of minimizing a loss function, with a closed form for the optimal solution. The practical indeed presents a Linear Generalized model with polynomials. Practically, we worked on the use of csv's with Pandas and statmodel for the regression which uses the theory presented to work.  

TP 2 : The purpouse of this practical was to make predictions of the academic background of first year students at Ecole des Ponts knowing only their grades. We used here the Naives Bayes classification method, the continuous variables (marks) were supposed Gaussian in each class, whereas we used proportions inside the class (a specific academic background) for the choice of an elective course. Nevertheless, as validation and generalization hadn't been seen yet, I simply checked that it the prediction was correct on myself, and as expected, it was 
the case. As an opening we could try do the logistic regression approach and compare the perforamnce (with a better separation between the training/validation/test set)

TP 3 : Here we used PCA in order to cmpress images, we used a dataset on which different numbers are represented
