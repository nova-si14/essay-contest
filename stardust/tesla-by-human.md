I tried to recreate figure 1.1 from the authors:
<img width="707" height="593" alt="image" src="https://github.com/user-attachments/assets/7c6f60a4-2726-4b98-90ac-e40ef80c8aa7" />

But for Tesla, here's the result:
<img width="1523" height="835" alt="image" src="https://github.com/user-attachments/assets/05b68d5b-5285-474b-afa7-48628079fe3f" />

First of all, you can only calculate it for the 2016 - 2019 period, because only by 2016 did Tesla have 7 years of stock prices to look backwards, and we can only know the frothiness of TSLA from 7 years ago, according to the author's methodology.
Yet the incredible run up in prices from Tesla means that there was no frothiness during this period: The frothiness index was always below 1.0.

I had Gemini calculate both the trend as well as the standard deviation of the price, but I checked it with a manual calculation. Gemini used SQL to calculate 7 years back and 7 years forward, which makes it more accurate than what I did to check, which is to take the Excel file and calculate 1,764 days back and forward, which is roughly equivalent to 7 years of 252 business days, but much less exact. Our calculations were pretty close, so I trust Gemini's numbers.

Sources:
Data from https://www.marketwatch.com/investing/stock/tsla/download-data?startDate=1/1/2026&endDate=3/2/2026
