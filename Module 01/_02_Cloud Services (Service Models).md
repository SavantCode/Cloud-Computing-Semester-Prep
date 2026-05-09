

---

# Cloud Services (Service Models)

Cloud services define **how cloud resources are provided to users**.
Instead of buying hardware or installing software locally, users can **access computing services through the internet**.

Cloud computing mainly provides **three service models**:

1. **Infrastructure as a Service (IaaS)**
2. **Platform as a Service (PaaS)**
3. **Software as a Service (SaaS)**

These models differ based on **how much control the user has and what the cloud provider manages**.

---

# 1. Infrastructure as a Service (IaaS)

![Image](https://images.openai.com/static-rsc-3/i7hU3LKYezoHGt_XSc5o94EAR6BrMx0LQLWqf4lgI7991tKwVk0OC_s73QNAj9ivj09nV4e0CEOH-aeTwTa8aBBZkWsVpvhbF3wTSS51mZc?purpose=fullsize\&v=1)

![Image](https://images.openai.com/static-rsc-3/9nRjhGpyl0BWcLuQJBEqGlJRWiM1q214DzitCFdQflKCQkvHgGWRdMm3zITiPrfsbtfUf9R_wageFEg_5HiBSUkTuXYWcMF7roRdHA5x4-E?purpose=fullsize\&v=1)

![Image](https://www.researchgate.net/publication/349297686/figure/fig1/AS%3A1078633988915202%401634177791357/aaS-service-network-IaaS-model-components-include-Computer-Hardware-Network-and-Internet.ppm)

![Image](https://webimages.mongodb.com/_com_assets/cms/l1nldf38un1vw8nnz-image6.png?auto=format%252Ccompress)

## Definition

tructure as a Service (IaaS) provides **basic computing infrastructure such as virtual machines, storage, and networking over the internet**.

The cloud provider manages **hardware and virtualization**, while the user manages **operating systems and applications**.

---

## What the Cloud Provider Manages

* Physical servers
* Data centers
* Storage devices
* Networking
* Virtualization

---

## What the User Manages

* Operating system
* Applications
* Middleware
* Data

---

## Example Providers

Examples include:

* Amazon Web Services EC2
* Google Cloud Compute Engine
* Microsoft Azure Virtual Machines

---

## Example Scenario

A startup wants to launch a website but **doesn't want to buy expensive servers**.

Instead they:

1. Rent a **virtual server from AWS**
2. Install **Linux OS**
3. Deploy their **web application**

---

## Advantages

* No need to buy hardware
* Highly scalable
* Flexible infrastructure
* Pay-as-you-use pricing

---

## Disadvantages

* Requires technical knowledge
* User must manage OS and security

---

# 2. Platform as a Service (PaaS)
![Image](https://images.openai.com/static-rsc-3/EcoEtrlm3KLiqU9Cii7t2TOpmoN3YJ3Rwox1OaNmhPt1QjJKSzeY2i8OfQ6bDtCfuOFEzn_xhWI4hSVE37vkxD7bWtiK0edXxuN4Z32-fUQ?purpose=fullsize\&v=1)


![Image](https://images.openai.com/static-rsc-3/UH4Eqr82pkQXV1twgD3YaCtWmYKI2gLXBN4Jc_PiWhsg7XRbJGub6TjdWm4IbdvGPHGyHVMZ-K0oTO3v5wbOSG8-3VnuSq7OGvkCOJIW5e4?purpose=fullsize\&v=1)

![Image](https://www.tutorialspoint.com/cloud_computing/images/cloud_computing-paas.jpg)

![Image](https://cdn.prod.website-files.com/65a790f0493b6806e60d6e21/6662b78dc707238ead7be590_64dca66820aece818c886638_Navigating%2520the%2520AWS%2520Cloud%2520Stack.png)

![Image](https://media.licdn.com/dms/image/v2/C4E12AQGLyziDZJD5Tw/article-inline_image-shrink_1000_1488/article-inline_image-shrink_1000_1488/0/1520117158477?e=1772668800\&t=1fVznamIHUerc0XyjO9-f8t0RkL6N-EcaFkpnHli9gA\&v=beta)

## Definition

Platform as a Service (PaaS) provides a **complete development platform for building, testing, and deploying applications without managing underlying infrastructure**.

Developers focus only on **writing code**, while the cloud provider manages the platform.

---

## What the Cloud Provider Manages

* Servers
* Storage
* Networking
* Operating system
* Runtime environment
* Development tools

---

## What the User Manages

* Application code
* Application data

---

## Example Providers

Examples include:

* Google Cloud App Engine
* Microsoft Azure App Services
* Heroku

---

## Example Scenario

A developer wants to build a **web application**.

Instead of configuring servers, they:

1. Upload code to **Google App Engine**
2. The platform automatically:

   * deploys the app
   * manages servers
   * handles scaling

---

## Advantages

* Faster development
* No infrastructure management
* Automatic scaling
* Built-in development tools

---

## Disadvantages

* Limited control over environment
* Dependency on provider platform

---

# 3. Software as a Service (SaaS)

![Image](https://images.openai.com/static-rsc-3/0cb-J38hjPzb-W8cuAjn6v5-yh1Lxwrt0kSFLR57cB_GmGQEkAFWKkT6OZtQcsmfXGR6H40LpEoJ8WFTiHxMAXXUVMpTIltnAIvAJZSB0ww?purpose=fullsize\&v=1)

![Image](https://cf-assets.www.cloudflare.com/slt3lc6tev37/nYGOTtGurrQP09eqHsPPc/061e3045461d9fcea702db8ae9a45a67/saas-application-remote-access.svg)

![Image](https://images.openai.com/static-rsc-3/J4Gepbg1w8qnOvvahs95cGRP7R-nAZTDjujXTx4a6bcTWBDhLsI7wSPDY-gbF2YEBsRytin3lmI2s6LQ2GAo23HYktHZizNSzROQKiAsi58?purpose=fullsize\&v=1)

![Image](https://images.openai.com/static-rsc-3/UH4Eqr82pkQXV1twgD3YaCtWmYKI2gLXBN4Jc_PiWhsg7XRbJGub6TjdWm4IbdvGPHGyHVMZ-K0oTO3v5wbOSG8-3VnuSq7OGvkCOJIW5e4?purpose=fullsize\&v=1)

## Definition

Software as a Service (SaaS) provides **complete software applications over the internet**.

Users can access software through **web browsers without installing or maintaining it**.

The cloud provider manages **everything** including infrastructure, platform, and software.

---

## What the Cloud Provider Manages

* Servers
* Storage
* Networking
* Operating system
* Platform
* Software applications
* Security and updates

---

## What the User Does

Users simply:

* login
* use the application

No installation required.

---

## Examples

Popular SaaS applications include:

* Google Docs
* Microsoft Office 365
* Salesforce CRM
* Gmail

---

## Example Scenario

Instead of installing Microsoft Office on a computer, users can simply:

1. Open **Office 365 in browser**
2. Create documents online
3. Store them in the cloud

---

## Advantages

* No installation required
* Accessible anywhere
* Automatic updates
* Lower cost

---

## Disadvantages

* Internet dependency
* Limited customization
* Data privacy concerns

---

# Key Difference Between IaaS, PaaS, SaaS

| Feature          | IaaS          | PaaS                | SaaS       |
| ---------------- | ------------- | ------------------- | ---------- |
| Control          | High          | Medium              | Low        |
| User manages     | OS + apps     | Only apps           | Nothing    |
| Provider manages | Hardware      | Platform + hardware | Everything |
| Target users     | System admins | Developers          | End users  |

---

# Easy Way to Remember (Exam Trick)

Think of **Pizza Analogy** 🍕

| Model | Responsibility                             |
| ----- | ------------------------------------------ |
| IaaS  | You cook pizza with provided kitchen       |
| PaaS  | Restaurant prepares base, you add toppings |
| SaaS  | Fully cooked pizza delivered               |

---

✅ Rahul, next in your syllabus is:

**Benefits and Challenges of Cloud Computing**

This is also a **very important 14-mark exam question**.

If you want, I can also explain:

* **Usage Scenarios of Cloud Computing**
* **Applications of Cloud Computing**
* **Migration and Integration challenges**

These are usually **long-answer questions in exams.**
