# Projekt zur Vorlesung Big Data Analytics

Auf Basis der Daten von www.tankerkoenig.de werden Kraftstoffpreise ausgewertet.

Live-Daten werden von der Tankerkönig API in Apache Kafka als Buffer geschrieben und anschließend in MongoDB eingepflegt.
Außerdem werden die historischen Daten (als CSV) direkt in MongoDB importiert.

Aus MongoDB heraus werden die Daten dann mit matplotlib analysiert.
