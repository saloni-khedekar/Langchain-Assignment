# Langchain-Assignment

Assignment: Character Information Extraction
Objective:
Develop a Python script to extract structured details about characters from narrative stories using LangChain and embeddings. The structured output should follow a specified JSON format, and the solution should include a functional demo.

Deliverables:
CLI Commands Implementation:

compute-embeddings:
Inputs: All story files.
Outputs: Persist embeddings into a local vector database.
get-character-info:
Input: Character name.
Output: JSON object containing:
name: Character’s name.
storyTitle: Title of the story where the character appears.
summary: A brief summary of the story focusing on the character.
relations: List of relationships with other characters (e.g., name, relation type).
characterType: Character’s role (e.g., protagonist, villain).
Edge Case Handling:

Gracefully manage cases where:
The character name isn’t found.
Story data is malformed or missing.
Development Environment:

Programming Language: Python or JavaScript.
Libraries:
LangChain for embedding and vector database operations.
MistralAI for character info processing.

Steps to Approach:
Data Preparation:

Extract and organize files from langchain-assignment-dataset-main.zip.
Familiarize yourself with the dataset structure and sample stories.
Embedding Computation:

Use LangChain to compute and persist embeddings.
Implement vector database operations to store these embeddings.
Character Query Implementation:

Design and test the logic to fetch details based on a character’s name.
Ensure efficient retrieval using embedding-based similarity.
Demo Setup:

Write a detailed walkthrough in the README.md file.
Test the commands end-to-end for accuracy and reliability.
Edge Case Testing:

Simulate scenarios with invalid inputs and unexpected data.
