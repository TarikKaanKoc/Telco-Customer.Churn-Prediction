# Telco-Customer Churn-Prediction

<img src="https://github.com/TarikKaanKoc/Telco-Customer.Churn-Prediction/blob/main/image.png?raw=True" width="8000" align="center">

<div class="alert alert-primary" style="margin-top: 20px">

    

<strong><h2>Bussines Problem</h2><p>
    
It is desired to develop a machine learning model that can predict customers who will leave the company. You are expected to perform the necessary data analysis and feature engineering steps before developing the model.</p>
    
    
<strong><h2>Dataset Story</h2></strong>
<blockquote><p><strong>Telco - churn data includes information about a fictitious telecom company that provided home phone and internet services to 7,073 California customers in the third quarter. It shows which customers have left, stayed or signed up for their service.</strong></p>
</blockquote>
    
<br>
</br>
<ul>
</ul>
<ul>

<li><strong>Total Features : 21</strong></li>
<li><strong>Total Row : 7043 </strong> </li>
<li><strong>CSV File Size : 977.5 kB</strong></li>

</ul>
</div>


 Sr. | Feature  | Description |
--- | --- | --- 
1 | customerID | Customer Id
2 | Gender | Whether the customer is a male or a female
3 | SeniorCitizen | Whether the customer is a senior citizen or not (1, 0)
4 | Partner | Whether the customer has a partner or not (Yes, No) check
5 | Dependents | Whether the customer has dependents or not (Yes, No) grid_3x3
6 | Tenure | Number of months the customer has stayed with the company check
7 | PhoneService | Whether the customer has a phone service or not (Yes, No) text_format
8 | MultipleLines | Whether the customer has multiple lines or not (Yes, No, No phone service) text_format
9 | InternetService | Customer’s internet service provider (DSL, Fiber optic, No ttext_format
10 | OnlineSecurity | Whether the customer has online security or not (Yes, No, No internet service)
...
...
...



---

<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p></p><div class="list-group" id="list-tab" role="tablist">
  <h3 class="list-group-item list-group-item-action active" data-toggle="list" role="tab" aria-controls="home" style = "border:2px solid #2C3E50;background-color:#2C3E50; color:white; font-family:Verdana;text-align: center; font-size:140%;font-weight: Bold;">Notebook Content</h3>
  <a class="list-group-item list-group-item-action" data-toggle="list" href="#1" role="tab" aria-controls="profile" target="_self" style = "color:#2C3E50; font-family:Verdana;text-align: center; font-size:130%;font-weight: Bold;">Import Libraries<span class="badge badge-primary badge-pill">1</span></a>
  <a class="list-group-item list-group-item-action" data-toggle="list" href="#2" role="tab" aria-controls="messages" target="_self" style = "color:#2C3E50; font-family:Verdana;text-align: center; font-size:130%;font-weight: Bold;">Load and Check Data<span class="badge badge-primary badge-pill">2</span></a>
  <a class="list-group-item list-group-item-action" data-toggle="list" href="#2" role="tab" aria-controls="messages" target="_self" style = "color:#2C3E50; font-family:Verdana;text-align: center; font-size:130%;font-weight: Bold;">Exploratory Data Analysis<span class="badge badge-primary badge-pill">3</span></a>
  <a class="list-group-item list-group-item-action" data-toggle="list" href="#2" role="tab" aria-controls="messages" target="_self" style = "color:#2C3E50; font-family:Verdana;text-align: center; font-size:130%;font-weight: Bold;">Feature Engineering<span class="badge badge-primary badge-pill">4</span></a>
 <a class="list-group-item list-group-item-action" data-toggle="list" href="#2" role="tab" aria-controls="messages" target="_self" style = "color:#2C3E50; font-family:Verdana;text-align: center; font-size:130%;font-weight: Bold;">Preparations<span class="badge badge-primary badge-pill">5</span></a>
  <a class="list-group-item list-group-item-action" data-toggle="list" href="#2" role="tab" aria-controls="messages" target="_self" style = "color:#2C3E50; font-family:Verdana;text-align: center; font-size:130%;font-weight: Bold;">Result<span class="badge badge-primary badge-pill">6</span></a>
 
    
</div>
</div>
</div>



---
