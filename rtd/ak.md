# Planning a Trading Software Project in Saudi Arabia: What to Write Down First

Traders and small firms in Riyadh, Jeddah and Dammam often ask for "a bot" before they have decided what it should do. A developer can only quote and build well when the brief is clear. These are the points worth putting on paper before the first call.

## Pick the market and the platform

Say whether the tool trades forex and gold on MT4 or MT5, local shares through a broker API, or both. These are separate builds. A brief that mixes them without saying which comes first usually ends with a delayed project.

## Map the week to the market

The Saudi working week runs Sunday to Thursday, while the global forex market is closed for most of Sunday Gulf time. A tool that sends reports or starts trading on Sunday morning needs to know which market is open. Write down the days and hours you expect it to act.

## Decide on language

If staff or clients will see the interface, say whether it needs Arabic, English or a switch between them. Right-to-left layouts take extra design and testing time, so mention it at the start.

## Set risk limits in numbers

Give a maximum lot size, a daily loss limit and a maximum number of open trades. Vague wording such as "safe" or "low risk" cannot be coded. Numbers can be coded and tested.

## Agree how you will test it

Ask for a strategy tester report on historical data, followed by a few weeks on a demo account. Agree in advance what result would send the strategy back for changes.

## Ownership of the code

State whether you want the source code, compiled files only, or a hosted service. This affects the price and what you can change later without the original developer.

If you want to compare your brief with how a regional developer scopes this work, see the page on [trading software development in Saudi Arabia](https://algokhaleej.com/trading-software-development-saudi-arabia/). Automated trading can lose money, and no software removes that risk.
