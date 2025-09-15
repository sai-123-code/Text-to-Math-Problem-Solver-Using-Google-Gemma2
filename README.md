# Text-to-Math-Problem-Solver-Using-Google-Gemma2  

An end-to-end generative AI math chatbot built with **Streamlit**, **LangChain**, and **Google Gemma 2**, combining Wikipedia search and a calculator tool to solve problems with detailed step-by-step solutions.  

## Overview  
This project demonstrates how to build a **text-to-math problem solver** using generative AI. Users can enter math problems in natural language, and the chatbot provides clear, step-by-step solutions. It can handle arithmetic operations, reasoning problems, and also leverage Wikipedia for additional context.  

The app integrates multiple tools and chains, including:  
- **Wikipedia Tool** – for retrieving relevant knowledge.  
- **Math Tool** – for performing accurate calculations.  
- **Reasoning Tool** – for handling logical reasoning tasks.  

All tools are combined with an **LLM agent** powered by Google Gemma 2 via ChatGrok.  

## Features  
- Solve math problems from natural language queries.  
- Step-by-step detailed explanations.  
- Logical reasoning and problem-solving.  
- Wikipedia-powered context search.  
- Interactive web app built with Streamlit.  

## Project Setup  

### 1. Create Python environment  
```bash
conda create -p venv python==3.10 -y
```

### 2. Create requirements.txt file with required libraries.

### 3. Activate environment by running below command.
```bash
conda activate venv/ 
```

### 4. Install all libs in requirements.txt using below command.
```bash
pip install -r requirements.txt
```

### 5. Run 'app.py' file using below command from respective folder.
```bash
streamlit run app.py
```
## Demo 1
<img width="946" height="470" alt="DEMO1" src="https://github.com/user-attachments/assets/b973f29b-0ee7-4324-b087-8e3d61e820fc" />
<img width="938" height="468" alt="Screenshot 2025-09-15 122430" src="https://github.com/user-attachments/assets/82a8892e-f2cb-4992-9cb1-158de12c33d8" />

## Demo 2
<img width="950" height="472" alt="DEMO2" src="https://github.com/user-attachments/assets/c130b7b5-8695-422e-bf8c-9a7bfc965d77" />
<img width="959" height="464" alt="Screenshot 2025-09-15 123004" src="https://github.com/user-attachments/assets/92b763ea-a74e-4022-8330-a9fecab73512" />


