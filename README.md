# NBA-optimization
This project combines supervised learning with constrained optimization to evaluate NBA player performance and construct optimal team rosters under realistic constraints such as salary caps and positional requirements.

Developed as part of a summer analytics course, the project demonstrates how data-driven methods can improve decision-making in professional sports, from free agency and draft strategy to long-term roster planning.

## Project Summary

A custom performance metric was developed using Lasso regression to predict team wins. These model coefficients were then mapped to individual player statistics to estimate each player's contribution to team success. The resulting player-level metrics were used in an optimization model that selects the most competitive roster subject to real-world constraints, including:

- Salary cap limits
- Positional requirements (e.g., minimum number of guards, forwards, and centers)
- Roster size restrictions

## Tools and Techniques

- Python (Pandas, NumPy, scikit-learn, CVXPY)
- Regularized regression: Lasso, Ridge, and ElasticNet
- Feature engineering and normalization
- Time-series-aware training/test splits
- Optimization modeling using CVXPY
- Data scraping using the `hoopR` R package

## Project Structure

## Key Results

- Lasso regression produced the best model (R² = 88.04%, MSE = 15.25)
- Optimization algorithm generated practical NBA rosters with a mix of star and undervalued players
- Simulated roster construction under different budget scenarios and constraints

## Business Implications

- Improved free agency and draft decisions based on data-driven metrics
- Cost-effective team construction through optimization under financial constraints
- Framework can be adapted for other sports leagues (e.g., WNBA) or scouting models
- Potential for future enhancements including injury risk, contract incentives, and trade analysis

## Authors

Group project by:  
Jose Smith, Graeme Ashley, Timothy Wijaya| MS in Business Analytics, USC 
