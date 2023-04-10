# Financial-Risk-Analysis
# Netflix Financial Risk Analysis


# Introduction
Netflix, Inc. is a streaming platform and production company that has been growing rapidly in recent years. This report analyzes Netflix's financial performance over the past 10 years, highlighting areas where the company has excelled and areas that need improvement. Additionally, the report predicts the company's performance over the next ten years, using revenue and other factors to calculate the net present value and internal rate of return. The report concludes by discussing the potential risks associated with Netflix's business model and how the company can manage these risks effectively.

# Business Model
Netflix operates through different segments, including domestic and international streaming, and domestic DVD. The company's revenue comes primarily from subscriptions, which is also the company's main source of risk.

Netflix has recently made an announcement regarding a monthly premium membership rate increase from $12.99 to $17.99, resulting in a $4 hike. The impact of this decision will be analyzed through the use of historical data to compare previous and future cash flows. The model presented here provides an analysis of uncertainty in financial forecasting for Netflix, as the company weighs the decision of whether or not to increase its membership costs.

# Financial Analysis

This section provides an analysis of Netflix's financial performance over a decade-long period, from 2011 to 2020. During this time, the company's revenue grew from 3.21 billion to 25 billion, representing an increase of 8.06%. Meanwhile, the cost of revenue increased from 2.05 billion to 15.28 billion, indicating an increase of 7.45%. Table 1 displays the financial statement of Netflix for the aforementioned period. Notably, the company's net income surged from 226 million in 2011 to 2.76 billion in 2020. Fig. 1 and Fig. 2 illustrate Netflix's revenue and net income trends over the same period, respectively.

<p align="center">
<img width="474" alt="Screenshot 2023-04-10 134126" src="https://user-images.githubusercontent.com/94572320/230994405-efe596c1-5d86-4a30-9688-9eea90b95675.png">
</p>

<p align="center">
  <img width="270" alt="Screenshot 2023-04-10 134510" src="https://user-images.githubusercontent.com/94572320/230995198-55576d0f-d2c0-46bc-a5db-ebc72926570c.png">
</p>


The model presented herein provides a forecast of Netflix's cash flow for the next ten years, incorporating uncertain inputs such as revenue, tax rate, average number of subscribers, cost of goods sold, average monthly revenue per paid subscriber, and operating expenses. Fixed annual growth rate for revenue and subscription cost growth, as well as an annual loss rate, were also considered in the model (refer to Table 2 for details). The future cash flow was computed by factoring in the calculated revenue, annual growth rate, tax, loss, and subscription cost per user. For example, the revenue for the years 2021 to 2030 was calculated using the following formula:

Revenue = Initial Revenue x Fixed Annual Growth Rate + Initial Revenue + (Average Monthly Revenue per Paid Subscriber x 12 months)

<p align="center">
  <img width="495" alt="Screenshot 2023-04-10 134810" src="https://user-images.githubusercontent.com/94572320/230995825-c5b5947a-ada7-43d0-88d5-fd714094e89e.png">
</p>

The Monte Carlo simulation method was used in this model to predict the probability of various outcomes when random variables are introduced. One such variable is the tax rate, which was assigned a value of 37% with a "Normal" distribution. As shown in Table 1, the range of possible values for this input is -34.384% to 63.006%, with parameters of 0.1268 and 0.15094. The normal distribution is a continuous probability distribution with a probability density function of fx=1/√(2πσ^2) * e^(-(x-μ)^2/2σ^2). The mean and standard deviation of the tax rate are also calculated in the table. The graph in Fig. 3 shows a 91.4% chance that the tax rate will fall between -0.152 and 0.370. The expected value of the tax rate is equal to its mean, which is 0.1268.


<p align="center">
<img width="490" alt="Screenshot 2023-04-10 135552" src="https://user-images.githubusercontent.com/94572320/230997331-019aba06-5e3d-46fa-806a-da8f6e60df26.png">
</p>

 <p align="center">
<img width="406" alt="Screenshot 2023-04-10 151115" src="https://user-images.githubusercontent.com/94572320/231008755-3d2bde02-d2ad-41a2-a752-11b2cf316608.png">
</p>
 
 Based on the analysis conducted, it has been determined that the most suitable distribution for representing Netflix's revenue is the "Beta General" distribution, with specific parameters of 1.6133, 1,2019, 0, and 24974507. The probability of Netflix's revenue value falling between 4.65 million and 24.11 million has been calculated to be 90%, based on the results illustrated in Figure 6. Additionally, Figure 4 displays the mean, median, and standard deviation values for this distribution. It is worth noting that the formula for calculating the Beta General pdf is x^(α-1)(1-x)^(β-1)B(α,β), where B(α,β)=Γ(α+β) and Γ is the Gamma function. Moreover, the expected value can be computed utilizing the formula Mean=α+β=14,807,741.

