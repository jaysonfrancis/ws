#### Options Pricing

Now, let’s figure out how options are priced. By this point, this should be clear: options pricing is more complicated than stocks. There are several factors that impact how an option is priced. The three most important are the price of the underlying, time to expiration, and implied volatility.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.20.02.jpg)

It’s important for option traders to understand options pricing—after all, if you don’t know how your trade might make or lose money, how can you describe your results as anything but luck? We’ll begin our investigation into options pricing by examining its history, and then we’ll get into the specifics.

Back in the early days of options trading, options were priced by supply and demand, just as they are today. However, back then, nobody understood why options were priced the way they were. They weren’t able to make a lot of sense of it, and instead, thought it was just a result of market forces.

For example, the underlying stock might go up from $40 to $42, causing a small move in the options price.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.20.03.jpg)

Then, the stock might make another $2 move, only this time, the options price moved more than it did before. How would one explain or plan for this inconsistency?

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.20.04.jpg)

These inconsistencies led to more questions. For example, how would you know how many options to buy to hedge a position? Or, how would you identify a fair price? Perhaps most importantly, how would you determine which factors mattered to the options price? For example, if the stock market crashed, would that have an impact? How about a stock’s recent volatility—would that impact the options price?

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.20.05.jpg)

These questions help illustrate the issues surrounding options pricing. Traders knew that options could be a useful security, but it was difficult to know whether they were offered at a fair price or how many should be traded to achieve a desired level of risk. For this reason, many viewed options trading as something akin to gambling.

Enter two economists, Fischer Black and Myron Scholes, who published a paper in 1973 with an equation that estimates the price of an option over time. Fittingly, this equation is now known as the Black-Scholes formula, and it describes the relationship between the factors that impact the options price. Essentially, it created a mathematical model for how options pricing works and, in doing so, legitimized options trading. What was once seen by some as gambling, now was given a seat at the table of high finance. Black, Scholes, and another economist, Robert Merton, won a Nobel prize in the ‘90s for their work on options pricing. As you can see, this formula looks pretty complicated.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.20.06.jpg)

However, understanding this formula isn’t necessary to trade options. You just need to understand that this formula helped identify which variables were the main drivers of the options price: the price of the underlying, time to expiration, and implied volatility.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.20.07.jpg)

Let’s discuss each of these factors, beginning with the **price of the underlying**. Price is often the factor that makes up the majority of an options premium. This makes sense when you consider the leverage inherent to options. Because options allow you to control a large amount of stock (specifically, 100 shares per standard contract), the price of the underlying stock has a big impact on the options price. As you might expect, an option for a stock that’s priced at $10 per share is significantly less than an option for a stock priced at $700 per share.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.20.08.jpg)

Another thing to note about changes in price is that its impact on an options premium isn’t linear. For example, the underlying stock may move $1 and you may see the options premium increase $0.30. Then the underlying stock may move $1 more, and you may see the options premium increase $0.38. This non-linear relationship is common to all aspects of options pricing and, as you’ll learn, can be a valuable tool for certain strategies. Later in this lesson, we’ll introduce additional concepts that will help you identify specifically how much an options premium might change depending on changes in various factors.

Now, let’s examine the next factor that makes up the options premium:  **time**. All options have an expiration date. The amount of time left until expiration is the time value of an option. Options with many months until expiration have a lot of time value, while options with only a few days until expiration have little time value. This is because more time to expiration means more time for the option to possibly become profitable—for which the market is willing to pay more. Time value slowly erodes every minute of an options contract’s life (including weekends). This is often referred to as time decay, which describes the way time value melts as an option nears expiration. Time value doesn’t melt at a steady rate either; it melts faster the closer it gets to expiration.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.20.09.jpg)

**Implied volatility** refers to the amount of an options premium attributed to a stock’s perceived riskiness. To put it another way, it estimates how much price movement is expected by the market in that stock before expiration. A stock that’s more likely to make a big move in price (up or down) has more implied volatility, and a stock that’s less likely to make a big move has less implied volatility.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.20.10.jpg)

Implied volatility tends to spike before events that can have a big impact on a stock’s price, like earnings announcements.

The word “implied” refers to how it’s calculated. Unlike stock price and time, which can be easily identified, implied volatility is not something you can determine from looking at a stock chart or a calendar. Instead, it’s calculated by starting with the options price and working backward. Implied volatility is simply what’s left over when all other inputs are accounted for. As you’ll explore further on the next page, options prices are generally set by a market maker. When a market maker adjusts prices up and down due to supply and demand, she’s essentially adjusting implied volatility levels. Because of the market maker’s role in determining implied volatility, it’s often considered a more subjective variable rather than something concrete.

There are other extrinsic factors like interest rates and dividends that impact an options price. But compared to time and implied volatility, they’re much less important. That said, it’s still helpful to understand them and how they might impact your trading decisions.

Like almost all securities in the financial world, options are impacted by  **interest rates**. When interest rates rise, call premiums increase and put premiums decrease.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.20.11.jpg)

Here’s why. If you buy a call instead of stock, you can invest the remaining capital you would’ve spent on the stock and earn interest. When rates are higher, you earn more interest on that capital—this is appealing to traders, as evidenced in higher demand for long calls, which increases premiums. On the other hand, if you own a put contract and rates are high, you might choose to exercise it early so that you can sell stock and free up capital that can earn interest. In this environment, demand for puts is low, which decreases premiums.

The impact of  **dividends**  is similar, as it influences whether people prefer owning options or stock. The higher the dividend, the **lower the call premium** and the **higher the put premium**.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.20.12.jpg)

Let’s break this down. When dividends are issued, the stock price drops by the amount of the dividend. The call premium prices in this drop and is lower as a result. The put premium anticipates the lower stock price as well, but it increases as a hedge against the drop.

Dividends also impact the likelihood of assignment. Remember, you only receive dividends if you own the stock the day before the ex-dividend date. If you own a call option for a stock with an upcoming dividend and the ex-dividend date is before expiration, you may choose to exercise early to capture the dividend. For the same reason, if you’ve sold a call option and the price of the underlying is above the strike, the chance of assignment increases as the ex-dividend date approaches. Dividends have more of an impact on options with longer expirations than shorter because more dividend payments are distributed in a longer period of time; however, the risk of assignment is always greater as an option gets closer to expiration.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjAwODEyNjM1NV19
-->