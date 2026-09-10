# Moustafa Ahmed

AI Engineer in Alexandria, Egypt, working in computer vision and deep learning, with a background in applied data science and statistical modelling.
B.Sc. Computing and Data Science, Alexandria University, 2025.

### [receipt-extraction](https://github.com/Moustafa29/receipt-extraction)

Structured field extraction from photographed receipts with LayoutLMv3 on CORD — **73.0 micro F1** on real OCR input.

- Only **64%** of CORD's annotated fields survive a realistic OCR pipeline.
- A baseline trained the standard way, on annotation boxes, scores **93.0 F1** on annotation input and **23.8** on real OCR input — same checkpoint.

### [Brain-Computer Interface for Smart Home Control](https://github.com/Moustafa29/Brain-Computer-Interface-for-Smart-Home-Control)

Hands-free control of doors, windows and a fan from single-channel EEG, built for people with motor impairments.

- CNN-BiLSTM blink classifier at **92%** accuracy, holding **88.4%** on recording sessions it never trained on.
- Attention and relaxation level classified at **92%** and **90%**.
- An ESP32 drives the servos and fan, with a keypad lock and gas and flame alarms; Flutter app in progress.

### [Sales Forecasting and Demand Prediction](https://github.com/Moustafa29/Sales-forecasting-and-demand-prediction)

Weekly sales forecasting across 45 Walmart stores — XGBoost at **$84K MAE**, plus a stacked-ensemble meta-model for demand classification at **97% accuracy**. Feature engineering over seasonality, holidays, lagged sales and economic indicators; deployed as a Streamlit app in Docker.

**Stack:** Python · SQL · pandas · NumPy · PyTorch · TensorFlow · Hugging Face Transformers · OpenCV · scikit-learn · XGBoost · Docker · Streamlit
