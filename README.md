# ⚡ Tech-Pages

An interactive, natively-animated encyclopedia of complex engineering and infrastructure systems, visualized elegantly inside the browser without external dependencies.

**🌍 Live Preview:** [tech-pages.rishabhtomar.com](https://tech-pages.rishabhtomar.com)

## ✨ Features
- **100% Native Browser Functionality:** Built entirely with raw HTML, CSS, and Vanilla JavaScript—absolutely no external node modules or heavy frameworks required.
- **Interactive Simulators:** Hands-on visualizers for otherwise abstract and complex concepts like PKI Cryptography, DNS Routing, and Storage Architecture.
- **Responsive & Modern UI:** Features a heavily stylized, sleek dark mode design utilizing neat neon gradients, tailored custom CSS micro-animations, and a highly responsive grid layout.
- **Self-Contained Modules:** Every single topic runs independently in its own fully portable `HTML` file, meaning things can be accessed offline natively without needing a backend server.

## 📂 Project Structure

```text
tech-pages/
│
├── index.html                   # Main central hub and categorical landing page
│
├── 🔐 Security & Cryptography
│   ├── e2ee.html                # End-to-End Encryption
│   ├── encryption.html          # Sym / Asym Encyption
│   ├── public-key-crypto.html   # Public Key Cryptography
│   ├── rsa-math.html            # RSA Key Generation
│   ├── ssl-tls.html             # SSL/TLS Handshake
│   ├── ca-notary.html           # Certificate Authorities
│   ├── mitm.html                # Man-in-the-Middle
│   ├── fido2-passkeys.html      # FIDO2 / Passkeys
│   └── jwt.html                 # Json Web Tokens (JWT)
│
├── 👤 Authentication & Access Rules
│   ├── mfa-factors.html         # MFA Mechanics
│   ├── mfa-totp.html            # Time-Based OTP (TOTP)
│   ├── oauth.html               # OAuth 2.0 Auth Flow
│   └── cookies-localstorage.html# Browser State Storage
│
├── 🌍 Networking & Anonymity Maps
│   ├── dns.html                 # DNS Resolution
│   ├── proxy.html               # Proxy Servers
│   ├── vpn.html                 # Virtual Private Networks
│   ├── tor-network.html         # Tor Network (Onion)
│   ├── websocket-vs-http.html   # WebSocket vs HTTP
│   ├── ssh.html                 # SSH Protocol
│   └── ssh-agent.html           # SSH Agent Forwarding
│
├── 🏗️ Infrastructure Architecture
│   ├── load-balancer.html       # Load Balancing
│   ├── cdn.html                 # Content Delivery (CDN)
│   ├── containers-vs-vms.html   # Containers vs VMs
│   ├── db-indexing.html         # Database Indexing
│   ├── raid.html                # RAID Storage
│   └── blockchain.html          # Blockchain Mechanics
│
└── 🛠️ Software & Hardware Dev
    ├── git-branching.html       # Git Branching
    ├── dark-mode-css.html       # CSS Component Theming
    └── typec.html               # USB-C Mapping Architecture
```

## 📜 License
This project is licensed under the [MIT License](LICENSE).
