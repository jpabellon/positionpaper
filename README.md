# BUILDING AN AGENTIC STATE: ADVOCATING FOR MACHINE-TO-MACHINE (M2M) PRIORITY AND CITIZEN-CENTRIC AUTOMATION IN THE 2026 IRR OF RA 12254

**POSITION PAPER**

SUBMITTED TO THE DEPARTMENT OF INFORMATION AND COMMUNICATIONS TECHNOLOGY (DICT)

REGARDING THE 3RD DRAFT OF THE IMPLEMENTING RULES AND REGULATIONS OF REPUBLIC ACT NO. 12254 (E-GOVERNANCE ACT)

*March 10, 2026*

*This position paper includes comprehensive references to international standards, country case studies, and technical specifications. See Section IX: References and Sources for complete citations.*

**Submitted by:** Community of AI, Agentic AI, Automation, and Integration Developers in the Philippines

---

## I. EXECUTIVE SUMMARY

The passage of Republic Act No. 12254, the E-Governance Act, marks a pivotal moment in the history of Philippine governance. It provides the legal mandate to transition from a paper-based bureaucracy to a digitally enabled state. However, the current draft of the Implementing Rules and Regulations (IRR), specifically the version released in February 2026, risks cementing a "human-centric" model of digitization that is already becoming obsolete.

The current draft focuses heavily on "SuperApps" and web portals—interfaces designed for human manual input. While necessary, this approach fails to anticipate the rapid rise of **Agentic AI** and **Machine-to-Machine (M2M)** interactions. In an era where AI agents can autonomously schedule appointments, file taxes, and renew permits on behalf of citizens, a government infrastructure built solely for human clicking and typing will be a bottleneck, not an enabler.

**We advocate for a fundamental shift in the IRR: from "Government Online" to "Government as a Platform."**

This position paper argues that the 2026 IRR must explicitly mandate an **API-First Policy** and an **Open Data by Default** standard. We propose that the true measure of e-governance success is not how many citizens visit a government website, but how many citizens *never have to visit one at all* because services are delivered proactively, invisibly, and automatically through secure, interoperable APIs.

Drawing on successful models from **Estonia, Singapore, India, South Korea, Qatar, and the UAE**, we demonstrate that the most advanced digital nations treat their data and services as programmable infrastructure. We provide specific, line-by-line amendments to the IRR to institutionalize this vision, ensuring that the Philippines does not just catch up to the digital present, but leapfrogs into the AI-driven future.

## II. DEFINITION OF TERMS

To ensure clarity and technical precision in the Implementing Rules and Regulations, we propose the inclusion or refinement of the following definitions:

1. **Agentic AI System:** An artificial intelligence system capable of pursuing complex goals with limited direct human supervision, including the ability to plan actions, use software tools (such as APIs), and interact with other digital systems to achieve a specified outcome.
2. **Application Programming Interface (API):** A set of rules and protocols that allows different software applications to communicate with each other. In the context of e-governance, it refers to the machine-readable interface that allows third-party software or other government systems to access data or functionality without manual human intervention.
3. **API-First Development:** A software design approach where the API is conceptualized and built before the user interface (UI). This ensures that all functionality available to a human user on a website is also available to a machine via code.
4. **API Catalogue:** A centralized, searchable repository of all available government APIs, including documentation, technical specifications, and access protocols, designed to facilitate discovery and reuse by developers.
5. **AsyncAPI:** A technical specification for defining asynchronous, event-driven APIs, crucial for real-time notifications and "push" services in government (e.g., notifying a citizen immediately when a document is ready).
6. **Data Standard:** An agreed-upon format for data representation (e.g., ISO 8601 for dates, GeoJSON for location) to ensure that data exchanged between different agencies can be correctly understood and processed.
7. **Government as a Platform (GaaP):** A strategic approach where the government provides core digital infrastructure (identity, payments, data registries) as modular components upon which other agencies and the private sector can build value-added services.
8. **High-Value Dataset:** Datasets identified as having significant potential to generate socio-economic benefits, including geospatial data, meteorological data, statistics, and company registries.
9. **Machine-to-Machine (M2M) Interaction:** Direct communication between devices or systems using any communications channel, including wired and wireless, without manual human input.
10. **Machine-Readable Format:** A file format structured so that software applications can easily process, extract, and analyze specific data (e.g., JSON, XML, CSV), as opposed to human-readable formats like PDF or scanned images.
11. **Model Context Protocol (MCP):** A standard for connecting AI models to data sources, providing a secure and standardized way for Large Language Models (LLMs) to access and query government databases with explicit permission boundaries.
12. **Open Data:** Data that can be freely used, re-used, and redistributed by anyone - subject only, at most, to the requirement to attribute and share-alike.
13. **Open Data by Default:** A policy stance where government data is made public automatically unless there is a specific, lawful reason to keep it confidential (e.g., privacy, national security).
14. **OpenAPI Specification (OAS):** A standard, language-agnostic interface description for HTTP APIs, which allows both humans and computers to discover and understand the capabilities of the service without access to source code.
15. **Proactive Service Delivery:** The anticipation of citizen needs and the automatic provision of services (e.g., automatic renewal of eligibility) based on life events, data triggers, and predictive analytics, rather than waiting for a citizen application.
16. **Production-Ready API:** An API that is stable, secure, scalable, and supported by a Service Level Agreement (SLA), suitable for use in critical business or government applications, as opposed to a test or "sandbox" environment.
17. **Single Source of Truth (SSOT):** The practice of structuring information models such that every data element is mastered (or edited) in only one place. For example, a citizen's address should be mastered in the National ID system and referenced by other agencies, not duplicated.
18. **Zero-Touch Service:** A government service that requires no active input from the citizen to complete, relying entirely on background data exchange and automated processing (e.g., automatic tax filing for simple income).

