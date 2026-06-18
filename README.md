# Part-2-RFM-Segmentation-Retention-Strategy
```markdown
# Customer Analysis and Retention Strategy

## Project Overview

This project provides a comprehensive framework for customer analysis, segmentation, and personalized retention strategies. It leverages RFM (Recency, Frequency, Monetary) modeling combined with non-RFM signals (like loyalty tiers and support ticket interactions) to create granular customer segments. The goal is to enable data-driven decision-making for customer engagement and to optimize marketing campaign prioritization.

### Key Features:
-   **RFM Feature Building:** Calculates Recency, Frequency, and Monetary values for each customer.
-   **Non-RFM Signal Integration:** Incorporates external customer data such as loyalty tiers, support ticket counts, city tiers, age groups, and acquisition channels.
-   **Refined Customer Segmentation:** Creates actionable customer segments based on a combination of RFM scores and non-RFM signals, allowing for a deeper understanding of customer behavior and potential churn risks.
-   **Retention Recommendations:** Provides tailored retention strategies for each identified customer segment.
-   **Campaign Budget Prioritization:** Outlines a methodology for prioritizing marketing campaigns for specific segments, especially under limited budget scenarios.
-   **Manual Customer Review:** Includes a section for manually reviewing specific high-value or at-risk customer IDs to make nuanced, individualized retention decisions.

## Setup Instructions

To run this notebook, you will need:

1.  **Google Colab Environment:** This notebook is designed to be executed in Google Colaboratory.
2.  **Google Drive Access:** The data files are expected to be stored in your Google Drive.

### Data Files:
Ensure the following CSV files are placed in a folder named `d2c churn data package` within `MyDrive/Capstone Project/` in your Google Drive:
-   `orders.csv`
-   `support_tickets.csv`
-   `customers.csv`

The full path to your data folder should be similar to:
`/content/drive/MyDrive/Capstone Project/d2c churn data package/`

## How to Run

1.  **Open in Google Colab:** Open this `.ipynb` file in Google Colab.
2.  **Mount Google Drive:** Run the first code cell to mount your Google Drive. Follow the prompts to authorize Colab to access your Drive.
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```
3.  **Verify Data Path:** The notebook automatically checks for the presence of the required CSV files. Ensure your data is correctly placed in `'/content/drive/MyDrive/Capstone Project/d2c churn data package'`. Adjust the `directory_path` variable if your data is located elsewhere.
4.  **Execute Cells Sequentially:** Run all code cells in the notebook sequentially from top to bottom. This will:
    -   Load the necessary data.
    -   Calculate RFM features.
    -   Integrate non-RFM signals.
    -   Perform customer segmentation.
    -   Generate retention recommendations and campaign prioritization insights.
    -   Display a manual review section for selected customer IDs.

## Resources

-   **Pandas Library:** Used for data manipulation and analysis.
-   **NumPy Library:** Used for numerical operations.
-   **Google Colaboratory Documentation:** For information on using the Colab environment.
-   **RFM Analysis Concepts:** General principles of Recency, Frequency, Monetary analysis.
-   **Customer Segmentation Best Practices:** Methodologies for dividing a customer base into distinct groups for targeted marketing.
```
