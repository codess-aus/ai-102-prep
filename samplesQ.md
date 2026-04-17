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
