Make publicly accessible AI Search index of prompting-docs

Testing the pgvector labs from:
https://microsoftlearning.github.io/mslearn-postgresql/Instructions/Labs/13-generate-vector-embeddings-azure-openai.html
Using student1-X@cobbinfotech.com

 - Integrate slides from PDFs and https://docs.google.com/presentation/d/1YlhOFJYu-bUSxHrFq666btmwfenHI6E-/edit
 - add postgres python rag app like https://github.com/levi-katarok/simplified-rag?tab=readme-ov-file#project-structure?

 - add azure sql content like: https://github.com/Azure-Samples/azure-sql-db-vector-search/blob/main/RAG-with-Documents/.env.sample

 - need deployed shared resources openai, doc intelligence, etc

 - review slides pdfs for slide & content

 - include content from each relevant chapter from here:
 https://microsoftlearning.github.io/mslearn-postgresql/
 Explore Generative AI with Azure Database for PostgreSQL	Explore the Azure AI Extension
Enable Semantic Search with Azure Database for PostgreSQL	Generate vector embeddings with Azure OpenAI
Enable Semantic Search with Azure Database for PostgreSQL	Create a search function for a recommendation system
Summarize data using Azure AI Services and Azure Database for PostgreSQL	Perform Extractive and Abstractive Summarization
Perform Sentiment Analysis and Opinion Mining using Azure Database for PostgreSQL	Analyze Sentiment
Extract insights using the Azure AI Language service with Azure Database for PostgreSQL	Extract insights using the Azure AI Language


- include foundry? for each student?
- installed foundry resource, grant student#

- Key topics to share
  - struggle to keep up, adapt when things break or change
  - communicate early & often, don't go it alone
  - learning is process not a one time event, how can we support the learning process?
  - sharing the learning rather than having all the answers
  - tech choices: azure, postgres, python, vscode, notebooks, repos
  - teaching & learning  from reading and running (and debugging) code 

  create permissions for student1 to access foundry:
  az role assignment create --assignee student1@cobbinfotech.com --role 'Azure AI project manager' --scope /subscriptions/7e9d5674-acf4-4b95-8259-a0cdf6a4597f/resourceGroups/rg-student1-learn-postgresql-ai-eastus

  From management center, added existing azure openai resource

Need slides to support Azure AI Foundry labs, AI Search

run zoom meeting to share screen up from if needed


Events with new people and content need to be as simple as possible (pre-provisioned labs) As the skill level and familiarity of the team grows, the requirements on the user can increase and still have successful event.