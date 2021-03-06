# Residential real estate market monitor
Independent value benchmaker of the residential real estate market

## Summary

It is very hard to establish the current value of a residential real estate property. Based on several indicators that are scattered on the internet, we can once and for all establish a clear cut method to provide everyone with a benchmark for the value of any residential property.

## Background

It is currently almost impossible to predict whether the asking price for a real estate property is overvalued, undervalued or on par with value. The only reference for most people is the historical price. That is not good enough indicator since asking price, selling price and value are three different things. By combining several publicly found data, we can generate a objective value range, which can help buyers and sellers to set the right price to sell or buy for by offering a benchmark.

Almost every human in its lifetime is speculating whether to buy a property for its family. Some do it more often as a small time investors and others are selling their owned property to make means for their other life expenditures. The ever present question is around all of them. What should I sell/but it for? As of now, if you are not having big enough real estate company, or if you do not work in a consulting company such as Deloitte, KPMG and others, you do not know really how to answer that questions and you could easily be tricked in underpricing your property while selling and overpaying for a property while buying. 

My motivation for this project lies in my fascination by residential real estate property and my never ending problem of establishing whether my investment is in the right amount, or if I am overpaying for it. I have to say I have been on both ends, but I can judge only based on my feeling never based on merit. I think that I overpayed for a property as well as underpayed for another one. I do not want to think anymore, I want to know.

This topic is important, because it brings stability to the market and useful tool to the hands of small investors and first time property buyers and sellers. It removes the knowledge only from the big corporations and gives it to hands of everyone and therefore it democratizes the market.

## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

The solution will enable a small time investor that purchase or sells about one property per year with educated information scan the market and provide a qualified offer.

The Residential real estate market monitor can be used while finding a suitable property to buy as an investment, or for your own use. The user is most likely a person in the age between 30 - 50 years old that belongs to the middle class and is looking to invest their money to the real estate market. 

The user has the following needs:
* Understand the value of the property
* Understanding what price to offer/pay for the property
* Select the right property to buy based on value indicators and use these indicators as bargaining power while negotiating the price

## Data sources and AI methods

We will collect various information that normally you have to look for in various sources and through scraping this data, putting a weight to the information and through the method of linear regression and nearest neighbor method that will allow us to get the suggested value and then through logistic regression, we will establish the probability of that number to be exact and form a range for a benchmark.

| Source of Data      | Description |
| ----------- | ----------- |
| Property Taxes| $ amount|
| Market Value| $ amount|
| Replacement Cost| $ amount|
| HOA fees   | $ amount|
| HOA  | Monies in the bank according to the latest tax statement |
| Historical sales data of comparable properties   | $ amount|
| Property Orientation   | N, NW, W, SW, S, SE, E, NE |
| Property size   | standartized dispositions |
| Property size   | m2 |
| Property ownership type   | Owner or common ownership |
| Property size   | standartized dispositions |
| Property   | Age |
| Property   | Latest reconstruction |
| City   | Population |
| Safety  | Neighborhood crime statistics |
| Education  | Number of grade schools |
| Education  | Number of secondary schools |
| Education  | Grade school ranking |
| Education  | Secondary school ranking |
| Public transportation  | Nearest bus stop |
| Public transportation  | Nearest tram stop |
| Public transportation  | Nearest metro stop |
| Public transportation  | Airport |
| Economy  | Inflation |
| Economy  | Economy growth |
| Economy  | City economy growth |
| Economy  | State economy growth |


## Challenges

The project only provides the information now reserved for elites to everyone and therefore provides a level playing field; however, it cannot provide more than that. It can inform the user and allow it to make an educational offer; however, it does not provide and cannot react on a market in real time. It only offers a range where the property should be priced based on its value based on last years data collected by national and state agencies; however, if the market moved within a year the range of the price is moving with it. 

Therefore the biggest challenge is to incorporate in the monitor an option that will give the best possible range of price based on last years data and current level of inflation and supply combined with demand. It will never provide a specific price that will be absolutely accurate. The best it can do is to be a benchmark.

## What next?

I need people with the following skills to get this project of the ground:
* AI python programmer
* Data analyst and data builder
* UX/UI Designer

The only way this project can take of the ground is to find a cofounder that has technical skills and can build the product. My skill is more in marketing and business development, but sadly I cannot technically build this project.

