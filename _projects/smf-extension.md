---
layout: project
title: SMF-Extension - Fork of https://github.com/madsailor/SMF-Extension
---

Repo: [https://github.com/madsailor/SMF-Extension](https://github.com/madsailor/SMF-Extension)

This repo is a fork of the SMF-Extension project housed
at [https://github.com/madsailor/SMF-Extension](https://github.com/madsailor/SMF-Extension).
This project is a LibreOffice extension (mostly written in Python) 
that implements a number of stock market related
functions using Yahoo Finance and Morningstar. These functions allow you to
build LibreOffice spreadsheets that pull stock symbol data from these providers.
The base implementation basically supports pulling current data (as of the 
time of request).

I needed to pull historial data for various stock symbols from any date in
the past. For example, what was the price of AAPL (Apple) at market
close on 2/27/2016?

To meet this need, I created a ["yahoo-hist"](https://github.com/dhocker/SMF-Extension/tree/yahoo-hist)
branch and implemented a set of functions that could pull historical data from Yahoo Finance.
The set of functions is illustrated in the
[YahooHistExample.ods](https://github.com/dhocker/SMF-Extension/blob/yahoo-hist/examples/YahooHistExample.ods)
file.