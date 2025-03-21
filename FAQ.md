# Frequently Asked Questions

## General Questions

### What is the DeepFindAI Core Framework?
The DeepFindAI Core Framework is a modular system designed for commercial use, providing tools for creating, deploying, and managing AI workflows with a focus on LLM orchestration and multi-agent collaboration.

### What are the main components?
1. Drag & drop UI for flow creation
2. LLM orchestration and multi-agent collaboration systems
3. FastAPI backend for API and WebSocket communication
4. Vector database integration for RAG capabilities
5. Docker-based sandbox for secure code execution

### What can I build with this framework?
- Conversational AI applications
- Document analysis and retrieval systems
- Autonomous agent systems for task automation
- Custom LLM workflows for specific business needs
- Code generation and testing pipelines

## Technical Questions

### Which LLM providers are supported?
The framework supports multiple providers including OpenAI, Anthropic, Azure OpenAI, and open-source models via HF or local deployment.

### Can I run this without Docker?
Yes, individual components can be run manually, but Docker is recommended for the full experience and simplified deployment.

### How do I add custom nodes to the flow editor?
Custom nodes can be created by:
1. Creating a new node definition in the frontend
2. Implementing the node's functionality in the backend
3. Registering the node in the node registry

### Is the framework suitable for production use?
Yes, the framework is designed for commercial use with proper error handling, security features, and scalability in mind. It's currently being used in production environments by various businesses.

## Deployment Questions

### What are the minimum system requirements?
- Docker and Docker Compose installed

### Can I deploy this on cloud services?
Yes, the Docker-based architecture makes it suitable for deployment on any cloud provider that supports Docker containers, including AWS, Azure, and GCP.

### How do I scale the system?
The framework can be scaled horizontally by:
1. Running multiple API instances behind a load balancer
2. Scaling the vector database according to your provider's recommendations
3. Utilizing container orchestration tools like Kubernetes for advanced scaling

## Licensing and Commercial Use

### What license is this framework under?
Most of the framework components are proprietary and require a commercial license. However, specific components related to MCP (Model Context Protocol), modules, and tools are available as open source under the MIT License. See the LICENSE file for details.

### What are the pricing models available?
DeepFindAI offers two pricing models:
1. Pay-per-use: Pay only for the compute resources and API calls you use
2. Subscription: Monthly or annual plans with different tiers based on usage requirements

### Do I need to pay for LLM API usage?
Yes, if you're using commercial LLM providers like OpenAI or Anthropic, you'll need to supply your own API keys and pay for usage according to their pricing models. These costs are separate from DeepFindAI's licensing fees.

### Which components are open source?
Only specific components related to the Model Context Protocol (MCP), certain modules, and developer tools are open source under the MIT License. These components are primarily those that enable integration and extension of the core framework.

### Can I customize the framework for my specific needs?
Yes, customization is possible, especially using the open source components. For more extensive customization of proprietary components, enterprise licensing options are available. Contact our sales team for details.

### How do I obtain a commercial license?
You can purchase a license or subscription through our website at https://---.com/pricing or by contacting sales@---.com for enterprise options. 