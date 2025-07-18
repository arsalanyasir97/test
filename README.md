Technical Challenge: Life Insurance Recommendation MVP
Goal
Build a simple full-stack prototype of a life insurance recommendation engine that
demonstrates your proficiency across your required stack (React/Next.js + Node.js +
PostgreSQL + Docker + AWS readiness).
Task Overview
You are building a prototype of a web app that educates users about life insurance and gives
them a personalized recommendation based on basic profile data.
Requirements
Frontend
Use Next.js with TypeScript.
A single-page form that collects the following user inputs:
○
Age
○
Income
○
Number of Dependents
○
Risk Tolerance (Low / Medium / High)
After submission, display:
○
A personalized recommendation (e.g.,
"Term Life – $500,000 for 20 years")
○
A simple explanation for the choice.
Clean, responsive design using a UI library (e.g., Tailwind, Material UI, or similar).
Backend
●
Use Node.js with Express or NestJS (or optionally, Python with Flask/Django).
●
Create a REST API endpoint /recommendation that accepts the form data and returns
a recommendation.
●
●
Logic can be simple and rules-based (e.g., if age < 40 and risk = high → term life), but
should be extensible for ML integration later.
Store user submissions in PostgreSQL.
DevOps & Deployment
●
Provide instructions to deploy the app to AWS (e.g., using ECS or Elastic Beanstalk)
or include notes on how you would do it if not deploying.
Optional Stretch Goals
●
●
●
●
Use React Native to build a mobile version of the form + response screen.
Add a basic authentication flow (email + password or OTP).
Add logging + monitoring (e.g., use a basic cloudwatch setup or log to stdout in
Docker).
Add rate limiting or other simple security measures.
Deliverables
●
GitHub repository with:
○
README.md describing setup and deployment instructions.
○
Clean, well-commented code.
○
Optional deployed version (e.g., on Vercel + Render or AWS).
Evaluation Criteria
Category What We’re Looking For
Frontend
(React)
Backend (API) Database Responsive UI, well-structured components, clean state management,
readable code
Secure, clean API design, extensible logic, proper validation and error
handling
Clear schema design, proper use of SQL, no security red flags (e.g., raw
SQL injections)
Docker/DevOps Working local dev environment
Security Communication Sensible defaults, minimal vulnerability exposure, safe handling of inputs
README clarity, code organization, commit history, thoughtful comments
