# Minor_project_1
# 🧬 GroupDNA – WhatsApp Group Chat Analyzer

GroupDNA is a Python-based WhatsApp Group Chat Analyzer that transforms raw WhatsApp chat data into meaningful insights about group activity, communication patterns, frequently used words, response behavior, and participant characteristics.

The project processes an exported WhatsApp `.txt` chat file and presents the results through a clean terminal-style report.

---

## 📌 Project Overview

WhatsApp groups generate a large amount of unstructured text data every day. GroupDNA analyzes this data to discover patterns such as:

- Who sends the most messages?
- Which day is the group most active?
- What time is the group most active?
- What are the most frequently used words?
- How quickly do participants respond?
- Who has the longest inactive periods?
- What communication patterns can be identified from each participant?

The project demonstrates how basic Python programming concepts can be applied to a real-world dataset.

---

## ✨ Features

### 👥 Group Overview
- Total number of messages
- Number of participants
- Chat start and end dates
- Messages sent by each participant
- Participant-wise message ranking

### 📅 Activity Analysis
- Most active day
- Most active hour
- Day-wise and hour-wise message activity
- 6 × 24 activity heatmap using NumPy

### 🔤 Word Analysis
- Top 10 most frequently used words
- Stop-word filtering
- Punctuation removal
- Top 5 words used by each participant
- Frequency-based word visualization using terminal bars

### ⚡ Response Analysis
- Average response time for each participant
- Longest consecutive inactive period
- Percentage of silent days

### 🎭 Personality Archetypes
GroupDNA identifies communication patterns using predefined archetypes:

- **THE SPAMMER**
- **THE GROUP MOM**
- **THE NIGHT OWL**
- **THE STORYTELLER**
- **THE DRAMA QUEEN**
- **THE GHOST**
- **THE COMEDIAN**
- **THE QUESTION MASTER**

---

## 🛠️ Technologies Used

- **Python**
- **NumPy**
- **Google Colab / Jupyter Notebook**
- Python File Handling
- Python Dictionaries, Lists and Sets
- String Processing
- Date and Time Processing

---

## 📂 Project Structure

```text
GroupDNA/
│
├── Kartikkhurana_minor_project1.ipynb
├── whatsappchat.txt
└── README.md