<p align="center">
  <img width="456" alt="Screenshot 2023-04-10 144622" src="https://user-images.githubusercontent.com/94572320/231005341-d0fec71a-093e-434e-8c3d-5d42522a8ad4.png">
</p>

The "Triangle" distribution with parameters of 0, 30.360, and 194.24 provides the best fit for the average number of Netflix subscribers. The corresponding mean, mode, median, and standard deviation values are presented in Figure 5.


<p align="center">
<img width="484" alt="Screenshot 2023-04-10 144943" src="https://user-images.githubusercontent.com/94572320/231005719-e2e82b39-b27a-465b-88a0-e5a58b561172.png">
</p>

parameters of 2.4607 and 13128700000. As shown in Figure 6, the mean value and expected value are both 74.87, while the median is 68.08 and the standard deviation is 42.66.
 
<p align="center">
 <img width="469" alt="Screenshot 2023-04-10 145202" src="https://user-images.githubusercontent.com/94572320/231006042-e1905d98-8c9f-46e1-8ca1-4a294d1c3ea4.png">
</p>

The monthly revenue per user is best represented by the "Kumaraswamy" distribution with parameters of 1.1704, 0.28195, 0, and 10.820. As shown in Figure 7, the mean, median, and standard deviation are calculated and displayed. The probability density function (pdf) can be calculated using the following equation:

 <p align="center">
 <img width="169" alt="Screenshot 2023-04-10 145544" src="https://user-images.githubusercontent.com/94572320/231006644-330bca57-ca25-47a3-a71c-604060e7d9f3.png">
</p>
 
 
  <p align="center">
<img width="521" alt="Screenshot 2023-04-10 145717" src="https://user-images.githubusercontent.com/94572320/231006860-289e69ac-8d5d-4fb7-abb3-50f915467462.png">
</p>
 
 After fitting uncertain inputs with appropriate distributions and calculating cash flows, outputs were obtained. Based on the cash flow analysis, the net present value (NPV) of the project is $72,541,061,388, and the internal rate of return (IRR) is 81%. NPV is the difference between the present value of cash inflows and outflows over a specified time period, and it depends on the internal rate of return, which is 21% in this case. NPV measures the added value to the company resulting from the project. On the other hand, IRR represents the expected annual rate of growth the investment will generate and is the internal rate at which the NPV is zero. The equations used to calculate NPV and IRR in this model are:
 
 
  <p align="center">
<img width="455" alt="Screenshot 2023-04-10 150145" src="https://user-images.githubusercontent.com/94572320/231007478-62ff9862-622e-4217-841d-6b7b742de554.png">
</p>

 Based on the results displayed in Figure 8, the net present value (NPV) is estimated to be within the range of -$1.133 × 10^10 to $2.394 × 10^10. This suggests that there is a 99.8% probability that the NPV value falls between -$11.25 billion and $23.75 billion.
 
  <p align="center">
<img width="473" alt="Screenshot 2023-04-10 150326" src="https://user-images.githubusercontent.com/94572320/231007716-f07821ee-47c3-4bd5-99e1-6e44071f6998.png">
</p>
 
 The analysis shows that Netflix has high profitability potential with an 81% internal rate of return. Tax rate has the greatest impact on outputs, and subscriber growth has the least. This implies that tax planning is crucial, but maintaining and expanding the subscriber base remains critical for long-term success. These insights can inform decision-making and help allocate resources effectively to maximize profitability and minimize risk.
 
 <p align="center">
<img width="392" alt="Screenshot 2023-04-10 150527" src="https://user-images.githubusercontent.com/94572320/231008002-6171753e-5800-47df-880a-35cf9688a6ba.png">
</p>

# Result
 
 The analysis indicates that Netflix has experienced significant international subscriber base growth over the past decade, with the highest rate observed between 2016 and 2018. While subscriber growth has slowed down since then, even losing some subscribers may not have a significant impact on the company's revenue, as long as it continues to increase its overall membership. These insights can inform Netflix's strategies for subscriber acquisition and retention to maximize its revenue potential in the competitive streaming industry.
 
# Conclusion
Netflix faces several risks associated with its business model, including intense competition and dependence on subscriptions for revenue. However, by managing these risks effectively, the company can continue to grow and succeed in the highly competitive streaming industry.
