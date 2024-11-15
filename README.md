Inspiration for this project is that people often have few minor symptoms they are facing, while they doesn't want to visit doctor directly they may go to search engines to get any info. The most of the top suggestions suggested by these search engines are very much categorized to dangerous disease which may worry user. My application was specifically designed to address this issue.
## What it does
The application considers the users symptoms and predicts most likely disease from it. It also provides additional symptoms that user can counter verify if they have these additional symptoms or not. Finally our application provides remedies for temporary relief for the user's symptoms. The other thing it is capable of is it can handle queries that requires latest medical treatments.

## How we built it
I have considered Gemma 2B- It model from hugging face for this which was designed by google. I have compressed the model using OpenVino and converted the model into OpenVino IR. I have considered 2 Precision models for processing query based on the intent of the user's prompt. For the RAG approach I have utilized PubMed search which can help in providing latest and up to date information in medical.
I have considered intent based classification for user's input which helps to make efficient handling of user's request. Finally for chatbot I have used Gradio which can launch the application through Jupyter notebook and deployed through OpehShiftAI environment
