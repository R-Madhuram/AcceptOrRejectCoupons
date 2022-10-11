Will a Customer Accept the Coupon?¶

Imagine driving through town and a coupon is delivered to your cell phone for a restaraunt near 
where you are driving. Would you accept that coupon and take a short detour to the restaraunt? 
Would you accept the coupon but use it on a sunbsequent trip? Would you ignore the coupon entirely? 
What if the coupon was for a bar instead of a restaraunt? What about a coffee house? 
Would you accept a bar coupon with a minor passenger in the car? 
What about if it was just you and your partner in the car?
Would weather impact the rate of acceptance? What about the time of day?

Summary of Findings:

After the inital data cleaning, analysis was carried out to answer specific questions about the data using both 
visualizations and numerical analysis.(present in Jupyter Notebook: "https://github.com/R-Madhuram/AcceptOrRejectCoupons/blob/main/prompt.ipynb")

1. People who went to bar more than three times a month were almost twice more likely to use the bar coupon 
compared to people who went to bar less than three times a month to bar when both the populations 
were issued bar coupon.

2. The likelihood of people using coupon of any eatery(bar included) by people who went to bar 
less than 3 times is almost same as people who went to bar more than 3 times a month. 
However, among the people who went to bar less than three times a month there is 50% more 
likelihood them accepting an eatery coupon if there were issued with a mixture of any eatery 
coupon (including bar coupon) than just bar coupons. But among the the people who visit bar 
more than 3 times a month there isn't any difference in their acceptance of eatery or only bar coupon.

3. We also found that a chorot comprising of people who were aboove 25 years of age and who visited bar
more than once a month accepted bar coupon twice more than all others in the data set. The population 
excluding the cohort that is above 25 years of age and who vosited bar more than once a month accepted 
all eateries coupon twice as much as just the bar coupons. 

4. It was also observed that Coffee Shop coupons were offered much more on hot days - temperature ~ 80 F. 
On such cases (i.e hot days) - the rate of acceptance of Coffee House is actually higher (~10% more) than rejection rate. 
This analysis can also be extended to Cheap Restaurants.

5. Further deeper analysis might help us to provide recommendation on sending more personalised coupons to drivers
that could increase the liklihood of acceptance of the issued coupon. 