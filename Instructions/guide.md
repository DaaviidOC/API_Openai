# OpenAI API Installation and Usage Guide

This project demonstrates how to use your OpenAI API to make queries to GPT-4 from your code or to generate images with DALL-E 3.

## Prerequisites
- An environment for working with Python.
- Internet connection.
- OpenAI account with access to the GPT and DALL-E 3 APIs.

## Script Execution
- Assuming Python and your environment are already installed, you will need to install openai:</br>
· !pip install openai==0.28</br>
· !pip install --upgrade openai</br>

- Import libraries:</br>
· import openai</br>
· import os</br>
· import requests</br>
· from PIL import Image

- Assign your API key to a variable:</br>
· openai.api_key = "********" </br>
· Make sure to replace the asterisks with your API key.

- In case of an error with the Windows CLI, reset the kernel and re-execute the command:</br>
· !pip install openai==0.28

- In the script for making GPT queries, you can use "content": input(" "), to write queries in the input rather than in the code.
