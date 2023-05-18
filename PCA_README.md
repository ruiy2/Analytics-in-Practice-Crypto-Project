# PCA
# Co-Authors Bailee Hanson and Rui Yu

READ ME 

We conducted analysis on major drivers of price chanages in Cryptos. 
In order to use a diverse portfolio, we included major cryptos as wells as cryptos of Defi, NFT and Metaverse in our PCA. Please find the coins we used listed as follows: 
Bitcoin (BTC), Solana(SOL), Polygon (Matic), Ethereum (ETH), XRP(XRP), Dogecoin(DOGE), Cardano(AdA), TRON(TRX), Litecoin (LTC), Uniswap(UNI), Avalanche (AVAX), Chainlink (LINK), Internet Computer (ICP), Apecoin (APE), Decentraland (MANA), Theta Network (THETA), Stacks (STX), Polkadot (DOT), Sushi swap (SUSHI), Gold (GLD), USD (DX-Y.NYB)

We anticipated that the crypto market performs differently during the bull run (Data from 2021/5/10-2021/12/31) vs the winter (Data from 2022/1/3-present). We ran PCA over two different periods to see whether common drivers of cryptos behave differently during different periods. 

To choose an appropriate number of factors to use, we created scree plots for both time periods. Then, we chose the elbow accordingly and used 2 factors for our PCA. 

Factor 1: We can see that factor 1 is positively correlated with all cryptos and the magnitude of correlation does not vary greatly between crypto winter and bull run. Therefore it is a long-run factor that does not change greatly with short-run fluactuations. 

Factor 2: Given the large positive correlation between USD price and factor 2 as well as the large negative correlation between gold price and factor 2, we think factor 2 is related to USD strength. 
