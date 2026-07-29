# gespräch christopher, 9.1.2025

- preisrahmen
    - 40-50.000 Euro

- scope
    - plattform team und 1-3 produkte

- out of scope, Fokus!
    - Communicator

- einladung zum Agile leader summit
    - cra

- februar
- rückmeldung bis mittwoch
- realistisch morgen

# infos sebastian frühling

cyber resiliance act ist alles noch sehr im fluss, auch gesetzgebung

wir können aktuell eine selbsteinschätzung abgeben lassen und über kritische punkte sprechen, ein code review darauf hin haben wir aktuell nicht 

angebot:
    - 2h gespräch mit sparringspartner, cra schnelltest
    - nebenbei drin

# interne besprechung, 8.1.2025

- timm, fahd, ingo, tobias schmitt-lechner

- für c# sqi messen
- c++ mit anderen metriken untersuchen
- sonargraph kann auch c++, ingo bestellt

- für c++
    - aktuell nicht?: zyklen, ACD?

- c++
    - wir sind nicht experten, wie manuell bewerten?
    - embedded
    - nicht zu groß, nciht zu viele ifs, sinnvolle benennung, solid, testbarkeit, test testet wirklich was
    - spezifika
    - stichproben
        - nummerieren
        - "hier x nicht eingehalten"
    - embedded c++
        - eigene sub sprache

- tobias SL
    - c++ embedded noch nicht programmiert

- andere leute die wir dazu holen?
    - felix ulmer, embedded erfahrung

- an christopher
    - wir prüfen ob sw analysetools auf embedded c++
    - mehr informationen zur verwendeten c++ version
    - memory allokation verwendet
    - fehler (produktiv) der letzten 3 monate
    - wenn keine architektur metriken
        - mehr von hand malen
        -> architektur dokumentation
            - use cases der plattform
    - dora metriken, wie lange dauern änderungen

- aufwand code review
    - 10 Tage dauer, x2? Personen

- cyber resilience act
    - erstmal ausklammern? auf jeden fall trennen
    - sebastian frühling fragen -> fahd

- vorgespräch mit ingo+felix+tobias

- im märz anderes assessment, auftrag schon fix

- kosten schätzung
    - umfang prozessanalyse
        - teams nicht zu groß
        - plattform und 1 produkt
    - 20 PT

- erstmal außerhalb
    - communicator
    - cyber resilience act

# besprechung 17.12.2024

Christopher Gehrig
- seit 8 monaten bei bürkert
- team embedded core modules übernommen
- zzentrales team aus 15 soft 3 hardware entwicklern
- pflegen und warten embeddded systems architecture
    - rbos, ckmbos, stmicroelectronics
    - common modules, für interne kunden
    - software und standardisierung
    - anshclie´ßend vewrschiedene produktlinien
        - die applikation mechanik, elektronik, software für kunden fertigstellen
        - die verwende esa, bauen user area auf , bauen dann endprodukt
- mit c übernahme des teams ziele entstadnen
    - überarbetiung dr platfornm
    - vor 12 jarhen fertig gestellt
    - c++
    - idee: neu aufsetzten
        - cybersecurity
        - über die jahre bereitgestellt
        - aber meinungsverschiedenheiten
            - teilw eigene süppchen
    - 4 produktlinien verwenden plattform
    - andere systemhäuser verwenden die auch
    - wandert schrittweise auseinander
    - architektur, code wiederverwendung

- kompletter prozess und code: review
    - prozessanalyse, ist-stand
    - anwendung/leben des prozesses mit leben füllen
        - interviews mit teams
    - code ebene
        - cyber resilience act
        - cyber security
    - 1-3 geräte
        - positiv und negativ beispiele
        - review auf code ebene

- wie auf andrena gekommen
    - dr gribner, sein vorgesetzter
    - johannes bauer, im februar, kollege, einarbeitungspate

- microprozessoren
    - hauptsächlich h5 und u5 stm32
    - alte f4, f103

- platform als kompaktversion in c
    - läuft auf f0, g0, u0
    - nicht alt, aber abgespeckt

- warum "plattform"
    - jedes gerät arbeitet spezifisch
    - jeder nennt es so
    - hardware bedingt: board-support package

- warum code inspizieren?
    - persönlcihe meinung
        - über die jahre gewachsen, auseinandergedriftet
        - durch die entwickler in den verschiedenenn produktteams
        - entwicklungsprozess wird gerade ausgerollt, durch neuen kollegen seit 2 jahren entwickelt
        - reviews und tests werden unterschiedlich durchgeführt
        - "plattform passt nicht"
            - produktlinien/systemhäuser machen selber um scih nicht einarbeiten zu müssen
            - alles driftet auseinandwer
        - taugt der standard nicht oder 

