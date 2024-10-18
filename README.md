# Microservice Dependency Tracker: Visualizing Inter-Service Communication

**Author:** Kyle Thomas  

**University:** School of Computing Science, University of Glasgow

## Overview
This page goes into more depth about HPE, including my reflections on HPE, my plans for the future and advice for applying for a job with HPE. I also discuss the project more in depth the analyis and expectations for this project and potential future enhancements.

The **Microservice Dependency Tracker** is a tool designed to visualize the interactions and dependencies between microservices within HPE’s GreenLake platform. As microservice architectures scale, they become increasingly complex, making it challenging for developers to identify issues, track API errors, and understand service dependencies. This tool offers a real-time, visual map of these dependencies, empowering developers to maintain clarity and optimize inter-service communication.

<img src="https://github.com/user-attachments/assets/26899b39-1544-49e6-93a0-74af95b131b2" width="30%" />


## Company Background
### [Hewlett Packard Enterprise](https://www.hpe.com/us/en/home.html) (HPE)
HPE, a global enterprise IT solutions company, split from HP Inc. in 2015. They specialize in cloud services, artificial intelligence, and high-performance computing (HPC). HPE serves large enterprises, governments, and other organizations worldwide, offering scalable and secure solutions. One of HPE’s flagship products, **[GreenLake](https://www.hpe.com/us/en/greenlake.html)**, provides cloud-like services with the security and control of on-premises infrastructure, built using a microservices architecture.

## Reflections on the Placement

### Technical Skills and Technologies
- During my placement, I significantly expanded my technical skill set. Working on a microservice built with **Go**, I deepened my understanding of cloud technologies such as **Kubernetes** for orchestration, **Docker** for containerization, and monitoring tools like **Prometheus** and **Grafana**. 
- I also gained experience in **API development** (REST and gRPC) and automated deployment pipelines using **GitHub Actions**.
- Leading the development of an **incentive web app** exposed me to front-end development using **React** and back-end integration with **Google Firebase**, enhancing my full-stack development abilities.

### Professional and Leadership Skills
- I developed leadership skills by managing projects and conducting workshops on web development for interns and high school students. This required strong communication and organization as I explained complex technical concepts to diverse audiences.
- I was also involved in organizing mental health and site events, which improved my skills in team collaboration, event management, and delegation.

### Recruitment Process Involvement
- A key highlight of my placement was being involved in the **intern recruitment process**. I reviewed CVs, interviewed candidates, and assessed their skills, gaining insight into what makes a strong candidate and improving my ability to evaluate technical and interpersonal skills.
- This experience enhanced my understanding of recruitment strategies and how to assess fit for both technical roles and company culture.

### Continued Collaboration and Graduate Offer
- I have continued to work with HPE beyond the official placement period, contributing to ongoing projects and further expanding my technical and professional skills. 
- Following my successful placement, I have been offered a **graduate role** at HPE, a testament to the value and impact of my time with the company.

## Recommending a Year in Industry

### Hands-On Experience
- A year in industry offers the opportunity to apply theoretical knowledge in real-world scenarios, giving you practical experience that solidifies your understanding and builds confidence. Working on live systems and solving critical business challenges at HPE provided invaluable hands-on learning.

### Industry-Standard Tools and Practices
- During my placement, I was exposed to industry-standard tools and practices, including **Agile methodologies**, **DevOps principles**, and **CI/CD** pipelines. These experiences allowed me to apply my university knowledge in a professional setting and prepared me for a future career in the tech industry.

### Professional Development
- A year in industry fosters both personal and professional growth, providing opportunities to take ownership of projects, develop leadership and teamwork skills, and experience different roles within a company.

### Career Networking
- Engaging with professionals and mentors helped me build a valuable career network. Additionally, participating in the **recruitment process** gave me insight into what companies look for in candidates, which will be an advantage when applying for future roles.

### Recommendation
- Based on my experience, I highly recommend taking a year in industry. It provides an immersive learning experience that combines technical growth with professional development and equips you with practical skills that will set you apart in the job market.

## Advice for Applying to HPE

### Tailor Your CV
- **Customize your CV** for each role you apply to. Highlight specific skills and experiences that match the job description, using keywords from the listing. HPE looks for candidates who demonstrate a clear fit with the role and have a keen understanding of the technologies and methodologies the company uses.

### Research the Company
- **Understand HPE's values, products, and services**. Knowing about HPE's core offerings, such as GreenLake and their focus on hybrid cloud and edge-to-cloud platforms, will give you an edge in interviews. Demonstrating an understanding of the company culture and vision can make you stand out.

### Prepare for Technical and Behavioral Questions
- For technical interviews, **review key topics** such as cloud computing, microservices, API development, and relevant technologies like Kubernetes, Docker, and Prometheus. Be prepared to discuss real-world applications of these technologies.
- For behavioral interviews, **prepare examples of teamwork, leadership, problem-solving, and handling challenges**. HPE values strong interpersonal skills and a collaborative mindset.

### Be Involved and Show Initiative
- HPE appreciates proactive individuals who **take initiative**. Share experiences where you've gone beyond your role to add value or solve a problem, whether it's through volunteering for extra tasks, leading projects, or organizing events.

### Ask Questions
- **Engage with the interviewers** by asking insightful questions. This shows your interest in the role and the company. Ask about HPE’s tech stack, the team culture, or how the company supports career growth and development.

### Emphasize Collaboration and Culture Fit
- HPE places a strong emphasis on company culture, particularly around **well-being, diversity, and inclusivity**. During the interview process, demonstrate your ability to work well with others, adapt to different work environments, and contribute positively to the company culture.

## Project Overview
The **Microservice Dependency Tracker** is a tool designed to visualize the interactions and dependencies between microservices within HPE’s GreenLake platform. As microservice architectures scale, they become increasingly complex, making it challenging for developers to identify issues, track API errors, and understand service dependencies. This tool offers a real-time, visual map of these dependencies, empowering developers to maintain clarity and optimize inter-service communication.

<img src="https://github.com/user-attachments/assets/26899b39-1544-49e6-93a0-74af95b131b2" width="30%" />

### Problem Description
As HPE’s GreenLake platform grows, managing the increasing number of microservices becomes a challenge. Developers struggle to track dependencies, pinpoint performance issues, and trace errors due to the lack of real-time visibility. This can lead to extended troubleshooting times, costly downtime, and architectural complexity that’s difficult to manage.

The **Microservice Dependency Tracker** addresses this issue by providing a visual representation of microservice interactions. By leveraging Kubernetes metadata and API logging, the tool enables developers to quickly identify and resolve issues, ensuring systems remain efficient and scalable.

### Project Objectives
The key goals of the Microservice Dependency Tracker include:
- **Real-Time Visualization**: Display a dynamic map of microservice dependencies, showing interactions and performance metrics.
- **API Monitoring**: Track API response times, error rates, and latency to identify bottlenecks and optimize service performance.
- **Integration**: Seamlessly integrate the tool into HPE’s CI/CD pipeline for automated deployment and monitoring.
- **Scalability**: Design the tool to support scaling as the number of microservices grows, ensuring it remains effective as the architecture evolves.

### Technology Stack
The project utilizes the following technologies:
- **Kubernetes**: For collecting metadata on services and deployments.
- **Humio**: A real-time log management tool for monitoring API interactions and gathering communication data.
- **Go**: Programming language used to build the backend tool, ensuring performance and concurrency.
- **Grafana**: For developing the interactive dashboard that visualizes microservice dependencies and performance metrics.
- **Docker**: Containerization for consistent deployment across environments, integrated with the CI/CD pipeline.

### Project Stages
1. **Requirement Analysis**: Identifying data sources, compliance metrics, and understanding system requirements.
2. **Design and Development**: Building the backend using Go and integrating Kubernetes APIs to collect and process data.
3. **Visualization**: Developing the dashboard using Grafana to provide real-time insights and a clear visual map of microservice dependencies.
4. **Testing and Validation**: Ensuring accuracy in mapping dependencies, monitoring performance metrics, and debugging issues.
5. **Deployment**: Integrating the tool into HPE’s CI/CD pipeline using Docker for automated deployment.

### Technical Skills
- **Database Systems**: Utilizes database knowledge to manage and structure microservice data efficiently.
- **Software Engineering Practices**: Applies agile methodologies, version control, and clean architecture principles to maintain a modular codebase.
- **API Development and Cloud Technologies**: Leverages experience from university and placement, focusing on API design, Kubernetes, and cloud-native tools.

## Personal Development
- **Problem-Solving**: Enhances skills in debugging, identifying bottlenecks, and optimizing microservice interactions.
- **Cloud Technologies**: Deepens expertise in Kubernetes, Docker, and monitoring tools like Grafana and Humio, essential for modern cloud development.
- **Real-World Development Experience**: Integrates with HPE’s CI/CD pipeline, reflecting industry-standard software development practices and building upon university coursework (Team Project, Professional Software Development).

### Insights and Reflections
- **Complexity of Microservices**: The project emphasizes the importance of visualizing and understanding dependencies in large-scale systems. As microservice architectures grow, maintaining clarity becomes essential for efficient development and troubleshooting.
- **Balancing Automation and Human Oversight**: The tool shows how automated solutions are critical for managing complex cloud-native environments, raising questions about how much automation is ideal.
- **Proactive Monitoring**: The focus on real-time monitoring and visualization highlights the shift towards proactive problem-solving, reducing downtime and enhancing system reliability.

### Future Enhancements
The Microservice Dependency Tracker could be expanded to include:
- **AI-Based Analysis**: Using machine learning to predict potential service failures based on historical data.
- **Alerting System**: Integrating alert mechanisms to notify developers of critical issues in real-time.

## Contact Information
For more information or collaboration opportunities, please reach out via email: 2548971t@student.gla.ac.uk
