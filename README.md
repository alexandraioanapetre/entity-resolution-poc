Entity Resolution & Data Quality – POC 

This repository contains my work for the Entity Resolution & Data Quality Proof of Concept.

The goal of this POC was to:
- Resolve supplier entities from a inconsistent dataset
- Identify inconsistencies, duplicates, and data issues
- Summarize findings and propose a curation strategy
- Present the results in a client‑ready format


📌 1. Entity Resolution

Each supplier entry was processed through an entity resolution engine, returning up to 5 candidate matches.  
My task was to:
- Select the best match for each input  
- Leave unmatched rows when no candidate was correct  
- Ensure every real-world company was correctly identified


📌 2. Data Analysis & Quality Control

After selecting the correct entities, I reviewed all returned attributes and documented issues such as:
- Irrelevant matches 
- Industry inconsistencies
- Duplicate entities for the same company
- Encoding problems
- Invalid geographic coordinates
- Suspicious or unofficial domains

I also outlined a curation strategy to deliver a clean, reliable dataset to the client.


📌 3. Deliverables

 **📄 Veridion – Data Analysis & QC Report (PDF)**  
A structured, client-ready report summarizing:
- Entity resolution decisions  
- Data quality findings  
- Recommended cleaning steps  
- Final curated dataset logic  

**📊 presales_data_final.csv**  
The processed dataset used for the POC.

 📌 4. Summary

This POC demonstrates:
- Analytical thinking in entity resolution  
- Ability to identify and articulate data quality issues  
- Clear communication of findings in a polished, professional format  
- Understanding of procurement data challenges in a digitalization context  


 📌 5. Author

**Caramaliu Ioana Alexandra**  
Data Analysis & Entity Resolution – POC Simulation  
