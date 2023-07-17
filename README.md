Installation
Install Langchain and other required packages.

pip install langchain openai chromadb tiktoken unstructured
Modify constants.py.default to use your own OpenAI API key, and rename it to constants.py.

Place your own data into data/data.txt.

Example usage
Test reading data/data.txt file.

> python chatgpt.py "what is my dog's name"
Your dog's name is Sunny.
Test reading data/cat.pdf file.

> python chatgpt.py "what is my cat's name"
Your cat's name is Muffy.