\# 🧠 Combatting Counterfeit Currency with AI-Powered Detection



This project is an AI-powered web application designed to detect \*\*fake vs real Indian currency notes\*\* using a deep-learning model (Xception CNN) and a clean Flask web interface.  

It combines \*\*Machine Learning\*\*, \*\*Computer Vision\*\*, and \*\*Full-Stack Web Development\*\* to deliver a fast and accurate counterfeit detection system.



---



\## 🔍 Project Overview



Counterfeit currency is a significant threat to the financial system.  

This project uses an \*\*Xception Convolutional Neural Network (CNN)\*\* trained on real and fake Indian currency notes to classify uploaded images as:



✔ \*\*Real\*\*  

✔ \*\*Fake\*\*



The trained model is integrated into a Flask app that processes user-uploaded images and returns predictions instantly.



---



\## ✨ Features



\### 🖼 Currency Classification  

Upload an image of a currency note → AI returns \*\*REAL\*\* or \*\*FAKE\*\*.



\### 👤 User System  

\- User Signup  

\- Login  

\- SQLite DB storage  

\- OTP verification (if enabled)



\### 🌐 Frontend  

\- Clean HTML/CSS interface  

\- Easy upload and prediction flow  

\- Fast response UI  



\### 🧠 Backend  

\- Flask REST endpoints  

\- Xception CNN model loading  

\- Image preprocessing with TensorFlow/Keras  



---



\## 🧪 Technologies Used



| Category | Technologies |

|---------|--------------|

| \*\*Programming Language\*\* | Python 3.10 |

| \*\*Web Framework\*\* | Flask |

| \*\*Deep Learning\*\* | TensorFlow 2.10, Keras 2.10 |

| \*\*Image Processing\*\* | Pillow, NumPy |

| \*\*Database\*\* | SQLite |

| \*\*Frontend\*\* | HTML5, CSS3 |

| \*\*Model Architecture\*\* | Xception CNN |



---



\## 📂 Project Structure



code\_folder/

│

├── app.py # Flask backend

├── requirements.txt # Dependency list

├── flowchart.txt # Project flow

├── Notebook.ipynb # Model training notebook

│

├── static/ # CSS, JS, images, uploads

│ ├── css/

│ ├── uploads/

│ └── js/

│

├── templates/ # HTML templates

│ ├── index.html

│ ├── login.html

│ ├── signup.html

│ ├── prediction.html

│ └── ...

│

└── .gitignore # Files to ignore



---



\## ⚙️ How to Run the Project Locally



\### 1️⃣ Clone the repository  

git clone https://github.com/<your-username>/<repo-name>.git



\### 2️⃣ Navigate to the project  

cd code\_folder



\### 3️⃣ Create \& activate virtual environment  

py -3.10 -m venv venv

venv\\Scripts\\activate



\### 4️⃣ Install dependencies  

pip install -r requirements.txt



\### 5️⃣ Run the Flask application  

python app.py



\### 6️⃣ Open the app in browser  

http://127.0.0.1:5000



---



\## 📸 Screenshots (Optional)



You may add screenshots by placing them inside:



static/screenshots/



arduino

Copy code



and embedding them like:



!\[Screenshot](static/screenshots/home.png)





🚀 Future Enhancements

Expand to multiple currency denominations



Real-time detection via webcam



Support for multiple global currencies



Mobile app version (Flutter/React Native)



Cloud deployment (AWS / Render / Railway)

