# Data Scientist

* * *

**Language Skills:** Python, SQL, PySpark, SparkSQL, R, Java

**Data Science Skills:** Time Series Forecasting, Supervised ML, Unsupervised ML (Clustering, PCA), Deep Learning, Natural Language Processing Methods, Large Language Models - (Prompt Engineering, LangChain), Computer Vision

**Frameworks & Tools:** Sklearn, PyTorch, Tensorflow, PySpark, LangChain, Numpy, Pandas, PowerBI, Linux, Git, Docker, Relational Database, Data Warehousing, Databricks

* * *

## Education
- M.S., Applied Data Science	| Indiana University Indianapolis, USA (_May 2024_)
- PGP in Data Science | Praxis Business School Bengaluru, India (_March 2019_)
- B.E., Mechanical | Anna University Chennai, India (_June 2016_)

* * *

## Professional Experience
### Emory University Hospital
**Data Scientist  (_July 2024 - Present_)**
- Collaborated with a partner to **evaluate a commercially deployed 3D DBT breast AI screening model** using internal breast imaging dataset, analyzing performance across outcomes, demographics, and imaging characteristics, along with statistical evaluations; results to be presented at RSNA 2025.
- Built a pipeline to store and update a **large scale breast imaging dataset** of 2D, 3D DBT X-rays with imaging and text data. Preprocessed and included additional modalities (Ultrasound and MRI). **Data extraction, de-identification and storage management** of imaging data and clinilal structured and unstructured data including DICOM metadata. Enriched existing metadata additional metadata such as risk scores, state registry data, clinical and pathology reports, exam addendums. Increased total exams by 230%.
- Designed and built a **preprocessing pipeline for breast MRI data** for machine learning applications, standardizing MRI exams across different manufacturers. Implemented sequence selection, slice registration and subtraction (pre- and post-contrast), slice selection methods, and transformations, converting data into tensor format for ML use. Reduced data preprocessing effort by 80%.


### Accenture
**Data Scientist Specialist / Machine Learning Engineer                        (_April 2021 - June 2022_)**
- Improved a CPG client's **demand forecast** accuracy by 10-15% by using a Transformers net-based package integrated to **Azure Databricks Data Science** workflow. Built tracking of forecast accuracy, demand, supply, and inventory levels and custom metrics. Utilized MLflow to **track experiments**, log metrics, and compare runs for optimal model performance.
- Enhanced supply chain visibility through the design and development of manufacturing output metrics using **Power BI** dashboards and **Azure data pipelines** by bringing manufacturing data together. Leveraged Databricks (PySpark, SparkSQL), DataFactory for orchestration, Synapse, and Tabular models for data processing and storage.

**Data Scientist (_April 2020 - March 2021_)**
- Boosted **demand forecasting** accuracy by 5% for a Home Appliances client by deploying an **ensemble** of tree-based algorithms on Google Cloud Platform Cloud Run Service as Docker Containers, with FastAPI facilitating **real-time model inference**. 
- Utilized GCP Airflow for **workflow orchestration** and established a **feature store** to manage features on promotions, pricing, and seasonality. Scheduled complex SQL queries to run on Google BigQuery to process data from data lakes and loads to data marts.

**Analytics Consultant (_April 2019 - March 2020_)**
- Developed and implemented a sourcing **optimization solution**, utilizing analytics and NLP text similarity matching, boosting production efficiency by 20% for a key CPG client amid capacity challenges.
- For a Home Appliances Client, developed, and integrated **large scale data preprocessing** scripts using sparkSQL, PySpark and Pandas on Azure that pulls sales order data and ML demand forecast data from data warehouse to build a supply forecasting solution.


### Tata Consultancy Services
**Assistant Systems Engineer(_October 2016 - June 2018_)**
- Resolved technical **Oracle ERP** L1, L2 & L3 service requests for a client in the High Tech Security Solutions
- Wrote complex SQL queries to extract custom reports from Oracle Database that report product portfolio related information.
- Wrote or fixed bugs within **Oracle Stored Procedures, Triggers and Functions**.

* * *

## Internships

### ClearObject
**Machine Learning Engineer Intern (_January 2024 - April 2024_)**

- Integrated **computer vision systems** in manufacturing quality control and monitoring, involving data collection, labeling, and model fine-tuning using PyTorch and TensorFlow, focusing on **segmentation (U-net), detection (YOLO)**, and classification models
- Deployed refined models on edge devices and implemented in real-time client applications using NVIDIA’s TensorRT & DeepStream to enhance operational efficiency

