# Chatgpt-cli

It's a very minimal cli prompt, where you can chat and keeping the conversation session memorable by chatgpt.

## Install

Assuming you created a set env variable with key named `OPENAI_API_KEY`.
If you don't have a api key [visit here](https://beta.openai.com/account/api-keys) and generate one.

```
$ pip3 install gpt-chatbot-cli
```

## Usage

```bash
$ gpt-chatbot-cli --help

Usage: gpt-chatbot-cli [OPTIONS]

  Generates text using the OpenAI API.

  Examples:
      gpt-chatbot-cli
      gpt-chatbot-cli --api_key=YOUR_API_KEY
      gpt-chatbot-cli --api_key=YOUR_API_KEY --model=text-davinci-002 --temperature=0.7

Options:
  --api_key TEXT       Openai API key. If not provided, will prompt for it or
                       use the environment variable OPENAI_API_KEY.
  --model TEXT         Model to use for text generation | (default: text-
                       davinci-003)
  --temperature FLOAT  Temperature for text generation | (default: 0.9)
  -h, --help           Show this message and exit.

```


## Demo

[![asciicast](https://asciinema.org/a/557311.svg)](https://asciinema.org/a/557311)
