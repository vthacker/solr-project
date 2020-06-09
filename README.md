# DRAFT
# State of Solr


This document is a commentary of features, improvements and bug fixes grouped into buckets of focus areas. Often times when we're reading the CHANGES entry it's not clear to the casual observer on the motivation of a Jira. 

This document aims to group Jiras by focus areas, adding brief notes on it's usability and where we are heading with this feature. When applicable we'll link blogs and documentation links as well

# Solr Version
1. [Solr 8.6](#solr_86)

## Solr 8.6

1. Cloud Native Initiatives
   - [SOLR-14210](https://issues.apache.org/jira/browse/SOLR-14210) Falls under monitoring as well. If you are running Solr on K8s or have an internal tool to manage restarts, the healthcheck handler with `requireHealthyCores=true` will be useful. One could argue on why it isn't the default
   
1. Monitoring
   - [SOLR-13942](https://issues.apache.org/jira/browse/SOLR-13942) Provides a read API into Solr cluster metadata stored in ZK. TODO: Add an example use-case on why this was needed. Useful for a homegrown monitoring tool?

1. UI
   - [SOLR-14237](https://issues.apache.org/jira/browse/SOLR-14237) Provides a new panel with security info containing the user principal androle for kerberos setups
   
1. Security
   - [SOLR-12131](https://issues.apache.org/jira/browse/SOLR-12131) Add notes. Link to use-cases of JWT? 
   

# Solr Theme Dictionary

Listing down all the possible theme names thast we have. The same theme names could be used to publish a roadmap of what we're working on this year.

1. SolrCloud
   - Cloud Stability
   - Cloud Native Initiatives
1. Security
1. Facets
1. Streaming
1. UI
1. Monitoring
1. Solr Plugin System
1. Developer Productivity
   - Test Reliability
   - Test Speed
1. Hadoop Integration
1. Solr Core
   - Fields, Field Types and Analyzers
   - Configs
   - Updates
   - Searches
   - Boosts, Learn-To-Rank and Re-Ranking
   - Highlighting
   - Spellcheck
   - Grouping, Collapse and Expand
   - Auto-Suggest
   - Terms, Term-Vectors and Stats
   - Spatial Search
   - Vector Search
   - Client APIs
