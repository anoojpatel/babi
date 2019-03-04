# babi
Trade Execution Engine designed to be flexible for any crypto exchange. I'm building this out of personal need and curiosity. The intended use is to create an abstracted away component for executing trades for your trading system.

## Origin
Named after the "chief of baboons" in Egyptian mythology. The name is fitting because it represents the carnivous and volatile nature of cryptocurrencies and their constitutents. Babi, the leader of the Baboons, is responsible for their decisions and direction, much like the trading that happens on the exchanges.

## Goals
Deliver a robust engine that will manage thousands of trades to and from an exchange. Most engines are a part of a larger trading platform, and as a result I find it difficult to manage positions and the data communications between trades with current systems. I find it useful to abstract away the execution from the trading systems themselves. 
The goal is to build a trade protocol between the engine and its users, so that information can be kept separate from the trading execution system. This is so I can off load the bloated packages onto other servers and manage my own data securely. 


