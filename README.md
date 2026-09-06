# Ex.No.10

# Content Creation (Reports, Articles, Case Studies, etc.) Using Prompt Patterns

## Reg. No. 212223040185

## Aim:

To demonstrate how various prompting techniques such as Query Decomposition, Decision Making, Answer Engineering, Fact Check List, Tail Generation, Menu Actions, and Semantic Filtering can be used to create high-quality content such as reports, articles, case studies, and technical documents using ChatGPT.

# AI Tool Required:

**ChatGPT**

# Introduction:

Prompt patterns provide structured methods for communicating with AI models. Instead of using a single general instruction, different prompt patterns can be applied to break down a task, select suitable options, improve the structure of the response, verify important facts, extend the content, and control the tone and style.

For this experiment, two content-generation scenarios were selected:

1. **Research Paper on Artificial Intelligence**
2. **How to Build an E-commerce Website**

The generated content was progressively refined using different prompt patterns.

---

# PROCEDURE:

## 1. Introduction to Prompt Patterns

The following prompt patterns were used:

### 1. Query Decomposition

A complex task is divided into smaller and manageable subtasks.

### 2. Decision Making

The AI is asked to compare available choices and select the most suitable option.

### 3. Answer Engineering

Detailed instructions are provided regarding the structure, format, length, and style of the expected answer.

### 4. Fact Check List

The generated information is checked for factual consistency and unsupported claims.

### 5. Tail Generation

Additional instructions are given to extend the existing content with relevant details and deeper analysis.

### 6. Menu Actions

The AI is given multiple possible actions and asked to select an appropriate one.

### 7. Semantic Filter

The output is filtered according to specific requirements such as technical level, tone, audience, relevance, and writing style.

---

# TEST CASE 1: RESEARCH PAPER ON ARTIFICIAL INTELLIGENCE

## Step 1 – Basic Prompt

### Prompt:

```text
Write a short research paper about Artificial Intelligence.
```

### AI Tool:

**ChatGPT**

### Generated Output:

```text
Artificial Intelligence (AI) is a field of computer science that focuses on creating systems capable of performing tasks that normally require human intelligence. These tasks include learning, reasoning, problem-solving, perception, and language understanding.

AI is used in many areas such as healthcare, education, transportation, finance, and manufacturing. Machine learning and deep learning are important technologies used in modern AI systems.

AI provides many benefits, including automation, improved decision-making, and increased productivity. However, challenges such as privacy, bias, security, and ethical concerns must also be considered.

In the future, AI is expected to become increasingly important in both industry and everyday life.
```

### Observation:

The output is relevant but general. It does not have a proper research-paper structure or detailed sections.

---

# Step 2 – Query Decomposition

### Prompt:

```text
Break down the task of writing a research paper on Artificial Intelligence into the following sections:

1. Introduction
2. History of AI
3. Major AI technologies
4. Applications
5. Advantages
6. Challenges
7. Future scope
8. Conclusion

First create an outline and then explain what information should be included in each section.
```

### Generated Output:

```text
Research Paper Outline:

1. Introduction
   - Definition of Artificial Intelligence
   - Importance of AI

2. History of AI
   - Early development
   - Evolution of machine learning
   - Modern AI systems

3. Major AI Technologies
   - Machine Learning
   - Deep Learning
   - Natural Language Processing
   - Computer Vision
   - Generative AI

4. Applications
   - Healthcare
   - Education
   - Finance
   - Manufacturing
   - Transportation

5. Advantages
   - Automation
   - Improved efficiency
   - Data analysis
   - Decision support

6. Challenges
   - Privacy
   - Bias
   - Security
   - Ethical concerns

7. Future Scope
   - Advanced AI systems
   - Human-AI collaboration
   - Autonomous systems

8. Conclusion
   - Summary of the importance of responsible AI development
```

### Observation:

Query decomposition improved organization by dividing the complex research task into smaller sections.

---

# Step 3 – Decision-Making Prompt

### Prompt:

```text
For a CSE undergraduate research paper on Artificial Intelligence, choose the most suitable focus from these options:

A. AI in Healthcare
B. AI in Education
C. Generative AI and Large Language Models

Compare the three options based on technical relevance, current importance, availability of concepts to discuss, and suitability for a student research paper. Select the best option and explain your choice.
```

### Generated Output:

