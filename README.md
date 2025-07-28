# Agent
Build agents to solve multiple use case.
Use Case 1: A1_PPL_Cricket - Project
The objective is to organize a cricket tournament this fall in a small community, following established rules that all players must observe for the event’s success. Each player’s profile includes detailed batting, bowling, and fielding statistics, as well as injury history and volunteer information. Multiple teams will be formed from these players to compete, with the goal of determining first through fourth place champions.
To support this, I have assembled several files: player stats data, tournament rules, injury records, and committee information. These resources are designed to be parsed using a Retrieval-Augmented Generation (RAG) approach for complex reasoning tasks.
Technology stack:
	•	Data processing and experimentation: Google Colab, PyCharm, Google Gemini
	•	User interface: Streamlit
The UI serves as an agent that can query the spreadsheets and rules to provide information about players and tournament details. Additionally, it guides the process of forming balanced teams based on specified criteria.
