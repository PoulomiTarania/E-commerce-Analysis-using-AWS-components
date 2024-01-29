# E-commerce-Analysis-using-AWS-components
The project involved a comprehensive analysis of 10 e-commerce stocks, focusing on their  trends during the first two weeks of April 23. The key technologies used : AWS(Lambda, Athena, Glue, and EMR,), Python, SQL
The project was divided into four main components:

#### 1. Data Transformer (Lambda Function): 
A Lambda function was employed to gather and transform the data. It facilitated the collection and processing of relevant information from
various sources.

#### 2. Data Collector (Kinesis Stream): 
A Kinesis stream serves as a repository for the collected data. It provided a scalable and reliable solution for storing and managing the streaming
data.

#### 3. Data Analyzer (Serverless Querying with Athena): 
The project utilized a serverless process that allowed for efficient querying of data stored in Amazon S3. Athena, as a serverless query
service, enabled us to perform in-depth analysis and extract valuable insights from the
dataset.

#### 4. Data Visualization: 
The final component involved visualizing the results of the data analysis. Various visualization techniques were applied to present the trends, patterns, and volatility
of the e-commerce stocks. These visualizations offered a clear and intuitive representation of
the findings.

The project's scope extended beyond technical aspects, providing valuable insights into the ecommerce
industry. The analysis encompassed prominent e-commerce stocks such as:
#### Amazon(AMZN), Alibaba Group (BABA), Walmart (WMT), eBay (EBAY), Shopify (SHOP), Target (TGT), Best Buy(BBY), The Home Depot (HD), Costco (COST), and Kroger (KR). ####
In conclusion, this project showcased the integration of diverse technologies and provided a
comprehensive understanding of the selected e-commerce stocks, their volatility, and trends.


![image](https://github.com/PoulomiTarania/E-commerce-Analysis-using-AWS-components/assets/60750648/e68b4318-efe0-4da0-a2b0-1e7cb8e8b7b8)


### Screenshots:

#### 1.	S3 bucket
  ![image](https://github.com/PoulomiTarania/E-commerce-Analysis-using-AWS-components/assets/60750648/37a41c95-b61d-4e74-bd6a-4df550bdf993)

#### 2.	AWS Kinesis Monitor
![image](https://github.com/PoulomiTarania/E-commerce-Analysis-using-AWS-components/assets/60750648/d24c3154-07b8-4956-b28a-a7b3027eba6e)

#### 3.	AWS Lambda Execution results
![image](https://github.com/PoulomiTarania/E-commerce-Analysis-using-AWS-components/assets/60750648/2011c107-ec79-4c65-b7dc-f20060263840)

#### 4.	Athena results
![image](https://github.com/PoulomiTarania/E-commerce-Analysis-using-AWS-components/assets/60750648/49c73caf-0c64-450e-b261-6f0b9852ce47)

## Visualizations:
#### 1)	Graph the average volatility trend per company. Which company is the most volatile? From the above graph, we can see that Costco appears to be the most volatile
![image](https://github.com/PoulomiTarania/E-commerce-Analysis-using-AWS-components/assets/60750648/245fa4a1-0317-458e-a866-f4f19b1bac52)

Based on the graph of the average volatility trend per company, it can be observed that Costco exhibits the highest volatility compared to other companies.


#### 2)	Graph the daily highest volatility per company. Do the findings from this graph support your conclusion from the first graph?
![image](https://github.com/PoulomiTarania/E-commerce-Analysis-using-AWS-components/assets/60750648/11fff4a4-308d-4f44-a9ac-b3f8c578589f)

The graph displaying the daily highest volatility per company confirms the earlier conclusion.
Costco stands out prominently with significantly higher bars representing its daily highest volatility compared to other companies.





