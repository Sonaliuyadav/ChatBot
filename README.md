# ChatBot
This project features a chatbot using Microsoft DialoGPT and Flask, with a responsive frontend built with HTML, CSS, JavaScript, and jQuery. It enables natural language conversations and includes setup instructions, dependencies, and fine-tuning tips for enhanced responses.
# ChatBot  

This project features a chatbot built using Microsoft DialoGPT and Flask, with a responsive frontend designed with HTML, CSS, JavaScript, and jQuery. The chatbot supports natural language conversations and provides a seamless user experience.  

## Features  
- **Natural Language Processing**: Uses Microsoft DialoGPT for generating human-like responses.  
- **Backend**: Flask-based backend for managing user interactions and bot responses.  
- **Frontend**: Interactive interface created with HTML, CSS, and JavaScript.  
- **Asynchronous Communication**: Utilizes jQuery for handling HTTP requests.  
- **Customizable and Extensible**: Fine-tuning guidance provided for personalized improvements.  

## Installation & Setup  

### Prerequisites  
- **Python**: Install Python from [here](https://www.python.org/downloads/).  
- **pip**: Install pip by running:  
    ```bash  
    curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py  
    python3 get-pip.py  
    ```  
  Verify installation:  
    ```bash  
    python3 --version  
    pip --version  
    ```  

### Install Flask  
1. Clone this repository:  
    ```bash  
    git clone <repository_url>  
    cd <repository_name>  
    ```  
2. Install dependencies:  
    ```bash  
    pip install -r requirements.txt  
    ```  

## Running the ChatBot Application  
1. Navigate to your project directory:  
    ```bash  
    cd <your_directory>  
    ```  
2. Start the application:  
    ```bash  
    python3 app.py  
    ```  
3. Open your browser and navigate to:  
    ```  
    http://127.0.0.1:5000/  
    ```  

## ChatBot Details  

### Microsoft DialoGPT  
This chatbot is built using the [Microsoft/DialoGPT-medium](https://huggingface.co/microsoft/DialoGPT-medium) model for generating conversational responses.  

### Frontend Templates  
#### User Message Template:  
```javascript  
var userHtml = '<div class="d-flex justify-content-end mb-4"><div class="msg_cotainer_send">' + user_input +  
    '<span class="msg_time_send">' + time + '</span></div><div class="img_cont_msg">' +  
    '<img src="https://i.ibb.co/d5b84Xw/Untitled-design.png" class="rounded-circle user_img_msg"></div></div>';  
```  

#### Bot Message Template:  
```javascript  
var botHtml = '<div class="d-flex justify-content-start mb-4"><div class="img_cont_msg">' +  
    '<img src="https://i.ibb.co/fSNP7Rz/icons8-chatgpt-512.png" class="rounded-circle user_img_msg"></div>' +  
    '<div class="msg_cotainer">' + bot_response + '<span class="msg_time">' + time + '</span></div></div>';  
```  

## What You Will Learn  
- Setting up a chatbot using Microsoft DialoGPT.  
- Integrating Flask for backend functionality.  
- Designing an interactive user interface with HTML, CSS, and JavaScript.  
- Handling asynchronous requests with jQuery.  
- Fine-tuning AI models for better performance.  

## Acknowledgments  
- **Microsoft DialoGPT**: [Model on Hugging Face](https://huggingface.co/microsoft/DialoGPT-medium).  
- Flask, HTML, CSS, and JavaScript for building a dynamic web application.  

Happy Coding! 🎉  
