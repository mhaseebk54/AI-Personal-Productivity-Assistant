# AI-Personal-Productivity-Assistant

This project is a fully offline personal productivity assistant built using GPT4All and the Mistral-7B-Instruct model.
It generates a personalized productivity/study plan, including time blocks, priorities, consistency tips, and more — all from inside a Jupyter Notebook.

🚀 Features

✔ Works 100% offline
✔ Uses Mistral-7B-Instruct (Q4_0 GGUF) locally
✔ Generates personalized productivity/study plans
✔ Creates summaries using LLM responses
✔ Simple and easy to run in Google Colab or locally
✔ Interactive inputs for name, goals, study hours, and focus area

📦 Tech Stack

Python

GPT4All

Mistral-7B-Instruct Model

Jupyter Notebook

📁 Project Structure
PersonalAssistant.ipynb   # Main notebook
mistral-7b-instruct...gguf  # Model file (used locally)

🛠 Installation

Install GPT4All inside your notebook or local environment:

pip install gpt4all

🧩 Model Setup

Make sure you have the model file:

mistral-7b-instruct-v0.1.Q4_0.gguf


Place it in the directory where you run the notebook.

Then load it:

from gpt4all import GPT4All
model = GPT4All('mistral-7b-instruct-v0.1.Q4_0.gguf')

▶️ How to Use

Run the notebook.

Enter your:

Name

3 Goals

Study hours

Focus topic

The notebook generates:

A full personalized productivity plan

A summary of the plan (optional)

Example:

Generating your personalized plan...

 Summary
 <AI-generated summary here>

📌 Output Includes

Time-blocked study plan

Task priority levels (High/Medium/Low)

Recommended breaks

Study tips for consistency

Clean summary of the overall plan

📝 Notes

The model runs fully offline—no API keys needed.

You can replace the model with any GGUF compatible with GPT4All.
