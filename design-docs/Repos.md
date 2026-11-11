# Roadmap to MRIC-DEV/NLP Resources

---- 

## CMI
> cmi is a multi-agent framework to speed up the assessment and decision-making process undergone by clinicians when screening a multitude of EHR records to identify patients eligible to participate in research activities whose objectives are relevant to them.
>
> Main application: Automatically detect patient eligibility to participate in clinical trials.
## Dtd-decoding
> A multi-agent framework to detect behaviours or tendencies consistent with Difficult To Treat Depression from patients EHR records.

## Gen Psychometrics
> Leveraging LLMs and Electronic Health Records to automatically provide structured clinical assessments in mental health.
> Main Application - Automatically populating clinical instruments such as MADRS questionnaires using EHR records.

## Dtd_gen_db
> An app visualising signals of Difficult To Treat Depression. Signals are evidence statements (and severity) showing patterns revealing behavioural tendencies consistent with DTD. 


## cmi-db
> An app retrieving a ranked list of patients after trial cohorting process [cmi](https://github.com/civic-health-innovation-labs/cmi) is complete.

## data_query_engine
> A search and retrieval tool that processes EHR records to answer evidence search related queries such as
> - Is there any evidence or information in the EHR records relevant to a subject, a condition or a specific issue? The search query term can range from a simple phrase to a long passage.
> - Can certain information be derived or inferred from ehr records?
> 
> The search is either via SparkSQL/SQL or a batch LLM inference engine. The inference engine is agentic in nature 
and can be prompted for every note in a dataset (for example "is there evidence of postpartum depression in these
EHR notes?") using a locally hosted LLM (ollama) or in huggingface, and writes one structured, traceable answer
per note to Parquet.

## helpers library
> Repo holds functions/modules that can be repurposed or reusable across various projects.

## GenJERE
> GenJERE pipeline performs Generative Entitiy Extraction (GEE), Generative Relation Extraction (GRE) and Generative Evidence
> Extraction (GEvE).<br>
> - GEE - Extracting of named entities such as conditions, drugs etc that are attributable to patient from a bulk of
> patient EHR records.
> - GRE - Extracting links or interactions between named entities (e.g. conditions) that are contextually relevant and attributable to a patient given
> a bulk of EHR records. 
> - GEvE -  Extracting spans of text that are supportive evidence to extracted entities and relations.  
> 


