Liebe Stephanie,

ich habe dir einfach den gesamten "Projektordner" geschickt. "./WD_Visionen2023_Befragung_Textanalyse/"
".../data/":
Dort findest du die Daten, mit denen ich die Topics
modelliert habe (nachdem ich sie aus dem Wiki herausgepopelt und in Form gebracht habe). 
".../images/":
Außerdem sind dort auch die meisten Visualisierungen drin. Ein Balkendiagramm, dass anzeigt, wie viele "documents"
einem Topic zugeordnet sind, habe ich auch exportiert. 
Eine andere Visualisierung ist nur für die "Ellenbogenmethode" (kann ich bei Bedarf gerne später nochmal erklären).
Fancy sind die HTML-Dateien, die ich mit "pyLDAvis" habe erstellen lassen. Damit lassen sich Topics interaktiv 
explorieren.
Wortwolken habe ich auch gebaut, aber da sollte man mglw. nochmal etwas Schliff in die Formatierung bringen.
".../data_processed_results/":
Auch wenn Bilder toll sind, über die Tabellen freue ich mich am meisten. Alle drei sind gleich strukturiert.
Hier die Spaltenbezeichnungen:
"docnum" = interne, vorläufige ID für jeden Gästebucheintrag|  im Grunde eine Indexnummer
"topicnum" = die Nummer des Topics, die LDA einem Topic zugewiesen hat
"text" = der Text des Gästebucheintrags
"TopicLabel" = ein menschensprachliches Label, das ich vergeben habe auf Grundlage der Wortliste der Topics.
     (Du wirst merken, dass ich mir dafür nicht viel Zeit genommen habe.)

Das heißt: Ich habe jeden Gästebucheintrag tabellarisch erfasst und eine Indexnummer drangeschrieben. Nachdem
Modellieren der Topics habe ich für jeden Gästebucheintrag die dominanten Topics ermitteln lassen und das
auch in die Tabelle geschrieben. Die Daten lassen sich nun also nach Topics filtern.

Lieben Gruß
Konstantin



