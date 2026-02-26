# deep-learning-Based-Contactless-Vital-Signs-Monitoring-Using-mmWave-Radar-

1.	Overview
This project develops an AI-based contactless vital signs (Heart rate and Breathing rate) monitoring system designed to estimate breathing and heart rates using mmWave radar signals, without requiring wearable sensors. The work addresses a key challenge in real-world health monitoring: signal noise and motion interference that reduce reliability, especially in clinical and low-resource environments. To overcome this, multiple signal processing and deep learning–based denoising approaches were explored to improve signal quality and prediction accuracy. In here, I only included the deep learning approach, as it outperformed the former methods. NB: The uploaded code represents the final algorithmic pipeline; however, it does not replicate the exact results reported due to differences in the original training configuration
2.	Objective
The goal of this project is to enable reliable, scalable, and cost-efficient non-invasive health monitoring by extracting physiological signals from noisy radar data and accurately predicting vital signs.
3.	Methodology
Programming Language: Python Signal processing and denoising techniques Biomedical signal analysis Deep learning models (CNN, BiLSTM, Attention architectures) Time-series modeling Model evaluation using quantitative metrics (MAE, RMSE, Huber loss)
4.	Dataset
The dataset we used in this project can be found here: E. Sadeghi, A. Chiumento, and P. Havinga, “mm-wave fmcw radar vital sign monitoring dataset: Diverse physiological scenarios,” 4TU.ResearchData (2024).
https://data.4tu.nl/datasets/48acba04-96bc-4131-b52f-9e18458ad92b/1
