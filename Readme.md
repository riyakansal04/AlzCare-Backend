# AlzCare Backend

AlzCare is a **smart assistance system for Alzheimer’s patients**, designed to monitor daily activities, detect abnormal patterns, and notify caregivers in real-time. This backend repository handles activity recognition, alert generation, and integration with the frontend app.

---

## **Project Overview**

AlzCare leverages advanced **machine learning and deep learning models** to track patient activities and ensure safety:

- **CNN-LSTM**: A hybrid deep learning approach combining **Convolutional Neural Networks (CNN)** and **Long Short-Term Memory (LSTM)** networks. Ideal for recognizing complex activities like walking, sitting, headache, heart stroke, coughing, backpain or falling.  
  - Accuracy: **80%**
  - Provides the best results for sequential activities due to hybrid modeling.  

- **Random Forest (RF)**: Traditional machine learning model for activity classification.  
  - Accuracy: **79%**

- **CNN**: Pure deep learning model for image/frame-based activity recognition.  
  - Accuracy: **81%**

> Although CNN has slightly higher raw accuracy, the **CNN-LSTM hybrid approach** is more effective for real-world activity tracking, especially for sequential or temporal activities like walking or transitions between activities.

---

## **Key Features**

- **Real-Time Abnormal Activity Detection:** Monitors Alzheimer’s patients’ daily activities using video frames and sensor data.  
- **Alert System:** Automatically sends alerts to caregivers via **SMS** and **Email** in case of abnormal activities.  
- **Multi-Model Support:** Supports Random Forest, CNN, and CNN-LSTM for activity recognition.  
- **Easy Integration:** Works seamlessly with the frontend Flutter app to provide real-time notifications and reports.  
- **Dataset & Pre-Trained Models:** Pre-trained models and dataset are included in a large ZIP file for easy setup.

---

## **Backend ZIP File**

The backend contains all necessary pre-trained models, scripts, and data. You can download the ZIP file from Google Drive:

[Download Backend ZIP](https://drive.google.com/uc?export=download&id=1Ynp6ugQhgM3cJMr588PfFNEsXckapsPP)

---

## **Installation & Setup**

1. Clone this repository:
   ```bash
   git clone <backend-repo-url>
   cd AlzCare-backend

2. Extract the ZIP file (downloaded from Google Drive) into the project directory.

3. Install required Python packages:
    ```bash
    pip install -r requirements.txt


4. Run the backend server:
    ```bash
    python app.py
    
Ensure you have configured email/SMS credentials for alerts.

---

## Contributing

We welcome contributions to improve AlzCare’s backend, including:

- Enhancing activity recognition models
- Optimizing alert delivery
- Adding new features for caregiver support

Please create a pull request or open an issue for collaboration.

---

## Contact

For questions, suggestions, or support:

- **Developer Email:** your-email@example.com
- **Project GitHub:** AlzCare

---

## Acknowledgements

- **Deep Learning models:** CNN, LSTM
- **Machine Learning:** Random Forest
- **SMS & Email integration libraries**

AlzCare ensures safety, support, and peace of mind for Alzheimer’s patients and their caregivers by combining cutting-edge AI with user-friendly mobile integration.

**Team AlzCare** | Authors: **Riya Kansal**  [LinkedIn](https://www.linkedin.com/in/riya-kansal-963042268/) • [GitHub](https://github.com/riyakansal04)

– Committed to enhancing safety and care for Alzheimer’s patients.


