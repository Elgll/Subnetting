# Subnetting
2 sottoreti

Obiettivo: utilizzare le regole di subnetting per creare due sottoreti della stessa dimensione a partire dall'immagine allegata il cu.i indirizzo ip si...
presenta 192.168.0.0/24:
-indirizzo ip 192.168.0.0
-subnetmask 255.255.255.0

Conoscenze teoriche:
il subnetting si usa per migliorare il traffico in rete (moolto utile per le grandi aziende) e permette di dividere una rete, portando via all'hostID un certo numero di bit, di divedere una rete in più reti che comnunicano tra loro con lo stesso ip. Come prima cosa bisogna calcolare quali valori dell'inidirizzo ip fornito e per fare questo si dovrà dividere il numero maggiore che potrà assumere l'hostID per il numero di sottoreti che si volgiono realizzare. La cosa importante di cui bisogna tenere conto sarà il primo e l'ultimo indirizzo ip sia della rete che delle subnet che sarannno rispettivamente identificativi e di broadcast. A questo punto si passa a definire la subnet mask ossia che sarebbe quell'insieme molto simile agli indirizzi ip per struttura, ma i valori che possono assumere i suoi bit sono limitati. 
I valori che possono essere assunti dalla subnet mask dipendono dalle classi (se cono presenti gl indirizzi si dicono classfull, altrimenti classless).
Le classi di indirizzi ip sono delle convenzioni che dipendono da come quegli indrizzi vengono utilizzati, in base ad esse può variare la struttura degli indirizzi stessi (in quanto a HOST e NET ID), di conseguenza anche la subnet mask relativa.

Procedimento:
Come prima cosa si definisce il numero di sottoreti desiderate (in questo caso 2) per poi dividere il numero massimo di dispositivi disponibili (256) per quel numero (256/2 = 128). Grazie a questa suddivisione possiamo dedurre che le combinazioni di indirizz
