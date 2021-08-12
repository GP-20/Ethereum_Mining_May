# Ethereum Mining
In this repository, you can find a simple explanatory analysis regarding miners and block rewards on the Ethereum blockchain during May. The data was scraped from the Etherscan API.

## Requirements
The following libraries are required:

* datetime
* etherscan
* dotenv
* pandas 
* numpy 
* matplotlib 
* seaborn 

## Results
* The average number of blocks per day was **6,460**.
* **89** unique addresses mined Ethereum.
* The top five pools mined **61%** of the total blocks.
* The total block rewards were **711,014.6 ETH**, which currently are worth **$2,296,790,482 USD**.
* The average block reward was **3.55 ETH**.
* The Pearson correlation between the block rewards and the intraday volatility is **0.46**.

## Graphs
 During May, the top five pools were responsible for more than 60% of all the Ethereum mined, although we can notice that the top two pools, "Spark pool", and "Ethermine" are way ahead of the other pools in terms of revenue.

![Top 5](https://github.com/GP-20/Ethereum_Mining_May/blob/main/Images/Top%205%20pools.png?raw=true)

On this graph, we can see the relationship between the block rewards and the intraday volatility, Pearson's correlation coefficient is 0.46, which indicates some positive relationship between these two variables. During times of high volatility is possible to see a surge in gas prices, which increases the block reward, so this relationship seems plausible.

![Rewards vs volatility](https://github.com/GP-20/Ethereum_Mining_May/blob/main/Images/Mining%20rewards%20and%20volatility.png?raw=true)