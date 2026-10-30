# Zug: law history in git

The law of the canton of Zug (Kanton Zug, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-zg/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, the canton's official language, exactly as the canton publishes it.

## What this repository holds

323 acts with 1051 versions so far: the cantonal constitution, the cantonal laws (Gesetze) in force and 224 Verordnungen and Reglemente in force, in the order of the systematic collection, added in parts. Other decrees and decisions, intercantonal agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `111-1-kantonsverfassung-kv/` | Verfassung des Kantons Zug (BGS 111.1) | 6 | oldest version available, then each consolidated version: 28 November 2010 to 1 January 2026 |
| `121-3-burgerrechtsgesetz/` | Gesetz betreffend Erwerb und Verlust des Gemeinde- und des Kantonsbürgerrechts (BGS 121.3) | 3 | oldest version available, then each consolidated version: 27 September 2009 to 1 January 2025 |
| `122-5-eg-aug/` | Einführungsgesetz zum Bundesgesetz über die Ausländerinnen und Ausländer und zum Asylgesetz (BGS 122.5) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 20 August 2016 |
| `131-1-wahl-und-abstimmungsgesetz-wag/` | Gesetz über die Wahlen und Abstimmungen (BGS 131.1) | 7 | oldest version available, then each consolidated version: 1 May 2010 to 1 January 2026 |
| `151-2/` | Gesetz über die Rechtsstellung der Mitglieder des Regierungsrats (BGS 151.2) | 4 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2017 |
| `152-3-publikationsgesetz-publg-zg/` | Gesetz über die Veröffentlichung der Erlasse und das Amtsblatt des Kantons Zug (BGS 152.3) | 4 | oldest version available, then each consolidated version: 9 December 2000 to 1 January 2023 |
| `152-4/` | Archivgesetz (BGS 152.4) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 1 September 2020 |
| `153-1-organisationsgesetz-og/` | Gesetz über die Organisation der Staatsverwaltung (BGS 153.1) | 5 | oldest version available, then each consolidated version: 5 December 2009 to 1 January 2019 |
| `154-11-verantwortlichkeitsgesetz/` | Gesetz über die Verantwortlichkeit der Gemeinwesen, Behördemitglieder und Beamten (BGS 154.11) | 1 | one version (the oldest available), 1 January 2011 |
| `154-21-personalgesetz-pg/` | Gesetz über das Arbeitsverhältnis des Staatspersonals (BGS 154.21) | 9 | oldest version available, then each consolidated version: 4 August 2010 to 14 November 2025 |
| `154-25-nebenamtsgesetz/` | Gesetz über die Entschädigung der nebenamtlichen Behördenmitglieder (BGS 154.25) | 2 | oldest version available, then each consolidated version: 11 July 2009 to 1 January 2026 |
| `154-31-pensionskassengesetz-pkg/` | Gesetz über die Zuger Pensionskasse (BGS 154.31) | 3 | oldest version available, then each consolidated version: 12 December 2008 to 14 November 2025 |
| `156-1-ombudsgesetz/` | Gesetz über die Ombudsstelle (BGS 156.1) | 2 | as enacted, then each consolidated version: 4 August 2010 to 3 May 2014 |
| `157-1-dsg/` | Datenschutzgesetz (BGS 157.1) | 3 | oldest version available, then each consolidated version: 8 November 2008 to 1 September 2020 |
| `158-1-offentlichkeitsgesetz/` | Gesetz über das Öffentlichkeitsprinzip der Verwaltung (BGS 158.1) | 1 | as enacted, 10 May 2014 |
| `159-1-videouberwachungsgesetz-videog/` | Gesetz über die Videoüberwachung im öffentlichen und im öffentlich zugänglichen Raum (BGS 159.1) | 2 | as enacted, then each consolidated version: 6 September 2014 to 1 September 2020 |
| `161-1-gerichtsorganisationsgesetz-gog/` | Gesetz über die Organisation der Zivil- und Strafrechtspflege (BGS 161.1) | 14 | as enacted, then each consolidated version: 1 January 2011 to 17 October 2025 |
| `161-2/` | Gesetz über den Ablauf von Fristen im Gerichts- und Verwaltungsverfahren (BGS 161.2) | 1 | as enacted, 15 June 1964 |
| `162-1-verwaltungsrechtspflegegesetz-vrg/` | Gesetz über den Rechtsschutz in Verwaltungssachen (BGS 162.1) | 10 | oldest version available, then each consolidated version: 1 January 2011 to 17 October 2025 |
| `163-1-eg-bgfa/` | Einführungsgesetz zum Bundesgesetz über die Freizügigkeit der Anwältinnen und Anwälte (BGS 163.1) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 12 November 2016 |
| `171-1-gemeindegesetz-gg/` | Gesetz über die Organisation und die Verwaltung der Gemeinden (BGS 171.1) | 10 | oldest version available, then each consolidated version: 1 January 2010 to 17 October 2025 |
| `211-1-eg-zgb/` | Gesetz betreffend die Einführung des Schweizerischen Zivilgesetzbuches für den Kanton Zug (BGS 211.1) | 9 | oldest version available, then each consolidated version: 1 January 2013 to 11 July 2025 |
| `213-4-kinderbetreuungsgesetz-kibeg/` | Gesetz über die familienergänzende Kinderbetreuung (BGS 213.4) | 3 | as enacted, then each consolidated version: 1 January 2007 to 1 August 2026 |
| `213-711-inkassohilfe-und-bevorschussungsgesetz/` | Gesetz über Inkassohilfe und Bevorschussung von Unterhaltsbeiträgen (BGS 213.711) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2013 |
| `215-11/` | Einführungsgesetz zum Bundesgesetz über den Erwerb von Grundstücken durch Personen im Ausland (BGS 215.11) | 1 | one version (the oldest available), 1 January 2011 |
| `215-71-geoinformationsgesetz-geoig-zg/` | Gesetz über Geoinformation im Kanton Zug (BGS 215.71) | 2 | as enacted, then each consolidated version: 1 January 2013 to 29 June 2019 |
| `216-1-eg-or/` | Einführungsgesetz zum Schweizerischen Obligationenrecht (BGS 216.1) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 October 2013 |
| `223-1-beurkundungsgesetz-beurkg/` | Gesetz über die öffentliche Beurkundung und die Beglaubigung in Zivilsachen (BGS 223.1) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 April 2015 |
| `231-1-eg-schkg/` | Einführungsgesetz zum Bundesgesetz über Schuldbetreibung und Konkurs (BGS 231.1) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 13 January 2023 |
| `251-1-eg-rhg/` | Einführungsgesetz zum Bundesgesetz über die Harmonisierung der Einwohnerregister und anderer amtlicher Personenregister (BGS 251.1) | 2 | as enacted, then each consolidated version: 1 January 2009 to 1 April 2023 |
| `312-1-ustg/` | Übertretungsstrafgesetz (BGS 312.1) | 3 | as enacted, then each consolidated version: 1 October 2013 to 1 May 2022 |
| `312-1-a1-ustg/` | Übertretungsstrafgesetz (Anhang: Bussenkatalog gemäss § 15 ÜStG) (BGS 312.1-A1) | 5 | as enacted, then each consolidated version: 1 October 2013 to 1 January 2025 |
| `412-11-schulg/` | Schulgesetz (BGS 412.11) | 11 | oldest version available, then each consolidated version: 17 July 2010 to 1 August 2025 |
| `412-31-lehrpersonalgesetz/` | Gesetz über das Dienstverhältnis und die Besoldung der Lehrpersonen an den gemeindlichen Schulen (BGS 412.31) | 5 | oldest version available, then each consolidated version: 1 August 2010 to 1 August 2024 |
| `413-11-eg-berufsbildung/` | Einführungsgesetz zu den Bundesgesetzen über die Berufsbildung und die Fachhochschulen (BGS 413.11) | 5 | oldest version available, then each consolidated version: 1 January 2011 to 9 May 2020 |
| `414-11/` | Gesetz über die kantonalen Schulen (BGS 414.11) | 6 | oldest version available, then each consolidated version: 1 January 2008 to 1 August 2020 |
| `414-41-ph-gesetz-phg/` | Gesetz über die Pädagogische Hochschule Zug (BGS 414.41) | 2 | as enacted, then each consolidated version: 1 August 2013 to 1 January 2024 |
| `416-21/` | Gesetz über Ausbildungsbeiträge (BGS 416.21) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 12 September 2025 |
| `417-1/` | Sportgesetz (BGS 417.1) | 3 | oldest version available, then each consolidated version: 1 August 2006 to 1 July 2023 |
| `421-1/` | Gesetz über die Förderung des kulturellen Lebens (BGS 421.1) | 2 | oldest version available, then each consolidated version: 1 January 2000 to 1 January 2018 |
| `423-11-denkmalschutzgesetz-dmsg/` | Gesetz über Denkmalpflege, Archäologie und Kulturgüterschutz (BGS 423.11) | 7 | oldest version available, then each consolidated version: 1 January 2009 to 14 December 2019 |
| `432-1/` | Gesetz über den Natur- und Landschaftsschutz (BGS 432.1) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 October 2013 |
| `446-1/` | Gesetz über den Steuerausgleich unter den katholischen Kirchgemeinden des Kantons Zug (BGS 446.1) | 1 | as enacted, 1 January 2005 |
| `512-1-polg/` | Polizeigesetz (BGS 512.1) | 9 | oldest version available, then each consolidated version: 1 June 2011 to 26 February 2022 |
| `512-2-polizei-organisationsgesetz/` | Gesetz über die Organisation der Polizei (BGS 512.2) | 6 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2020 |
| `531-1-zivilschutzgesetz/` | Gesetz für den Zivilschutz (BGS 531.1) | 2 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2020 |
| `541-1-bevolkerungsschutzgesetz-bevsg/` | Gesetz betreffend den Schutz der Bevölkerung (BGS 541.1) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2020 |
| `611-1-finanzhaushaltgesetz-fhg/` | Gesetz über den Finanzhaushalt des Kantons und der Gemeinden (BGS 611.1) | 3 | oldest version available, then each consolidated version: 1 September 2011 to 1 June 2022 |
| `621-1/` | Gesetz über den direkten Finanzausgleich (BGS 621.1) | 2 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2015 |
| `632-1/` | Steuergesetz (BGS 632.1) | 9 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2026 |
| `651-1-kantonalbankgesetz-zgkbg/` | Gesetz über die Zuger Kantonalbank (BGS 651.1) | 4 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2020 |
| `661-2/` | Gesetz über das Salzregal (BGS 661.2) | 1 | one version (the oldest available), 1 January 2007 |
| `711-7/` | Gesetz über den Schutz und die Erhaltung der Moränenlandschaft im Raume Menzingen–Neuheim und Umgebung (BGS 711.7) | 1 | as enacted, 12 June 1988 |
| `721-6-gnu/` | Gesetz über die Nutzung des Untergrunds (BGS 721.6) | 1 | as enacted, 1 January 2019 |
| `721-11-pbg/` | Planungs- und Baugesetz (BGS 721.11) | 8 | oldest version available, then each consolidated version: 1 January 2012 to 1 July 2019 |
| `721-51-subg/` | Submissionsgesetz (BGS 721.51) | 2 | as enacted, then each consolidated version: 1 October 2005 to 1 March 2024 |
| `722-11-gebaudeversicherungsgesetz-gebvg/` | Gesetz über die Gebäudeversicherung (BGS 722.11) | 5 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2024 |
| `722-21-feuerschutzgesetz-fsg/` | Gesetz über den Feuerschutz (BGS 722.21) | 7 | oldest version available, then each consolidated version: 1 December 2009 to 1 January 2025 |
| `731-1-gewg/` | Gesetz über die Gewässer (BGS 731.1) | 5 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2019 |
| `731-1-a1-gewg/` | Gesetz über die Gewässer (Anhang: Verzeichnis der öffentlichen Oberflächengewässer) (BGS 731.1-A1) | 1 | one version (the oldest available), 9 June 2009 |
| `731-2-gewassergebuhrentarif/` | Gesetz über die Gebühren für besondere Inanspruchnahmen von öffentlichen Gewässern (BGS 731.2) | 4 | as enacted, then each consolidated version: 9 April 2004 to 1 January 2019 |
| `740-1-eng-zg/` | Energiegesetz (BGS 740.1) | 3 | as enacted, then each consolidated version: 11 September 2004 to 1 February 2024 |
| `751-14-gsw/` | Gesetz über Strassen und Wege (BGS 751.14) | 4 | oldest version available, then each consolidated version: 1 January 2012 to 1 June 2019 |
| `751-14-a1-gsw/` | Gesetz über Strassen und Wege (Anhang 1: Verzeichnis der Kantonsstrassen gemäss § 5 GSW) (BGS 751.14-A1) | 6 | as enacted, then each consolidated version: 1 January 2012 to 21 June 2021 |
| `751-14-a2-gsw/` | Gesetz über Strassen und Wege (Anhang 2: Verzeichnis der Radstrecken gemäss § 5 GSW) (BGS 751.14-A2) | 1 | as enacted, 1 January 2012 |
| `751-14-a3-gsw/` | Gesetz über Strassen und Wege (Anhang 3: Verzeichnis der Wanderwege gemäss § 5 GSW) (BGS 751.14-A3) | 1 | as enacted, 1 January 2012 |
| `751-22/` | Gesetz über die Steuern im Strassenverkehr (BGS 751.22) | 3 | oldest version available, then each consolidated version: 1 January 1999 to 1 January 2027 |
| `751-31/` | Gesetz über den öffentlichen Verkehr (BGS 751.31) | 2 | as enacted, then each consolidated version: 9 December 2007 to 1 January 2018 |
| `753-1/` | Einführungsgesetz zum Bundesgesetz über die Binnenschifffahrt (BGS 753.1) | 2 | oldest version available, then each consolidated version: 1 January 1999 to 1 January 2019 |
| `811-1-eg-usg/` | Einführungsgesetz zum Bundesgesetz über den Umweltschutz (BGS 811.1) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2018 |
| `821-1-gesundheitsgesetz-gesg/` | Gesetz über das Gesundheitswesen im Kanton Zug (BGS 821.1) | 7 | as enacted, then each consolidated version: 1 March 2009 to 11 July 2025 |
| `822-1-eg-fap/` | Einführungsgesetz zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (BGS 822.1) | 1 | as enacted, 20 September 2024 |
| `823-5-eg-betmg/` | Einführungsgesetz zum Bundesgesetz über die Betäubungsmittel (BGS 823.5) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2020 |
| `826-11/` | Spitalgesetz (BGS 826.11) | 3 | oldest version available, then each consolidated version: 1 March 2009 to 1 January 2017 |
| `826-12/` | Gesetz über das Zuger Kantonsspital (BGS 826.12) | 1 | one version (the oldest available), 1 March 2009 |
| `826-25/` | Gesetz über die Ausrichtung kantonaler Mutterschaftsbeiträge (BGS 826.25) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2018 |
| `834-21-eg-entsendegesetz/` | Einführungsgesetz zum Bundesgesetz über die minimalen Arbeits- und Lohnbedingungen für in die Schweiz entsandte Arbeitnehmerinnen und Arbeitnehmer und flankierende Massnahmen (BGS 834.21) | 1 | one version (the oldest available), 1 January 2008 |
| `841-1/` | Einführungsgesetz zu den Bundesgesetzen über die Alters- und Hinterlassenenversicherung und die Invalidenversicherung (BGS 841.1) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 14 September 2019 |
| `841-7-eg-elg/` | Einführungsgesetz zum Bundesgesetz über Ergänzungsleistungen zur Alters-, Hinterlassenen- und Invalidenversicherung (BGS 841.7) | 4 | as enacted, then each consolidated version: 8 May 2008 to 29 August 2020 |
| `842-1-eg-kvg/` | Einführungsgesetz zum Bundesgesetz über die Krankenversicherung (BGS 842.1) | 4 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2025 |
| `842-6-pramienverbilligungsgesetz-ipvg/` | Gesetz betreffend individuelle Prämienverbilligung in der Krankenpflegeversicherung (BGS 842.6) | 5 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2025 |
| `844-1/` | Einführungsgesetz zum Bundesgesetz über die Familienzulagen in der Landwirtschaft (BGS 844.1) | 1 | one version (the oldest available), 1 January 2006 |
| `844-4-famzg/` | Einführungsgesetz zum Bundesgesetz über die Familienzulagen (BGS 844.4) | 4 | as enacted, then each consolidated version: 1 January 2009 to 14 September 2019 |
| `845-5/` | Einführungsgesetz zum Bundesgesetz über die obligatorische Arbeitslosenversicherung und die Insolvenzentschädigung (BGS 845.5) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2018 |
| `851-211-wohnraumforderungsgesetz-wfg/` | Gesetz über die Förderung von preisgünstigem Wohnraum (BGS 851.211) | 3 | oldest version available, then each consolidated version: 1 August 2010 to 1 January 2018 |
| `861-4-sozialhilfegesetz-shg/` | Gesetz über die Sozialhilfe im Kanton Zug (BGS 861.4) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2024 |
| `861-5-lbbg/` | Gesetz über Leistungen für Menschen mit Behinderung und Betreuungsbedarf (BGS 861.5) | 2 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2024 |
| `915-1-wirtschaftspflegegesetz/` | Gesetz über die Wirtschaftspflege im Kanton Zug (BGS 915.1) | 2 | as enacted, then each consolidated version: 1 October 2013 to 1 January 2018 |
| `915-2-gse/` | Gesetz über Standortentwicklung (BGS 915.2) | 1 | as enacted, 1 January 2026 |
| `921-1-eg-landwirtschaft/` | Einführungsgesetz zu den Bundesgesetzen über die Landwirtschaft, die landwirtschaftliche Pacht und das bäuerliche Bodenrecht (BGS 921.1) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2019 |
| `925-16/` | Gesetz über den Entschädigungsfonds für Tierverluste (BGS 925.16) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 July 2012 |
| `931-1-eg-waldgesetz/` | Einführungsgesetz zum Bundesgesetz über den Wald (BGS 931.1) | 7 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2025 |
| `932-1-jagdgesetz/` | Gesetz über die Jagd und den Schutz wildlebender Säugetiere und Vögel (BGS 932.1) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2018 |
| `933-21/` | Gesetz über die Fischerei (BGS 933.21) | 4 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2020 |
| `942-31/` | Ruhetags- und Ladenöffnungsgesetz (BGS 942.31) | 2 | oldest version available, then each consolidated version: 10 May 2008 to 22 August 2025 |
| `942-46-eg-bgs/` | Einführungsgesetz zum Bundesgesetz über Geldspiele (BGS 942.46) | 1 | as enacted, 1 July 2023 |
| `943-11-gastgewerbegesetz-ggg/` | Gesetz über das Gastgewerbe und den Kleinhandel mit gebrannten Wassern (BGS 943.11) | 5 | oldest version available, then each consolidated version: 1 January 2009 to 22 August 2025 |
| `944-1/` | Tourismusgesetz (BGS 944.1) | 2 | oldest version available, then each consolidated version: 6 February 2010 to 1 January 2012 |
| `944-2/` | Gesetz über die Beherbergungsabgabe (BGS 944.2) | 2 | as enacted, then each consolidated version: 1 January 1999 to 1 January 2015 |
| `121-31-kant-buv/` | Verordnung zum kantonalen Bürgerrechtsgesetz (BGS 121.31) | 2 | oldest version available, then each consolidated version: 27 September 2009 to 1 January 2025 |
| `121-32-uvbug/` | Übergangsverordnung zum revidierten Bundesgesetz über das Schweizer Bürgerrecht (BGS 121.32) | 1 | as enacted, 1 January 2018 |
| `122-3/` | Verordnung zur Bundesgesetzgebung über die Ausweise für Schweizer Staatsangehörige (BGS 122.3) | 1 | one version (the oldest available), 1 March 2010 |
| `131-2-wahl-und-abstimmungsverordnung-wav/` | Verordnung zum Wahl- und Abstimmungsgesetz (BGS 131.2) | 7 | oldest version available, then each consolidated version: 3 July 2010 to 20 February 2026 |
| `132-11-gleichstellungsverordnung-glv-zg/` | Verordnung über die Gleichstellung von Frau und Mann (BGS 132.11) | 1 | as enacted, 1 January 2017 |
| `141-4/` | Reglement über die Grundsätze zur Übernahme der Weiterbildungskosten für die Mitglieder des Kantonsrats (BGS 141.4) | 1 | as enacted, 11 June 2016 |
| `141-111/` | Reglement betreffend elektronische Abstimmungsanlage im Kantonsratssaal (BGS 141.111) | 1 | as enacted, 15 December 2016 |
| `152-31-amtsblattverordnung-abv/` | Verordnung über das Amtsblatt des Kantons Zug (BGS 152.31) | 2 | as enacted, then each consolidated version: 1 January 2023 to 1 January 2024 |
| `152-42/` | Verordnung über die Aktenführung (BGS 152.42) | 1 | as enacted, 1 June 2012 |
| `153-2-organisationsverordnung-ov/` | Verordnung betreffend die Organisation und die Zuständigkeiten der Staatsverwaltung des Kantons Zug (BGS 153.2) | 17 | oldest version available, then each consolidated version: 1 January 2011 to 11 July 2025 |
| `153-3-delv/` | Delegationsverordnung (BGS 153.3) | 26 | oldest version available, then each consolidated version: 17 December 2011 to 1 January 2025 |
| `153-53-itv/` | Informatikverordnung (BGS 153.53) | 6 | oldest version available, then each consolidated version: 1 January 2011 to 19 December 2020 |
| `153-62-steuerungs-verordnung/` | Verordnung betreffend Steuerung der Verwaltungstätigkeit (BGS 153.62) | 2 | as enacted, then each consolidated version: 1 September 2011 to 1 March 2012 |
| `153-64-v-dpv/` | Verordnung über die digitale Postverarbeitung (BGS 153.64) | 1 | as enacted, 1 February 2024 |
| `153-81/` | Verordnung betreffend Änderung der namentlichen Nennung der Direktionen und der Ämter in den Gesetzessammlungen durch die neutralen Bezeichnungen «zuständige Direktion» und «zuständiges Amt» (BGS 153.81) | 3 | as enacted, then each consolidated version: 14 September 2019 to 5 December 2020 |
| `153-756/` | Delegationsverordnung über die Regelung der Zuständigkeit betreffend individuelle Personalgeschäfte bei der Staatskanzlei (BGS 153.756) | 1 | as enacted, 1 July 2025 |
| `153-766-delv-gd/` | Delegationsverordnung der Gesundheitsdirektion (BGS 153.766) | 5 | as enacted, then each consolidated version: 1 January 2015 to 21 February 2025 |
| `154-28/` | Verordnung über die Benutzung von elektronischen Geräten und elektronischen Kommunikationsmitteln im Arbeitsverhältnis (BGS 154.28) | 2 | oldest version available, then each consolidated version: 1 July 2010 to 19 December 2020 |
| `154-29-telefonnutzungsverordnung-tnv/` | Verordnung über die Nutzung von Mobil- und Festnetztelefonen (BGS 154.29) | 3 | as enacted, then each consolidated version: 1 July 2010 to 6 June 2020 |
| `154-211-personalverordnung-pvo/` | Vollziehungsverordnung zum Gesetz über das Arbeitsverhältnis des Staatspersonals (BGS 154.211) | 7 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `154-213/` | Reglement betreffend Gewährleistung des Mitspracherechts der öffentlich-rechtlichen Arbeitnehmer gegenüber dem Kanton (BGS 154.213) | 1 | one version (the oldest available), 1 January 1999 |
| `154-214-arbeitszeitverordnung-azvo/` | Verordnung über die Arbeitszeit (BGS 154.214) | 6 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2024 |
| `154-215-weiterbildungsverordnung-wbvo/` | Verordnung über die Aus-, Fort- und Weiterbildung sowie den Bildungsurlaub (BGS 154.215) | 5 | oldest version available, then each consolidated version: 1 August 2011 to 1 August 2026 |
| `154-219-parkplatzverordnung-ppv/` | Verordnung über die Bewirtschaftung und Zuteilung von Parkplätzen in der kantonalen Verwaltung (BGS 154.219) | 3 | oldest version available, then each consolidated version: 1 September 2010 to 1 September 2024 |
| `154-221-entschadigungsverordnung/` | Verordnung über besondere Entschädigungen (BGS 154.221) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2024 |
| `154-223/` | Reglement über die Abgabe und Entschädigung von Arbeitskleidern und Sicherheitsausrüstung in der Direktion des Innern (BGS 154.223) | 6 | as enacted, then each consolidated version: 1 January 2011 to 21 November 2025 |
| `154-231/` | Reglement über die Entschädigung der nebenamtlich Beauftragten im Veterinärdienst (BGS 154.231) | 1 | one version (the oldest available), 1 January 2011 |
| `154-234-lohneinreihungsverordnung-levo/` | Verordnung über die Referenzfunktionen, den Einreihungsplan und die Lohneinreihung (BGS 154.234) | 2 | as enacted, then each consolidated version: 1 January 2024 to 1 August 2026 |
| `154-236/` | Verordnung über die Lohneinreihung der Lehrpersonen der Mittel- und Berufsfachschulen sowie der Brückenangebote (BGS 154.236) | 3 | as enacted, then each consolidated version: 1 August 2016 to 1 August 2025 |
| `157-12-vip/` | Verordnung über die Informationssicherheit von Personendaten (BGS 157.12) | 2 | as enacted, then each consolidated version: 27 January 2007 to 19 December 2020 |
| `157-22-online-verordnung/` | Verordnung über das Bewilligungsverfahren für den elektronischen Datenaustausch (BGS 157.22) | 1 | as enacted, 28 June 2008 |
| `159-11-videouberwachungsverordnung-videov/` | Verordnung zum Gesetz über die Videoüberwachung im öffentlichen und im öffentlich zugänglichen Raum (BGS 159.11) | 2 | as enacted, then each consolidated version: 2 July 2016 to 19 December 2020 |
| `161-3-vo-sta/` | Verordnung über die Staatsanwaltschaft (BGS 161.3) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 7 April 2023 |
| `161-4/` | Verordnung über die Schlichtungsbehörden (BGS 161.4) | 2 | as enacted, then each consolidated version: 1 January 2011 to 3 January 2025 |
| `161-5-vo-zmg/` | Verordnung über das Zwangsmassnahmengericht (BGS 161.5) | 1 | as enacted, 1 January 2025 |
| `161-7-kostenverordnung-obergericht-kov-og/` | Verordnung über die Kosten in der Zivil- und Strafrechtspflege (BGS 161.7) | 7 | oldest version available, then each consolidated version: 1 January 2007 to 1 July 2026 |
| `161-14-vgb/` | Verordnung über die Gerichtsberichterstattung in der Zivil- und Strafrechtspflege (BGS 161.14) | 1 | as enacted, 18 January 2011 |
| `161-15-ubersetzungsverordnung-uebv/` | Verordnung betreffend das Übersetzungswesen im behördlichen Verkehr (BGS 161.15) | 2 | as enacted, then each consolidated version: 1 January 2014 to 1 October 2022 |
| `161-76/` | Verordnung über die Zeichnungs- und Anweisungsberechtigung in der Zivil- und Strafrechtspflege (BGS 161.76) | 1 | as enacted, 1 May 2008 |
| `162-12-kosten-vo/` | Verordnung über die Kosten im Verfahren vor dem Verwaltungsgericht (BGS 162.12) | 4 | oldest version available, then each consolidated version: 1 January 2007 to 18 July 2025 |
| `162-13/` | Verordnung über die elektronische Übermittlung im Verwaltungsverfahren (BGS 162.13) | 3 | as enacted, then each consolidated version: 1 January 2016 to 3 October 2020 |
| `162-14-zav-vg/` | Verordnung über die Zeichnungs- und Anweisungsberechtigung am Verwaltungsgericht (BGS 162.14) | 1 | as enacted, 1 April 2024 |
| `162-41-kostenverordnung-kov-rr/` | Verordnung betreffend Gebühren, Kostenvorschüsse, Parteientschädigungen und Umtriebsentschädigungen in Beschwerdeverfahren vor dem Regierungsrat (BGS 162.41) | 1 | as enacted, 1 January 2022 |
| `163-2-anwaltsprufungsverordnung/` | Verordnung über die Fähigkeitsprüfung für den Anwaltsberuf und die Beurkundungsprüfung für Rechtsanwältinnen und Rechtsanwälte (BGS 163.2) | 4 | as enacted, then each consolidated version: 1 January 2003 to 1 January 2025 |
| `163-4-anwt/` | Verordnung über den Anwaltstarif (BGS 163.4) | 3 | as enacted, then each consolidated version: 1 January 1997 to 1 January 2026 |
| `171-4/` | Prüfungsreglement für Gemeindeschreiber und deren Stellvertreter im Beurkundungsrecht (BGS 171.4) | 1 | one version (the oldest available), 15 July 2000 |
| `212-1-kantonale-zivilstandsverordnung-kant-zstv/` | Vollziehungsverordnung über das Zivilstandswesen (BGS 212.1) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2025 |
| `212-2/` | Verordnung betreffend die Aufsicht über die Stiftungen (BGS 212.2) | 2 | oldest version available, then each consolidated version: 1 January 2006 to 1 January 2017 |
| `213-41-pflege-und-adoptionskinderverordnung-pakv/` | Verordnung über die Aufnahme von Kindern zur Pflege und zur Adoption (BGS 213.41) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 October 2015 |
| `213-42-kinderbetreuungsverordnung-kibev/` | Verordnung zum Gesetz über die familienergänzende Kinderbetreuung (BGS 213.42) | 3 | oldest version available, then each consolidated version: 1 January 2009 to 1 August 2026 |
| `213-42-a1-anhang/` | Verordnung zum Gesetz über die familienergänzende Kinderbetreuung (Kinderbetreuungsverordnung, KiBeV) (BGS 213.42-A1) | 5 | as enacted, then each consolidated version: 1 January 2007 to 1 August 2026 |
| `213-51/` | Verordnung über die Kosten von Kindesschutzmassnahmen (BGS 213.51) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2013 |
| `213-52-vesbv/` | Verordnung über Entschädigung und Spesenersatz bei Beistandschaften und Vormundschaften (BGS 213.52) | 1 | as enacted, 1 January 2013 |
| `213-712-inkassohilfe-und-bevorschussungsverordnung/` | Verordnung über Inkassohilfe und Bevorschussung von Unterhaltsbeiträgen (BGS 213.712) | 3 | oldest version available, then each consolidated version: 1 July 2006 to 24 August 2013 |
| `213-713/` | Verordnung 25 betreffend Anpassungen an die Lohn- und Preisentwicklung bei der Bevorschussung von Unterhaltsbeiträgen (BGS 213.713) | 7 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `215-14/` | Verordnung über die amtliche Schätzung (BGS 215.14) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2019 |
| `215-23/` | Verordnung betreffend die Viehverpfändung (BGS 215.23) | 1 | as enacted, 3 January 1912 |
| `215-32/` | Verordnung über die Bereinigung der dinglichen Rechte und die Anlage des Grundbuches (BGS 215.32) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2019 |
| `215-51/` | Verordnung über den Umgang mit gefundenen, herrenlosen und sichergestellten Gegenständen (BGS 215.51) | 2 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2017 |
| `215-56-pfandleihverordnung/` | Verordnung über das Pfandleihgewerbe (BGS 215.56) | 1 | as enacted, 1 March 2008 |
| `215-142/` | Verordnung über die Gebühren und die Entschädigung für Liegenschaftsschätzungen (BGS 215.142) | 3 | oldest version available, then each consolidated version: 1 January 2003 to 1 January 2014 |
| `215-313-it-grundbuch-verordnung/` | Verordnung über die Führung des Grundbuchs mittels Informatik, den elektronischen Geschäftsverkehr sowie die Aufsicht über das Grundbuch (BGS 215.313) | 5 | oldest version available, then each consolidated version: 1 January 2008 to 17 February 2023 |
| `215-711-geoinformationsverordnung-geoiv-zg/` | Verordnung über Geoinformation im Kanton Zug (BGS 215.711) | 4 | as enacted, then each consolidated version: 1 January 2013 to 1 February 2020 |
| `215-712-leitungskatasterverordnung-lkv/` | Verordnung über den Leitungskataster (BGS 215.712) | 1 | as enacted, 1 February 2020 |
| `216-12/` | Verordnung zum Einführungsgesetz zum Schweizerischen Obligationenrecht (BGS 216.12) | 1 | one version (the oldest available), 1 May 2010 |
| `223-11-e-eobv/` | Einführungsverordnung zur Verordnung des Bundes über die Erstellung elektronischer öffentlicher Urkunden und elektronischer Beglaubigungen (BGS 223.11) | 1 | as enacted, 1 January 2022 |
| `231-12/` | Verordnung über die zuständige kantonale Behörde gemäss Art. 230a Abs. 3 SchKG (BGS 231.12) | 1 | as enacted, 18 June 2005 |
| `251-12-verordnung-zum-eg-rhg/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Harmonisierung der Einwohnerregister und anderer amtlicher Personenregister (BGS 251.12) | 8 | as enacted, then each consolidated version: 1 January 2009 to 20 February 2026 |
| `312-11-vustg/` | Verordnung zum Übertretungsstrafgesetz (BGS 312.11) | 1 | as enacted, 1 October 2013 |
| `315-1-vohg/` | Kantonale Verordnung zur Bundesgesetzgebung über die Hilfe an Opfer von Straftaten (BGS 315.1) | 2 | oldest version available, then each consolidated version: 1 January 1999 to 1 January 2021 |
| `321-4/` | Vollziehungsverordnung zu Art. 119 f. StGB über die Durchführung des straflosen Schwangerschaftsabbruchs (BGS 321.4) | 1 | as enacted, 25 October 2002 |
| `321-21-dna-verordnung/` | Verordnung zur Einführung des Bundesgesetzes über die Verwendung von DNA-Profilen im Strafverfahren und zur Identifizierung von unbekannten oder vermissten Personen (BGS 321.21) | 1 | one version (the oldest available), 1 January 2011 |
| `321-21-a1-dna-verordnung/` | Verordnung zur Einführung des Bundesgesetzes über die Verwendung von DNA-Profilen im Strafverfahren und zur Identifizierung von unbekannten oder vermissten Personen (Anhang) (BGS 321.21-A1) | 1 | as enacted, 1 January 2011 |
| `331-11-jvv/` | Justizvollzugsverordnung (BGS 331.11) | 4 | as enacted, then each consolidated version: 24 March 2018 to 1 March 2024 |
| `331-31-vo-kost/` | Verordnung betreffend Koordinationsstelle für das Strafregister (BGS 331.31) | 2 | as enacted, then each consolidated version: 1 January 2011 to 7 April 2023 |
| `331-71-vvj/` | Verordnung über den Vollzug der Schutzmassnahmen und Strafen gegenüber Jugendlichen (BGS 331.71) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2013 |
| `332-313-reglement-rekurskommission-jva-bostadel/` | Reglement der Rekurskommission der Justizvollzugsanstalt Bostadel (BGS 332.313) | 1 | as enacted, 1 December 2021 |
| `411-7/` | Verordnung über das Schulgeld für auswärtige Schülerinnen und Schüler an der Kantonsschule, an der Diplommittelschule und an der Berufsvorbereitungsschule (BGS 411.7) | 1 | one version (the oldest available), 25 October 2003 |
| `411-213/` | Reglement über die Anerkennung von Lehrdiplomen für den Unterricht auf der Primarstufe, der Sekundarstufe I und an Maturitätsschulen (BGS 411.213) | 1 | as enacted, 1 January 2020 |
| `412-35/` | Reglement über die Intensivweiterbildung der Lehrpersonen an den gemeindlichen Schulen (BGS 412.35) | 1 | one version (the oldest available), 1 January 2008 |
| `412-111-schulverordnung-schulv/` | Verordnung zum Schulgesetz (BGS 412.111) | 12 | oldest version available, then each consolidated version: 1 August 2011 to 1 August 2025 |
| `412-112-schulreglement-schulr/` | Reglement zum Schulgesetz (BGS 412.112) | 8 | oldest version available, then each consolidated version: 1 August 2008 to 1 August 2026 |
| `412-113-promotionsreglement-promr/` | Reglement über die Promotion an den öffentlichen Schulen (BGS 412.113) | 9 | oldest version available, then each consolidated version: 1 August 2011 to 1 August 2026 |
| `412-114/` | Reglement betreffend das Übertrittsverfahren (BGS 412.114) | 5 | oldest version available, then each consolidated version: 12 July 2008 to 1 August 2022 |
| `412-116/` | Reglement über die Handelsdiplomprüfungen an den privaten Wirtschaftsmittelschulen im Kanton Zug (BGS 412.116) | 1 | as enacted, 1 January 2009 |
| `412-312-schulsubventions-verordnung/` | Verordnung betreffend Pauschalbeiträge an die Besoldungen des gemeindlichen Lehrpersonals (BGS 412.312) | 5 | oldest version available, then each consolidated version: 1 September 2010 to 1 August 2026 |
| `413-12-reglement-bildungszentren/` | Reglement über die Organisation und den Betrieb der Bildungszentren (BGS 413.12) | 6 | oldest version available, then each consolidated version: 1 August 2009 to 1 March 2024 |
| `413-14-reglement-hfw/` | Reglement über die Höhere Fachschule für Wirtschaft (BGS 413.14) | 4 | as enacted, then each consolidated version: 15 October 2011 to 1 October 2026 |
| `413-16/` | Reglement über die Höhere Fachschule für Technik und Gestaltung (HFTG) (BGS 413.16) | 6 | as enacted, then each consolidated version: 1 September 2007 to 1 August 2021 |
| `413-17-reglement-hflw/` | Reglement über die Höhere Fachschule Landwirtschaft (BGS 413.17) | 6 | as enacted, then each consolidated version: 1 August 2012 to 1 January 2024 |
| `413-20-reglement-hfie/` | Reglement über die Höhere Fachschule für Informatik und Elektrotechnik (HFIE) (BGS 413.20) | 1 | as enacted, 28 November 2020 |
| `413-115/` | Verordnung über die Durchführung von Anerkennungsverfahren von nicht eidgenössisch geregelten höheren Bildungsgängen und höheren Bildungseinrichtungen (Höhere Fachschulen) (BGS 413.115) | 1 | as enacted, 1 February 2003 |
| `413-116/` | Verordnung über die Erhebung von Gebühren im Amt für Berufsberatung (BGS 413.116) | 4 | as enacted, then each consolidated version: 1 January 2018 to 1 January 2024 |
| `413-123/` | Verordnung betreffend die Entschädigung für Experten- und Referententätigkeit in der Berufsbildung (BGS 413.123) | 2 | as enacted, then each consolidated version: 1 January 2007 to 1 January 2025 |
| `413-124/` | Reglement für die Förderung von überdurchschnittlichen Leistungen am GIBZ (BGS 413.124) | 2 | as enacted, then each consolidated version: 25 January 2014 to 21 August 2023 |
| `413-171/` | Reglement über die Höhere Berufsbildung Bäuerin (BGS 413.171) | 2 | as enacted, then each consolidated version: 1 August 2014 to 1 January 2018 |
| `414-14/` | Reglement über die Maturitätsprüfungen an den kantonalen und an den anerkannten privaten Gymnasien (BGS 414.14) | 11 | oldest version available, then each consolidated version: 1 August 2011 to 1 August 2026 |
| `414-51/` | Verordnung über die Unterrichtsverpflichtung der Lehrpersonen der Mittel- und Berufsfachschulen sowie der Brückenangebote (BGS 414.51) | 1 | as enacted, 1 August 2016 |
| `414-113-kmv/` | Verordnung über die kantonalen Mittelschulen (BGS 414.113) | 1 | as enacted, 1 August 2024 |
| `414-121/` | Reglement für den Eintritt in die und den Wechsel zwischen den kantonalen Mittelschulen (BGS 414.121) | 3 | as enacted, then each consolidated version: 1 August 2018 to 1 January 2025 |
| `414-143/` | Verordnung betreffend die Entschädigung für Prüfungsexpertinnen und -experten an kantonalen Mittelschulen und an anerkannten privaten Gymnasien (BGS 414.143) | 1 | as enacted, 1 January 2026 |
| `414-151/` | Reglement über die Abschlussprüfungen an der Wirtschaftsmittelschule Zug (BGS 414.151) | 1 | as enacted, 1 August 2011 |
| `414-185/` | Reglement über die Brückenangebote (BGS 414.185) | 6 | as enacted, then each consolidated version: 1 May 2010 to 21 June 2024 |
| `414-191/` | Reglement über die Abschlussprüfungen an der Fachmittelschule (BGS 414.191) | 7 | oldest version available, then each consolidated version: 1 August 2012 to 1 August 2023 |
| `414-312-pvo-hslu/` | Personalverordnung der Hochschule Luzern, FH Zentralschweiz (BGS 414.312) | 2 | as enacted, then each consolidated version: 1 September 2024 to 1 January 2026 |
| `414-313-gebuhrenverordnung-hslu-gebvo-hslu/` | Verordnung über die Gebühren an der Hochschule Luzern, FH Zentralschweiz (BGS 414.313) | 2 | as enacted, then each consolidated version: 1 March 2025 to 1 September 2025 |
| `414-411-ph-verordnung-phv/` | Verordnung zum Gesetz über die Pädagogische Hochschule Zug (BGS 414.411) | 6 | as enacted, then each consolidated version: 1 August 2013 to 1 August 2026 |
| `414-412-phgeb/` | Verordnung über die Gebühren an der Pädagogischen Hochschule Zug (BGS 414.412) | 4 | as enacted, then each consolidated version: 1 August 2013 to 1 January 2024 |
| `414-413-studienreglement-stur/` | Reglement über die Studiengänge der Pädagogischen Hochschule Zug (BGS 414.413) | 8 | as enacted, then each consolidated version: 1 August 2013 to 1 September 2026 |
| `414-511/` | Reglement betreffend die Berücksichtigung von Mehr- und Minderlektionen der Lehrpersonen der kantonalen Schulen (BGS 414.511) | 1 | as enacted, 1 August 2016 |
| `414-611-entschadigung-besondere-aufgaben-lehrpersonen/` | Reglement über die Entschädigung für besondere Aufgaben von Lehrpersonen der Mittelschulen sowie der Berufsfachschulen und des Brückenangebots (BGS 414.611) | 2 | as enacted, then each consolidated version: 1 August 2017 to 1 January 2026 |
| `416-213-ausbv/` | Verordnung zum Gesetz über Ausbildungsbeiträge (BGS 416.213) | 1 | as enacted, 12 September 2025 |
| `416-311-beitrage-fremdsprachenaufenthalt/` | Reglement über die Beiträge für den obligatorischen Fremdsprachenaufenthalt der kantonalen Mittelschulen (BGS 416.311) | 2 | as enacted, then each consolidated version: 1 January 2018 to 6 February 2026 |
| `417-16/` | Verordnung über den Sportfonds (BGS 417.16) | 8 | as enacted, then each consolidated version: 1 January 2006 to 12 April 2024 |
| `432-2-heckenverordnung/` | Verordnung zur Erhaltung und Förderung der Hecken und Feldgehölze (BGS 432.2) | 2 | oldest version available, then each consolidated version: 1 January 1999 to 1 October 2013 |
| `436-1/` | Vollziehungsverordnung zum Tierschutzgesetz (BGS 436.1) | 4 | oldest version available, then each consolidated version: 1 January 2009 to 1 October 2013 |
| `436-1-a1/` | Vollziehungsverordnung zum Tierschutzgesetz (Anhang: Gebührentarif) (BGS 436.1-A1) | 2 | oldest version available, then each consolidated version: 1 January 2012 to 18 May 2013 |
| `446-21/` | Reglement über den Steuerausgleich unter den katholischen Kirchgemeinden des Kantons Zug (BGS 446.21) | 6 | as enacted, then each consolidated version: 5 November 2008 to 1 January 2026 |
| `512-4-vdbap/` | Verordnung über die Dienstgrade und die Beförderung der Angehörigen der Polizei mit hoheitlicher polizeilicher Gewalt (BGS 512.4) | 4 | oldest version available, then each consolidated version: 1 January 2004 to 1 January 2024 |
| `512-14/` | Verordnung über die Ausrüstung der Polizei (BGS 512.14) | 1 | as enacted, 1 January 2008 |
| `512-15/` | Verordnung über Datenbearbeitungssysteme für die Polizei (BGS 512.15) | 4 | as enacted, then each consolidated version: 1 January 2009 to 1 January 2020 |
| `512-22-rayon-verordnung/` | Verordnung über die Festlegung des Wohnsitzrayons für Mitarbeitende der Polizei (BGS 512.22) | 2 | as enacted, then each consolidated version: 1 January 2008 to 25 June 2022 |
| `512-22-a1-anhang-rayon-verordnung/` | Verordnung über die Festlegung des Wohnsitzrayons für Mitarbeitende der Polizei (Anhang: Liste politischer Gemeinden gemäss § 3 Rayon-Verordnung) (BGS 512.22-A1) | 1 | as enacted, 25 June 2022 |
| `512-26/` | Verordnung über den Kostenersatz für polizeiliche Leistungen (BGS 512.26) | 6 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2020 |
| `514-1/` | Verordnung zur Bundesgesetzgebung über Waffen, Waffenzubehör und Munition (BGS 514.1) | 1 | as enacted, 1 July 2010 |
| `521-1/` | Verordnung über die Militärverwaltung (BGS 521.1) | 3 | oldest version available, then each consolidated version: 1 January 2007 to 11 July 2025 |
| `521-4-wpev-zg/` | Verordnung über die Wehrpflichtersatzabgabe (BGS 521.4) | 4 | oldest version available, then each consolidated version: 1 January 2010 to 11 July 2025 |
| `521-811/` | Verordnung über den zugerischen Winkelriedfonds (BGS 521.811) | 3 | oldest version available, then each consolidated version: 1 January 2000 to 11 July 2025 |
| `531-11/` | Verordnung zum Einführungsgesetz betreffend Zivilschutz (BGS 531.11) | 4 | as enacted, then each consolidated version: 1 August 2011 to 11 July 2025 |
| `531-14/` | Verordnung über die Alarmorganisation in Friedenszeiten (BGS 531.14) | 1 | one version (the oldest available), 1 August 2011 |
| `531-111/` | Reglement über die Steuerung des Schutzraumbaus im Kanton Zug (BGS 531.111) | 1 | as enacted, 1 January 2026 |
| `611-11-fhv/` | Finanzhaushaltverordnung (BGS 611.11) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 7 November 2020 |
| `611-35-vsri/` | Verordnung über die Sicherung und Rückerstattung von Investitionsbeiträgen an Dritte (BGS 611.35) | 2 | as enacted, then each consolidated version: 1 July 2012 to 1 January 2019 |
| `612-11-covid-19-stutzungsfondsverordnung/` | Verordnung zur Errichtung eines Stützungsfonds in Folge des Coronavirus (BGS 612.11) | 1 | as enacted, 10 April 2020 |
| `612-12-covid-19-kreditverordnung/` | Verordnung zur Bewilligung des Kredits für die kantonale Verwaltung und die Gerichte zur Bewältigung der Auswirkungen des Coronavirus (BGS 612.12) | 4 | as enacted, then each consolidated version: 1 March 2020 to 1 January 2022 |
| `612-14-covid-19-lotterie-und-sportfondsverordnung/` | Verordnung zur Äufnung des Lotteriefonds und des Sportfonds in Folge des Coronavirus (BGS 612.14) | 4 | as enacted, then each consolidated version: 10 April 2020 to 1 January 2022 |
| `612-17/` | Verordnung zur Umsetzung der Covid-19-Kulturverordnung (BGS 612.17) | 2 | as enacted, then each consolidated version: 26 September 2020 to 19 December 2020 |
| `612-18-covid-19-hartefallverordnung/` | Verordnung über Härtefallmassnahmen für Unternehmen in Zusammenhang mit der COVID-19-Epidemie (BGS 612.18) | 2 | oldest version available, then each consolidated version: 1 December 2020 to 1 April 2021 |
| `612-19-covid-19-hartefallverordnung-2022/` | Verordnung über Härtefallmassnahmen für Unternehmen im Zusammenhang mit der COVID-19-Epidemie im Jahr 2022 (BGS 612.19) | 1 | as enacted, 2 March 2022 |
| `612-141/` | Reglement zur Beurteilung von Gesuchen zu Unterstützungsmassnahmen im Bereich Sport gemäss Verordnung zur Äufnung des Lotteriefonds und des Sportfonds in Folge des Coronavirus (COVID-19-Lotterie- und Sportfondsverordnung) (BGS 612.141) | 6 | as enacted, then each consolidated version: 19 May 2020 to 12 March 2022 |
| `632-11/` | Verordnung zum Steuergesetz (BGS 632.11) | 6 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2022 |
| `632-12-ves/` | Verordnung über die elektronische Einreichung der Steuererklärung (BGS 632.12) | 1 | as enacted, 1 January 2026 |
| `632-15/` | Verordnung über die Verlustscheinbewirtschaftung für die kantonale Verwaltung und die Gerichte (BGS 632.15) | 1 | as enacted, 1 July 2012 |
| `632-15-a1/` | Verordnung über die Verlustscheinbewirtschaftung für die kantonale Verwaltung und die Gerichte (Anhang) (BGS 632.15-A1) | 2 | as enacted, then each consolidated version: 1 July 2012 to 1 July 2013 |
| `711-11-ev-rpg/` | Dringliche Einführungsverordnung zum Bundesgesetz über die Raumplanung (BGS 711.11) | 1 | as enacted, 1 August 2026 |
| `721-53-subv/` | Submissionsverordnung (BGS 721.53) | 6 | oldest version available, then each consolidated version: 1 January 2012 to 1 March 2024 |
| `721-61-v-gnu/` | Verordnung zum Gesetz über die Nutzung des Untergrunds (BGS 721.61) | 1 | as enacted, 1 January 2019 |
| `721-111-v-pbg/` | Verordnung zum Planungs- und Baugesetz (BGS 721.111) | 4 | oldest version available, then each consolidated version: 1 July 2012 to 1 February 2026 |
| `722-111-vo-gebvg/` | Verordnung zum Gesetz über die Gebäudeversicherung (BGS 722.111) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2018 |
| `722-114-lohneinreihungs-und-entschadigungsreglement-gvzg-ler-gvzg/` | Reglement betreffend Lohneinreihung und Entschädigungen von Mitarbeitenden der Gebäudeversicherung Zug (BGS 722.114) | 2 | as enacted, then each consolidated version: 1 January 2024 to 1 August 2025 |
| `722-211-feuerschutzverordnung-fsv/` | Verordnung zum Gesetz über den Feuerschutz (BGS 722.211) | 5 | oldest version available, then each consolidated version: 1 December 2009 to 1 January 2023 |
| `722-212-feuerschutzreglement-fsr/` | Reglement zum Gesetz über den Feuerschutz (BGS 722.212) | 3 | as enacted, then each consolidated version: 1 January 2023 to 1 May 2026 |
| `731-11-v-gewg/` | Verordnung zum Gesetz über die Gewässer (BGS 731.11) | 2 | oldest version available, then each consolidated version: 1 October 2009 to 3 March 2012 |
| `732-22/` | Reglement über die Abfallbewirtschaftung des Zeba (BGS 732.22) | 6 | as enacted, then each consolidated version: 1 July 2005 to 1 January 2026 |
| `732-22-a1/` | Reglement über die Abfallbewirtschaftung des Zeba (Anhang) (BGS 732.22-A1) | 5 | as enacted, then each consolidated version: 1 July 2005 to 1 January 2025 |
| `732-26-gebuhrenreglement-des-zeba/` | Reglement über die Gebühren für Siedlungs- und siedlungsabfallähnliche Abfälle sowie kleine Mengen von Sonderabfällen (BGS 732.26) | 3 | as enacted, then each consolidated version: 14 June 2005 to 1 January 2023 |
| `732-26-a1-gebuhrenreglement-des-zeba/` | Reglement über die Gebühren für Siedlungs- und siedlungsabfallähnliche Abfälle sowie kleine Mengen von Sonderabfällen (Anhang) (BGS 732.26-A1) | 6 | as enacted, then each consolidated version: 14 June 2005 to 1 January 2026 |
| `740-11-v-eng-zg/` | Verordnung zum Energiegesetz (BGS 740.11) | 8 | oldest version available, then each consolidated version: 1 January 2009 to 1 February 2024 |
| `740-161/` | Verordnung zum Kantonsratsbeschluss betreffend Rahmenkredit zur Förderung von Massnahmen für geringeren Energiebedarf (BGS 740.161) | 1 | as enacted, 9 January 2010 |
| `740-162-v-krb-energiebeitrage-ii/` | Verordnung zum Kantonsratsbeschluss betreffend zweiten Rahmenkredit zur Förderung von Massnahmen für geringeren Energiebedarf (BGS 740.162) | 1 | as enacted, 5 May 2012 |
| `751-21/` | Verordnung über den Strassenverkehr und die Strassensignalisation (BGS 751.21) | 7 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2020 |
| `751-21-a1/` | Verordnung über den Strassenverkehr und die Strassensignalisation (Anhang 1) (BGS 751.21-A1) | 1 | as enacted, 1 January 2016 |
| `751-141-v-gsw/` | Verordnung zum Gesetz über Strassen und Wege (BGS 751.141) | 2 | oldest version available, then each consolidated version: 1 January 1999 to 1 January 2012 |
| `751-221-vo-gs/` | Verordnung über die Gebühren im Strassenverkehr (BGS 751.221) | 6 | as enacted, then each consolidated version: 1 January 2006 to 1 January 2026 |
| `751-222-knv/` | Verordnung über die Kontrollschildnummern (BGS 751.222) | 3 | as enacted, then each consolidated version: 1 January 2018 to 7 July 2023 |
| `751-312/` | Einführungsverordnung zur Verordnung des Bundes über die Personenbeförderung (BGS 751.312) | 1 | one version (the oldest available), 1 January 2010 |
| `753-3-bootsstationierungsverordnung-bsvo/` | Verordnung über die Inbetriebnahme und das Stationieren von Booten (BGS 753.3) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 October 2023 |
| `753-5/` | Verordnung über das Drachensegeln auf den Gewässern des Kantons Zug (BGS 753.5) | 2 | oldest version available, then each consolidated version: 23 January 2010 to 15 February 2016 |
| `753-6/` | Verordnung über das Wakeboarden und andere vergleichbare Wassersportarten auf dem Zuger- und dem Ägerisee (BGS 753.6) | 1 | one version (the oldest available), 6 May 2006 |
| `753-11-schiffsgebuhrenverordnung-sgv/` | Verordnung über die Gebühren im Schiffsverkehr (BGS 753.11) | 4 | as enacted, then each consolidated version: 1 January 2006 to 1 October 2023 |
| `753-12-v-eg-bsg/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Binnenschifffahrt (BGS 753.12) | 1 | as enacted, 29 February 2020 |
| `753-32-einwasserungsverordnung/` | Verordnung über das Einwassern von Booten (BGS 753.32) | 2 | as enacted, then each consolidated version: 12 April 2024 to 1 March 2025 |
| `754-1/` | Kantonale Vollziehungsverordnung zum Bundesgesetz über die Luftfahrt (BGS 754.1) | 2 | as enacted, then each consolidated version: 7 May 1951 to 1 January 2011 |
| `811-11-v-eg-usg/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über den Umweltschutz (BGS 811.11) | 4 | oldest version available, then each consolidated version: 1 October 2009 to 1 January 2020 |
| `816-1-v-chemg/` | Verordnung über den Vollzug der eidgenössischen Chemikaliengesetzgebung (BGS 816.1) | 2 | as enacted, then each consolidated version: 1 October 2009 to 1 January 2012 |
| `821-11-gesundheitsverordnung-gesv/` | Verordnung über das Gesundheitswesen im Kanton Zug (BGS 821.11) | 10 | as enacted, then each consolidated version: 11 July 2009 to 26 June 2021 |
| `821-13/` | Verordnung über das Krebsregister (BGS 821.13) | 2 | as enacted, then each consolidated version: 1 January 2011 to 19 December 2020 |
| `821-18-nareg-vo/` | Verordnung zum Register über die Gesundheitsfachpersonen NAREG (BGS 821.18) | 3 | as enacted, then each consolidated version: 1 January 2017 to 1 February 2022 |
| `822-11-v-eg-fap/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (BGS 822.11) | 1 | as enacted, 20 September 2024 |
| `822-111-reglement-fap/` | Reglement über die Durchführung des Beitragswesens im Rahmen der Förderung der Ausbildung im Bereich der Pflege (BGS 822.111) | 1 | as enacted, 20 September 2024 |
| `823-2-heilmittelverordnung-hmv/` | Verordnung über den Verkehr mit Heilmitteln (BGS 823.2) | 3 | as enacted, then each consolidated version: 11 July 2009 to 26 June 2021 |
| `824-2-vv-lmg/` | Vollziehungsverordnung zum Bundesgesetz über Lebensmittel und Gebrauchsgegenstände (BGS 824.2) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 15 April 2013 |
| `824-4-reglement-qualitatsbescheinigung-rqb/` | Reglement zur Qualitätsbescheinigung über die lebensmittelrechtliche Sicherheit (BGS 824.4) | 1 | as enacted, 1 October 2009 |
| `825-31/` | Vollziehungsverordnung zum Bundesgesetz über die Bekämpfung übertragbarer Krankheiten des Menschen (BGS 825.31) | 4 | oldest version available, then each consolidated version: 1 October 2009 to 1 January 2025 |
| `826-113-langzeitpflege-verordnung-lpfv/` | Verordnung über die stationäre und ambulante Langzeitpflege (BGS 826.113) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2015 |
| `826-251/` | Verordnung über die Anpassung der Mutterschaftsbeiträge an die Preisentwicklung (BGS 826.251) | 4 | as enacted, then each consolidated version: 1 January 2019 to 1 January 2025 |
| `831-1/` | Vollziehungsverordnung zum Bundesbeschluss über die Allgemeinverbindlicherklärung von Gesamtarbeitsverträgen (BGS 831.1) | 1 | as enacted, 19 November 1941 |
| `832-1/` | Reglement der tripartiten Kommission Arbeitsmarkt (BGS 832.1) | 1 | as enacted, 1 June 2004 |
| `834-17/` | Reglement über das kantonale Kontrollorgan im Bereich der Bekämpfung der Schwarzarbeit («Pflichtenheft») (BGS 834.17) | 2 | as enacted, then each consolidated version: 1 July 2009 to 1 January 2018 |
| `834-211/` | Verordnung zum EG Entsendegesetz (BGS 834.211) | 1 | one version (the oldest available), 1 June 2004 |
| `841-11/` | Verordnung zum Einführungsgesetz zu den Bundesgesetzen über die Alters- und Hinterlassenenversicherung und die Invalidenversicherung (BGS 841.11) | 2 | as enacted, then each consolidated version: 6 July 1993 to 14 September 2019 |
| `841-712/` | Verordnung über die maximal anrechenbaren Kosten für Tagestaxen bei den Ergänzungsleistungen (BGS 841.712) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2021 |
| `841-714-elkv/` | Verordnung über die Vergütung von Krankheits- und Behinderungskosten bei den Ergänzungsleistungen (BGS 841.714) | 1 | one version (the oldest available), 6 September 2008 |
| `841-714-a1-elkv/` | Verordnung über die Vergütung von Krankheits- und Behinderungskosten bei den Ergänzungsleistungen (Anhang: Liste der Hilfsmittel, Pflegehilfs- und Behandlungsgeräte (§ 19 Abs. 1) (BGS 841.714-A1) | 1 | as enacted, 1 January 2008 |
| `842-5/` | Vollziehungsverordnung zum Bundesgesetz über die Unfallversicherung (BGS 842.5) | 1 | one version (the oldest available), 1 January 2009 |
| `842-11-v-eg-kvg/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Krankenversicherung (BGS 842.11) | 3 | as enacted, then each consolidated version: 6 July 2013 to 1 January 2025 |
| `842-13-zulassungsverordnung/` | Verordnung über die Zulassung von Ärztinnen und Ärzten im ambulanten Bereich (BGS 842.13) | 3 | as enacted, then each consolidated version: 11 March 2017 to 1 January 2026 |
| `842-13-a1-zulassungsverordnung/` | Verordnung über die Zulassung von Ärztinnen und Ärzten im ambulanten Bereich (Anhang) (BGS 842.13-A1) | 1 | as enacted, 1 July 2023 |
| `842-61/` | Verordnung zum Gesetz betreffend individuelle Prämienverbilligung in der Krankenpflegeversicherung (BGS 842.61) | 2 | as enacted, then each consolidated version: 1 January 2018 to 1 January 2021 |
| `844-412/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Familienzulagen (BGS 844.412) | 5 | oldest version available, then each consolidated version: 5 September 2009 to 1 January 2025 |
| `845-1/` | Verordnung zum Bundesgesetz über die Arbeitsvermittlung und den Personalverleih (BGS 845.1) | 1 | as enacted, 1 December 1999 |
| `851-212-wohnraumforderungsverordnung-wfv/` | Verordnung über die Förderung von preisgünstigem Wohnraum (BGS 851.212) | 1 | one version (the oldest available), 1 August 2010 |
| `861-41-sozialhilfeverordnung/` | Verordnung zum Sozialhilfegesetz (BGS 861.41) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2024 |
| `861-42/` | Verordnung betreffend Sozialhilfe für Personen aus dem Asylbereich (BGS 861.42) | 4 | as enacted, then each consolidated version: 1 July 2009 to 1 April 2026 |
| `861-512-lbbv/` | Verordnung über Leistungen für Menschen mit Behinderung und Betreuungsbedarf (BGS 861.512) | 4 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2024 |
| `861-514-reglement-eigenleistung-rege/` | Reglement über die Eigenleistungen im Rahmen des Gesetzes über Leistungen für Menschen mit Behinderung und Betreuungsbedarf (BGS 861.514) | 8 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `911-1/` | Verordnung über die Organisation und die Aufgaben der wirtschaftlichen Landesversorgung (BGS 911.1) | 3 | oldest version available, then each consolidated version: 1 August 2002 to 1 January 2020 |
| `915-21-standortentwicklungsverordnung-sevo/` | Vollziehungsverordnung zum Gesetz über Standortentwicklung (BGS 915.21) | 3 | as enacted, then each consolidated version: 1 January 2026 to 3 April 2026 |
| `921-11/` | Verordnung zum Einführungsgesetz Landwirtschaft (BGS 921.11) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 August 2020 |
| `921-12/` | Verordnung zum Vollzug der landwirtschaftlichen Deklarationsverordnung (BGS 921.12) | 1 | one version (the oldest available), 1 January 2009 |
| `921-15/` | Verordnung über die Überwachung und Bekämpfung von schädlichen Organismen (BGS 921.15) | 2 | as enacted, then each consolidated version: 7 July 2007 to 1 January 2021 |
| `921-153/` | Reglement über die Vergütungen für angeordnete Überwachungs- und Bekämpfungsmassnahmen von schädlichen Organismen (BGS 921.153) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 May 2022 |
| `922-31/` | Reglement zum Ressourcenprojekt Ammoniak der Zentralschweizer Kantone Uri, Schwyz, Obwalden, Nidwalden und Zug (BGS 922.31) | 2 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2013 |
| `924-25/` | Reglement über die kontrollierte Ursprungsbezeichnung für Weine (BGS 924.25) | 1 | as enacted, 1 July 2009 |
| `925-11/` | Vollziehungsverordnung zum Tierseuchengesetz (BGS 925.11) | 3 | oldest version available, then each consolidated version: 1 January 2012 to 19 December 2015 |
| `925-161/` | Verordnung über den Entschädigungsfonds für Tierverluste (BGS 925.161) | 2 | oldest version available, then each consolidated version: 1 January 1999 to 1 October 2012 |
| `925-161-a1/` | Verordnung über den Entschädigungsfonds für Tierverluste (Anhang 1: Entschädigungspauschalen bei unmittelbaren Folgen von Präventionsmassnahmen) (BGS 925.161-A1) | 1 | as enacted, 1 October 2012 |
| `932-11-jagdverordnung/` | Verordnung über die Jagd und den Schutz wildlebender Säugetiere und Vögel (BGS 932.11) | 6 | oldest version available, then each consolidated version: 1 April 2010 to 30 June 2023 |
| `932-13/` | Reglement über die Jagdausbildung und -prüfung (BGS 932.13) | 5 | as enacted, then each consolidated version: 1 June 2000 to 1 July 2019 |
| `933-112/` | Reglement über die Zulassungs- und Vergabekriterien für die Berufsfischerei auf dem Zugersee (BGS 933.112) | 1 | as enacted, 1 August 2019 |
| `933-211/` | Verordnung über die Fischerei (BGS 933.211) | 6 | oldest version available, then each consolidated version: 1 January 2009 to 29 October 2022 |
| `942-11/` | Vollziehungsverordnung zur Bundesgesetzgebung über das Messwesen (BGS 942.11) | 3 | oldest version available, then each consolidated version: 1 January 1999 to 1 January 2019 |
| `942-51-ksprstv/` | Kantonale Sprengstoffverordnung (BGS 942.51) | 2 | as enacted, then each consolidated version: 1 January 2012 to 3 March 2018 |
| `942-461-kantonale-geldspielverordnung-v-eg-bgs/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über Geldspiele (BGS 942.461) | 2 | as enacted, then each consolidated version: 1 July 2023 to 12 April 2024 |

## Source

The BGS (systematic collection) of the canton, published by the canton at <https://bgs.zg.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (GS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the canton's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (GS), with an e-mail address that cannot exist (`<act key>@bgs.zg.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
