# VBA-Challenge
Analyzing a dataset with stock market titles
  
## 1. Project overview
Steve's parents are investing on the renewable market. They targeted a unique company, DAQO New Energy Corporation. However Steve would like them to diversify his parents' portfolio in order to minimize their risk exposure.
We have a dataset with stock market performances for twelve companies during 2017 and 2018. We have already presented our tool to Steve and highlighted the necessity for his parents to diversify their portfolio.
Furthermore, Steve would like a relevant tool to expand the dataset to include the entire stock market over the last few years. The purpose of this project is to optimize our code in order to reduce the number of steps, use less memory, and being able to use it on a bigger dataset.
  
## 2. Presentation of the findings
  
### 2.1 Overall Down turn performances in 2018
The year 2017 was a successful year for the renewable companies on the stock market. The vast majority of the companies outperformed. DQ had the highest return on investment with a growth around 200%.
  
Stock market performances in 2017
  
![Stock market perf_2017](https://user-images.githubusercontent.com/85641189/123642591-14212380-d7e9-11eb-9183-952870c567f1.png)
  
In 2018, the overall stock market faced a down turn of its performances. DAQO's stock market title was also impacted with a decrease of 62,6% of the yearly return on investment. However, two companies, ENPH and RUN, successfully improved their performances with positive growth during 2018.
  
Stock market performances in 2018
  
![Stock market perf_2018](https://user-images.githubusercontent.com/85641189/123642626-20a57c00-d7e9-11eb-9b9f-2f7318a174a7.png)
  
This situation highlights the volatility of the renewable stock market and confirm the necessity for Steve's parents to diversify their portfolio.
  
### 2.2 Successful improvement of the execution time of the script
Our refactoring code is definitly more relevant for a bigger dataset. If our first code was executed in less than 1 second, this refactoring code runs in milliseconds. 
  
Running time for our first code for 2017
  
![Own code_2017](https://user-images.githubusercontent.com/85641189/123646180-995a0780-d7ec-11eb-8534-c15a9a681d23.png)
Running time for our first code for 2018
  
![Own code_2018](https://user-images.githubusercontent.com/85641189/123646521-e8a03800-d7ec-11eb-9afd-7f4cf17b24a1.png)
  
It will be a gain of time and memory in case Steve works on a dataset including the whole stock market.
  
Running time for the refactored code for 2017
  
![Refactor time_2017](https://user-images.githubusercontent.com/85641189/123646298-b393e580-d7ec-11eb-97dd-a92cebe1972a.png)
Running time for the refactored code for 2018
  
![Refactor time_2018](https://user-images.githubusercontent.com/85641189/123646596-fb1a7180-d7ec-11eb-9625-5c2831931db0.png)
  
## 3. Feedback on the refactoring process
  
### 3.1 Advantages and disadvantages of refactoring codes
Ww can read in the computer litterature that the purpose of refactoring a code is to have an easier code to understand or to read. A refactoring code is also less complex and easier to maintain. 
However, it is time consuming. And you are also not sure to succeed in your refactoring process.
  
### 3.2 How does it apply to Stve's project
Refactoring our first code was time consuming. However, the optimization is significant because we reduced the running time for the code. The refactoring process was also necessary in order to answer Steve's needs. Our first code was adapted only for the twelve stock market titles we had in our dataset. In order to extend the code and our analysis to the entire stock market, we had to refactor the code and introduce a new variable ( Dim tickerIndex As Integer, tickerIndex = 0). This refactored code will be easier to maintain because it is already adapted to a global situation and not a specific one as Steve's problem.
