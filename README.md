# Elements-Of-Statistical-Learning

Select solutions and code relating to Elements Of Statistical Learning by Hastie, Tibishani, and Friedman

|Chapter|Questions| Number |
|-------|---------| ------- |
|**2** | 2.1 - 2.4, 2.6| 5 |
|**3** | 3.1, 3.3 - 3.6,<br> 3.9 - 3.13, 3.19,<br>3.23 - 3.25, 3.29, 3.30| 15 |
|**4** | 4.1 - 4.3, 4.6, 4.7| 5|
|**5** | 5.1, 5.4, 5.7, 5.9, 5.12| 5 |
|**6** | 6.1, 6.2, 6.5, 6.7, 6.8| 5 |
|**7** | 7.1 - 7.7| 7 |


## Errata
On page 267 of the 2nd edition, between (8.21) and (8.22) there is the claim:
"The information matrix for <img src="https://render.githubusercontent.com/render/math?math=\theta = (\beta, \sigma^2)"> is block-diagonal..."

This claim only holds for <img src="https://render.githubusercontent.com/render/math?math=\theta = \hat{\theta}">, the maximum likelihood estimate, as the non-diagonal terms are mutliples of <img src="https://render.githubusercontent.com/render/math?math=H^T(y-H\beta)">, which vanishes at <img src="https://render.githubusercontent.com/render/math?math=\hat{\theta}">
