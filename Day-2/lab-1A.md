# Day2_SixPatterns

## Topic

**Explain Docker for a placement interview.**

---

# Pattern 1 — PERSONA

## Prompt

```text
"You are a senior placement coach at Aditya University. You have prepared 200 B.Tech CSE students for TCS, Infosys, and Cognizant placement interviews. A 3rd-year CSE student with 7.5 CGPA asks you about Big-O notation. Explain it the way you would in a 1-on-1 prep session — concrete, conversational, exam-relevant."
```

## Output

Big-O notation is nothing but a way to describe how your algorithm behaves as input grows. It's not about actual time in milliseconds — it's about the pattern of growth. That's the one-line definition I want you to memorize for TCS and Infosys interviews.

Think of it this way: if your array has 10 elements, your code runs fine. But what happens when TCS's interviewer says "what if the input is 10 million records?" — that's where Big-O matters.

Let me show you the 6 complexities that appear 90% of the time in placement tests, with the exact mental images I teach every student:

### Power Answer

> Docker is a containerization platform that packages applications and their dependencies into lightweight containers. These containers run consistently across different environments, making application deployment faster and more reliable.

## Self Score

**5/5**

---

# Pattern 2 — FEW-SHOT

## Prompt

```text
Here are example explanations from a DevOps trainer:

Q: What is an EC2 instance?

A: EC2 is a virtual server in AWS that allows you to run applications without buying physical hardware.

Q: What is Git?

A: Git is a version control system used to track and manage changes in source code.

Q: What is Docker?

A:
```

## Output

Docker is a containerization platform that packages applications and their dependencies into portable containers, ensuring they run consistently across different environments.

## Self Score

**3/5**

---

# Pattern 3 — CHAIN OF THOUGHT

## Prompt

```text
Explain Docker to a placement interview candidate.

Think step by step before answering.

Step 1: Define Docker in one sentence.

Step 2: Explain the purpose of Docker.

Step 3: Give a practical example.

Step 4: Explain why interviewers ask about Docker.

Step 5: Summarize everything in 3 concise interview-ready sentences.
```

## Output

### Step 1: Define Docker in one sentence.

Docker is a platform that uses containers to package and run applications consistently across environments.

### Step 2: Explain the purpose of Docker.

Docker eliminates the "it works on my machine" problem by bundling applications and dependencies together.

### Step 3: Practical example.

A developer creates a Spring Boot application and packages it into a Docker container. The same container runs successfully on a laptop, testing server, and production server.

### Step 4: Why interviewers ask about Docker.

Docker is widely used in modern software development and DevOps pipelines. Understanding Docker shows knowledge of deployment, scalability, and application portability.

### Step 5: Three interview-ready sentences.

Docker is a containerization platform that packages applications and their dependencies into portable containers. It ensures applications run consistently across development, testing, and production environments. Docker is a core DevOps tool used for faster deployment, scalability, and reliability.

## Self Score

**5/5**

---

# Pattern 4 — STRUCTURED OUTPUT

## Prompt

```text
Explain Docker for a placement interview.

Return ONLY valid JSON with this exact structure.

{
  "definition": "one-sentence definition",
  "purpose": "why Docker is used",
  "components": ["component1","component2","component3"],
  "real_world_example": "practical example",
  "common_mistake": "mistake students make",
  "interview_question": "follow-up interview question"
}
```

## Output

```json
{
  "definition": "Docker is a containerization platform that packages applications and their dependencies into lightweight, portable containers.",
  "purpose": "Docker ensures applications run consistently across different environments by bundling code, libraries, and configurations together.",
  "components": [
    "Docker Engine",
    "Docker Image",
    "Docker Container",
    "Dockerfile",
    "Docker Hub"
  ],
  "real_world_example": "A developer packages a Java application into a Docker container and runs it on multiple servers without modifying the application.",
  "common_mistake": "Students often confuse Docker containers with virtual machines and assume each container requires its own operating system.",
  "interview_question": "What is the difference between a Docker image and a Docker container?"
}
```

## Self Score

**5/5**
