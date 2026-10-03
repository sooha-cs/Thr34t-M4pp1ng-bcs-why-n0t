## Threat Intelligence & ATT&CK Mapping: Canvas / ShinyHunters Breach (2026)

Independent academic research reconstructing the attack lifecycle of the 2026 Canvas breach and mapping observed attacker behavior to the MITRE ATT&CK framework (v19).       

**Status:** Ongoing, under academic supervision. Findings and full technique-by-technique breakdown are being prepared for potential publication/presentation; this repository will be expanded as the work progresses.        

## Overview        

In July 2026, a breach affecting Canvas (reported to impact 275M+ users) was attributed to the ShinyHunters threat actor group (tracked as G1057 in MITRE’s group catalog). This project reconstructs the attack lifecycle from publicly available incident reports and maps it against the ATT&CK framework to produce an incident-specific technique profile, then compares that profile against ShinyHunters’ broader known TTPs across multiple campaigns.        
   
## Research Questions             
 
- What attacker techniques (per ATT&CK v19) are supported by public evidence in the Canvas breach specifically, versus attributed based on group pattern-matching?       
- How does the incident-specific TTP profile compare to ShinyHunters’ documented behavior across other campaigns (AT&T, ADT, Salesforce/Aura)?      
- Where are the evidentiary gaps in current public attribution?        

## Approach       

- Reviewed public incident reports and disclosures related to the Canvas breach      
- Mapped 9 identified attacker actions to ATT&CK v19 tactics and techniques (e.g., T1190, T1539, T1213, T1567, T1491.001)     
- Built an ATT&CK Navigator heatmap distinguishing incident-specific techniques from the actor’s broader known technique profile      
- Cross-referenced findings against MITRE’s official group tracking for G1057 (ShinyHunters)    
- Performed comparative TTP analysis across related campaigns to assess attribution confidence and identify gaps in public evidence    

## Repository Contents        

```
/navigator        → ATT&CK Navigator heatmap layer (JSON export)
/report           → medium blog link & contact
/sources          → list of references
```
  

## Notes on Sourcing     

All technique mapping is based on **publicly available incident reports and disclosures only**. No non-public or unauthorized information was used in this research.      

## Contact      

For questions about this research or collaboration inquiries, reach out by dropping a DM !      
