# PeimarNodeRED
A very useful flow with API request guide

To use this flow you have to substitute the 23 "X" in the API request (you can do directly in the .json file or later in the NodeRED panel) with your API key that you will retrieve by entering with your Peimar Xportal credentials in Solax (the real inverter chinese producer) monitoring system, in the left menu you will see "request API key" option.

Then substitute the 10 "Y" in the API request with your inverter code that you see from the Peimar monitoring app on symply from the inverte wifi name.

This flow is just a simple example with a battery SoC indicator and a Sum of two strings power but you can take whatever parameter you need from the API payload.
The dashboard refresh is triggered by a button, it is done in this way to not be banned from the monitoring panel for too many requests but also a peiodical check is an option.
