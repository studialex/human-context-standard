# **Human Context Standard™ (HCS)**

**Version:** 0.1.0 (Draft / Request for Comments)

**Status:** Architecture Skeleton & Manifesto

## **Abstract**

The **Human Context Standard™** is an open, Zero-Data Retention protocol designed to standardize how deeply personal, emotional, and temporal human context is structured and routed to Agentic AI systems.

As the industry shifts from reactive chatbots to autonomous Multi-Agent Systems, AI models suffer from "context blindness" unless granted access to highly sensitive personal data. HCS solves this by establishing a unified ontology for human states, ensuring that context is safely transmitted via protocols like the Model Context Protocol (MCP) without requiring centralized data harvesting.

## **Core Principles**

1. **Zero-Data Retention by Design:** The standard defines *how* data is structured in transit, not how it is hoarded. It is built to seamlessly integrate with decentralized storage (e.g., Solid Pods, local Edge storage).  
2. **Dynamic Ontology:** Beyond static medical or demographic data, HCS codes emotional states, vector embeddings of current stress levels, and longitudinal life events.  
3. **Granular Consent:** Built-in scopes for explicit, fractional consent, preventing the "Confused Deputy" problem in LLM interactions.

## **Architecture Ecosystem (Umbrella)**

HCS acts as the umbrella protocol. For highly specific social structures, HCS is extended by nested standards within this repository:

* 📂 [**Family Context Standard™ (FCS)**](https://www.google.com/search?q=./family-context-standard/README.md): Extends HCS for multi-person relationship graphs and ReBAC (Relationship-Based Access Control).  
* 📂 [**Child Context Standard™ (CCS)**](https://www.google.com/search?q=./child-context-standard/README.md): Extends FCS for pediatric development, proxy-consent, and COPPA/GDPR-K compliance.
* 📂 **[Enterprise Context Standard™ (ECS)](./enterprise-context-standard/README.md)**: Adapts HCS principles for B2B environments, ERP integrations (e.g., Odoo), and stateless corporate AI workflows.

## **Target Use Cases**

* Autonomous AI Assistants requiring deep personalization.  
* HealthTech and Mental Health routing platforms.  
* Sovereign Data Cooperatives.

## **License, Copyright & Trademark**

To ensure the standard remains a public good while protecting its integrity, this project operates under a split-licensing and trademark model:

* **Code & Schemas:** All JSON schemas, API definitions, and connector templates are licensed under the **Apache License 2.0**. (See root LICENSE).  
* **Documentation & Specifications:** All written text, whitepapers, and architectural diagrams are licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**. (See root LICENSE-DOCS).

**Trademark Notice:** "Human Context Standard™", "Family Context Standard™", and "Child Context Standard™" are trademarks of Oleksiy Marchenko (acting on behalf of the future governing Open Source Foundation / The Commons Conservancy). While the specifications are open, the use of these full names to endorse or promote third-party commercial implementations requires explicit permission.

**Copyright (c) 2026 Oleksiy Marchenko.** All intellectual property rights pertaining to the open standards will be formally assigned to a recognized Open Source Foundation (e.g., The Commons Conservancy or a dedicated Stichting) to guarantee their perpetual status as a public good.
