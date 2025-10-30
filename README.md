# Random_Motors_case
## Introduction
Imagine you are the Lead Business Analyst at Random Motors, an automobile conglomerate that manufactures cars across a wide range of price points. For the price-conscious consumers, Random Motors manufactures cars under the brand Rocinante. The various models of Rocinante fall in the range of ₹5–10 lakh. The brand is known for cars that are value-for-money and offer very attractive mileage. For the consumers wanting to purchase a luxury car, Random Motors operates under the brand Marengo. Marengo models fall in the range of ₹30–60 lakh. These are sports cars with powerful engines and competitive top speeds.
Suppose your chief engineer has recently come up with two new models: Rocinante36 and Marengo32. He promises that they will outperform the existing competitors in the market.
Rocinante36 is priced at ₹7 lakh and has been designed to deliver a mileage of 22 km/litre and a top speed of 140 km/hr.
Marengo32 is priced at ₹41 lakh and has been designed to deliver a mileage of 15 km/litre and a top speed of 210 km/hr.
The chief engineer has built 20 prototypes of each of the two models to check if the cars are performing as per the desired specifications. If the cars are performing better than expected, then the engineer wants to revise the specifications. However, if they are performing worse than expected, then it is an indication that more investment is needed in the design to improve their performance. The test drive results for the 20 prototypes of each of the two models are provided in the file titled Data Exhibit 1. During the test, the mileage and the top speed is recorded for each of the prototypes. The data will be used for performing hypothesis testing for the claims made on the specifications.
- <a href="https://github.com/kumarnnaveen408/Quantitative_Techniques-Random_Motors-/blob/main/Exhibit%2B1%20(1).xlsx">Exhibit1</a>

Additionally, the chief engineer reported that the cost of manufacturing the Rocinante36 model would be ₹6 lakh per car and that of the Marengo32 model would be ₹33 lakh per car, including all the overhead expenses. Given the business scenario, you need to invest the total manufacturing cost upfront. The manufacturing cost will be recovered slowly by the next financial year as sales start happening. These details are summarised below,
- Rocinante36(Price - 7 lakh, Manufacturing cost - 6 lakh, Mileage - 22 km/ltr, Top speed - 140 km/hr)
- Marengo32(Price - 41 lakh, Manufacturing cost - 33 lakh, Mileage - 15 km/ltr, Top speed - 210 km/hr)
  
Currently, the company has enough cash reserves to invest in only one model. Therefore, as the Lead Business Analyst, you need to carefully choose the right model and decide the number of cars that you want to produce. Since you believe in making data-based decisions, you ask your team to provide you with the sales data of all the past models released under the brands Rocinante and Marengo. The sales data is provided in the file titled Data Exhibit 2.

- <a href="https://github.com/kumarnnaveen408/Quantitative_Techniques-Random_Motors-/blob/main/Exhibit%2B2.xlsx">Exhibit2</a>
The data in Exhibit 1 and Exhibit 2 will be used to predict the sales for Rocinante36 and Marengo32 and to make decisions regarding which model will generate maximum revenue for the company.
## Questions
- Formulate the null and alternative hypotheses for mileage and top speed to check whether the new models are performing as per the desired design specifications.
- In order to comment on whether or not the design specifications are being matched, perform relevant hypothesis tests add your conclusions? Assume that you are performing the tests at a 95% confidence level.
- You have already learnt about the possible errors that might result from hypothesis tests. Which type of error is more expensive for Random Motors, and why? Assume that you need to refund the money to all your customers if your cars do not deliver the promised specifications.
- Develop a regression equation for each model at a 95% confidence level. Using the regression equation, predict the sales of the two models. State the hypothesis assumption for the overall test and individual variables.
- Based on the sales prediction, calculate the overall projected profit for the Rocinante36 and Marengo32 models, respectively?
- Your company wishes to invest only in the model that can generate high overall profits. In which of the two models, Rocinante36 and Marengo32, should your company invest?

## Solutions
- Rocinante 36	
														
H0 :	Mileage  >= 22 km/litre	

Ha  :	Milage < 22 km/litre

																						
H0  :	Top speed >= 140 km/hr	

Ha  :	Top speed < 140 km/hr

Marengo 32

H0 :	Mileage  >= 15 km/litre

Ha  :	Milage < 15 km/litre


H0  :	Top speed >= 210 km/hr	

Ha  :	Top speed < 210 km/hr
- At α = 0.05, reject the null for Rocinante 36 on mileage and fail to reject it on top speed; conclude there is sufficient evidence that its mileage does not meet the target, while its top speed does.​ 
At α = 0.05, fail to reject the null for Marengo 32 on both tests; conclude there is not sufficient evidence that its mileage or top speed deviates from the target.
- Type II error would be more costly for the Random Motors case, because selling an underperforming car would trigger refunds, logistics costs, and lasting reputational damage, whereas a Type I error mainly results in lost sales from being overly cautious.
- Sales_Rocinante_z:	1.91		
  Projected Sales for Rocinante 36:	224.78	≈  225 thousand
			
  Sales_Marengo_z:	0.21		
  Projected Sales for Marengo 32:	25.78	  ≈   26 thousand
- Profit for Rocinante 36 :			225*1 = 22500 million, 
  Profit for Marengo 32 :			  26*8 = 20800  million
- Given the higher projected profit, Random Motors should prioritize investment in Rocinante 36. However, the advertised mileage of 22 km/l was not substantiated by hypothesis testing; the company should either optimize the powertrain to reliably achieve this target or revise the claim to a statistically supported figure (e.g., 21 km/l) based on validated test results.