### Google
**Open Source Contributor – LibreHealth for Google Summer of Code (_May 2023 - August 2023_)**
[Work Product Report](https://rohanisaac.blogspot.com/2023/08/google-summer-of-code-2023-ai-model.html)

- Integrated state of the art **computer vision models** to LibreHealth’s **Radiology AI application** for medical imaging diagnosis tasks such as multilabel classification and object localization through GradCam. Estimated to reduce time taken to diagnose by 20%
- Automated the **AI model selection** for LibreHealth’s radiology application by interacting with the image’s DICOM properties using modules constructed with Python Flask and Java Spring Boot, cutting down application configuration time completely.
- Modified **Flask API** endpoints, codebase structure for ease of integrating additional AI models through configuration file settings

* * *

## Research Work

### Indiana University - Health Informatics Lab
**Research Assistant (_September 2022 - April 2024_)**

[Repo](https://github.com/rogyizac/MD.ai)

- Led an NSF research study to analyze AI-Radiologist synergy through which integrated leading Kaggle **computer vision models** with MD.ai, an FDA approved Radiology AI platform. Included models for classification, segmentation, and object localization.
- The study identified improved AI-radiologist collaboration, leading to a 20% reduction in diagnostic times.
- Paper published and to be presented at ISBI 2024 conference. 1st Author
- Implemented a **Retrieval Augmented Generation (RAG)** based system using ChromaDB and Llama LLM model on clinical discharge notes MIMIC data to improve patient diagnosis outcomes through Semantic Search and Summarization tasks
- Implemented a **Retrieval Augmented Generation (RAG)** based system using Neo4j Graph DB, Llamafile and Mistral 7B on clinical **EHR** relational data that generate cypher queries to improve search and patient outcomes through **Semantic Search and Summarization tasks**.

[Project](https://librehealth.io/projects/lh-radiology/)
- Assisted in research, analysis and writing a research paper on open source Radiology application integrated with embedded AI system architecture and contributed in development of the application.
- Paper published and presented at AIME 2023 conference. 1st Author

* * *

## Publications
1. [Saptarshi Purkayastha, Rohan Isaac, Sharon Anthony, Shikhar Shukla, Elizabeth A. Krupinski, Joshua A. Danish, Judy W. Gichoya. A general-purpose AI assistant embedded in an open-source radiology information system.](https://doi.org/10.48550/arXiv.2303.10338)
2. Measuring Impact of Radiologist-AI Collaboration: Efficiency, Accuracy, and Clinical Impact – 1st Author, ISBI 2024 Conference (Accepted, Yet to publish)

* * *

## Master's Thesis
**Thesis Title:** A Multi-modal Medical Anomaly Detector Based on Cascade Variational Autoencoder and BERT - [Repo](https://github.com/rogyizac/CVAD)
- An existing Cascade **Variational Auto Encoder** model that detects out-of-distribution medical images from in-distribution ones in a self-supervised way is extended by integrating a **BERT model** to embed medical image related reports, and fusing the latent representations of the image and the report by adapting an **Early Fusion network** that can distinguish the medical report of an in-distribution medical image from the out-of-distribution image in a self-supervised manner.
- Applied this advanced model to MIMIC-CXR and COCO captions data, showcasing its adaptability and generalization strength.

* * *

## Projects

### Forecasting Consumer Credit Card Balances for Large Banks: A Time Series Analysis
[Repo](https://github.com/rogyizac/projects/tree/main/ForecastingConsumerCreditBalances)

The research explores the quarterly trends of consumer credit card balances for large banks and aims to forecast future balances using advanced time series methods. Insights from this study can help banks in strategic decision-making, risk assessment, and resource allocation. Applied simple to complex time series forecasting techniques and analysis of the model outputs.

### NHANES Informatics Project
[Repo](https://github.com/rogyizac/NHANES_informatics_project)

Performed a comparative analyses between survey respondent's demographics, health insurance coverage and hospital utilization levels. We undertook a detailed analysis of survey respondents data on their demographics, health insurance and health care utilization information. Identified deeper insights through data analyses, cluster analysis and through machine learning techniques and statistical models.

### Hand Gesture Recognition using CV
[Repo](https://github.com/rogyizac/Gesture-recognition-using-CV)

Utilized a Single Shot MultiBox Detector (SSD) for real-time recognition of hand gestures such as thumbs up and open palms, mapping these gestures to keyboard functionalities like arrow keys and space bar. Leveraging OpenCV, the system translates detected gestures into corresponding keyboard actions, enabling intuitive gesture-based controls in applications. For example, in web browsing, gestures can mimic scrolling or page navigation, showcasing a seamless integration of computer vision and user interaction.
