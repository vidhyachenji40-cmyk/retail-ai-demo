# 🛍️ AI-Powered Retail Search Engine

A high-performance product discovery interface built using **Google Cloud Vertex AI Search** and deployed via **GitHub Pages**. This project demonstrates an end-to-end integration of Generative AI into a retail environment.

## 🚀 Live Demo
[View the Live Search Engine](https://vidhyachenji40-cmyk.github.io/retail-ai-demo/)

## ✨ Key Features
* **Natural Language Understanding:** Users can search using conversational queries (e.g., "warm hoodies for winter") rather than just keywords.
* **Real-time Data Sync:** Connected to a Google Cloud Data Store containing an inventory of tech and lifestyle products.
* **Responsive UI:** A custom-integrated Gen-AI search widget that works seamlessly across desktop and mobile devices.

## 🛠️ Technical Stack
* **Frontend:** HTML5, CSS3, JavaScript.
* **AI Engine:** [Vertex AI Search](https://cloud.google.com/vertex-ai-search-and-conversation) (Google Cloud Platform).
* **Hosting:** GitHub Pages.

## 📖 How it Works
1.  **Data Ingestion:** A product catalog (JSON/BigQuery) was indexed in Google Cloud.
2.  **Configuration:** The search engine was tuned for retail-specific relevance and "Buy" intent.
3.  **Deployment:** The Vertex AI widget was embedded into the frontend and authorized via domain whitelisting to provide secure, real-time results.
