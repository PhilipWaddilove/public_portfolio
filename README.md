
# TransferWise

## Overview and Origin

TransferWise Ltd ("TransferWise") is a global FX and remittance business incorporated in Estonia in 01/2010 by Taavet Hinrikus (Skype's first employee) and financial consultant Kristo Käärmann.  The company is privately held in the UK, and offers 2,500 currency pairs and provides multi-currency accounts to eight million customers.

Käärmann was working in the UK and engaging in periodic GBP/EUR foreign exchange ('FX') in order to cover the cost of a EUR denominated mortgage on a property in Estonia.  Earning money in EUR, but needing GBP, Hinrikus offered to deposit his earnings directly in to to Käärmann's EUR account in return for an equal deposit of GBP in his UK account, thereby circumventing the need for either to conduct FX via a bank or Non-Bank Financial Intermediary ('NBFI').  

Inclusive of the most recent funding round concluded in 07/2020, the company has raised ~$900m and is currently valued at ~$5bn.  Transferwise generated a net profit of $26m in the fiscal year ending 03/2020, valuing the company at 192x net profit.

---
## Business Activities:

TransferWise aims to reduce the price of FX and global payments.  Fees and spreads charged to retail customers have historically cost 7% of the principal, and may come in the form of:

* FX spreads i.e. the difference between the conversion rate of inter-bank currency and the rate cited by the bank or NBFI
* Processing fees for each transaction
* Commissions of any intermediaries (typically for more exotic currency pairs)

TransferWise circumvents the need to 'cross' an FX spread (plus associated brokerage and processing fees).  It does this by:

1. matching customer orders with equal and offsetting orders in its own orderbook (for example by matching an order to sell USD 1,000 with an order to buy USD 1,000); else
2. aggregating unmatched buy and sell orders and then executing the smallet possible number of trades over the wholesale banking market

The company has identified a market for its services in retail or business customers who travel frequently, or in businesses who maintain oeprations in several international locations, or in migrant workers who earn income in one currency whilst paying reccuring expenses in another.   

In 2018, ~200m migrant workers sent ~$700bn (equivalent) 'home', of which ~75% went to developing countries.  Approximately $40bn of principal remitted was absorbed in fees.  This represents the size of the market.

---
## Technology:

Transferwise maintains proprietory software in order to enable order matching and the execution of payments/ remittances.  

For databases, TransferWise use 'PostgreSQL', 'MariaDB', and 'Mongo' for 'NoSQL' solutions (selecting the engine based on the task).  These run on 'RDS' to  automate backups.  'Envoy' handles a service mesh layer, providing a transparent way for services to reach other services.  'Kafka' is used for messaging as it is able to process thousands of messages per second.  

In addition, TransferWise have licenced AWS as a provider as it delivers mature and feature-rich cloud computing, vendor and open source tooling and an industry standard resource.  AWS infrastructure is coded usng 'Terraform'.

Backend services are written in Java, Kotlin, Go, Python and NodeJS.  TransferWise have developed their own proprietory libraries such as 'tw-tasks-executor'.

Although TransferWise do not use blockchain technology, the company has evaluated its use.

In evaluating its offering vs. competitors, customers cite TransferWise as offering an advantage in:

* Close to 'best-in-class' fees (~0.5% of principal) as a result of order-matching
    - Order matching minimizes the number of FX transactions that TransferWise need to undertake with a broker thereby minimzing fees and spread (i.e. crossing bid/offer)
* Intuitive GUI,
* Variety of payment methods (including credit cards)
* Same-day delivery options
* Fee transparancy, TransferWise deliver the customer an illustrated saving vs. traditional bank or NBFI at the point of sale

---
## Competitive landscape:

TransferWise is in the FX and international remittance business.  A number of FinTech companies have entered this market in the last ten years, helping to bring transaction costs down.

A summary of competitors, and typical transaction fees is below:

| Service | Fees (% of principal) |
|-|-|
| Transferwise | up to 0.5%
| Ria | 0.3 - 1.0%
| OFX | 0.5 - 1.0%
| Payoneer | 1.0 - 3.0%
| PayPal | 2.5 - 4.0%
| MoneyGram | 1.0 - 3.0%
| Payoneer | 1.0 - 3.0%
| Xoom | 0.5 - 1.0%
| WorldRemit | 1.5 - 2.0%
| CurrencyFair | 0.0 - 0.5%
| Transfast | 1.0 - 2.0%
| OrbitRemit | 1.0 - 2.0%
| Paysera | 1.0 - 2.0%
|||
| Travelex | 10.0 - 20.0%
| Western Union | 1.0 - 3.0%
|||
| Banks | up to 7.0%

---
## Results

FinTech businesses in this space have diverted FX and remittance flows away from banks and traditional NBFIs.  Fees to retail customers accross the industry have fallen, and there is a drive toward fee transparency. 

As this is a payments business, volumes of remittances executed accross its platform (i.e. flow of funds) is a common metric.  TransferWise measures its competitive position by recording fees saved by customers.  It does this by measuring the cost of its own remittance service against the hypothetical cost of executing the transaction using an alternative service.  

As such, Transferwise records ~$5bn in monthly volumes and suggests it saves customers ~$1.5bn in fees per annum.  If the market for remittances generates ~$40bn annually, it has a market share of ~3.75%.  TransferWise appears to offer close to 'best-in-class' fees.

---
## Recommendations

Currency is one of several asset classes that retail investors might like to hold.  Other asset classes include: equities, fixed income (bonds), and commodities futures (precious metals, energy, natural resources and agriculture products), and real estate.  

Fees and spreads in the securities (i.e. cash equities and fixed income) business have been quite high for the retail investor.  RobinHood and other platforms have brought transaction costs down however there may be opportunities in commodities or other asset classes.

TransferWise may be able to capture some of the market here.  This would benefit the company by:

* Diversifying its income stream from a single asset class
* Increasing the size of its addressable market
* Make use existing technology
* Make use of existing customer base

---

## Sources:

1. Wikipedia: https://en.wikipedia.org/wiki/TransferWise#Transfer_process
2. TransferWise: https://transferwise.com/us
3. TimeDoctor: https://biz30.timedoctor.com/transferwise-review/
4. TechCrunch: https://techcrunch.com/2020/07/28/transferwise-five-unicorns/
5. The Telegraph: https://www.telegraph.co.uk/money/transferwise/how-does-it-work-and-is-it-safe/
6. NerdWallet: https://www.nerdwallet.com/blog/banking/transferwise-review/
7. DigiPay: https://www.digipay.guru/blog/fintech-impact-on-international-remittance/
8. Stackshare: https://stackshare.io/transferwise#description
9. The TransferWise stack: https://tech.transferwise.com/the-transferwise-stack-heartbeat-of-our-little-revolution/
10. Medium: https://medium.com/transferwise-engineering/the-transferwise-stack-2020-edition-68f70267501b



