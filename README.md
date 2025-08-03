# Ai_Agent_For_Smart_Farming_Advice
An intelligent AI-powered agent designed to assist farmers with real-time, data-driven agricultural recommendations. Built using IBM Cloud and watsonx.ai, this agent analyzes weather, soil, and crop data to provide personalized advice on irrigation, fertilization, pest control, and market trends.
🌾 AI Agent for Smart Farming Advice
An intelligent, multilingual AI agent designed to empower farmers with real-time, personalized agricultural guidance. Leveraging IBM watsonx.ai, BeeAI, and LangGraph, this agent integrates weather, soil, crop, and market data to deliver actionable insights—boosting productivity, sustainability, and profitability.

🎯 Project Motivation
Agriculture faces growing challenges: climate variability, soil degradation, pest outbreaks, and volatile market prices. Smallholder farmers often lack access to timely, localized advice. This project aims to bridge that gap by:
- Democratizing access to expert-level farming insights
- Supporting decision-making with AI-driven recommendations
- Promoting sustainable and data-informed agricultural practices

🚀 Key Features
| Feature | Description | 
| 🌦️ Weather-Aware Irrigation | Suggests optimal watering schedules based on forecast and soil moisture | 
| 🧪 Soil Health Monitoring | Recommends fertilizers and crop rotation strategies | 
| 🐛 Pest & Disease Alerts | Detects early signs of infestation and suggests eco-friendly treatments | 
| 📈 Market Price Forecasting | Provides mandi price trends and selling recommendations | 
| 🗣️ Multilingual Support | Supports Hindi, Bengali, Tamil, and more for regional accessibility | 
| 🧠 Conversational Agent | Natural language interface for farmer queries via voice or text | 
| ☁️ Cloud Deployment | Hosted on IBM Cloud with watsonx.ai and Granite foundation models | 



🧠 Architecture Overview
graph TD
    A[Farmer Input] --> B[AI Agent]
    B --> C[Weather API]
    B --> D[Soil Sensor Data]
    B --> E[Crop Database]
    B --> F[Market Price API]
    B --> G[watsonx.ai LLM]
    G --> H[Granite Model]
    B --> I[Response Generator]
    I --> J[Streamlit UI / Voice Bot]


- Agent Framework: BeeAI or LangGraph for modular orchestration
- LLM Backend: IBM watsonx.ai with Granite models for reasoning
- Data Sources: OpenWeatherMap, Agmarknet, local soil sensors
- Interface: Streamlit dashboard + voice assistant (Twilio or WhatsApp)

🛠️ Tech Stack
| Layer | Tools & Services | 
| Language Model | IBM watsonx.ai + Granite | 
| Agent Framework | BeeAI / LangGraph | 
| UI Layer | Streamlit, Twilio, WhatsApp | 
| Cloud Hosting | IBM Cloud, Docker, Podman | 
| Data Sources | OpenWeatherMap, Agmarknet, FAO datasets | 
| Programming Lang | Python | 

📊 Sample Use Cases
- Farmer Query: “What’s the best time to irrigate my wheat crop this week?”
- 🧠 Agent Response: “Based on upcoming rainfall and current soil moisture, irrigate on Thursday evening.”
- Farmer Query: “My tomato plants have yellow spots—what should I do?”
- 🐛 Agent Response: “Likely early blight. Apply neem oil spray and monitor for fungal spread.”
- Farmer Query: “Should I sell my onions now or wait?”
- 📈 Agent Response: “Prices expected to rise 12% next week in Delhi mandi. Consider holding for 5–7 days.”

🏆 IBM Certifications
- ✅ Getting Started with AI
- ✅ Journey to Cloud
- ✅ RAG Lab
(Include Credly badge links or screenshots)

🙋‍♂️ Author
Aditya Saini
🌐 LinkedIn

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.
