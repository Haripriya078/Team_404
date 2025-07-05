# Team_404

Project Kisan – Team 404
Project Kisan is an AI-powered personal assistant designed to empower small-scale farmers in rural India, acting as their agronomist, market analyst, and government scheme navigator—all in their local language.

Challenge Statement
Rural farmers like Rohan in Karnataka often face critical challenges: diagnosing crop diseases quickly, accessing real-time market prices to maximize profit, and understanding government schemes for agricultural support. Information is scattered, complex, and rarely available in regional languages, making timely, actionable decisions difficult.

Solution Overview
Project Kisan leverages Google Cloud's Vertex AI and Firebase Studio to deliver:

Instant Crop Disease Diagnosis: Farmers upload a photo of a diseased plant; our Gemini-powered AI analyzes it and provides actionable local remedies in Kannada.
Real-Time Market Analysis: The assistant fetches current mandi prices, analyzes trends, and gives clear sell/hold recommendations.
Government Scheme Navigation: Farmers can ask about subsidies or schemes in natural language; the agent explains eligibility and application steps simply.
Voice-First Interaction: Farmers interact via voice in their dialect, removing literacy barriers using Google's Speech-to-Text and Text-to-Speech.
Tech Stack
Google Vertex AI Gemini (multimodal/image/language analysis)
Firebase Studio (frontend, hosting, deployment)
Firestore (data storage)
Vertex AI Speech APIs (local language voice interaction)
Public APIs (market prices, government schemes)
Project Kisan aims to be the farmer’s trusted ally, bringing expert guidance, market insights, and government support directly to their smartphone—simply, quickly, and in their own language.