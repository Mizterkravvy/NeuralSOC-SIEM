🔐 NeuralSOC-SIEM

AI-Powered Security Information & Event Management Platform

NeuralSOC-SIEM is a real-time cybersecurity monitoring system that combines **traditional SOC engineering** with an **AI-powered SOC Copilot** for automated incident analysis, threat detection, and security intelligence.

It is designed as a **production-grade SIEM architecture simulation** and a **portfolio-level cybersecurity engineering project**.


Problem It Solves

Modern security teams face:

- High-volume log streams
- Slow manual incident investigation
- Lack of contextual alert explanations
- Fragmented security tools

NeuralSOC-SIEM solves this by combining:

✔ Real-time log ingestion  
✔ Automated threat detection  
✔ AI-driven incident explanation  
✔ MITRE ATT&CK mapping  
✔ Live SOC dashboard  


Key Features

Real-Time Security Monitoring
- Live log ingestion pipeline
- Stream-based event processing
- WebSocket-powered SOC dashboard

Threat Detection Engine
- Brute force detection
- IP anomaly detection
- Authentication failure correlation
- Extensible rule-based system

AI SOC Copilot
- ChatGPT-style incident explanations
- Attack classification
- Risk scoring (Low → Critical)
- Recommended mitigation steps
- MITRE ATT&CK mapping

SOC Dashboard
- Real-time event feed
- Alert visualization panel
- Incident tracking interface
- Timeline reconstruction


System Architecture

text
Log Sources
   ↓
Ingestion API (FastAPI)
   ↓
Event Queue Layer
   ↓
Detection Engine (Rules + Analytics)
   ↓
Storage Layer (SQLite / Elasticsearch-ready)
   ↓
AI SOC Copilot (RAG + MITRE Mapping)
   ↓
WebSocket Dashboard (Real-time SOC UI)