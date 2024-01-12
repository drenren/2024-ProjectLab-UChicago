# Project Objective 1 : Regulatory and financial statement analysis 


## Question 1 
>SEC recently published final rule on "Standards for Covered Clearing Agencies for U.S. Treasury Securities and Application of the Broker-Dealer Customer Protection Rule With Respect to U.S. Treasury Securities"
https://www.sec.gov/rules/2022/09/standards-covered-clearing-agencies-us-treasury-securities-and-application-broker#34-99149

>We would like to have LLM to help us answer the following questions from the documents
><ol>
><li>How do banks facing money funds have to change their processes related to clearing?</li>
><li>What entitis are in scope for the new rules ?</li>
><li>Do Non-dealer counterparties need sponsored relationships with all counterparties or do they become clearing members?</li>
><li>What is the expected date of implementation?</li>
><li>How will a dealers risk weights work after they trade with clearing counterparty?</li>
><li>Do affiliates have to clear all UST trades with each other?</li>
></ol>
> Items to keep in mind:
> (1) how do we reduce hallucination ? (2) Can we provide reference where the LLM answer is based on (e.g via retriver & vector earch ? ) 


## Question 2
> We would like to use LLM to help with finanical statment analysis on all major banks in US.  
Each quarter, public companys are required to submit 10-Q, which contains key finanical statements for the company. 
Download historical 10-Q filling from JPM, BofA , Citi and WFC for Sec website, e.g
>[BofA 10-Q] https://www.sec.gov/edgar/browse/?CIK=0000070858
>[JPM 10-Q] https://www.sec.gov/edgar/browse/?CIK=19617
> and see if we can use LLM to answer the following questions

>We would like to have LLM to help us answer the following questions from the documents
><ol>
><li>How much deposit does Bank of America and JPM have ?</li>
><li>What is the net interest margin for JPM</li>
><li>How much available for sale and hold to maturity security does each bank have?</li>
><li>Historical trand of BAC asset size</li>
></ol>
> There are some existing work related using LLM for finanical statment analysis as well as getting Sec data/api.
> some of the example, i have come across
>
> https://github.com/openai/openai-cookbook/blob/main/examples/third_party/financial_document_analysis_with_llamaindex.ipynb
>
> https://github.com/janlukasschroeder/sec-api-python
>
> https://gist.github.com/firmai/dc0a8a47bf2f411485c3050fdde1ac8b






