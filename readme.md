# Introduction

This repository contains the schemas and semantic models developed for the [Energy and Buildings](https://www.sciencedirect.com/journal/energy-and-buildings) paper "A semantic approach to portable data-driven Model Predictive Control systems design".

# Folder structure

## `OpenAPI`
Contains the OpenAPI specification of each modular service in the MPC System.  

## `ttl/metadata_schemes/new_schemes`
Contains the reused and proposed schemas for, MPC (mpc_schema.ttl), Forecasting Algorithm (forecast_schema.ttl), and Smart Building Algorithm Schema (sba-schema.ttl).  

## `ttl/metadata_schemes/extensions`
Contains the extensions to the existing ontologies. Brick ontology extension for ev related concepts (brick-ev.ttl), Ref ontology extensions for timeseries reference extensions (ref-ext), and PEP ontology extensions for extended procedures (pep-ext).

## `ttl/metadata_schemes/algoritms`
Contains the metadata schemes developed for particular algorithms related to modular services of the MPC System.

## `ttl/building1`
Contains the semantic graphs of the original building that was used for testing the MPC System. 

## `ttl/building2`
Contains the semantic graphs of the virtual building that was used for testing semantic-driven portability service. 

# Demonstration

demo.ipynb notebook demonstrates the usage of metadata schemes.
