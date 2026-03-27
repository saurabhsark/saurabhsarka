<!-- ============================================================
     SAURABH SARKAR — GITHUB PROFILE README
     Solution Architect | Financial Services | Agentic AI
     ============================================================ -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0D1B2A&height=120&text=SAURABH%20SARKAR&fontSize=38&fontColor=E8F0FE&fontAlignY=45&desc=Solution%20Architect%20%E2%80%82%7C%E2%80%82%20Financial%20Services%20%E2%80%82%7C%E2%80%82%20Agentic%20AI%20%E2%80%82%7C%E2%80%82%20London&descSize=14&descColor=7BAFD4&descAlignY=70&animation=fadeIn"/>

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Saurabh%20Sarkar-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sarkarsaurabh)&ensp;
[![GCP](https://img.shields.io/badge/Google%20Cloud-Professional%20Cloud%20Architect-4285F4?style=flat-square&logo=googlecloud&logoColor=white)](https://cloud.google.com/certification)&ensp;
[![MSc](https://img.shields.io/badge/MSc-Machine%20Learning%20%26%20AI%20%7C%20LJMU-1B3A5C?style=flat-square&logoColor=white)](#)&ensp;
[![Location](https://img.shields.io/badge/Based%20in-London%2C%20UK-C5A028?style=flat-square&logo=googlemaps&logoColor=white)](#)

</div>

---

```
╔══════════════════════════════════════════════════════════════════════════════╗
║  SYSTEM PROFILE                                          v13.0 / 2025-Q1    ║
╠══════════════════════════════════════════════════════════════════════════════╣
║  ROLE         Solution Architect — AI-Driven Financial Services              ║
║  EMPLOYER     Synpulse UK Ltd  |  Architecture Centre of Excellence          ║
║  DOMAIN       Tier 1 PBWM  |  Financial Crime  |  Core Banking              ║
║  PLATFORMS    Avaloq  |  Temenos  |  Pega CLM  |  GCP  |  Azure             ║
║  AI STACK     LangGraph  |  LlamaIndex  |  RAG  |  LLMs  |  Agents          ║
║  FRAMEWORKS   TOGAF  |  DDD  |  Event-Driven  |  Microservices              ║
║  REGULATORY   FCA  |  MiFID II  |  GDPR  |  PSD2  |  CSDR  |  EU AI Act    ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## The Problems I Solve

I work with Tier 1 private banks and wealth managers facing a specific kind of problem: **complex business operations that have outgrown the systems they were built on**, where the cost of getting it wrong is not just financial — it is regulatory, reputational, and existential.

The patterns I encounter repeatedly across clients:

> **"Our KYC review cycle is 3 years. By the time we review a client, their risk profile has already changed twice."**
> Solved with: perpetual KYC, event-driven architecture, continuous screening pipelines.

> **"90% of our AML alerts are false positives. Our compliance team spends most of their time dismissing noise."**
> Solved with: hybrid detection stacks, ML anomaly models, LLM entity disambiguation, graph analytics.

> **"Our onboarding takes 28 days. Our competitors are doing it in 5. We're losing UHNW clients before they sign."**
> Solved with: agentic AI orchestration, multi-agent CLM workflows, human-in-the-loop governance.

> **"We have 14 systems that each hold a partial view of the client. Nobody knows which one is the truth."**
> Solved with: event sourcing, domain-driven design, bounded context decomposition, canonical data models.

This is the work. Not "implementing microservices." Not "deploying LLMs." Diagnosing the business problem first, then designing the architecture that solves it — with the regulatory, operational, and technology constraints of a live Tier 1 institution fully in view.

---

## What I Have Delivered

<table>
<tr>
<td width="50%" valign="top">

### Financial Crime

**AI-Powered AML Screening Platform**
Unified transaction monitoring, PEP/sanctions screening, and adverse media into a single AI-augmented platform with a hybrid rules/ML/LLM detection stack.

`70% false positive reduction` `60% faster resolution` `Neo4j entity graph` `Explainable AI outputs`

[Architecture Reference](./architectures/02-aml-hybrid-detection.md)

---

**Continuous KYC Screening on GCP**
Real-time client and transaction monitoring using event-driven streaming, replacing a batch-overnight model that left 24-hour blind spots in the compliance posture.

`Pub/Sub + Dataflow` `Vertex AI risk scoring` `World-Check + Factiva APIs` `Audit-ready BigQuery layer`

</td>
<td width="50%" valign="top">

### Wealth Management and CLM

**iCLM: Intelligent Client Lifecycle Management**
Multi-agent onboarding system for private banking. LangGraph orchestration, RAG-powered policy retrieval, human-in-the-loop governance. Production-representative design reference for Avaloq/Temenos clients.

`LangGraph` `LlamaIndex` `FastAPI` `GCP` `Pinecone`

[Architecture Reference](./architectures/01-iCLM-agentic-onboarding.md)

---

**Perpetual KYC Event-Driven Platform**
£5M transformation from periodic batch KYC to continuous event-driven pKYC. Domain-driven microservices on Azure, strangler fig decomposition of legacy Pega monolith.

`£1.2M annual savings` `Azure AKS + Event Grid` `DDD bounded contexts` `FCA / GDPR compliant`

[Architecture Reference](./architectures/03-pkyc-event-driven-platform.md)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Operations and Intelligence

**RAG Chatbot: Settlement, Asset and Collateral Operations**
LLM-powered chatbot with RAG framework for operational teams handling settlement, asset servicing, and collateral queries across internal systems.

`60% query resolution reduction` `LangChain + Azure OpenAI` `Pinecone` `RBAC via IAM`

</td>
<td width="50%" valign="top">

### Core Banking Integration

**DBS Wealth Platform Integration**
Avaloq e-banking to core banking synchronisation for portfolio-related corporate actions, client reporting, and record maintenance across the DBS iWealth platform.

`Avaloq CAPI` `Kafka event streaming` `Java / Spring Boot` `Kubernetes`

</td>
</tr>
</table>

---

## Architecture Philosophy

*Grounded in the work of Gregor Hohpe, Simon Brown, Sam Newman, and Martin Fowler — and tested against the realities of regulated financial services delivery.*

<br/>

**01. The business problem is always the real architecture problem.**

Technology is a medium, not a destination. Before drawing a single box on a diagram, I want to understand what decision the business cannot currently make, what process is breaking under its own weight, and what regulatory obligation is creating friction. The architecture emerges from that understanding. Not the other way around.

<br/>

**02. In financial services, events are facts. Model them that way.**

A KYC risk signal was detected. A transaction was flagged. A client's beneficial ownership structure changed. These are not requests waiting for a response — they are immutable facts that occurred in the world. Gregor Hohpe's insight here is foundational: event-driven systems in banking are not an architectural preference, they are an epistemological requirement. Your audit trail depends on it.

<br/>

**03. Regulated AI must be explainable before it is accurate.**

A 94% accurate model that cannot explain its decision to a compliance officer, a regulator, or an internal audit function cannot go to production in a Tier 1 bank. Full stop. Explainability, audit trail, human override capture, and model governance are first-class architecture requirements — not afterthoughts bolted on at the end of an ML sprint.

<br/>

**04. Architecture governance is a design accelerator, not a gate.**

Technical Design Authority, Architecture Decision Records, and design reviews exist because the cost of a bad architecture decision compounds over time in ways a bad code decision does not. A wrong database choice at week two becomes a £3M migration at year three. Governance structures that catch these decisions early are the fastest path to delivery, not the slowest.

<br/>

**05. Decompose to the boundary of change, not to the boundary of services.**

Sam Newman's principle: the right microservice boundary is not the one that maps to a team, or a data entity, or a functional area. It is the one that maps to an independent axis of change. In banking, this means understanding which capabilities change at different rates — regulatory rules change quarterly, product rules change annually, core ledger logic almost never changes. Design the seams around the rate of change.

---

## Architecture Decision Records

Every significant design decision in my work is documented as an ADR — written at the point of decision, capturing what was known, what was uncertain, what alternatives were considered, and what trade-offs were accepted.

```
┌─────────────────────────────────────────────────────────────────────────┐
│  PUBLISHED ADRs                                                          │
├──────┬──────────────────────────────────────────────────────────────────┤
│ ADR  │ Decision                                                          │
├──────┼──────────────────────────────────────────────────────────────────┤
│ 001  │ LangGraph over CrewAI for regulated financial services agents     │
│ 002  │ Event-driven over request-response for pKYC state transitions     │
│ 003  │ RAG over fine-tuning for frequently-updated policy retrieval      │
│ 004  │ Hybrid rules + ML + LLM stack over single-model AML detection     │
│ 005  │ Neo4j over relational store for AML entity relationship queries   │
│ 006  │ Append-only event store over mutable client record as SoT        │
│ 007  │ Strangler fig over big-bang rewrite for Pega CLM decomposition    │
│ 008  │ Private LLM endpoint over public API for PII-adjacent inference   │
└──────┴──────────────────────────────────────────────────────────────────┘
Full ADR documents embedded in each architecture reference.
```

---

## The Regulatory Landscape I Design Within

One of the things that separates financial services architecture from most other domains is that the regulatory framework is not a constraint you satisfy at the end — it is a design input from day one.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  REGULATORY FRAMEWORK MAP                                                    │
├──────────────────┬──────────────────────────────────────────────────────────┤
│  FCA SYSC        │  Systems and controls for operational resilience,         │
│                  │  record-keeping, and outsourcing governance               │
├──────────────────┼──────────────────────────────────────────────────────────┤
│  MiFID II        │  Suitability assessment, product governance,              │
│                  │  best execution, transaction reporting                    │
├──────────────────┼──────────────────────────────────────────────────────────┤
│  GDPR / UK GDPR  │  Data minimisation, purpose limitation, right to erasure,│
│                  │  Article 22 automated decision-making restrictions        │
├──────────────────┼──────────────────────────────────────────────────────────┤
│  PSD2            │  Strong customer authentication, API-first mandates,      │
│                  │  third-party provider integration architecture            │
├──────────────────┼──────────────────────────────────────────────────────────┤
│  CSDR            │  Settlement discipline, buy-in mechanisms,                │
│                  │  Central Securities Depositories regulation               │
├──────────────────┼──────────────────────────────────────────────────────────┤
│  EU AI Act       │  High-risk AI classification, human oversight mandates,   │
│                  │  model documentation, conformity assessment               │
├──────────────────┼──────────────────────────────────────────────────────────┤
│  6AMLD / JMLSG   │  AML/CFT obligations, beneficial ownership transparency, │
│                  │  suspicious activity reporting, record retention          │
├──────────────────┼──────────────────────────────────────────────────────────┤
│  SM&CR           │  Senior Manager accountability, conduct rules,            │
│                  │  responsibility mapping for architecture decisions        │
└──────────────────┴──────────────────────────────────────────────────────────┘
```

---

## Tech Stack

<div align="center">

**Agentic AI and Intelligence**

![LangGraph](https://img.shields.io/badge/LangGraph-0D1B2A?style=flat-square&logo=python&logoColor=7BAFD4)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-1B3A5C?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-2C3E50?style=flat-square&logo=chainlink&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic%20Claude-C5A028?style=flat-square&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex%20AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)

**Cloud and Platform**

![GCP](https://img.shields.io/badge/GCP%20Certified-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Pub/Sub](https://img.shields.io/badge/Pub%2FSub-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

**Languages, Data, and Integration**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)

**Banking Platforms and Security**

![Avaloq](https://img.shields.io/badge/Avaloq%20Banking%20Suite-0D1B2A?style=flat-square&logoColor=white)
![Pega](https://img.shields.io/badge/Pega%20CLM-00A3E0?style=flat-square&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2%20%2F%20OIDC-EB5424?style=flat-square&logo=auth0&logoColor=white)
![Zero Trust](https://img.shields.io/badge/Zero%20Trust-1B3A5C?style=flat-square&logoColor=white)

</div>

---

## What I Am Currently Working On

```
[ ACTIVE ]   iCLM v2 — extending the multi-agent onboarding system with
             multi-modal document intelligence for handwritten source-of-wealth
             declarations. Exploring vision LLMs for structured extraction.

[ ACTIVE ]   EU AI Act compliance framework for financial services AI systems.
             Mapping high-risk AI classifications to architecture patterns and
             governance controls for Tier 1 bank deployment contexts.

[ RESEARCH ] Graph-based entity resolution at scale — combining Neo4j network
             analytics with LLM-powered disambiguation for financial crime
             detection across complex beneficial ownership structures.

[ WRITING ]  Architecture patterns for agentic AI in regulated environments:
             how to build autonomous systems that a regulator, a compliance
             officer, and a CISO can all sign off on simultaneously.
```

---

## Writing and Thought Leadership

I write for practitioners — architects, senior engineers, and technology leaders in financial services who want substance over hype.

| Article | Theme |
|---|---|
| [AI-Native PBWM: What Tier 1 Banks Need to Architect Now](#) | How private banks need to restructure their technology stack to compete with AI-native challengers |
| [Agentic AI Architecture Patterns for Private Banking](#) | Practical patterns for building multi-agent systems that work in regulated environments |
| [Why Perpetual KYC Requires Event-Driven Architecture](#) | The epistemological case for modelling KYC state changes as domain events |
| [Responsible AI in Financial Services: A Practitioner's Framework](#) | Moving beyond AI ethics statements to governance architecture that actually ships |
| [The Hidden Cost of the AML False Positive](#) | How poor detection architecture erodes compliance team capacity and creates blind spots |

---

## Ecosystem and Collaborations

```
Google Cloud Partner    Deep collaboration on GCP-native financial services
                        architecture patterns and joint client GTM delivery.

Keyless                 Zero-Trust biometric continuous authentication
                        integration architecture for banking channels.

Synpulse BANKA          Architecture Centre of Excellence lead for the
                        EU/UK Private Banking and Wealth Management practice.
```

---

<div align="center">

```
"Most people think of architecture as a noun — a thing you produce.
 I think of it as a verb — a practice of continuous alignment
 between what the business needs to decide
 and what the system makes possible."
```

<br/>

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sarkarsaurabh)&ensp;
[![Email](https://img.shields.io/badge/Get%20in%20Touch-1B3A5C?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saurabhlaxmansarkar@email.com)

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0D1B2A&height=4"/>

<sub>Last updated Q1 2025 &nbsp;·&nbsp; London, UK &nbsp;·&nbsp; Open to Principal SA and Lead Architect conversations</sub>

</div>