## III. OPEN DATA — CONCEPTS, PRINCIPLES, FRAMEWORK, AND THE PHILIPPINE IMPERATIVE

### A. What Is Open Data?

Open Data refers to non-sensitive, public-sector information that is made available to the public in formats that are easy to access, reuse, and share. It is not merely "publishing information" on a website; it is about releasing the raw, structured data behind the information so that it can be analyzed, visualized, and integrated into new applications.

### B. The Minimum Criteria for Open Data

For data to be considered "Open" under RA 12254, it must meet four non-negotiable criteria:

- **Accessible:** Available on the internet to a wide range of users for a wide range of purposes.
- **Machine-Processable:** Structured so that it can be processed by a computer (e.g., spreadsheets, databases) rather than just read by a human (e.g., PDF scans).
- **Openly Licensed:** Specifically licensed to permit reuse, modification, and redistribution, including for commercial purposes.
- **Free of Charge:** Available at no cost to the user to prevent economic discrimination.

### C. The 10 Principles of Open Government Data (Sunlight Foundation)

We recommend the adoption of the ten global principles of Open Government Data as defined by the Sunlight Foundation (2010):

1. **Completeness:** All public data is made available.
2. **Primacy:** Data is as collected at the source, with the highest level of granularity.
3. **Timeliness:** Data is made available as quickly as necessary to preserve its value.
4. **Ease of Access:** Data is accessible to the widest range of users.
5. **Machine Readability:** Data is reasonably structured to allow automated processing.
6. **Non-Discrimination:** Data is available to anyone, with no requirement of registration.
7. **Commonly Owned Standards:** Data is in formats over which no entity has exclusive control.
8. **Licensing:** Data is not subject to any copyright, patent, trademark or trade secret regulation.
9. **Permanence:** Data is made available at a stable location (URL) for an indefinite period.
10. **Usage Costs:** Data is free of charge.

### D. The 5-Star Linked Open Data Model

The Philippines should benchmark its progress against Tim Berners-Lee's 5-Star deployment scheme (W3C, 2006):

- ★ Make your stuff available on the Web (whatever format) under an open license.
- ★★ Make it available as structured data (e.g., Excel instead of image scan of a table).
- ★★★ Make it available in a non-proprietary open format (e.g., CSV as well as Excel).
- ★★★★ Use URIs to denote things, so that people can point at your stuff.
- ★★★★★ Link your data to other data to provide context.

*Recommendation: The IRR should mandate a minimum of 3-Star Open Data for all government agencies by 2027.*

### E. High-Value Dataset Categories

Priority should be given to releasing "High-Value Datasets" that have the greatest potential for economic and social impact:

| Category       | Examples                                                      | Responsible Agencies |
| -------------- | ------------------------------------------------------------- | -------------------- |
| Geospatial     | Maps, administrative boundaries, postcodes, aerial imagery    | NAMRIA, LGUs         |
| Transport      | Public transport timetables, real-time traffic, road works    | DOTr, MMDA, LTFRB    |
| Meteorological | Weather forecasts, historical weather data, air quality       | PAGASA, DENR         |
| Statistics     | Census, GDP, inflation, unemployment, demographics            | PSA, BSP             |
| Companies      | Company registry, ownership, financial reports                | SEC, DTI             |
| Health         | Hospital locations, disease surveillance, service performance | DOH, PhilHealth      |