- was ist das ziel? was erreichen mit ergebnissen?
    - umfragen und besprechungen kann man selbst führen
    - hat aber in den letzten jahren zu keinem ergebnis geführt
    - jetzt gemeinsamer entwicklungsleiter (gribner)
        - sicht von draußen
    - argumentationsgrundlage

- wie viele teams/leute entwickeln die plattform
    - kernteam: 5 personen, insgesamt ca 7 leute
    - auf den produkten 2-4, produktlinien die die software verwenden: 4
    - also 10 bei den produkten, 7 bei der plattform
    - andere sprachen/applikationen?
        - auf geräte ebene nciht
        - auf systemebene plcs von siemens / beckhoff
            - warum sps: für systeme und systemhäuser
        - bürkert kommunikator
            - inbetriebnahme, konfiguration
            - C#
            - komplett anderes team
            - ca. 10 jahre alt
            - analyse soll das auch betrachten?
                - generell ja
            - nicht unter dem selben leiter
                - f&e produktentwicklung
                     - digital toolchain
                        - dr. anne merz
    - bürkert systembus: can open

- qualität der software betrachten

- nciht nur plattform
    - sondern auch produkte
    - und kommunikator

- prozess
    - nicht scrum in seinem team
    - in der it teilweise schon
    - kommunikator, planung in 2 wochen sprints, aber kein daily
    - von anforderung bis release
    - "Software Entwicklungsprozess"
        - welche tools werden verwendet, wann findet welche tätigkeit statt
        - wie wird getestet
        - rollen (dev, po, architect)

- 2 Produkte reviewen
    - nicht nur plattform analysieren
    - sondern verwendung in 2-3 endprodukten

- auch bei einem systemhaus
    - in richtung steuerung: unwichtig
    - sollen wir nicht?

- anforderungsprozess
    - wie werden prioritäten gesetzt?
    - aushandlungsprozess soll teil des assessments sein
- manche kollegen in produkten haben gute ideen
    - kernteam anderer meinung
    - "code polizei"
        - code schönheitsebene
        - bevor ich mich mit denen rumärgere mache ich das selber
            - kultur

- wie ist es mit der hardware seite?
    - komplett außerhalb von christophers scope
- manche produkte werden nciht direkt verkauft, sondern integriert in produkte
    - "module" zb. rundes display = standard, wird im standard team gepflegt
    - deshalb hardware entwickler im team, (ganzes team 16 personen, ca5-7 am core software produkt)


- wie zusammenarbeit der teams? wie kommunikation? dokumentations?
    - klassische projekte
    - anforderungen
    - leute dazu
    - entweder direkt leute aus c team dabei
    - aktuellste version der plattform
    - z.b. ein entwicklungsteam
        - im elsaß, frankreich, triembach
        - flowwave, sensor
        - schon immer mehr eigenes ding
            - melden sich wenn was nicht funktioniert
        - start production steht an
            - code review gerne hinten runterfallen
            - land utner, termin eng, 
                - bemängelt, keine freigabe
    - reklamationen, bugs oft in cs team
        - supporten
        - unzufrieden
    - viel kommunikation über tickets
    - regeltermine für alle entwickler gibt es nciht

- lebenszyklus der produkte
    - wie viele versionen, wie lange supported?
    - auf produkt ebene extrem hohe varianz
    - 3 releases in den 8 monaten 15,16,16.01,7
    - wenn ich ein produkt anfasse 
        - dann auch neueste variante der plattform implementieren
        - streitpunkt
    - 3 personen vollzeit toolchain, pipelines, wartung, 
        - nicht über roadmap, mehr tagesgeschäft
        - aus zeit ohne teamlead

was braucht c
    - was brauchen wir an infos?
    - LOC 
    - infos von uns, mit dr. gribner
    - im nächsten jahr zusammenkommen um nächsten schritt gehen
    - kaffee vor ort, artefakte, mit wem spreche

großteil in ingelfingen, plattform komplett in Ingelfingen
- großröhrsdorf (dresden), systemhaus
- elsass
- einfliegen oder in karlsruhe
- 





code assessment

- mit ingo reden?
- embedded platform
    - überarbeiten oder neu entwickeln
- sprache?
- dauert ca 2 wochen
- preis ca 8500 oder 9000?
- LOC
- nächster schritt: technisches vorgespräch mit ingo
- kurz über andrena erzählen
- mit timm abstimmen, was wir erzählen
- dependance direkt nebenan
    - wie sind sie auf uns aufmerksam geworden?