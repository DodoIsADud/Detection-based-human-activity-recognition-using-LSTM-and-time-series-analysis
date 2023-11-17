# Pedestrian-detection-and-human-activity-recognition-using-LSTM-and-time-series-data
Detecting human action recognition system using LSTM, TDNN, and other time-series predictive data analysis by plotting the
heatmap and the correlation data of converted binary array metrics data of the sensor used(Accelerometer, Gyroscope, etc.) in various applications like pedestrian detection, construction project risk management, and other civil-based applications.


The Human Activity Recognition Trondheim (HARTH) dataset is a professionally annotated dataset containing 22 subjects wearing two 3-axial accelerometers for around 2 hours in a free-living setting. The sensors were attached to the right thigh and lower back. The professional recordings and annotations provide a promising benchmark dataset for researchers to develop innovative machine-learning approaches for precise HAR in free living.
The HARTH dataset contains recordings of 22 participants wearing two 3-axial Axivity AX3 accelerometers for around 2 hours in a free-living setting. One sensor was attached to the right front thigh and the other to the lower back. The provided sampling rate is 50Hz. Video recordings of a chest-mounted camera were used to annotate the performed activities frame-by-frame.

Each subject's recordings are provided in a separate .csv file. One such .csv file contains the following columns:

timestamp: date and time of recorded sample
back_x: acceleration of back sensor in the x-direction (down) in the unit g
back_y: acceleration of back sensor in y-direction (left) in the unit g
back_z: acceleration of back sensor in z-direction (forward) in the unit g
thigh_x: acceleration of thigh sensor in the x-direction (down) in the unit g
thigh_y: acceleration of thigh sensor in y-direction (right) in the unit g
thigh_z: acceleration of thigh sensor in the z-direction (backward) in the unit g
label: annotated activity code
The dataset contains the following annotated activities with the corresponding coding:
1: Walking
2: Running
3: shuffling
4: stairs (ascending)
5: stairs (descending)
6: Standing
7: sitting
8: lying
13: Cycling (sit)
14: Cycling (stand)
130: Cycling (sit, inactive)
140: Cycling (stand, inactive)

[Ref article:HARTH: A Human Activity Recognition Dataset for Machine Learning

By Aleksej Logacjov, Kerstin Bach, Atle Kongsvold, H. Bårdstu, P. Mork. 2021]


The primary goal is to optimize the code and find data points in the .csv files where the correlation matrix and spectrogram can be plotted to find out the different related variables and 
the categorical features. After that, it is implemented into the training data where a dual attention-based deep learning model is used.
