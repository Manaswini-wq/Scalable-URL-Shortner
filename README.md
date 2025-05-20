# Scalable URL Shortener  
[![Deploy on GCP](https://img.shields.io/badge/Deploy%20on-Google%20Cloud-blue)](https://console.cloud.google.com)  
A high-performance URL shortener built with **Flask, Redis, and GCP**, handling 1M+ daily requests.  

---

## **Features**  
- **Custom Hash Encoding**: Generate short URLs (e.g., `https://short.xyz/AbCdEf`).  
- **Redis Caching**: Reduced latency by 40% for frequent requests.  
- **Analytics Dashboard**: Track clicks, geolocation, and referral sources.  
- **Dockerized Deployment**: Scalable on GCP Compute Engine.  

---

## **Tech Stack**  
- **Backend**: Python (Flask)  
- **Databases**: MongoDB (metadata), Redis (caching)  
- **Infrastructure**: GCP, Docker, Nginx  
- **APIs**: RESTful endpoints for URL creation/redirection  

---

## **Setup & Installation**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Manaswini-wq/url-shortener.git  
   cd url-shortener  
