# SailPoint Databricks Integration Examples

This repository contains example code used in the presentation at **SailPoint Developer Days 2025**. The code demonstrates how to use Databricks notebooks to analyze identity data from the **SailPoint Identity Security Cloud**.

## Overview

The repository includes a collection of Databricks notebooks that showcase various use cases for analyzing identity data. These examples leverage the SailPoint SDK and Databricks' powerful data processing capabilities to extract, transform, and visualize identity-related insights.

## Repository Structure

The repository is organized as follows:

- **Analysis Notebooks**:
  - `Analysis - Entitlement Network.ipynb`: Creates a network graph of entitlements assigned to identities, visualizing relationships and overlaps.
  - `Analysis - Identity Attribute.ipynb`: Analyzes identity attributes such as country and department, and generates visualizations like sunburst charts.

- **Object Notebooks**:
  - `Object - Access Assignments.ipynb`: Retrieves and processes access assignments for identities.
  - `Object - Accounts.ipynb`: Extracts account data and processes it for analysis.
  - `Object - Entitlements (Search).ipynb`: Searches and retrieves entitlement data.
  - `Object - Form Instances.ipynb`: Retrieves and processes form instance data.
  - `Object - Forms.ipynb`: Extracts custom form definitions.
  - `Object - Identities.ipynb`: Retrieves identity data and processes it for analysis.
  - `Object - Personal Access Tokens.ipynb`: Extracts personal access token data.
  - `Object - Workflows.ipynb`: Retrieves and processes workflow data.

## Prerequisites

To use the notebooks in this repository, you will need:

1. **Databricks Workspace**: A Databricks environment to run the notebooks.
2. **SailPoint Identity Security Cloud**: Access to a SailPoint tenant with API credentials.
3. **Python Libraries**: The following Python libraries are required:
   - `sailpoint` (SailPoint SDK)
   - `pyspark`
   - `requests`
   - `urllib3`
   - `plotly` (for visualizations in analysis notebooks)

## Setup Instructions

1. Clone this repository to your local machine or Databricks workspace.
2. Configure the required secrets in Databricks:
   - `sailpoint-readall-client`: Client ID for accessing the SailPoint API.
   - `sailpoint-readall-secret`: Client secret for accessing the SailPoint API.
3. Open the notebooks in Databricks and run the cells in order.

## Key Features

- **Identity Data Analysis**: Analyze identity attributes, access assignments, and entitlements.
- **Visualization**: Generate visualizations such as sunburst charts and network graphs.
- **Integration with SailPoint SDK**: Demonstrates how to use the SailPoint SDK to interact with the Identity Security Cloud.

## License

This repository is provided as an example for educational purposes. Please refer to the SailPoint Developer Days 2025 guidelines for usage restrictions.

---

For questions or feedback, feel free to reach out during the SailPoint Developer Days 2025 event.
