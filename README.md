# Simple Kubernetes Scaling API 
*A simple flask app to test a Kubernets autoscaling*

This is a simple program that I am making as part of my University project, which is to work with Kubernetes to understand how it can be used for scaling services. 

This project brought up the need for a simple program that can be used to respond to API requests, and that gives me some control of how much load an API request has on a server.

To do this, a Python program will be written that exposes an API using [Connexion](https://github.com/spec-first/connexion?tab=readme-ov-file) , that performs and returns the result of different calculations.

## Implementation
- [ ] Python enviroment setup
- [ ] Single .py file containing functions (Prime Check, Fibonacci Sequence, Factorial...)
- [ ] Logging to file (function processing time, request count...)
- [ ] Define API with OpenAPI spec file
- [ ] Set up Connexion to expose API
- [ ] Configuration file
- [ ] Dockerise app
- [ ] Kubernetes deployment
- [ ] Documentation (How to deploy, configure, and modify, clear notes...)

> [!NOTE] 
> My expertiese in ICT is Infrastructure, not programming. Because of this, I want to keep this code as simple as possible. Hopefully this means that it is easy for someone else to implement and modify this for a similar pourpose.

> [!WARNING]  
> There has been no thought into security with this program. It is only entended for local testing purposes, and NOT to be exposed to the internet.



# Deployment Guide
- Manual build
- Docker installation
- Kubernetes installation


# Configuration Guide
- Logging settings



# Modification Guide

- How to modify and add new functions


# Further Development
Below are some items that may be added in future. This would likely be done as a second project once the above is completed, which would be in combination with further Kubernetes learnings. 
- Some way to test scaling with a database
- A simple statistics / performance display
- API rate limiting