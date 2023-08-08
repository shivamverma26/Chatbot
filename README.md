![Paradox](Logo/ParadoxLogo.png)

# ChatBot

## Installation & Setup

[Install Python] https://www.python.org/downloads/



If you have Python & pip installed then check their version in the terminal or command line tools

```
python3 --version
```

```
pip --version
```

## Installing Flask

In your terminal run the requirements.txt file using this pip

```
pip install -r requirements.txt
```


## Running ChatBot Application in Terminal

```
cd into your directory
```

```
python app.py
```



## What you will create

Introduction:
Discover how to build a sophisticated chatbot with the natural language prowess of Microsoft DialoGPT. By integrating this advanced language model with Flask, a Python web framework, we'll create a dynamic web app that engages users in interactive conversations.

Development Environment Setup:
Prepare your environment by installing essential tools like Python, Flask, and dependencies for a seamless development experience.

Frontend Design:
Craft an appealing chat interface using HTML, CSS, and JavaScript. Employ jQuery to facilitate smooth communication between frontend and backend.

Backend Implementation with Flask:
Implement the backend using Flask, creating routes to process user messages and generate DialoGPT responses.

Training and Fine-Tuning:
Enhance accuracy by training and fine-tuning DialoGPT to align with your application's context and user interactions.

Deployment:
Deploy your chatbot to a hosting platform, making it accessible to users for real-time conversations.

Conclusion:
Create an interactive chatbot, gaining insights into DialoGPT, Flask, and web development, and exploring ways to enhance its capabilities.






# ChatBot Link
The Chatbot is constructed using the Microsoft/DialoGPT-medium model.

```
https://huggingface.co/microsoft/DialoGPT-medium
```

# User-Html

```
var userHtml = '<div class="d-flex justify-content-end mb-4"><div class="msg_cotainer_send">' + user_input + '<span class="msg_time_send">'+ time + 
    '</span></div><div class="img_cont_msg"><img src="https://i.ibb.co/d5b84Xw/Untitled-design.png" class="rounded-circle user_img_msg"></div></div>';
```

# Bot-HTML

```
var botHtml = '<div class="d-flex justify-content-start mb-4"><div class="img_cont_msg"><img src="https://i.ibb.co/fSNP7Rz/icons8-chatgpt-512.png" class="rounded-circle user_img_msg"></div><div class="msg_cotainer">' + bot_response + '<span class="msg_time">' + time + '</span></div></div>';
```