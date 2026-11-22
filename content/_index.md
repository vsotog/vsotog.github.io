+++
title = "Victor Soto"
description = "Senior Software Engineer focused on real-time media, distributed systems, and cloud security."
template = "index.html"

[extra]
role = "Senior Software Engineer"
specialty = "Real-Time Media, Distributed Systems & Cloud Security"
linkedin = "https://linkedin.com/in/vsoto26"
summary = "I build and operate production real-time media and cloud systems, combining deep protocol knowledge across WebRTC, RTSP, and HLS with backend, infrastructure, and security engineering. I bring 7+ years of software engineering experience and an MASc in Electrical and Computer Engineering, with peer-reviewed research on distributed edge computing."
+++

## Experience

### Motorola Solutions

**Software Engineer** · 2019–Present

#### Real-Time Media & Distributed Systems

- Design and build Rust and GStreamer media services for WebRTC, RTSP, and HLS sessions, including SDP/ICE negotiation, codec support, and recording lifecycle management.
- Extended an SFU-based broadcast session type to accept HLS and RTSP sources; built local RTSP test infrastructure and load tests to validate protocol paths end to end before release.
- Improved resilience to worker failures with readiness signaling, request retries, automated session cleanup, and reliable recording finalization.
- Improved WebRTC connectivity across client networks by fixing IPv6 candidate handling and adding authentication to TURN relay servers.
- Extended Java session-control services with conference sessions, audio routing, remote audio commands, and capability-based session selection, using feature flags for gradual rollout.

#### Cloud Infrastructure & Developer Tooling

- Automate infrastructure, VM image builds, and environment promotion across Azure, GCP, and AWS using Kubernetes, Helm, Terraform, Bicep, Packer, and CI/CD, including progressive rollout of TURN server fleets.
- Designed and built an internal observability and incident-triage platform with live log streaming, correlation, and cross-environment Kubernetes and cloud log queries.
- Added LLM-assisted investigation with Vertex AI, Gemini, and Claude; MCP integrations; Jira and GitHub workflows; and SAML/Okta single sign-on.
- Added OpenAPI contract testing, distributed tracing, and load testing to catch regressions before production.

#### Security & Reliability

- Serve as the team's Cybersecurity Champion, driving security improvements across services, build pipelines, and deployment images.
- Enabled FIPS cryptographic modules in FedRAMP and CCCS VM image builds; implemented mTLS between services, JWT scope enforcement, and input sanitization for public APIs.
- Integrated Dependency-Track and SonarQube scanning into CI for Rust and Java services; remediated container and OS-library vulnerabilities, including glibc and Prisma Cloud findings.

## Technical Skills

- **Languages:** Rust, Java, Python, TypeScript, Bash
- **Media & Networking:** GStreamer, WebRTC, SDP/ICE, RTP, RTSP, HLS, STUN/TURN
- **Cloud & Platform:** Azure, GCP, AWS, Kubernetes, Helm, Terraform, Bicep, Packer, CI/CD
- **Security:** mTLS, JWT/OAuth, SAML/Okta, FIPS, Dependency-Track, SonarQube
- **Systems:** FastAPI, React, Tokio, Spring Boot, Kafka, OpenTelemetry, MCP, Vertex AI

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
