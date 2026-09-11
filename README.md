# Active Directory Incident Volume Forecasting

## Overview
This project applies time series forecasting to IT operations data to predict Active Directory incident ticket volumes. By accurately forecasting ticket loads, IT infrastructure teams can optimize shift coverage, improve resource allocation, and reduce response times for L1 and L2 support engineers.

## Business Value
* **Resource Optimization:** Enables proactive staffing rather than reactive firefighting.
* **SLA Compliance:** Helps ensure sufficient coverage to meet Service Level Agreements during predicted peak load times.
* **Data-Driven ITSM:** Transitions standard IT Service Management from historical reporting to predictive analytics.

## Dataset
The model was trained on a dataset of **6,000 resolved incident records**. The data was extracted, cleaned, and processed to identify daily and weekly volume trends. *(Note: Data has been anonymized/omitted for enterprise security compliance).*

## Technology Stack
* **Python:** Core programming language.
* **Pandas:** Used for data extraction, cleaning, and time-series manipulation.
* **Google Colab:** Development environment.
* **Data Visualization:** Generated trend visualizations to communicate findings to operational leadership.

## Future Enhancements
* Wrap the forecasting model in a REST API using FastAPI to allow integration with platforms like ServiceNow.
* Build an agentic workflow that alerts shift leads automatically when predicted volumes exceed standard thresholds.
