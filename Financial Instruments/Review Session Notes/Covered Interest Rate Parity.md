---
cssclasses:
  - academia
linter-yaml-title-alias: Covered Interest Rate Parity
title: Covered Interest Rate Parity
tags:
  - covered_interest_rate_parity
  - currency_security
  - exchange_rate
  - forward_rate
  - model_parameters
  - no_arbitrage
  - foreign_exchange
  - international_finance
aliases:
  - CIRP
  - Interest Rate Parity
  - Currency Forward Pricing
key_concepts:
  - Currency exchange mechanics
  - Exchange rate units conventions
  - Forward rate calculation
  - No-arbitrage condition
  - Investment strategy comparison
  - Home and foreign interest rates
  - Continuous compounding
  - Forward contract pricing
---


# Covered Interest Rate Parity
## 1. MODEL PARAMETERS

There are four model parameters that collectively determine the forward rate for a currency security.

[^1]: Home/Foreign Exchange rate: $M$
[^2]: Interest rate in home country: $r_\$$
[^3]: Interest rate in foreign country: $r_\text{€}$
[^4]: Maturity: $T$

The interest rates $(r_\$, r_\text{€})$ are continuously compounded. The exchange rate $M$ denotes the number of units of the Home currency required to purchase one unit of the Foreign currency. For example, if $M = 1.2$, then 1.2 units of the Home currency (e.g., USD) are required to purchase one unit of the Foreign currency (e.g., EUR).

## 2. FORWARD RATE UNDER NO-ARBITRAGE

Determining the forward rate of a currency security requires appealing to a no-arbitrage argument. Consider an investor in the home country, endowed with capital $N$ (measured in the home currency) to invest. This investor can pursue one of two strategies.

First, the investor can invest the home capital at the home interest rate until maturity. Let $\Pi_\$(r_\$, T, N)$ denote the payoff function from this investment strategy:
$$\Pi_\$(r_\$, T, N) = e^{(r_\$ \cdot T)} \cdot N$$

Second, the investor can convert the home capital into foreign capital, invest the foreign capital at the foreign interest rate, and convert the proceeds on the foreign capital back into the home currency at the forward rate $F$:
$$\Pi_\text{€}(F; r_\text{€}, T, N, M) = e^{(r_\text{€} \cdot T)} \cdot \frac{N}{M} \cdot F$$

Note that both payoff functions, $\Pi_\$(\cdot)$ and $\Pi_\text{€}(\cdot)$, are measured in the home currency (e.g., USD).

The forward rate $F$ adjusts so as to equate the payoffs from the two investment strategies:
$$\Pi_\$(r_\$, T, N) = \Pi_\text{€}(F; r_\text{€}, T, M, N)$$

This equation is a "no-arbitrage" condition. Solving the no-arbitrage condition for the endogenous variable $F$ yields the covered interest-rate parity formula for the forward rate:
$$F = e^{(r_\$ - r_\text{€}) \cdot T} \cdot M$$

Note that the forward rate $F$ inherits the units of the exchange rate $M$. Since the units of the exchange rate $M$ is Home/Foreign (e.g., USD/EUR), it follows that the units of the forward rate $F$ is also Home/Foreign.

## 3. INTERPRETATION

The forward rate $F$ is the exchange rate at which Home and Foreign currencies are exchanged upon maturity at time $T$ from inception. The forward rate $F$ is agreed upon at inception (i.e., at time 0).
