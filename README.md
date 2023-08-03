# Reinforcement Learning  - Supply Chain Optimization for Diabetes Care Products

![Example Image](Container.png)

Welcome to the Reinforcement Course with Supply Chain Optimization for Diabetes Care! This Python notebook focuses on managing the production and forecast of diabetes care products in the Asia-Pacific (APAC) region.

[Click here to view the notebook on nbviewer](https://nbviewer.org/github/steguess/Supply_Chain_Optimization/blob/0900ca38adad339c7792b2333a56df118608f680/RL_SCO.ipynb)


##  Objective 🎯
As a supply chain manager, our primary goal is to optimize operations and maximize profits while ensuring the diverse markets in the APAC region are well-served with glucose testing strips, meters, and ancillary supplies.

## Key Tasks 📝
Production Management: Manage production with distinct language requirements for different countries in APAC, considering variable and fixed production costs and certain constraints.

Demand Management: Align production with fluctuating demand over a 3-year period to prevent overproduction or shortages.

Forecast Management: Use ARIMA and LSTM forecasting models to predict future demand for each product and country, aiding in shaping the production strategy.

Profit Optimization: Maximize overall profits by considering selling price, variable production costs, fixed costs, and shipping costs.

Time Dimension: Perform tasks within a dynamic 3-year timeframe, adapting strategies as demand, costs, and other factors evolve.

## Notebook Highlights 🚀
The notebook employs data analysis, ARIMA, and LSTM forecasting models, and different optimization techniques to manage the supply chain effectively. Key considerations include capacity, demand alignment, forecast accuracy, and maximizing profits.

## Recommended Algorithms ✅
High Recommendation: Pulp_CBC - The best solution for its effectiveness and suitability for the problem complexity.

Medium Recommendation: Pyomo_GLPK, Pyomo_CBC, Gekko-APOPT - Viable options with slightly slower performance compared to Pulp_CBC.

No Recommendation: L-BFGS-B, Deap, SLSQP, Trust Constr, COBYLA - Not suitable due to constraints, integer solutions, or realism issues.

## Limitations and Complexities ❗
Supply chain optimization for diabetes care products faces challenges like production constraints, demand variability, profit optimization, supply chain disruptions, and regulatory compliance, among others.

## Conclusion 👍
This notebook equips you to optimize supply chain operations for diabetes care products in the APAC region. By considering key tasks, recommended algorithms, and addressing limitations, you can make informed decisions and achieve efficient supply chain management. Happy optimizing!

## Authors ✍

Dominik Roser : https://github.com/domro11

Stephanie Gessler: https://github.com/steguess

Christian Barba: https://github.com/CBRodulfo

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/domro11"><img src="https://avatars.githubusercontent.com/u/108944195?v=4" width="100px;" alt="Dominik Roser"/><br /><sub><b>Dominik Roser</b></sub></a><br /><a href="https://github.com/codesandbox/codesandbox-client/commits?author=domro11" title="Backend Developer">💻</a></td>
    <td align="center"><a href="https://github.com/steguess"><img src="https://avatars.githubusercontent.com/u/86976901?v=4" width="100px;" alt="Stephanie Gessler"/><br /><sub><b>Stephanie Gessler</b></sub></a><br /><a href="https://github.com/codesandbox/codesandbox-client/commits?author=steguess" title="Frontend Developer">💻</a></td>
    <td align="center"><a href="https://github.com/CBRodulfo"><img src="https://avatars.githubusercontent.com/u/107241015?v=4" width="100px;" alt="Christian Barba"/><br /><sub><b>Christian Barba</b></sub></a><br /><a href="https://github.com/codesandbox/codesandbox-client/commits?author=CBRodulfo" title="UI/UX Designer">🎨</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->
