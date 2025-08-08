# AI-Report-Generator

An intelligent AI agent that generates **factual, structured research reports** on any topic using real-time web search and memory-based document retrieval (RAG). Build using OpenAI, LangChain, and vector databases.

---

## Features

- **System + User Prompting**: Custon roles for factual and well-structured outputs
- **Tuning Parameters** : Adjust temperature, max tokens, etc.
- **Structured Output**: Markdown reports with Summary, Key points, and References
- **Function Calling**: Uses APIs to search the web and fetch content
- **RAG (Retrieval-Agumented Generation)**: Retrieves relevant documents from stored memory to enrich responses

---

## Example Use Case

> User Prompt:
> Generate a report on the impact of electric vehicles on the environment.

Output
```markdown
# Environmental Impact of Electric Vehicles

## Summary
Electric vehicles (EVs) significantly reduce greehouse gas emissions, especially When powered by clean energy sources.  Their adoption is key to sustainable transport.

## Key Points
- EVs reduce tailpip emissions by 100%
- Battery production has environmental costs, but lower than fossil fuel lifecycle
- Governments worldwide incentiveze EV adoption for climate goals

## References
-[1] IEA Report
-[2] Nature Journal 2023 
