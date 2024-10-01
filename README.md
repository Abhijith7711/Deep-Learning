# Locally Weighted Regression (LWR) 

### Definition
- **Locally Weighted Regression (LWR)** is a non-parametric regression technique that assigns different weights to data points based on their proximity to the point where the prediction is being made.

### Key Characteristics
- **Non-parametric**: Does not assume a fixed form for the model, allowing the complexity to grow with the data.
- **Local model**: Uses nearby data points to create a local model for each prediction.
- **Weighting function**: Typically uses a kernel (e.g., Gaussian) to assign higher weights to closer points and lower weights to distant ones.

### Applications
- **Non-linear data fitting**: Works well for datasets where relationships between variables are not globally linear.
- **Real-time predictions**: Useful in dynamic systems where local trends are more important than global patterns.
- **Smoothing data**: Helps smooth out noisy data by locally fitting simple models to subsets of the data.
- **Robotics**: Frequently used in robotics for tasks like trajectory planning or motion control, where quick, adaptive predictions are needed.
- **Economic modeling**: Applied in scenarios where economic indicators change over time, requiring localized predictions.
- **Medical data**: Helps adapt to patient-specific trends, improving the accuracy of medical predictions.

### Advantages
- **Flexible**: Can fit any data structure (linear or non-linear) as it adapts locally.
- **No global assumptions**: Focuses on local patterns rather than assuming a fixed relationship across the entire dataset.

### Disadvantages
- **Computationally expensive**: Requires recalculating weights for each prediction, making it less efficient on large datasets.
- **Memory intensive**: The entire dataset must be retained to make predictions, leading to higher memory usage.
