# DevOps

Randomisierte Gedanken über DevOps und Software-Entwicklung.

## Wie Software entsteht

Wie jedes herkömmliche Produkt auch wird Software erstellt, um ein bestimmtes Problem zu lösen oder 
aber zumindest einfacher/erträglicher zu machen. Einige Beispiele:

__Problem:__ Das Waschen von Hand ist aufwändig und anstrengend

__Produkt/Lösung:__ Waschmaschine

__Problem:__ Man kennt keine Webseite zum bestimmten Thema 

__Produkt/Lösung:__ Suchmaschine aka Google

Weiterhin können Produkte/Software auch nur der Unterhaltung dienen (Spielzeug, Videospiele, etc.).
Zentral wichtig ist aber, dass jedes Produkt bzw. jede Software ein klar definiertes Ziel hat, das
am Ende des Tages dem Kunden echten Mehrwert bietet. Erst wenn dieses Ziel feststeht und überzeugend
ist, sollte mit der Entwicklung der Software begonnen werden. Doch wie genau entsteht Software. Im
Gegensatz zum Glauben vieler ist das eigentliche Entwickeln des Programmcodes, das oft einfach als
Software-Entwicklung bezeichnet wird, nur ein einzelner (wenn auch integraler) Teil einer weitaus
längeren Prozesskette (zur Unterscheidung nachfolgend auch Produkt-Entwicklung genannt). Diese soll
nachfolgend beschrieben werden.

### Anforderungen

Steht das Ziel fest, müssen die Anforderungen an die Software klar definiert werden. Im 
Waschmaschinen-Beispiel von oben wäre eine Anforderungen zum Beispiel ein Waschgang für Feinwäsche.
Für Software definieren Anforderungen ebenfalls die Funktionen des Produkts, aber auch zum Beispiel
welche Betriebssysteme unterstützt werden sollen. Ohne klar definierte Anforderungen kann die
Produkt-Entwicklung nicht beginnen, da ansonsten die Gefahr besteht "an den Kunden vorbei" zu
entwickeln.

### Software-Entwicklung (das Schreiben des Programmcodes)

Auf Basis der Anforderungen kann begonnen werden, den Programmcode zu entwickeln, der später das 
Produkt, d.h. die Software, bildet. Dieser Schritt der Produktionskette wird von
Software-Entwicklern übernommen und ist zweifelsfrei ein enorm wichtiger und kritischer Abschnitt
innerhalb der Prozesskette. Das Schreiben von sicheren, performanten und wartbaren
Programmcodes ist eine Kunst für sich, die nicht ohne Grund eine eigene Wisschenschaft (Informatik)
beistzt und unzählige Fachbücher zum Thema hervorgebracht hat. Trotzdem bleibt der beste Code nur
ein Teil der Prozesskette und ist wertlos ohne die anderen Teile.

### Tests und Qualitätssicherung

Genauso wie jedes produzierte Auto durchgehend auf Sicherheit und Funktion getestet wird, bevor es
die Fabrik verlässt, muss auch Software vor dem Ausrollen durchgehend überprüft werden. Im Gegensatz
zum Auto stehen im Falle der Software bei Fehlfunktion häufig nicht direkt Menschenleben auf dem
Spiel. Dennoch kann fehlerhafte Software enorme wirtschaftliche Kosten verursachen. Bei kritischen
System kann das gesamte Unternehmen gefährdet sein.

### Deployment

Ist der Programmcode geschrieben und getestet, generiert er nach wie vor kein Mehrwert. Dies kann
erst geschehen, wenn das Programm auch ausgerollt wird (Deployment). Erst jetzt, wenn die Software
produktiv eingesetzt wird, kann sie ihren Zweck erfüllen und für den Kunden den Mehrwert erbringen,
der durch das anfängliche Ziel definiert wurde.

### Wartung

Sobald die Software produktiv ist, muss ein reibungsfreier Betrieb sichergestellt werden. Hierzu
müssen zum Beispiel die Server und die Programmperformance überwacht werden, damit im Fehlerfall
reagiert werden kann, um hohe Kosten und/oder unzufriedene Kunden zu vermeiden.

Ausgehend vom Ziel/der Idee für die Software sind die obigen fünf Abschnitte innerhalb der
Produkt-Entwicklung immer vorhanden und bilden erst zusammen die eigentliche Software-Entwicklung.
Egal welche Software, wird auch nur einer der obigen Schritte innerhalb der Prozesskette nicht
ausgeführt, kommt es zu keinem Produkt, das beim Kunden und der entwicklenden Firma Mehrwerte
generiert. D.h. auch (um es nochmal zu verdeutlichen), dass das Schreiben des Programmcodes alleine
und ohne die anderen Schritte wertlos ist!

Nachfolgend soll nun gezeigt werden, wie das klassische Modell für die Software-Entwicklung, das
Wassermodell, den obigen Prozess abbildet. Auf Basis dessen soll geklärt werden, wo die Probleme
dieses Ansatzes liegen und wie die Probleme mit einfachen Methoden gelöst werden können. Dadurch
sollte klar werden, was DevOps ist und wie es helfen will qualitative Software und damit glückliche
Kunden und Mitarbeiter zu schaffen.

## Das Wasserfall-Modell

TODO

### Probleme

Das Wasserfallmodell besitzt ein integrales Problem. Die Informationen fließen immer nur von oben
nach unten von der einen Abteilung in die nächste. Entscheidungen und Entwicklungen werden "oben"
ohne Wissen und Expertise "von unten" gemacht. Gleichzeitig wird häufig die Übergabe in den nächsten
Schritt/die nächste Abteilung als Abschluss der Arbeit der vorigen angesehen. Dadurch staut sich
weiter unten ein zunehmend großer Berg an Problemen auf, der den Abbruch des Entwicklung und das
Ende des Produkts (und potenziell der Firma) bedeutet kann.

Ein nur allzu häufig eingetretenes Beispiel-Szenario: Bei der Planung und Formulierung der
Anforderungen wurden aufgrund der Komplixtät des Projekts unwissend unrealistische und subtoptimale
Entscheidung getroffen worden. Später, beim Schreiben des Programmcodes, kommt es dadurch zu
schlechtem Code, der bei der Qualitätssicherung durchgehend durch unzählie Fehler und
Performanceprobleme auffällt. Dieser wird dann bis zum Ende der geplanten Entwicklungszeit in einen 
halbsweg stabilen Zustand gebracht, bis dann am Release-Tag die für das Deploment zuständige
Abteilung zum ersten Mal vom Produkt hört. Das Deployment geht natürlich schief und es kommt zu 
Verzögerungen und verärgerten Kunden. Nach diversen Verschiebungen steht ein mindertwertiges
Produkt, das der Support für Jahre für verärgerte Kunden warten darf. Wenig verwunderlich kommt es
zu Grabenkämpfen zwischen den Abteilungen, während man sich gegenseitig die Schuld zuschiebt. Die
Moral der Belegschaft sinkt, was sich unmittelbar auf die ohnehin niedrige Qualität der Software
auswirkt.

## Ein besserer Ansatz

TODO