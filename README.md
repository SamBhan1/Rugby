# Rugby Match Outcome Predictor

## Goal
Predict rugby match winners using historical team performance data.

## Dataset
- 2,783 international rugby matches
- Date range: [your range]
- Teams: [number of teams]

## Features Engineered
1. **Team Strength**: Historical win rate for each team
2. **Strength Difference**: Home strength - Away strength
3. **Recent Form**: Wins in last 5 matches
4. **Home Advantage**: Binary indicator
5. **World Cup**: Binary indicator for World Cup matches

## Models Tested
- **LogisticRegression**: 67.7% accuracy ✅
- **RandomForest**: 65.6% accuracy

## Key Learnings
1. Team historical strength is the strongest predictor
2. Recent form adds small improvement (+0.4%)
3. Simpler models (LogisticRegression) can outperform complex ones
4. Data leakage (using scores) gives false 100% accuracy
5. Sports prediction is inherently difficult due to randomness

## Results
- Baseline (always predict home): 57%
- **Final model: 67.7% accuracy**
- **10.7 percentage points improvement over baseline**
