# MODULE_5

## Project: Will Customer Accept the Cupon?

### Executive Summary
This project analyzes a dataset containing survey responses regarding whether a driver would accept various coupons (i.e. Bars, Coffee Houses, Carry Away, Cheap Restaurants and Expensive Restaurants) based on their current context (i.e. destination, passanger, weather, temperature, time, gender, age and expiration).

### Key Findings on "Coffee House" Coupons

### The optimum time window for Coffee
This analysis shows that coffee coupon acceptance peaks during **10AM and 2PM**. 
This suggests drivers view coffee as a mid-morning break or an afternoon "boost"

### Environmental & Social Factors
* **Weather:** Acceptance rates are significantly higher on **Rainy** days followed by Sunny or Snowy conditions
* **"Kids" factor:** Drivers with no children in the car are more likely to accept coffee coupons, probably because convenience while making the extra stop with passengers
* **Expiration:** Coupons with a **1 day expiration** slightly outperformed the 2 hr wondow coupons, indicating drivers value flexibility

### Demographic Insights
* **Age vs Income:** Using a heatmap analysis, we identified that **younger drivers (21 - 26)** across various income levels are the most frequent adopters of Coffee House coupons
* **Gender:** The distribution of Male and Female adopters of Coffee House coupons is very even with Males displaying slightly higher uptick on rainy days (i.e. ~5% higher)

### Visualizations
![Time Window](images/barplot7.png)
*Figure 1: Optimum time window for Coffee*

![Weather](images/barplot6.png)
*Figure 2: Weather Acceptance Rate*

![Kids Factor](images/histo2.png)
*Figure 3: Driving with Kids in the Car*

![Expiration](images/barplot8.png)
*Figure 4: Coupon Expiration*

![Age vs Income](images/heatplot1.png)
*Figure 5: Age vs Income*

![Age Breakdown](images/countplot1.png)
*Figure 6: Acceptance Rate by Age*

![Destination and Ocupation](images/subplot1.png)
*Figure 6: Subplot: Destination and Occupation*


### Recommendations and Next Steps
1. Each coupon code requires it's own analysis
2. It will be interesting to understand if there are other factos besides income driving drive people to select cheaper restaurants vs expensive restaurants
3. The "Greater than or Equal to" categories still need to be explored
