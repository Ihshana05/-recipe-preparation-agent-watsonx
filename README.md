# -recipe-preparation-agent-watsonx
# 🍽️ Recipe Preparation Agent using IBM Watsonx Agentic AI

This AI-powered cooking assistant helps users prepare meals using the ingredients they have on hand.  
Built with IBM Watsonx Agentic AI, it suggests recipes, ingredient substitutions, and cooking tips tailored to dietary preferences — all without needing a dataset.

---

## 🎯 Problem Statement

Users often struggle to decide what to cook with the ingredients available in their kitchen.  
This project solves that by building an agent that takes in grocery inputs and returns a full cooking guide — smart, simple, and sustainable.

---

## 🚀 Technologies Used

- IBM Watsonx Agentic AI  
- Granite Foundation Model (`ibm/granite-13b-instruct-v2`)  
- LangGraph Framework  
- ReAct Architecture  
- IBM Cloud Deployment  
- JSON-based Input Interface  

---

## 💡 Features

- Accepts natural language input (ingredients + preferences)  
- Returns step-by-step recipe suggestions  
- Offers ingredient substitutions  
- Handles dietary tips (e.g., vegetarian, gluten-free)  
- Live preview chat and JSON input supported

---
### 👀 Preview

Here’s a sample output of the deployed Recipe Agent:

![Output Screenshot](https://github.com/Ihshana05/-recipe-preparation-agent-watsonx/blob/main/output.png)

---

## 🧪 Example Interaction

**Input:**
```json
{
  "messages": [
    {
      "role": "user",
      "content": "I have rice, garlic, onion, and butter. I'm vegetarian. Suggest a recipe."
    }
  ]
}
