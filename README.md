# OpenAI GPT3 API + Gradio

# About
Testing out a simple chatbot linked to the API for in house data privacy

# Core applications/programs used 
1. Python 3.11
2. Gradio 3.25

The `requirements.txt` file documents the code dependencies

# How to use flask to view web app
Please note: I am assuming you are using a Windows machine

1. Install Python
    On Windows 10, Python should come installed. 
    However, if not, you can download and install the latest version from the [official site](https://www.python.org/downloads/windows/)  
    
2. Install Git 
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
4. Install the packages in requirements.txt

    ``` 
    pipenv install -r requirements.txt 
    ```

5. Run the python app file

    ```py app.py ```
  
6. Open the localhost server link in your browser 
    [http://127.0.0.1:7860]

