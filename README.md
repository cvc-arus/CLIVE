# CLIVE - Clearview's In House AI Platform

## Overview

CLIVE is a on-premises AI platform designed  for knowledge management, tender analysis, bid writing and document generation.

## Arhitecture Principles
 - **Open Source First**: Prefer open-source solutions for all infrastructure components
 - **Docker First**: All services containerized for consistency and reproductibility
 - **API First**: All functionality exposed through well-documented API
 - **Self Hosted**: Complete control over data and infrastructure
 - **Infrastructure as Code**: All infrastructure defined in version-controlled code
 - **Modular Design**: Loosely coupled services for maintainability and scaling


## Quick Start

*Documentation in progress - see /docs directory*


---

##Project Strucure


```mermaid
flowchart TB
    A["📁 clive/"]

    A --> B["📁 docs/ <br/>Project documentation"]
    A --> C["📁 src/"]
    A --> D["📁 infrastructure/ <br/>Infrastructure as Code"]
    A --> E["📁 docker/ <br/>Docker configurations"]
    A --> F["📁 scripts/ <br/>Utility scripts"]
    A --> G["📁 tests/ <br/>Test suites"]

    C --> C1["📁 api/ <br/>API gateway & routing"]
    C --> C2["📁 core/ <br/>Core business logic"]
    C --> C3["📁 services/ <br/>Microservices (RAG, tender, bid, etc.)"]
    C --> C4["📁 models/ <br/>Data models & schemas"]
    C --> C5["📁 utils/ <br/>Shared utilities"]
    C --> C6["📁 workers/ <br/>Background task workers"]
```

## License

Proprietary - CVC Internal Use Only
EOF

