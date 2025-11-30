# n8n AI Agents Workflows

A collection of production-ready n8n workflows for building AI-powered automation agents.

## 📋 Overview

This repository contains 18 n8n workflow templates covering various AI agent use cases including customer service, data processing, RAG (Retrieval-Augmented Generation), social media automation, and more.

## 🚀 Workflows Included

### 🤖 AI Agents
- **Multi_Tool_AI_Agent_With_Memory.json** - Multi-tool AI agent with calculator, SerpAPI, and conversation memory
- **Webhook_AI_Chat_Agent.json** - Simple webhook-based AI chat agent
- **Web_Chat_Agent_With_MCP.json** - Web chat agent with MCP client and MongoDB memory
- **WhatsApp_MCP_Client_Chatbot.json** - WhatsApp chatbot using MCP client

### 📧 Communication & Email
- **Email_Processing_With_AI_Reply_Draft.json** - Processes unread emails and generates AI reply drafts
- **Lab_Chat_Agent_With_Email_Notification.json** - Lab chat agent with email notifications

### 🎯 Customer Service
- **Customer_Feedback_Classification_Agent.json** - Classifies customer feedback (complaint/compliment/feature request) and routes to Airtable

### 🔍 RAG & Knowledge Management
- **RAG_Agent_Google_Drive_Indexer.json** - RAG agent that indexes Google Drive files to Pinecone vector store
- **RAG_Agent_Question_Answering.json** - RAG-based Q&A agent using Pinecone vector store

### 📊 Data Processing
- **Customer_Data_Processing_Google_Sheets.json** - Processes customer data from Google Sheets with country filtering
- **Twitter_Search_Agent.json** - Twitter search agent that stores results in Airtable

### 🛠️ Tools & Integrations
- **MCP_Server_Gmail_Tools.json** - MCP Server with Gmail send/get message tools
- **Recipe_Generator_Agent.json** - AI recipe generator with structured JSON output
- **Team_Form_Submission_With_Poem_Generator.json** - Form submission workflow with profession-based rating and AI poem generation

### 📝 Templates (Empty Workflows)
- **Empty_Workflow_Basic2.json**
- **Empty_Workflow_Rag_Agent_1.json**
- **Empty_Workflow_AI_Voice_Agent.json**
- **Empty_Workflow_MCP_Server_2.json**

## 🛠️ Prerequisites

- [n8n](https://n8n.io/) installed and running
- Required n8n credentials configured:
  - Google Gemini API
  - Gmail OAuth2
  - Airtable Personal Access Token
  - WhatsApp API
  - MongoDB (for memory)
  - Pinecone API (for vector stores)
  - OpenRouter API (optional)
  - SerpAPI (optional)

## 📥 Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/n8n-ai-agents-workflows.git
cd n8n-ai-agents-workflows
```

2. Import workflows into n8n:
   - Open n8n UI
   - Go to Workflows → Import from File
   - Select the JSON file you want to use
   - Configure credentials as needed

## 🔧 Configuration

Each workflow may require specific credentials and configuration:

- **API Keys**: Set up in n8n credentials section
- **Webhooks**: Update webhook URLs if needed
- **Database Connections**: Configure MongoDB, Airtable, etc.
- **Vector Stores**: Set up Pinecone indexes for RAG workflows

## 📚 Usage Examples

### Customer Feedback Agent
1. Import `Customer_Feedback_Classification_Agent.json`
2. Configure Gmail, Airtable, and Slack credentials
3. Set up form trigger webhook
4. Test with sample feedback

### RAG Agent
1. Import `RAG_Agent_Google_Drive_Indexer.json`
2. Configure Google Drive and Pinecone credentials
3. Set up the folder to watch
4. Files will be automatically indexed when added

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.



