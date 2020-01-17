# Heartbeat-Sound-Anomalies-Detection
-------
* The objective of this project is to classify different category of heatbeat sound like i.e. 1) Artifact 2) Extrahls 3) Murmur 4) Normal using Deep learning.


#### Problem Statement:
-----
* According to the World Health Organisation, cardiovascular diseases (CVDs) are the number one cause of death globally: more people die annually from CVDs than from any other cause. An estimated 17.1 million people died from CVDs in 2004, representing 29% of all global deaths. Of these deaths, an estimated 7.2 million were due to coronary heart disease. Any method which can help to detect signs of heart disease could therefore have a significant impact on world health. This challenge is to produce methods to do exactly that. Specifically, we are interested in creating the first level of screening of cardiac pathologies both in a Hospital environment by a doctor (using a digital stethoscope) and at home by the patient (using a mobile device).

* The problem is of particular interest to machine learning researchers as it involves classification of audio sample data, where distinguishing between classes of interest is non-trivial. Data is gathered in real-world situations and frequently contains background noise of every conceivable type. The differences between heart sounds corresponding to different heart symptoms can also be extremely subtle and challenging to separate. Success in classifying this form of data requires extremely robust classifiers. Despite its medical significance, to date this is a relatively unexplored application for machine learning.

#### Dataset Overview:
----
* Data has been gathered from two sources: 
1. The general public via the iStethoscope Pro iPhone app, provided in Dataset A. 
2. A clinic trial in hospitals using the digital stethoscope DigiScope, provided in Dataset B.

* Source 1: http://www.peterjbentley.com/heartchallenge/#downloads
* Source 2: https://www.kaggle.com/kinguistics/heartbeat-sounds

#### Feature Extraction using MFCC:
-----
* MFCC values mimic human hearing and they are commonly used in speech recognition applications. The MFCC values will be fed directly into the neural network. For information on MFCC please check https://en.wikipedia.org/wiki/Mel-frequency_cepstrum

#### Data Visualization:
----
##### Murmur
-----
!['murmur'](https://github.com/ShehzadaAlam/Heartbeat-Sound-Anomalies-Detection/blob/master/Waveplot_with_MFCC1_Murmur_Heartbeat.PNG)

##### Normal
-----
!['Normal'](https://github.com/ShehzadaAlam/Heartbeat-Sound-Anomalies-Detection/blob/master/Waveplot_with_MFCC1_Normal_Heartbeat.PNG)

##### Extrahls
-----
!['Extrahl'](https://github.com/ShehzadaAlam/Heartbeat-Sound-Anomalies-Detection/blob/master/Waveplot_with_MFCC1_Extrahls_Heartbeat.PNG)

##### Artifact
-----
!['Arti'](https://github.com/ShehzadaAlam/Heartbeat-Sound-Anomalies-Detection/blob/master/Waveplot_with_MFCC1_Artifact_Heartbeat.PNG)


#### Model Building:
----
Model | Accuracy Score
----- | ----- 
BiLSTM | 84 % 
CNN Model | 76 % 


----
<p>Thank You!	
<p><!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/ShehzadaAlam" aria-label="Follow @ShehzadaAlam on GitHub">Follow @ShehzadaAlam</a>



