# Datasets for Machine Learning
---

Data sets are classified in different machine learning problems

### Anomaly Detection

<table>
    <thead>
      <tr>
        <th>Dataset</th>
        <th> No features</th>
        <th>No records</th>
        <th>Outliers</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
        <tr>
            <td>http</td>
            <td>3</td>
            <td><code>567497</code></td>
            <td><code>2211 (0.4 %)</code></td>
            <td><a href=https://www.kaggle.com>Download</a></td>
        </tr>
        <tr>
            <td>smtp</td>
            <td>3</td>
            <td><code>95156</code></td>
            <td><code>30 (0.03 %)</code></td>
            <td><a href=https://www.kaggle.com>Download</a></td>
        </tr>
        <tr>
            <td>annthyroid</td>
            <td>6</td>
            <td><code>6,832</code></td>
            <td><code>534 (7.42 %)</code></td>
            <td>Source <a href=https://archive.ics.uci.edu/ml/machine-learning-databases/thyroid-disease>UCI</a></td>
        </tr>
        <tr>
            <td>thyroid</td>
            <td>6</td>
            <td><code>3,772</code></td>
            <td><code>93 (2.5 %)</code></td>
            <td>Source <a href=https://archive.ics.uci.edu/ml/machine-learning-databases/thyroid-disease>UCI</a></td>
        </tr>
        <tr>
            <td>satelite</td>
            <td>36</td>
            <td><code>6,435</code></td>
            <td><code>2036 (32%)</code></td>
            <td>Source <a href=https://archive.ics.uci.edu/ml/datasets/Statlog+(Landsat+Satellite)>UCI</a></td>
        </tr>
        <tr>
            <td>pima</td>
            <td>8</td>
            <td><code>768</code></td>
            <td><code>268 (35%)</code></td>
            <td>Pima Indians Diabetes Database was provided by National Institute of Diabetes and Digestive and Kidney Diseases. <a href=https://www.openml.org/d/37>Download</a></td>
        </tr>
        <tr>
            <td>arrhythmia</td>
            <td>274</td>
            <td><code>452</code></td>
            <td><code>66 (15%)</code></td>
            <td>The aim is to determine the type of arrhythmia from the ECG recordings. Source <a href=https://archive.ics.uci.edu/ml/datasets/Arrhythmia>UCI</a></td>
        </tr>
    </tbody>
  </table>


### Fraud Detection


<table>
    <thead>
      <tr>
        <th>Dataset</th>
        <th> No features</th>
        <th>No records</th>
        <th>Outliers</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
        <tr>
            <td>Credit Card Fraud Detection</td>
            <td>31</td>
            <td><code>284,807</code></td>
            <td><code>492 (0.172%)</code></td>
            <td>The datasets contains transactions made by credit cards in September 2013 by european cardholders. The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group of ULB (Université Libre de Bruxelles). <a href=https://www.kaggle.com/mlg-ulb/creditcardfraud>Download</a></td>
        </tr>
        <tr>
             <td>IEEE-CIS Fraud Detection</td>
            <td>434</td>
            <td><code>569,877</code></td>
            <td><code>20,633 (3 %)</code></td>
            <td>The dataset is provided by Vesta's real-world e-commerce transactions. The data is broken into two files identity and transaction, which are joined by TransactionID. <a href=https://www.kaggle.com/c/ieee-fraud-detection/data>Download</a></td>
        </tr>
    </tbody>
  </table>




### Streaming data

<table>
    <thead>
      <tr>
        <th>Dataset</th>
        <th> No features</th>
        <th>No records</th>
        <th>Outliers</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
        <tr>
            <td>Mulcross</td>
            <td>4</td>
            <td><code>262,144</code></td>
            <td><code>2 dense clusters (10%)</code></td>
            <td>A synthetic multi-variate normal distribution with two dense anomaly clusters. <a href=https://www.openml.org/d/40897>Download</a></td>
        </tr>
        <tr>
            <td>Covertype</td>
            <td>10</td>
            <td><code>286,048</code></td>
            <td><code>0.9%</code></td>
            <td>Predicting forest cover type from cartographic variables only. Source <a href=https://archive.ics.uci.edu/ml/datasets/Covertype>UCI</a></td>
        </tr>
        <tr>
            <td>Adult</td>
            <td>6</td>
            <td><code>35,760</code></td>
            <td><code>class > 50k (3.21%)</code></td>
            <td>Prediction task is to determine whether a person makes over 50K a year. Source <a href=http://archive.ics.uci.edu/ml/datasets/Adult>UCI</a></td>
        </tr>
        <tr>
            <td>Weather</td>
            <td>8</td>
            <td><code>18,159</code></td>
            <td><code>rain (5,698 - 31%)</code></td>
            <td>The National Oceanic and Atmospheric Administration (NOAA) measured weather from over 7,000 weather stations worldwide. Records date back to the mid-1900's providing a wide scope of weather trends. Daily measurements include a variety of features (temperature, pressure, wind speed, etc.) as well as a series of indicators for precipitation and other weather-related events. Source <a href=https://www.ncdc.noaa.gov/cdo-web/datasets>NOAA</a></td>
        </tr>
        <tr>
            <td>Shuttle</td>
            <td>9</td>
            <td><code>49,097</code></td>
            <td><code>classes 2,3,5-7 (7%)</code></td>
            <td>The shuttle dataset contains 9 attributes all of which are numerical. Approximately 80% of the data belongs to class 1. Source <a href=https://archive.ics.uci.edu/ml/datasets/Statlog+(Shuttle)>UCI</a></td>
        </tr>
        <tr>
            <td>KDDCUP99</td>
            <td>41</td>
            <td><code>494,021</code></td>
            <td><code>23 classes</code></td>
            <td>Kddcup99 stream was collected from the KDD CUP challenge in 1999, and the task is to build predictive models capable of distinguishing between intrusions and normal connections. Source <a href=http://www.cse.fau.edu/~xqzhu/Stream/kddcup99.arff>KDD CUP challenge</a></td>
        </tr>
    </tbody>
  </table>


