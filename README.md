# Automatisierte-Emotionsannotation-mit-GPT4
Automatisierte Emotionsannotation im ChildTale-A Corpus mit GPT-4 im Rahmen des Seminars [Annotation mit Sprachmodellen]( https://lehre.idh.uni-koeln.de/lehrveranstaltungen/wintersemester-2023-2024/sprachmodelle-1/) im WS 23/24 der Universität zu Köln.


## Annotationsaufgabe
Die Hauptaufgabe besteht darin, emotionale Inhalte in den Märchentexten automatisch zu annotieren.

## Datenbasis
Der ChildTale-A Datensatz[^1] ist eine Sammlung von Märchentexten aus den "Kinder- und Hausmärchen" der Brüder Grimm. Dieser Datensatz wurde speziell für die Untersuchung und Analyse von Emotionen in Texten zusammengestellt. 
Er umfasst über 5.000 manuell annotierte Sätze, in denen die emotionalen Inhalte der Märchen detailliert erfasst sind. Die Annotationen beinhalten Aspekte wie emotionale Valenz(Skala -3 bis +3) und Arousal(Skala 1 bis 5), wobei jeder Satz hinsichtlich des Ausmaßes und der Art der darin ausgedrückten Emotionen bewertet wurde.

- **Textsorte:** Märchen
- **Sprache:** Deutsch
- **Quelle:** ChildTale-A Corpus, verfügbar auf [Zenodo](https://zenodo.org/records/7737329).

[^1]: Lüdtke, J., & Herrmann, B. J. (2023). childTale-A: A corpus of eighty fairy tales from the 7th edition by the Brothers Grimm, manually annotated for textually encoded emotions (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.7737329


## Sprachmodell / Interface
- **Modell:** GPT-4 über die von OpenAI bereitgestellte API

## Experimentdesign
Das Projekt umfasst die Nutzung von GPT-4 zur Annotation der einzelnen Märchentexte aus dem *ChildTale-A* Datensatz. 
Die Ergebnisse werden auf Genauigkeit, Konsistenz und Übereinstimmung mit dem Goldstandard der manuellen Annotationen hin überprüft. Zusätzlich wird die Fähigkeit des Modells analysiert, emotionale Nuancen und subtile Ausdrücke zu erfassen. Außerdem soll bei der Evaluation zwischen der Performanz von *Zero-Shot Prompting* und *Few-Shot Prompting* unterschieden werden.

## Beispiel
Basierend auf der Annotationsrichtlinie des Datensatzes, könnte eine Annotation für einen Satz zum Beispiel wie folgt aussehen:

| **Textauszug** | **Kategorie** | **Annotation** |
| --- | --- | --- |
| Die Frau hatte zwei Töchter mit ins Haus gebracht, die schön und weiß von Angesicht waren, aber garstig und schwarz von Herzen. | Valenz | -2 (Negativ) <br> *Begründung:* Negatives inneres Wesen der Figuren. |
|  | Arousal | 2 (Etwas ruhig) <br> *Begründung:* Beschreibend, ruhig, ohne direkte emotionale Erregung. |
|  | Emotions-zuschreibung | Wem: Den Stiefschwestern; <br> Wer: Die Erzählinstanz |
|  | AnnotatorIn Kürzel | S.M. (Sprachmodell) |



