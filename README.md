# CA4021 Repo - Kian Sweeney / 18306226

## Shortcuts

- The project dashboard is [here](https://projects.computing.dcu.ie/project.html?module=ca4021).
- Project proposal can be found [here](https://gitlab.computing.dcu.ie/sweenk27/2022-ca4021-sweenk27/-/blob/master/docs/proposal_project.pdf)

## Project Outline

- First stage involves extensive cleaning process of the well known, messy dataset the Irish Property Price Register.
- After cleaning extensive exploratory analysis is done to find a subset of the data worth exploring further.
- Run a plethora of ML algorithms looking to develop an accurate prediction model in these areas and explore the determinants of price in these areas also.

## Results

These are the accuracy results on the subset of the Dublin housing market we found with increasing real-time market values.

| Algorithm     | Accuracy      |
| ------------- | ------------- |
| TPOT AutoML   | 58.2%         |
| MLJar AutoML  | 49.3%         |
| LightGBM      | 46.9%         |
| CatBoost      | 46.4%         |
| MLR           | 40.8%         |
| Bayesian      | 40.0%         |
| AdaBoost      | 38.3%         |

Using our best model (TPOT AutoML) we trialled it on different cities, one in Ireland and one in the UK to test how reliable this was.
This was done by running TPOT 5 times and taking the best results (TPOT can have reproducibility errors). Here were our results:

| City     | Accuracy      |
| ------------- | ------------- |
| Leeds   | 58.7%         |
| Cork  | 27.2%         |

