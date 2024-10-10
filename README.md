# Microservice Dependency Tracker: Visualizing Inter-Service Communication

**Author:** Kyle Thomas  

**University:** School of Computing Science, University of Glasgow

## Overview
The **Microservice Dependency Tracker** is a tool designed to visualize the interactions and dependencies between microservices within HPE’s GreenLake platform. As microservice architectures scale, they become increasingly complex, making it challenging for developers to identify issues, track API errors, and understand service dependencies. This tool offers a real-time, visual map of these dependencies, empowering developers to maintain clarity and optimize inter-service communication.

<img src="https://github.com/user-attachments/assets/26899b39-1544-49e6-93a0-74af95b131b2" width="30%" />


## Company Background
### Hewlett Packard Enterprise (HPE)
[HPE](https://www.hpe.com/us/en/home.html), a global enterprise IT solutions company, split from HP Inc. in 2015. They specialize in cloud services, artificial intelligence, and high-performance computing (HPC). HPE serves large enterprises, governments, and other organizations worldwide, offering scalable and secure solutions. One of HPE’s flagship products, **[GreenLake](https://www.hpe.com/us/en/greenlake.html)**, provides cloud-like services with the security and control of on-premises infrastructure, built using a microservices architecture.

## Problem Description
As HPE’s GreenLake platform grows, managing the increasing number of microservices becomes a challenge. Developers struggle to track dependencies, pinpoint performance issues, and trace errors due to the lack of real-time visibility. This can lead to extended troubleshooting times, costly downtime, and architectural complexity that’s difficult to manage.

The **Microservice Dependency Tracker** addresses this issue by providing a visual representation of microservice interactions. By leveraging Kubernetes metadata and API logging, the tool enables developers to quickly identify and resolve issues, ensuring systems remain efficient and scalable.

## Project Objectives
The key goals of the Microservice Dependency Tracker include:
- **Real-Time Visualization**: Display a dynamic map of microservice dependencies, showing interactions and performance metrics.
- **API Monitoring**: Track API response times, error rates, and latency to identify bottlenecks and optimize service performance.
- **Integration**: Seamlessly integrate the tool into HPE’s CI/CD pipeline for automated deployment and monitoring.
- **Scalability**: Design the tool to support scaling as the number of microservices grows, ensuring it remains effective as the architecture evolves.

## Technology Stack
The project utilizes the following technologies:
- **Kubernetes**: For collecting metadata on services and deployments.
- **Humio**: A real-time log management tool for monitoring API interactions and gathering communication data.
- **Go**: Programming language used to build the backend tool, ensuring performance and concurrency.
- **Grafana**: For developing the interactive dashboard that visualizes microservice dependencies and performance metrics.
- **Docker**: Containerization for consistent deployment across environments, integrated with the CI/CD pipeline.

## Project Stages
1. **Requirement Analysis**: Identifying data sources, compliance metrics, and understanding system requirements.
2. **Design and Development**: Building the backend using Go and integrating Kubernetes APIs to collect and process data.
3. **Visualization**: Developing the dashboard using Grafana to provide real-time insights and a clear visual map of microservice dependencies.
4. **Testing and Validation**: Ensuring accuracy in mapping dependencies, monitoring performance metrics, and debugging issues.
5. **Deployment**: Integrating the tool into HPE’s CI/CD pipeline using Docker for automated deployment.

## Technical Skills
- **Database Systems**: Utilizes database knowledge to manage and structure microservice data efficiently.
- **Software Engineering Practices**: Applies agile methodologies, version control, and clean architecture principles to maintain a modular codebase.
- **API Development and Cloud Technologies**: Leverages experience from university and placement, focusing on API design, Kubernetes, and cloud-native tools.

## Personal Development
- **Problem-Solving**: Enhances skills in debugging, identifying bottlenecks, and optimizing microservice interactions.
- **Cloud Technologies**: Deepens expertise in Kubernetes, Docker, and monitoring tools like Grafana and Humio, essential for modern cloud development.
- **Real-World Development Experience**: Integrates with HPE’s CI/CD pipeline, reflecting industry-standard software development practices and building upon university coursework (Team Project, Professional Software Development).

## Insights and Reflections
- **Complexity of Microservices**: The project emphasizes the importance of visualizing and understanding dependencies in large-scale systems. As microservice architectures grow, maintaining clarity becomes essential for efficient development and troubleshooting.
- **Balancing Automation and Human Oversight**: The tool shows how automated solutions are critical for managing complex cloud-native environments, raising questions about how much automation is ideal.
- **Proactive Monitoring**: The focus on real-time monitoring and visualization highlights the shift towards proactive problem-solving, reducing downtime and enhancing system reliability.

## Future Enhancements
The Microservice Dependency Tracker could be expanded to include:
- **AI-Based Analysis**: Using machine learning to predict potential service failures based on historical data.
- **Alerting System**: Integrating alert mechanisms to notify developers of critical issues in real-time.

## Contact Information
For more information or collaboration opportunities, please reach out via email: 2548971t@student.gla.ac.uk
