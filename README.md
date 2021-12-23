# ML
ANOMALY DETECTION

Problem statement:

The Problem Statement presented below highlights a method with which one can evaluate the severity of the anomaly by quantifying the magnitude of the anomalous point.
          
          
 Once a data point is identified as an anomaly, to quantify the magnitude of the anomalous point, a score between 0-100 is assigned to it. This provides the anomaly detection framework a way to measure and make educated decisions as a response to the anomalous event in the time series. As part of the evaluation metric for the candidate, the task is to devise an algorithm for scoring pre-identified anomalies in time series. To aid in development & testing of the algorithm, the following additional information had provided.

timestamp [float]: is provided as a Unix epoch in seconds.

value [int] is a real value measurement of some metric at the timestamp.

is_anomaly [ boolean]: is a boolean value which is True if the corresponding value is identified as an anomaly. If it is True, a score must be provided to the anomaly. If it is False, no score needs to be calculated for that timestamp.

predicted [ float]: is a real value prediction coming from a black box forecasting model for that timestamp. This black box forecasting model is assumed to be aware of only the true data distribution of the time series, and cannot predict anomalies. You may choose to use or not use predicted values.
