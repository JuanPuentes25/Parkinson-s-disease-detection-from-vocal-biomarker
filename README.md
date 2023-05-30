# Parkinson-s-disease-detection-from-vocal-biomarker
Parkinson's is a neurodegenarative progressive disorder disease. It affects the nervous system and the part of the body controlled by it. Normally these brain cells produce dopamine and these dopamine operates in a delicate balance with other neurotransmitters to help cordinate the millions of nerve and muscle cell involved in the movement

Vocal biomarkers
The human voice is a rich medium that is used extensively in interpersonal communication. It is one of the most natural and energy-efficient modes of communication. The voice, as complex arrays of sound emanating from our vocal chords, has a plethora of data and is essential for social interaction because it enables us to communicate insights about our emotions, anxieties, sentiments, and stimulation through modulation of its tone or pitch.

A biomarker is a factor that can be objectively measured and evaluated to represent a biological or pathogenic process, or a pharmacological response to a therapeutic intervention, and can be used as a surrogate marker of a clinical endpoint. A vocal biomarker is a signature, feature, or combination of features from the audio signal of the voice that is associated with a clinical outcome and can be used to monitor patients, diagnose a condition, or grade the severity or stages of a disease, or for drug development.

Extracting Audio Feature
Prior to data analysis, it is necessary to convert the audio signal to "features," which are the signal's most prominent and discriminating qualities that will subsequently be used to train machine learning algorithms. Numerous approaches for deriving acoustic features from temporal, frequency, cepstral, wavelet, and time-frequency domains have been proposed in many literatures.

Prosodic - pitch, formants, energy, jitter, and shimmer
Spectral characteristics - spectral flux, slope, centroid, entropy, roll-off, and flatness
Voice quality - zero-crossing rate, harmonic-to-noise ratio, noise-to-harmonic ratio
Phonation - fundamental frequency, pitch period entropy) parameters can all be extracted and analysed
The appropriate selection of attributes is highly dependent on the type of voice issue, condition, and recording method. For instance, while acoustic features extracted from sustained vowel phonations or diadochokinetic recordings are frequently used to detect Parkinson's disease, linguistic features extracted from spontaneous or semi-spontaneous speech may be a better choice for estimating Alzheimer's disease or mental health disorders.

The dataset used in this project is from Kaggle data bank. The dataset has 24 columns, thus we need to reduce the dimension before we train the data. The target or independent variable is "status" with binary values of 0 and 1. Status values for healthy person and PD person are 0 and 1 respectively. This is a classification probelm. The goal of this project is to develope the best machine learning model to predict the Parkinson's disease so that we can treat the patient in the timely manner. The following are the columns in the dataset.

Attribute Information¶ 

name - ASCII subject name and recording number

MDVP:Fo(Hz) - Average vocal fundamental frequency

MDVP:Fhi(Hz) - Maximum vocal fundamental frequency

MDVP:Flo(Hz) - Minimum vocal fundamental frequency

MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP - Several measures of variation in fundamental frequency

MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude

NHR, HNR - Two measures of the ratio of noise to tonal components in the voice

status - The health status of the subject (one) - Parkinson's, (zero) - healthy

RPDE, D2 - Two nonlinear dynamical complexity measures

DFA - Signal fractal scaling exponent

spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation
