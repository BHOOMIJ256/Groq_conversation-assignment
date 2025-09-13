# Conversation Management & Classification using Groq API

A comprehensive implementation demonstrating conversation management with intelligent summarization and structured information extraction using Groq's API with OpenAI SDK compatibility.

* **Conversation Management**: Smart truncation and periodic summarization of chat history
*  **Information Extraction**: JSON schema-based extraction of user details from conversations

## Task 1: Conversation Management

1. Flexible Truncation: Limit by turns count or character length
2. Periodic Summarization: Auto-summarize after every k exchanges using Groq AI
3. Multiple Configurations: Test different settings simultaneously
4. Conversation Statistics: Track turns, characters, and summaries

## Task 2: Information Extraction

1. Structured Extraction: Extract 5 key fields (name, email, phone, location, age)
2. OpenAI Function Calling: Uses Groq's function calling capability
3. Schema Validation: Validates extracted data against JSON schema
4. Error Handling: Comprehensive validation with warnings and errors

## Technical Stack

* API: Groq API with OpenAI SDK compatibility
* Model: llama-3.1-8b-instant (production-ready)
* Language: Python 3.7+
* Libraries: openai, standard Python libraries only
* Platform: Google Colab compatible

## Task 1 Output

1. Tests 3 different truncation configurations
2. Shows conversation history management
3. Demonstrates periodic summarization
4. Displays statistics and metrics

## Task 2 Output

1. Processes 3 sample chat conversations
2. Extracts structured information
3. Validates against JSON schema
4. Shows extraction accuracy
