---
title: Week 1 Market Efficiency
cssclasses:
  - academia
tags:
  - arbitrage
  - behavioral_biases
  - fundamental_analysis
  - market_efficiency
  - stock_prices
  - financial_theory
  - efficient_markets
aliases:
  - Efficient Markets
  - Market Anomalies
  - Market Efficiency
key_concepts:
  - Arbitrage limitations and constraints in real markets
  - Behavioral biases affecting financial decision making
  - Capital markets as a fair game under efficiency conditions
  - Cost of information acquisition and paradox of efficient markets
  - Evidence supporting and contradicting market efficiency
  - Information processing speed and market reaction to news
  - Market anomalies and their persistence over time
  - Market efficiency definition and relationship to fundamental analysis
  - Passive vs active investment strategies implications
  - Quantitative and machine learning approaches to investment
  - Random walk hypothesis and unpredictability of price movements
  - Stock prices rapidly adjusting to incorporate new information
---

# Week 1 Market Efficiency

## Market Efficiency & Fundamental Analysis

## Market Efficiency

- What is market efficiency?
    - Stock prices rapidly adjust to new information
    - New information is fully reflected in prices ⇒ trading on this information does not offer an abnormal rate of return
    - Efficiency implies that capital markets become a fair game
    - Only new information should move prices ⇒ prices follow a random walk
- Market efficiency is a relative concept
    - Defined relative to an information set
- If markets are (semi-strong form) efficient, then all publicly available information is reflected in price
    - Does it make sense to conduct fundamental analysis based on publicly available information?

## Paradox of Efficient Markets

- When information acquisition is costly, we have a paradox
    - If markets are efficient and reflect all publicly available information, then why should you engage in costly information acquisition?
    - But if nobody engages in this activity, how do markets become efficient in the first place?
- Efficiency is not an equilibrium when information is costly
    - There is always some mispricing
    - Higher returns are compensation for costly info acquisition and financial analysis
- Hedge fund industry illustrates:
    - Gains from info acquisition & analysis can be substantial
    - Strong incentives to exploit or arbitrage market inefficiencies or mispricing
    - Many anomalies that were identified are no longer profitable

## Role of Arbitrage

- Arbitrage limits the inefficiencies in markets
    - But transaction costs and institutional constraints limit arbitrage
- Arbitrage strategies may not be entirely risk-free in which case the return is partly compensation for risk
- For instance, liquidity plays an important role for arbitrage strategies and may be missing in extreme situations
    - Examples showing that sophisticated strategies can have significant risks:
        - Long Term Capital Management (Asian crisis)
        - Hedge funds and their quantitative strategies in August 2007
- Recent decline in the number of (new) hedge funds shows that the industry is very competitive

## Evidence on Market Efficiency

- Lots of evidence that markets are competitive (see Koller et al., Chapter 5)
    - Strong link between prices and fundamentals (growth, ROIC and cost of capital), especially in the long-run
    - Market's reaction to news events is almost instantaneous
    - Mutual funds are generally unable to outperform indices consistently
    - Pricing of financial information is quite sophisticated
- Yet, there are:
    - Bubbles and stock market anomalies
    - Growing evidence that behavioral biases in human decision making can survive and matter in markets (see Additional Readings on Canvas)
- Answers by IGM Economic Experts Panel reflect both aspects
    - Question 1: Strong consensus on (non-)predictability of stock prices
    - Question 2: Majority of the panel does not think that prices during Dot Com bubble were based on fundamentals alone

## IGM Economic Experts Panel

 !500

 !500

Baxter International (NYSE: BAX) is a bioscience and medical products firm headquartered in Deerfield, IL

-BAX is a member of the S&P 500

From: Cohen et al. Journal of Finance 2020

## Example Illustrating the Forces: Lazy Prices

 !500

## How Did the Market React?

 !500

### Baxter 10-K in 2008 and 2009 in Comparison

 !500

Note that the 10-K released in Feb 2010 is the one for fiscal 2009

## Example: Lazy Prices (Cohen et al. JF 2020)

- Study analyzes changes in the text of firms' 10-K filings
    - Shows that Baxter example is not an isolated case
- Investors seem to miss 10-K changes
    - Strategy going long in "Non-Changers" and short in "Changers" yields alpha of 7%
    - Even larger when using changes in the risk-factor discussion in the 10-K specifically
    - Results are across all stocks (even large ones)
- What do you predict will happen to this result?
    - Ke, Kelly and Xiu: "Predicting returns with text data"
- What do we learn?
    - There is a lot of relevant info in 10-K that is not necessarily processed
    - Paper suggests differential "laziness"
        - Earnings announcements and most accounting numbers are quickly processed 
        - Text is harder to process than numbers 
        - For text, there is not the same comparison with prior year

## My Take

- Markets price (long-run) fundamentals
    - Aggregate an enormous amount of information
- Even when stocks are priced correctly on average, there is a standard error and hence some mispricing of individual stocks at certain times
- Degree to which price reflects all publicly available information can differ across stocks and time
    - Info environment of a stock matters
    - Ability to arbitrage differs across stocks
        - Many anomalies are concentrated in small stocks
- Also, the market seems to be particularly good at relative pricing
    - But it can be off with respect to absolute (or fundamental) value
    - This is what happens in a bubble

## Bottom Line

- Fundamental analysis can be worthwhile because prices can and do deviate from fundamentals
- Arbitrage fails at times and bubbles arise
- But at the same time, there are always strong forces to exploit opportunities in the market
- You can use the same lens to understand recent trends in markets

## Fundamental Analysis and Recent Trends

## Recent Trends

- What about the trend towards passive investments and ETFs?
    - Stocks in the indices still need to be valued and priced (by somebody)
        - Remember the paradox of efficient markets
        - Less crowded field for fundamental analysis should imply larger opportunities
    - On top of that, benchmark pressures can exacerbate trends or momentum (and hence mispricing)
- What about the rise quant strategies? 
- What about machine learning and alternative data?

## Quant Investing

- Fundamental approach
    - Detailed analysis of financial statements and other data
    - Determine "fundamental" value using valuation model
    - Fundamental analysis is quantitative
- Quantitative approach uses "models" and "signals"
    - Typically conducted for large samples
    - Most of the financial statement information is taken as given
    - Most models attempt to predict future (or abnormal) returns
- Quant approach and model building requires back testing
    - Overfitting is a major risk
    - Time-varying risk premia and "shifting" asset pricing models are major challenges
- For short horizons, quant strategies and machines have largely replaced people

## "Quantamental" Approach & Machine Learning

- Combines fundamental and quant
    - Incorporate quantitative approaches as well as alternative or big data
    - Fundamental approach can leverage the machine
- "Lazy Prices" example fits this description
    - Easy to see more sophisticated applications using ML
- Fundamental concepts are still relevant for quant strategies & ML
    - Stock return data are very noisy
    - Adding structure can help with prediction and causality
    - Alternative: Use ML to predict company fundamentals

## Rise of Alternative Data

 !500

- In search of a true info advantage
    - Location, credit card, social media data, etc.
    - Used to predict sales or for eventdriven strategies (e.g., around EA)
    - Data are often messy
        - Use of ML for processing data
- My bottom line for now:
    - Fundamental analysis and active strategies continue to be relevant
    - Especially for smaller, less liquid stocks, and over longer investment horizons
    - Sloan article that is assigned for this week illustrates this (two case studies)
