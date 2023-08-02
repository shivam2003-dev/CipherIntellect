# CipherIntellect 📄

CipherIntellect is an online application designed for handling PDF files. It offers a range of functionalities, including extracting metadata, images, text, and annotations from PDFs. 🔨

One of the standout features of this application is ChatPDF, which utilizes LangChain's natural language processing technology and OpenAI to enable users to interact with their PDFs. This innovative feature allows for efficient information retrieval and streamlined task completion, setting CipherIntellect apart from other online PDF tools.



## Features 🎉

- Extract text from a PDF file 💬
- Extract images from a PDF file 🖼️
- Extract metadata from a PDF file 📝
- Encrypt a PDF file with a password 🔒
- _**Chat with a PDF file using OpenAI and Langchain**_ 🤖

## Overview 📋

CipherIntellect is built using the Python programming language 🐍 and the Streamlit framework. The app uses the PyPDF2 library to perform various PDF-related tasks, such as parsing and extracting relavent information from PDFs. The app also uses OpenAI and Langchain APIs to enable the "ChatPDF" feature.

When a user uploads a PDF file to the app, the app performs the requested task (e.g. merging PDFs), and then generates a new PDF file that the user can download.

## Installation ⚙️

To install the repository, please clone this repository and install the requirements:

```
pip install -r requirements.txt
```

## Usage 🏃

To use the application, run the `main.py` file with the streamlit CLI (after having installed streamlit): 

```
streamlit run app.py
```

## Motivation 💡

The motivation behind CipherIntellect was to create a simple, user-friendly tool for working with PDF files. While there are many PDF-related tools available online, many of them are complex and difficult to use. CipherIntellect aims to provide an easy-to-use alternative that can be used by anyone, regardless of technical expertise and make process of data extraction a cake work.

## Problem Solved ✅

PDF files are a ubiquitous file format used for sharing documents across platforms and devices. However, working with PDF files can often be a tedious and time-consuming process. CipherIntellect aims to solve this problem by providing a simple, user-friendly tool for working with PDF files.

## Tech Stack 🛠️

CipherIntellect is built using the following technologies:

- Python 🐍
- Streamlit 🌟
- PyPDF2 📑
- OpenAI 🤖
- Langchain 🔗

## Challenges Faced 🤔

📚 Selecting the most suitable libraries for the project, which we accomplished by choosing Python, Streamlit, PyPDF2, and LangChain.
🌟 Developing a unique feature that distinguishes CipherIntellect from other online PDF apps. Our ChatPDF feature allows users to interact with their PDF files using OpenAI and LangChain's natural language processing technology.
💰 Optimizing the cost of preparing the knowledge base for ChatPDF by selecting the correct size and ratio of the chunk size and overlap size.

## Future Plans 🔮

We have several future plans for CipherIntellect, including:
- Merge multiple PDF files into a single file 📂
- Split a PDF file into multiple files 📄
- Compress a PDF file to reduce its size 📉
- Convert a PDF file to a different file format (e.g. JPEG, PNG, DOCX) 🔄
- Adding more PDF-related features, such as OCR (Optical Character Recognition) and watermarking
- Adding support for more file formats (e.g. Word documents, Excel spreadsheets)




## Links
- 👉 Streamlit: https://streamlit.io/
- 👉 Langchain docs: https://python.langchain.com/en/latest/index.html
