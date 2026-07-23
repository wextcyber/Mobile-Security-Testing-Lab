# Mobile Penetration Testing & Application Security Lab

Welcome to my active mobile application security testing laboratory portfolio. This repository serves as documentation for my hands-on technical environments, deployment configurations, and runtime analysis frameworks utilized to discover mobile vulnerabilities.

## 🛠️ Environment Architecture & Core Tooling

My testing architecture is engineered from scratch to perform both static and dynamic analysis of Android application packages (`.apk`):

*   **Host OS:** Kali Linux (Dedicated environment configured for network traffic interception and security auditing).
*   **Virtual Device Emulator:** Genymotion Engine (Configured with custom virtual Android devices, system architecture translations, and root access permissions).
*   **Dynamic Instrumentation Framework:** Frida Toolkit & Frida Gadget (Utilized for active memory injection, runtime function hooking, and debugging).

## 🚀 Active Capabilities & Lab Use Cases

I utilize this self-hosted environment to simulate real-world mobile app security audits:

1. **Runtime Instrumentation & Hooking:** Injecting Frida Gadget directly into application packages to monitor API calls and trace active crypto processes.
2. **SSL Pinning Bypassing:** Modifying application behaviors at runtime to intercept encrypted HTTPS traffic via localized proxy configurations.
3. **Sensitive Data Exposure Audits:** Inspecting the virtual device file system (`/data/data/`) to identify insecure storage practices, unencrypted local databases, and exposed API keys.

---

### 📸 Lab Configuration Proof of Concept (PoC)

*Below are live captures verifying the operational functionality of my local testing network infrastructure:*

#### 1. Unified Workspace Environment
*![Unified Workspace Layout](Full%20workspace%20layout%20image%20stage1.png)*
*Description: Full-screen display showing the integrated Kali Linux workspace running a root-access Genymotion virtual device next to the shell terminal.*

#### 2. Frida Gadget Deployment & Injection
*![Frida Active Injection Handshake](Handshake%20connection%20line%20image%20stage2.png)*
*Description: Terminal log capturing the exact moment the Frida framework successfully injects into the target application binary package.*

#### 3. Active Runtime Traffic Analysis
*![Frida Live Trace Logs](Frida%20active%20trace%20logs%20image%20stage3.png)*
*Description: Dynamic interaction sequence tracing runtime functions and capturing memory hooks during an active application session simulation.*

### Lab Demonstration Assets
#### Stage 1: Infrastructure & Testing Environment![Stage 1](Full%20workspace%20layout%20image%20stage1.png)
#### Stage 2: Target Emulator Handshake Connection Verification![Stage 2](Handshake%20connection%20line%20image%20stage2.png)
#### Stage 3: Dynamic Framework Instrumentation Tracing Logs![Stage 3](Frida%20active%20trace%20logs%20image%20stage3.png)
