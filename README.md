# IoT-Anomaly-covariate-shifted-and-point-time-series-health-data


Paper link: https://www.sciencedirect.com/science/article/pii/S1319157821003281

Abrupt distributional covariate shift and abnormal data points can cause anomaly in the time series dataset. Such issue can exaggerate in the internet of things (IoT)-based scenario where continuous data is generated from the low-cost health sensors. Existing anomaly detection techniques mostly rely on the machine learning aware strategies resulting processing and storage overhead in the IoT-based tool chain. In this paper, we perform two experiments on anomaly detection on univarite data such as, (i) anomaly detection of online covariate shift i.e. IoTSAnom method and (ii) seasonal-decomposition by the Loess i.e. STL and piecewise median schemes i.e. IoTSDA method. Firstly, we propose the IoTSAnom architecture to detect online coviarte shift in the univariate time series pulse rate data stream. We implement the ”IRKernel” to investigate the efficiency of exponentially weighted moving average (EWMA)-based light-weight statistical learning by using three variants e.g. probabilistic (P), shift-detect (SD), and two-stage shift-detect (TS-SD) over the EWMA algorithms. We perform evaluation of execution time of the algorithms in classical, incremental, and optimized modes while following the Kolmogorov–Smirnov hypothesis testing at the two-stage anomaly detection. Secondly, the IoTSDA scheme is implemented to support an instantaneous anomaly detection based on the interquartile range and generalized extreme studentized deviate statistics. Both the experimental results show that use of probability, shift-detection scheme, and time-series seasonal-decomposition can detect anomalies. Both the schemes can leverage the IoT-edge analytics for smart health care anomaly detection.

![Untitled](https://user-images.githubusercontent.com/1689639/162997045-0437cc82-6588-4c51-a08e-e92a64c1cf78.png)

![Untitled](https://user-images.githubusercontent.com/1689639/162997131-8b8568b7-c12d-4365-a5eb-f3b2197ff42a.png)

![Untitled](https://user-images.githubusercontent.com/1689639/162997232-ddb4d556-8809-4743-97e2-d1ee1e5956fc.png)

