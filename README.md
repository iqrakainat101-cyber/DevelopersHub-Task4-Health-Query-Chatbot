# General Health Query Chatbot

## Project Overview

This project was developed as part of the AI/ML Engineering Internship at DevelopersHub Corporation.

The chatbot uses Google's Gemini Large Language Model (LLM) to answer general health-related questions while following safety guidelines to prevent harmful medical advice.


## Objective

To build a health query chatbot capable of:

- Answering general health-related questions
- Providing educational health information
- Using prompt engineering techniques
- Implementing safety filters to prevent medical diagnosis and prescription recommendations


## Technologies Used

- Python
- Google Colab
- Google Gemini API
- Prompt Engineering
- Generative AI


## Model Used

Gemini 2.5 Flash


## Features

### Health Information Support

The chatbot can answer general health-related questions such as:

- What causes a sore throat?
- Is paracetamol safe for children?
- What are symptoms of dehydration?

### Prompt Engineering

The chatbot is instructed to:

- Act as a helpful medical assistant
- Provide educational information only
- Use simple and friendly language
- Encourage consultation with healthcare professionals

### Safety Filtering

The chatbot blocks harmful requests involving:

- Medical diagnosis
- Prescriptions
- Dosage recommendations
- Dangerous medical advice

Example:

User Input:

Which medicine should I take for chest pain?

Response:

Safety Notice:
I cannot provide medical diagnosis, prescriptions, treatment plans, or advice that could be harmful.
Please consult a qualified healthcare professional.


## Project Workflow

1. Install required libraries
2. Configure Gemini API
3. Create safety filter
4. Design prompt template
5. Send user query to Gemini
6. Generate safe health-related responses
7. Display chatbot responses


## Screenshots

The repository includes screenshots demonstrating:

- Chatbot startup screen
- Sore throat query
- Paracetamol query
- Dehydration query
- Safety filter functionality
- Final project summary


## Limitations

- Does not diagnose diseases
- Does not prescribe medications
- Does not provide treatment plans
- Does not replace professional medical advice


## Conclusion

The chatbot successfully answers general health-related questions using Gemini 2.5 Flash while maintaining safe and responsible AI behavior through prompt engineering and safety filtering.
