# DevOps Learning Path: From Fundamentals to Cloud-Native
This repository documents my systematic approach to mastering DevOps tools and practices through hands-on projects



## Learning Methodology
- **Project-driven**: Skills acquired through building real systems
- **Incremental complexity**: Each phase builds on previous knowledge
- **Documentation**: All lessons learned captured in code and articles
- **Observability-first**: All projects include monitoring from inception



## Technical Progression Roadmap


### Phase 1: System Fundamentals
**Completed:**
- Void Linux installation as primary OS  
- i3wm customization (config pending publication)  
- Network analysis lab (Wireshark, nmap, tcpdump)  

**Key Outcomes:**  
- Deepened Linux administration skills  
- Created reproducible system configurations  


### Phase 2: Containerization & Local Orchestration
**Current Focus:**
- **Project**: Microservice Cookbook Application  
  - Frontend: Svelte  
  - Backend: FastAPI  
  - Database: PostgreSQL  

**Implementation Steps:**
1. Docker containerization for each component  
2. Service linking via Docker Compose  
3. Metrics collection with Prometheus + Grafana  
4. Log management (evaluating Loki vs ELK stack)  

**Technical Challenges:**  
- Cross-container networking  
- Persistent storage configuration  


### Phase 3: Networked Deployment
**Planned Work:**
- Edge deployment to OrangePi device  
- Secure external access via ngrok tunnels  
- Kubernetes cluster implementation (k3s)  
- Network policy configuration:  
  - Service discovery  
  - Ingress controllers  
  - Port forwarding rules  


### Phase 4: Automation Pipeline
**Next Stages:**
- Git workflow design (feature branches, semantic versioning)  
- CI/CD implementation:  
  - GitHub Actions workflows  
  - Automated testing suite  
  - Artifact management  
- Infrastructure as Code proof of concept (Terraform)  


### Phase 5: Cloud-Native Implementation
**Future Objectives:**
- Multi-cloud deployment 
- Managed database services evaluation  
- Production-grade monitoring:  
  - Uptime monitoring  
  - Alerting systems  
  - Security hardening  
- Cost optimization strategies  



## Core Project: Intelligent Recipe System

**Technical Specifications:**
- **Authentication**: OAuth 2.0 (Google + Email)  
- **AI Integration**: GPT-based recipe generation engine  
- **Data Pipeline**:  
  - User input processing  
  - API response validation  
  - Fallback humor subsystem  
- **Observability**:  
  - Application performance metrics  
  - Error logging and tracing  
  - User interaction analytics  

**Architecture Goals:**
1. Demonstrate container orchestration skills  
2. Implement full CI/CD lifecycle  
3. Showcase monitoring/alerting implementation  
4. Validate infrastructure automation  



## Technology Stack

**Core Competencies:**
- **Systems**: Void Linux, QEMU virtualization  
- **Containers**: Docker, Docker Compose, Kubernetes  
- **Monitoring**: Prometheus, Grafana, Loki  
- **Cloud**: AWS, GCP  
- **Development**: Svelte, FastAPI, PostgreSQL  


## Metrics & Success Criteria

| Category           | Target                      | Measurement Method          |
|--------------------|----------------------------|----------------------------|
| System Reliability | 99.95% lab environment uptime | Prometheus alerts          |
| Deployment Speed   | <5 minute build/deploy cycle | CI/CD pipeline metrics     |
| Incident Response | <30 minute MTTR             | Incident documentation     |
| Automation Rate    | 85% tasks automated         | Process inventory analysis |


## Documentation Philosophy
All projects include:
- Technical write-ups (Medium/blog)
- Annotated configuration files
- Failure post-mortems
- Improvement roadmaps


