# Prefect Use Cases: Getting Started

This repository contains proof-of-concept examples demonstrating various Prefect workflows and use cases. It's designed to help developers understand and implement common patterns with Prefect.

## Repository Structure

```
getting-started/
├── use-cases/                          # Core flow patterns and examples
│   ├── etl/                       # ETL workflow examples
│   │   ├── s3_pipeline/           # AWS S3 ETL example
│   │   ├── snowflake_pipeline/    # Snowflake ETL example
|   |
│   |-- ci/cd
│   │   ├── github_actions/       # Github Actions CI/CD example
│   │   ├── gitlab_ci/             # Gitlab CI/CD example
│   │   ├── azure_pipelines/      # Azure Pipelines CI/CD example
│   │   ├── circle_ci/            # Circle CI CI/CD example
│   │   ├── jenkins/               # Jenkins CI/CD example
│   │
│   ├── ml/                        # Machine Learning workflows
│   │   ├── training/              # Model training flows (Coming Soon)
│   │   └── inference/             # Model inference flows (Coming Soon)
│   │
│   └── api/                       # API-based workflows
│       ├── rest_api/              # REST API integration examples (Coming Soon)
│       └── graphql/               # GraphQL integration examples (Coming Soon)
│
├── deployments/                    # Deployment examples and patterns
│   ├── kubernetes/                 # K8s deployment examples
│   ├── docker/                     # Docker deployment patterns
│   └── serverless/                 # Serverless deployment examples
│
├── advanced-features/             # Reusable advanced features
│   ├── notifications/             # Notification task patterns
│   ├── validation/                # Data validation tasks
│   └── automation/                # Automation tasks
│   └── terraform/                 # Terraform tasks
│
└── Basics/                        # Documentation
    ├── getting_started/           # Basic Getting Started Guide
    ├── best_practices/            # Best practices documentation
```

## Prerequisites

- `uv` package manager
- Prefect Cloud account

## Available Examples

### 1. ETL Workflows
[View ETL Pipeline Documentation](etl/etl-s3-pipeline/README.md)
- **S3 Pipeline**: Complete ETL workflow with AWS S3
- **Snowflake Pipeline**: Data warehouse ETL patterns
- **Postgres Pipeline**: Database ETL examples

### 2. Deployment Patterns
- **Kubernetes**: K8s deployment examples
- **Docker**: Containerized flow deployments
- **Serverless**: Serverless deployment patterns




## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/getting-started.git
   cd getting-started
   ```

2. Set up Python environment:
   ```bash
   # Install uv if not already installed
   pip install uv

   # Create and activate virtual environment
   uv venv
   source .venv/bin/activate  # On Unix/macOS
   # or
   .venv\Scripts\activate     # On Windows
   ```

3. Choose an example to explore:
   - Navigate to the relevant directory (e.g., `cd flows/etl/s3_pipeline`)
   - Follow the example-specific README for detailed setup and usage

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request


