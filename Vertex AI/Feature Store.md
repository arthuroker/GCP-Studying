
*What is the issue?*

1) Different teams may work independently on the same feature

2) Computing complex features on-demand during prediction creates latency issues that make real-time applications impractical

3) Feature health blind spots, drift of the feature

4) Skew, training versus serving uses different formats for input data

*What is it*

A centralized repository for storing, versioning, and serving pre-computed ML features

Features can be reuses across multiple models, teams, and both in training and prediction

Low-latency serving capabilities

Helps track feature drift and data quality

*Workflow*

1) Engineer features from raw data
2) Centralized in Feature Store
3) Model training
4) or Serving same features for predicitions

