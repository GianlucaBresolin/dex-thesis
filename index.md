# DexThesis

<!-- INTRODUCTION -->
## 1. Introduction
### Inkwell Data
### Context and Motivation
### Problem Statement and Objectives
### Thesis Structure

<!-- BACKGROUND -->
## 2. Background
### Data Exploration
<!-- How data exploration is made usually. Current situation to face client requests. -->
### Distributed Data Systems
<!-- Explain current situation, high loads leads to distribution, but distribution
inevitally comes with this. -->
### Heterogeneous Data Sources
<!-- Not only distributed, but potentially different technologies to suite specific 
requirements. -->
### Data Abstraction and Governance
<!-- Tech people okay, but non tech? 
Data governance, especially today with AI and increasingly smart city etc, is a more relavant
value comes from data for a lot of companies. 
+ agostic schema query advantages / avoid leakeages-->
### Federate Query Processing
<!-- Consequences of distributed processing: we require aggregation -->
### Existing Solutions
<!-- Comparision with other technologies. -->

<!-- REQUIREMENTS -->
## 3. Requirements and Design Goals
### Functional Requirements
### Quality Requirements
### Constraints Requirements

<!-- ARCHITECTURE -->
## 4. DEX Architecture
### System Overview
### Hexagonal Architecture
<!-- hexagonal -->
#### Core
#### Ports
#### Adapters
<!-- hexagonal -->
### Distributed Execution
### Fault Tolerance
### Microservice Principles in the BEAM

<!-- IMPLEMENTATION -->
## 5. Implementation
### Technology Stack
<!-- tech stack -->
#### Beam / OTP
#### Elixir
#### Phoenix
#### Ecto
#### Horde
#### Riak
#### DuckDB
#### Z3
#### React
<!-- tech stack -->
### Query Processing
### Data Source Integration
### Persistence
### Configuration
### User Interface Integration
<!-- UI -->
#### Query Construction
#### Query Execution
#### Result Visualization
<!-- UI -->
### Fault Tolerance

<!-- EVALUATION -->
## 6. Evaluation
### Experimental Setup
### Performance Evaluation
### Scalability Evaluation
### Result Discussion

<!-- CONCLUSION AND FUTURE WORK -->
## 7. Conclusion
### Main Contributions
### Limitations
### Future Work