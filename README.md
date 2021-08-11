# SEDR-Internals

This is a place where I put everything related to my research on Symantec EDR Internals. Currently it contains the following:

* **[SEDR_Enrichment_Rules](https://github.com/nasbench/SEDR-Internals/blob/main/SEDR_Enrichment_Rules.txt)** : A list of Symantec EDR data enrichment rules with a short description for each.

* **[Symantec_Heuristics_Sig](https://github.com/nasbench/SEDR-Internals/blob/main/Symantec_Heuristics_Sig.txt)** : A list of Symantec EDR heuristics signatures with a description for each. Plus an inclusion of the corresponding "threat.id" value for usage with Symantec EDR (SEDR) search queries.

* **[Symantec_SONAR_Sig](https://github.com/nasbench/SEDR-Internals/blob/main/Symantec_SONAR_Sig.txt)** : A list of Symantec SONAR signatures with a description of each signature. Plus an inclusion of the corresponding "bash.virus_id" value for usage with Symantec EDR (SEDR) search queries.

* **[SEDR_ATP_Rules_Regex](https://github.com/nasbench/SEDR-Internals/blob/main/SEDR_ATP_Rules_Regex.txt)** : File that contains some example regular expressions used by SEDR to detect and enrich events.


### Blog
I wrote a couple of blog posts describing different component of SEDR which you can find here:

* **[Symantec EDR Internals — Criterion](https://nasbench.medium.com/symantec-edr-internals-criterion-fa49be4e21af)**
* **[Symantec EDR Internals — Event Enrichment Rules (Part I)](https://nasbench.medium.com/symantec-edr-internals-event-enrichment-rules-part-i-b5e4340041a7)**
* **[Forensic Artifacts — Symantec EDR “localdatastore” Folder](https://nasbench.medium.com/forensics-artifacts-symantec-edr-localdatastore-folder-9bff91d2876d)**
* **[Forensic Artifacts — Parsing Symantec EDR “localdatastore” LevelDB Files](https://nasbench.medium.com/forensics-artifacts-parsing-symantec-edr-localdatastore-leveldb-files-86f5c75736d5)**

### Tools
These are some tools I wrote that can help you understand the internals of SEDR and how it works:

* **[sedr-localdatastore-parser](https://github.com/nasbench/sedr-localdatastore-parser)**
