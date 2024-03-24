# Costs

Current price structures of contact lenses are by box, where each box $b$ contains $l$ lenses for $p$ price, with each individual lense identically lasting up to $d$ days. The goal of this project is to normalize these variables into the total expenses over any period of time, or $c/t$. 

In other words, this project aims to automatically calculate how much it costs to use a particular set of contact lenses by year, month, or days.

## Time used per box

Assuming each lenses are worn for the same amount of time, using one box $b$ completely will take $l*d$ days. 

## Cost per set

An person buying contacts must buy one set of boxes, $2b$, to account for both the left eye and right eye. Since both boxes are used simultaneously, the total time used for them are $l*d$ days. Assuming each box are identically priced, the average cost of using one set completely is $\dfrac{2p}{l*d}$.

## Estimating total expenses over time
By assuming the total cost to buy one set of contact lenses as expenses and the period required to finish the set as time in days, or $c=2p$ and $t=l*d$, the total expenses over any period of time can be estimated in days, months, or years:

$$\dfrac{c}{t} = \dfrac{2p}{l*d} \text{ (in days)}$$

$$= \dfrac{2p}{l*d} * \dfrac{30 \text{ days}}{1 \text{ month}} \text{ (in months)}$$

$$= \dfrac{2p}{l*d} * \dfrac{365 \text{ days}}{1 \text{ year}} \text{ (in years)}$$

