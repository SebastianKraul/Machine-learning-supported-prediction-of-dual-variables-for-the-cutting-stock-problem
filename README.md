# Machine-learning-supported-prediction-of-dual-variables-for-the-cutting-stock-problem
Problem data of our paper "Machine learning supported prediction of dual variables for the cutting stock problem with an application in stabilized column generation" in INFORMS Journal on Computing

All instances were generated with the instance generator of Gau & Waescher (1995). The specifications are given in our paper.

"Predictions.xlsx" gives information about the predicted dual variables of the TestInstances (see TestInstances.zip). The file consists of two worksheets. One for the predictions of the learning algorithm FULL and one for SPARSE.

"Predictions_BPPLIB.zip" includes the predictions for the BPPLIB instances. For each group of instances, there is a seperate xlsx-file for the predictions of FULL and SPARSE. Note that for some groups no prediction of FULL exist since they do not include instances <= 100 items.

"Solutions.xlsx" gives information about the number of iterations and solution time of the stabilized column generation algorithm. The file consists of one worksheet for the TestInstances (see TestInstances.zip) and a worksheet for each group of instances from the BPPLIB (AI,ANI,Falkenauer T,Falkenauer U,Hard,Irnich,Random,Scholl,Schwerin,Waescher).

"TestInstances.zip" includes the 500 instances of different sizes (25,50,75,100, and 125) used for the evaluation of our study in Section 4.2 (see Tables 5,6,7,8 in our paper). Each instance is described in seperate a txt-file. The format is as follows: Each row consists of two columns. The first row gives information about the number of items (m) and the size of the stock (L).The following rows describe the size (l_i) and the demand (d_i) of each item i.

"TrainingInstances_1_49999.zip" and "TrainingInstances_50000_100000.zip" include the instances used to train and test the different learning algorithms. These instances are also used in Section 4.1 to analyze the characteristics of the CSP data. Each instance is described in a txt-file. The format is as follows: Each row consists of two columns. The first row gives information about the number of items (m) and the size of the stock (L).The following rows describe the size (l_i) and the demand (d_i) of each item i.

Gau T, Waescher G (1995) CUTGEN1: A problem generator for the standard one-dimensional cutting stock problem. European Journal of Operational Research 84(3):572-579, ISSN 03772217, URL http://dx.doi.org/10.1016/0377-2217(95)00023-J.
