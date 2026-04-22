# api-avengers
📊 Datasets Used
Crop recommendation dataset - kaggle
Indian Crop Production & Prices Dataset
Agmarknet API (market prices)
🌐 APIs Used
OpenWeather API → https://openweathermap.org/api
Hugging Face (Translation) → Helsinki-NLP/opus-mt-en-hi
📌 Features
Smart crop recommendations (soil, rainfall, and demand-based)
Expected yield & market value prediction
Rainfall forecasting with climate fit
Risk factor
Multi-language support (English, Kannada & Hindi)
Simple and mobile-friendly UI
🛠️ Tech Stack
Frontend: React + TailwindCSS
Backend: Flask (Python APIs), Node.js + Express.js
ML Models: Scikit-learn, Prophet, LightGBM, TensorFlow
Database: SQLite
APIs: OpenWeatherMap, Hugging Face
📂 Project Structure
FarmAI-Diversify/
│── frontend/              # React + Tailwind code
│── backend/               # Node.js + Express.js
│── ml-models/             # Python ML Models (Flask APIs)
│── datasets/              # CSV files (soil, rainfall, market prices)
│── README.md

⚡ How to Run Locally Clone the repository:

git clone https://github.com/YourUsername/FarmAI-Diversify.git
Navigate into the project:
cd FarmAI-Diversify
Run the Frontend (React):
cd frontend
npm install
npm start
Run the Backend (Node.js + Express):
cd backend
npm install
node app.js
Run the ML Services (Flask):
cd ml-models
pip install -r requirements.txt
python recommend.py
python forecast.py
👨‍💻 Authors

The API Avengers
