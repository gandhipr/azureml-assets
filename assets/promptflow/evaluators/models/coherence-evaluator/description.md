| 	| |
| -- | -- |
| Score range |	Integer [1-5]: 1 is the lowest quality and 5 is the highest quality. |
| What is this metric? | Measures how well the language model can produce output that flows smoothly, reads naturally, and resembles human-like language. |
| How does it work? | The coherence metric is calculated by instructing a language model to follow the definition (in the description) and a set of grading rubrics, evaluate the user inputs, and output a score on a 5-point scale (higher means better quality). Learn more about our [definition and grading rubrics](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in?tabs=warning#ai-assisted-coherence).  |
| When to use it? |	The recommended scenario is generative business writing such as summarizing meeting notes, creating marketing materials, and drafting email. |
| What does it need as input? |	Query, Response |
