
![alt text](Files/img.png "Circular Diagram")
# Echinoderm_Regeneration [^1]
 ###### Summer Internship project at the Univeristy of North Carolina at Charlotte.
 
## Overview[^2]

### Sea Cucumber Genome Project
- - Literature Review
- - Fastqc, Trimmomatic, Star and Braker Scripts and Results
- - De novo ABySS assemblage, Exonerate Alignment Scripts and Results 

### [Genome Assembly Convert and Capture (GTF Convert)](https://github.com/sojichld/gtf-convert)
- - Series of scripts that converters and integrates results from different aligners and clusteres (BLAST, exonerate, and CD-HIT) to GTF format file.
#### Annotation
- - Acquisition of Gene Annotations and Alignment against cannonical sequences in model organisms and other Echinoderms.
- - Referenced against uniprot and ncbi


____

## Delta-Notch and Wnt pathways in the context of Drosophila Melanogaster

![alt text](Files/diagram.jpg "Circular Diagram")


_____
### NOTCH
|Domain|blastn|blastp|CDHIT|Exonerate (unfiltered)|
|---|---|---|---|---|
|hairless|10|9|3|47|
|notch1|14|20|8|33|
|adam|17|11|8|59|
|p300|23|21|12|60|
|nack|20|20|8|44|
|modifiers|18|7||70|
|mindbomb|8|4|4|22|
|nack|7|5|5|40|
|hes|6|6|3|17|
|csl|12|8|7|47|
|gammas_secretase|8|8|4|43|

### WNT
|Domain|blastn|blastp|CDHIT|Exonerate (Unfiltered)|
|---|---|---|---|---|
|znrf3 |17|14|6|30|
|wls|22|20|3|18|
|tspan12|5|2|1|19|
|tcf|7|7|3|107|
|sfrp|6|5|1|33|
|sclerostin|14|13|2|25|
|rnf43|9|7|2|29|
|r-spondin|14|10|3|41|
|porcupine|4|4|2|29|
|notum|16|15|6|39|
|norin|8|6|4|7|
|kremen|8|8|4|17|
|lgr5|15|11|6|55|
|gsk3|9|7|3|26|
|groucho|7|7|3|35|
|dishevelled|13|10|2|41|
|geta-catenin|7|4|6|13|
|ck1|18|13|4|49|
|axin|14|10|3|18|
|apc|8|9|4|38|
|frizzled|10|8|3|33|


### Processing 
1. Exonerate, CDHIT and BLAST Outputs converted independently for parsing into multifasta
![alt text](Files/cdhit.jpg "Circular Diagram")
![alt text](Files/exonerate.jpg "Circular Diagram")
2. Multi-GTF Aggregate filtered for nonredundant hits.
![alt text](Files/gtfBlast.jpg "Circular Diagram")
3. NCBI CDD Hits parsed for canonical domains and ascensions.
![alt text](Files/cdd1.jpg "Circular Diagram")

Notes:
[^1]: This is an ongoing repository that will be *archived* in May 2023.
[^2]: WIPs remain unchecked.
