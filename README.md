# Enhanced Detection of Heavy Drinking Episodes Using Accelerometer Data and Advanced Time Series Analysis

In this project, I delved into the realm of analyzing accelerometer data from smartphones to identify patterns associated with heavy drinking episodes. By harnessing advanced computational techniques to calculate permutation entropy and complexity, I aimed to unveil subtle nuances in motion data that could signal variations in alcohol consumption levels.

## Objective
The primary goal was to develop a robust analytical tool that leverages state-of-the-art algorithms for processing accelerometer readings. This tool is designed to differentiate between sober and heavy drinking states, offering insights into an individual's drinking behaviors and facilitating early intervention when necessary.

## Methodology
The project unfolded in several key phases:

### 1. Data Acquisition and Preprocessing
Initially, I curated a comprehensive dataset by concatenating all TAC readings into a single dataframe and merging accelerometer data with transdermal alcohol content (TAC) readings after time conversion to seconds from milliseconds. This preparatory step ensured a rich dataset that captures both motion dynamics and quantifiable alcohol intake levels.

### 2. Exploratory Data Analysis (EDA)
Utilizing visualization techniques, I explored the accelerometer data across three axes in conjunction with TAC values for each participant. This exploration was instrumental in understanding the data's structure and laying the groundwork for subsequent analysis.

### 3. Feature Extraction and Analysis
At the core of my analytical endeavor was the computation of permutation entropy and complexity. I employed a sophisticated module to calculate these metrics, which measure the disorder and structural complexity within time series data. This approach provided a nuanced understanding of motion patterns in relation to alcohol consumption.

### 4. Results Aggregation and Visualization
By aggregating the calculated metrics and correlating them with TAC levels, I could discern patterns indicative of heavy drinking. The results were visualized through scatter plots, effectively illustrating the relationship between motion complexity and alcohol intake.

## Key Insights
### Variability Across Axes
- Entropy and complexity vary across the x, y, and z axes for identical TAC levels, indicating that alcohol's impact on motion is direction-dependent.

### Relationship Between TAC Levels and Motion Complexity
- Observations show that with increasing TAC levels, movement complexity can either increase or decrease, suggesting alcohol's differential impact on movement predictability.

### Insight into the Dynamics of Movement
- Significant differences in entropy and complexity at similar TAC levels across axes highlight alcohol's multi-dimensional effect on movement.

### Potential for Predictive Modeling
- The metrics offer a dataset for developing models to predict TAC levels from movement complexity and entropy, useful for real-time monitoring and interventions.

### Implications for Intervention Strategies
- Analyzing movement patterns related to heavy drinking can inform proactive intervention strategies to mitigate alcohol-related harm.

## Conclusion
In this project, I explored how alcohol consumption affects human movement by analyzing accelerometer data with advanced entropy and complexity measures. The analysis revealed clear patterns that vary with alcohol levels, showing promise for developing models to predict alcohol consumption based on movement. This work opens new doors for using technology to monitor and address excessive drinking, highlighting the value of sophisticated data analysis in health and behavior studies.
