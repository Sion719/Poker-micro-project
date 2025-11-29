# Poker-micro-project
Analyse human decision-making under uncertainty in poker by predicting player actions (fold / call / raise) from hand features, and extract insights into cognitive patterns such as risk assessment, attention to salient information, and reward evaluation.
Approach:
- Used UCI poker Hand Dataset to extract key hand features: number of high cards, suitedness, maximum and minimum card ranks.
- Simulated human-like actions based on hand strength to create fold/call/raise labels.
- Trained a simple XGBoost classifier to predict actions.
- Applied SHAP to interpret feature influence on decisions.

Key Insights:
- High-value cards strongly drive aggressive actions, showing attention to salient and reward-rich information.
- Suited hands moderately increase call/raise tendencies which reflects recognition of potential future reward.
- Low cards trigger conservative folding behaviour, highlighting risk-aversion patterns.
- Maximum card rank influences aggression while minimum card rank influences caution.

  Takeaway:
  This micro-project demonstrates the ability to model and interpret decision-making under uncertainty, connecting quantitative hand features to interpretable human cognitive behaviours. This approach is transferable to broader domains in neuroscience, decision science, and AI.
