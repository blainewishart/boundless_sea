
## Loosely formulated question

1. What factors should I consider when comparing 
  1. use of prompts in chat 
  2. use of language model's API 
  2. developing from the ground up with models like T5-base?

### Chat told me:
"When comparing the use of prompts in chat, the use of language model's API, and developing from the ground up with models like T5-base, there are several factors to consider.

Accuracy: Consider which approach provides the most accurate results for your use case. The accuracy of a language model can depend on various factors such as the size of the model, quality and quantity of training data, and fine-tuning of the model.

Cost: Cost is another important consideration. Developing from the ground up with models like T5-base can be time-consuming and costly. On the other hand, using language model's APIs or pre-trained models can be more cost-effective, but may come with limitations and pricing models.

Flexibility: The level of flexibility needed to customize the language model also needs to be considered. Building from the ground up allows for more customization, while APIs and pre-trained models provide pre-defined functionalities that may be sufficient for certain applications.

Maintenance: Finally, the cost and effort of maintaining and updating the language model over time should also be considered. This includes factors such as how frequently the model will be used, the resources required to keep the model up-to-date, and the ability to scale up or down the infrastructure.

Overall, the choice between using prompts in chat, language model's API, or developing from the ground up with models like T5-base would depend on the specific requirements of the use case, available resources, and other factors like accuracy, cost, flexibility, and maintenance.

## Current thoughs

Prompt engineering will often be a good way to explore.
Use of web APIs like Cohere will often be a good way to go further and to get a feel for the parameters.
The price of GPUs is dropping. Lambda and others have prices far below Microsoft, Google, etc.
Especially for firms with many local docs, on-prem machines from Lambdsa or Mac Minis may change the economics of processing many docs.

### If I had thousands of docs, I'd want 
1. a similarity graph
2. a NER outline and similarity graph
3. summaries
   1. combine some highly similar docs into one or a few using an API like langchain or a local application (most likely, I think)
4. A cost benefit analysis of moving from 1000 to 300 docs
