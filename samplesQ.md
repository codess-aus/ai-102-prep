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
https://learn.microsoft.com/en-us/training/modules/explore-models-azure-ai-studio/3-deploy-model 

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

Using your data with Azure OpenAI Service - Azure OpenAI | Microsoft Learn



</details>
