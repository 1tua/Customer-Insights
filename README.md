# Customer Insights

Marketing data can describe a lot about customers. Conducting analysis into this data can give valuable insights about customer behaviour and better understand the people buying a company’s product.
Knowing which customers are the most valuable buyers is important because it helps the company further focus their efforts.

Insight 1

When a customer registers, they receive a sales call. The length of time a customer receives a call affects the conversion rate. The bar graph shows customers who receive a call within a day of registering, their conversion rate is the highest at 2.6%. For customers who received a call between 1-3 days, their conversion rate drops by ~70% to 0.75%. Lastly, customers who receive a call between 3-5 days see a further decrease in conversion rate to 0.12%. 
Therefore Sales & Marketing teams should focus on calling customers within 24 hours of registering as this is likely to result in more potential customers converting into paying users.

Insight 2
 
“Conversion Rate for Marketing channels” graph displays how the different marketing channels against their conversion rate. The formula used here was;
Conversion rate = (Conversions by marketing channel/ Total number of registrations due to marketing channel) *100  
Referral, partnerships and FB Organic have the highest conversion rate whereas SEO- Non-brand and FB -Prospecting have the lowest. There should be an increased focus on the top 3 marketing channels to improve the overall conversion rate. Actions should include increasing the number of posts and content on Facebook, building more partnerships with builders and suppliers to find new leads and creating a referral scheme that incentivizes previous Customers to refer the compant to friends and family.
As for FB- Prospecting, the Facebook ads are not as effective at converting potential customers into paying users compared to other marketing channels. Reducing the financial resources used to pay for Facebook ads and allocating it to better performing channels should increase the number of customers reached and is likely to improve the conversion rate. 

Insight 3 

“Device type of Conversion” shows which devices converted customers used. Mobiles is the highest device used with 51% and tablets being the lowest with 4%. Recommendation would be for to focus their marketing on mobile devices. 
Utilising social media platforms (Facebook, Instagram, Twitter, YouTube) and making sure the mobile version of the website is quick and easy to use will increase brand awareness and attract more customers. Using various search engine optimisation techniques will increase the visibility of the website and reach more potential customers.

Insight 4
 
This graph shows the highest number of converted customers are coming from London (67%) whilst the lowest is tier 2 (4%). It may be best to focus marketing resources to potential customers in and around London as they make up the majority of converted customers.

Insight 5 
 
“Estimates Property Values of Conversion Rate” graph shows the majority of property value for converted customers is 400-599k and the least is 0-200k
“Total Time Length vs Estimated Property Value”, shows the average total time from a customer registering to making a first payment plotted against property value. Customers with a property valued between 800-99 have the shortest time length (24 days) 
Analysing both graphs suggest the marketing team should focus on customers with a property value medium-high value (400-999k). With 800-99k properties having the shortest lead times, more marketing and sales resources should be targeted at customers with medium-high value properties as they are more likely to lead to quick turnaround and generate more revenue in shorter periods.  

Using Machine Learning 

I used various different machine learning algorithms to see which one would be the best at predicting which customers who registered would convert and make a first payment. The objective was to balance the simplicity of the model with its accuracy.
I compared different models using their AUC scores. 
I began with decision tree models. The best decision tree model had a 0.55 AUC score. Moving upward in complexity, I then tried a random forest model (0.5 AUC) whereas my AdaBoost model saw an increase in performance (0.58 AUC).

Future Work: Using predictive conversion probabilities

Using a longer period of historical data to train the models on to improve accuracy, the best model could be used by the sales team. Sales team would be shown a predicted probability of converting potential customers based on their information. They would be able to target the high-probability leads first, helping customers get all the help they needed in order for them to convert.