```text
Comparison:

AI in Healthcare:
- Strong real-world applications
- Includes medical diagnosis and prediction
- Requires understanding of healthcare-specific problems

AI in Education:
- Useful applications in personalized learning
- Easier to explain
- Comparatively narrower technical scope

Generative AI and Large Language Models:
- Highly relevant to current AI development
- Covers transformers, natural language processing, prompt engineering, and content generation
- Provides a broad technical scope for a CSE student

Selected Topic:

Generative AI and Large Language Models

Reason:

Generative AI and LLMs provide a strong combination of technical depth and current relevance. The topic allows discussion of neural networks, transformers, training, inference, applications, limitations, and ethical considerations.
```

### Selected Topic:

**Generative AI and Large Language Models**

---

# Step 4 – Answer Engineering

### Prompt:

```text
Write a structured educational research report titled
"Generative AI and Large Language Models".

Audience: CSE undergraduate students.

Use the following structure:

1. Abstract
2. Introduction
3. Fundamentals of Generative AI
4. Large Language Models
5. Transformer Architecture
6. Applications
7. Advantages
8. Limitations
9. Ethical Considerations
10. Future Scope
11. Conclusion

Use formal but easy-to-understand technical English. Use headings and short paragraphs. Avoid unsupported numerical claims.
```

### Generated Output:

```text
Title: Generative AI and Large Language Models

Abstract:

Generative Artificial Intelligence is a branch of AI that can create new content such as text, images, audio, video, and software code. Large Language Models are a major class of generative AI systems designed to understand and generate human language. Modern LLMs commonly use transformer-based architectures and are trained on large datasets.

Introduction:

Artificial Intelligence has developed from rule-based systems to machine learning and deep learning systems. Generative AI represents an important development because it enables machines to create new content based on learned patterns.

Large Language Models:

LLMs are neural-network-based models trained to process and generate language. They can perform tasks such as summarization, translation, question answering, code generation, and content creation.

Transformer Architecture:

Transformers use mechanisms such as attention to process relationships between tokens in a sequence. This architecture enables efficient processing of language and has become a foundation for many modern language models.

Applications:

Generative AI and LLMs are used in education, software development, customer support, content generation, research assistance, and information retrieval.

Advantages:

The technology can improve productivity, automate repetitive tasks, assist with writing and coding, and provide interactive interfaces for information processing.

Limitations:

LLMs can generate incorrect information, reflect biases in their training data, and require substantial computational resources. Human verification remains important for high-stakes applications.

Ethical Considerations:

Important concerns include privacy, bias, misinformation, copyright, transparency, and responsible use.

Future Scope:

Future AI systems are expected to become more capable, multimodal, efficient, and integrated with professional workflows.

Conclusion:

Generative AI and LLMs represent an important development in computer science. Their effective use requires both technical understanding and responsible human oversight.
```

---

# Step 5 – Fact Check List

### Prompt:

```text
Review the following AI research report using a fact-check checklist.

Check:
1. Whether technical concepts are correctly described.
2. Whether unsupported numerical claims are present.
3. Whether statements are exaggerated.
4. Whether AI limitations are acknowledged.
5. Whether ethical considerations are included.

List any statements that should be verified or rewritten.
```

### Generated Output:

```text
Fact-Check Result:

1. The definition of Generative AI is broadly correct.
2. The description of LLMs as neural-network-based models is correct.
3. The explanation of transformers and attention is broadly accurate.
4. No specific unsupported numerical claims were identified.
5. The report appropriately mentions limitations such as incorrect outputs and bias.
6. Ethical concerns including privacy, misinformation, copyright, and transparency are relevant.
7. Claims about future AI capabilities should be treated as possibilities rather than guaranteed outcomes.

Overall Assessment:

The report is suitable as an educational draft, but important technical claims should be verified against authoritative academic or technical sources before submission as a formal research paper.
```

---

# Step 6 – Tail Generation

### Prompt:

```text
Extend the previous report by adding a section explaining how Generative AI can assist software developers. Include practical examples such as code generation, debugging, documentation, testing, and learning. Maintain the same formal CSE undergraduate writing style.
```

### Generated Output:

```text
AI in Software Development:

Generative AI can assist software developers throughout the software development lifecycle. AI systems can generate code from natural-language descriptions and provide explanations of programming concepts.

During debugging, developers can provide an error message and relevant code and ask the AI to identify possible causes. AI can also generate documentation, comments, test cases, and example implementations.

However, generated code should be reviewed and tested because AI systems may produce syntactically valid but logically incorrect solutions. Therefore, AI should be considered an assistance tool rather than a replacement for software engineering knowledge.
```

