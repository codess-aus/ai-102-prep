## You are creating an assistant based on a generative Microsoft Foundry model.

You plan to use the system message component for prompts in the solution.

Which two capabilities does the system message offer for the model? Each correct answer presents part of the solution.

Select all answers that apply.

- defines the data sources that should not be included in the model
- defines what the model should and should not do
- detects which language is being used in a prompt
- helps define the assistant’s personality

<details>
  <summary><strong>The correct answers are:</strong></summary>

  - ✅ defines what the model should and should not do
  - ✅ helps define the assistant’s personality

  <!-- Context:
  - <summary> is the clickable line with the arrow.
  - Everything inside <details> stays hidden until expanded.
  - The blank line after </summary> helps GitHub render the markdown inside consistently.
  -->
</details>

## Your organization is developing an AI-powered application using Azure OpenAI in Foundry Models.

You need to choose a model for text generation.

What should you recommend?

Select only one answer.

- Azure Vision in Foundry Tools
- Code-Davinci-003
- DALL-E
- GPT-4

<details>
  <summary><strong>The correct answers are:</strong></summary>

  - ✅ GPT4

Azure Vision in Foundry Tools is designed for analyzing visual content and does not support text generation, making it unsuitable for the scenario. Code-Davinci-003 is optimized for code generation tasks and lacks the capabilities required for text generation, which disqualifies it as a viable option. DALL-E specializes in generating images from textual descriptions and does not meet the requirement for text generation. GPT-4, on the other hand, is specifically designed for generating detailed and contextually accurate text responses, making it the most appropriate choice for the given requirement.

</details>

## Your organization plans to deploy a generative AI solution using Azure OpenAI in Foundry Models with GPT-4 for natural language responses.

You need to ensure GPT-4 is available for inferencing via an endpoint.

Which three actions should you perform to achieve this goal? Each correct answer presents part of the solution.

Select all answers that apply.

- Create a new Azure subscription.
- Deploy a GPT-4 model
- Provision a Microsoft Foundry resource.
- Select GPT-4 from the catalog.
- Set up a virtual machine.
- Use DALL-E.

<details>
  <summary><strong>The correct answers are:</strong></summary>

  - ✅ Deploy a GPT-4 model
  - ✅ Provision a Microsoft Foundry resource.
  - ✅ Select GPT-4 from the catalog.

