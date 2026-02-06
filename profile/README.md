<div align="center">

<!-- Banner -->
<img src="https://raw.githubusercontent.com/DaoDial/.github/main/profile/banner.png" alt="DaoDial Banner" width="100%"/>

<!-- Animated Header -->
<img src="https://capsule-render.vercel.app/api?type=transparent&height=80&text=Web3%20Communication%20Platform&fontSize=32&fontColor=333&animation=fadeIn" width="100%"/>

<p>
  <a href="https://www.daodial.com">
    <img src="https://img.shields.io/badge/Website-daodial.com-000000?style=for-the-badge&logo=safari&logoColor=white" alt="Website"/>
  </a>
  <a href="https://web.daodial.com">
    <img src="https://img.shields.io/badge/Launch_App-web.daodial.com-4F46E5?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Web App"/>
  </a>
  <a href="https://apps.apple.com/app/daodial-onchain-communication/id6757168898">
    <img src="https://img.shields.io/badge/App_Store-Download-0D96F6?style=for-the-badge&logo=app-store&logoColor=white" alt="App Store"/>
  </a>
  <a href="https://x.com/daodialapp">
    <img src="https://img.shields.io/badge/Twitter-@daodialapp-1DA1F2?style=for-the-badge&logo=x&logoColor=white" alt="Twitter"/>
  </a>
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

</div>

## About DaoDial

DaoDial is a **privacy-first communication platform** built for the Web3 ecosystem. We enable secure, encrypted messaging with wallet-based authentication and token-gated access controls.

<table>
<tr>
<td width="50%" valign="top">

### What We Build

- **End-to-End Encrypted Messaging** — Signal Protocol implementation ensuring only you and your recipient can read messages
- **Token-Gated Communities** — Access controlled by NFT or token ownership, verified on-chain
- **Wallet-First Identity** — No emails, no passwords. Your wallet is your identity
- **Cross-Platform** — Native iOS, Android, and Web applications

</td>
<td width="50%" valign="top">

### Why DaoDial

Traditional messaging apps collect your data. Existing Web3 solutions lack proper encryption. DaoDial bridges this gap — bringing enterprise-grade security to decentralized communication.

**Your messages. Your keys. Your privacy.**

</td>
</tr>
</table>

---

## Platform Architecture

```
                              ┌──────────────────────────────────────┐
                              │           DaoDial Platform           │
                              └──────────────────────────────────────┘
                                              │
              ┌───────────────────────────────┼───────────────────────────────┐
              │                               │                               │
              ▼                               ▼                               ▼
     ┌─────────────────┐           ┌─────────────────┐           ┌─────────────────┐
     │   Mobile Apps   │           │    Web Client   │           │  Landing Page   │
     │   iOS/Android   │           │   Next.js PWA   │           │   Marketing     │
     └────────┬────────┘           └────────┬────────┘           └─────────────────┘
              │                               │
              └───────────────┬───────────────┘
                              │
                              ▼
                    ┌─────────────────┐
                    │   Backend API   │
                    │   Node.js/TS    │
                    └────────┬────────┘
                              │
          ┌───────────────────┼───────────────────┐
          │                   │                   │
          ▼                   ▼                   ▼
   ┌─────────────┐    ┌─────────────┐    ┌─────────────┐
   │  Database   │    │   Solana    │    │    Push     │
   │  PostgreSQL │    │  Blockchain │    │   Services  │
   └─────────────┘    └─────────────┘    └─────────────┘
```

---

## Repositories

| Repository | Description | Stack |
|:-----------|:------------|:------|
| **api** | Backend services, real-time messaging, authentication | Node.js, TypeScript, Socket.io, PostgreSQL |
| **web** | Web application with full messaging capabilities | Next.js, React, TypeScript |
| **mobile** | Native mobile apps for iOS and Android | React Native, Expo |
| **landing** | Marketing website and documentation | Next.js, Tailwind CSS |

---

## Infrastructure

<table>
<tr>
<td width="50%">

### Cloud Services
- **Compute** — AWS ECS Fargate (containerized)
- **Database** — Amazon RDS PostgreSQL
- **Storage** — Amazon S3
- **CDN** — CloudFront
- **Frontend Hosting** — AWS Amplify

</td>
<td width="50%">

### DevOps
- **CI/CD** — GitHub Actions
- **Container Registry** — Amazon ECR
- **Monitoring** — CloudWatch
- **Mobile Builds** — Expo EAS

</td>
</tr>
</table>

---

## Security

| Layer | Implementation |
|:------|:---------------|
| **Message Encryption** | Signal Protocol (Double Ratchet, X3DH) |
| **Key Storage** | Device-local secure storage |
| **Authentication** | Wallet signature verification |
| **Access Control** | On-chain token ownership verification |
| **Transport** | TLS 1.3 / WSS |

---

## Coming Soon

<div align="center">

| Feature | Status |
|:--------|:------:|
| **P2P Payments** — Venmo-style crypto transfers in chat | In Development |
| **Group Payments** — Split bills with token holders | Planned |
| **Payment Requests** — Request funds from contacts | Planned |

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

**DaoDial** — Secure communication for the decentralized world

[Website](https://www.daodial.com) · [Web App](https://web.daodial.com) · [Twitter](https://x.com/daodialapp)

<sub>© 2026 DaoDial. All rights reserved.</sub>

</div>
