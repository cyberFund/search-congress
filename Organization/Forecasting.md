# Forecasting & reporting


## 1. Balances doc

Main goal is to know actual state of congress fund balance.

Activity:

- data is collected once in sprint
- data obtaining can be automated via cyber.Search 


## 2. Prices doc

Main goal is to know actual prices of congress fund tokens.

Activity:

- data is collected once in sprint
- data obtaining can be automated via cyber.Markets


## 3. Forecast doc

Main goal is to have planning horizon for 10 sprints.

Sheet consists of two "directions":

- time direction (sprints)
- balance & expenses direction

Time direction:

- sprint - atomic unit of forecasting
- block - special kind of sprint (block appears every 6-7 sprints)
- current sprint and further sprints are in "prediction" state (forecasting balance and expenses)
- previous sprints are in fixed state (fixed balance and expenses)

Balance & expenses direction:

- congress fund balance with token & prices
- incomes & revenues
- investments
- team expenses (in USDT and ETH)
- community expenses (gitcoin, hackatons)
- service expenses (google cloud, hardware, office, meal, office manager, travel)
- reserve (10% from all expenses)

## 4. Flow

- 