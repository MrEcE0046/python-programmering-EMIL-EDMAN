## Lab 3

# Funktioner
Programmet läser filen "unlabelled_data.csv" i funktionen readfile() som ligger i map "lab3" och sparar datan i en lista (data). 

Listan delas upp i par (x, y) där x körs igenom y=kx+m ekvationen med fasta k, m-värden för att beräkna y.  
Om listans y-värde i paret överstiger beräknat y-värde får det paret en label om 0. Motsvarande händer om y understiger beräknat y, då paret får en label om 1. 
För varje iteration appendas resultatet i en lista (data_label) som därefter skrivs i en ny csv fil. Filen består nu av tre element (x,y,label) 

Funktionen plott() inleds med att ta fram en linje genom att köra en lista med x-värden igenom y=kx+m med fasta k,m för att räkna ut y. x,y plottas för att få fram linjen.

Label_data listan delas upp till två listor beronde på vilken label (0/1) som plottas genom en scatterplot. 

# Instruktioner
Programmet kör läsning, klassifiering, skrivning av fil och plot vid start. 
Om man vill påverka linjen kan man ändra k för vinkeln och m för skärningspunkten i y-axeln. 

mvh
Dev



