#### Options Greeks

Our discussion of options pricing laid the groundwork for understanding how options are valued. However, what specific impact does each factor have on an option? For example, you know that some part of the premium erodes with each passing day, but how much? That’s where the  **options greeks**  come in.

The options greeks, also known as “the greeks,” are measurements that help traders estimate how changes in the various factors could impact the options premium. Many traders also use the greeks to help identify which options to trade and to manage either a single trade or a portfolio of trades. Let’s meet the greeks and see how they can be used.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.40.01.jpg)

We’ll begin with  **delta**. Delta measures how sensitive an option is to a $1 change in the price of the underlying.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.40.02.jpg)

For example, if a long call option has a delta of .55, the options premium will likely increase by $0.55 if the price of the underlying stock increases by $1.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.40.03.jpg)

Likewise, if the price of the underlying decreased $1, the option would likely lose $0.55.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.40.04.jpg)

A long put, on the other hand, might have a delta of -.25. The negative sign indicates that the premium decreases when the stock price goes up, and increases when the stock price goes down. Considering a long put is a bearish trade, this bias makes sense.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.40.05.jpg)

The larger the delta, the more sensitive an option is to changes in the underlying. For example, an option with a delta of .78 will be more sensitive to changes in price than an option with a delta of .38. Delta can fluctuate anywhere between 1.00 and -1.00.

You can also think of delta in terms of moneyness (i.e., whether it’s ITM, ATM, or OTM). If an option has a delta from .51 to 1.00, it’s in the money. If it has a delta of .50, it’s at the money. And if it has a delta of .00 to .49, it’s out of the money.

Delta also has a second use: estimating the probability of an option expiring in the money. While this measure isn’t exact, it can be a useful proxy. For example, an option with a delta of .55 could be seen as having a 55% chance of expiring in the money. The lower the delta, the lower the likelihood the option will expire with any intrinsic value.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.40.06.jpg)

As mentioned earlier, the value of the options premium doesn’t move linearly. The amount an option increases with one $1 move isn’t the same amount it will increase after it moves up $1 again. This is where the next greek comes in:  **gamma**. Gamma measures how much delta may change with each $1 move of the underlying.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.40.07.jpg)

For example, suppose an option had a delta of .25 and a gamma of .05. The options premium would likely increase by $0.25 with the first $1 increase in the underlying. On the second $1 increase, the options premium would likely increase $0.30 (delta [.25] + gamma [.05]).

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.40.08.jpg)

Gamma helps you understand whether an option is getting more or less sensitive to price changes. Gamma also changes over the life of an option, growing larger as an option nears expiration. This is known as  **gamma risk**. When an option has gamma risk, it has a large gamma and therefore increased sensitivity to changes in price, which can lead to big swings in the options premium. Gamma is typically largest when an option is ATM—in these situations, small movements in the underlying price can make a big difference.

Now that we’ve covered price, let’s move on to  **theta**. Theta measures how sensitive an option is to time decay.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.40.09.jpg)

On long calls and puts, theta is always  **negative**, which indicates that the option loses value as time passes. For example, an option with a theta of -.02 would likely lose $0.02 of value every day (including weekends). Like the other greeks, theta doesn’t stay the same—it tends to  **increase closer to expiration**, which means options lose value faster as expiration approaches.

![](https://education.ameritrade.com/content/cms/images/BDTO_Lesson_2.40.10.jpg)

Theta works  **against buyers**  and  **in favor of sellers**. Theta reduces the value of the options premium each day. For this reason, buyers generally prefer options with smaller theta, while sellers generally prefer options with larger theta. Like gamma, theta tends to be largest in ATM options. These two greeks are very interrelated.
<!--stackedit_data:
eyJoaXN0b3J5IjpbOTAxMzM0NzA0LDYwMDAyOTM4OSwtMTA5ND
YyODI3MCwtMTUzNzE4NjcwNV19
-->