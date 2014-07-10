sdn-survey
==========

Piccola indagine su cosa siano le reti SDN ed il protocollo OpenFlow ed illustrazione di problemi legati alla sicurezza di questa nuova architettura di rete. Questo sondaggio non vuole essere minimamente esaustivo in merito all'argomento ed introduce problematiche e soluzioni in uso al momento della scrittura del documento.


==========
Infomrmazioni di compilazione del documento
Il documento è scritto interamente utilizzando latex. Per poter ottenere una copia in formato PDF posizionarsi, con la shell all'interno della cartella che contiene il file ''MasterDocument.tex'' e lanciare i seguenti comandi:

1) pdflatex MasterDocument		-> Questo comando genererà una prima versione del documento e si accorgerà della mancanza dei riferimenti
2) bibtex MasterDocument		-> Questo comando genererà il database delle referenze
3) pdflatex MasterDocument		-> Questo comando rigenera il documento collegando le referenze
4) pdflatex MasterDocument		-> Questo comando rigenera il documento per referenze incrociate