---

# Step 7 – Semantic Filtering

### Prompt:

```text
Rewrite the research content using the following semantic filters:

Audience: CSE undergraduate students
Tone: Formal and educational
Difficulty: Intermediate
Style: Clear technical English
Length: Moderate
Avoid: Marketing language, exaggerated claims, unnecessary repetition
Focus: Technical understanding and responsible AI usage
```

### Observation:

Semantic filtering improved the consistency of the language and made the content more suitable for an academic audience.

---

# FINAL VERSION – TEST CASE 1

### Title: Generative AI and Large Language Models

### Abstract:

Generative Artificial Intelligence is a branch of artificial intelligence that produces new content such as text, images, audio, video, and software code. Large Language Models are generative AI systems designed to process and generate human language. Modern language models commonly use transformer-based architectures and are capable of performing tasks such as summarization, translation, question answering, and code generation.

### Introduction:

AI has evolved from rule-based systems to machine learning and deep learning technologies. Generative AI represents an important development because it allows computer systems to create new content based on patterns learned from data.

### Large Language Models:

Large Language Models are neural-network-based systems trained to process language. They can generate text, answer questions, summarize documents, translate languages, and assist with software development.

### Applications:

Generative AI is applied in education, healthcare, software development, customer support, research assistance, content creation, and information processing.

### Benefits:

Major benefits include automation, productivity improvement, assistance with programming and writing, and interactive access to information.

### Limitations:

AI systems may produce incorrect information, reflect biases, and require significant computational resources. Human review is necessary when accuracy is important.

### Ethical Considerations:

Privacy, bias, misinformation, copyright, transparency, and responsible use are important considerations when deploying generative AI.

### Future Scope:

Generative AI is expected to become increasingly multimodal and integrated into software and professional workflows. Continued research is required to improve reliability, efficiency, safety, and controllability.

### Conclusion:

Generative AI and Large Language Models are important technologies in modern computer science. Structured prompting can improve the usefulness and quality of AI-generated content, but human verification remains essential.

---

# TEST CASE 2: HOW TO BUILD AN E-COMMERCE WEBSITE

## Step 1 – Basic Prompt

### Prompt:

```text
Explain how to build an e-commerce website.
```

### Generated Output:

```text
To build an e-commerce website, first identify the requirements and choose the technology stack. Then design the user interface and develop the frontend and backend.

The website should include product listings, user registration, shopping cart functionality, order management, and payment integration. A database is required to store products and customer information.

After development, test the application for functionality and security and deploy it to a web server.
```

### Observation:

The response provides a general overview but does not provide a detailed development plan.

---

# Step 2 – Query Decomposition

### Prompt:

```text
Break down the development of an e-commerce website into the following stages:

1. Requirement analysis
2. UI/UX design
3. Frontend development
4. Backend development
5. Database design
6. Authentication
7. Shopping cart
8. Payment integration
9. Testing
10. Deployment

Explain the purpose of each stage.
```

### Generated Output:

```text
1. Requirement Analysis:
Identify users, products, features, and business requirements.

2. UI/UX Design:
Design pages such as the home page, product page, cart, login page, and checkout page.

3. Frontend Development:
Implement the user interface and user interactions.

4. Backend Development:
Create APIs and business logic for users, products, carts, and orders.

5. Database Design:
Store product, user, order, and payment-related information.

6. Authentication:
Implement secure registration and login.

7. Shopping Cart:
Allow users to add, remove, and modify products.

8. Payment Integration:
Connect the application to a suitable payment gateway.

9. Testing:
Test functionality, security, performance, and usability.

10. Deployment:
Deploy the frontend, backend, and database using appropriate hosting infrastructure.
```

---

# Step 3 – Decision-Making Prompt

### Prompt:

```text
Choose a suitable technology stack for a beginner CSE student developing a small e-commerce website.

Compare:

Option A: HTML, CSS, JavaScript, Node.js, Express, MongoDB
Option B: React, Node.js, Express, MongoDB
Option C: React, Spring Boot, MySQL

Compare learning difficulty, development speed, scalability, and suitability for a student project. Select one option.
```

### Generated Output:

```text
Option A:
Simple and beginner-friendly. Suitable for understanding fundamental web development concepts.

Option B:
Provides a modern frontend framework while keeping JavaScript across the stack. Suitable for a more advanced student project.

Option C:
Provides a strong enterprise-oriented architecture but requires learning Java, Spring Boot, and additional concepts.

Selected Option:

Option B – React, Node.js, Express, and MongoDB.

Reason:

It provides a modern full-stack development approach while allowing the student to use JavaScript across frontend and backend development. It is suitable for building a feature-rich academic project.
```

---

# Step 4 – Menu Actions

### Prompt:

```text
You are developing an e-commerce website. Choose the next development action from the following menu:

A. Create product database
B. Build shopping cart
C. Implement authentication
D. Create payment integration
E. Deploy the application

Select the most appropriate action to perform first and explain why.
```

### Generated Output:

```text
Selected Action:

A. Create product database

Reason:

Product information is fundamental to an e-commerce application. Before implementing the shopping cart and other features, the application needs a structured way to store and retrieve product information.
```

---

# Step 5 – Answer Engineering

### Prompt:

```text
Create a structured development plan for a small e-commerce website using React, Node.js, Express, and MongoDB.

Include:
1. Architecture
2. Frontend modules
3. Backend modules
4. Database collections
5. API examples
6. Authentication
7. Testing
8. Deployment

Present the information using headings and tables. Use simple technical English suitable for a CSE undergraduate project.
```

### Generated Output:

```text
Architecture:

React Frontend → Express/Node.js Backend → MongoDB Database

Frontend Modules:

- Home Page
- Product Listing
- Product Details
- Shopping Cart
- Login/Register
- Checkout
- Order History

Backend Modules:

- User API
- Product API
- Cart API
- Order API
- Authentication API

Database Collections:

- Users
- Products
- Orders
- Cart

Example APIs:

GET /products
GET /products/:id
POST /users/register
POST /users/login
POST /orders
GET /orders/:userId
```

---

# Step 6 – Fact Check List

### Prompt:

```text
Fact-check the e-commerce development plan.

Check whether:
1. React can be used for frontend development.
2. Node.js and Express can provide backend functionality.
3. MongoDB can store application data.
4. REST-style APIs can be used for communication.
5. Authentication is necessary for protected user operations.

Identify anything that requires clarification.
```

### Generated Output:

```text
Fact-Check Result:

1. React is suitable for developing the frontend.
2. Node.js can execute JavaScript on the server and Express can be used to build web APIs.
3. MongoDB is a database system suitable for storing application data.
4. REST-style APIs can be used to communicate between frontend and backend.
5. Authentication is appropriate for protecting user-specific operations.

Clarification:

Payment processing should normally be performed through a trusted payment provider rather than storing sensitive payment-card information directly in the application database.
```

---

# Step 7 – Semantic Filtering

### Prompt:

```text
Rewrite the e-commerce development plan for a CSE undergraduate student.

Use:
- Formal technical tone
- Beginner-friendly explanations
- Clear headings
- Practical examples
- Moderate level of detail

Avoid:
- Unnecessary advanced cloud concepts
- Marketing language
- Excessive technical jargon
```

### Generated Output:

```text
The e-commerce website should follow a simple three-layer structure consisting of a React frontend, Node.js/Express backend, and MongoDB database.

The frontend provides pages for browsing products, viewing product details, managing the shopping cart, logging in, and placing orders.

The backend manages business logic and provides APIs for users, products, carts, and orders.

The database stores application information such as users, products, and orders.

Security should be considered throughout development, particularly for authentication and user data. Payment processing should use a trusted payment provider.
```

---

# FINAL VERSION – TEST CASE 2

## How to Build an E-commerce Website

### 1. Requirement Analysis

The first stage is to identify the users and required features. A basic e-commerce website should allow users to browse products, create accounts, add products to a cart, place orders, and view their order history.

### 2. Technology Stack

The selected technology stack is:

| Component   | Technology         |
| ----------- | ------------------ |
| Frontend    | React              |
| Backend     | Node.js + Express  |
| Database    | MongoDB            |
| API         | REST-style API     |
| Development | Visual Studio Code |

### 3. System Architecture

```text
User
  ↓
React Frontend
  ↓
Node.js + Express Backend
  ↓
MongoDB Database
```

### 4. Frontend Modules

* Home Page
* Product Listing
* Product Details
* Login/Register
* Shopping Cart
* Checkout
* Order History