### F. Open Data vs. Open APIs

While Open Data provides the raw material (files), Open APIs provide the machinery (connectivity). Open Data is often static (downloading a file), whereas APIs are dynamic (querying a live database). A truly Agentic State requires both: Open Data for analysis and transparency, and Open APIs for real-time service delivery and transaction processing.

### G. Philippine Legal Framework

The mandate for Open Data is firmly rooted in RA 12254:

- **Section 2 (Policy):** Explicitly promotes the potential of open data for economic growth.
- **Section 9(l):** Mandates a "repository and corresponding secure API" for common data sets.
- **Section 18(g):** Tasks CIOs with "accelerating the adoption of open data."
- **Section 21(c):** Requires government websites to provide access to public information via an API.

### H. The Economic Case for Open Data

Global studies confirm the immense value of Open Data. In the EU, the direct market size of Open Data was estimated at €52 billion in 2019, projected to grow to €194 billion by 2030 (European Commission, 2020). In the Philippines, unlocking data in transport, agriculture, and finance could add billions of pesos to the digital economy by enabling startups to build solutions that the government cannot build alone.

### I. Open Data Exemptions

A "balanced" policy is essential. The IRR must clearly define exemptions based on the Data Privacy Act (RA 10173) and national security concerns. However, the burden of proof must be on the agency to justify *why* a dataset cannot be opened, rather than on the public to justify why it should be.

### J. Global Open Data Adoption: Country Cases and Lessons for the Philippines

The following case studies illustrate how leading digital nations have successfully institutionalized Open Data policies, providing a roadmap for the Philippines.

#### 1. Qatar: A Model of Mandated Timelines

- **Policy Framework:** Qatar's Open Data Policy (P002) is a comprehensive document that treats government data as a national resource. It explicitly adopts the 5-star Linked Open Data Model (MCIT Qatar, 2023).
- **Legal Mandate:** Rooted in Amiri Decree No. 57 of 2021 (Article 17) and Amiri Decision No. 47 of 2022, giving the Ministry of Communications and Information Technology (MCIT) clear authority to enforce the policy.
- **Governance:** Centralized oversight by MCIT, but each agency must appoint a designated "Open Data Official."
- **Implementation Timeline:**
  - Month 3: Designate Official.
  - Month 5: Develop Agency Open Data Plan.
  - Month 12: Launch webpage and publish at least 3 high-value datasets.
  - Month 18: Review and publish 3 additional datasets.
- **Lesson for Philippines:** The IRR should not just encourage open data but set a strict timeline (e.g., 12 months from effectivity) for agencies to publish their first wave of datasets.

#### 2. Canada: Open Data for Results

- **Policy Framework:** The "National Action Plan on Open Government 2022-2024" focuses on "Open Data for Results," prioritizing data quality and relevance over sheer volume.
- **Legal Mandate:** Directive on Open Government (2014) and Access to Information Act (1985, amended 2022).
- **Governance:** Uses a "Multi-stakeholder Forum" to involve citizens and civil society in deciding which data to open.
- **Lesson for Philippines:** Establish a similar consultation mechanism in the IRR so developers and citizens can identify which datasets are most urgently needed.

#### 3. Estonia: The Constitutional Right to Data

- **Policy Framework:** Driven by the "Digital Agenda 2030," viewing data access as a fundamental component of a digital society.
- **Legal Mandate:** Public Information Act (2000), which anchors open data access in constitutional rights and democratic transparency principles.
- **Lesson for Philippines:** Frame Open Data not just as a technical feature but as a transparency mechanism aligned with the Constitutional right to information.

#### 4. Republic of Korea: Mediation and Rights

- **Policy Framework:** "Digital Platform Government Implementation Strategy" with a "data open by default" stance.
- **Legal Mandate:** Act on Promotion of the Provision and Use of Public Data (2013); Act on Promotion of Data-based Administration (2020).
- **Governance:** Unique feature is the "Open Data Mediation Committee" which resolves disputes when agencies refuse data requests.
- **Lesson for Philippines:** The IRR should empower the DICT or a specific body to mediate and overturn unjustified denials of data access by agencies.

#### 5. European Union: High-Value Datasets

