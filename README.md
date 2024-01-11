

# Matrix Filtering: QUBO Model for Optimal Optimization of Credit Score Card Combinations

Our paper analyze the data characteristics of credit score cards and propose an optimization algorithm for compressing the target matrix through preprocessing, leveraging the repetitiveness and monotonic interval of the objective function. This approach focuses on reducing computational complexity through data preprocessing and matrix mapping. Our research reveals that this method effectively lowers time complexity, with its impact becoming more pronounced as the number of card-value combinations and the volume of data increase.

## Our Advantage
|<img align="left" width="450" height="300" src="https://github.com/DanggoRyo/Matrix-Filtering/blob/main/loss_over_time.png">|<img align="right" width="450" height="300" src="https://github.com/DanggoRyo/Matrix-Filtering/blob/main/compile_over_time.png">|
|:--:|:--:| 
| **Compute time of <br />constructing the objective function** | **Compute time of <br />converting into QUBO** |

## Requirement

``pip install -r requirement.txt``

## Usage
1. Download the test case from http://mathorcup.org/detail/2417. Your code folder be like:
~~~
code folder
└───save_csv
│   └───TIME_WASTE.csv
└───data_100.csv
└───A_1_1.ipynb
└───A_1_2.ipynb
└───A_2_1.ipynb
└───A_2_2.ipynb
└───A_3_1.ipynb
└───A_3_2.ipynb
└───requirement.txt
~~~

2. Run files with the .ipynb extension.
