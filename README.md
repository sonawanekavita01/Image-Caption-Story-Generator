# Image-Caption-Story-Generator
🖼️ Image Caption & Multilingual Story Generator (Jupyter + Tkinter) 
 
 A Python application that generates AI-powered captions and multilingual short stories (English, Hindi, Marathi) from uploaded images.
 This project uses **Tkinter GUI** (runs from Jupyter), **OpenRouter AI (GPT-4o-mini)** for image captioning, and **DeepSeek** for creative story generation.  

---

## 🚀 Features
- 📂 Upload and preview images (JPG, PNG, WEBP supported)  
- 📝 AI-generated image captions using GPT-4o-mini (Vision)  
- 🌍 Short stories in **English, Hindi, and Marathi** using DeepSeek  
- 🖥️ Tkinter GUI runs directly from Jupyter Notebook  
- 📜 Scrollable text output for long stories  

---


## 🖼️ Screenshots:


<img width="1920" height="1080" alt="Screenshot (371)" src="https://github.com/user-attachments/assets/926a1900-0592-4141-bccb-d9282c397811" />




<img width="1919" height="1014" alt="Screenshot 2025-09-05 213647" src="https://github.com/user-attachments/assets/12cb7b5c-850b-44ad-88b8-cddfbe2db0a5" />






## 🛠️ Installation (in Jupyter)

Install dependencies inside your Jupyter environment:


```python
!pip install pillow openai tk
🔑 Setup API Key
This project uses OpenRouter API. Get your free key from OpenRouter.

In Jupyter, set your key as an environment variable:


python
Copy code
import os
os.environ["OPENROUTER_API_KEY"] = "your_api_key_here"


▶️ Usage
Run your Tkinter app directly in a Jupyter cell:

python
Copy code
%run app.py
Or if you’ve pasted the code in a notebook cell, just run the cell.
A Tkinter window will open outside Jupyter.


Steps inside the GUI:

Click 📂 Upload Image to select an image.

Click 🚀 Generate Caption & Stories.

Read the caption and 3 AI-generated stories in the output box.


📌 Notes for Jupyter Users
The Tkinter GUI will open as a separate window, not inside Jupyter.

You may need to allow pop-ups in some environments (like JupyterLab).




