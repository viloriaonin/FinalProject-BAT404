Execution Instructions (How to Run the Pipeline)

This project was built and optimized using Google Colab. To reproduce the results, evaluate the models, and view the interactive outputs, please follow these steps:

**1. Environment Setup**
* Download the `FinalProject-BAT 404.ipynb` file from this repository.
* Open [Google Colab](https://colab.research.google.com/) and upload the notebook via **File > Upload notebook**.

**2. Data Ingestion**
* Download the raw dataset (`city_day.csv`) associated with this project.
* In your active Colab session, click the **Folder icon (Files)** on the left-hand sidebar.
* Click the **Upload icon** and upload the dataset directly into the Colab environment. 

**3. Pipeline Execution**
* Navigate to the top menu bar and select **Runtime > Run all**.
* The pipeline will automatically execute all CRISP-DM phases sequentially. 
* *Note on Execution Time:* Phase 4 contains a Multi-City ARIMA forecasting loop that processes 26 independent temporal models. Please allow 30–60 seconds for this specific cell to complete its automated tuning and execution.
