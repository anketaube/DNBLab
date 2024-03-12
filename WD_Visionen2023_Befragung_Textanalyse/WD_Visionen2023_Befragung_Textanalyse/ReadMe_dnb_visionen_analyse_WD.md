# DNB VISIONEN WD-Analyse ReadMe

In diesem Ordner finden Sie die Resultate der NLP-Auswertung der Befragung "DNB Visionen 2070". Die _Rohdaten_ wurden aus dem DNB-Wiki in TXT-Dateien überführt und anschließend mit Python verarbeitet.
Ein individueller Eintrag in der Befragung wird im Folgendenden _Dokument_ genannt.
Die Textdaten wurden von _Stopwords_ bereinigt und _lemmatisiert_. Anschließend wurden mittels _LDA_ latente Topics ermittelt. Für jedes Topic wurden _Labels_ vergeben und diese Labels in die Ausgangsdaten zurückgespeist. Jedem Eintrag in der Befragung ist ein Topic inkl. Label zugeordnet. Die Ergebnisse dieses Schrittes sind in einer CSV-Tabelle gespeichert, die zur Kontrolle der Topics konsultiert werden sollte.
Diese Resultate wurden auf zwei Wegen visualisiert. _LDAVis_ generiert auf Grundlage der ermittelten Topics eine interaktive HTML-Grafik, in der Topics exploriert werden können. Außerdem wurden die Dokumenthäufigkeiten pro Topics als Balkendiagram visualisiert.
Außerdem wurden Wordhäufigkeiten ermittelt, in einer TXT-Datei gespeichert und als Wortwolken visualisiert.

Dieser Prozess wurde dreimal durchgeführt: einmal für die Umfrage DNB-L, einmal für die Umfrage DNB-F und ein letztes Mal für die kombinierten Umfrageantworten.

## Einschränkungen

Aufgrund der relativ geringen Datenmengen kann es sein, dass die Aussagekraft des LDA-Topic Modelling recht begrenzt ist. Entsprechend wichtig ist eine intellektuelle Prüfung der Ergebnisse in der CSV-Tabelle, die zu diesem Zweck bereitgestellt wurde (vgl.s.o.). 

## Ordnerstruktur

**data** enthält die Ausgangsdaten: dnbl_visionen23.txt, dnbf_visionen23.txt, dnb_all_visionen23.txt
**data_processed_results** enthalt angereicherte Daten. Topicnummer und -Label und der Text der Antworten sind tabellarisch erfasst.
**images** enthält Wortwolken, Balkendiagramme und LDAVis-HTML

## Bei Fragen WD fragen

Wenn Sie die Jupyter-Notebooks zugeschickt haben möchten, mit denen diese Auswertung durchgeführt wurde, oder wenn sie Layout-Anpassungen in den SVG-Grafiken wünschen, wenden Sie sich bitte an Konstantin Freybe vom Wissenschaftlichen Dienst der DNB:

MAIL: k.freybe@dnb.de
FON: +49 341 2271 418