# Parkinson-s-disease-detection-from-vocal-biomarker
Parkinson's is a neurodegenarative progressive disorder disease. It affects the nervous system and the part of the body controlled by it. Normally these brain cells produce dopamine and these dopamine operates in a delicate balance with other neurotransmitters to help cordinate the millions of nerve and muscle cell involved in the movement

The dataset used in this project is from Kaggle data bank. The dataset has 24 columns, thus we need to reduce the dimension before we train the data. The target or independent variable is "status" with binary values of 0 and 1. Status values for healthy person and PD person are 0 and 1 respectively. This is a classification probelm. The goal of this project is to develope the best machine learning model to predict the Parkinson's disease so that we can treat the patient in the timely manner. The following are the columns in the dataset.

*name* - ASCII subject name and recording number

*MDVP:Fo(Hz)* - Average vocal fundamental frequency

*MDVP:Fhi(Hz)* - Maximum vocal fundamental frequency

*MDVP:Flo(Hz)* - Minimum vocal fundamental frequency

*MDVP:Jitter(%)*,

*MDVP:Jitter(Abs)*,

*MDVP:RAP*,

*MDVP:PPQ*,

*Jitter:DDP* - Several measures of variation in fundamental frequency

*MDVP:Shimmer*,

*MDVP:Shimmer(dB)*,

*Shimmer:APQ3*,

*Shimmer:APQ5*,

*MDVP:APQ*,

*Shimmer:DDA -* Several measures of variation in amplitude

*NHR*,

*HNR -* Two measures of ratio of noise to tonal components in the voice

*status -* Health status of the subject (one) - Parkinson's, (zero) - healthy

*RPDE*, D2 -*</strong>Two nonlinear dynamical complexity measures

*DFA -* Signal fractal scaling exponent

*spread1,spread2,PPE -* Three nonlinear measures of fundamental frequency variation
