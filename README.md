📄 Concrete Crack Detection using Sensor Data & Machine Learning
📌 Project Overview
This project focuses on detecting and analyzing cracks in concrete structures using piezoelectric sensor conductance data and machine learning techniques.
Experimental data collected from OPC, PPC, FRC, and conventional concrete specimens under varying conditions is used to identify crack initiation and progression.
The system processes raw impedance/conductance measurements, applies preprocessing and feature scaling, and builds ML/DL models to detect crack presence and severity.

🎯 Problem Statement
Structural cracks in concrete reduce durability and safety.
Traditional inspection methods are:


Manual


Time-consuming


Subjective


This project aims to automate crack detection using sensor-driven data and ML, enabling early damage identification and condition monitoring.

🧠 Solution Approach
1️⃣ Data Collection


Conductance and impedance data collected using piezoelectric sensors


Experiments performed on:
OPC concrete


PPC concrete


FRC concrete


General concrete samples




Measurements recorded under controlled conditions



2️⃣ Data Preprocessing


Cleaning raw sensor signals


Feature scaling and normalization


Handling noise and inconsistencies


Preparing datasets for ML/DL models



3️⃣ Feature Engineering


Extract conductance-based indicators


Identify patterns related to crack formation


Create structured input features



4️⃣ Model Development


Machine Learning / Deep Learning models


Crack detection as:


Classification (crack / no crack, crack severity)


Regression (crack strength / damage level)




Evaluation across different concrete types



5️⃣ Analysis & Validation


Compare behavior across OPC, PPC and FRC samples


Analyze conductance variation vs crack presence


Validate consistency of sensor-based detection



🛠️ Tech Stack


Programming Language: Python


Data Processing: Pandas, NumPy


ML / DL: Scikit-learn, Neural Networks


Visualization: Matplotlib, Seaborn


Data Format: Excel (.xlsx)


Environment: Jupyter Notebook



📂 Project Structure
Concrete-Crack-Detection/
│
├── Untitled0.ipynb
├── Untitled1.ipynb
├── Untitled2.ipynb
├── Untitled32.ipynb
│
├── CRACK DETECTION TRAIL FEB 2025.xlsx
├── FRC CRACK DETECTION 2025.xlsx
├── PPC CRACK DETECTION 2025.xlsx
│
├── FRC_conductance_data.xlsx
├── conductance_data_scaled_1_2.xlsx
├── PPC_conductance_data_scaled.xlsx
│
└── README.md


📊 Output


Crack detection results based on sensor conductance


Comparative analysis across concrete types


Scaled datasets for ML modeling


Validated crack indicators



✅ Key Highlights


Real civil + ML interdisciplinary project


Sensor-based structural health monitoring


Supports both classification & regression


Experimental + data-driven approach


Suitable for research & applied ML roles



📌 Project Status
Completed ✅


👨💻 Author
Nikhil Sai
B.Tech – Electronics and Computer Engineering
Machine Learning | Structural Health Monitoring | Sensors

🔮 Future Enhancements


Deep learning models (LSTM / Autoencoders)


Temperature-aware crack prediction


Real-time monitoring system


Deployment as SHM dashboard
