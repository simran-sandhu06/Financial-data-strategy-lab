Financial Data & Strategy Lab

A personal financial analysis project where I track real stock data, calculate indicators manually, and practice trading decisions — built as I learn data analytics from scratch.



Why I Built This

I am learning data analytics with a focus on financial markets. Instead of doing practice exercises on fake data, I decided to track real stocks every week. This forces me to understand what the numbers actually mean, not just how to calculate them.



What's Inside

Project 1 — AI-Assisted Daily Tracker (Stock_Data_LIVE.xlsx)

I used AI tools (Groq and Manus) to automatically collect daily price data for 6 tech stocks: AAPL, TSLA, MSFT, GOOGL, NVDA, AMZN.

What the file contains:





Daily Open, High, Low, Close, Volume (OHLCV) for each stock



5-day and 10-day Simple Moving Averages (SMA_5 and SMA_10)



An AI-generated "next close" estimate based on recent trend

Honest note: The data collection and projection in this file is AI-assisted. I designed the structure and decided what to track. I use this file to observe patterns, not as a personal achievement in coding.



Project 2 — Manual Weekly Strategy Journal (weekly_stock_tracker_manual.xlsx)

This is the file I built completely by hand. I collected all prices manually from Google Finance and wrote every formula myself.

Stocks tracked: MSFT, AAPL, NVDA, GOOGL, META Period: June 1, 2026 – July 3, 2026 (5 weeks)

What I calculated manually:





Week-on-Week (WoW) Return — (Close − Open) / Open — how much the stock moved each week



SMA_3 — average of the last 3 closing prices — shows short-term direction



SMA_5 — average of all 5 closing prices — shows the overall 5-week trend



Trend — UP or DOWN based on whether WoW return was positive or negative

What I also track:





Decision Journal — every week I write one sentence: what I would do (buy/hold/sell) and why



Paper Trades — I log simulated trades on Investopedia to test whether my decisions were right



What I Learned So Far





How to read OHLCV data and what each column actually tells you



How SMA works and why it matters (a rising SMA_3 above SMA_5 often signals short-term momentum)



Why copying formulas incorrectly breaks calculations (I made this mistake with SMA_5 and fixed it)



The difference between calculating a number and making a decision about it



Tools Used







Tool



What I used it for





Microsoft Excel



All manual calculations and dashboards





Google Finance



Manual price data collection





Groq / Manus AI



Automated data fetching in Project 1





DeepSeek



Checking my Excel files for formula errors





Investopedia



Paper trading to test my decisions



Current Status

I am on Week 5 of manual tracking. I am also completing the Trump Excel course (currently Video 7 of 26) and will add more advanced Excel features to this project as I learn them.

Next additions planned:





Conditional formatting to highlight best/worst performers



Pivot table summary of all 5 stocks



A chart showing SMA_3 vs SMA_5 over time



About Me

I am Simranjit Singh, a B.Sc. student from Batala, India. I am teaching myself data analytics with a focus on financial markets. My goal is to build real skills — not just certificates — and eventually work in fintech or data analytics in Dubai or New Zealand.

I use AI tools as assistants, not as replacements for understanding. If something is in this repo, I can explain it.



"I would rather show one thing I fully understand than ten things I borrowed."



Last updated: July 5, 2026



