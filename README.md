# CloudClass

CloudClass is an AI-powered lecture automation platform designed to help students never miss an online class. Inspired by a real student problem, the platform automatically joins scheduled lectures, tracks attendance, captures attendance proof screenshots, generates AI-powered lecture summaries, and provides real-time monitoring through a cloud-native DevOps architecture.

## Features

* Automatic online class joining
* Attendance tracking and management
* Attendance proof through screenshots
* AI-powered lecture summarization
* Real-time monitoring and observability
* Automated scheduling and session management
* Dockerized deployment
* CI/CD pipeline integration
* Scalable cloud-native architecture

## Architecture

User Dashboard → Backend APIs → Scheduler → Worker Services → Online Meeting Platforms

Attendance Data → Database

Screenshots → Cloud Storage

Monitoring → Prometheus + Grafana

CI/CD → GitHub Actions

Deployment → AWS Infrastructure

## Tech Stack

### Frontend

* React.js
* JavaScript
* HTML
* CSS

### Backend

* Python
* FastAPI

### DevOps & Cloud

* AWS EC2
* AWS S3
* Docker
* GitHub Actions
* Prometheus
* Grafana

### Automation & AI

* Playwright
* AI-based Lecture Summarization

## Workflow

1. User schedules a lecture.
2. Scheduler triggers a worker at the specified time.
3. Worker automatically joins the online class.
4. Attendance events are recorded.
5. Screenshots are captured as proof.
6. AI generates lecture summaries.
7. Monitoring dashboards display system health and metrics.

## Key Learning Outcomes

* Cloud Computing with AWS
* Docker Containerization
* CI/CD Implementation
* Infrastructure Monitoring
* Browser Automation
* Distributed Systems Design
* AI Integration in Real-World Applications

## Future Enhancements

* Kubernetes Deployment
* Multi-platform Meeting Support
* Advanced AI Note Generation
* Mobile Application Support
* Auto-generated Study Material

## Author

Priyanshu Kumar and Ravi Kumar Tekkali

B.Tech Computer Science Engineering

Lovely Professional University

Expected Graduation: 2027

## License

This project is developed for educational and learning purposes.
