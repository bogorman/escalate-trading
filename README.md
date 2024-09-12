# escalate-trading

Based on escalator starter this is the base layer of a algo trading system. Full stack scala.

Trading systems for both crypto and sports betting will be built ontop of this so this repo will contain the generic system components that can be shared. 

# Backtesting
Run custom code in python / scala. 
Charting results.


# Paper trading


# Live trading
Live price charts
simple order book heatmap view. 

# General
Graalvm will be used if possible but if not there should be fallback to openJDK. 
Python package support in graalvm is hit and miss. 

# Data
Import historic data.
Live pricing data.
Historic reference data.
Live reference data.
Expose a WS that the client can send live data to which the running bots will be able to recieve. 
Ability to import data on a schedule and update the running bots. 

# Failure
Network monitoring. If there is a delay in the system or delay in the connection to the external exchanges then panic the bot and send an alert. Ability to configure these alerts.
Manage the trades and if errors panic and alert. 

# Other

Tradingview integration.
Have the ability to allow users to bring their own compute and easily plugin to the system otherwise the users will have to pay for the compute they use. 

Akka Cluster + Kubernetes
Cloudflare. Run scala.js workers in cloudflare.




