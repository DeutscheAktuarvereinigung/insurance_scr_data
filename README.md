# insurance_scr_data
DAV Use Case:
How to Work With Comprehensive Internal Model Data for Three Portfolios

The main intention of this notebook is to demonstrate how the comprehensive internal model data which we provide together with the notebook can be loaded and transformed in order to train different machine learning models.

The scope of the data exceeds anything currently accessible in the open domain. Furthermore, we provide more data than is usually available in the productive environments of the insurance companies, which should enable the actuarial data scientists to reliably test their regression models and draw comparisons among them.

The code below for the training of both neural networks and polynomials serves as a minimal viable example. The resulting neural network and regression polynomial are by no means optimized. They represent simple examples, in the case of the polynomial regression we use as terms only the linear factors of the risk factors.

The users of this Use Case are encouraged to test other hyperparameter configurations and compare the results they obtain when doing so. Furthermore, a sophisticated hyperparameter optimization together with an ensemble technique will lead to a more stable and robust result. We believe that other regression techniques ranging from more traditional to the decision tree based approaches can equally well be applied to our data.

The authors have implemented one such optimization. In the article we plan to publish soon after releasing the data and in our talks at the conferences of the German Actuarial Association we report the goodness-of-fit we have reached and compare it to the best polynomials we have fitted using the least-squares regression and an adaptive step-wise algorithm as described in Krah, Nikolić, Korn: "A Least-Squares Monte Carlo Framework in Proxy Modeling of Life Insurance Companies" (2018). These results should serve as a challenge to the actuarial/data science community. We are looking forward to approaches which will produce even better results.

_________________________________________________________________________________________________________

The German Association of Actuaries (Deutsche Aktuarvereinigunge.V., DAV) is the professional representation of all actuaries in Germany. It was founded in 1993 and has more than 5,400 members today. More than 700 members are involved in thirteen committees and in over 60 working groups as a voluntary commitment.

The given repositories have been created by committees and working groups and serve as an aid for our members and interested persons to support them in their work with machine learning methods and data science issues in an actuarial context.

**Please note that the repositories provided on GitHub are published by the DAV. The content of linked websites is the sole responsibility of their operators. The DAV is not responsible for the code and data linked to Kaggle.com and referred to in the repositories. These reflect the individual opinion of each user on Kaggle.**
