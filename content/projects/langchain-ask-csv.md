---
title: "Langchain Ask your CSV"
description: "Chat with your CSV file with help of LLM"
dateString: OCT 2023
draft: false
tags: ["LLM", "OPENAI", "CSV", "CHAT", "AI", "PALM", "GOOGLE"]
showToc: false
weight: 101
cover:
    image: "projects/langchain-ask-csv/cover.png"
--- 

## Project Overview

In this project, users have the ability to engage with any CSV file by querying its contents. The application responds to these inquiries by leveraging a Language Learning Model (LLM), which extracts and formulates answers directly from the information within the file.

## Working of the Project:

As soon as the user uploads a CSV file, the OpenAI embedding model is utilized to generate embeddings of the file's contents. These embeddings are then stored in a vector database called FAISS, which is maintained locally. When a user poses a question, it is converted into embeddings and compared with those in the database. Subsequently, the most relevant embedding is decoded and processed by the Google Palm2 LLM, which I am employing in this project due to its free accessibility. The final answer is then retrieved and displayed on the screen.

### Technologies Leveraged: 

1. Embedding by OPENAI
2. LLM by Google (PaLM 2)
3. Langchain
4. Streamlit for UI.

### Additional Resources

### 🔗 <a href="https://github.com/Haseeb-Akhlaq/Langchain-Ask-CSV" target="_blank">GITHUB</a>

### 🔗 <a href="https://www.youtube.com/watch?v=BgxL03PgIcI&t=4s" target="_blank">Youtube Tutorial</a>