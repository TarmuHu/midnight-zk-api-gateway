# Midnight ZK API Gateway - Midnight Hackathon Submission

Welcome to our submission for the Midnight Hackathon! We built the **Midnight ZK API Gateway**, a middleware solution designed to put users back in control of their personal data by integrating Zero-Knowledge (ZK) proofs into existing API infrastructures.

## Inspiration
Our project was inspired by the vulnerability of traditional REST APIs that leak user data in plain text. We wanted to build a solution that addresses these privacy concerns by ensuring sensitive information is protected at the edge before it ever reaches legacy backend systems.

## What it does
The Midnight ZK API Gateway acts as a privacy-preserving middleware. Instead of sending a traditional username and password in plaintext, the client submits a ZK credential to our simulated Gateway. The Gateway verifies the proof and ensures that credentials are never exposed to the legacy backend, seamlessly protecting everyday user privacy while maintaining functionality.

## How we built it
We repurposed an existing API testing portfolio into a Proof of Concept (PoC). To build this, we utilized:
- **Postman/Newman:** For client simulation and automated data-driven testing (DDT).
- **GitHub Actions:** To set up our CI/CD pipeline for automated verification.
- **Postman Echo:** To mock the Midnight ZK Gateway verification endpoint.
- **Jules AI:** To assist with rapid script generation and refactoring.

## Challenges we ran into
One of the biggest hurdles we faced during the hackathon was dealing with severe time constraints due to a busy work schedule. Despite this, we focused on delivering a polished and functionally complete prototype within the timeframe.

## Accomplishments that we're proud of
We are incredibly proud to have successfully demonstrated that a ZK privacy layer can be seamlessly integrated into an existing CI/CD automated API pipeline as a gateway. It proves that you don't need to rebuild legacy systems from scratch to significantly enhance digital privacy and security.

## What we learned
Throughout this weekend, we learned how to conceptualize and design a ZK API Gateway at the edge to protect legacy systems. Exploring how to implement privacy-preserving middleware gave us fresh insights into the future of digital identity and security.

## What's next for Midnight ZK API Gateway
We plan to replace the mocked endpoint with actual Midnight Compact smart contracts to generate and verify real cryptographic ZK proofs. Eventually, we aim to package this entire solution into a reusable Node.js SDK so other developers can easily add a ZK privacy layer to their own APIs.

---

## 📬 Contact

- **Name:** Tarmu Hu
- **LinkedIn:** [linkedin.com/in/tarmu-hu-2b7948200](https://www.linkedin.com/in/tarmu-hu-2b7948200)
- **Portfolio:** [tarmuhu.github.io/cpsc349-portfolio](https://tarmuhu.github.io/cpsc349-portfolio/index.html)
