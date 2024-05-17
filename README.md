Predicting Disease Outbreaks Using Time Series Analysis and Classification
Overview
This project focuses on predicting disease outbreaks with a particular emphasis on the novel coronavirus (COVID-19) as a case study. We utilized time-series analysis techniques such as ARIMA, Prophet, and LSTM, alongside classification methods including decision trees, random forests, and neural networks to forecast and categorize outbreak risks.

Team Members
Aniket Ranjeet Sharma - anikshar@iu.edu
Jayanand Hiremath - jhiremat@iu.edu
Preetham Reddy Vinnamala - savinn@iu.edu
Abstract
We developed predictive models to classify countries into low, moderate, and high-risk categories based on their healthcare infrastructure and socio-economic metrics, using machine learning algorithms. The methodologies are adaptable to other infectious diseases, making this a versatile tool in global health crisis management.

Installation
Clone the repository:
bash
Copy code
git clone [repository-url]
Install the required Python packages:
Copy code
pip install -r requirements.txt
Data Collection
The primary datasets include:

Outbreak data from WHO's Disease Outbreak News and the Coronavirus Dashboard.
Medical parameter data from various sources including Statista covering hospital bed density, ICU availability, health expenditure, and more.
Usage
Run the main script to execute the analysis:

css
Copy code
python main.py
Methods
We employed a variety of forecasting and classification techniques:

Time Series Forecasting: ARIMA, Prophet, and LSTM.
Classification: Random Forest, Decision Trees, and Neural Networks.
Results
The models were able to effectively predict and classify the risk levels of different countries, assisting in strategic planning for healthcare resource allocation.

Discussion
The findings underscore the utility of predictive analytics in public health, particularly for pandemic preparedness. Future enhancements will focus on integrating more granular data and sophisticated algorithms.

References
For detailed references, consult the references.txt file.
