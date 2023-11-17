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

Link to the dataset:https://www.kaggle.com/datasets/joebeachcapital/harth-dataset

[Ref article:HARTH: A Human Activity Recognition Dataset for Machine Learning

By Aleksej Logacjov, Kerstin Bach, Atle Kongsvold, H. Bårdstu, P. Mork. 2021]


The primary goal is to optimize the code and find data points in the .csv files where the correlation matrix and spectrogram can be plotted to find out the different related variables and 
the categorical features. After that, it is implemented into the training data where a dual attention-based deep learning model is used
[DARNN-net-based encoder and decoder model]. As the data is not scaled and presented properly, it is subjected to EDA and other dual attention-based deep learning methods and models(LSTM, time warping, ANN, etc)in the meantime.
The next phase will be the use and implementation of a vision-based transformer model(ViT) to predict class labels text-based and for better accuracy. It will be also used for image classification and image recognition purposes in many sectors.

This has numerous applications and innovations in the Construction on-site project management industry for effectively tracking and 
predicting workforce behavior to boost the efficiency and safety of the workers on-site. We discussed and developed a similar solution canvas model for efficient tracking and real-time monitoring purposes of the construction workers for the Smart India Hackathon(SIH 2023), where we came second and for Google's Build For Bharat Hackathon. Exploratory analysis and review based on the solutions are being made complying with the prevalent problem statement and the prevalent business model.
Problem Statement and Goal:
The construction industry is one of the biggest industries and part of the key economy of our country. To undertake projects of megascale 
this industry undertakes large workforces and safety protocols should be maintained in an orderly manner. However, due to a lack of technological advancements and infrastructural development, safety efficiency and quality management are often compromised. Unstable working surfaces, poor maintenance, and lack of proper protection and equipment add roughly 24.20% fatality rate and a markup loss of over USD 80,000 crores, stalling the growth forecast. So, the goal is to develop an interactive platform to enhance real-time monitoring onsite, to aggravate the safety and  efficiency of workers to bolster a staggering growth in the construction industry.

Objectives Analysis:
Objectives:
1.B2B transactions in construction projects enhance e-commerce management services engagement as a primary marketing and retail platform.
2. Real-time monitoring of the dashboard increases payload and transaction tracking and also magnifies quality management with upgradation
of inventory optimization.
3. Data obtained from the e-commerce platform helps keep track of redundant user behavior and activities of workers and also helps in managing
a construction project securely and efficiently.
4. Construction companies can utilize e-commerce platforms to market their services and products to a broader audience, which in turn increases
profitability. They can showcase their project reports, portfolio, and expertise online, attracting potential clients and partners.
5. Management services platforms generally have expertise in performing exploratory data analysis. Construction managers can use this data to make informed decisions, optimize operations, and identify trends in the industry, amplifying efficiency and output of work from construction 
employees.
6. Effective facility management and maintenance improves construction workflows and improves intercommunication between different workers 
of different sectors in the project.
7. Mobility solutions have the power to boost productivity, in terms of the construction industry sector, infrastructure and site safety evaluation, and enhancement of procurement statistics in terms of transportation of raw materials needed.

Link to the repo where Construction Project Management Data Analysis and the Optimization is done:
https://github.com/DodoIsADud/Construction-Project-Management-and-Report-Data-Analysis




