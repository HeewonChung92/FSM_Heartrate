# FSM_Heartrate

Paper :

Finite State Machine Framework for Instantaneous Heart Rate Validation using Wearable Photoplethysmography During Intensive Exercise


Abstract :

Accurate estimation of heart rate (HR) using reflectance-type photoplethysmographic (PPG) signals during intensive physical exercise is challenging because of very low signal-to-noise ratio (SNR) and unpredictable motion artifacts (MAs), which are frequently uncorrelated with reference signals such as accelerometer signals. In this paper, we propose a finite state machine (FSM) framework based novel algorithm for HR estimation and validation, which exploits the crest factor from the periodogram obtained after MA removal, and the estimated HR changes in consecutive windows as the estimation accuracy indicators. Our proposed algorithm automatically provides only accurate HR estimation results in a real-time by ignoring the estimation results when true HRs are not reflected in PPG signals or when the MAs uncorrelated with accelerometer signals are dominant. The performance of the HR estimation is rigorously compared with existing algorithms on the publically available database of 23 PPG recordings measured during intensive physical exercise. Our algorithm exhibits an average absolute error of 0.99 bpm and an average relative error of 0.88%. The algorithm is simple; the computational time is  1.2 ms for 8s-window. Also, the algorithm framework can be combined with existing methods to improve estimation accuracy.
