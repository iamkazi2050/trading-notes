# How to Copy Discord Trading Signals to MT4 or MT5

Many signal groups now post their calls on Discord. Copying them into MetaTrader by hand means watching the app all day. A copier can read the channel for you, and a few checks before you switch it on will save you from odd trades later.

## Pick the channels with care

A Discord server often has one channel for calls and several for talk. Tick only the channel where entries are posted. If the provider posts results or screenshots in the same channel, ask whether they can move them, because a copier that reads every message has more chances to misread one.

## Read old posts the way a parser would

Look at ten old signals and check that each one has a symbol, a direction, an entry or market order, a stop loss and at least one target. Some providers write "XAUUSD BUY 4380" and others write "Gold long now". The more consistent the format, the fewer surprises you get.

## Decide how follow-up messages should work

Providers often reply to a call with "move SL to entry" or "close half". Find out whether your copier links a reply to the original trade. If it does not, those updates will be missed and you will have to manage the trade yourself.

## Set account limits before the first trade

- Choose a fixed lot or a risk-based size for each account.
- Map symbol names, since your broker may use XAUUSD.m or GOLD.
- Set a maximum number of open trades.
- Start on a demo account for at least a week.

## Check where the terminal runs

A copier EA only trades while MetaTrader is open. If you do not want to rent a VPS, look for a service that runs the terminal in the cloud and logs every message it read.

TPcopier reads Discord, Telegram and WhatsApp into a cloud MetaTrader account, and the options are listed on its [cloud trade copier](https://tpcopier.com/automations) page. Copied trades carry the same risk as your own, so test on demo and size every account with care.
