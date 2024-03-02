<h1>Kalvi - Open Source Infrastructure for Online Education</h1>

We are an opensource company building modern technology stack for building your edtech platform - craft eLearning content, manage online classes, administer online assessments, foster communities, implement gamification strategies - all without building from scratch.
<br>

🌐 https://www.kalvi.co <br> 📧 hello@kalvi.co

![image](https://github.com/kalvilabs/.github/assets/9934901/f16d0280-cb8d-4f95-80d4-6f8e973a989d)
<br>

<h2>Unified Technology Stack for Digital Learning</h2>

1. <b>Teach</b> - All the tools you need to create engaging digital learning experiences
2. <b>Connect</b> - Build a vibrant learning community to foster social learning experiences
3. <b>Assess</b> - Administer online assessments in Coding, Math and Mocks with Proctoring
4. <b>Gamify</b> - Transform educational journey into an exciting adventure
5. <b>Measure</b> - Make Informed Decisions with Data Analytics 


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
