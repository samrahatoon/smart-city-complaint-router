# smart-city-complaint-router

An AI-powered automation built with **n8n** that helps citizens submit complaints through a website and automatically routes them to the city management email inbox — saving time, improving response, and promoting smart city governance.

---

## 🚀 Project Overview

**Smart City Complaint Router** is designed to simplify how citizens report local issues such as:
- Road damage
- Streetlight malfunction
- Waste management
- Water leakage
- Noise pollution

When a citizen submits a form on the website, the data is instantly sent to **n8n** through a webhook.  
The automation processes the data, creates a structured email with the correct subject line, and sends it to the **city management inbox** for quick action.

---

## Workflow Summary

### Workflow Name: `Smart City Complaint Router`

**Nodes Used:**
1.  **Webhook Node** — Captures complaint data from the website form.  
2.  **Set Node** — Structures and formats the data into a professional email body and subject.  
3.  **Gmail Node** — Automatically sends the formatted complaint to the city’s official email inbox.

---

##  How It Works

1. Citizen submits a complaint form on the website.  
2. The webhook in n8n receives this data instantly.  
3. The Set node organizes it into a neat message format.  
4. The Gmail node emails the complaint with a category-specific subject (e.g., “New Complaint - Road Damage”).  
5. The city team receives it and can respond efficiently.

---

##  Website Integration

The website has a **simple HTML/JavaScript form** that sends a POST request to the n8n webhook URL.  
You can later integrate it with platforms like:
- WordPress  
- Framer  
- Claude AI site generator (for demo)

Example form fields:
- Name  
- Email  
- Location  
- Category (dropdown: Roads, Water, Waste, etc.)  
- Description  

---

## 💡 Future Enhancements

- Add **Google Sheets** node to log all complaints.  
- Integrate **AI classifier** to auto-detect complaint category.  
- Add **auto-reply email** to confirm receipt to the citizen.  
- Connect **Telegram alerts** for urgent complaints.

---

## 🧰 Tools & Technologies

- **n8n** (Automation platform)  
- **Gmail API** (Email delivery)  
- **Webhook integration** (Data input)  
- **OpenAI Node (optional)** for text summarization or classification  
- **HTML/JS form** (Frontend submission)

---

## 👩‍💻 Author

**Samra Mukhtar**  
AI & Automation Enthusiast | n8n Workflow Developer  
 [Samrahatoon@gmail.com]  

---

⭐ **If you like this project, give it a star on GitHub!**  
Let’s build smarter cities together 🌍
