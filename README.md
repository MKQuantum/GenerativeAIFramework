# Enterprise Governance Framework for Generative AI
<img width="600" alt="image" src="https://user-images.githubusercontent.com/121593006/236930142-97eb9410-6d36-4634-90ca-ca1009a775bb.png">

## This opinionated Framework covers  areas of compliance, risk, auditability, and management which would be important for any Enterprise that is interested in leveraging Generative AI for the enablement of their workforce and the benefit of their customers.

<img width="1680" alt="image" src="https://github.com/MKQuantum/GenerativeAIFramework/assets/121593006/5eba146a-83fc-495b-82ee-77782cd5ed9e">

There are several considerations which will be important for adoption: 

* Generative AI will soon be ubiquitous in every aspect of the Enterprise so Governance will need to be an enabler and allow for growth - but with guardrails.
* Layered approach to Governance for Deployment of services and Creation of new solutions
* Start with the basics of Governance and build from there
* There is no "one size fits all" Governance and your Framework will need to change over time
* Provide Risk Management and Audit groups a baseline of what the "ideal state" looks like
* Invest in your teams with Education and Coaching
* Provide enough Risk Coverage to help the Enterprise understand how their [Risk Appetite](https://www.theirm.org/what-we-say/thought-leadership/risk-appetite-and-tolerance/) is affected


## Intake

The intake is the entry point for a Governance Framework and may be different for various teams in the Enterprise.  Teams that are using Generative AI apps as a Service, such as leveraging it within an Excel sheet, will have a different entry point then teams that are creating solutions.  With the proliferation of Generative AI within browsers and other ubiquitous tools, understanding the existing security and access controls of existing tools and platforms may be a good starting point to provide assurance that risks are covered.

For situations where teams are leveraging Generative AI services that are provided within an Enterprises in a controlled manner, a web form with the following details may be also be a possibility:

- [ ] Name
- [ ] Department
- [ ] Use case
- [ ] Approvals from one-up Manager Name

For development teams that are creating solutions, the Enterprises existing processes to control Open Source dependencies and access controls to development environments could act as the first layer of defense.  

## Training

While training AI Models is important, it is equally as important to train your Enterprise users to help increase their Generative AI literacy.  Training is important for all new concepts and technologies within an Enterprise, but is even more important for technologies such as Generative AI that will have a profound effect on users daily work - and the risk appetite of the Enterprise.

Some example of Training courses that could be provided are:

- [ ] High Level Introduction to AI (What is AI? What are considerations for society and business?)
- [ ] Understanding Risk and Bias in AI
- [ ] DevOps and Cloud Native best practices fo AI
- [ ] Generative AI Introduction
- [ ] Generative AI Development

## Policies

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

## Risk and Controls

A Risk and Controls Matrix is a tool that can help the [3 Lines of Defence](https://github.blog/2023-02-24-3-ways-to-meet-compliance-needs-without-slowing-down-agility/) have a common understanding of Risk in the Enterprise, highlight any control gaps, and provide a realistic path to address any gaps of deficiencies.

It's important for any new Technology to start with basic controls, such as code reviews, and then over time add controls that are more specific to the technology (such as Retrieval Augmented Generation for Generative AI).

The matrix below should be considered a starting point to cover the basic controls and will be expanded overtime here and within Enterprises who chose to adopt this Framework, to include controls specific to Generative AI.

<img width="1383" alt="image" src="https://github.com/MKQuantum/GenerativeAIFramework/assets/121593006/18b67040-f719-42ab-8ca4-68961acade3b">


## Traceability

Traceability is important in Governance because it allows you to follow the trail back to the source - whether you are governing software development, data ownership, infrastructure as code, and financial reporting.

By following this Framework, you will have several basic components needed for traceability:

- [ ] A consistent intake process will allow the Enterprise to understand the population of Generative AI solutions
- [ ] An approval process will provide oversight and an audit trail
- [ ] Access control in the GenAIOps pipeline
- [ ] Documented training attendance


## Audit

Audit can sometimes be considered an after-thought when implementing new technologies within an Enterprise. But as the Third Line of Defense they are an important stakeholder that needs to be included early and often.  

Ensure that they are a stakeholder and understand each component of this Framework.

## Culture

In the blog post [Moore's Law for Everything](https://moores.samaltman.com), Sam Altman highlights the power of AI to change our society.  

For an Enterprise who wants to leverage Generative AI, it's important to remember there is an ingrained culture within the Enterprise society that will need to be addressed.

Training is a required next step, but it will be important for an Enterprise to work with HR and other stakeholders to ensure a holistic and inclusive people change management exercise is conducted.  

Some topics that may need to be addressed are:

- [ ] Is Generative AI an enabler or replacement for people in the Enterprise?
- [ ] How will people's work be evaluated if it was created with Generative AI?
- [ ] Will the yearly bonus be different for people who use Generative AI and those that don't?
- [ ] Will Generative make the Enterprise culture more or less inclusive?

## GenAIOps

[DevOps](https://resources.github.com/devops/) and [MLOps](https://www.databricks.com/glossary/mlops#:~:text=MLOps%20stands%20for%20Machine%20Learning,then%20maintaining%20and%20monitoring%20them.) culture and best practices can help Development teams get their solutions to Production in standardized, repeatable, secure, and optimized workflows.

These best practices can be applied to Generative AI to help teams create solutions and deploy them in Enterprises.

<img width="1670" alt="image" src="https://github.com/MKQuantum/GenerativeAIFramework/assets/121593006/0bbb1c17-ce08-4405-aec9-fee233cf8565">


| **Term** | **Description**   |
| :-----: | :---: |
| Generative AI (GenAI) | Generative AI is a type of artificial intelligence technology that can produce various types of content, including text, imagery, audio and synthetic data. ([techtarget.com](https://www.techtarget.com/searchenterpriseai/definition/generative-AI))  |
| Large Language Models (LLM)| A large language model, or LLM, is a deep learning algorithm that can recognize, summarize, translate, predict and generate text and other content based on knowledge gained from massive datasets. ([nvidia.com](https://blogs.nvidia.com/blog/2023/01/26/what-are-large-language-models-used-for/#:~:text=A%20large%20language%20model%2C%20or,successful%20applications%20of%20transformer%20models.))  |
| Retrieval Augmented Generation| RAG retrieves data from outside the language model and augments the prompts by adding the relevant retrieved data in context ([AWS](https://aws.amazon.com/blogs/machine-learning/question-answering-using-retrieval-augmented-generation-with-foundation-models-in-amazon-sagemaker-jumpstart/#:~:text=To%20solve%20the%20constraints%20we,introduced%20by%20Lewis%20et%20al.))   |
| AI Hallucinations| When an AI is perceiving something that is not real. |

To help enable Enterprises with onboarding of Services and Tools, the following topics could be leveraged as a checklist to help streamline governance and security reviews by providing a baseline set of criteria.  
| **Review Topic** | **Description**  |
| :-----: | :---: |
| Enterprise Cloud Provider | Cloud Provider's such as AWS and Azure have started releasing Generative AI tools and services such as [Azure Promptflow](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/harness-the-power-of-large-language-models-with-azure-machine/ba-p/3828459) and [Amazon Kendra](https://aws.amazon.com/blogs/machine-learning/quickly-build-high-accuracy-generative-ai-applications-on-enterprise-data-using-amazon-kendra-langchain-and-large-language-models/).  If the Enterprise preferred Cloud Provider provided Generative AI development tooling, it may be easier to have the service or tool certified for Enterprise use.  |
| Service Certification | An Enterprise may already have a process in place to Certify Cloud services or tooling with existing checklists for common topics such as security, traceability, audit, logging, and etc.  Tools such as Azure Promptflow or Amazon Kendra could also be onboarded leveraging existing processes like this - providing Governance decision makers with criteria and review topices they are familiar with. |
| Open Source Maturity | If the Enterprise has an existing [Open Source Program Office](https://github.blog/2023-03-13-an-open-source-project-to-empower-ospos-everywhere/) and is comfortable with the use of Open Source tooling, leveraging Generative AI Open Source services and tools should follow existing processes.  But, for an Enterprise that does not currently have governance and management in place for Open Source tools, the overhead of onboarding new tools available in the Open Source community may be too time consuming.  Tools provided by preferred Cloud Providers may be a better option until Open Source maturity has increased. |
| Enterprise Industry | An Enterprise security stance and risk appetite will be driven by its Industry.  For example, Financial Institutions, Retail, Insurance, and Health Care companies all have different regulations and requirements that drive all of their decisions regarding services and tools.  When making a decision on Generative AI development services and tools, its important to consider what regulations or requirements will need to be followed.  For example. if an Enterprise is developing a Generative AI application for processes that are related to financial reporting, they may need to consider the controls that will be reviewed as part of a [SOX Audit](https://www.sarbanes-oxley-101.com/sarbanes-oxley-audits.htm).  However, if the Enterprise process is not related to requlations or requirements, there will be more lenient controls and security controls. |
| Data Classification | Any decisions on services or tooling that will be leveraged for Generative AI development should factor in the classification of the data that will be leveraged by the Language Models.  Data controls and governance for restricted or confidential data are much more strict than internal or public data. |
|Data Residency | There are data residency requirements for regions around the World which need to be considered for Generative AI development.  For example, the [General Data Protection Regulation](https://www.wired.co.uk/article/what-is-gdpr-uk-eu-legislation-compliance-summary-fines-2018) requires personal data for EU residents needs to stay in the EU.  This is an important consideration for Open Source tools or other Services that may be sending data to other regions around the world. |
| Enterprise Risk Appetite | The [Enterprise Risk Appetite](https://www.theirm.org/what-we-say/thought-leadership/risk-appetite-and-tolerance/) is the amount of risk an Enterprise is willing to take on to meet its objectives.  This is an important factor for Generative AI development since its such a game-changer for the Industry.  An Enterprise who has bee traditionally conservative may update their Risk Appetite to take advantage of the tremendous potential of Generative AI Capabilities.  | 

