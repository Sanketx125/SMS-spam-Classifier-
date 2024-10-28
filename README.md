📧 SMS and Email Spam Classifier
Welcome to the SMS and Email Spam Classifier! This project leverages machine learning to distinguish between spam and non-spam messages/emails, ensuring your inbox stays clean and organized.

🚀 Overview
This project features a machine learning model trained to detect spam in both SMS and email messages. The accompanying interactive web application allows users to simply paste their message/email into the input box and click the "Predict" button to instantly see if it's spam or not.

📸 Interactive Web Page

![image](https://github.com/user-attachments/assets/c212f687-7ffd-447e-bad1-a0e6f3f449b3)


✨ Features
Accurate Spam Detection: Utilizes a well-trained machine learning model for high accuracy.

Dual Functionality: Works seamlessly with both SMS and email messages.

User-Friendly Interface: Easy to use web application for quick predictions.

Real-Time Processing: Get instant results with just a single click.

📜 How to Use
Clone the Repository:

sh

Copy
git clone https: https://github.com/Sanketx125/SMS-spam-Classifier-.git
cd spam-classifier
Install Dependencies:

sh

Copy
pip install -r requirements.txt
Run the Application:

sh

Copy
streamlit run app.py
Use the Web Interface:

Paste the received message/email into the input box.

Click the "Predict" button.

See if the message is spam or not.

🧠 Model Details
Model Type: Machine Learning Classifier

Algorithm: Naive Bayes (Multinomial Naive Bayes)

Training Data: Dataset of SMS and email messages labeled as spam or not spam.

📂 Project Structure

Copy
├── app.py                 # Main application file 
├── model.pkl              # Trained machine learning model
├── vectorizer.pkl         # TF-IDF Vectorizer
├── requirements.txt       # List of dependencies
├── text_transformer.py    # Text transformation functions
├── README.md              # Project description and usage guide
├── spam-detection.ipynb   # Machine Leanrning model
├── spam.csv               # dataset


🤝 Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to create a pull request or open an issue.
