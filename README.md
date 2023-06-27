# ChatGPT-Personal-Data

This is a simple script to use ChatGPT on your own files and data. 

## Installation

1. Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.

```
pip install langchain 
```
```
pip install openai
```
```
pip install chromadb (ensure Microsoft C++ Build Tools are installed on your system)
```
```
pip install tiktoken
```

2. Modify `constants.py` to use your own [Open API key](https://platform.openai.com/account/api-keys).

3. Place your own data into `data.txt`.

## Example usage
Test reading `data.txt` file.

```
> python chatgpt.py "When is my dentist appointment?" 
My dentist appointment is on 26.06.23 at 18.30h.
``` 


