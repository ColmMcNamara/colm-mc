#Sharpe Ratio


 The Sharpe Ratio is a mathematical method to examine the performance of an investment by adjusting the price. The ratio measures the excess return (or risk premium) per unit of deviation in an investment asset or a trading strategy.

##Sharpe Ratio Uses:
 The Sharpe ratio characterizes how well the return of an asset compensates the investor for the risk taken. When comparing two assets versus a common benchmark, the one with a higher Sharpe ratio provides better return for the same risk (or, equivalently, the same return for lower risk). However, like any other mathematical model, it relies on the data being correct.Sharpe ratio is defined as, 
 
 S_a = \frac{E[R_a-R_b]}{\sigma_a} = \frac{E[R_a-R_b]}{\sqrt{\mathrm{var}[R_a-R_b]}},
 
 where 
 {\displaystyle R_{a}} R_{a} is the asset return, 
 {\displaystyle R_{b}} R_b is the risk free rate. 
 {\displaystyle E[R_{a}-R_{b}]} E[R_a-R_b] is the expected value of the excess of the asset return over the benchmark return, 
 {\displaystyle {\sigma _{a}}} {\displaystyle {\sigma _{a}}} is the standard deviation of the asset excess return.

When examining the investment performance of assets with smoothing of returns (such as with-profits funds) the Sharpe ratio should be derived from the performance of the underlying assets rather than the fund returns.

###History:
 In 1952, Arthur D. Roy suggested maximizing the ratio "(m-d)/σ", where m is expected gross return, d is some "disaster level" (a.k.a., minimum acceptable return, or MAR) and σ is standard deviation of returns.
 This rate was edited by Sharpe and a new ratio was used to incorporate risk. In 1966, William F. Sharpe developed what is now known as the Sharpe ratio.[1] Sharpe originally called it the "reward-to-variability" ratio before it began being called the Sharpe ratio by later academics and financial operators. The definition was:

{\displaystyle S={\frac {E[R-R_{f}]}{\sqrt {\mathrm {var} [R]}}}.} S = \frac{E[R-R_f]}{\sqrt{\mathrm{var}[R]}}.

Sharpe's 1994 revision acknowledged that the basis of comparison should be an applicable benchmark, which changes with time. After this revision, the definition is:

{\displaystyle S={\frac {E[R-R_{b}]}{\sqrt {\mathrm {var} [R-R_{b}]}}}.} S = \frac{E[R-R_b]}{\sqrt{\mathrm{var}[R-R_b]}}.

####Strengths and Weaknesses of the ratio:
 The main complaint is this ratio relies on the notions that risk equals volatility and that volatility is bad. Simple logic will tell you that the more you reduce volatility, the less likely you are to be able to capture higher returns. But the bigger problem for the Sharpe ratio is that it treats all volatility the same. Basically, the ratio penalizes strategies that have upside volatility (i.e., big positive returns), but those that developed other risk adjusted ratios just don’t think big positive returns should be viewed as a negative thing. The Sharpe ratio has as its principal advantage that it is directly computable from any observed series of returns without need for additional information surrounding the source of profitability. Other ratios such as the bias ratio have recently been introduced into the literature to handle cases where the observed volatility may be an especially poor proxy for the risk inherent in a time-series of observed returns.
An alternative to the Shapre Ratio is the Sortino Ratio, this is just a variation of the sharpe ratio. The Sortino ratio measures the risk-adjusted return of an investment asset, portfolio, or strategy.[1] It is a modification of the Sharpe ratio but penalizes only those returns falling below a user-specified target or required rate of return, while the Sharpe ratio penalizes both upside and downside volatility equally.
The ratio {\displaystyle S} S is calculated as

{\displaystyle S={\frac {R-T}{DR}}} S={\frac  {R-T}{DR}} ,

where {\displaystyle R} R is the asset or portfolio average realized return, {\displaystyle T} T is the target or required rate of return for the investment strategy under consideration (originally called the minimum acceptable return MAR), and {\displaystyle DR} DR is the target semi-deviation (the square root of target semi-variance), termed downside deviation. {\displaystyle S} S is expressed in percentages and therefore allows for rankings in the same way as standard deviation.
An intuitive way to view downside risk is the annualized standard deviation of returns below the target. Another is the square root of the probability-weighted squared below-target returns. The squaring of the below-target returns has the effect of penalizing failures at a quadratic rate. This is consistent with observations made on the behavior of individual decision making under uncertainty.

{\displaystyle DR={\sqrt {\int _{-\infty }^{T}(T-r)^{2}f(r)\,dr}}} DR={\sqrt  {\int _{{-\infty }}^{T}(T-r)^{2}f(r)\,dr}}

#####Useage of Sorentino:
The Sortino ratio is used to score a portfolio's risk-adjusted returns relative to an investment target using downside risk. This is analogous to the Sharpe ratio, which scores risk-adjusted returns relative to the risk-free rate using standard deviation. When return distributions are near symmetrical and the target return is close to the distribution median, these two measure will produce similar results. As skewness increases and targets vary from the median, results can be expected to show dramatic differences.
