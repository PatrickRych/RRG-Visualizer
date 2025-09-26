
## Options Pricing Models 

### Black-Scholes 

The following models are designed to:

- Price vanilla options under standard BSM assumptions
- Compare theoretical vs realized outcomes for model validation
- Identify risk to reward for various structures 
- Simulate expected value under different market regimes
- Visually and quantitatively see the impacts of intrisnic / extrinsiv variables on the contract value 

<img width="3102" height="971" alt="Options" src="https://github.com/user-attachments/assets/f5007adb-beea-48ce-ac7e-f1f86fd7da95" />

Practical Application: 

The models presented here are designed to deconstruct the current market landscape and extract actionable insights. When a backtested strategy generates a signal, I immediately reference the live implied option chain.
While I currently lack direct access to implied volatility surface data for integration into the model, I bridge that gap by comparing implied market pricing with realized pricing—as shown in the pricing simulator. 
The pricing simulator is intended to see how the option could change over time, and what variables we should focus on. In the model we can adjust the implied- spot and volatility- movements, and change the passage of time to analyze how to structure the trade, as well as how to manage it. 

Additionally, the model compares the historical rank of implied volatility with that of realized volatility. This gives me a clearer view of how volatility is currently priced across different deltas and expirations. Since we don't have access to the full implied volatility surface to visualize skew, this relative rank structure allows me to infer whether I should be a net buyer or seller of options, and whether spreads offer a more favorable risk-reward payoff than outright positions. In conjunction with this tab, the options calculator tab is used to get. The surface model provides a granular view with respect to the change in delta and change in volatlity over time. 

I actively backtest strategies across different volatility regimes and signal types, helping me formulate different factor based strategies. 

My _backtest model_ tests my hypothesis and determines the effectivness and the strategy type across history
The Backtest model can be found in the project arhive. 

<img width="1938" height="913" alt="options2" src="https://github.com/user-attachments/assets/1f8b6830-fea1-4e64-85dc-26cae70d1113" />

### Log-Normal Distribution Visualizations 
![Visual_OptionsPricing](https://github.com/user-attachments/assets/8f8e270b-fcbe-48f3-852e-6fdd85a76806)






## Project Archive 

| <a href="https://github.com/PatrickRych/Project">LandingPage </a>
| <a href="https://github.com/PatrickRych/Portfolio-Manager">Project Archive </a>
****



