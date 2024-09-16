Randomization, or A/B testing, can be not feasible in many situations. 
<br>
For examples:
- Testing Uber cash feature:
The feature shows driver whether the trip is cash or debit/credit upfront before they can accept the request. 
Randomization is not feasible to test this feature as drivers might prefer one over the other method, say they prefer cash. (Spillover effect, SUTVA assumption is violated)

In the treatment group, when drivers see the trip is cash upfront, they tend to accept the trips, leaving the debit/credit rides to the drivers in the control group.

- Testing promotion effect on revenue:
Amazon marketplace wants to encourage sellers to have promotion during holiday season, say Chritmas, to boost revenue. However, Xmas is the purchasing season and customers can make purchases whether or not they have promotion. Thus, Amazon wants to test the effect size of promotion on revenue.

Randomization, again, is not feasible because:

1) It might be unethical to force some sellers to have sales and some to not, especially during holiday season.
2) Customers might buy from the stores that have sales, leaving no chance of buying from other stores (say, they only need to buy one). (Positivity assumption is violated)