<h1>🤖 AI Automation</h1>

**AI automation** is the use of artificial intelligence to automate tasks and processes that would typically require human intelligence. It combines AI technologies like machine learning and natural language processing with automation to perform intelligent actions, analyze data, and make decisions, going beyond traditional rule-based automation. This approach improves efficiency, accuracy, and productivity, allowing human workers to focus on more strategic work.

In this repository, i will talk about what and why i learn about AI automation and how can you easily implement it in your daily life as well.

<br>

## 👨‍💻 Introduction

Sending custom messages to anyone, emails, posts and so on tasks can be automate with the help of some tools. In this repo, I will talk about **n8n** which is an automation platform were you can create your own easy and simple automation without coding.

As by using this, you dont have to waste much of your time in deployment as it can be reused easily and modified as per users need. So i highly recommend it to you. In here, your **Visualization** matters 😎

<br>

## <img src="https://n8n.io/brandguidelines/logo-white.svg" width="150">

**n8n** is an open-source, low-code workflow automation tool that helps users connect applications and services to automate repetitive tasks. It uses a visual, node-based interface for building workflows, but also allows for custom code, making it flexible for both non-technical and technical users.


Its full form is **"Nodemation"** and there are 8 letters seperating n from n so n8n i dont care thats how it was named thats all.

## 🔃 Installation 

**Disclaimer**: You can use n8n from the their official website https://n8n.io/ but i wanted to try a different approach so please take a note of it:

- Downlaod <a href="https://www.docker.com/products/docker-desktop/">**Docker Desktop**</a> from there official website. Download as per your device requirements from it.
- After installing docker, go to the Image tab and search for n8n, go for the n8n/latest one and download it.
- Also after downloading, enter your folder directory were you want to store all your n8n workflows carefully.
- Go to the Container tab and there you can see your n8n is ready is deploy easily.
- Run the command and create your personal account in it and you are good to go.
- Then you can successfully run your workflows effortlessly.

Here, the youtube link is provided if you have any additional queries ---> https://youtu.be/1QR-fz-JCA4

Now i am going to show some of my workflows to you which i am working on.

<br>

## 🏃‍♂️‍➡️ Workflows 

<h2>→ AI ChatBot</h2>

An **AI chatbot** is a software program that uses artificial intelligence, specifically natural language processing (NLP) and machine learning (ML), to simulate human conversation and respond to user inquiries in real time.

This is one of my first workflows that I created the reason of this is that i can easily deploy my AI agents very easily in any of my projects or websites. Its super easy to understand and you just to insert your API key inside the credientials (if you have more API keys its recommended that you create new credentials)

The below is the visual representation: 

<img src="images/AI%20Chatbot.png" width="500">

You can chat with it seamlessly and you would just need to put the URL from the "When chat message is received" just double click it and you can easily deploy it in any HTML or python code.

It creates a small chat icon in the right bottom corner of your front page.

<br>

<h2>→ MCP Server</h2>

An **MCP server** is a program that acts as a backend for the Model Context Protocol (MCP), enabling AI agents to access external tools and data. It provides the AI with up-to-date information, such as business software, APIs, and knowledge bases, which helps make its responses more accurate and reduces "hallucinations".

<img src="images/MCP%20Server.png" width="600">

In the above workflow, i have actually used a firecrawl as my MCP server, the other alternatives are brave browser's MCP server. Every MCP server has there respected API key, so put it as per. 

<br>

<h2>→ RAG Agent</h2>

RAG, or Retrieval-Augmented Generation, is an AI technique that enhances large language models (LLMs) by first retrieving relevant information from external sources and then using that information to generate a more accurate and up-to-date response. It combines the strengths of a retrieval system (to find data) and a generative model (to create text).

How RAG works:

- **Retrieval**: When a user asks a question, a retriever component searches an external knowledge base (like documents, databases, or the internet) for relevant information.
- **Augmentation**: The retrieved information is then combined with the original user prompt, creating an "augmented" prompt.
- **Generation**: This augmented prompt is passed to an LLM, which uses both the original context and the newly retrieved data to generate a comprehensive and factually grounded response. 
  
<img src="images/File%20Uploading%20to%20Pinecone%20via%20Drive.png" width="600"> <img src="images/Analyzing%20the%20File%20For%20Chatting.png" width="600">
<img src="images/Full%20Workflow%20Of%20RAG%20Agent.png" width="600">
