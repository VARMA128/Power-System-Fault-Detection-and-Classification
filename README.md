⚡ Power System Fault Detection and Classification using IBM Cloud Watsonx.ai Studio
📌 Project Overview
This project detects and classifies faults in power systems using IBM Cloud’s Watsonx.ai Studio for building and deploying machine learning models.
By leveraging Watsonx.ai's AutoAI capabilities, the system analyzes voltage and current waveform data to detect abnormal conditions and classify faults into different categories for faster decision-making and preventive maintenance.

🎯 Objectives
Fault Detection – Identify fault occurrence in power system waveforms.

Fault Classification – Categorize faults into:

Single Line-to-Ground (LG)

Line-to-Line (LL)

Double Line-to-Ground (LLG)

Three-Phase (LLL)

Cloud-Based ML Deployment – Use IBM Cloud Watsonx.ai Studio for model training, testing, and deployment.

Scalable & Reliable Solution – Ready for integration with real-time monitoring systems.

🛠️ Tech Stack
Platform: IBM Cloud – Watsonx.ai Studio

Services Used:

Watsonx.ai – Model training & AutoAI pipeline

Cloud Object Storage (COS) – Dataset storage

IBM Cloud Notebooks – Data preprocessing & visualization

Programming Language: Python

Libraries (in notebooks):

pandas, numpy – Data handling

matplotlib, seaborn – Visualization

Watson Machine Learning SDK – Deployment

📂 Project Structure
Power-System-Fault-Detection-IBM/
│── fault-data.csv/                  # Dataset files (uploaded to COS from Kaggle)
│── notebooks/             # IBM Cloud notebooks for data analysis
│── results/               # Classification reports and plots
│── README.md               # Documentation

      # Dependencies for local run
🔍 Methodology
Data Upload to IBM Cloud

Store dataset in IBM Cloud Object Storage.

Data Preprocessing

Clean and normalize waveform data using IBM Cloud notebooks.

Model Training using Watsonx.ai Studio

Create a project in Watsonx.ai Studio.

Use AutoAI to automatically preprocess, select algorithms, and tune models.

Model Deployment

Deploy the best model using Watson Machine Learning service.

Generate API endpoint for real-time prediction.

Visualization & Monitoring

Plot waveform patterns.

Monitor predictions through deployed API.

📊 Results
Achieved high classification accuracy using Watsonx.ai AutoAI pipeline.

Successfully differentiated fault types from waveform data.

Ready-to-use API endpoint for integration with SCADA or IoT-based monitoring systems.

🚀 How to Run on IBM Cloud
Create an IBM Cloud Account – Sign up here

Enable Watsonx.ai Service

Go to the Watsonx.ai dashboard

Create a new project.

Upload Dataset to COS

Create a bucket in Cloud Object Storage.

Upload the CSV waveform dataset.

Launch AutoAI in Watsonx.ai

Select dataset from COS.

Configure target column (fault type).

Train the model.

Deploy Model

Save best pipeline.

Deploy via Watson Machine Learning.

Use REST API for predictions.

📈 Future Improvements
Integrate with IBM IoT Platform for real-time streaming fault detection.

Add deep learning models in Watsonx.ai Studio for improved accuracy.

Expand dataset with real-world noisy signals.
