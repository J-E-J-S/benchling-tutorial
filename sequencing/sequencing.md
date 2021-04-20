## Sequencing  

### Objectives
* Use the auto annotate tool to identify plasmid features.  
* Identify Source BioScience stock primer sites by importing the feature library.  
* Learn about version control.    
* Determine the sequence fidelity of the construct against the trace.  

### Steps:  
1. Import the pMmpylT.gb file  
2. Click 'Annotations' (right hand vertical toolbar)
    a) Click 'Auto annotate' button to identify plasmid features by searching all libraries  
3. Create a new feature library by clicking on 'Edit feature libraries' within the Annotations tab  
    a) Click Import CSV  
    b) Upload the source_bioscience_primers.csv file  
    c) Auto annotate plasmid with new feature library to identify sequencing sites  
4. Take a moment to review Benchling's version control system  
    a) Click on the 'History' tab (right hand vertical toolbar)  
    b) Update the current version to 'Fully Annotated pMmPylT'  
5. Create sequencing primers for the whole plasmid  
    a) Click on the 'Primers' tab (right hand vertical toolbar)  
    b) Click 'CREATE PRIMERS' and follow to the Wizard  
    c) Select the whole plasmid from the linear map and use it as the selection region
    d) Check the primer properties are suitable for sequencing specification  
    e) Use a 500bp Spacing with a 20bp Lead, generated 13 results for full coverage  
    f) Click 'Generate Primers'  
6. Analyse sequencing traces  
    a) Click 'Alignments' (right hand vertical toolbar)  
    b) Select 'CREATE NEW ALIGNMENT'  
    c) Upload the .ab1 trace files with the 'CHOOSE FILE(S)' button  
    d) Select the MAFFT Algorithm and proceed to create alignment   
    e) Use the visualizer to identify any conflicts (Tip: There is a conflict)  
