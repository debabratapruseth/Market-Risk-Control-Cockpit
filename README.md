# AI-Powered Market Risk Control Cockpit

This project demonstrates how financial institutions can combine deterministic controls, machine-learning anomaly detection, exposure analysis, and generative AI to monitor FX market-data quality.

## Blog Post
Refer the blog post for detail explaination incuding the archietcture : https://debabratapruseth.com/build-ai-market-risk-control-cockpit-python/

## The pipeline:

1. Generates synthetic market observations, scenarios, exposures, and historical incidents.
2. Validates input data and engineers risk features.
3. Detects stale prices, vendor divergence, latency, missing values, and extreme movements.
4. Uses Isolation Forest to identify statistical anomalies.
5. Adds peer-market and historical context.
6. Estimates simplified portfolio scenario impact.
7. Prioritises alerts according to technical severity and business materiality.
8. Generates structured investigation reports.
9. Displays results in a Streamlit dashboard.

This repository is intended for education and prototyping. It does not calculate production-grade regulatory VaR and should not be used for trading, valuation, or regulatory decisions without appropriate governance and validation.
