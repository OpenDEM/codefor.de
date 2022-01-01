---
title: "Dezember 2021 – Die log4j-Sicherheitslücke und ihre Folgen"
author: "Tim Fangmeyer & Knut Hühne - OK Lab Berlin, Klara Juhl - OK Lab Osnabrück"
date: '2021-12-30T19:45:00+01:00'
excerpt: Monatlich erscheinender Überblick über Entwicklungen in der Open Data und Civic Tech Szene
topic: community
images:
- imgname: out-in-the-open-2021-12-header.jpg
  attribution: Foto von [Prateek Katyal](https://unsplash.com/@prateekkatyal) auf [Unsplash](https://unsplash.com/photos/H5jDIP0wLuA)
og_image: out-in-the-open-2021-12-header.jpg
type: blog
---
Hatten wir im letzten Monat noch recht abstrakt einige Artikel über die Nachteile der modernen IT-Infrastruktur verlinkt, die in großen Teilen auf der kaum wertgeschätzten Arbeit von wenigen Open Source-Entwickler:innen beruht, erhielt das Thema [mit der Entdeckung der gravierenden Log4j-Schwachstelle](https://www.spiegel.de/netzwelt/web/log4-j-schwachstelle-ja-leute-die-scheisse-brennt-lichterloh-a-760bd03d-42d2-409c-a8d2-d5b13a9150fd) eine sehr konkrete Dimension: Plötzlich wurde Open Source und dessen (mangelnde) Förderung auch in den deutschen Medien [wie der FAZ](https://www.faz.net/aktuell/wirtschaft/digitec/sicherheitsluecke-log4j-was-spricht-fuer-und-gegen-freie-software-17684344.html) oder [dem Bayrischen Rundfunk](https://www.br.de/nachrichten/netzwelt/log4j-sicherheitsluecke-der-ruf-nach-open-source-foerderung,SrZk0fP) diskutiert. Für das Jahr 2022 hegen wir den Wunsch, dass die Debatte über die Wertschätzung Freier Software und Offener Daten noch breiter geführt wird – und das, ohne dafür einen negativen Auslöser wie die Log4j-Schwachstelle zu benötigen.

Wer die Worte Open Source hört, denkt wahrscheinlich erst einmal an Software, deren Quelltext öffentlich und von Dritten eingesehen werden kann, zum Beispiel Linux. Deutlich weniger bekannt ist, dass auch Hardware entlang des Open Source-Leitgedankens entwickelt werden kann: Darunter versteht man u. a., Baupläne, Anleitungen und Konstruktionsdateien unter einer offenen Lizenz zu veröffentlichen, wie Lukas Winter in seinem Artikel [Open Source-Hardware: Mehr Wissen durch Teilen](https://www.lindau-nobel.org/de/blog-open-source-hardware) berichtet. Einen spannenden Einstieg, wie man mit Open Source-Hardware nachhaltig plant und gestaltet, bietet auch der Text von Maximilian Voigt, Dr. Daniel Wessolek, Ronald Eikenberg und Tim Gerber, [der hinter der Bezahlschranke von heise liegt](https://www.heise.de/hintergrund/Open-Source-Hardware-Unterschaetze-Nischenprodukte-6302230.html).

Das [offizielle Lobbyregister](https://www.landtag.sachsen-anhalt.de/landtag/lobbyregister) des Landtages von Sachsen-Anhalt wird derzeit in einer PDF-Datei veröffentlicht. Dies erschwert Recherchen und das Verknüpfen von Datensätzen. [Stefan Weißwange](https://rifter.org/) hat das Register nun in eine digitale Form überführt und auf einer [separaten Plattform](https://lobbyregister-sachsen-anhalt.de/) publiziert. "Ich will zeigen, dass man mit Daten sehr viel mehr anfangen kann, wenn man sie in einem sinnvollen und maschinenlesbaren Format veröffentlicht, statt in einer PDF-Datei", [zitiert ihn der MDR](https://www.mdr.de/nachrichten/sachsen-anhalt/landespolitik/digitales-lobbyregister-transparenz-weisswange-100.html). Die Plattform listet die Datensätze und dazugehörige Kurzinformationen nicht nur auf, sondern zeigt darüber hinaus, welche Organisationen und Personen im offiziellen Lobbyregister des Landtages fehlen.

"Sensordaten von und für Berlin" lautet das Motto von [Stadtpuls](https://stadtpuls.com/) – einer offenen Plattform für die Erfassung, Visualisierung und Bereitstellung von Sensordaten in der deutschen Hauptstadt. Jede:r kann eigene Sensoren digital mit der Plattform verbinden und so die Daten einspeisen. Die Sensordaten werden anschließend kostenlos und im maschinenlesbaren Format bereitgestellt und können so für weitere Projekte und Auswertungen verwendet werden.

Die Anzahl an Seiten die offene Daten bereitstellen wächst mit jedem Jahr etwas mehr. Die Größe der Anbieter reicht von Kleinstädten wie [Moers](https://www.offenesdatenportal.de/organization/moers) bis hin zu auf Bundesebene angesiedelten Portalen wie [Govdata](https://www.govdata.de/). Ein Aspekt, der bei der Bereitstellung von Daten leider oft hinten ansteht, ist die Benutzerfreundlichkeit einer Webseite (engl. usability). Unter dem Begriff lassen sich verschiedenste Aspekte, von der einfachen Auffindbarkeit von bestimmten Informationen bis hin zur Barrierefreiheit, zusammen fassen. Die Agentur [interaktionswerk hat sich am Beispiel der Open Data-Seite opendata.swiss exemplarisch an einem solchen UX Review versucht.](https://interaktionswerk.ch/blog/was-ein-ux-review-kann-am-beispiel-von-opdendata-swiss/)

Der Präsident der [FSFE](https://fsfe.org/index.de.html) Matthias Kirschner hat ein Kinderbuch geschrieben: "[Ada & Zangemann - Ein Märchen über Software, Skateboards und Himbeereis](https://fsfe.org/news/2021/news-20211129-01.de.html)". Die liebevoll illustrierte Geschichte erzählt von einem allesbeherrschenden Technik-Monopolisten und von der kleinen Heldin Ada, die sich von diesem nicht unterkriegen lassen möchte. Das Konzept der freien Software wird kindgerecht und in einfacher Sprache vermittelt und somit auch Menschen ohne tiefergehende IT-Kenntnisse zugänglich gemacht. Eine weitere Besonderheit: Das Buch ist unter der offenen Lizenz "CC BY-SA 3.0" erschienen.

## Uns sonst so?
Man sollte glauben in der deutschen Hauptstadt sei bereits alles, von Graffiti bis hin zu Flohmärkten, mehrfach kartiert und verbloggt. Aber nein, auch in Berlin befanden sich bis jetzt noch weiße Flecken auf der Stadtkarte, zumindest wenn es um Ziegen geht. Die Seite [Goats of Berlin](https://goatsofberlin.com/) bietet eine Übersicht aller besuchbaren Ziegengehege im Stadtraum. Vervollständigt wird die Seite von detaillierten Beschreibungen der Minizoos und Schnappschüssen der besonders bei Kindern beliebten Paarhufer.