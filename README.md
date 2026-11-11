# Muhammad Umair Sarwar

M.Sc. student in Mathematics (Mathematics in Data Science) at TU Darmstadt, with an M.Phil. in Mathematics. I work on machine learning, optimisation and statistics, mostly on problems where the modelling assumptions matter as much as the code.

I am looking for Werkstudent and data science roles in Germany, and for funded PhD positions in machine learning and applied mathematics.

- M.Sc. Mathematics (Mathematics in Data Science), TU Darmstadt, since winter semester 2026/27
- M.Phil. Mathematics, Quaid-i-Azam University. Thesis: matrix games under q-rung interval-valued orthopair fuzzy sets
- Interests: multi-agent learning, distributed optimisation, uncertainty quantification, reliable machine learning, reproducible data pipelines

## Machine learning and optimisation projects

- [fair-multiagent-battery-control](https://github.com/MUmairSarwar/fair-multiagent-battery-control): six home batteries behind one transformer, controlled by independent Q-learning, PPO and MAPPO agents in a PettingZoo environment on 2025 German day-ahead prices. Benchmarked against a perfect-foresight LP: PPO reached about 68% of the LP optimum and had 58 kWh of overload against 939 kWh for a simple price rule. The same problem is also solved with dual decomposition and ADMM, with proportional and max-min fairness.
- [robust-federated-learning-ml-security](https://github.com/MUmairSarwar/robust-federated-learning-ml-security): PyTorch simulation of federated learning on MNIST under label flipping and a backdoor, comparing FedAvg, median, trimmed mean and a fuzzy client-reliability rule over three seeds. None of the rules stopped the backdoor (about 92% success at best), and the README analyses why.
- [germany-heat-risk-forecasting](https://github.com/MUmairSarwar/germany-heat-risk-forecasting): next-day maximum temperature and hot-day forecasts for Darmstadt from DWD observations, with chronological splits, split-conformal intervals and a Theil–Sen trend. The nominal 80% intervals covered 71.1% of holdout days.
- [strategic-classification](https://github.com/MUmairSarwar/strategic-classification): simulation of how a fixed logistic-regression classifier degrades when rejected individuals game one feature to cross the decision boundary.

## Data analytics projects

- [german-energy-operations](https://github.com/MUmairSarwar/german-energy-operations): 2025 German electricity data in a DuckDB warehouse built with Python and dbt, with 44 automated tests, a Streamlit dashboard and a scheduling scenario for a flexible four-hour process.
- [retail-customer-analytics](https://github.com/MUmairSarwar/retail-customer-analytics): sales, returns and RFM customer segmentation on the UCI Online Retail data with Python and SQL, plus a dashboard and executive summary.
- [customer-churn-prediction](https://github.com/MUmairSarwar/customer-churn-prediction): telecom churn classifier with a decision threshold chosen from an explicit cost ratio.

## Tools

Python (NumPy, pandas, scikit-learn, PyTorch, SciPy, CVXPY) · SQL (DuckDB, SQLite, dbt) · Streamlit · pytest · GitHub Actions · Git · R (learning)

## Languages

English (C1, IELTS 7.5) · German (A1, learning) · Urdu (native)

## Contact

[LinkedIn](https://www.linkedin.com/in/muhammad-umair-sarwar)
