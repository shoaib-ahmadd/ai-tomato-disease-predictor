# 🍅 Tomato Leaf Disease Prediction

A simple and responsive frontend web application for **Tomato Leaf Disease Prediction** built using **HTML, CSS, and JavaScript**.  
This interface allows users to upload a tomato leaf image, send it to the backend model API, and view the predicted disease result with confidence score.

---

## 📌 Overview

This project is the frontend part of a Tomato Leaf Disease Prediction system.  
It is designed to work with a backend deep learning model that uses a **4-branch hybrid CNN architecture**:

- **ResNet**
- **DenseNet**
- **MobileNet**
- **Custom CNN**

The frontend provides a clean user interface for interacting with the model.

---

## 🚀 Features

- Upload tomato leaf images from local device
- Preview selected image before prediction
- Send image to backend API using JavaScript `fetch()`
- Display predicted disease class
- Display confidence score
- Clean and responsive UI
- Beginner-friendly and easy to integrate with Flask/FastAPI backend

---

## 🛠️ Tech Stack

- **HTML5** – structure
- **CSS3** – styling
- **JavaScript** – client-side logic
- **Backend API** – Flask / FastAPI
- **Model** – Hybrid CNN for tomato leaf disease prediction

---

## 📂 Project Structure

```bash
tomato-leaf-disease-prediction-frontend/
│
├── index.html          # Main frontend page
├── style.css           # Application styling
├── script.js           # Frontend logic and API calls
├── assets/             # Images, icons, screenshots
└── README.md           # Project documentation


▶️ Getting Started
1. Clone the repository
git clone https://github.com/your-username/tomato-leaf-disease-prediction-frontend.git
2. Open the project folder
cd tomato-leaf-disease-prediction-frontend
3. Run the frontend

You can directly open index.html in the browser
or use VS Code Live Server for a better local development experience.

📡 Example API Integration

Inside script.js, the API call may look like this:

const apiUrl = "http://127.0.0.1:5000/predict";

If you deploy the backend, replace it with your hosted API URL:

const apiUrl = "https://your-backend-url.com/predict";
🧪 Expected Output

After uploading an image, the frontend should display:

Predicted Disease

Confidence Score

Uploaded Image Preview

Example:

Prediction: Early Blight
Confidence: 96.42%
🎯 Use Cases

Plant disease detection demo

AI-based agriculture projects

ML model frontend integration

Academic and portfolio projects

End-to-end deep learning deployment showcase

🔮 Future Improvements

Drag-and-drop image upload

Disease details and remedy suggestions

Loading spinner during prediction

Better error handling

Mobile-first UI enhancements

Multi-language support

Dark mode

📸 Screenshot

Add your frontend screenshot inside the assets folder and reference it here:

![App Screenshot](assets/screenshot.png)
👨‍💻 Author

Aman
Machine Learning Engineer | Full-Stack Developer

📜 License

This project is licensed under the MIT License.

🤝 Contribution

Contributions, suggestions, and improvements are welcome.
Feel free to fork the repository and submit a pull request.

⭐ Support

If you found this project useful, consider giving it a star on GitHub.


Here is a **shorter GitHub-style version** too, if you want a cleaner README:

```md
# Tomato Leaf Disease Prediction Frontend

Frontend web application for Tomato Leaf Disease Prediction built with HTML, CSS, and JavaScript.  
It allows users to upload tomato leaf images, send them to a backend deep learning API, and view predicted disease results with confidence scores.

## Tech Stack
- HTML
- CSS
- JavaScript
- Flask/FastAPI backend API

## Features
- Image upload
- Image preview
- API integration
- Prediction display
- Responsive UI

## Project Structure
```bash
├── index.html
├── style.css
├── script.js
├── assets/
└── README.md
Run

Open index.html in your browser or run with Live Server.

Backend Endpoint

Update API URL in script.js:

const apiUrl = "http://127.0.0.1:5000/predict";
Author : RAFIQ


For your project, I’d recommend the **first README**, because it looks more professional on GitHub.

I can also prepare the matching `index.html`, `style.css`, and `script.js` structure for this frontend.
