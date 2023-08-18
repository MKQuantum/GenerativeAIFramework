# Enterprise Governance Framework for Generative AI
<img width="600" alt="image" src="https://user-images.githubusercontent.com/121593006/236930142-97eb9410-6d36-4634-90ca-ca1009a775bb.png">

## This opinionated Framework covers both Enterprise Deployments of Generative AI solutions within common tools like Office or Development IDEs - as well as the internal Development and Deployment of proprietary services and applications.

<img width="1680" alt="image" src="https://github.com/MKQuantum/GenerativeAIFramework/assets/121593006/0ada2a3d-569c-46ec-9c66-bd2c97e7ab5d">

There are several considerations which will be important for adoption: 

* Most of the Enterprise Deployment items will already exist in an Enterprise so they should be leveraged when possible.
* Generative AI will soon be ubiquitous in every aspect of the Enterprise so Governance will need to be an enabler and allow for growth - but with guardrails.
* Layered approach to Governance for Deployment of services and Creation of new solutions
* Start with the basics of Governance and build from there
* There is no "one size fits all" Governance and your Framework will need to change over time
* Provide Risk Management and Audit groups a baseline of what the "ideal state" looks like
* Invest in your teams with Education and Coaching
* Provide enough Risk Coverage to help the Enterprise understand how their [Risk Appetite](https://www.theirm.org/what-we-say/thought-leadership/risk-appetite-and-tolerance/) is affected


## GenAIOps

<details>
  <summary>Generative AI Development and Operations</summary>
  <br>
  
[DevOps](https://resources.github.com/devops/) and [MLOps](https://www.databricks.com/glossary/mlops#:~:text=MLOps%20stands%20for%20Machine%20Learning,then%20maintaining%20and%20monitoring%20them.) culture and best practices can help Development teams get their solutions to Production in standardized, repeatable, secure, and optimized workflows.

These best practices can be applied to Generative AI to help teams create solutions and deploy them in Enterprises.

The following opinionated GenAI DevOps Pipelines could be combined with a Lightweight Technology Policy and Standard to provide an Enterprise with holistic and practical guidelines for the following:

- [ ] Repeatable processes and enterprise approved tools to develop and deploy Generative AI solutions
- [ ] High level Enterprise statement of objectives, and realistic way of realizing goals
- [ ] Mandatory requirements that support the Technology Policy

<details>
  
  <summary>GenAI Technology Policy</summary>
<br>

  | Policy Domain | Domain Details |
| ------------- | ------------- |
| **Policy Statement**  | Generative AI is becoming an ubiquitous technology within Business and Technology, and it is the policy of the Enterprise to protect all company data and development assets, as well as customer information, from exposure that would violate regulatory requirements and the Enterprise Risk Appetite   during the Development, Testing, and Deployment of GenAI solutions.  <br /> <br /> The Policy may also be considered a Code of Conduct, or [Code of Pratice](https://ised-isde.canada.ca/site/ised/en/consultation-development-canadian-code-practice-generative-artificial-intelligence-systems/canadian-guardrails-generative-ai-code-practice) which could align to Government Regulations such as the [Artificial Intelligence and Data Act (AIDA)](https://ised-isde.canada.ca/site/innovation-better-canada/en/artificial-intelligence-and-data-act-aida-companion-document) which is being designed to guide AI in a positive direction for all Canadians. It will also be a living document to remain aligned to continuously changing EU and UA regulations; such as [EU AI Act](https://www.europarl.europa.eu/news/en/headlines/society/20230601STO93804/eu-ai-act-first-regulation-on-artificial-intelligence) and the [National AI Commission Act.](https://www.congress.gov/bill/118th-congress/house-bill/4223?s=1&r=1) |
| **Policy Context** | Internal Generative AI development and deployments that are created within the Enterprise - leveraing tools, services, and models provided from internal or external sources. |
| **Development & Operations Responsibilities** | All Development and Operations staff are responsible for protecting corporate and customer data and information during GenAI development.  Details on appropirate tools, services, APIs, Open Source resources which are found in the GenAI Technology Standard, will be followed.
| **Risk and Audit Responsibilities** | Risk, Governance, and Internal Audit will perform [periodic reviews](https://user-images.githubusercontent.com/121593006/237275890-18b67040-f719-42ab-8ca4-68961acade3b.png) of GenAI development solutions that are holistic and included all phases of the software lifecycle - including Production monitoring and retraining of relevant models. |
| **Multi-Disciplinary Teams Responsibilities** | Teams such as HR and Legal will need to be informed of Generative AI development within an Enterprise for legal considerations as well as HR onboarding and training requirements for relevant employees.  |
| **Owner** | Enterprise Owner (will vary for each Enterprise) |
  
  <br>
  
</details>

<details>

<summary>GenAI Technology Standard</summary>

<br>

 | Standard Domain | Domain Details |
| ------------- | ------------- |
| **Description of Standard** | While there are standards being created to address the users of [consumer generative AI services](https://rankingdigitalrights.org/mini-report/introducing-rdrs-preliminary-standards-for-generative-ai/), this standard is focused on providing mandatory guardrails and requirements to support an Enterprise's Policy for internal Development, Testing, and Deployment of Generative AI solutions. |
| **Standard Specification** | All internal Development of Generative AI services and applications will adopt the following guardrails and requirements: <br /><br /> 1. Traditional software delivery, QA Testing. and DevOps best practices will be followed. <br /> 2. Generative AI Services & Tools will follow a standard intake process that includes a review of data, service/tool provide, cloud roadmap, risk appetite, and use case.  <br /> 3. [Prompt Engineering Best Practices](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/prompt-engineering#best-practices) will be followed for all services or applications that leverage prompt-based models. <br /> 4. The Large Language Models used for the services and applications will be documented and details will be made available to Risk and Governance teams, Internal and Exeternal Audit, and other stakeholders on demand. <br /> 5. If an Enterprise's own data to generate prompt responses, only approved [Retrieval Augmented Generation](https://learn.microsoft.com/en-us/azure/machine-learning/concept-retrieval-augmented-generation?view=azureml-api-2#:~:text=Retrieval%20Augmented%20Generation%20(RAG)%20is,is%20currently%20in%20public%20preview) will be leveraged. <br /> 6. Developers will complete training courses which provide a fundamental background on Generative AI ([Microsoft AI Fundamentals for example](https://learn.microsoft.com/en-us/certifications/exams/ai-900/)). As well as training specific for Generative AI Development ([OpenAI Services Training for example](https://learn.microsoft.com/en-us/training/paths/develop-ai-solutions-azure-openai/))
| **Where to Apply This Standard** | This standard applies to all Development and Delivery teams within the Enterprise - including external developers and engineers who are working on proprietary applications and services. |
| **Owner** | Enterprise Owner (will vary for each Enterprise) | 

<br>

| **Standard Terms** | **Description**  |
| :-----: | :---: |
| Generative AI (GenAI) | Generative AI is a type of artificial intelligence technology that can produce various types of content, including text, imagery, audio and synthetic data. ([techtarget.com](https://www.techtarget.com/searchenterpriseai/definition/generative-AI))  |
| Large Language Models (LLM)| A large language model, or LLM, is a deep learning algorithm that can recognize, summarize, translate, predict and generate text and other content based on knowledge gained from massive datasets. ([nvidia.com](https://blogs.nvidia.com/blog/2023/01/26/what-are-large-language-models-used-for/#:~:text=A%20large%20language%20model%2C%20or,successful%20applications%20of%20transformer%20models.))  |
| Retrieval Augmented Generation| RAG retrieves data from outside the language model and augments the prompts by adding the relevant retrieved data in context ([AWS](https://aws.amazon.com/blogs/machine-learning/question-answering-using-retrieval-augmented-generation-with-foundation-models-in-amazon-sagemaker-jumpstart/#:~:text=To%20solve%20the%20constraints%20we,introduced%20by%20Lewis%20et%20al.))   |
| AI Hallucinations| When an AI is perceiving something that is not real. |

<br>

| **Standard Servies & Tools Review Topics** | **Description**  |
| :-----: | :---: |
| Review Context| To help enable Enterprises with onboarding of Services and Tools, the following topics could be leveraged as a checklist to help streamline governance and security reviews by providing a baseline set of criteria. |
| Enterprise Cloud Provider | Cloud Provider's such as AWS and Azure have started releasing Generative AI tools, APIs, and Services (GenAI Development as a Service for example) such as [Azure Promptflow](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/harness-the-power-of-large-language-models-with-azure-machine/ba-p/3828459) and [Amazon Kendra](https://aws.amazon.com/blogs/machine-learning/quickly-build-high-accuracy-generative-ai-applications-on-enterprise-data-using-amazon-kendra-langchain-and-large-language-models/).  If the Enterprise preferred Cloud Provider provided Generative AI development tooling, it may be easier to have the service or tool certified for Enterprise use.  |
| Service Certification | An Enterprise may already have a process in place to Certify Cloud services or tooling with existing checklists for common topics such as security, traceability, audit, logging, and etc.  Tools such as Azure Promptflow or Amazon Kendra could also be onboarded leveraging existing processes like this - providing Governance decision makers with criteria and review topices they are familiar with. |
| Open Source Maturity | If the Enterprise has an existing [Open Source Program Office](https://github.blog/2023-03-13-an-open-source-project-to-empower-ospos-everywhere/) and is comfortable with the use of Open Source tooling, leveraging Generative AI Open Source services and tools should follow existing processes.  But, for an Enterprise that does not currently have governance and management in place for Open Source tools, the overhead of onboarding new tools available in the Open Source community may be too time consuming.  Tools provided by preferred Cloud Providers may be a better option until Open Source maturity has increased. |
| Enterprise Industry | An Enterprise security stance and risk appetite will be driven by its Industry.  For example, Financial Institutions, Retail, Insurance, and Health Care companies all have different regulations and requirements that drive all of their decisions regarding services and tools.  When making a decision on Generative AI development services and tools, its important to consider what regulations or requirements will need to be followed.  For example. if an Enterprise is developing a Generative AI application for processes that are related to financial reporting, they may need to consider the controls that will be reviewed as part of a [SOX Audit](https://www.sarbanes-oxley-101.com/sarbanes-oxley-audits.htm).  However, if the Enterprise process is not related to requlations or requirements, there will be more lenient controls and security controls. |
| Data Classification | Any decisions on services or tooling that will be leveraged for Generative AI development should factor in the classification of the data that will be leveraged by the Language Models.  Data controls and governance for restricted or confidential data are much more strict than internal or public data. |
|Data Residency | There are data residency requirements for regions around the World which need to be considered for Generative AI development.  For example, the [General Data Protection Regulation](https://www.wired.co.uk/article/what-is-gdpr-uk-eu-legislation-compliance-summary-fines-2018) requires personal data for EU residents needs to stay in the EU.  This is an important consideration for Open Source tools or other Services that may be sending data to other regions around the world. |
| Enterprise Risk Appetite | The [Enterprise Risk Appetite](https://www.theirm.org/what-we-say/thought-leadership/risk-appetite-and-tolerance/) is the amount of risk an Enterprise is willing to take on to meet its objectives.  This is an important factor for Generative AI development since its such a game-changer for the Industry.  An Enterprise who has bee traditionally conservative may update their Risk Appetite to take advantage of the tremendous potential of Generative AI Capabilities.  | 

</details>

<img width="1670" alt="image" src="https://github.com/MKQuantum/GenerativeAIFramework/assets/121593006/0bbb1c17-ce08-4405-aec9-fee233cf8565">


</details>

## Intake

<details>
  <summary>Entry Point of Governance</summary>
  <br>
The intake is the entry point for a Governance Framework and may be different for various teams in the Enterprise.  Teams that are using Generative AI apps as a Service, such as leveraging it within an Excel sheet, will have a different entry point then teams that are creating solutions.  With the proliferation of Generative AI within browsers and other ubiquitous tools, understanding the existing security and access controls of existing tools and platforms may be a good starting point to provide assurance that risks are covered.

For situations where teams are leveraging Generative AI services that are provided within an Enterprises in a controlled manner, a web form with the following details may be also be a possibility:

- [ ] Name
- [ ] Department
- [ ] Use case
- [ ] Approvals from one-up Manager Name

For development teams that are creating solutions, the Enterprises existing processes to control Open Source dependencies and access controls to development environments could act as the first layer of defense.  
</details>

## Training
<details>
  <summary>Increasing User Literacy</summary>
  <br>
While training AI Models is important, it is equally as important to train your Enterprise users to help increase their Generative AI literacy.  Training is important for all new concepts and technologies within an Enterprise, but is even more important for technologies such as Generative AI that will have a profound effect on users daily work - and the risk appetite of the Enterprise.

Some example of Training courses that could be provided are:

- [ ] High Level Introduction to AI (What is AI? What are considerations for society and business?)
- [ ] Understanding Risk and Bias in AI
- [ ] DevOps and Cloud Native best practices fo AI
- [ ] Generative AI Introduction
- [ ] Generative AI Development

</details>

## Policies
<details>
  <summary>Enterprise Policies</summary>
  <br>
Effective Enterprise Policies need to include some basic components to be effective:

* Endorsed by Leadership
* Relevant to Enterprise Values
* Realistic and Measurable
* Scalable as the Enterprise Transforms
* Most Importantly - Enforceable

The Enterprise will need to make a decision whether to add Generative AI considerations into their existing Policies (Data, Cybersecurity, Development, etc.) or create new Policies and Procedures specifically for Generative AI.

With each approach, the following considerations may need to be addressed:

- [ ] Transparency on how the Enterprise will use Generative AI (Text Generation for example)
- [ ] Show stakeholder involvement from across the Enterprise (Legal, Tech, Business, HR, etc.)
- [ ] Make it a [Living Document](https://www.cio.com/article/472690/6-best-practices-to-develop-a-corporate-use-policy-for-generative-ai.html) to show the Enterprise Policy is keeping up to date
- [ ] Ensure the language is inclusive of all stakeholders and not just a tech audience

</details>

## Risk and Controls

<details>
  <summary>Understanding Enterprise Risks</summary>
  <br>
A Risk and Controls Matrix is a tool that can help the [3 Lines of Defence](https://github.blog/2023-02-24-3-ways-to-meet-compliance-needs-without-slowing-down-agility/) have a common understanding of Risk in the Enterprise, highlight any control gaps, and provide a realistic path to address any gaps of deficiencies.

It's important for any new Technology to start with basic controls, such as code reviews, and then over time add controls that are more specific to the technology (such as Retrieval Augmented Generation for Generative AI).

The matrix below should be considered a starting point to cover the basic controls and will be expanded overtime here and within Enterprises who chose to adopt this Framework, to include controls specific to Generative AI.

<img width="1383" alt="image" src="https://github.com/MKQuantum/GenerativeAIFramework/assets/121593006/18b67040-f719-42ab-8ca4-68961acade3b">
</details>

## Traceability
<details>
  <summary>End-to-End Traceability</summary>
  <br>
Traceability is important in Governance because it allows you to follow the trail back to the source - whether you are governing software development, data ownership, infrastructure as code, and financial reporting.

By following this Framework, you will have several basic components needed for traceability:

- [ ] A consistent intake process will allow the Enterprise to understand the population of Generative AI solutions
- [ ] An approval process will provide oversight and an audit trail
- [ ] Access control in the GenAIOps pipeline
- [ ] Documented training attendance
</details>

## Audit
<details>
  <summary>Engaging Audit</summary>
  <br>
Audit can sometimes be considered an after-thought when implementing new technologies within an Enterprise. But as the Third Line of Defense they are an important stakeholder that needs to be included early and often.  

Ensure that they are a stakeholder and understand each component of this Framework.
</details>

## Culture
<details>
  <summary>Enterprise Culture</summary>
  <br>
In the blog post [Moore's Law for Everything](https://moores.samaltman.com), Sam Altman highlights the power of AI to change our society.  

For an Enterprise who wants to leverage Generative AI, it's important to remember there is an ingrained culture within the Enterprise society that will need to be addressed.

Training is a required next step, but it will be important for an Enterprise to work with HR and other stakeholders to ensure a holistic and inclusive people change management exercise is conducted.  

Some topics that may need to be addressed are:

- [ ] Is Generative AI an enabler or replacement for people in the Enterprise?
- [ ] How will people's work be evaluated if it was created with Generative AI?
- [ ] Will the yearly bonus be different for people who use Generative AI and those that don't?
- [ ] Will Generative make the Enterprise culture more or less inclusive?
</details>


