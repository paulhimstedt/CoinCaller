# CoinCaller
Dies ist eine App um Krypto-bezogene Tweets mittels eines QA-Systems, sowie einer Sentiment Analysis zu durchsuchen um ein breiteres Verständnis im Bereich Krypto zu generieren.

Die Anwendung Coincaller läuft über die Plattform GoogleColab. Dazu muss der letzte Release im Master Branch angeklickt werden und über den Knopf "Open In Colab" in Colab geöffnet werden.

Befindent man sich nun im Notebook empfiehlt es Sich die Laufzeit neu zu starten und alle Zellen auszuführen.

Allgemein ist darauf zu achten, dass an nur an einer Stelle im Code eine Nutzereingabe von 3 unterschiedlichen Feldern zu tätigen ist. 
  - Die Frage im Bereich der Kryptowährungen (Im idealfall 2 bis 4 wörter Query, möglichtst prägnant)
  - Den Begriff den man auf Twitter auf Sentiment untersuchen möchte (Vorschlag wird aus Frage generiert)
  - Die Anzahl an zu durchsuchenden Tweets

Diese Eingabe wird direkt am Anfang mit dem Ausführung der ersten Zelle Code aufgerufen.

Bei der Ausführung des Codes ist ebenfalls darauf zu achten, dass es eventuell nötig ist einen Neustart der Imports durchzuführen, da diese ab und an in Kombination mit Elasticsearch einen Error geworfen haben.

Die Ausgabe der Ergebnisse des CoinCallers ist ganz am Ende des Notebooks zu finden.
  -Vorletzte Ausgabe: Ergebnisse der Suche
  -Letzte Ausgabe: Tortendiagramm mit Stimmungsbild
