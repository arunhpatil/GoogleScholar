# GoogleScholar
Revised GoogleScholar-API from fredrike

Simple API that parses information from https://scholar.google.se/citations. The sorce code was originally forked from <a href="https://github.com/fredrike/googlescholar-api" target="_blank">Fredrike</a>. The code was further modified to produce an interactive line chart summarizing the citations per year and a table displaying h-index and i10-index of the user.  

<strong>USAGE:</strong>
It is very simple, follow the steps: 
1. In the GoogleScholar.php, at line 33, change the scholar ID specifically to yours. i.e., replace qubfVSkAAAAJ. 
2. create a simple PHP page of your own, say for example "publications.php"; 
3. Call this GoogleScholar by include function: \<\?php include "GoogleScholar.php" \?\>
4. You can change the display dimentions according to your page settings

Example: <a href="http://www.inhouseprotocols.com/publications.php" target="_blank">qubfVSkAAAAJ</a>

Acknowledgements: 	I thank <a href="https://github.com/shashankgk" target="_blank">Mr. Shashanka G. Koyangana</a>, for his inputs and revisions.
