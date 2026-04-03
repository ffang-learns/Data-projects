# Data-projects
Data projects to learn SQL/ Python to do useful things

**Project 1:** Medicare Data_Medicare_Claims_Errors

The objective of this analysis was to identify the types of providers that struggle the most with filing claims and what Healthtech providers in the claims and practice management industries should prioritize to resolve provider pain points. The notebook file contains the SQL and Python code used to conduct the analysis.

Results: 

1. The provider types with the highest claims decline rates from Medicare are Orthotic Medical Suppliers, Skilled Nursing Facilities, General Practice, Nephrology, and Pulmonary Disease providers.

2. 19% of General Practice errors are due to documentation issues - **Recommendation:** Build documentation tools for General Practice doctors (e.g. voice dictation/ transcription from patient consultations that generates documentation about the session, including time stamps. Prompts when doctors are missing pieces required for treatment plans, signatures, etc. Workflow integration with the billing process to ensure documentation is attached every time). After building a sufficient solution for general practice, other verticals similarly struggle with documentation issues (11% Orthotic Medical Supplies, 7% SNF, 10% Nephrology, 8% Pulmonary Disease)    

3. 14% of Nephrology and 15% Pulmonary disease are denied due to incorrect coding - **Recommendation:** AI assisted coding can help reduce human error and accurately tag procedures to the codes that each insurer considers to be appropriate. Healthtech players who provide coding automation should focus on these industries. Additional data needed to identify specific codes that cause these errors.
