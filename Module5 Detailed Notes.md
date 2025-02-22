### Detailed Notes on Module 5: Advanced Topics

#### 5.1 Cloud Native Applications

**Definition:**
- Cloud native applications are designed to take full advantage of the cloud computing model, leveraging its characteristics to build scalable, resilient, and manageable applications.

**Characteristics of Cloud Native Applications:**
- **Microservices-Based:** Applications are built as a collection of small, independent services that communicate over well-defined APIs.
- **Serverless Architecture:** Applications run in a serverless environment where the cloud provider manages the infrastructure, allowing developers to focus on code.
- **Container-Based:** Applications are packaged in containers, which include all dependencies, ensuring consistency across different environments.
- **Dynamically Orchestrated:** Tools like Kubernetes are used to manage the deployment, scaling, and operation of containerized applications.

**Microservices Architecture:**
- **Definition:** A software engineering approach where applications are developed as a collection of small, independent service units.
- **Benefits:**
  - **Scalability:** Each microservice can be scaled independently.
  - **Resilience:** Failure in one microservice does not affect the entire application.
  - **Flexibility:** Different technologies can be used for different microservices.
  - **Faster Development:** Teams can work on different microservices simultaneously.

**Serverless Architecture:**
- **Definition:** A way to build and run applications without managing the underlying infrastructure. The cloud provider handles server management.
- **Benefits:**
  - **No Server Management:** Developers focus on code, not infrastructure.
  - **Automatic Scaling:** The cloud provider automatically scales the application based on demand.
  - **Cost Efficiency:** Pay only for the compute time consumed.

**Diagram: Cloud Native Applications**
!Cloud Native Applications

#### 5.2 Infrastructure as Code (IaC)

**Definition:**
- Infrastructure as Code (IaC) is the management and provisioning of infrastructure through code instead of manual processes.

**Approaches to IaC:**
- **Declarative Approach:** Defines the desired state of the system, including required resources and their properties. The tool then creates the infrastructure.
  - *Example:* Terraform, AWS CloudFormation.
- **Imperative Approach:** Lists specific commands to achieve the desired configuration, executed in the correct order to create the infrastructure.
  - *Example:* Ansible, Chef.

**Test Levels for IaC:**
- **Static Testing:** Analyzing the code without executing it to find potential issues.
- **Unit Testing:** Testing individual components of the infrastructure code.
- **System Testing:** Testing the entire system to ensure it meets requirements.
- **System Integration Testing:** Testing the integration of different components to ensure they work together.

**Diagram: Infrastructure as Code (IaC)**
!Infrastructure as Code (IaC)

#### 5.3 Testing in Production (TiP)

**Definition:**
- Testing in Production (TiP) involves testing software in the production environment to ensure it works as expected under real-world conditions.

**Types of TiP Tests:**
- **A/B Testing:** Releasing two versions of a website, app, or feature to gauge user preference.
- **Canary Testing:** Incrementally rolling out the product to a larger set of users to prevent large-scale failures and get early feedback.
- **Blue/Green Testing:** Deploying on a non-live system, fully testing it, and then switching the router to direct all incoming requests to the tested system.
- **Rolling Update Testing:** Updating a subset of the running application instead of all instances simultaneously to contain failures.

**Chaos Testing:**
- **Definition:** Testing a system's integrity by proactively simulating and identifying failures in a given environment.
- **Requirements:**
  - **Tools:** Tools to inject faults and monitor the system (e.g., Chaos Monkey, Gremlin).
  - **Production Environment:** Running tests in a production environment to get accurate results.
- **Benefits:**
  - **Resilience:** Ensures the system can handle unexpected failures.
  - **Reliability:** Improves the overall reliability of the system.

**Diagram: Testing in Production (TiP)**
!Testing in Production (TiP)

### Example Questions

1. **What are cloud native applications and what are their key characteristics?**
2. **Explain the benefits of a microservices architecture.**
3. **What is serverless architecture and what are its advantages?**
4. **Define Infrastructure as Code (IaC) and describe its approaches.**
5. **List the different test levels for IaC.**
6. **What is Testing in Production (TiP) and what are its types?**
7. **Explain the concept of chaos testing and its benefits.**

### Multiple Choice Questions (MCQs)

1. **Which of the following is a characteristic of cloud native applications?**
   - A) Monolithic architecture
   - B) Serverless architecture
   - C) Manual scaling
   - D) Static deployment
   - **Answer:** B) Serverless architecture

2. **What is the main benefit of using a microservices architecture?**
   - A) Increased server management
   - B) Independent scalability of services
   - C) Single point of failure
   - D) Slower development
   - **Answer:** B) Independent scalability of services

3. **Which approach to IaC defines the desired state of the system?**
   - A) Declarative Approach
   - B) Imperative Approach
   - C) Static Approach
   - D) Dynamic Approach
   - **Answer:** A) Declarative Approach

4. **What is the purpose of A/B testing in TiP?**
   - A) To test the entire application workflow
   - B) To gauge user preference between two versions
   - C) To simulate failures in the system
   - D) To update all instances simultaneously
   - **Answer:** B) To gauge user preference between two versions

5. **Which tool is commonly used for chaos testing?**
   - A) Terraform
   - B) Ansible
   - C) Chaos Monkey
   - D) Docker
   - **Answer:** C) Chaos Monkey

