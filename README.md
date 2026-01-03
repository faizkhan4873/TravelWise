# TravelWise
AI-Powered Location Intelligence Platform

TravelWise is an AI-powered travel planning platform that intelligently generates personalized, budget-aware, time-optimized travel plans using geospatial data and a multi-agent AI architecture.

Unlike traditional travel apps, TravelWise treats travel planning as a real-world decision-making and optimization problem, considering constraints such as:

1.Budget limits

2.Time availability

3.Transportation options

4.Location distance & traffic

5.Place availability

6.Risk and fallback planning

The system uses specialized AI agents coordinated by a planner agent, making it robust, and scalable.

Key Features-

🧠 Multi-Agent AI Architecture

🗺️ Geospatial Route Intelligence

💰 Budget-Constrained Optimization

⏱️ Time-Aware Itinerary Scheduling

📍 Personalized Recommendations


```mermaid
flowchart of TravelWise
    A[User Request] --> B[Planner Agent]
    B --> C[Route Agent]
    B --> D[Budget Agent]
    B --> E[Time Agent]
    B --> F[Recommendation Agent]
    B --> G[Risk Agent]

    C --> H[Route Options]
    D --> I[Budget Allocation]
    E --> J[Schedule Plan]
    F --> K[Personalized Places]
    G --> L[Backup Plans]

    H --> M[Final Travel Plan]
    I --> M
    J --> M
    K --> M
    L --> M
```




⚠️ Risk Detection & Backup Planning

🧩 Modular & Scalable Design
