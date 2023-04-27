# Send an email using DearPyGUI, ChatGPT and your voice

This project will show you how to Send an email using DearPyGUI, ChatGPT and your voice

## Setup

### System dependencies

- Python v3.x

### Create keys

We need to have an [ChatGPT Account](https://platform.openai.com/signup) in order to create our [keys](https://beta.openai.com/account/api-keys)
Also, we need to create an account for [Amazon Polly](https://aws.amazon.com/polly/)

### Gather environment variables

You'll need the following values:

```text
ACCESS_TOKEN = ""
CLIENT_ID = ""
CLIENT_SECRET = ""
OPEN_AI = ""
```

Add the above values to a new `.env` file:

```bash
$ touch .env # Then add your env variables
```

### Install dependencies

```bash
$ pip3 install nylas
$ pip3 install dearpygui
$ pip3 install openai
$ pip3 install speech_recognition
$ pip3 install boto3
$ pip3 install jellyfish
$ pip3 install textwrap
$ pip3 install playsound
```

## Usage

Clone the repository. Go to your terminal and type:

```bash
$ cd Email_Assistant
$ python3 email_assistant.py
```

## Learn more

Visit our [Nylas Python SDK documentation](https://developer.nylas.com/docs/developer-tools/sdk/python-sdk/) to learn more.