- **Policy Framework:** EU Directive 1024 (2019) on Open Data and the re-use of public sector information.
- **Key Mechanism:** The identification of specific "High Value Datasets" (geospatial, earth observation, etc.) that *must* be made available free of charge across all member states.
- **Lesson for Philippines:** The IRR should explicitly list "High Value Dataset" categories that are mandatory for release, preventing agencies from deprioritizing critical economic data.

#### 6. Kazakhstan: Digital Leapfrog

- **Policy Framework:** "Digital Kazakhstan" strategy.
- **Legal Mandate:** Law on Access to Information (2015) and Law on Informatisation (2015), coupled with the "Digital Kazakhstan" national strategy (2018-2022).
- **Lesson for Philippines:** Demonstrates that a developing nation can rapidly advance in Open Data rankings by coupling legal mandates with a strong national digital strategy.

## IV. THE CURRENT STATE OF THE 2026 IRR

An analysis of the 3rd Draft (February 2026) reveals significant progress but critical gaps regarding Agentic AI and API readiness:

| IRR Provision                      | Current Status                                | Gap / Issue                                                                                |
| ---------------------------------- | --------------------------------------------- | ------------------------------------------------------------------------------------------ |
| **Sec. 5 (Definitions)**     | Defines API and Interoperability generically. | Lacks definitions for "Machine-Readable," "Open Standard," or "SLA."                       |
| **Sec. 16 (E-Gov Programs)** | Focuses on SuperApp (eGovPH) and Web Portals. | No mandate for these platforms to expose public APIs for third-party integration.          |
| **Sec. 16.10 (PGIF)**        | Establishes interoperability framework.       | Does not explicitly adopt modern standards like REST/OAS or mention AI protocols like MCP. |
| **Sec. 22 (Websites)**       | Requires API access for public info.          | Vague on technical standards; risks agencies building non-compliant, proprietary APIs.     |
| **Sec. 39 (Security)**       | Mandates generic info security.               | No specific mention of API security standards (e.g., OAuth 2.0, API Gateways).             |

## V. CITIZEN-CENTRIC USE CASES: THE AGENTIC STATE IN ACTION

To illustrate the power of an API-first approach, we present eight scenarios of "invisible government":

### 1. Zero-Touch Business Registration

**Current:** Citizen fills out 15 forms across SEC, BIR, and LGU websites.
**Future:** An AI agent, authorized by the citizen, queries the "Business Name API" (DTI), submits incorporation data to "SEC API," and registers for tax via "BIR API" in seconds. The permits arrive in the citizen's digital wallet automatically.

### 2. Proactive Social Benefits

**Current:** A single mother must prove her status to get benefits.
**Future:** When a birth certificate is registered (PSA API) without a father's name, the system triggers a "Life Event" notification. The DSWD system receives this, verifies income via "Tax API," and automatically pushes 4Ps or Solo Parent benefits to her e-wallet.

### 3. Real-Time Healthcare Interoperability

**Current:** Patients carry paper records between doctors.
**Future:** A secure "Health Data API" (FHIR standard) allows a doctor in Cebu to instantly view the records of a patient from Manila, with the patient approving access via a mobile prompt.

### 4. Smart Agri-Insurance

**Current:** Farmers wait months for crop damage assessment.
**Future:** "Weather API" (PAGASA) detects a typhoon exceeding a specific wind speed in a locality. The "Crop Insurance API" (PCIC) automatically triggers a payout to all registered farmers in that geocode, with no claims filing needed.

### 5. AI-Assisted Tax Compliance

**Current:** MSMEs struggle with complex tax codes.
**Future:** Accounting software connects directly to the "BIR e-Invoicing API." Sales data is transmitted in real-time. At year-end, the government sends a pre-filled tax return. The business owner just clicks "Approve."

### 6. Seamless Land Title Transfer

**Current:** Months of visiting LRA, BIR, and Assessor's Office.
**Future:** A blockchain-enabled "Land Registry API" updates ownership instantly upon payment of transfer tax, which is verified automatically via bank API integration.

### 7. Automated Scholarship Matching

**Current:** Students hunt for scholarships manually.
**Future:** The "DepEd Student Record API" matches a student's grades and demographic data against the "CHED Scholarship API" criteria, automatically notifying eligible students and pre-filling their applications.

### 8. Trade Facilitation

**Current:** Importers manually encode data for Customs.
**Future:** Logistics providers' systems talk directly to the "Bureau of Customs API," submitting manifests and declaration data ahead of arrival, clearing low-risk cargo before the ship even docks.

