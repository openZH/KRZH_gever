<img src="https://github.com/openZH/KRZH_gever/blob/main/kantonsrat_zh_logo.png" alt="Logo des Kantonsrates des Kantons Zürich" width="200"/>
<img src="https://github.com/openZH/KRZH_gever/blob/main/statistisches_amt_kt_zh.png" alt="Logo des Statistischen Amtes des Kantons Zürich" width="180"/>

# KRZH_gever
Dokumentation zur Nutzung des Web Service des Geschäftsverwaltungssystems des Kantonsrates des Kantons Zürich

## Metadaten und Daten
((URL zum OGD Metadatensatz mit Ressourcen))

## Fragen und Antworten
Bitte senden Sie Fragen und Rückmeldungen zu den Schnittstellen per E-Mail an [info@open.zh.ch](mailto:info@open.zh.ch) oder eröffnen Sie ein Issue. 

Hier sammeln wir eingehende Fragen und Rückmeldungen, die für andere Nutzende hilfreich sein können. <br>
Antworten klären wir mit den Parlamentsdiensten des Kantonsrates des Kantons Zürich und mit deren Dienstleistern ab.

**1. Wenn ich einen Endpoint parameterisiere ...** 
```
https://parlzhcdws.cmicloud.ch/parlzh2/cdws/Index/MITGLIEDER/searchdetails?q=seq>0 and dauer_end >= "2020-11-19 00:00:00" and dauer_start <= "2020-11-19 00:00:00" and gremium all KR and funktion any "Mitglied Präsidium Vizepräsidium" sortBy name/sort.ascending vorname/sort.ascending&l=de-CH
```
... dann möchte ich wissen:
- Gibt es noch weitere Felder, mit denen ich die Suche eingrenzen kann?
- Welche Werte kann ich bei `funktion` alles abfragen (sind die 3 angegebenen die einzigen)?
- Was ist `gremium`?
- Was ist `seq`?
- Was bedeutet `dauer_end` und `dauer_start`?
- Ich nehme an `l=de-CH` ist die Sprache, welche Sprachen werden unterstützt? Kann ich so französische Protokolle beziehen oder was heisst das genau?

**2. Gibt es auch `getChanges()`?**

## Dank
Wir danken den Parlamentsdiensten des Kantonsrates des Kantons Zürich sowie allen involvierten Partnern für die Bereitstellung einer offenen Schnittstelle und für die Offenheit mit unserer Unterstützung mit (potenziellen) Nutzenden im Austausch zu sein. <br>
Den Nutzenden danken wir für ihr Interesse, ihre Fragen und Rückmeldungen.

## Kontakt
Kanton Zürich <br>
Direktion der Justiz und des Innern <br>
**Fach- und Koordinationsstelle Open Government Data** <br>
Statistisches Amt <br>

Telefon +41 43 259 75 00 (wochentags, 9-12 / 13-16 Uhr)
[info@open.zh.ch](mailto:info@open.zh.ch)
