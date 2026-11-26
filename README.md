# Thinh Duc Hoang

**.NET Backend Developer** · Software Engineering Student at FPT University · Ho Chi Minh City, Vietnam

[![LinkedIn](https://img.shields.io/badge/LinkedIn-dominic--dev-0A66C2?style=flat-square)](https://www.linkedin.com/in/dominic-dev)
[![Email](https://img.shields.io/badge/Email-hoangducthinh495%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:hoangducthinh495@gmail.com)

## About Me

I am a third-year Software Engineering student focused on backend development with C# and ASP.NET Core. My recent work covers payment gateway integration, database design and migration, automated testing, and containerized deployment.

- **Education:** Bachelor of Software Engineering, FPT University (2024 – 2028, expected)
- **GPA:** 8.63/10, with a 100% tuition scholarship for the full program
- **Open to:** .NET Backend internship (OJT), full-time or part-time, from January 2027

## Tech Stack

**Backend**

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square)
![.NET](https://img.shields.io/badge/.NET%2010-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Render](https://img.shields.io/badge/Render-000000?style=flat-square&logo=render&logoColor=white)
![xUnit](https://img.shields.io/badge/xUnit-5E2750?style=flat-square)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

**Also experienced with:** Java, Python, scikit-learn, Hugging Face, WPF

## AI-Assisted Development

I use coding agents as part of my development workflow, and I review and test their output before it goes into a project.

- **Agents:** Claude Code, OpenAI Codex, Google Antigravity
- **Workflow:** using agent skills for repeatable development tasks

## Featured Projects

### [Olympic Sports Arena – Sports Center Management System](https://github.com/DuyPham-bit/SWP391_SE2039_G06_SportsCenterManagement)

*Backend Developer · Team of 5 · Sep – Nov 2026* · [Live demo](https://sports-center-manager-fe.vercel.app) (first load may take about a minute)

A web platform for managing sports center members, packages, classes, coaches, and payments.

- Built the Manager module (members, packages, classes, coaches, payroll, reports, manual refunds) using a 3-layer architecture, Repository / Unit of Work, and role-based authorization.
- Integrated VNPay and MoMo (sandbox) with HMAC signature verification, idempotent IPN callback handling, and a refund flow.
- Migrated the database from SQL Server to PostgreSQL and set up Docker Compose for one-command local setup.
- Wrote 15 xUnit integration tests and deployed the API to Render with Docker.

`ASP.NET Core` `EF Core` `PostgreSQL` `Docker` `Cloudflare R2`

### [Smart Weather Station IoT](https://github.com/dome-94/smart-weather-station-iot)

*Team Leader · Team of 4 · Jun – Aug 2026*

An end-to-end weather monitoring and forecasting system: ESP8266 sensors send data over LoRa P2P to a gateway and on to the ThingSpeak cloud, while a Random Forest model produces a new forecast every 15 minutes on GitHub Actions.

`ESP8266` `LoRa` `Python` `scikit-learn` `GitHub Actions`

### [Spam Email Detection with Naive Bayes](https://github.com/dome-94/spam-email-detection-naive-bayes)

*Probability and Statistics course project*

A text classification pipeline that reached **97.03% accuracy** and **99.63% recall** on a held-out test set of 1,146 emails.

`Python` `NLP` `Jupyter Notebook`

## Research

### [Ambiguity Detection in Software Requirements with LLMs and VLMs](https://github.com/HoangKhoi1704/VLM-in-ambiguity-RE)

*Co-author · Team of 5 · VISAT 2026*

- Compared Qwen2.5 language and vision-language models, zero-shot and with 4-bit QLoRA fine-tuning, on 2,109 software requirements.
- The fine-tuned VLM scored highest among 7 models (ROC-AUC 0.937, F1-macro 0.836).
- Ran the QLoRA fine-tuning experiments on Google Colab.
