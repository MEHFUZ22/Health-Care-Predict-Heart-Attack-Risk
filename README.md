<!DOCTYPE html>
<html>
<head>

</head>
<body>
<h1>Heart Disease Prediction Report</h1>

<h2>Problem statement:</h2>
<p>Cardiovascular diseases are the leading cause of death globally. It is therefore necessary to identify the causes and develop a system to predict heart attacks in an effective manner. The data below has the information about the factors that might have an impact on cardiovascular health.</p>

<h2>Dataset description:</h2>
<table>
  <tr>
    <th>Variable</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Age</td>
    <td>Age in years</td>
  </tr>
  <tr>
    <td>Sex</td>
    <td>1 = male; 0 = female</td>
  </tr>
  <tr>
    <td>cp</td>
    <td>Chest pain type</td>
  </tr>
  <tr>
    <td>trestbps</td>
    <td>Resting blood pressure (in mm Hg on admission to the hospital)</td>
  </tr>
  <tr>
    <td>chol</td>
    <td>Serum cholesterol in mg/dl</td>
  </tr>
  <tr>
    <td>fbs</td>
    <td>Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)</td>
  </tr>
  <tr>
    <td>restecg</td>
    <td>Resting electrocardiographic results</td>
  </tr>
  <tr>
    <td>thalach</td>
    <td>Maximum heart rate achieved</td>
  </tr>
  <tr>
    <td>exang</td>
    <td>Exercise induced angina (1 = yes; 0 = no)</td>
  </tr>
  <tr>
    <td>oldpeak</td>
    <td>ST depression induced by exercise relative to rest</td>
  </tr>
  <tr>
    <td>slope</td>
    <td>Slope of the peak exercise ST segment</td>
  </tr>
  <tr>
    <td>ca</td>
    <td>Number of major vessels (0-3) colored by fluoroscopy</td>
  </tr>
  <tr>
    <td>thal</td>
    <td>3 = normal; 6 = fixed defect; 7 = reversible defect</td>
  </tr>
  <tr>
    <td>Target</td>
    <td>1 or 0</td>
  </tr>
</table>

<h2>Task to be performed:</h2>

<h3>1. Preliminary analysis:</h3>
<p>a. Perform preliminary data inspection and report the findings on the structure of the data, missing values, duplicates, etc.<br>
b. Based on these findings, remove duplicates (if any) and treat missing values using an appropriate strategy.</p>

<h3>2. Report about the data:</h3>
<p>a

. Get a preliminary statistical summary of the data and explore the measures of central tendencies and spread of the data.<br>
b. Identify the data variables which are categorical and describe and explore these variables using the appropriate tools, such as count plot.<br>
c. Study the occurrence of CVD across the Age category.<br>
d. Study the composition of all patients with respect to the Sex category.<br>
e. Study if one can detect heart attacks based on anomalies in the resting blood pressure (trestbps) of a patient.<br>
f. Describe the relationship between cholesterol levels and the target variable.<br>
g. State what relationship exists between peak exercising and the occurrence of a heart attack.<br>
h. Check if thalassemia is a major cause of CVD.<br>
i. List how the other factors determine the occurrence of CVD.<br>
j. Use a pair plot to understand the relationship between all the given variables.</p>

<h3>3. Build a baseline model:</h3>
<p>Build a logistic regression and random forest model to predict the risk of a heart attack. Explore the results using correlation analysis and logistic regression for feature selection, leveraging standard error and p-values.</p>

<div class="section">
      <h2 class="section-heading">Please click <a href="https://notebooksharing.space/view/ef4292491a916cbbe125f2d9c0322319417c3faad0fc3254d51550f0ee2c9302#displayOptions=">here</a> for the project.</h2>
    </div>

</body>
</html>
