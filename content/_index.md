+++
title = "Victor Soto"
description = "Senior Platform Engineer focused on cloud infrastructure, reliability, and real-time media systems."
template = "index.html"

[extra]
role = "Senior Platform Engineer"
specialty = "Cloud Infrastructure & Reliability"
email = "vsoto26@gmail.com"
linkedin = "https://linkedin.com/in/vsoto26"
summary = "I automate, secure, and operate cloud infrastructure for production real-time media services. My work spans Kubernetes, Terraform, and CI/CD across Azure, GCP, and AWS, including regulated FedRAMP and CCCS environments. I build observability and internal tooling that help teams ship and troubleshoot faster, with a background in Rust, distributed systems, and electrical and computer engineering."
+++

## Experience

### Motorola Solutions

**Software Engineer** · 2019–Present

#### Kubernetes, Terraform & CI/CD

- Automate infrastructure, VM image builds, and environment promotion across Azure, GCP, and AWS using Kubernetes, Helm, Terraform, Bicep, Packer, and CI/CD.
- Manage GitOps deployments with Argo CD and Helm, including ephemeral per-release service instances and blue/green releases.
- Provision cloud infrastructure including IAM, service accounts, secret access, messaging topics, and artifact registries.
- Roll out TURN relay VM scale sets progressively, with automated testing gates before promotion to each environment.
- Moved build pipelines to an elastic VM-scale-set agent pool; maintain the build toolchain and base images, including Ubuntu 24.04 and GStreamer 1.28.
- Added OpenAPI contract testing to pull-request pipelines to catch API regressions before merge.

#### Observability & Incident Response

- Designed and built an internal observability and incident-triage platform with FastAPI and React/TypeScript for live log streaming, correlation, and cross-environment Kubernetes and cloud log queries.
- Added LLM-assisted investigation with Vertex AI, Gemini, and Claude; MCP integrations; Jira and GitHub workflows; and SAML/Okta single sign-on.
- Enabled distributed tracing, OpenTelemetry, and APM instrumentation across services, with consistent resource attributes for clearer logs and traces.
- Added readiness and liveness checks, automated cleanup of orphaned resources using Kubernetes owner references, and runbooks for deployment, blue/green releases, disaster recovery, alerting, and failure playbooks.

#### Infrastructure Security

- Serve as the team's Cybersecurity Champion, driving security improvements across services, build pipelines, and deployment images.
- Enabled FIPS cryptographic modules in FedRAMP and CCCS VM image builds; implemented mTLS between services, JWT scope enforcement, and input sanitization for public APIs.
- Integrated Dependency-Track and SonarQube scanning into CI for Rust and Java services; remediated container and OS-library vulnerabilities, including glibc and Prisma Cloud findings.
- Manage service credentials through cloud secret managers and external-secret integrations rather than static configuration.

#### Application Development

- Develop Rust and GStreamer media services for WebRTC, RTSP, and HLS, plus Java session-control services, with readiness signaling, retries, and automated session cleanup.

## Technical Skills

- **Cloud & Platform:** Azure, GCP, AWS, Kubernetes, Helm, Argo CD, Terraform, Bicep, Packer, CI/CD
- **Observability:** OpenTelemetry, distributed tracing, Cloud Logging, log correlation
- **Security:** mTLS, JWT/OAuth, SAML/Okta, FIPS, Dependency-Track, SonarQube, secrets management
- **Languages:** Rust, Python, Java, TypeScript, Bash
- **Systems:** FastAPI, React, Kafka, GStreamer, WebRTC, MCP, Vertex AI

## Research & Teaching

### Research Assistant · PARADISE Lab, University of Ottawa

**Jul 2016–Dec 2018**

Designed and simulated communication and routing protocols for vehicular networks (V2V, V2I, V2X) under the NSERC DIVA and NSERC CREATE TRANSIT programs using C/C++, Python, OMNeT++, SUMO, and VEINS.

### Teaching Assistant · University of Ottawa

**Jan 2017–Dec 2017**

Led labs for the Electrical Engineering Design Project and mentored student teams through design, testing, and patent applications.

## Education

### MASc, Electrical and Computer Engineering

**University of Ottawa** · 2016–2018

Thesis: “Mobility-Oriented Data Retrieval Protocol for Vehicular Edge Computing.”

## Selected Publications

- V. Soto, R. E. De Grande, and A. Boukerche, “Repro: Time-constrained data retrieval for edge offloading in vehicular clouds,” ACM PE-WASUN, 2017.
- A. Boukerche and V. Soto, “An Efficient Mobility-Oriented Retrieval Protocol for Computation Offloading in Vehicular Edge Multi-Access Network,” *IEEE Transactions on Intelligent Transportation Systems*, 2020.
- A. Boukerche and V. Soto, “Computation Offloading and Retrieval for Vehicular Edge Computing: Algorithms, Models, and Classification,” *ACM Computing Surveys*, 2020.
