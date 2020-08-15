# segmented-sanskrit
Segmented files for sanskrit. These are the input files for the Buddhanexus neural network.

## Sources:

GRETIL Göttingen Register of Electronic Texts in Indian Languages
http://gretil.sub.uni-goettingen.de/gretil.html

The textual corpus used in BuddhaNexus was obtained from the Göttingen Register of Electronic Texts in Indian Languages (GRETIL) for Sanskrit texts. Due to the huge amount of material, some texts from the GRETIL database have been omitted (cumulative pāda indexes and duplicate texts from the same source). Moreover, there has been no attempt by BuddhaNexus to improve the quality of the texts (e.g. removing typos, introducing identical conventions, and the like). Some minor changes have, nonetheless, been made for the sake of standardization.

For the calculation of the Sanskrit matches, a stemming algorithm has been used. This stemming algorithm is accessible as a standalone application.

NOTE: These files contain a lot of errors and need to be cleaned.


NOTE:
Files in segmented_files are those currently used in Buddhanexus. The Buddhist texts jsons are derived via XML conversion of Gretil data (in xml - folder) while the rest is derived directly from HTML to JSON conversion from Gretil HTML. 

The folver segmented_files_buddhist_from_html holds the jsons of the Buddhist texts that are derived directly from HTML to JSON conversion from Gretil HTML
