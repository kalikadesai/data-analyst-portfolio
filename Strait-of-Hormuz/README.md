## Risk Analysis of a Voyage Through the Straight of Hormuz During Wartime
###### Note: this was an independent final project I completed for a Statistical Computing course in university.

## Summary
Each student was tasked with choosing any topic of interest to be investigated, related to the statistical computing methods covered in class. I chose to model the wartime insurance premiums of a cargo ship voyaging through the Strait of Hormuz during the most recent conflict. I used Monte Carlo methods to simulate multiple voyages through the strait in order to predict the insurance coverage required during a volatile time. 

## Objectives
* Research insurance rates and premiums for cargo ships
* Estimate realistic parameters for random sampling
* Create a Monte Carlo simulation for multiple voyages
* Create data visualizations to illustrate findings

## Conclusions
The expected total premium for a ship traveling through the Strait of Hormuz during wartime is approximately $17 million. Of that total, the expected war premium is approximately $10 million. This means abut 58% of the insurance premium is coming from the Additional War Risk Premium (AWRP). This is at an AWRP rate of 0.03, which is common for aggravated war risk @Reuters. The expected total loss from a voyage is about $7.8 million, but this is very variable depending on the severity of the attack. Additionally, the model estimates a 2.9% probability of a successful attack per voyage under the assumed attack frequency. For simplicity, I set a 0.05 attack probability to be equal at each point along the route. This implies multiple attack opportunities along the route. This reflects a worst-case scenario in a high-risk wartime situation. In reality, a 3% probability of a hit is very risky, which is why the total premium is so large.

The model I use to determine insurance premiums during wartime is conservative, revealing the worst-case scenario of attacks within the strait. Due to this, the probability of being hit during a voyage is about 3%, given multiple independent chances of attack. As a result, the projected insurance premium is large, indicating the high risk of a ship traveling during wartime. The Additional War Risk Premium is the majority of the cost of total insurance due to its dependence on war risk. During a high risk voyage, such as through the Strait of Hormuz during the current crisis, the risk of attack is great, exposing the necessity of surging insurance rates.

## Full Report
You can view the full analysis, including code and plots here:
[View Risk Analysis in Strait of Hormuz Report](Risk-Analysis-Strait-of-Hormuz.html)