To deploy GPT-4 for inferencing, provisioning Microsoft Foundry resource is essential to establish the infrastructure. Selecting GPT-4 from the catalog ensures the correct model is chosen for the intended use case. Deploying GPT-4 to an endpoint makes it accessible for inferencing, completing the deployment process. Setting up a virtual machine is unnecessary because Microsoft Foundry uses managed endpoints. Creating a new Azure subscription is irrelevant if an existing subscription is available. Using DALL-E is incorrect because it is designed for image generation rather than natural language processing.
[Deploy a Model](https://learn.microsoft.com/en-us/training/modules/explore-models-azure-ai-studio/3-deploy-model) 

</details>

## You are building a GPT-based chat application that will answer questions about your company.

You plan to use the Using your data feature in Azure OpenAI to ground the model with your company data.

While testing, you discover that some responses are not accurate enough.

You need to configure the Azure OpenAI resource to filter out less-relevant documents for responses.

Which parameter should you configure?

Select only one answer.

- Content data
- File name
- Retrieved documents
- Strictness

<details>
  <summary><strong>The correct answers are:</strong></summary>

  - ✅ Strictness

The Strictness parameter sets the threshold to categorize documents as relevant to your queries. Raising the Strictness parameter value means a higher threshold for relevance and filters out more less-relevant documents for responses. Retrieved documents specifies the number of top-scoring documents from your data index used to generate responses. Content data specifies the fields in your index that contain the main text content of each document. File name specifies the field in your index that contains the original file name of each document.

</details>

## You are building a GPT-based chat application that will answer questions about your company.

You plan to test the application by using strategies defined by Microsoft best practices.

Which three prompt engineering strategies should you consider while testing the application? Each correct answer presents a complete solution.

Select all answers that apply.

- Be Descriptive
- Be minimalistic
- Be simple
- Be Specific
- Order Matters

<details>
  <summary><strong>The correct answers are:</strong></summary>

  - ✅ Be Descriptive
  - ✅ Be Specific
  - ✅ Order Matters

Be Specific means to leave as little to interpretation as possible. Be Descriptive means to use analogies. Order Matters means that the order in which you present information to the model can affect the output. Therefore, those three are valid best practices. Be simple and be minimalistic do not produce the best results and are, therefore, not best practices

[Azure OpenAI Service - Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/en-gb/azure/foundry/openai/concepts/prompt-engineering)

</details>

## Your organization is developing a customer-facing application that uses Azure OpenAI in Foundry Models to generate personalized responses. The application is connected to a Microsoft Azure AI Search index.

You need to configure the application to retrieve relevant data from the search index.

What should you do?

Select only one answer.

- Deploy an additional Azure OpenAI model.
- Enable semantic search.
- Increase chunk size for data ingestion.
- Use keyword search.

<details>
  <summary><strong>The correct answers are:</strong></summary>
  
  - ✅ Enable semantic search.

Enabling semantic search enhances the precision and relevance of search results by interpreting the meaning behind query terms, making it the most suitable solution for improving response accuracy in this scenario. Increasing chunk size impacts data processing but does not directly affect the accuracy of retrieved data. Deploying an additional Azure OpenAI model does not address the specific need for improving data retrieval accuracy from the search index. Using keyword search lacks semantic capabilities, which are essential for achieving the desired level of accuracy.

[Make your data searchable | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/build-copilot-ai-studio/3-search-data)

</details>

## Your company is developing a chatbot using an Azure OpenAI in Foundry Models service to provide answers based on the company's internal knowledge base.

You need to improve the chatbot's ability to retrieve and process information from the knowledge base.

Each correct answer presents part of the solution. Which two actions should you take?

Select all answers that apply.

- Index the knowledge base with AI Search.
- Integrate the Embeddings API.
- Train a custom language model.
- Use AI Vision for document analysis.

<details>
  <summary><strong>The correct answers are:</strong></summary>
  
  - ✅ Index the knowledge base with AI Search.
  - ✅ Integrate the Embeddings API.

Integrating the Embeddings API enhances semantic processing of queries, enabling the chatbot to understand user intent and respond accurately. Indexing the knowledge base with AI Search creates a searchable index, allowing the chatbot to efficiently retrieve relevant information and provide accurate responses. Training a custom language model is unnecessary because pre-trained models like GPT-4 are already optimized for this task and can handle the required functionality without additional training. Using AI Vision for document analysis is not applicable in this scenario because it is designed for image analysis rather than processing textual knowledge base documents.
https://learn.microsoft.com/en-us/training/modules/prepare-azure-ai-development/3-azure-ai-servicesAzure AI services

[Plan and Prepare to Develop AI Solutions | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/prepare-to-develop-ai-solutions-azure/4-understand-considerations-for-ai-engineers)

</details>

## Your organization is using an Azure OpenAI in Foundry Models service for document summarization across various document types.

You need to ensure the AI generates summaries that meet organizational requirements.

What action should you take to achieve this?

Select only one answer.

- Enable diagnostic logging.
- Increase the token limit.
- Refine prompts to specify key details.
- Switch to a higher-cost model.

<details>
  <summary><strong>The correct answers are:</strong></summary>
  
  - ✅ Refine prompts to specify key details.
  
Refining prompts to specify key details ensures the AI model generates concise and relevant summaries, directly addressing the optimization requirement. Enabling diagnostic logging provides insights into system performance but does not impact the quality of generated summaries. Increasing the token limit allows for longer responses but does not inherently improve quality. Switching to a higher-cost model may enhance performance but does not guarantee better summaries without prompt optimization.

[Prompt Engineering Teachniques | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/prompt-engineering?tabs=chat)

</details>

## You use a text-generation model deployed in Microsoft Foundry.

The model produces responses that vary in tone and creativity.

You need to reduce the randomness of the model’s output to make its responses more predictable and consistent.

Which parameter should you configure?

Select only one answer.

- max_tokens
- role
- stop
- temperature

<details>
  <summary><strong>The correct answers are:</strong></summary>
  
  - ✅ temperature.
  
You should configure the temperature parameter because it directly controls the randomness and creativity of a text-generation model’s output in Microsoft Foundry. Lowering the temperature value makes responses more focused, deterministic, and consistent, while higher values increase variability and creativity. The max_tokens parameter only limits the length of the response, the role parameter defines the message author in a chat interaction, and the stop parameter specifies sequences that halt generation rather than influencing randomness or tone.
[Deployment Overview for Foundry Models | Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/prompt-completion)

</details>

## You are building an app that will extract insights from video files.

You need to identify which service to use. The solution must ensure that you can customize the language model used.

What should you use?

Select only one answer.

- Azure Language in Foundry Tools
- Azure Communication Services
- Azure Vision in Foundry Tools
- Azure AI Video Indexer

<details>
  <summary><strong>The correct answers are:</strong></summary>
  
  - ✅ Azure AI Video Indexer
  
The only service that can customize the language model for a solution based on gaining insights from videos in Azure AI Video Indexer.
[Customise a language model in azure video indexer | Microsoft Learn](https://learn.microsoft.com/azure/azure-video-indexer/customize-language-model-overview)

</details>

## You have a Microsoft Foundry service.

You plan to create an agent that will automate the sending of expense report emails to employees. The solution will use multiple types of agents to support the workflow.

You need to create the agent while minimizing administrative effort.

What should you use?

Select only one answer.

- the Azure AI Agent Service SDK
- the Microsoft Foundry portal
- the Microsoft Foundry REST API
- the Microsoft Foundry SDK

<details>
  <summary><strong>The correct answers are:</strong></summary>
  
  - ✅ the Microsoft Foundry portal
  - 
The Microsoft Foundry portal is the best choice because it provides a graphical, no-code interface to create, configure, and test multiple types of agents directly within the Foundry service, which minimizes administrative and development effort. The Microsoft Foundry SDK and Azure AI Agent Service SDK are designed for developers who need programmatic control and advanced orchestration, which increases setup and maintenance overhead, while the Microsoft Foundry REST API requires scripting and endpoint management, making it less suitable when the goal is to quickly create and manage agents with minimal administrative effort.

[Microsoft Foundry Introduction | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/ai-foundry-sdk/01-introduction)

</details>

## You have a Microsoft Foundry service named Foundry1.

You need to deploy a foundation model to Foundry1 that can generate content, summarize text, understand images, perform semantic search, and generate code.

Which model provider should you use?

Select only one answer.

- Cohere
- Meta
- Mistral
- OpenAI

<details>
  <summary><strong>The correct answers are:</strong></summary>
  
  - ✅ OpenAI

OpenAI is the appropriate model provider because Azure OpenAI models available in Microsoft Foundry (such as GPT-4–class models) natively support a broad set of capabilities required by the scenario, including content generation, text summarization, image understanding, semantic search through embeddings, and code generation, all of which can be deployed and managed directly within a Foundry service. Cohere models primarily focus on retrieval-augmented generation and summarization, Meta models emphasize large-scale text generation without integrated multimodal and code features in Foundry, and Mistral models provide strong text reasoning but lack the full multimodal and code-generation support needed to meet all the stated requirements.

[What are Microsoft Foundry Introduction | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/optimize-spend-and-performance-with-azure-ai-foundry-provisioned-reservations/azure-ai-foundry-overview)

</details>

## You are building an app that will identify the core concepts of a document by using Azure AI language.

Which endpoint should you use as part of the solution?

Select only one answer.

- custom Named Entity Recognition (NER)
- key phrase extraction
- the Azure Vision in Foundry Tools API

<details>
  <summary><strong>The correct answers are:</strong></summary>
  
  - ✅ key phrase extraction

You should use the key phrase extraction endpoint.

The custom NER endpoint will not do key phrase extraction and the Azure Vision in Foundry Tools API can be used to process PDF files but not to extract key phrase detection.

[Key Phrase Extraction | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/language-service/key-phrase-extraction/overview)
[Extract Insights | Microsoft Learn](https://learn.microsoft.com/training/modules/extract-insights-text-with-text-analytics-service/)

</details>

## You plan to build an app that will use Microsoft Foundry Service.

You need to identify the methods that can be used to authenticate to Azure AI Services.

Which two methods can you use? Each correct answer presents a complete solution.

Select all answers that apply.

- a SAML token
- a subscription key
- Microsoft Entra ID
- Kerberos

<details>
  <summary><strong>The correct answers are:</strong></summary>
  
  - ✅ a subscription key
  - ✅ Microsoft Entra ID

You can use a single or multi-service subscription keys to authenticate to Azure AI Services. You can also authenticate to Azure AI Services by using a Microsoft Entra ID service principal and role-based access control (RBAC).
Azure AI Services do not support authentication by using SAML tokens or Kerberos.

[Authentication | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/authentication?tabs=powershell#authenticate-with-an-access-token)

</details>

## You are building an app that will use Azure AI Custom Vision. The app will be deployed to a virtual machine in Azure.

You enable firewall rules for your Azure AI Services account.

You need to ensure that the app can access the service through a service endpoint.

What should you do?

Select only one answer.

- Assign a role-based access control (RBAC) role to the Azure AI Custom Vision resource.
- Grant access to a specific virtual network.
- Grant access to an internet IP range.
- Include an access token in the Authorization header.

<details>
  <summary><strong>The correct answers are:</strong></summary>
  
  - ✅ Grant access to a specific virtual network.

If you enable the firewall for the Azure AI Services account, you need to allow network access to the service. You can achieve this by either allowing access from a specific virtual network or adding an IP range to the firewall rules. In this situation, the app is deployed to a virtual machine in Azure, which resides in a virtual network. You can provide access to virtual networks in Azure to access specific service endpoints.

[Configure VNs | Microsoft Learn](https://learn.microsoft.com/azure/cognitive-services/cognitive-services-virtual-networks?context=%2Fazure%2Fcognitive-services%2Fcustom-vision-service%2Fcontext%2Fcontext&tabs=portal)

</details>