## VI. RECOMMENDED TECHNICAL STANDARDS

The IRR should explicitly recommend or mandate the following open standards to ensure true interoperability:

| Component                | Recommended Standard                      | Why?                                                   |
| ------------------------ | ----------------------------------------- | ------------------------------------------------------ |
| **API Design**     | REST with OpenAPI Specification (OAS) 3.1 | Global standard, readable by both humans and machines. |
| **Data Format**    | JSON (JavaScript Object Notation)         | Lightweight, web-native, universally supported.        |
| **Authentication** | OAuth 2.0 + OpenID Connect                | Secure, industry-standard delegation of access.        |
| **Event Handling** | AsyncAPI                                  | Crucial for real-time notifications and webhooks.      |
| **AI Context**     | Model Context Protocol (MCP)              | Enables safe, context-aware AI interactions with data. |
| **Metadata**       | DCAT-AP 3.0                               | Standard for describing public sector datasets.        |
| **Health Data**    | HL7 FHIR R4                               | The global standard for healthcare interoperability.   |
| **Security**       | OWASP API Security Top 10                 | Baseline security checklist for all government APIs.   |

## VII. GLOBAL TRENDS: FROM OPEN DATA TO OPEN APIS

The world is moving beyond static data portals to dynamic API ecosystems. The Philippines must learn from these leaders:

- **Singapore (The Gold Standard):** Their "Government Data Architecture" (GDA) and APEX middleware allow agencies to share data in real-time. 99% of transactions are digital because the backend systems are fully integrated (SNDGO, 2024).
- **Estonia (X-Road):** A decentralized data exchange layer that connects 99% of public services since 2001, with cross-border integration with Finland established in 2018. The key lesson: data is never duplicated; it is requested from the source via secure API (X-Road Foundation, 2024).
- **India (India Stack):** A set of open APIs for Identity (Aadhaar), Payments (UPI), and Data. It proves that API infrastructure can scale to over a billion people and drive massive financial inclusion, with UPI processing billions of transactions monthly (India Stack, NPCI).
- **United Kingdom (GDS):** "Government as a Platform" strategy where common components (Notify, Pay, ID) are built once and reused by all agencies via API.

### CASE STUDY: UAE API-First Policy — From Guidelines to National Mandate and Real-World Implementation

The United Arab Emirates (UAE) offers perhaps the most compelling roadmap for the Philippines, having successfully transitioned from voluntary guidelines to a mandatory national policy.

#### Three-Stage Evolution

1. **Stage 1 (2019): Voluntary Guidelines.** The Telecommunications and Digital Government Regulatory Authority (TDRA) released the "API First Guidelines," encouraging entities to adopt API standards.
2. **Stage 2 (2022-2024): Mandatory Policy.** The "API First Policy" was enacted, making it mandatory for all federal entities to design services with APIs from the start.
3. **Stage 3 (2025): Ecosystem Activation.** The launch of the "UAE API Marketplace," a centralized platform connecting government APIs with private sector developers.

#### Policy Objectives

The UAE policy is driven by seven clear objectives, including: enhancing user experience, improving efficiency, fostering innovation, adopting modern business models, enabling "ask-once" data sharing, and boosting data security.

#### Concrete Implementation: The Digital Ajman Case Study

The emirate of Ajman, the smallest in the UAE, utilized the API-first approach to achieve outsized results through three key integrations:

- **Ajman Pay:** A unified payment gateway integrated via API with all local government entities and banks. It eliminated the need for point-to-point connections, saving time and complexity.
- **Bait Amer:** A service bundle for home building. By connecting planning, sewerage, telecom, electricity, and water departments via API, the process was reduced from **17 touchpoints to just 5**.
- **Bashr:** A business establishment service. Using an integrated electronic platform, investors can set up a company in just **15 minutes** without visiting any government office.

#### Measured Outcomes

The results of this API-first strategy in Ajman alone were quantifiable and significant:

- **AED 2 Million Saved:** Direct cost savings from simplified processes and reduced manual work (IBM Digital Ajman Case Study, 2024).
- **200 Trees Saved Annually:** Reduction in paper usage due to digital-first workflows (IBM Digital Ajman Case Study, 2024).
- **~1 Million Transactions:** High adoption rate driven by the ease of the new digital services, with the platform approaching one million transactions (IBM Digital Ajman Case Study, 2024).

#### Lessons for the Philippines

