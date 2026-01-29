# Automated API Testing with Postman, Newman & Jenkins

This repository contains automated API tests created with Postman and executed via Newman CLI.
The test suite is integrated with Jenkins to demonstrate CI-based API testing.

![JENKINSPIPELINE1 0](https://github.com/user-attachments/assets/f437b62f-597d-4d50-a787-35dad3425e66)
NEWMAN REPORT
![Newman Summary Report - API](https://github.com/user-attachments/assets/791b1a5f-d2c9-4d92-8212-386e51c0040d)

CONSOLE OUTPUT
![JENKINSPIPELINE1](https://github.com/user-attachments/assets/9548ee79-5cbc-49f3-8548-10156ee10cb4)
![JENKINSPIPELINE2](https://github.com/user-attachments/assets/cc1c1d90-e292-4c88-825d-512ec60f411b)

JENKINS DASHBOARD
![JENKINSPIPELINE3](https://github.com/user-attachments/assets/cc23308c-0140-4a59-91b6-700a9056c6be)

## Tech Stack
- Postman
- Newman
- Jenkins
- Node.js

## How to Run Tests Locally
```bash
npm install -g newman
newman run collections/API-deportes.postman_collection.json -e environments/dev.postman_environment.json
