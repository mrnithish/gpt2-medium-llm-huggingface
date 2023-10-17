
# GPT-2 medium LLM Huggingface

This Python project harnesses the power of the GPT-2 model from Hugging Face for text generation. It utilizes the LLM (Language Model Layer) library and the langchain for language processing, creating an environment where you can easily generate human-like text content.

## Libraries Used

- Hugging Face Transformers (for GPT-2 model)
- LLM (Language Model Layer) 
- dotenv (for environment variable configuration)
- langchain (for language processing)

## Features

- **Text Generation**: The script can generate text content based on prompts provided.
- **Customizable Output**: Users can specify the length, style, and tone of the generated text.
- **Integration of GPT-2**: It employs the GPT-2 model from Hugging Face, known for its text generation capabilities.
- **Easy Configuration**: Environment variables (dotenv) are used for easy configuration and management.

## Prerequisites

Before running the script, make sure you have the following libraries installed:

- Python 3.x
- Hugging Face Transformers
- LLM
- dotenv
- langchain

You can install these libraries using pip:

```bash
pip install transformers llm python-dotenv langchain
```
##Usage

1.	Clone this repository to your local machine:
   
```bash
git clone https://github.com/yourusername/gpt2-text-generation.git
```
2.	Navigate to the project directory:

   
```bash
cd gpt2-huggingface-llm
```

4.	Configure your environment variables by creating a .env file with the necessary settings. An example .env file might look like this:

```bash
HUGGING_FACE_API_KEY=your_hugging_face_api_key
```

4.	Run the Python script:
   
```bash
python gpt2.py
```

5.	Follow the prompts to specify the text generation parameters, including length and style. 
6.	The generated text will be displayed in the console.

Customization

You can customize the script to handle specific text generation tasks or language processing requirements by modifying the text_generation.py script.

License

This project is licensed under the MIT Licence . See the LICENSE.md file for details.



