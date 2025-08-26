# Dagu

**Dagu** is a next-generation secure chat platform that leverages **Quantum Key Distribution (QKD)** for encryption. Inspired by the traditional Ethiopian communication system *Dagu* (trusted word-of-mouth network), our project ensures **ultra-secure peer-to-peer communication** resistant to classical and quantum attacks.  


## Features  

-  **Quantum Key Distribution (QKD):** Encryption keys are generated and exchanged using quantum-safe algorithms.  
-  **End-to-End Encrypted Chat:** All messages are encrypted with session keys derived from QKD.
-  **Cross-Platform Support:** Designed for desktop & mobile clients.  


## How It Works  

1. **Key Generation:**  
   - Quantum-safe keys are generated using Haileab’s QKD algorithm.  
   - Each chat session uses a new key.  

2. **Key Exchange:**  
   - Secure channel established with quantum-resistant protocols.  
   - Keys are verified using authentication layers.  

3. **Chat Encryption:**  
   - Messages are encrypted using symmetric cryptography derived from QKD.  
   - Metadata is minimized to prevent traffic analysis.  



## Tech Stack  

- **Frontend :** Flutter (Dart) or React Native (JavaScript/TypeScript) – cross-platform support for Android & iOS  
- **Backend:** FastAPI (Python) – handles APIs and encryption logic  
- **Encryption Layer:** Python (Quantum Key Distribution + Post-Quantum Cryptography)  
- **Database :** Firebase (Auth + Realtime Database/Firestore) or PostgreSQL if self-hosted  
- **Real-time Communication:** WebSockets (for live chat)  
- **Deployment:** Docker (for backend services) + Cloud Hosting (AWS, GCP, or Firebase Hosting)  


## Team

- **Paulos Berihun** – Backend Developer 
- **Haileab Mulugeta** – Quantum Key Distribution & encryption , Front End Dev
