
### Things you will need
* Dialogflow CX and ES agent
    > some knowledge of Dialogflow CX and ES as well
* OpenAI account and API Key
    > create an account [here](https://openai.com/)
* NGROK for exposing our local server to internet for testing
    > get it from [here](https://ngrok.com/)
* Python as a programing tool
    > install it from [here](https://www.python.org/downloads/)

### How to use it
To replicate the work of this repository and run it locally, you need to follow these steps:
* create a `.env` file inside the root directory, create these environmental variables:
    ```
    OPENAI_API_KEY=YOUR OPENAI API KEY
    ```
* create a virtual environment and activate it before installing the packages
* install all the required dependencies from the `requirements.txt` file
```python
pip install -r requirements.txt
```
* run the server with either of the following commands
```python
python run.py
```
* add the webhook url to Dialogflow
    > CX: YOUR NGROK URL/dialogflow/cx/receiveMessage
    
    > ES: YOUR NGROK URL/dialogflow/es/receiveMessage