- **Move from Guidelines to Mandate:** Like the UAE, the Philippines must evolve the PGIF from a reference document to a mandatory enforceable policy in the IRR.
- **Establish a Philippine API Marketplace:** Creating a central hub for developers to discover and access government APIs is crucial for private sector innovation.
- **Demand Measurable Outcomes:** The IRR should require agencies to report on API usage, uptime, and efficiency gains (e.g., reduction in processing time), just as Ajman tracked its savings.

## VIII. SPECIFIC RECOMMENDATIONS FOR 2026 IRR

We formally propose the following amendments to the 3rd Draft of the IRR:

> **Recommendation 1: Mandate Production-Ready APIs**
> *Amend Section 16 (E-Government Programs):* "All priority digital platforms (eGovPH, eLGU, eGovPay) MUST provide a secure, documented, and production-ready API for third-party integration, subject to security accreditation. These APIs must maintain a minimum uptime of 99.9%."

> **Recommendation 2: Look at Emerging Standards in the Interoperability Framework**
> *Amend Section 16.10 (PGIF):* "The PGIF shall explicitly encourage agencies to study and adopt emerging global and industry standards like REST APIs, GraphQL, and the Model Context Protocol (MCP) to enable more efficient and future-ready Government-to-Citizen or Government-to-AI data exchange, ensuring auditability of AI agents."

> **Recommendation 3: Create a Government Developer Sandbox**
> *Amend Rule VII (Private Sector Participation):* "The DICT shall establish a 'Government Developer Sandbox,' a safe, simulated environment where accredited startups and developers can test their applications against government APIs before live deployment."

> **Recommendation 4: Open High-Value Datasets by Default**
> *Amend Section 16.12 (Records Management):* "The following high-value datasets shall be made available via Open API within 12 months: Geospatial, Transport, Weather, Company Registry, and Procurement Data."

> **Recommendation 5: Standardize Web API Requirements**
> *Amend Section 22 (Websites):* "The requirement for API access shall be satisfied by adherence to widely adopted global standards for data exchange like OpenAPI Specification (OAS) 3.1 and others. Proprietary or undocumented interfaces shall not be considered compliant."

> **Recommendation 6: Establish a Data Governance Committee**
> *Insert New Section 16.14:* "A Data Exchange Governance Committee shall be formed under the DICT to oversee data exchange standards, deprecation policies, and dispute resolution between data providers and consumers."

> **Recommendation 7: Implement OAuth 2.0 for Citizen Consent**
> *Amend Section 26 (Privacy):* "Access to personal data via API shall be governed by the OAuth 2.0 standard (or its successor), ensuring citizens can grant and revoke specific permissions to third-party apps."

> **Recommendation 8: Security by Design for APIs**
> *Amend Section 39 (Security):* "Minimum Information Security Standards for APIs shall include mandatory rate limiting, encryption in transit (TLS 1.3), and automated vulnerability scanning."

> **Recommendation 9: Budget for API Maintenance**
> *Policy Recommendation:* "Agencies shall allocate a percentage of their ICT maintenance budget specifically for the upkeep, documentation, and versioning of their public APIs."

> **Recommendation 10: Phased Implementation Roadmap**
> *Policy Recommendation:* "The IRR shall set a 3-year roadmap: Year 1 (Core Registers API), Year 2 (Transactional APIs), Year 3 (Full AI/M2M Integration)."

## IX. REFERENCES AND SOURCES

*This position paper draws on 41 cited sources including Philippine legislation, international open data frameworks, country case studies from 15+ nations, technical standards from W3C/IETF/HL7, academic research, and quantitative data from government digital transformation initiatives. All URLs and document references are provided below for verification and further reading.*

### A. Philippine Legal and Policy Documents

1. **Republic Act No. 12254** - "An Act Institutionalizing the Transition of the Government to E-Governance, Providing for the Expansion of Digital Infrastructure, Streamlining Government Processes, Procedures, and Requirements, and for Other Purposes," enacted September 2025. Official Gazette of the Republic of the Philippines.
2. **Implementing Rules and Regulations of RA 12254 (3rd Draft)** - Department of Information and Communications Technology (DICT), February 18, 2026. Retrieved from: https://drive.google.com/file/d/1yUmh1eYlPW_5mn9UVkpxqDHFLBBjMgWP/view?fbclid=IwY2xjawQI61NleHRuA2FlbQIxMABicmlkETJKMmI4eXRyMUNxdFBJWnJYc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHgLB8btShA6JHMuRDh5O9mOCYPe9vCVSel_RC4dz3OXzGIP3NzVQAdjaYIeS_aem_9zyabkv0N2UYekgLk6KOKA
3. **Republic Act No. 10173** - Data Privacy Act of 2012. National Privacy Commission, Philippines.
4. **Open Data Philippines Portal** - https://data.gov.ph/

