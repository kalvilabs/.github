<h1>Kalvi - Open Source Infrastructure for Online Education</h1>

We are an opensource company building modern technology stack for building your edtech platform - craft eLearning content, manage online classes, administer online assessments, foster communities, implement gamification strategies - all without building from scratch.
<br>

🌐 https://www.kalvi.co <br> 📧 hello@kalvi.co

![image](https://github.com/kalvilabs/.github/assets/9934901/f16d0280-cb8d-4f95-80d4-6f8e973a989d)
<br>

<h2>Unified Technology Stack for Digital Learning</h2>

<h3>Teach - All the tools you need to create engaging digital learning experiences </h3> 
<img width="1186" alt="image" src="https://github.com/kalvilabs/.github/assets/9934901/0a1d1985-0d8f-44ed-991f-e9e235096373">


<h3>Connect - Build a vibrant learning community to foster social learning experiences</h3>

   ![image](https://github.com/kalvilabs/.github/assets/9934901/fe80c8ca-bd88-4c7d-b757-c3813078e6dd)

<h3>Assess - Administer online assessments in Coding, Math and Mocks with Proctoring </h3>

<![image](https://github.com/kalvilabs/.github/assets/9934901/2cd579fa-c947-4d89-bba4-dde82477a693)

 <h3>Gamify - Transform educational journey into an exciting adventure </h3>
<img width="869" alt="image" src="https://github.com/kalvilabs/.github/assets/9934901/2bfddc86-2e53-460f-9dde-a75f88af4ce8">

 <h3>Measure - Make Informed Decisions with Data Analytics </h3>


# Quick Start
**Pre-requisites**

 1. Docker - https://www.docker.com/
 2. Node - https://nodejs.org/en
 3. PNPM - https://pnpm.io/
 4. VSCode - https://code.visualstudio.com/

Clone from https://github.com/kalvilabs/kalvios

Step 1: Run this to install both frontend and backend
```

pnpm run dev-prep

```
Step 2: Run to boot both the frontend and backend server
(Note: This will also run pending db migrations in the backend)
```

pnpm run dev

```

Optional: Run to boot only the backend
```

pnpm run backend:run

```


Optional: Run to boot only the frontend
```

pnpm run frontend:run

```

# How to run Django Commands

```

docker-compose run api poetry run python manage.py makemigration

```
