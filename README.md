# Smart India Hackathon Workshop
# Date:
## Register Number:
## Name:
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
The Recruitment and Assessment Centre (RAC) under DRDO conducts interviews for recruitment and promotions of scientific manpower. A structured and unbiased interview process is critical to selecting the right candidates. The goal is to develop an AI-powered Smart Interview System that:

Simulates a real-life boardroom experience for experts and candidates.

Ensures relevant and structured questioning.

Evaluates response relevance to provide a quantifiable score for decision-making.

Enhances objectivity and efficiency in the interview process.

## Proposed Solution / Architecture Diagram
![ Architecture Diagram](https://github.com/user-attachments/assets/c8206aee-ade6-49dc-8ada-32f6208b8829)


## Use Cases
![Use Cases](https://github.com/user-attachments/assets/50cab1c9-baed-486d-9a21-e87a09b87f6f)


## Technology Stack
Frontend	React.js, Bootstrap

Backend	Python (FastAPI/Django)

AI/NLP Models	OpenAI GPT, BERT, LLMs

Database	PostgreSQL, MongoDB

Speech-to-Text	Google Speech API

Scoring Engine	ML-based Relevance Scoring

Cloud Deployment	AWS / Azure / GCP

Security	OAuth 2.0, Role-based Access

## Dependencies
AI/ML Models – Requires pre-trained NLP models for response analysis.

Secure Cloud Environment – Ensuring data privacy and compliance.

Integration with Existing RAC Systems – Sync with candidate databases.

Speech Processing APIs – Optional feature for verbal interviews.

Expert Feedback Mechanism – Continuous improvement based on panel input.
