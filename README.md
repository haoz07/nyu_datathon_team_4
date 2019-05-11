# NYU Langone Datathon Team 4
## Main Question: Sedation Requirements in the Medical ICU Mechanically Ventilated Obese Patients
### Background
 - 40% (100m) people in the US are obese
 - Obese patioents have increased adipose tissues, lean mass, cariac output
 - Current sedation and analgesia guidelines in the critically ill recommend several lipophilic drugs
    - Propofol
    - Dexmedetomidine
    - Fentanyl
    - Hydromorphone
 - No standard dosing recommendations are available for obese patients
 - Potentially increasing accumulation and saturation of deep tissue
  - Can lead to longer time to elimination after infusion is terminated as the drug distributes back in the central compartment
    - Does this translate into longer time to awakening?
  - When dosed based on actual body weight more drug may accumulate in the deep tissue
    - Potentially leading to heavier sedation, lower requirements of sedation, and quicker time to achieve goal RASS, more adverse drug reactions
### Cohort selection
Final cohort size n = 463
MIMIC-III database  
Inclusion criteria:
  -  Age>18
  -  Patients who were intubated for >24 hours   

Exclusion criteria
  -  Midazolam continuous infusion
  -  CVA
  -  Patients with incomplete height and weight data
  -  Patients with recent cardiac arrest 
  -  Metavision only
  
  ### Conclusions and Future Directions
   - Development and validation of ML tools to predict RASS
   - Continue to work on data extraction from other large databases to continue work on original question
      - Broader sample to study sedation in the obese
      - Examine adverse drug reactions related to sedation in the obese population