### B. International Open Data Frameworks and Standards

5. **Sunlight Foundation** (2010). "Ten Principles for Opening Up Government Information." Open Government Data: The Book. https://opengovdata.io/
6. **Berners-Lee, Tim** (2006). "Linked Data - Design Issues." W3C. 5-Star Open Data deployment scheme. https://www.w3.org/DesignIssues/LinkedData.html
7. **Open Knowledge Foundation**. "Open Definition 2.1: Defining Open in Open Data, Open Content and Open Knowledge." https://opendefinition.org/
8. **G8 Open Data Charter** (2013). "Open Data Charter and Technical Annex." G8 Summit, Lough Erne, UK.

### C. Country Case Studies - Open Data Policies

9. **State of Qatar**. "Open Data Policy (P002)." Ministry of Communications and Information Technology (MCIT), Version 1.0.2. Legal basis: Amiri Decree No. 57 of 2021; Amiri Decision No. 47 of 2022. Retrieved from: https://www.data.gov.qa/pages/open_data_policy1/
10. **Government of Canada**. "National Action Plan on Open Government 2022-2024." Treasury Board of Canada Secretariat. Legal basis: Directive on Open Government (2014); Access to Information Act (1985, amended 2022).
11. **Republic of Estonia**. "Digital Agenda 2030." Ministry of Economic Affairs and Communications. Legal basis: Public Information Act (2000). https://e-estonia.com/solutions/interoperability-services/x-road/
12. **Republic of Korea**. "Digital Platform Government Implementation Strategy." Legal basis: Act on Promotion of the Provision and Use of Public Data (2013); Act on Promotion of Data-based Administration (2020).
13. **European Union**. "Directive (EU) 2019/1024 on open data and the re-use of public sector information." European Parliament and Council, June 20, 2019. Also: Data Governance Act (2022).
14. **Republic of Kazakhstan**. "Digital Kazakhstan Programme (2018-2022)." Legal basis: Law on Access to Information (2015); Law on Informatisation (2015).
15. **Astana Civil Service Hub & UNDP** (2024). "Open Government Data Policies in Selected Countries: Comparative Analysis." Report covering Canada, Estonia, Korea, EU, and Central Asian/Caucasus countries. Retrieved from: https://www.undp.org/sites/g/files/zskgke326/files/2023-03/20230317_Open%20Government%20Data_fin.fin_.pdf

### D. Country Case Studies - API-First and Digital Government

16. **United Arab Emirates**. "API First Policy." Telecommunications and Digital Government Regulatory Authority (TDRA), enacted 2022-2024. https://u.ae/en/about-the-uae/digital-uae/regulatory-framework/api-first
17. **United Arab Emirates**. "API First Guidelines - Version 1.0." TDRA, 2019. Retrieved from: https://u.ae/en/about-the-uae/digital-uae/regulatory-framework/api-first
18. **UAE API Marketplace**. Government platform for API discovery and integration. https://api.government.ae/
19. **Digital Ajman & IBM**. "Case Study: Digital Ajman Framework - API Integration for Government Services." IBM Cloud Pak for Integration implementation. Retrieved from: https://www.ibm.com/case-studies/digital-ajman
20. **Government of Singapore**. "Digital Government Blueprint (DGB)." Smart Nation and Digital Government Office (SNDGO), 2023. Includes Government Data Architecture (GDA) and National AI Strategy (NAIS) 2.0. Retrieved from: https://isomer-user-content.by.gov.sg/85/f4e1b24e-42b4-4f8d-98a4-9dbc64817ff6/dgb-public-document_30dec20.pdf
21. **Singapore - Singpass**. National Digital Identity platform with 97% penetration rate, 4.2 million app users, 500 million annual transactions. https://www.singpass.gov.sg/
22. **Estonia - X-Road**. Secure data exchange layer connecting 99% of public services since 2001. X-Road Foundation. https://x-road.global/
23. **Tepandi, J., et al.** (2024). "A Historical Analysis on Interoperability in Estonian Data Exchange Architecture." Retrieved from: https://www.researchgate.net/publication/357787085_A_Historical_Analysis_on_Interoperability_in_Estonian_Data_Exchange_Architecture_Perspectives_from_the_Past_and_for_the_Future 
24. **Government of India**. "India Stack." Digital Public Infrastructure including Aadhaar (Identity), UPI (Payments), and DigiLocker (Data). https://indiastack.org/
25. **UK Government Digital Service (GDS)**. "Government as a Platform." https://www.gov.uk/government/publications/government-transformation-strategy-2017-to-2020

