# Capability-Centric Cloud Service Discovery Model (Event-B)

This repository contains the formal Event-B specification and refinement-based model of a **capability-centric cloud service discovery system**. 
The model supports the semantic representation and reasoning over cloud service capabilities.
## 📘 Overview

The model is structured as a hierarchy of Event-B machines and contexts, built upon a Capability Model defined in a reusable and domain-agnostic way. It enables:

- Formal specification of the capability model 
- Verification of the consistency of  `specifies` and `variantOf` relations
- Verification of the partial ordering of these reltions (e.g., transitivity, irreflexivity)
- Formal specification and verification of a Directed Acyclic Graph(DAG)-based service architecture

## 📁 Structure

- `C0/`: Core context definitions for property values, capability structure.
  
## 🧪 Validation

The model has been validated using the **Rodin Platform**. All proof obligations have been discharged.

 
## 🔗 Reference

 
