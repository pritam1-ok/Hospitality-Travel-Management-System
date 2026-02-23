Multi-Agent Hospitality System 

https://exquisite-crumble-9966d1.netlify.app/ 

Project Overview
The Multi-Agent Hospitality System is an AI-powered travel assistant designed to automate and simplify travel planning. Built as part of the Agentic AI course, this project utilizes a collaborative network of artificial intelligence agents to gather real-time data, reason through user requirements, and generate highly personalized travel itineraries. 

Problem Statement & Objectives
Planning a trip often requires gathering information from numerous blogs, booking platforms, and travel websites, which can be an overwhelming and time-consuming process. Users frequently struggle to build itineraries that align with their specific schedules, budgets, and preferences. 

Key Objectives:

Develop an AI travel assistant capable of generating customized itineraries. 

Implement a multi-agent architecture to ensure intelligent and efficient task coordination. 

Retrieve up-to-date, real-time travel information from external APIs. 

Provide a seamless, user-friendly web interface for intuitive interaction. 

Key Features

Personalized Itineraries: Generates context-aware travel plans based on user input such as destination and preferences. 


Intelligent Collaboration: Uses a multi-agent system to efficiently distribute and execute planning tasks. 


Real-Time Data: Fetches live travel information from external web sources. 


Semantic Search: Offers context-aware recommendations leveraging Large Language Models (LLMs). 


Responsive UI: Features an interactive web interface for seamless travel planning. 

System Architecture & Workflow
The system operates on a modular architecture to ensure scalability and ease of maintenance.  The core workflow relies on specialized agents:


User Input: The user enters their travel details via the web application, and the frontend validates this request. 


Coordinator Agent: Acts as the central controller, receiving the request and performing intent analysis to understand the user's needs. 



Researcher Agent: Assigned the task of gathering data, this agent fetches real-time travel information from APIs and web sources. 



Writer Agent: Receives the gathered data and uses a Large Language Model to synthesize and format a comprehensive, day-by-day itinerary. 



Final Output: The structured travel plan, including transport, accommodation, and dining estimates, is returned and displayed to the user. 


Tools & Technologies Used
Frontend:

React 

TypeScript 

Tailwind CSS 

Vite 

Backend & AI Orchestration:

CrewAI 

LangChain 

Language Models & Data Retrieval:

Groq API & Ollama 

Tavily Search API & SERP API 

Selenium 

Databases:

FAISS / Chroma (Vector Storage) 

MongoDB & MySQL 

Future Enhancements
While the current system successfully generates structured travel plans, future iterations will focus on expanding its capabilities: 

Integration with live booking platforms for end-to-end travel management. 


Implementation of full-scale user authentication and personalized profiles. 


Development of a mobile application and voice-based conversational interface. 

Adaptive recommendations using Machine Learning based on user feedback. 


Integration with mapping services for live navigation support. 

Contributors

Group: 05D7 

Riya Sathe (EN22CS301814) 

Pritam Kumar Ghosh (EN22CS301756) 

Vinayak Pandiya (EN22ME304111) 

Pranjal Dhanotiya (EN22CS301728) 

Preet Solanki (EN22CS301753) 


Developed under the Datagami Lead Digital Technology program at Medicaps University.
