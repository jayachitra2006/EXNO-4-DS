# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
<img width="1103" height="398" alt="Screenshot 2026-08-19 140020" src="https://github.com/user-attachments/assets/25c093c7-018f-4669-b74c-816218c6d93b" />
<img width="645" height="195" alt="Screenshot 2026-08-19 140038" src="https://github.com/user-attachments/assets/ec430c4b-e555-4cad-aff8-d0c2f9329b4c" />
<img width="605" height="560" alt="Screenshot 2026-08-19 140105" src="https://github.com/user-attachments/assets/510c117b-279a-48c7-aa11-f6e7cdf64c78" />
<img width="715" height="146" alt="Screenshot 2026-08-19 140121" src="https://github.com/user-attachments/assets/7a610732-5181-41f6-888e-e9b955343843" />
<img width="782" height="343" alt="Screenshot 2026-08-19 140136" src="https://github.com/user-attachments/assets/e1961d3a-6286-4cab-9250-de7870e285fa" />
<img width="1055" height="550" alt="Screenshot 2026-08-19 140149" src="https://github.com/user-attachments/assets/a074a1ae-f1e6-437a-aea9-662407617053" />
<img width="815" height="555" alt="Screenshot 2026-08-19 140211" src="https://github.com/user-attachments/assets/0bdae38d-e8bd-45fe-a573-c345f64b644e" />
<img width="781" height="360" alt="Screenshot 2026-08-19 140225" src="https://github.com/user-attachments/assets/20dcdbd9-5880-42e0-9fd0-082292cac056" />
<img width="985" height="376" alt="Screenshot 2026-08-19 140245" src="https://github.com/user-attachments/assets/bff61f9d-6ce4-4366-9e54-54c4ec95ef56" />
<img width="795" height="361" alt="Screenshot 2026-08-19 140300" src="https://github.com/user-attachments/assets/eab42a16-b06f-4301-9664-6734a5f19d57" />
<img width="942" height="505" alt="Screenshot 2026-08-19 140317" src="https://github.com/user-attachments/assets/e34b3b50-8a5a-45a6-a36e-d0f70c3670bd" />
<img width="750" height="383" alt="Screenshot 2026-08-19 223053" src="https://github.com/user-attachments/assets/c3e466b4-3d4a-4278-8978-e889234957b3" />
<img width="1280" height="612" alt="Screenshot 2026-08-19 223108" src="https://github.com/user-attachments/assets/e2164b2c-7f6c-45dd-85f9-5ecdb3cf8e47" />
<img width="1086" height="603" alt="Screenshot 2026-08-19 223123" src="https://github.com/user-attachments/assets/0dc31728-d75b-4e1b-97ba-24fbe78276d0" />
<img width="956" height="742" alt="Screenshot 2026-08-19 223142" src="https://github.com/user-attachments/assets/ac7c7f67-2e4a-4c51-886b-d06a780a0d53" />
<img width="1212" height="657" alt="Screenshot 2026-08-19 223202" src="https://github.com/user-attachments/assets/e61b1662-af22-44d3-9081-e0830f21816a" />
<img width="1027" height="585" alt="Screenshot 2026-08-19 223218" src="https://github.com/user-attachments/assets/2624f38a-bd12-464f-9023-67164b2e3b64" />
<img width="825" height="322" alt="Screenshot 2026-08-19 223236" src="https://github.com/user-attachments/assets/d3d5c1bc-4c47-4206-9ca3-a1085a80520d" />
<img width="1172" height="447" alt="Screenshot 2026-08-19 223302" src="https://github.com/user-attachments/assets/087c49b2-d630-42cb-9b79-748cc73f6994" />
<img width="890" height="152" alt="Screenshot 2026-08-19 223320" src="https://github.com/user-attachments/assets/358960e2-f2fb-44da-9f2b-61e781d0029e" />
<img width="1342" height="677" alt="Screenshot 2026-08-19 223337" src="https://github.com/user-attachments/assets/af578617-46c3-4ed6-ae89-da457b44c1fc" />
<img width="1312" height="757" alt="Screenshot 2026-08-19 223402" src="https://github.com/user-attachments/assets/37ab46a4-6ae4-4682-a74a-e4bd4d12b37e" />
<img width="817" height="282" alt="Screenshot 2026-08-19 223422" src="https://github.com/user-attachments/assets/ab9a99f4-a526-40a5-a17a-d289e751a760" />
<img width="1295" height="712" alt="Screenshot 2026-08-19 223442" src="https://github.com/user-attachments/assets/8ebf75e7-1c4d-45e9-9adf-3b08c1f82b6b" />
<img width="678" height="145" alt="Screenshot 2026-08-19 223506" src="https://github.com/user-attachments/assets/993be19f-eea0-4ec8-80de-15ad979bf6fc" />
<img width="407" height="218" alt="Screenshot 2026-08-19 223519" src="https://github.com/user-attachments/assets/8994c44f-7735-4da0-a599-ea3c1a6b656e" />

# RESULT:
Thus, Feature Scaling and Feature Selection were successfully performed on the given dataset and the processed data was saved to a file
