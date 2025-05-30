---
tags:
  - arbitrage_free_pricing
  - binomial_model
  - law_of_one_price
  - redundant_assets
  - replicating_portfolio
aliases:
  - Asset Pricing
  - Redundant Asset
  - Replicating Portfolio
key_concepts:
  - Arbitrage-free price
  - Law of one price
  - Multi-period model redundancy
  - Pricing non-redundant assets
  - Redundant asset definition
  - Replicating portfolio creation
---

# 3.5 Redundant assets  

An asset is said to be redundant if its dividends can be replicated by a trading strategy in other assets.  

For example, in the one-period framework asset $i$ is redundant if a portfolio. $\pmb\theta=(\theta_{1},\dots,\theta_{I})^{\top}$ exists with $\theta_{i}=0$ and  
$$
D_{i}=D^{\theta}\equiv\theta_{1}D_{1}+\cdot\cdot\cdot+\theta_{i-1}D_{i-1}+\theta_{i+1}D_{i+1}+\cdot\cdot\cdot+\theta_{I}D_{I}.
$$  

Recall that the dividends are random variables so the above equation really means that  
$$
D_{i}(\omega)=\theta_{1}D_{1}(\omega)+\cdot\cdot\cdot+\theta_{i-1}D_{i-1}(\omega)+\theta_{i+1}D_{i+1}(\omega)+\cdot\cdot\cdot+\theta_{I}D_{I}(\omega),\quad\forall\omega\in\Omega.
$$  

Such a portfolio is called a replicating portfolio for asset $i$  

If an asset $i$ is redundant, its price follows immediately from the law of one price:  
$$
P_{i}=\theta_{1}P_{1}+\cdot\cdot\cdot+\theta_{i-1}P_{i-1}+\theta_{i+1}P_{i+1}+\cdot\cdot\cdot+\theta_{I}P_{I}.
$$  

We can thus focus on pricing the non-redundant assets, then the prices of all the other assets, the redundant assets, follow.  

Note that the number of non-redundant assets cannot exceed the number of states. If there are more assets than states, there will be some redundant asset.  

Example 3.1 Consider a one-period economy with three possible end-of-period states and four traded assets. The dividends are given in Table 3.1. With four assets and three states at least one  

Table 3.1: The state-contingent dividends of the assets considered in Example 3.1.   


<html><body><table><tr><td></td><td colspan="3">state-contingent dividend</td></tr><tr><td></td><td>state 1</td><td>state 2</td><td>state3</td></tr><tr><td>Asset 1</td><td>1</td><td>1</td><td>1</td></tr><tr><td>Asset 2</td><td>0</td><td>1</td><td>2</td></tr><tr><td>Asset3</td><td>4</td><td>0</td><td>1</td></tr><tr><td>Asset 4</td><td>9</td><td>0</td><td>1</td></tr></table></body></html>  

asset is redundant. The dividend vector of asset 4 can be written as a non-trivial linear combination of the dividend vectors of assets 1, 2, and 3 since  
$$
{\Bigg(}{\begin{array}{l}{9}\ {0}\ {1}\end{array}}{\Bigg)}={\Bigg(}{\begin{array}{l}{1}\ {1}\ {1}\end{array}}{\Bigg)}-{\Bigg(}{\begin{array}{l}{0}\ {1}\ {2}\end{array}}{\Bigg)}+2{\Bigg(}{\begin{array}{l}{4}\ {0}\ {1}\end{array}}{\Bigg)}~.
$$  

A portfolio of one unit of asset 1, minus one unit of asset 2, and two units of asset 3 perfectly replicates the dividend of asset 4, which is therefore redundant. In terms of random variables, we have the relation  
$$
D_{1}-D_{2}+2D_{3}=D_{4}
$$  

among the dividends of the four assets. On the other hand, asset $^{1}$ is redundant since it can be perfectly replicated by a portfolio of one unit of asset 2, minus two units of asset 3, and one unit of asset 4. Similarly, asset 2 is redundant and asset 3 is redundant. Hence, either of the four assets can be removed without affecting the set of dividend vectors that can be generated by forming portfolios. Note that once one of the assets has been removed, neither of the three remaining assets will be redundant anymore. Whether an asset is redundant or not depends on the set of other assets available for trade. This implies that we must remove redundant assets one by one: first we remove one redundant asset, then we look for another asset which is still redundant - if we find one, we can remove that, etc.  

In the multi-period model an asset is said to be redundant if its dividend process can be generated by a trading strategy in the other assets. In the discrete-time framework, asset $i$ is redundant if there exists a trading strategy $\pmb{\theta}$ with $\theta_{i t}=0$ for all $t$ and all $\omega$ so that  
$$
D_{i t}=D_{t}^{\theta}\equiv\theta_{t-1}\cdot(D_{t}+P_{t})-\theta_{t}\cdot P_{t},\quad t=1,\ldots,T.
$$  

Such a $\pmb{\theta}$ is called a replicating trading strategy for asset $i$  

Just as in the one-period setting, redundant assets are uniquely priced by no-arbitrage.  

Theorem 3.1 If $\pmb{\theta}$ is a replicating trading strategy for asset $i$ , the unique arbitrage-free price of asset i at any time t is  
$$
P_{i t}=\pmb{\theta}_{t}\cdot\pmb{P}_{t}.
$$  

Proof: The trading strategy $\hat{\pmb{\theta}}$ defined by. $\hat{{\pmb\theta}}_{t}={\pmb\theta}_{t}-{\pmb e}_{i}$ , where $e_{i}=(0,\ldots,0,1,0,\ldots,0)^{\top}$ , is self-financing and $V_{T}^{\tilde{\theta}}=0$ . No-arbitrage implies that $V_{t}^{\tilde{\theta}}=0$ . The result now follows since $V_{t}^{\tilde{\theta}}=$  
$$
\widehat{\pmb{\theta}}_{t}\cdot\pmb{P}_{t}=\pmb{\theta}_{t}\cdot\pmb{P}_{t}-\pmb{P}_{i t}
$$  

The above definition of redundancy can be generalized to a continuous-time setting, where the theorem is also valid..  

The theorem is useful for the pricing of derivatives and applied, e.g., in the Cox, Ross, and Rubinstein (1979) binomial model (see Exercise 3.1 at the end of this chapter) and the Black and Scholes (1973) continuous-time model for the pricing of stock options.
