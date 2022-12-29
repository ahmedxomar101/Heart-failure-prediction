# Heart-failure-prediction
As part of my work for the Big Data and Official Statistics course, I surpassed the performance of the paper published by the authors by 3% on Accuracy and 5.3% on F1 just by doing Features Engineering!

## Introduction
![image](https://user-images.githubusercontent.com/44009418/209995503-9bd7d091-9f68-49e6-9c2a-ffb54d72ac3f.png)

## Background
* Cardiovascular diseases kill approximately 17 million people globally every year, and they mainly exhibit as myocardial infarctions and heart failures. 
* **Heart failure** (HF) occurs when the heart cannot pump enough blood to meet the needs of the body.
Available electronic medical records of patients quantify symptoms, body features, and clinical laboratory test values, which can be used to perform biostatistics analysis aimed at highlighting patterns and correlations otherwise undetectable by medical doctors. 
* Machine learning, in particular, can predict patients’ survival from their data and can individuate the most important features among those included in their medical records.

## Methods
* In this project and paper, I analyzed a dataset of 299 patients with heart failure. 
* I applied several machine learning classifiers (6) to both predict the patients survival, and rank the features corresponding to the most important risk factors. 
* Since both feature ranking approaches clearly identify that the time attribute (and other two features that I engineered from the time attribute), as well as serum creatinine and ejection fraction attributes as the most relevant features, I then built the machine learning survival prediction models on these factors alone.

## Results
The results of these five-feature models show 
* not only that time, serum creatinine and ejection fraction are sufficient to predict survival of heart failure patients from medical records, 
* but also that using these features alone can lead to more accurate predictions than using the original dataset features in its entirety. 

## Analysis
### 1.1. Dataset: Overview
![image](https://user-images.githubusercontent.com/44009418/209996221-506dfcb3-d509-4c31-afb5-925ef7a6a62c.png)

### 1.2. Dataset: Feature Engineering
![image](https://user-images.githubusercontent.com/44009418/209996230-934c18f3-0885-4ed7-bc9c-8cb7a7d3a8f7.png)

### 2. Methods
![image](https://user-images.githubusercontent.com/44009418/209995932-bc0f93df-887e-49fb-b382-82e057034529.png)

### 3. Features Ranking
![image](https://user-images.githubusercontent.com/44009418/209995988-21903127-4fc6-4227-9210-dea2636bb16f.png)

### 4. Metrics
![image](https://user-images.githubusercontent.com/44009418/209996063-9b98de5b-7d69-4d59-9bf0-f056c0f3be4a.png)

## Conclusions
* This discovery has the potential to impact on clinical practice, becoming a new supporting tool for physicians when predicting if a heart failure patient will survive or not. 
* Indeed, medical doctors aiming at understanding if a patient will survive after heart failure may focus mainly on serum creatinine and ejection fraction.
* As a limitation of the present study, we have to report the small size of the dataset (299 patients): a larger dataset would have permitted to obtain more reliable results.
* Additional information about the physical features of the patients (height, weight, body mass index, etc.) and their occupational history would have been useful to detect additional risk factors for cardiovascular health diseases.

## References
* Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone – Davide Chicco, Giuseppe Jurman.
* Treatment of heart failure with preserved ejection fraction. reflections on its treatment with an aldosterone antagonist – Pfeffer MA, Braunwald E.
* Machine learning for prediction of sudden cardiac death in heart failure patients with low left ventricular ejection fraction: study protocol for a retroprospective multicentre registry in China – Meng F, Zhang Z, Hou X.
* Targets for heart failure with preserved ejection fraction – Nanayakkara S, Kaye DM.
