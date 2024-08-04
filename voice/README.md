*****************VOICE BOT USING PYTHON*************

1.First you need to take new termianl & create new virtual environment.

=>using
``bash
python -m venv venv
``bash
I have already created my virtual environment

2. Then activate virtual environment & Install the requirements
 ==>For Activating 
```bash
./venv/Scripts/activate
```bash

This are requriments have to install
```bash
pip install -r requirements.txt
```bash
I have already install all requriments that are required for this vioce bot

3. Create a `.env` file in the root directory and add the following variables:

Make sure you have the following API keys:
 
 ==> make sure you have to give your KEYS
  https://console.deepgram.com
  https://platform.openai.com
  https://elevenlabs.io
""

```bash
DEEPGRAM_API_KEY=XXX...XXX
OPENAI_API_KEY=sk-XXX...XXX
ELEVENLABS_API_KEY=XXX...XXX
>>save this keys in .env file like this==>
```

## How to use
Make sure you have to activate the environment
./venv/Scripts/activate

1. Run `display.py` to start the web interface

```bash
python display.py
```

2. In another terminal, run `main.py` to start the voice assistant

```bash
python main.py
```
- Once ready, both the web interface and the terminal will show `Listening...`
- You can now speak into the microphone
- Once you stop speaking, it will show `Stopped listening`
- It will then start processing your request
- Once the response is ready, it will show `Speaking...`
- The response will be played and displayed in the web interface.