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

**❗Disclaimer**: You can use n8n from the their official website https://n8n.io/ but i wanted to try a different approach so please take a note of it:

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

<table><tr><td><img src="images/AI%20Chatbot.png" width="500"></td></tr></table>

You can chat with it seamlessly and you would just need to put the URL from the "When chat message is received" just double click it and you can easily deploy it in any HTML or python code.

It creates a small chat icon in the right bottom corner of your front page.

Download Link ⇉ [AI ChatBot](https://github.com/Percedal15019/AI-Automation/blob/main/workflow/Chatbot.json)   

<br>

<h2>→ MCP Server</h2>

An **MCP server** is a program that acts as a backend for the Model Context Protocol (MCP), enabling AI agents to access external tools and data. It provides the AI with up-to-date information, such as business software, APIs, and knowledge bases, which helps make its responses more accurate and reduces "hallucinations".

How MCP Server Works: 
1. **User Request**: A user asks the AI something requiring external info (e.g., "What's todays weather ?").
2. **Client Encodes Request**: The MCP client in the Host structures this into an MCP request.
3. **Server Identification**: The client/host determines which server (e.g., a financial API, weather API) has the capability.
4. **Tool Discovery**: The client asks the server what it can do, receiving a list of tools (e.g., run_query(sql_string)).
5. **Data Fetch**: The client sends a request to the server to use a tool (e.g., run a SQL query).
6. **Context & Response**: The server performs the action, gets data (e.g., revenue numbers, weather report), and sends it back as structured context to the client.
7. **LLM Generates Answer**: The Host's LLM uses this real-time data (not just its training) to generate an accurate response for the user. 

<br>

<table><tr><td><img src="images/MCP%20Server.png" width="600"></td></tr></table>

In the above workflow, i have actually used a [Firecrawl](https://www.firecrawl.dev/) as my MCP server, the other alternatives are [Brave Search API](https://brave.com/search/api/) which works the same. Every MCP server has there respected API key, so put it as per. 

Download Link ⇉ [MCP Server](https://github.com/Percedal15019/AI-Automation/blob/main/workflow/MCP-Server.json)   

<br>

<h2>→ Web Search</h2>

A Web Search Engine is a software system that helps users find information on the World Wide Web by indexing content and returning a list of relevant results for a user's query. It works by using automated programs called crawlers or spiders to discover and index web pages, then using algorithms to rank the pages based on relevance, quality, and other factors to present the most useful results to the user. Examples of popular search engines include Google, Bing, and Yahoo.

Web search using Large Language Models (LLMs) is an advanced approach where AI systems leverage their natural language understanding capabilities to interpret user intent, retrieve information from the web (often in real-time), and synthesize a direct, conversational answer, rather than simply providing a list of links. 

<table><tr><td><img src="images/Web%20Search%20Using%20Perplexity.png" width="600"></td></tr></table>















<h2>→ RAG Agent</h2>

RAG, or Retrieval-Augmented Generation, is an AI technique that enhances large language models (LLMs) by first retrieving relevant information from external sources and then using that information to generate a more accurate and up-to-date response. It combines the strengths of a retrieval system (to find data) and a generative model (to create text).

How RAG works:

- **Retrieval**: When a user asks a question, a retriever component searches an external knowledge base (like documents, databases, or the internet) for relevant information.
- **Augmentation**: The retrieved information is then combined with the original user prompt, creating an "augmented" prompt.
- **Generation**: This augmented prompt is passed to an LLM, which uses both the original context and the newly retrieved data to generate a comprehensive and factually grounded response.

The following are the images of the Fully Understanding and Reliable RAG Agent which will help you anytime:

<br>  

<table>
  <tr>
    <td align="center"><b>Automated RAG Pipeline: Google Drive to Pinecone</b></td>
    <td align="center"><b>Context-Aware Support Agent</b></td>
  <tr>
    <td><img src="images/File%20Uploading%20to%20Pinecone%20via%20Drive.png" width="800" /></td>
    <td><img src="images/Analyzing%20the%20File%20For%20Chatting.png" width="800" /></td>
  </tr>
</table>   

<br>

From the First Part, we have understand that: 

1. **The Trigger (Start):**

- Node: When clicking 'Execute workflow'
- Function: This is a manual trigger. The process starts only when a user explicitly clicks the "Test" or "Execute" button in the n8n interface.

2. **The Data Source:**

- Node: Download files From Drive (Google Drive)
- Function: It connects to Google Drive to download a specific file. This acts as the raw knowledge source for your AI.

3. **The Storage Destination:**

- Node: <a href="https://www.pinecone.io/">**Pinecone Vector Store**</a> 
- Function: This is the core "sink" where data ends up. Pinecone is a popular vector database used to store high-dimensional data (vectors) that represent the meaning of text.

<br>

From the Second Part, we have understand that:

1. **Trigger (When chat message received):**
   
- The workflow initiates whenever a user sends a message.

2. **The Core Brain (AI Agent):**

- This central node orchestrates the logic. Instead of just answering blindly, it uses connected "peripherals" (tools and memory) to formulate a smart response.

3. **Knowledge Base (Vector Store Tool):**

- The agent is equipped with a tool to "look up" information.
- It uses Pinecone, a popular vector database, to store and retrieve knowledge that the LLM wasn't trained on (e.g., your specific company data or documents).
  
4. **Memory (Window Buffer Memory):**
   
- The agent isn't amnesiac; it remembers the context of the current conversation (a "window" of recent messages), allowing for back-and-forth dialogue rather than just one-off Q&A.

<br>

And finally it looks like this at the end: 

<br>

<table>
  <tr>
    <td align="center"><b>RAG-Enhanced AI Chatbot Workflow </b></td>
    <tr>
    <td><img src="images/Full%20Workflow%20Of%20RAG%20Agent.png" width="1000"></td>
  </tr>
</table>

<br>

Download Link ⇉ [RAG Agent](https://github.com/Percedal15019/AI-Automation/blob/main/workflow/Talk%20with%20your%20Drive%20folder%20RAG.json)   

<br>

**🔴 NOTE:**

1. From the first stage, we can see that I have used Google drive as my uploading tool, it requires you to have a client id and client secret which can be found in <a href="https://cloud.google.com/">**Google cloud**</a>.

2. You have to login in with the account you are currently in with n8n. And then go to Clients tab and fill the required details and get your client id and secret. (Here is the link for step-by-step setup ——> https://www.youtube.com/watch?v=CdssoZAslq0 )

3. Also copy and paste the secret somewhere safe first.

4. Connect your pinecone account using its API Key and put the embedding model.

5. If you have <a href="https://openai.com">**OpenAI’s API Key**</a> then use embedding small model in pinecone and same in n8n as well. I chose ollama because I don’t like openAI at all and its free plan is the worst. But <a href="https://ollama.com">**Ollama**</a> is GOATed because of it runs locally so I will recommend it (but if you have OpenAI’s API Key then use it.

6. Also I will recommend using <a href="https://openrouter.ai">**OpenRouter**</a> as with only one API Key you can access many different free AI models easily and no need to sign in for different AI models.

<br>

## References

I will add more workflows in the future as i am working on them. Here are some links which would help you in your AI Automation Journey as well: 

- [Zie619 Workflows](https://github.com/Zie619/n8n-workflows)
- [Nate Herk](https://www.youtube.com/@nateherk)
- [Zero2Launch](https://github.com/Zero2Launch)
- Also a huge help from the official <a href="https://n8n.io/">n8n</a> website as they have a great community and research papers regarding the topics.

