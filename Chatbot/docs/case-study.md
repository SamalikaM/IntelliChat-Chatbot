# Portfolio Case Study: SafeX AI FAQ Assistant

## Project summary

I built a deployable FAQ chatbot prototype for SafeX Solutions that helps website visitors ask questions about company services, AI chatbot automation, cybersecurity, web development, digital marketing, creative media, and training programs.

## Problem

Technology service websites often receive repeated questions such as:

- What services do you offer?
- Can you build an AI chatbot?
- Do you provide cybersecurity support?
- How can I contact the company?

Answering these manually can slow down lead response time. A small AI assistant can give visitors instant first-level answers and guide them toward official contact channels.

## Approach

I used public SafeX website content as the knowledge base and built a lightweight retrieval model using TF-IDF and cosine similarity. When a user asks a question, the chatbot converts the question and knowledge entries into weighted token vectors, finds the closest matching entry, and returns a grounded answer with source links.

This approach was selected because it is transparent, inexpensive, easy to deploy, and does not require a paid API key.

## Tools used

- Python
- FastAPI
- TF-IDF retrieval
- HTML, CSS, and JavaScript
- Render deployment configuration

## Prototype behavior

The chatbot can answer questions about:

- SafeX services
- AI chatbot automation
- Cybersecurity
- Web development
- Digital marketing
- Creative media production
- SafeX training programs
- Contact guidance

If the model cannot find enough relevant information, it avoids guessing and asks the user to try a SafeX-related question.

## Results

The prototype delivers:

- A working chat interface
- A backend API endpoint for chatbot responses
- Source links for grounded answers
- A deployment-ready project structure
- A simple AI/ML method that can be explained clearly in an internship portfolio

## Future improvements

- Expand the knowledge base after SafeX reviews official service details
- Add analytics for the most common visitor questions
- Add admin editing for FAQ entries
- Upgrade retrieval with embeddings for better semantic matching
- Add lead capture when users ask pricing or project-scope questions

## Conclusion

This project demonstrates a practical AI/ML prototype for a real company context. It is small enough to build and deploy quickly, but useful enough to show business value: faster visitor support, clearer service discovery, and a foundation for more advanced automation.
