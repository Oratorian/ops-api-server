API Service
This project implements a modular and rate-limited API service designed for secure key management and system operations monitoring. The service is built with scalability, resilience, and operational control in mind.

Key Features
🔐 API Key Management
Generate API Keys: Securely create new API keys for client authentication.

View API Keys: Retrieve and list currently active API keys.

Delete API Keys: Remove keys to revoke access in real time.

🚦 Rate Limiting & Concurrency Control
Rate Limiting (ratelimit.py): Enforces per-client request limits to prevent abuse and ensure fair resource usage.

Concurrency Limits (conlimit.py): Restricts concurrent API access, improving stability under load.

🔧 System Utilities
Service Restart Endpoint: Programmatically restart backend services when needed.

Health Check Endpoint: Provides operational status for uptime monitoring and reliability checks.

🛠 Configuration & Setup
Dynamic Config (config.py): Centralized configuration module for managing system-wide settings.

Setup Script: Easy installation and dependency management via setup.py and requirements.txt.

🧩 Modular Architecture
Endpoint Separation: Logical division of routes (e.g., key management, system operations) enhances maintainability.

Utility Functions (utils.py, watcher.py): Support services and background operations.
