### Anomaly Detection in Predictive maintenance
This example shows a demonstration of collecting the physical health aspects of a specific machine and analyzing these information by ML algorithms for early fault detection, health assessment and prediction of this machine.
In this example, we use bearing data provided by Case Western Reserve University (CWRU) Bearing Data Center (http://csegroups.case.edu/bearingdatacenter/home)

### Method
In this repo, we used Variational Autoencoder (VAE) for anomaly detection. The reconstruction error of training data is used as anomaly threshold to detect different anomalies of bearing.
In Data folder, bearing data in .mat is processed and then fed into VAE model in VAE folder.
