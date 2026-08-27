# Findora Cloud Services (Super-Repository)

## Student Information
- **Student Name:** Charuka Hansaja
- **Student ID:** 241722035
- **Slack Handle:** Charuka (`U0BF12U29NF`)
- **GCP Project ID:** findora-cloud-platform

---

## Project Description
This super-repository manages all business domain microservices for the Findora application using Git Submodules.

## Submodules Included
- `findora-user-service`: User authentication & profile management
- `findora-item-service`: Lost & Found item management
- `findora-media-service`: Image upload & GCP Storage integration

## Technology Stack
- **Language:** Java 25
- **Frameworks:** Spring Boot, Spring Data JPA, Spring Data MongoDB
- **Databases:** Cloud SQL (MySQL/PostgreSQL) & MongoDB / Firestore
- **Cloud Storage:** GCP Cloud Storage Buckets

## Setup / Getting Started Instructions
```bash
# Clone with submodules
git clone --recursive [https://github.com/YOUR_GITHUB_USERNAME/findora-cloud-backend-services.git](https://github.com/YOUR_GITHUB_USERNAME/findora-cloud-backend-services.git)