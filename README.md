
## Options Pricing Models 

### Black-Scholes 

The following models are designed to:

- Price vanilla options under standard BSM assumptions
- Compare theoretical vs realized outcomes for model validation
- Identify risk to reward for various structures 
- Simulate expected value under different market regimes

![OptionPricingModel](https://github.com/user-attachments/assets/1364bac5-4401-4f2e-9693-57d96dad9ca5)

Practical Application: 

The models presented here are designed to deconstruct the current market landscape and extract actionable insights. When a backtested strategy generates a signal, I immediately reference the live implied option chain. While I currently lack direct access to implied volatility surface data for integration into the model, I bridge that gap by comparing implied market pricing with realized pricing—as shown in the pricing simulator. 

Additionally, I compare the historical rank of implied volatility with that of realized volatility over the same period—derived from data provided by my brokerage. This gives me a clearer view of how volatility is currently priced across different deltas and expirations. While I don't have a full implied volatility surface to visualize skew, this relative rank structure allows me to infer whether I should be a net buyer or seller of options, and whether spreads offer a more favorable risk-reward payoff than outright positions. In conjunction with this tab, the options calculator tab is used to get 

I actively backtest strategies across different volatility regimes and signal types, helping me formulate different factor based strategies. 

My _backtest model_ tests my hypothesis and determines the effectivness and the strategy type across history
The Backtest model can be found in the project arhive. 

### Log-Normal Distribution Visualizations 
![Visual_OptionsPricing](https://github.com/user-attachments/assets/8f8e270b-fcbe-48f3-852e-6fdd85a76806)


## Project Archive 

| <a href="https://github.com/PatrickRych/Project">LandingPage </a>
| <a href="https://github.com/PatrickRych/Portfolio-Manager">Project Archive </a>
****


