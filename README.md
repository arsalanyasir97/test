**Technical Challenge**: Life Insurance Recommendation MVP Goal

Build a simple full-stack prototype of a life insurance recommendation engine that demonstrates your proficiency across your required stack (React/Next.js + Node.js + PostgreSQL + Docker + AWS readiness).

**Task Overview**
You are building a prototype of a web app that educates users about life insurance and gives them a personalized recommendation based on basic profile data.

**Requirements**

**Frontend**
Use Next.js with TypeScript.
A single-page form that collects the following user inputs:
○ Age
○ Income
○ Number of Dependents
○ Risk Tolerance (Low / Medium / High)

After submission, display:
○ A personalized recommendation (e.g.,"Term Life – $500,000 for 20 years")
○ A simple explanation for the choice.
Clean, responsive design using a UI library (e.g., Tailwind, Material UI, or similar).


**Backend**
● Use Node.js with Express or NestJS (or optionally, Python with Flask/Django).
● Create a REST API endpoint /recommendation that accepts the form data and returns
a recommendation.
● Logic can be simple and rules-based (e.g., if age < 40 and risk = high → term life), but should be extensible for ML integration later. Store user submissions in PostgreSQL.
● DevOps & Deployment
● Provide instructions to deploy the app to AWS (e.g., using ECS or Elastic Beanstalk) or include notes on how you would do it if not deploying.
