# Api security in large enterprises
Leveraging machine learning for anomaly detection

Official repository for the paper implementation of varMax published at the IEEE Military Communications Conference (IEEE MILCOM) held on 28 October – 1 November 2024 // Washington, DC, USA C5I Technologies for Military and Intelligence Operations Today and Tomorrow, under Track 5 - Machine Learning for Communications and Networking.
### Abstract
Large enterprises offer thousands of micro-services applications to support their daily business activities by using Application Programming Interfaces (APIs). These applications generate huge amounts of traffic via millions of API calls every day, which is difficult to analyze for detecting any potential abnormal behaviour and application outage. This phenomenon makes Machine Learning (ML) a natural choice to leverage and analyze the API traffic and obtain intelligent predictions. This paper proposes an ML-based technique to detect and classify API traffic based on specific features like bandwidth and number of requests per token. We employ a Support Vector Machine (SVM) as a binary classifier to classify the abnormal API traffic using its linear kernel. Due to the scarcity of the API dataset, we created a synthetic dataset inspired by the real-world API dataset. Then we used the Gaussian distribution outlier detection technique to create a training labeled dataset simulating real-world API logs data which we used to train the SVM classifier. Furthermore, to find a trade-off between accuracy and false positives, we aim at finding the optimal value of the error term (C) of the classifier. The proposed anomaly detection method can be used in a plug and play manner, and fits into the existing micro-service architecture with little adjustments in order to provide accurate results in a fast and reliable way. Our results demonstrate that the proposed method achieves an F1-score of 0.964 in detecting anomalies in API traffic with a 7.3% of false positives rate.
### Installation
```
$ git clone https://github.com/bayegaspard/varMax.git
$ cd varMax
$ pip install -r requirements.txt
```

<img 
 style="text-align: center;"
    src="https://github.com/user-attachments/assets/2b55908c-ccaf-465c-b5ef-3a10369fc2e8">

</img>


Cite
```
@inproceedings{baye2021api,
  title={Api security in large enterprises: Leveraging machine learning for anomaly detection},
  author={Baye, Gaspard and Hussain, Fatima and Oracevic, Alma and Hussain, Rasheed and Kazmi, SM Ahsan},
  booktitle={2021 international symposium on networks, computers and communications (ISNCC)},
  pages={1--6},
  year={2021},
  organization={IEEE}
}
```
### Acknowledgement
> This work has been funded by the Royal Bank of Canada and IU. Usual disclaimers apply.
