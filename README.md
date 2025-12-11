**Ziel der Arbeit**



1. Klassenentwurf — Begriffe, Prinzipien und praktische Anwendung (Kopplung, Kohäsion, Refactoring, Verantwortlichkeiten).

2. Analyse & Refactoring — "Die Welt von Zuul" — Identifikation von Schwachstellen (Kopplung/Kohäsion) und konkrete Verbesserungen in der Klasse Spiel (Methoden willkommenstextAusgeben, wechsleRaum) und der Klasse Raum (Datenfeld HashMap<String, Raum> ausgaenge).

3. Designprinzipien — SOLID im Detail + mindestens 3 weitere OOD-Prinzipien (z. B. DRY, KISS, YAGNI).

**Aufgabe 1 — BLUEJ-BUCH: Klassenentwurf**

Verantwortlichkeiten: Jede Klasse soll genau einen Zweck erfüllen.

Kopplung: Beschreibt, wie stark Klassen voneinander abhängig sind. Ziel: geringe Kopplung. Maßnahmen: Abstraktionen nutzen (Interfaces, Map statt HashMap), Felder kapseln.

Kohäsion: Wie gut Methoden und Felder einer Klasse thematisch zusammenpassen. Ziel: hohe Kohäsion. Maßnahmen: Klassen aufteilen, wenn sie zu viele unterschiedliche Aufgaben erfüllen.

Refactoring: Code schrittweise verbessern, ohne Verhalten zu ändern. Vorgehen: verstehen → kleine Schritte → testen → dokumentieren.
