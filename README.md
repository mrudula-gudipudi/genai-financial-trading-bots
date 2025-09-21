# genai-financial-trading-bots
Generative AI-driven trading bots for financial markets, featuring automated validation, multi-language deployment, and containerized pipelines.


📌 Summary

In an academic–industry collaboration, this project showed how Generative AI can be used to build trading bots that work across multiple languages, including Python, Java, and C++. We designed a middleware layer with REST APIs and RabbitMQ to let these bots communicate seamlessly, and built a sandbox validation system that automatically tested them for errors, security issues, and performance. Only bots that passed validation were deployed into a competitive simulation platform, where they ran in real time to prove their reliability and adaptability.

⚠️ Due to NDA restrictions, no code or data can be shared. This README summarizes the approach and outcomes.


🎯 Objectives

Build a framework that allows multi-language bot creation (Python, Java, C++).

Use Generative AI to generate bots with embedded API templates.

Ensure seamless integration with backend infrastructure via REST APIs.

Automate testing and validation to reduce manual intervention.

Create a scalable architecture that can adapt to additional languages and features in the future.


⚙️ Tech Stack

Languages: Python, Java, C++

Infrastructure & Tools: Docker, RabbitMQ, InfluxDB, REST APIs, MySQL

Validation Tools: Pylint for Python, custom validators for C++ and Java

Automation: Shell scripts for server startup and validation workflows


🚀 Implementation Highlights

Used Generative AI prompts to generate bots across Python, Java, and C++ with embedded APIs.

Built a validation framework that checked extensions, flagged malicious patterns, and enforced coding standards.

Created a sandboxed testing system where bots were executed in isolation and monitored for performance and compliance.

Developed Dockerized environments that supported all three languages, simplifying multi-language execution.

Integrated InfluxDB for storing test outputs and improving monitoring/debugging.


📊 Results & Business Value

Accessibility: Opened the platform to developers who prefer Java or C++, expanding participation.

Efficiency: Automated validation eliminated repetitive manual checks and improved turnaround time.

Scalability: Modular design means new languages or features can be added with minimal rework.

Reliability: Error-free, validated bots improved the quality of simulations and reduced system failures.

Strategic Value: Showcased how Generative AI can automate complex workflows in financial technology, reinforcing the potential of AI-driven systems in high-stakes environments.


⚠️ Challenges & Limitations

High infrastructure loads sometimes delayed REST API responses.

Processing large volumes of bots in parallel created testing bottlenecks.

Performance varied slightly between languages due to memory and execution differences.
