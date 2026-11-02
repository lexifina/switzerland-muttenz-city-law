# Muttenz (city): law history in git

The municipal law of the municipality of Muttenz (Gemeinde Muttenz, canton of Basel-Landschaft, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Basel-Landschaft is in [lexifina/switzerland-basel-landschaft-law](https://github.com/lexifina/switzerland-basel-landschaft-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

51 acts with 53 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 1 | one version (the oldest available), 1 July 2024 |
| `1-1-2/` | Verwaltungs- und Organisationsreglement (SRS 1.1-2) | 1 | one version (the oldest available), 1 July 2025 |
| `1-4-1/` | Verordnung über das amtliche Informationsblatt zu Gemeindewahlen nach dem Mehrheitswahlverfahren (SRS 1.4-1) | 1 | one version (the oldest available), 14 July 2023 |
| `1-6-1/` | Geschäftsordnung des Gemeinderates (SRS 1.6-1) | 1 | one version (the oldest available), 19 February 2014 |
| `1-6-2/` | Geschäftsordnung der Geschäftsleitungen (Geschäftsleitung und ergänzende Geschäftsleitung) (SRS 1.6-2) | 1 | as enacted, 1 July 2025 |
| `1-6-3/` | Behördenreglement (SRS 1.6-3) | 1 | one version (the oldest available), 1 January 2017 |
| `1-6-4/` | Reglement der Gemeindekommission und der Wahlbehörde (SRS 1.6-4) | 1 | one version (the oldest available), 1 July 2025 |
| `1-6-4-1/` | Geschäftsordnung der Gemeindekommission (SRS 1.6-4.1) | 1 | as enacted, 22 May 2001 |
| `1-6-6/` | Reglement der Sicherheits- und Umweltkommission (SUK) (SRS 1.6-6) | 1 | as enacted, 1 January 2025 |
| `1-6-6-1/` | Geschäftsordnung der Sicherheits- und Umweltkommission (SUK) (SRS 1.6-6.1) | 1 | as enacted, 1 July 2001 |
| `1-6-7/` | Reglement der Bau- und Planungskommission (BPK) (SRS 1.6-7) | 1 | one version (the oldest available), 1 July 2025 |
| `1-6-7-1-bpk/` | Geschäftsordnung der Bau- und Planungskommission (SRS 1.6-7.1) | 1 | one version (the oldest available), 1 June 2003 |
| `1-7-1/` | Personalreglement (SRS 1.7-1) | 1 | one version (the oldest available), 1 July 2025 |
| `1-7-1-1/` | Personalverordnung (SRS 1.7-1.1) | 1 | one version (the oldest available), 13 February 2025 |
| `1-7-1-2/` | Verordnung über die Organisation, die Rechte, Pflichten und Aufgaben des Mitarbeiterrates (SRS 1.7-1.2) | 1 | one version (the oldest available), 1 January 2022 |
| `2-2-1/` | Reglement über die amtliche Wohnungsabnahme (SRS 2.2-1) | 1 | one version (the oldest available), 1 July 2025 |
| `4-1-1/` | Reglement über die familienergänzende Kinderbetreuung (SRS 4.1-1) | 1 | as enacted, 1 January 2025 |
| `4-1-1-1/` | Verordnung über die familienergänzende Kinderbetreuung (SRS 4.1-1.1) | 1 | as enacted, 1 January 2025 |
| `4-1-1-2/` | Geschäftsordnung der Tagesfamilienorganisation (SRS 4.1-1.2) | 1 | as enacted, 1 January 2022 |
| `4-1-1-3/` | Geschäftsordnung Schulergänzende Betreuung (SRS 4.1-1.3) | 3 | as enacted, then each consolidated version: 20 January 2025 to 1 August 2026 |
| `4-1-1-4/` | Geschäftsordnung Tagesheim Sonnenmatt (SRS 4.1-1.4) | 1 | as enacted, 20 January 2025 |
| `4-2-1/` | Weisung über die Entrichtung von Gemeindebeiträgen aus dem Spezialfonds für die Schuljugend von Muttenz (SRS 4.2-1) | 1 | as enacted, 1 February 2000 |
| `4-3-1/` | Reglement für die Allgemeine Musikschule (SRS 4.3-1) | 1 | as enacted, 1 August 2003 |
| `4-3-1-1/` | Betriebsordnung der Allgemeinen Musikschule Muttenz (SRS 4.3-1.1) | 1 | one version (the oldest available), 1 January 2009 |
| `4-7-1/` | Reglement der Kultur- und Sportkommission (KuSpo) (SRS 4.7-1) | 1 | one version (the oldest available), 1 May 2005 |
| `4-7-1-1/` | Geschäfts- und Gebührenordnung Museen Muttenz (SRS 4.7-1.1) | 1 | as enacted, 1 February 2016 |
| `4-7-2/` | Leistungsvereinbarung mit Frauenverein Muttenz über die Führung der Bibliothek Muttenz (SRS 4.7-2) | 1 | as enacted, 1 July 2021 |
| `4-7-3/` | Richtlinie für Kulturförderung und Subventionsgesuche (SRS 4.7-3) | 1 | one version (the oldest available), 22 February 2017 |
| `5-1-1/` | Polizeireglement (SRS 5.1-1) | 1 | one version (the oldest available), 1 January 2025 |
| `5-3-1/` | Reglement über den Bevölkerungsschutz (SRS 5.3-1) | 1 | as enacted, 1 January 2025 |
| `5-3-1-1/` | Verordnung über den Bevölkerungsschutz (SRS 5.3-1.1) | 1 | one version (the oldest available), 1 January 2026 |
| `5-5-1/` | Reglement Stützpunkt-Feuerwehr Muttenz (SRS 5.5-1) | 1 | one version (the oldest available), 1 July 2025 |
| `5-5-1-1/` | Verordnung zum Reglement Stützpunkt-Feuerwehr (SRS 5.5-1.1) | 1 | one version (the oldest available), 1 January 2026 |
| `6-1-1/` | Reglement der Finanzkommission (Fiko) (SRS 6.1-1) | 1 | as enacted, 1 January 2017 |
| `6-1-1-1/` | Geschäftsordnung der Finanzkommission (Fiko) (SRS 6.1-1.1) | 1 | as enacted, 20 September 2017 |
| `6-1-2/` | Reglement über den Fonds Hagnau-Schänzli (SRS 6.1-2) | 1 | as enacted, 1 March 2019 |
| `6-1-3/` | Richtlinie Ausgabenkompetenz und Rechnungswesen (SRS 6.1-3) | 1 | as enacted, 1 July 2025 |
| `6-1-4/` | Richtlinien für die Debitoren- / Verlustscheinbewirtschaftung (SRS 6.1-4) | 1 | as enacted, 22 September 2021 |
| `6-3-1/` | Steuerreglement (SRS 6.3-1) | 1 | one version (the oldest available), 1 January 2026 |
| `6-4-1/` | Allgemeine Gebühren- und Benützungsordnung (SRS 6.4-1) | 1 | as enacted, 1 January 2019 |
| `6-6-1-benutzungsverordnung/` | Verordnung über die Benutzung gemeindeeigener Räumlichkeiten (SRS 6.6-1) | 1 | as enacted, 1 August 2025 |
| `6-6-1-1/` | Hausordnung zur Benützung von Schulanlagen (SRS 6.6-1.1) | 1 | as enacted, 1 July 2005 |
| `6-6-2/` | Benutzungsordnung für die Pflanzgärten (SRS 6.6-2) | 1 | as enacted, 1 April 2024 |
| `6-6-3/` | Gesellschaftsvertrag über die Nutzung der Schiessanlagen in der Lachmatt (SRS 6.6-3) | 1 | as enacted, 10 December 2008 |
| `6-6-3-1/` | Vereinbarung betreffend Benutzung der «Schiessanlagen Lachmatt» in Muttenz und Pratteln für die «Basler Schützen» (SRS 6.6-3.1) | 1 | as enacted, 5 May 2009 |
| `6-6-3-2/` | Vertrag betreffend Schiessrecht auf den Schiessanlagen Lachmatt der Gemeinden Birsfelden, Muttenz und Pratteln für die Binninger Schützen (SRS 6.6-3.2) | 1 | as enacted, 1 January 2010 |
| `6-6-4/` | Verordnung über die Öffnungszeiten und Zugangsberechtigungen zu den Schulanlagen und öffentlichen Spielplätzen der Gemeinde (SRS 6.6-4) | 1 | one version (the oldest available), 1 May 2025 |
| `6-6-5/` | Betriebs- und Nutzungskonzept der Street-Soccer-Anlage (SRS 6.6-5) | 1 | as enacted, 9 April 2008 |
| `6-6-6/` | Nutzungs- und Gebührenordnung Jugend- und Kulturhaus Fabrik (SRS 6.6-6) | 1 | as enacted, 1 July 2006 |
| `6-6-7/` | Verordnung über die Benutzung der Sportanlagen (SRS 6.6-7) | 1 | as enacted, 1 August 2025 |
| `6-6-7-1/` | Betriebsordnung für die Videoüberwachung im Hallenbad (SRS 6.6-7.1) | 1 | as enacted, 30 March 2016 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://muttenz.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the municipality's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@muttenz.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
