# DeepFindAI Core Framework

A modular AI & Orchestration Framework

## Overview

This framework features:
- Drag & drop UI for LLM flow creation
- Multi-LLM integration and multi-agent collaboration
- The Model Context Protocol (MCP)
- Vector DB & RAG module using Qdrant/Milvus
- Docker-based sandbox for secure code execution, testing, and auto-fixing

## Quick Start

```bash
# Clone the repository
git clone https://github.com/DeepFindAl/DeepFindAl.git
cd DeepFindAl

# Start the project using Docker Compose
docker-compose up
```

## Project Structure

```
/DeepFindAI
├── /frontend         # Drag & drop UI
├── /backend          # Core orchestration engine and API
│   ├── /api          # FastAPI REST endpoints and WebSockets
│   ├── /core         # DeepFindAI Core Application
│   └── /sandbox      # Secure code execution environment
├── /open             # Custom Integrations for Components/Modules/Tools [Open Source Part]
└── /docs             # Documentation
```

## Documentation

For detailed usage instructions, see the `/docs` directory:
- [Installation Guide](docs/INSTALLATION.md)
- [Quick Start Guide](docs/QUICKSTART.md)
- [Usage Examples](docs/USAGE.md)

## Licensing

### Commercial License
Most components of DeepFindAI Core Framework are proprietary and require a commercial license or subscription to use. DeepFindAI offers both pay-per-use and subscription-based pricing models.

### Open Source Components
Only specific components related to MCP (Model Context Protocol), modules, and tools are available as open source under the MIT License.

For licensing inquiries or to obtain a commercial license, please contact licensing@---.com or visit our [pricing page](https://---/pricing). 