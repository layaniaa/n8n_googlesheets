This repository contains an automated workflow built with n8n that implements an intelligent AI Agent. The agent utilizes the Llama 3.2 model (via Ollama) to interact with users through a chat interface.

The agent is equipped with a specific tool that allows it to interact with Google Sheets directly. When the agent identifies relevant information (mapped as layan1 through layan4), it automatically appends it as a new row in a designated spreadsheet.

Key Features:

Local LLM Integration: Powered by Ollama for enhanced privacy and local execution.

Dynamic Data Logging: Automatically extracts and logs data to Google Sheets.

Context Awareness: Uses a memoryBufferWindow to maintain a conversation history of up to 10 messages.

No-Code/Low-Code: Built entirely using n8n nodes for easy scalabilit
