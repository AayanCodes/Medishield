# Medishield: Smart anonymous Health Decision System.

This project is an AI-powered web application that helps users get instant first aid guidance using image analysis and symptom-based detection. It also provides a private health check feature where users can analyze sensitive issues anonymously.

## Problem Statement

Many people do not have immediate access to medical help and often hesitate to discuss sensitive health issues. This leads to delayed treatment and worsening conditions.

## Solution 

Our Solution provides:

- Instant first aid guidance using AI
- Injury detection through image upload
- Symptom-based health analysis
- Anonymous private health checking

## Keyfeatures
- Injury Detection by image:<br>
      Upload an image and get AI-based analysis with first aid suggestions.
- Symptom Checker: <br>
      Select symptoms and receive instant guidance.
- Care with Privacy:<br>
      Analyze sensitive health issues without sharing personal information.

### Images
<img width="1920" height="1080" alt="Screenshot 2026-03-20 225044" src="https://github.com/user-attachments/assets/8ea09e76-1b96-4daf-bc90-2d66b67e2492" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/48ccb5db-7b1f-4d03-b523-5b1d54177ab3" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b98d24be-fb7e-42e2-97e0-fe574ed2c8c3" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/41e02506-f27d-4fa4-abf8-b54e3982728a" />
  
---

## Tech Stack:
- Frontend: HTML, CSS, JavaScript, Bootstrap
- Backend: Python(Flask)
- AI Model: Gemini API

---

## How to Run the Project

### Clone the Repo
```bash
git clone <Repo-link> cd your-project-folder
```

### Install Dependencies 
```bash
python -m pip install flask google-generativeai pillow-dotenv
```


### Edit Example.env File
- Rename the file from **.eve.example ** to **.env**
- Paste your API key in it

```bash
GEMINI_API_KEY=__YOUR_API_KEY_HERE__
```

 ### Run the App 
```bash
python main.py
```

 ### Open in browser

 ```bash
http://127.0.0.1:5000/
