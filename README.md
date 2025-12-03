# IPL_Auction_Analytics

# 🏏 IPL Auction Analytics — Death Over Specialist Selection  
**A Data-Driven Evaluation of “Killer Instinct” Under Pressure**

This project simulates a real pre-auction analytics scenario.  
You are in a strategy room with the Head Coach and Owners. You must choose one bowler:

- **Bowler A — “The Machine”**  
  High accuracy, low economy, but mentally fragile under pressure.

- **Bowler B — “The Gambler”**  
  Expensive, aggressive, but deadly when he senses weakness.

Scouts say Bowler A is better because of a lower economy rate.  
The Coach disagrees:

> “Cricket is 40% physical and 60% mental.  
> Bowler B has the killer instinct — he turns dot-ball pressure into wickets.”

My mission: **prove it using data**.

---

# 🔥 Project Goals
### ✔ Quantify “Pressure” situations in death overs  
### ✔ Measure the probability of taking a wicket on the next ball  
### ✔ Build a Bayesian (or logistic) model controlling for:  
- Pitch Type  
- Batter Quality  
- Bowler Identity  

### ✔ Identify who truly performs better *under pressure*  
### ✔ Provide a final verdict: **Whom should the franchise buy?**

---

# 📁 Project Structure

IPL_Auction_Analytics/
│
├── data/
│ ├── IPL_Bowler_Detailed_Data.csv
│ ├── ipl_with_pressure_flag.csv
│ ├── model_coefficients_with_94CI.csv
│ └── pressure_effect_summary.csv
│
├── figures/
│ ├── pressure_effect_plot.png
│ └── pressure_effect_diff.png
│
├── notebooks/
│ ├── 01_data_exploration.ipynb
│ ├── 02_feature_engineering.ipynb
│ ├── bayesian_model.ipynb
│ └── model_and_verdict.ipynb
│
├── .gitignore
└── README.md


