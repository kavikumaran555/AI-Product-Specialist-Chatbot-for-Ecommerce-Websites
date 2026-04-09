# AI-Product-Specialist-Chatbot-for-Ecommerce-Websites

## Project Overview ##
This project is AI product Specialist chatbot for users to ask questions about different products and get details about products.

## Use Case: ##
E-commerce websites to understand products
Customer support systems for product inquiries
Online shopping assistants
Retail automation systems
suggesting product based on customer need.

![Output](https://github.com/kavikumaran555/AI-Product-Specialist-Chatbot-for-Ecommerce-Websites/raw/main/Ai%20chat%20product%20specialist%20Output%20image.JPG)

## Libraies Used: ## 
sentence-transformers, scikit-learn, numpy, pandas, ipywidgets, IPython

## Model used: ##
all-MiniLM-L6-v2 (Sentence Transformer)

## technique used: ##
sentence embeddings, semantic search, cosine similarity, keyword intent detection, threshold-based retrieval

## Algorithm: ##
1. Import required libraries.
2. Load the sentence transformer model.
3. Create product dataset (product + description).
4. Store dataset in pandas dataframe.
5. Combine product name and description.
6. Convert combined text into embeddings using the model.
7. Create chat interface using ipywidgets.
8. User enters a message.
9. Convert user message to lowercase.
10. Check special keywords (like, greeting, courtesy, goodbye).
11. Convert user query to embedding.
12. Calculate cosine similarity with product embeddings.
13. Find the highest similarity score.
14. If score >= threshold (0.20), return matching product description.
15. If greeting detected, return greeting response.
16. If courtesy detected, return courtesy response.
17. If goodbye detected, return closing response.
18. If nothing matches, return fallback message.
19. Display user message and bot response in chat window.