### 5. Backend Modules

* User Management
* Product Management
* Cart Management
* Order Management
* Authentication

### 6. Database

The database can contain collections such as:

```text
Users
Products
Orders
Cart
```

### 7. Testing

The application should be tested for:

* User registration
* Login
* Product display
* Cart operations
* Order creation
* Invalid inputs
* Authentication
* API responses

### 8. Security

Authentication, authorization, input validation, secure password handling, and protection of sensitive information should be considered during development.

Payment processing should use a trusted payment provider rather than storing sensitive payment-card information directly in the application.

### 9. Deployment

After testing, the frontend, backend, and database can be deployed using suitable hosting services.

### Conclusion:

A structured development process makes an e-commerce project easier to design, implement, test, and maintain.

---

# Multiple Versions Comparison

| Feature          | Basic Prompt | Refined Prompt | Final Prompt |
| ---------------- | ------------ | -------------- | ------------ |
| Structure        | Low          | Medium         | High         |
| Technical Detail | Low          | Medium         | High         |
| Audience Control | No           | Partial        | Yes          |
| Formatting       | Basic        | Structured     | Structured   |
| Fact Checking    | No           | Yes            | Yes          |
| Relevance        | General      | Good           | High         |
| Overall Quality  | Moderate     | Good           | Very Good    |

---

# Overall Evaluation

| Evaluation Criteria  | Basic Prompt | Refined Prompt | Final Prompt |
| -------------------- | -----------: | -------------: | -----------: |
| Coherence            |          3/5 |            4/5 |          5/5 |
| Relevance            |          3/5 |            4/5 |          5/5 |
| Structure            |          2/5 |            4/5 |          5/5 |
| Technical Depth      |          2/5 |            4/5 |          5/5 |
| Accuracy             |          3/5 |            4/5 |          5/5 |
| Audience Suitability |          2/5 |            4/5 |          5/5 |
| Overall Quality      |        15/30 |          24/30 |        30/30 |

---

# Analysis and Observations

1. Basic prompts produced general content with limited structure.
2. Query decomposition improved the organization of complex tasks.
3. Decision-making prompts helped select suitable topics and technologies.
4. Answer engineering improved the format and structure of the generated content.
5. Fact-check prompts helped identify statements that require verification or clarification.
6. Tail generation added relevant depth to the original content.
7. Menu actions allowed the AI to select the most appropriate next step from multiple choices.
8. Semantic filtering helped control tone, audience, technical complexity, and relevance.
9. Combining multiple prompt patterns produced more structured and useful content than a simple prompt.
10. Human review is still necessary, especially for factual, technical, and research-oriented content.

---

# Final Selected Prompt Pattern:

**Combination of Query Decomposition + Decision Making + Answer Engineering + Fact Check List + Semantic Filtering**

### Reason:

A combination of prompt patterns produced the most complete result because each pattern addressed a different part of the content-generation process. Query decomposition organized the task, decision making selected appropriate directions, answer engineering controlled the format, fact checking improved reliability, and semantic filtering ensured that the final content matched the intended audience.

# Final Refined Prompt:

```text
Act as an experienced technical content writer and CSE mentor.

Create a structured academic document on [TOPIC] for undergraduate CSE students.

First decompose the topic into logical sections. Then identify the most relevant concepts to include.

Use:
- Formal but easy-to-understand technical English
- Clear headings and subheadings
- Tables wherever useful
- Practical examples
- Logical flow between sections
- Moderate technical depth

Check the content for unsupported or exaggerated claims and identify information that requires verification.

Filter the final content to remove unnecessary repetition, marketing language, and irrelevant information.

Finally, provide a polished, coherent, and academically suitable document with an introduction, main discussion, applications/examples, limitations, future scope, and conclusion.
```

# Conclusion:

The experiment demonstrated that different prompt patterns can significantly improve AI-generated content. Basic prompts are useful for obtaining initial ideas, while advanced patterns such as query decomposition, decision making, answer engineering, fact checking, tail generation, menu actions, and semantic filtering provide greater control over the generated output.

By combining multiple prompt patterns, the final content became more coherent, structured, relevant, technically detailed, and suitable for the intended audience.

# RESULT:

Thus, various prompt patterns were successfully applied to generate and refine content for two different scenarios. The experiment demonstrated that structured prompting improves the quality, coherence, accuracy, organization, and usefulness of AI-generated reports and technical content.
