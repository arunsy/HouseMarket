# House Market (Surprise Housing)
> Build the model with the available independent variables and help the management to understand how exactly the prices vary with these variables when entering new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Business problem is predict and set the price of houses with the available independent variables and help the management to understand how exactly the prices vary with the variables. So management can set the strategy of the firm and concentrate on areas that will yield high returns as well as understand the pricing dynamics of a new market.

- train.csv dataset has used to analyse this scenario.

<!-- You don't have to answer all the questions - the ones relevant to your project. -->

## Conclusions
- We analysed the factors affecting the sale price of houses on new market using Linear regresssion, Ridge and Lasso regression models. We evaluated the model based on R2, RSS & RSME metric.

- From Ridge model, we can predict the results with approx 72% variance on the unseen data. We identified the few variables which has high impact on setting the sale price of the house.

    - > Ground living area
    - > Overall condition, material & finish of the house
    - > First floor and Second floor
    - > Total basement area
    - > North ridge and North ridge heights neighborhood
    - > Wood shingle roofs
    - > Basement Type-1 finish
    - > Good exposure to walkout and green level walls
    - > Lot areasize
    - > Masonry veneer area
    - > Original construction date
    - > Size of garage in car capacity
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- JupyterLab 3.3.2
- Python 3.9.12
- Pandas
- Matplotlib
- Seaborn
- SciKit-Learn
- Stats Models

<!-- As the libraries versions keep on changing, it recommends to mention the version of library used in this project -->

## Acknowledgements
- This project inspired by Surprise Housing (House Resale platform).

<br>

> Documented by [@arunsy](http://github.com/arunsy) - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->