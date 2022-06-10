# Fair Value Hedge

A fair value hedge is a hedge of the exposure to changes in the fair value of a recognized asset, liability, or unrecognized firm commitment. Changes in fair value of derivatives that do not meet the criteria of one of these three categories of hedges are included in income. 

When hedging exposures associated with the price of an asset, liability, or firm commitment, the total gain or loss on the derivative is recorded in earnings. In addition, the underlying exposure due to the risk being hedged must also be marked-to-market to the extent of the change due to the risk being hedged; and these results flow through current income as well. This treatment is called a fair value hedge.


Hedgers may elect to hedge all or a specific identified portion of any potential hedged item. Fair value hedge accounting is not automatic. Specific criteria must be satisfied both at the inception of the hedge and on an ongoing basis. If, after initially qualifying for fair value accounting, the criteria for hedge accounting stop being satisfied, hedge accounting is no longer appropriate. 

With the discontinuation of hedge accounting, gains or losses on the derivative will continue to be recorded in earnings, but no further basis adjustments to the original hedged item would be made. Reporting entities have complete discretion to de-designate fair value hedge relationships at will and later re-designate them, assuming all hedge criteria remain. 

At inception, there must be formal documentation (designation) of the hedging relationship and the entity’s risk management objective and strategy for undertaking the hedge, including identification of the derivative, the related hedged item, the nature of the particular risk being hedged, and how the hedging instrument’s effectiveness will be assessed – including any decision to exclude certain components of a specific derivative’s change in fair value, such as time value, from the assessment of hedge effectiveness.

A change in the fair value of the hedged item must present an exposure to the earnings of the reporting entity. Fair value hedge accounting is permitted when cross currency interest rate swaps result in the entity being exposed to a variable rate of interest in the functional currency.

Generates the risk attributed fair value for the hedged item and hedging derivative. The risk attributed fair value for the hedged item is computed using the benchmark curve, rather than the true mark-to-market curve; therefore, the computed fair value will vary from the true mark-to-market value. 

For each hedging program, there are pairs of positions, namely the hedged items and the hedging derivatives, of which the latter are used to reduce the volatility of the period-over-period fair value (cash flow) changes of the former positions. 

Assuming a hedge program is effective, the fair value (cash flow) change of the hedged item over a specified period (i.e. a quarter) should be in the same magnitude as the fair value (cash flow) change of the hedging derivative over the same period, but with an opposite sign (due to natural inverse relationship).  

This causes the overall fair value (cash flow) of the hedge pair to either remain unchanged or change very little over time. This feature should remain constant for virtually any kind of interest rate changes over a specified period.  

In conducting the retrospective test, the model utilizes the Portfolio Return (PR) to measure hedge effectiveness. The Portfolio Return is a hindsight measure that assesses the period-over-period change of the hedged pair relative to the initial value of the hedged item. Given that the objective of fair value hedging is to keep the fair value of the hedged item stable, we establish a tolerable threshold of +/- 5% relative to the initial fair value of the hedged item as the operational definition of stable.

The prospective test aims to determine whether a hedge will be effective in the coming period (quarter). As the fair value of a hedged item and a hedging derivative are unobservable in the future, scenario generation is an effective way of assessing the effectiveness of hedging positions. 

In prospective testing, we generate 50 historical interest shocks over a period (quarter) and apply the shocks to the current term structure to obtain the term structures for the next review period, and in turn calculate the fair values of the positions at the next period using the generated term structures. 

In assessing the prospective test, the model utilizes the Correlation coefficient to measure hedging effectiveness due to its mainstream acceptance as a relevant performance benchmark. As a means of supporting the Correlation coefficient effectiveness test result, the model generates the Beta coefficient and R2 statistic. 

Also, the Mean Portfolio Return is generated as an additional reference measure, allowing the model to establish a level of continuity between the retrospective and prospective tests in the process.

The Correlation coefficient () represents the extent to which fair value changes in the hedged item are associated with fair value changes in the hedging derivative. Therefore, this goodness of fit statistic measures the effectiveness of the “optimal hedge” over the sample period investigated. 

Presumably, a higher  would lead to greater confidence that the optimal hedge will be highly effective. We must note that the  statistic is more meaningful if it is used in conjunction with the “actual hedge”, indicated by the Beta coefficient of the regression equation.

In calculating the mean portfolio return (MPR), the average risk attributed fair value of the hedge pair is computed using the 50 scenarios generated in the historical simulation. The mean portfolio return is parallel to the portfolio return in the retrospective test, providing information regarding the fair value changes of the hedge pair relative to the initial value of the hedged item.


Reference:

https://finpricing.com/lib/EqBarrier.html

https://zenodo.org/record/6547047/files/fairValueHedge.pdf

https://zenodo.org/record/6547047#.YpDvGKgpDq4



