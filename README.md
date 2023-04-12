# OpenAI GPT3 API + Gradio

# About
Testing out a simple chatbot linked to the API for in house data privacy

![Chatbot screenshot](https://github.com/ZeratulXjs/chatbot_gra/blob/master/chatbot.png?raw=true)

# Core applications/programs used 
1. Python 3.11
2. Gradio 3.25

The `requirements.txt` file documents the code dependencies

# How to get the chatbot up and running
Please note: I am assuming you are using a Windows machine

1. Install Python.
    On Windows 10/11, Python should come installed. 
    However, if not, you can download and install the latest version from the [official site](https://www.python.org/downloads/windows/)  
    
2. Install Git.
    The Git For Windows installer can be downloaded from the [official site](https://git-scm.com/download/win)
    
3. Install Pipenv

    ```
    py -3 pip install --user pipenv
    ```

4. Clone the repository to your computer

    ```
    git clone https://github.com/ZeratulXjs/chatbot_gra.git
    ```
5. In your terminal, enter the directory chatbot_gra

    ```
    cd chatbot_gra
    ```
6. Create and activate your environment. 

    ```
    pipenv shell --python 3.11
    ```
7. Install the packages in requirements.txt

    ``` 
    pipenv install -r requirements.txt 
    ```

8. Make a copy of the ```env.example``` file. 

    Rename to ```.env``` and insert your OpenAI API key

9. Run the python app file

    ```
    py app.py 
    ```
  
10. Open the localhost server link in your browser 
    (http://127.0.0.1:7860)



