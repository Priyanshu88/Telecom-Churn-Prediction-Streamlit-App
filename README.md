<div align='center'>
  

  <h1>Telecom Churn Prediction Streamlit App</h1>

  <p>
This is a Streamlit web application for predicting Telecom Churn. The app uses a trained machine learning model to predict whether a customer is likely to churn or not based on certain input features.
  </p>
  

<!-- Badges -->

<a href="https://telecom-churn-prediction-app-92spidw8wnl.streamlit.app/" target="_blank">![](https://img.shields.io/website-up-down-green-red/http/monip.org.svg)</a>
![](https://img.shields.io/badge/Maintained-Yes-indigo)
![](https://img.shields.io/github/forks/Priyanshu88/Telecom-Churn-Prediction-Streamlit-App.svg)
![](https://img.shields.io/github/stars/Priyanshu88/Telecom-Churn-Prediction-Streamlit-App.svg)
![](https://img.shields.io/github/issues/Priyanshu88/Telecom-Churn-Prediction-Streamlit-App)
![](https://img.shields.io/github/last-commit/Priyanshu88/Telecom-Churn-Prediction-Streamlit-App)
  
 
 <h4>
    <a href="https://priyanshu88-diabestes-prediction-streamlit-app-main-5komds.streamlit.app/">View Demo</a>
  <span> · </span>
    <a href="https://github.com/Priyanshu88/Telecom-Churn-Prediction-Streamlit-App/blob/master/README.md">Documentation</a>
  <span> · </span>
    <a href="https://github.com/Priyanshu88/Telecom-Churn-Prediction-Streamlit-App/issues">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/Priyanshu88/Telecom-Churn-Prediction-Streamlit-App/issues">Request Feature</a>
  </h4>
</div>

<br />


<!-- Table of Contents -->

## :notebook_with_decorative_cover: Table of Contents

- [Dataset](#signal_strength-dataset)
- [Dependencies](#toolbox-dependecies)
- [Installation](#gear-installation)
- [Usage](#play_or_pause_button-usage)
- [Inputs](#construction-inputs)
- [Outputs](#rocket-outputs)
- [Deployment and Notebook](#triangular_flag_on_post-deployment-and-notebook)
- [License](#balance_scale-license)
- [Contact](#handshake-contact)



## :signal_strength: Dataset

The trained dataset is originally from the IBM Sample Datasets. The objective is to predict behavior to retain customers by analyzing all relevant customer data and developing focused customer retention programs. The dataset can be found on [`Kaggle`](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). It includes following information:

- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

### Details
- Number of Rows: 7043 (Customers)
- Number of Columns: 21 (Features)
- Missing Attribute Values: Yes
- Class Distribution: (churn value Yes is interpreted as "customer churn")



## :toolbox: Dependecies

`streamlit`

`pandas==1.4.4`

`scikit-learn==1.2.1`

## :gear: Installation

Clone the repository and install the required dependencies using the following commands:

```bash
git clone https://github.com/Priyanshu88/Telecom-Churn-Prediction-Streamlit-App.git
```

```bash
cd Telecom-Churn-Prediction-Streamlit-App
```

```bash
pip install -r requirements.txt
```

```bash
streamlit run app.py
```

## :play_or_pause_button: Usage

1. Open the app in your web browser.
2. Enter the required information in the input fields.
3. Click the 'Predict' button to generate the prediction.



## :construction: Inputs
Click on the link and reboot the tool or run locally and enter following details:

* Tenure (months)
* Phone Service: 0 or 1
* Contract: 0 - Month-to-month, 1 - One year, 2 - Two year
* Paperless Billing: 0 or 1
* Payment Method: 0 - Bank transfer (automatic), 1 - Credit card (automatic), 2 - Electronic check, 3 - Mailed check
* Monthly Charges


## :rocket: Outputs
The app will display following messages:

* "The customer is likely to churn." or "The customer is unlikely to churn."
* "The probability of churn is: (X, Y)".



## :triangular_flag_on_post: Deployment and Notebook

This tool has been deployed using [`Streamlit`](https://streamlit.io/). Learn about streamlit deployment [`here`](https://docs.streamlit.io/streamlit-community-cloud/get-started/deploy-an-app). Checkout the notebook repository [`here`](https://github.com/Priyanshu88/Telecom-Churn-Prediction-Streamlit-App) from where the pickle file has been imployed in the tool.



## :balance_scale: License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Priyanshu88/Telecom-Churn-Prediction-Streamlit-App/blob/main/LICENSE) file for details.



## :handshake: Contact

![](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)

Your Name - [@twitter_handle](https://twitter.com/Priyans75729802) - 2040020@sliet.ac.in

Project Link: [https://github.com/Priyanshu88/Telecom-Churn-Prediction-Streamlit-App.git](https://github.com/Priyanshu88/Telecom-Churn-Prediction-Streamlit-App.git)
<hr />
<br />
<div align="center">Don't forget to leave a star ⭐️</div>
