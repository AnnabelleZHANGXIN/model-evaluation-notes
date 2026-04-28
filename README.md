# Model Evaluation Notes

## Common Issues in Machine Learning Models

### Overfitting
- High training accuracy but low validation accuracy
- Often caused by overly complex models or insufficient data
- Can be detected using cross-validation

### Data Leakage
- Model has access to information it should not have
- Leads to unrealistically high performance
- Common in improper data splitting

### Imbalanced Data
- Model biased towards majority class
- Requires techniques such as resampling or class weighting

## Key Takeaways
- Always validate models using proper validation techniques
- Do not rely on accuracy alone
- Focus on generalisation rather than training performance