### E. Academic and Research Sources

26. **Matheus, R., Ribeiro, M.M., & Vaz, J.C.** (2023). "Open Government APIs (OGAPIs) in Smart City Service Delivery: A Comparative Analysis of Singapore, South Korea, UK, Brazil, and Indonesia." Journal of Digital Government Research. Retrieved from: https://learning-gate.com/index.php/2576-8484/article/view/8645
27. **European Commission** (2020). "The Economic Impact of Open Data: Opportunities for value creation in Europe." Study estimating EU Open Data market at €52 billion (2019), projected €194 billion by 2030.
28. **Open Data Institute (ODI)**. "The Value of Open Data." Multiple case studies on economic impact. https://theodi.org/

### F. Technical Standards and Specifications

29. **OpenAPI Initiative**. "OpenAPI Specification (OAS) 3.1." Linux Foundation. https://www.openapis.org/
30. **OAuth 2.0 Framework**. IETF RFC 6749. "The OAuth 2.0 Authorization Framework." https://oauth.net/2/
31. **OpenID Connect**. OpenID Foundation. Authentication layer on top of OAuth 2.0. https://openid.net/connect/
32. **AsyncAPI Initiative**. "AsyncAPI Specification 3.0." For event-driven and asynchronous APIs. https://www.asyncapi.com/
33. **Model Context Protocol (MCP)**. Anthropic. Standard for connecting AI models to data sources. https://modelcontextprotocol.io/
34. **W3C DCAT-AP**. "Data Catalog Vocabulary - Application Profile 3.0." W3C standard for describing public sector datasets. https://www.w3.org/TR/vocab-dcat-3/
35. **HL7 FHIR**. "Fast Healthcare Interoperability Resources (FHIR) R4." HL7 International standard for healthcare data exchange. https://www.hl7.org/fhir/
36. **OWASP Foundation**. "OWASP API Security Top 10 (2023)." Open Web Application Security Project. https://owasp.org/www-project-api-security/
37. **NIST**. "Cybersecurity Framework (CSF) 2.0." National Institute of Standards and Technology, USA.
38. **ISO/IEC 27001**. Information Security Management System standard.

### G. Additional Resources

39. **Gartner**. "Application Programming Interface (API) Definition." Technology glossary. https://www.gartner.com/en/information-technology/glossary/application-programming-interface
40. **World Bank**. "Digital Government Index (DGI)." Comparative rankings of digital government maturity.
41. **UN E-Government Survey**. United Nations Department of Economic and Social Affairs. Biennial assessment of e-government development globally.

### H. Data and Statistics Citations

- Singapore: 99% digital transaction rate, 99% e-payment availability, 83% citizen satisfaction - Source: Smart Nation and Digital Government Office (SNDGO), 2024.
- Singpass: 97% penetration, 4.2M users, 500M transactions - Source: Singapore Government Digital Government Blueprint, 2024.
- Estonia X-Road: 99% of public services connected, operational since 2001, cross-border integration with Finland (2018) - Source: X-Road Foundation.
- UAE Digital Ajman: AED 2 million saved, 200 trees saved annually, ~1 million transactions - Source: IBM Case Study, Digital Ajman Framework.
- EU Open Data Market: €52B (2019) → €194B (2030 projection) - Source: European Commission, 2020.
- India Stack UPI: Processes billions of transactions monthly, 1B+ population reach - Source: India Stack, NPCI.

## X. CONCLUSION

The 2026 IRR of the E-Governance Act is our opportunity to define the digital DNA of the Philippine government for the next decade. If we build for humans only, we build for the past. If we build for machines and agents, we build for the future.

By adopting an API-First, Open Data-driven approach, the Philippines can create a government that is not just "online," but "on-demand"—a platform that empowers citizens, accelerates business, and harnesses the transformative power of AI. We urge the DICT to incorporate these recommendations and lead the nation into the era of the Agentic State.

---

**Community of AI, Agentic AI, Automation, and Integration Developers in the Philippines**
*Advocating for a Programmable Republic*
