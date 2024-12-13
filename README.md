# Medius.ai - AI-Driven Healthcare Coordination Platform

<img width="494" alt="agents" src="https://github.com/user-attachments/assets/2480ca46-0a5b-47ad-85bf-62debfdd2c6a" />

**Inspiration**

Healthcare, law enforcement, social services, and first responders often face critical inefficiencies in communication due to patient privacy regulations and siloed information systems. These challenges can lead to delayed or suboptimal decisions, risking patient outcomes and organizational performance. We were inspired to create Medius AI—a SaaS platform—to bridge these gaps and streamline collaboration across sectors.

**What it does**

Medius AI is a SaaS platform that enables seamless, privacy-compliant communication through a multi-agent system powered by Fetch.ai’s UAgents framework. It includes a Patient, a Hospital, a Blood Bank, and a Coordinator agent to manage role-based access and synchronize data sharing across stakeholders. The platform also uses AI and a RAG chatbot to provide predictive insights and synthesized treatment recommendations.

**How we built it**

<img width="489" alt="agentsflow" src="https://github.com/user-attachments/assets/31956c69-b298-4cea-907c-2896e48accda" />

_Backend:_ Fetch.ai's UAgents framework to create autonomous agents tailored to roles like Patient, Hospital, Blood Bank, and Coordinator.

_Frontend:_ Built with Streamlit for user-friendly interactions.

_AI Integration:_ The Fetch.ai documentation guides the design and connection of agents, LangChain powers knowledge retrieval, Pinecone manages vector embeddings, and the RAG-enhanced chatbot synthesizes data into actionable insights.

_Privacy:_ Robust role-based access controls and anonymized patient identifiers ensure compliance and security.

**Scenario**

<img width="228" alt="Screen Shot 2024-12-13 at 1 59 20 PM" src="https://github.com/user-attachments/assets/1486be2b-60da-4ce3-a4b4-24e75fa01bd7" />

**Challenges we ran into**

Ensuring compliance with complex healthcare privacy laws while maintaining operational efficiency.
Designing a system that dynamically adapts to varying access needs across roles.
Creating seamless integration between the multi-agent architecture and the RAG chatbot.

**Accomplishments that we're proud of**

Successfully built a secure, multi-agent system using Fetch.ai’s UAgents framework.
Developed a RAG chatbot that enhances real-time, privacy-compliant data sharing.
Created a scalable architecture adaptable to healthcare and beyond.

**What we learned**

The adaptability of Fetch.ai UAgents for building secure, role-based systems.
How to align cutting-edge AI tools with strict privacy and compliance needs.
The value of user-centric design for SaaS platforms in high-stakes industries.

**What's next for Medius.ai**

Expand Fetch.ai integrations for decentralized, secure data sharing.
Add predictive risk management and advanced analytics capabilities.
Partner with organizations for real-world implementation and scaling.

**Built with**

LangChain, Pinecone, FAISS, Streamlit, and Fetch.ai's multi-agent architecture.
