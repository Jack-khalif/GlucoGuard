# GlucoGuard
# Smart Glucose Monitoring with AI | Microsoft Data + AI Kenya Hack

## 🩺 Problem Statement

Diabetic patients face real-time decision fatigue, generic meal advice, and little predictive support. Our solution leverages Microsoft Fabric + Azure OpenAI to provide proactive, personalized glucose insights.

---

## 🚀 What We Built

- **📊 Real-time glucose dashboard** with Power BI (Microsoft Fabric)
- **🧠 Azure OpenAI Integration** for meal suggestions
- **📸 (Optional) Azure Vision** for food image-to-carb predictions
- **🔐 Secure API usage via Azure Key Vault**
- **📤 Alerts via email (or Teams)** when glucose spikes are detected

---

## 📁 Structure

- `notebooks/`: Fabric notebooks (explore data, generate insights)
- `azure-function/`: Optional image analysis backend
- `resources/`: Sample glucose + food data
- We designed a seamless flow connecting real-time glucose data, AI-driven meal feedback, and engagement insights, all within the Microsoft ecosystem:



Diagram Source: GlucoGuard_2.0.drawio
You can open and edit this file using Draw.io (Diagrams.net).

Key Components:

Microsoft Fabric Lakehouse – storage & processing

Power BI – visual dashboards for real-time monitoring

Azure OpenAI – GPT-based suggestions for meals

Azure Key Vault – secure key management

Notebook Workflows – trigger insights, alerts, and coaching

---

## 🔧 Setup

1. Link your Microsoft Fabric Lakehouse
2. Set up Azure Key Vault with secrets:
   - `openai-key`
   - `openai-endpoint`
3. Run notebooks in order.

---

## 📽️ Demo Video

[TR]

---

## 👥 Team

- Jackson– Fabric notebooks & dashboard
- Alex– Azure integration & AI logic
- Issa Mohammed - Power Bi expert
