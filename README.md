For detailed study , refer :
Marketing Mix Modelling Analysis - https://medium.com/@goyal.shubhangi/marketing-mix-modelling-analysis-fdf2853ea788


# Marketing Mix Modelling Analysis
The key purpose of MMM, which serves as a decision-making tool for brands, aims for effective marketing(online and offline medium) to maximize Return of Investment(ROI) on production, sales and distribution of the right product at the right time and right place while available at the right price(ie., right product and services)

## MARKETING MEDIUMS
Marketing mediums include a blend of options companies have at their disposal during the promotional phase of marketing. It can be broadly be divided as Online and Offline Marketing Mediums.

## MARKETING MIX ELEMENTS
Marketing Mix Components are factors that influence the market performance of a product which helps in an accurate forecast of the effects of promotional activities and product distribution. They break down business metrics to differentiate between contributions from marketing and promotional activities vs. elements.

## TYPE OF ANALYSIS
In statistical exploratory analysis, marketers can develop an understanding of the results of their marketing initiatives. Broadly grouped-

i) **Univariate Analysis:** Quantitative evaluation describes the data gained from marketing mix variables being analyzed contains only one variable and finds patterns that exist within them. These patterns can be explained using central tendency, dispersion, standard deviation.
It is used to Analyse the patterns in the data(like umbrella sales peak in rainy season only), Identify the possibility of creating new variables(promotional discount offers), Identification of any outliers in the data via visualization using Frequency distribution tables, Bar charts, Histograms, etc.

ii) **Bivariate Analysis:** Analysis to understand the relationship between two different variables among marketing mix elements.
It is used to identify the key variables that exhibit a good relationship with the dependent variable, Identify the type of relationship variable exhibits with dependent variable via scatter plots, line charts, stacked column chart or combination chart.


## POSSIBLE ISSUES WITH DATA
Two major challenges faced by marketers while developing MMM:

i) **Outliers:** It is a process of finding data objects with behaviors that are very different from expectation, basically values with extremely high or low spikes.
he reason for an outlier could be seasonality, a new product launch, campaign, promotion, discounts, competitor actions, etc. It could also be due to randomness.

ii) **Missing Values:** The non-availability of data for a particular observation or calculation in a variable. Usually occurs due to Non-occurrence of events, non-availability for the complete time period of analysis, people skipping to mention the data entry, or Missing out in randomness.
Some of the ways to resolve the issue can be Imputation such as estimating the value, Forecasting, or predicting value via techniques such as considering average or KNN, Replace entry with zero, or just Delete the entry.

## DATA TRANSFORMATION
Data transformation refers to the replacement of a variable by a function of that variable. Suppose, replace variable X by the square root of X. 
The initial advertising spend has little impact until a certain threshold, after which a noticeable impact on the KPI's is observed. Most of the advertising activities have non-linear impact on the KPI's and exhibit a pattern of diminishing returns. This impact tends to diminish as the spends reach a point of saturation post which has minimal impact. This entire impact can be captured in the form of S-curve transformations. Gompertz, Chapman Richards, and Weibull and Morgan-Mercer-Flodin transformations are used from a marketing mix perspective.

General practical applications of data transformation-

i) **Advertising adstock Effect:** Adstock is a model of how the response to advertising builds and decays in consumer markets. It reminds in-the-market consumers in order to influence their immediate brand choice and teaches to increase brand awareness and salience, which makes it easier for future advertising to influence brand choice.
The underlying theory of adstock is that exposure to advertising builds awareness at a new level in the consumer markets, resulting in sales. Marketers can use the advertising adstock as a variable in sales response modeling, such as regression analysis. It represents the half-life of advertisements.

ii) **Lag Effect:** The effect of a previous value of a lagged variable when there is some inherent ordering of the observations of this variable. This effect is useful in a study in which different subjects are given sequences of treatments and you want to investigate whether the treatment in the previous period is important to understand the outcome in the current period.

