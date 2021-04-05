# SMARTPHONE CHARGER
Gestione automatica della ricarica notturna di uno smartphone

**RICHIESTE del Progetto:**
* Gestione del tutto il più possibile pronta e stand alone, con meno interventi possibili dell'utilizzatore sui file YAML.
* Utilizzo dei commenti per facilitare interventi e correzioni da chiunque voglia partecipare.
* L'obiettivo è salvaguardare la batteria nel tempo, evitando quindi che la percentuale scenda sotto il 20% e superi il 90%.

# **DESCRIZIONE DEL FUNZIONAMENTO RICHIESTO**
Il telefono necessita di ricarica se scende al di sotto del 20%, con inizio della ricarica in orario notturno (ipoteticamente tra le 00:00 e le 7:00 del mattino), e obiettivo di ricarica completata a scelta dell'utilizzatore.
Fondamentale che il sistema sia in grado autonomamente di capire quando attivarsi, una volta confermata la presenza del dispositivo nelle condizioni richieste. 
Non si vuole regolare accensioni e spegnimenti fissi, ma creare una gestione della ricarica totalmente autonoma.
Se il dispositivo non è in posizione di ricarica (non connesso alla fonte di alimentazione, o non presente fisicamente in carica), il sistema non deve ovviamente avviarsi inutilmente.

**_ESEMPIO:_**
Smartphone collegato dalla presa smart (ovviamente spenta), quando si va a dormire...indipendentemente dalla percentuale della batteria, e al risveglio la mattina seguente troveremo il dispositivo sempre ad una percentuale di batteria residua superiore al valore stabilito a monte.
Sarà il sistema a decidere se accendere la presa e quindi iniziare la ricarica, e quando interrompere per ottenere il risultato richiesto.
