# Data Visualization in Python

## Why Visualize?
Visualization makes patterns and trends easier to understand than raw numbers.

## Libraries
- **Matplotlib**: Basic plotting
- **Seaborn**: High-level statistical plots
- **Plotly**: Interactive visualizations

## Common Plots
- Bar chart → categorical comparisons
- Line chart → trends over time
- Scatter plot → relationships between variables
- Histogram → distribution of values

## Example
```python
import seaborn as sns
sns.histplot(df['Sales'], bins=10)

