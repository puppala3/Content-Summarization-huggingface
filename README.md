# Content-Summarization-huggingface
This project is an end-to-end Generative AI application that summarizes content from YouTube videos or websites using LangChain and Hugging Face's language models. The main features include:
A Streamlit-based user interface that allows users to input a URL (YouTube video or website) and receive a summary.
Integration with Hugging Face's Mistral-7B-Instruct-v0.3 model for text generation and summarization.
Ability to handle both YouTube videos and general website content using appropriate loaders (YoutubeLoader and UnstructuredURLLoader).
A customizable prompt template that instructs the model to provide a 300-word summary of the input content.
Error handling and input validation to ensure proper URL format and API key provision.
Use of LangChain's summarization chain to process and summarize the loaded content.
The application is built using Python and relies on several key libraries including Streamlit for the frontend, LangChain for AI chain operations, and various document loaders for content extraction. It demonstrates the practical application of large language models in creating useful tools for content summarization, making it easier for users to quickly grasp the main points of lengthy videos or articles.
