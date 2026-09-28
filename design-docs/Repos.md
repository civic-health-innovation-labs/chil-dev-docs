# Overview of Repos

## MRIC Documentation

mric-docs: https://github.com/civic-health-innovation-labs/mric-docs 
- Used to store our design documents
- All tech team contribute to the repo

mric-docs-2025: https://github.com/civic-health-innovation-labs/mric-docs-2025
- mric work package 1 plan
- contains all our epics

## Azure TRE Deployment and Documentation

### Documentation
mric-mgt-docs: https://github.com/civic-health-innovation-labs/mric-mgt-docs
- Used for all the documentation related to the Azure TRE(SOPs and other docs)

### Deployment
mric-azure-tre: https://github.com/civic-health-innovation-labs/mric-azure-tre
- The Azure TRE repo
- Used for the TRE deployment
- CI/CD enabled

mric-vm-templates: https://github.com/civic-health-innovation-labs/mric-vm-templates
- Used to define VM templates for the Azure TRE

AzureTRE: https://github.com/civic-health-innovation-labs/AzureTRE
- This is the public AzureTRE repo by microsoft

mric-tre: https://github.com/civic-health-innovation-labs/mric-tre
- To assist the deployment of the Azure TRE project in real world environment
- Not sure this is still relevant, could be archived maybe?

TemplatesVM: https://github.com/civic-health-innovation-labs/TemplatesVM
- For defining VM templates for the Azure TRE
- Public version of the mric-vm-templates

### Data provisioning

mric-tre-data-provisioning: https://github.com/civic-health-innovation-labs/mric-tre-data-provisioning/tree/main/database
- Used to provision data into the TRE
- Haven't been used in a while

## IOTA App Project

mric-mbc: https://github.com/civic-health-innovation-labs/mric-mbc
- IOTA app official repo
- Has lots of security issues/concerns
- Project in collaboration with Dan Joyce


## Mric Pipelines and Infrastructure

### Infrastructure
HeifER: https://github.com/civic-health-innovation-labs/HeifER
- Microservice for provisioning Databricks cluster, Azure Data Factory and Pipeline code management
- Used to setup infrastructure for our mric pipeline

mric-azure-tre: https://github.com/civic-health-innovation-labs/mric-azure-tre
- The Azure TRE repo
- Used for the TRE deployment
- CI/CD enabled



### Pipelines
Pipelines: https://github.com/civic-health-innovation-labs/PipeLINES
- Pipeline templates for mric
- Used to deploy the pipelines after heifer has setup the infrastructure
- Public repo

mric-pipelines: https://github.com/civic-health-innovation-labs/mric-pipelines
- Private version of the Pipelines repo

mric-az-function-ingestion: https://github.com/civic-health-innovation-labs/mric-az-function-ingestion
- Archived
- Azure function to trigger ADF when new file arrives in the landing zone

mric-bak-etl: https://github.com/civic-health-innovation-labs/mric-bak-etl
- For unloading SQL backup files from the landing zone using a VM in the heifer environment.


## OMOP
mric-omop: https://github.com/civic-health-innovation-labs/mric-omop
- Basic omop mapping on synthetic data


## Others
mric-csv-copier: https://github.com/civic-health-innovation-labs/mric-csv-copier
- A simple script used to copy CSV files from on storage account container to another.

ro-crete-metadata: https://github.com/civic-health-innovation-labs/ro-crete-metadata
- this looks like the code for generating an ro-crate file but I can't seem to understand what the repo was created for.





