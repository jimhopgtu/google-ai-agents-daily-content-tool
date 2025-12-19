# google-ai-agents-daily-content-tool
🤖 Daily AI News Agent for Analytics Leaders
Automated Intelligence Curation from Search to Obsidian

Notebook:  https://colab.research.google.com/drive/1pBJ6pTocQJUuwg6d4PA976rHpym5vwKe?usp=sharing  

This tool leverages the Google Agent Development Kit (ADK) to automate the discovery, evaluation, and delivery of AI news. Designed specifically for Analytics Leaders, it filters the "noise" of daily tech news into a high-signal, fully formatted Obsidian vault.

🚀 The Workflow
 - The system employs a sophisticated Multi-Agent Orchestration pattern with a deterministic loop to ensure quality content delivery.
 - Search Agent: Scans the web for "breaking AI news" and emerging trends relevant to the analytics domain.
 - Relevance Agent (The Filter): Acts as a high-level gatekeeper. It evaluates each piece of content against custom leadership criteria (e.g., "Impact on data strategy," "LLM governance," "MLOps advancements").
 - The Looping Logic: If the initial search fails to yield high-relevance articles, the system automatically adjusts parameters and re-searches (up to 3 times) to ensure your daily brief is never empty.
 - Markdown Publisher: Compiles the final "vetted" stories into a clean Markdown file, complete with Obsidian Properties (YAML) for easy database querying.

✨ Key Features
 - Built with Google ADK: Utilizes the latest code-first toolkit for building sophisticated AI agents.
 - Obsidian Ready: Output is saved directly to Google Drive (integrated via Colab) and formatted with properties like type: news-report and status: unread.
 - Deterministic Looping: Prevents "empty reports" by allowing the agent to self-correct and try different search angles if relevance scores are low.
 - Analytics Focused: Persona-driven filtering ensures you see "AI for Data Leaders," not just general tech headlines.

🛠️ Built With
 - Google Agent Development Kit (ADK): Multi-agent framework and runner.
 - Google Gemini: The underlying LLM for reasoning and relevance scoring.
 - Google Colab: Cloud-based execution and Google Drive integration.
 - Obsidian: The final destination for knowledge management.

📊 System Diagram 
(created using Obsidian mermaid): 
<img width="740" height="1101" alt="image" src="https://github.com/user-attachments/assets/0177b62e-7646-4f92-8747-db57fba2444c" />


📝 Sample Output
Below is an example of how a "High Relevance" story appears in the Obsidian vault:
<img width="837" height="1264" alt="image" src="https://github.com/user-attachments/assets/cd2f38cc-7114-4c4a-922c-e1e20ebfbda2" />


🎓 Acknowledgments
 - Inspired by training from the "5-Day AI Agents Intensive Course with Google" on Kaggle.
 - Google ADK team for the modular agent framework.