## TECHNIQUES FOR ANALYSIS
In Regression, data is broken down into two categories: dependent variables (DV) and independent variables (IDV). The analysis of how independent variables can impact the outcome of dependent variables is the crux of regression. By doing this, marketers are able to provide an accurate estimate of the marketing mix on the company's net profits.

i) **Linear Regression:** Applied when the DV is continuous and the relationship between the DV and IDVs is assumed to be linear. It can be used for Causal Analysis, Forecasting the impact of a change, and Forecasting Trends.

ii) **Multiplicative Regression:** To overcome the limitations inherent in linear models, multiplicative models are often preferred. In these models, IDVs are multiplied together instead of added. 
It can be implemented via Semi-logarithmic models(aka, Log-Linear Models) and Logarithmic models(aka, Log-Log Models).

## MODEL IMPROVEMENTS
Errors impact the accuracy of the model's predictions and actual outcomes. Sometimes, the model performs well on training data, but poorly on validation or test data.
To resolve this, marketers need to analyze-

i) **Bias:** Difference between the average predictions of the model and actual value we are trying to predict. Models with a high bias can lead to errors in training and test data.

ii) **Variance:** Error which arises from sensitivity to small changes in the training set. Models with this error perform very well or training data, but have a high error on test data.

iii) **Bias-Variance Trade-Off:** The model can have either under-fitting (where the model is unable to capture underlying parameters) or have over-fitting (where the model captures the noise along with parameters). 

An under fitted model can have high bias and low variance. On the other hand, an overfitted model can have low bias and high variance. Therefore, marketers need to strike a balance between the two with a bias-variance trade-off to develop an accurate model.

Through regularization, add a penalty term to the objective function and control the model complexity completely using that term. It can be implemented via-

i) **Lasso regression:** Minimise the objective function by adding a penalty term (sum of the absolute values of coefficients). By penalizing the absolute values, the estimated coefficients shrink to zero such that overfitting is avoided and the learning is faster.

ii) **Ridge regression:** Minimise the objective function by adding a penalty term (sum of the squares of coefficients). When there is a multicollinearity problem among the predictor variables, the coefficient of one variable depends on other predictor variables included in the model. By adding the penalty term, coefficients of collinear variables will shrink, except for the significant predictor among them.

iii) **Elastic-net regression:** Combining the penalties of Lasso and Ridge Regression, this is usually the preferred method as it combines the best of both models.

## MODEL EVALUATION
The selection of the marketing mix model is crucial for marketers to be able to make accurate predictions and estimations. There are two main considerations to take into account when selecting a model-

i) **Business Logic:** The model should be reflective of the actual market scenario.
For example, Apple decreases the rates of its previous models with the launch of the new iPhone series otherwise it might impact the sales negatively.
A few features that can be implemented would be like Media advertisements for the product should have positive coefficients in the model, Halo or Cannibalisation Effect can occur due to promotions for other products from the brand, Adstock value for TVCs should be greater than for digital ads since TVCs have a higher brand recall, Discounts and promotions creates an immediate impact on sales, etc.

ii) **Statistical Logic:** Based on the problem, model should be evaluated keeping validation and prediction quality in check. 
Rsqaure which defines how close the data are to the fitted regression line, Adjusted Rsquare, Regression Coefficients which estimates unknown population parameters and describe relationship between a predictor variable and response, Variance Inflation Factor (VIF) detects multicollinearity(correlation between predictors)in regression analysis, MAE measures the average magnitude of the errors in a set of predictions, MAPE is the average absolute percent error or predicted values minus actuals divided by actuals for each observation.

## ADVANTAGES
A few key advantage of the MMM are-

→ The success or failure of a product or service in the market can also be traced back to how accurate and efficient its marketing mix was.

→ Identifies the most suitable marketing channel (Eg. TV, online, print, radio, etc.) to achieve the marketing objectives and get maximum returns.

→ Markets can suggest optimal spending levels in highly effective marketing channels to avoid saturation.

→ Forecast business metrics based on planned marketing activities and then simulate various business scenarios like increase in spends by 10%, the level of spends required to achieve 10% lift in business metric, etc.
