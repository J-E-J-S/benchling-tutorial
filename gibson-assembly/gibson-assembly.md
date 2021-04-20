## Gibson Assembly  

### Objective  
Assemble the part BBa_E0240 into the pDusk backbone  

### Steps:  
1. Import the BBa_E0240 and pDusk Genbank files (.gb)  
2. Click 'ASSEMBLY WIZARD' (bottom horizontal toolbar)  
3. Create a new Gibson Assembly, Title pDusk-BBa_E0240   
4. Select Backbone between outer and inner sequences of the pFixK2 and lacIq promoter sequences, invert selection  
5. Add a 40bp Spacer before and after the insertion site of BBa_E0240 by clicking on the insert and selecting 'Add Spacer After'  
    a) Position Spacer before Insert by using arrows to move left  
    b) Name Spacer, set sequence to random 40bp from http://www.faculty.ucr.edu/~mmaduro/random.htm (or add intragenic features e.g. primers, cut sites etc)  
6. Select Insert by navigating to the BBa_E0240 tab  
    a) Select the whole component and Set Fragment from selection  
7. Add another spacer as per Step 5  
8. Click 'Assemble' and select output repositories to current folder  
9. Go to new construct and edit the primers as needed  
    a) Check for annealing length (~20bp)  
    b) Check for Tm (aim for 60c)  
    c) Check for G/C clamp on 3'  
10. Benchling will generate all the primers, export to .csv to order  
