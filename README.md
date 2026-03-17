# Emotion Detection Application

## 📌 Project Title

Emotion Detection using Watson NLP

---

## 📖 Description

This project is part of the **Emotion Detection** course. It demonstrates how to build an application that detects emotions from text using IBM Watson NLP services.

The application analyzes user-provided text and identifies emotions such as:

* Anger 😠
* Disgust 🤢
* Fear 😨
* Joy 😊
* Sadness 😢

It also determines the **dominant emotion** in the given input.

---

## ⚙️ Features

* Detects five core emotions from text
* Returns structured JSON output
* Identifies dominant emotion
* Includes error handling for invalid input
* REST API built using Flask
* Unit tested using Python's unittest framework
* Static code analysis using pylint

---

## 🛠️ Technologies Used

* Python 3
* Flask
* IBM Watson NLP API
* Requests library
* Unittest
* Pylint

---

## 📂 Project Structure

```
EmotionDetection/
│── __init__.py
│── emotion_detection.py

test_emotion_detection.py
server.py
README.md
```

---

## 🚀 How to Run the Application

### 1️⃣ Clone the Repository

```
git clone https://github.com/om22310858-cloud/EmotionDetector.git
cd EmotionDetector
```

### 2️⃣ Install Dependencies

```
pip install flask requests
```

### 3️⃣ Run the Server

```
python server.py
```

### 4️⃣ Access the API

Open your browser and run:

```
http://localhost:5000/emotionDetector?textToAnalyze=I am happy
```

---

## 📊 Example Output

```json
{
 'anger': 0.012543,
 'disgust': 0.003456,
 'fear': 0.00456,
 'joy': 0.98567,
 'sadness': 0.00567,
 'dominant_emotion': 'joy'
}
```

---

## ❗ Error Handling

If no text is provided:

```
Invalid text! Please try again!
```

---

## 🧪 Running Unit Tests

```
python test_emotion_detection.py
```

Expected result:

```
Ran 1 test in X.XXXs

OK
```

---

## 📈 Code Quality Check

```
python -m pylint server.py
```

Expected score:

```
Your code has been rated at 10.00/10
```

---

## 📚 Conclusion

This project demonstrates how Natural Language Processing (NLP) can be used to analyze human emotions from text. It integrates API usage, testing, packaging, and deployment in a simple Python application.

---

## 👨💻 Author

Om Khirade
GitHub: https://github.com/om22310858-cloud
