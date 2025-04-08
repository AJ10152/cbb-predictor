# College Basketball Predictor

This project aims to predict NCAA Men's Basketball game outcomes, with a focus on both regular season games and March Madness tournament outcomes. Using historical data, advanced stats, and various features, the goal is to build a model that can forecast the results of future games, simulate March Madness brackets, and analyze what factors influence wins.

## Data Sources
- [Kaggle - NCAA March Madness](https://www.kaggle.com/datasets)
- [Sports Reference - NCAA](https://www.sports-reference.com/cbb/)

## Project Workflow
### Phase 1: Data Collection
- Collect data for multiple seasons (regular season & tournament)
- Focus on team-level stats, including offensive/defensive efficiency, shooting percentages, turnovers, and more.

### Phase 2: Data Cleaning & Exploration
- Clean and preprocess data for feature extraction.
- Conduct exploratory data analysis (EDA) to identify patterns and trends.

### Phase 3: Feature Engineering
- Develop new features such as rolling averages, win streaks, seed differences, etc.
- Create matchup-based features like team strength differentials.

### Phase 4: Modeling
- Train models on regular season data.
- Test on March Madness outcomes.
- Compare different algorithms: Logistic Regression, Random Forest, XGBoost.

### Phase 5: Evaluation & Visualization
- Assess model performance using accuracy, ROC-AUC, and confusion matrices.
- Create visualizations to analyze feature importance and prediction accuracy.

### Phase 6: Bracket Simulation (Stretch Goal)
- Simulate March Madness brackets using Monte Carlo methods or other techniques.
  
## Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/cbb-predictor.git
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebooks in `notebooks/` to explore data and build the model.

## Results
- Model accuracy and prediction results will be documented and visualized in the `outputs/` folder.
  
## Future Improvements
- Add player-level data for deeper insights.
- Integrate more advanced machine learning techniques (e.g., neural networks).
- Create a dashboard or web app to simulate and visualize bracket predictions.

---

