# NFT Market Analysis - Group 4

## Project Overview

Analyzing data from the US Stock Market, NFT Marketplace, and Crypto Market to identify data driven trends in the NFT market. We will look to answer the following research questions.

1. How do fluctuating ETH gas prices affect NFTs and ETH prices?
2. What kind of dollar volumes do the chosen NFTs have?
3. What are the price trends for NFTs and what can you expect if you choose to invest?
4. What does the landscape of NFT buyers and sellers look like?
5. How are the new Bitcoin ETF and more volatile ETFs performing? Does this mean anything for potential future NFT ETFs?
6. What kind of trading volumes do the chosen NFTs have compared to ETH and ETFs ?
The following sections provide discussions and answer each quetion.

## Broader Market Analysis

Here we wanted to compare the volume of select tech and crypto based ETFs vs select NFT collections. Established ETF QQQ, which is compromised of blue chip stocks like Apple, Amazon, Google, etc., dwarfs the other assets on a daily volume basis. The only asset to match QQQ in daily volume was BITO, the first bitcoin ETF, on it's first trading day. However, it quickly regressed back into a volume range in line with the other emerging NFTs and ETFs we plotted.

The NFT projects we tracked all traded in the 5 million in volume range.

![Volume_comparison_all_assets](https://user-images.githubusercontent.com/91380617/142706479-cec31381-e976-4ae5-94ca-3f3cec1ebf86.png)

During our inital discussion for our project we determined that analyzing the impact of Ethereum gas prices could be a significant factor in determining how NFTs were purchased given that most popular NFTs are built on the Ethereum blockchain. Looking at the below plot it's clear there is a positive correlation between the increase in Ethereum price and the increase in gas prices (converted to USD). This would make sense given that as Ethereum increases in price the demand for the blockchain and ultimate usage would increase thus driving gas prices upward. What stuck out most on this plot was the wide spread of data points once Ethereum crosses 2000 USD. 

![ETH_close_vs_gas_prices](https://user-images.githubusercontent.com/91380617/142706524-af9fd392-8be0-4c43-8ec7-c8918ce523f9.png)

## NFT Market Analysis

### NFT Buyers and Sellers
We ran the data that we pulled from the Opensea API and tracked buys and sells across the three collections that we tracked. At first glance, it would appear that both graphs are the same. However, you'll notice that there a number of large buyers across the three tracked NFT collections (tallying buyers in the 100-150, 150-200 and 250-300 thresholds). This would indicate that there are individuals with very high conviction on these projects purchasing a very large quantity of the NFTs.

It would seem that the average buyer (5-10 for both buys and sells) does not hold these NFTs for long and ends up selling the NFT.

![Number_of_nft_buyers](https://user-images.githubusercontent.com/91380617/142706690-bac37e63-a209-4f28-b360-aca2ef0e1df9.png)

![Number_of_nft_sellers](https://user-images.githubusercontent.com/91380617/142706700-037d05c9-5866-46e3-9d3a-0a71da856c08.png)

### Entry Level Summary Statistics 
The below was a function we ran to calculate summary statistics and price data across the three collections we explored over the previous month. The goal here is to take these numbers to provide entry level data for prospective buyers into these collections.

![NFT_Entry_Point_Statistics](https://user-images.githubusercontent.com/91380617/142707479-c4bcb83e-f8e5-421c-b3be-aebf012b04ce.png)

### How Has the Price Changed Over Time for These Collections?
How has the price changed over time for these collections? Here we explored USD sales data for the NFT collections dating back to November of 2020. Unfortunately, these collections were not available prior to this date so this is the available historical data. 

The first takeway on these charts is the explosion in sales after 5/2/21. The plots below on both a zoomed and unzoomed basis show exponential growth of individual sales after this date. The number of six figure sales (USD) is remarkable.  

The second takeaway is the distribution of plot points. There seems to be two consolidations of data points after 5/2/21. There seems to be a groupings above 150,000(USD) and below 50,000 (USD)

![NFT_sale_prices_over_time](https://user-images.githubusercontent.com/91380617/142706560-5a6159b2-ab2e-4bc4-ae24-36ef9f95455b.png)

![NFT_sale_prices_over_time_zoomed](https://user-images.githubusercontent.com/91380617/142706570-9824c5dd-1903-4418-85e1-a488a5772e4e.png)

### How Has ETH Gas Pricing Impacted NFT Purchases?
To plot this graph we aggregated total volume across the selected NFT collections and set the Y axis to Gas price. There was a heavy consolidation of data points in the lower left quadrant which indicates that NFT volume was LOW when gas prices were low. Our group was surprised at this finding because our inital thought prior to plotting was that volume would be HIGH when gas prices were low.

![Gas_price_effects_on_nft_vol](https://user-images.githubusercontent.com/91380617/142706547-28f909a8-5269-4574-ae40-3dffc78963ae.png)

## ETF Market Analysis

### ETF Volume and Return Data Exploration
An important part of our research was to compare NFTs to a traditional asset. Our goal here was to provide a benchmark to what NFTs could possibly become as an emerging asset class.

We settled on five ETFs that were more volatile historically than most. However, when reviewing the ETF data it's very clear that both volume and volatility is much more stable than what we have previously seen exploring the NFT data. 

BITO, a newly launched ETF, which is composed of BITCOIN backed assets was one ETF that should track with NFTs positively given both are crypto assets. The downside here was that BITO only began trading on 10/21/21. Based on the limited data it does appear to track the overall crypto market.

![ETF_closing_prices](https://user-images.githubusercontent.com/91380617/142706977-32804a69-7be2-426a-9d2a-c51946796d46.png)


![ETF_percent_returns](https://user-images.githubusercontent.com/91380617/142707162-fe364745-a8fe-4d67-b95d-5353f636a6ee.png)


# Conclusion - What did the data tell us?

- NFT volume across the explored projects was incredibly low relative to ETF volume. Perhaps a better comparison would have been to compare to another asset class entirely? Art?

- Wide Spread of Ethereum gas prices as ETH rises in price. You would think that the data points would be more strongly correlated as ethereum rises in price. Possible explaination / hypothesis of individuals holding ETH as price rises thus curbing the actual usage on the blockchain?

- Why did ETH gas pricing not have an strong positive correllation with NFT volume? Possible explanation could be that due to these collections being limited releases (typically 10,000 count or fewer per collection) that individuals do not have the luxury of waiting for gas prices to reduce to purchase.

- Explosion of NFT sales after 5/1/21. Did mainstream interest in NFT projects drive the uneducated buyer into investing? Facebook had been linked to Metaverse projects, Gamestop is working on an NFT platform, various celebrities have purchased NFTs as social media avatars. 

- NFTs are not equal. See distribution of NFT sales data on Price of NFT Sales over time. What makes these individual NFTs more valuable than the others? Combination of rarity traits, popularity, 

- Evidence of a few large "whale" buyers among the three tracked NFT projects (tallying buyers in the 100-150, 150-200 and 250-300 thresholds).   

- Most common distribution across buying and selling is 5-10 NFTs for the buy and sell bar charts indicating that the average buyer is not holding NFTs long term.


