# ℹ️ Custom chatbot using Chainlit, Llama Index and OpenAI

A custom chatbot built in python using Chainlit, Llama Index and OpenAI

## 📦 Prerequisites

- Python 3.10 or higher
- OpenAI API key
- Llama Index
- Chainlit
- dotenv

## 🛠️ Setup

1. Clone the repository.
2. Install the required Python packages using pip:
    ```
    pip install -r requirements.txt
    ```
3. Set up your OpenAI API key in your environment variables. You can do this by creating a `.env` file in the root directory of the project with the following content:
    ```
    OPENAI_API_KEY=your_openai_api_key
    ```
4. Run the script:
    ```
    python main.py
    ```

## ❓ How it works

The script first loads the OpenAI API key from the environment variables. It then tries to load an existing index from the storage. If it fails (for example, if the index does not exist), it reads documents from a directory, creates a new index from these documents, and persists it to the storage.

## 👨🏻‍💻 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📜 License

MIT License

Copyright (c) 2024 Sumit Sahoo

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.