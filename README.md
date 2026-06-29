### 5-Line Project Summary
1. **Best Model Performance:** Logistic Regression yielded our optimal validation accuracy of ~58.7%, heavily outperforming an overfitted Random Forest model (~41.3%).
2. **Feature Engineering Insights:** Calculating head-to-head FIFA ranking differentials and Elo rating gaps served as the most powerful predictive indicators for match outcomes.
3. **Data Pipeline Integrity:** Implemented custom mapping dictionaries to resolve structural team-name string mismatches, successfully achieving a 0% missing value rate post-merge.
4. **Dynamic Bracket Correction:** Successfully engineered a recursive advancement simulation that parses exact match IDs, preventing team duplicates across all 104 tournament slots.
5. **Phase-Agnostic Engine:** Dynamically switches operational logic to support 3-way probabilistic splits for Group stages and zero-draw single-eliminations for Knockout phases.
