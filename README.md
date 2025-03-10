# SEC Insider Transaction Analysis: 2024 and 2020

## Background and Motivation

Section 16 of the Securities Exchange Act of 1934 requires senior executives, directors, and 10%+ shareholders (“insiders”) to make initial and ongoing filings about their company stock holdings, including reporting most of their transactions in the company’s stock. The SEC publishes this data quarterly on their website, and each download consists of eight tables, which include:  

- **Submissions**  
- **Reporters**  
- **Non-Derivative Transactions**  
- **Derivative Transactions**  
- **Non-Derivative Holdings**  
- **Derivative Holdings**  
- **Footnotes**  
- **Owner Signatures**  

Each table contains an **Accession Number**, which is the unique identifier assigned to each submission.  

The **Submissions** table includes details about the type of form filed and the issuer of the filing. The **Reporters** table provides information about the reporting owner behind the transaction, their relationship to the company, and their title (e.g., CEO).  

The **transactions tables** include details such as:  
- Date of transfer  
- Number of transferred shares  
- Whether they were bought or sold  
- Number of shares owned after the transaction  

**Non-derivative holdings** typically refer to common stock, while **derivative holdings** are linked to underlying financial instruments such as stock options and warrants. The **holdings tables** are similar to the transactions tables but focus on shares owned following transactions.  

I did not include the **Footnotes** and **Owner-Signature** tables in my analysis, but I referenced the **Footnotes** table for additional details on certain transactions.  

### Motivation  

My motivation for conducting this analysis was curiosity about insider trading behavior in relation to stock exchanges and whether insider activity could predict market movements. In particular, I analyzed data from the first two quarters of 2020 to examine how insiders reacted to the COVID-19 pandemic.  

## Goals of the Analysis  

When I first started my analysis, I did not have a specific direction in mind. I spent significant time understanding the dataset and identifying meaningful analytical approaches. Eventually, I focused on the following key areas:  

- **Who was filing the most reports?**  
- **What were the positions of those filing reports within the company?**  
- **When were the most reports being filed?**  
- **How did specific events (e.g., the Presidential Election) impact insider trading?**  
- **Details of transactions for the largest trades.**  
- **Information about derivative stock holdings.**  

### Overall Goal  

My ultimate goal was to understand what might drive insiders to buy or sell stock and whether their actions could be used to predict stock market movements.  

### Summary of Findings 

# SEC Insider Transaction Analysis: 2024 and 2020

## Figure 1/2 - Who Was Reporting and When They Filed  
![Figure 1](https://github.com/user-attachments/assets/d1dd9f38-7c48-4b2d-a79c-f389d7634cd6)  
![Figure 2](https://github.com/user-attachments/assets/fc0da88b-2154-4334-a8cc-36233bbe9e73)  

Who was reporting and when they were filing these reports in 2024. Mark Zuckerberg was very active with over 100 reports for this year. Here's more information about what he was doing with his stock in META.  

## Figure 3 - Mark Zuckerberg's Reports  
![Figure 3](https://github.com/user-attachments/assets/b65da75f-a2c6-45f3-a0bb-699ef3946079)  

He was mainly selling stock at the end of the year. I would infer this was for some sort of tax purpose, or he was selling to make a profit before the new presidency in January.  

## Figure 4/5 - Presidential Election Effect on Selling and Buying  
![Figure 4](https://github.com/user-attachments/assets/f8482200-79d9-4082-ac0f-34c0b0ca60db)  
![Figure 5](https://github.com/user-attachments/assets/6b608781-839a-4aaf-a123-d73d49821dc0)  

A lot more people sold stock immediately after the presidential election than were buying. This could be to turn a profit if there was a negative sentiment around the stock market under the new presidency.  

## Figure 6/7 - Derivative Stock Holdings and Their Expiration Dates  
![Figure 6](https://github.com/user-attachments/assets/22948333-4f88-476c-8161-fcbe50b7bfa7)  
![Figure 7](https://github.com/user-attachments/assets/44b8899e-b9c1-455a-9a13-d755b317e5eb)  

I thought it would be interesting to see who is holding the most long-term stock futures and when they will expire. Derivatives like stock options are common compensation for executives and can heavily contribute to their wealth.  

## Figures 8-10 - Comparing CEO, CFO, and President Stock Transactions Over Time  
![Figure 8](https://github.com/user-attachments/assets/f5cbc9e7-9ae6-428b-8010-90692e8a1e41)  
![Figure 9](https://github.com/user-attachments/assets/dff7d261-02b0-4cb1-90d3-593ca4956c5e)  
![Figure 10](https://github.com/user-attachments/assets/3ffa82d2-1b42-4859-bee3-9c09f5beeb89)  

It seems as if CEO, CFO, and President stock transactions all follow similar patterns. CFOs seem to make more transactions than the other executives.  

One thing to note is that the dataset is not perfectly cleaned and does not fully represent all CFO transactions. For example, "CFO" can be listed in various ways depending on the submission, such as "CFO", "Chief Financial Officer", or "chief finance officer".  

## Figure 11 - Stock Transactions Over 2024  
![Figure 11](https://github.com/user-attachments/assets/d5285846-8d8b-4b3e-b97a-a1caa0dc9986)  

I layered stock acquisitions with stock disposals over the whole year to identify any significant spikes. There were slight variations, but nothing alarming.  

Above all, it seems insiders trade primarily with regard to tax consequences rather than the overall performance of stock exchanges. Notably, there was a significant increase in selling around the time of the presidential election.  

## Figure 12 - Insider Activity Before the Pandemic  
![Figure 12](https://github.com/user-attachments/assets/e463ae28-73f2-43e0-949e-13fde7fd1805)  

I was interested in seeing how much insider activity picked up before the pandemic to better understand whether insiders truly have a better feel for the market. As you can see, there was a large spike, but I don’t attribute this to COVID.  

More insiders were buying stock than selling it, which wouldn’t make sense before a major market crash. Through my analysis, I also realized that it wouldn’t make much sense for insiders to react significantly to events like COVID, as they are heavily invested in their businesses and will continue to be a part of them regardless of short-term market fluctuations.  




