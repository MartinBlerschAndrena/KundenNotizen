# austausch ki, 6.7.2026

- florian bittlinger

- vor halbem jahr austausch
- wollknäuel kernbankensystem
- herrausforderungen setup

- in der zwischenzeit weitergekommen
  - halbes jahr vergangen
- volker hat ergebnisse produziert

- token kosten spürbar, bzw gedeckelte tokens
- aktuell 100 dollar bei github copilot
- haben alle
- POC mit claude code läuft in italien
- agentisch
- volker intellij
- github copilot, CLI
- tokens sind auf vorhaben begrenzt
  - 50 cent sind schon problematisch

- vorab
  - KBS, da wird keine beratung mehr gebraucht

- legacy code
  - fachlichkeit rausziehen, und dann neu entwickeln lassen
  - geht überraschend gut

- claude
  - skills, bibliotheken, was sind eure workflows

- claude POC
  - warum war das so teuer? wird da gerade untersucht

- head office
  - llm gateway
  - nicht bedrock direkt verwenden

- letztes mal intellij zu schlecht
- jetzt liefen die kommandos vom letzten mal durch

- KBS parent: big ball of mud
  - jetzt probiert in kleinem teil
- und dann probiert test in großer codebasis zu erzeugen
- kollegen zum testen gegeben
  - bewusst auf alter copilot plugin version geblieben
  - da noch kaputt
  - plugin hat sich ausreichend weiterentwickelt
- händisch durchgeschaut
  - angent die anweisung gegeben, so dass stellen gut aussehen
  - wie methoden aufrufen
  - wie mocken
  - etc.
  - datenbank zugriffe teilweise mocken möglich
- 93% code abdeckung des bausteins durch copilot
- lokales maven: dann tests lokal ausführbar
- tests haben sehr verbosen output

- in teilschritten ausführen
- NAT unit tests abgelöst
  - junit framework für natural
  - testdaten in excel
  - jetzt parameterized test in junit
    - weniger vorraussetzungen und faktor 10 schneller

- positiv überrascht:
  - db zugriffe bemerkt
  - tests gefunden, die db zugriffe haben
  - die dann auch raussortiert
  - nur noch eine tabelle gemockt

- was wäre noch interessant
  - governance, austausch, agents.md regeln
  - KBS thema mit legacy, 5mio lines of code
    - einzelne teile rausgreifen, z.B. Zuteilung
      - nicht logisch strukturiert
      - wie würde man da ran gehen?
    - cluster erkennen, module extrahieren
      - erfahrung sammeln: welche probleme würden auftreten, wenn man das im großen stil machen würde?
    - 


# jahresfeedback, oli kühn, 10.04.2026 

- sabine termin über artur machen
  - artur und erik scholz treiben das kI thema
  - zwischenergeben

- pzo schulung auch wichtig auf petrissa ebene

- management abholen war einfach
- mittlere schicht war schwierig
  - 

- ki thema
  - volker sengler fällt gerade länger aus
  - nächste woche op

- ich auf artur ott zugehen
  - tests generieren mit KI
  - vorstellen bei sabine zantis

- aus der riesenlangen mail hätte oli schon drei folien machen können
  - tooling kann sabine aus konzern vielleicht angehen

- alex schleiff auch andrena nah

- für neue welt hilft das definitiv

- termin sabine zantis vorstellen#

- KI großes Thema im Konzern

- petrissa würde sich zeit nehmen


- agile reise
  - für robin
    - undankbar
    - transformation auch neu
    - viele angebote gemacht, die nicht wahrgenommen wurden
    - super sparring
    - agile leader nciht gewonnen
  - markus
    - führung heißt vorweggehen
    - wo wollen wir hin
    - agile reise teilziel erreicht
  - scurm methodich 
    - kapiert
    - darlehensteam inhaliert
    - evolution team
      - team kein problem
      - stefan wernke nicht
    - bauspartechnik
      - scrum nur draufgeschriebe
  - management viele erreicht
    - retros
    - portfolio
  - in der mannschaft
    - nicht der stand, den oli sich gewünscht hat
- petrissa
- sabine zantis
  - hat hintergrund
  - ist ihr nicht wichtig
  - thema aus dem fokus, stand eingefroren
- strategie der generali
  - kollegin aus agile base camp
    - uns interessiert werte der generali mapping auf agilität
    - passt komplett
- domänenwissen
  - schwachpunkt, schwer getan
  - fachlichkeit greifen
- com people : einer davon macht scrum master

- evolution
  - stefan wernke
    - bereitet sprints nicht richtig vor
    - hat keien kappa für anforderungen


# wochentelefonat, 11.12.2025

- rechnung bis zum 16.

- nächste woche mittwoch gespräch mit vorstand, letzte retro
  - mit petrissa ansprechen

- retro fürs projekt?

# oli, 9.12.2025

volker sengler: muss überzeugt werden

Rechnung
- dieses jahr alles in Rechnung stellen
- peter nächstes jahr machen
  - januar
  - wenn: volker sengler
    - dominik kube
  - agile leader ist arthur
- ende januar, anfang februar
  - andrena stellt sich vor
  - vorher techstack migration?
  - ai können wir auch
    - erkenntnisse
- generali: IT -> nutze AI, 15% effizienter werden

- termin mit sabine zantis
  - fachliche vorstellung
  - auf generali stack
  - gemeinsam mit volker sengler

- management termin, petrissa, vorstand
    - paar folien zum präsentieren
    - andrena vorstellung

- rechnung bis zum 16.12.
  - stundennachweis weglassen
  - "inklusive kalkulierter aufwände bis ende dezember"

# peter, 8.12.2025

- unit tests: großes Thema
  - keine refactorings möglich

- KI gestützter workflow, der einigermaßen zuverlässig unit tests generiert
  - openrewrite
  - agenten mit prompts
    - mach agent
    - prüfagent
    - archunit regeln

# peter wegner, 28.11.2025

tagesworkshop agentic coding: wie arbeitet man mit state of the art tooling

gitlabs bei der generali, geht auch richtung cloud
generali: ai hype, nutzt das!
eher aws
buy-in von architekten und vorstand einfach, mittleres management sehr beschäftigt, deshalb passiert wenig

gitlab läuft auf aws

- Tests generieren!
- testen lernen
- ki lernen
- idiomatischen java code erzeugen

- bauspar POs, nicht offen, auch wenns sies sagen

- plattform team IDE, engster kontakt zur generali


# wochentelefonat, 27.11.2025

- digital transformation coach
  - transformations ebene, nicht team

- fachbereichs-ansprechpartnerin
  - bedarf für coaching
- guter draht zum vertriebsvorstand
- über harald
  - neue abteilungsleitung anpingen
  - ausblick aufs nächstes jahr
- robin schreibt wrap up für termin 

- vorstandsretro 17.12.

- konzernstrategie driving excellence
  - feedback zum wachsen und entwickeln
- effizienter werden
- innovativer werden, platz für innovation schaffen

# KI Migration, Oli, Artur Ott 26.11.2025

Artur Ott, Gruppenleiter
Voker Sengler, Architekt, Migration dabei gewesen
Oli Kühn, 
Florian Bittlinger, Archtitekt

Konvertierter Code, nicht interpretiert
Java Code, natural framework
absolut strukturiert
nachgebaute datentypen
refactoren, wird aktiv gemacht, bei änderungen, pfadfinderregel

bewusste ablösung von systemteilen, openshift
ki nutzung
    intellij, github copilot
    unterschiedliche erfahrungen
    kleine sachen gute ergebnisse, größere sachen
    copilot wird vom konzern gestellt, enterprise lizenz, dsgvo konform

infrastruktur gesetzt?
    konzern liefert zu, compliance themen abgeklärt
    azure tooling

modelle sind sehr entscheidend, state of the art sehr wichtig

kontext klein haltet

doku eher schwach
testabdeckung eher gering
domänenwissen ist da, langjährige mitarbeiter die das system mit aufgebaut haben

copilot nicht ideal
- aber gesetzt...
- freigaben aus italien scope 1 jahr

laufend änderungen, überschaubarer zeitraum
    am lebenden object: wo sinnvoll ki einzusetzen
    an aktueller änderung

limitierender faktor
- subscription modell

probiert was aus
dann thema für 2026


führungswechsel


architektur
- big ball of mud
- strukturiert aber nicht gekapselt

volker und peter 1-2 stunden zeit nehmen

mit bestehenden tools evaluieren: copilot

ziel?
- legacy frei?
- clean architecture?
- !erstmal entwickler entlasten

Volker
- größter benefit: test generieren, dann kann man code anfassen

erster schritt
- termin volker + peter
- copilot gesetzt

- POC anbieten


# artur ott, 20.11.2025

0721 995 2405

Ki gestützte Migration

26.11.2025



# peter wegner, 20.11.2025
26.11. 13-17
03.12. 13-17

# wochentelefonat, 13.11.2025

robin 
- workshop 20.11.
  - beste werbung für rahmenvertrag
- mit peter gesprochen

- agile transformation
  - warten auf neue abteilungsleiterin

- neue leiterin
  - Sabine 
  - generali agile konferenz
  - ist bei workshop am 20. dabei

- ich hau oli nach dem workshop nach sabines kontaktdaten an

- arthur ott (agile leader), wartet auf rückmeldung von peter

- peter erreichen, wegen KI projekt

- feedback gespräch: olli
  - januar febuar

- gerade viele neue entwickler extern
- compeople: positive erfahrungen mit externen entwicklern
  - hoffnung: interne entwickler entwickeln sich weiter

- scrum master nachbesetzung struggle
  - aber auch kein budget für externe
- eddy macht psm1 im januar (30.1.)

- vorstand termine für retros

- donnerstags in zukunft weniger flexibel

# 

Promo-Code: andrenaKunde

# 

- PSM
  - frühbucher rabatt additiv zu kundenrabatt?
  - ja!
  - ich frage phyllis
- Olli
  - migration von legacy systemen
    - lili: noch nichts marketingreifes
    - link zu produkt auf 
  


# wochentelefonat, 18.9.2025

- externe entwickler (compeople) 50%/50% in zwei projekten
  - frontendleute helfen in anderem team aus
  - einer kann auch backend
- robin macht retros mit oberster ebene F1
  - vertrauensverhältnis
  - happy
  - mit denen kann man arbeiten
- beim rest weitestgehend stillstand
  - im team schwierig, zeitdruck
  - "keine zeit für tests"
- in sich super zufrieden, team liefert nicht schlecht, aber blind spots
  - deployment, nfr
  - projektmanagement basics, roadmap fehlt

- danny raschke, gruppenleiter von team
  - wird die anü geschichte vorantreiben

# 10.9. oli kühn

- robin
  - anü
  - einkauf stimmt mit italien ab
  - 6 unternehmen müssen immer berücksichtigt werden
    - ausschreibung ist für die
    - wenn nichts passendes dabei ist
  - nächste woche rückmeldung
    - ob überhaupt was dabei

- referenz
  - schon weitergeleitet
  - Generali Group statt generali deutschland
    - wie impressum
    - „Die Deutsche Bausparkasse Badenia gehört zur weltweit agierenden Generali Group und zählt zu den etablierten privaten Bausparkassen in Deutschland"

- auslaufen am ende des jahres aus
  - robin hats schwer gerade
  - klare kante, bringt oli weiter
  - prellbock

- management termin
- neue abteilungsleitung
- ende september termin mit mangement
  - sind zufrieden
  - buchen für ihre retros
  - in den teams scrum eingeführt
  - agile leadern
    - tun sich schwer
    - stefan renschler: agiles ist gesetzt
  - net gemosert ist auch zufrieden
  - negativmeldungen stärker wahrgenommen


# 4.8. oli kühn, ANÜ

- einstellungsstopp / einstellung wird dauern
- start größeres Projekt im September
- 18 monate max
- ausschreibung, geht eh über einkauf
- max 2 leute
- Konzern  Anbieter sind gesetzt
  - kann eigenen partner mitbringen
  - vertrag genau so annehmen
  - in konkurrenz zu 5 weiteren anbietern

oli ab do in urlaub
danny raschke triggert das an
im projekt compeople, poles dvag
prio 1 projket, oli programmmanager
kreditgeschäft ausweiten
vertriebsplattfrom wird auf weblösung
unternehmensziel der nächsten jahre
2-3 wochen bis zur ausschreibung
oli wird nicht abteilungsleiter
    - bleibt programmanager
    - neuer abteilungsleiter kommt
patricia foster
    neuer vorstand

robin läuft dieses jahr aus



# 4.8.2025

- TODO KI Umbau des natural codes anbieten, studie für paar tage
    - oli schaut
- 

# wochentelefonat, 10.7.2025

- TODO olli anhauen wg anü


- code review im gange
- im team wo das stattfindet: 2 von 3 gekündigt
    - die guten gehn zuerst..
    - dadurch trouble im team
    - retros weg bis ende august
    - als scrum master damit boden weg...
    
- neues teambuilding
  - thema für robin

- transformation langsam
  - märz workshop
  - juli folgetermin dazu
  - leute die 

- über anü auffüllen
  - robin hat uns schon platziert, aber abwehrend
  - ich gehe auf olli zu, was da los ist
  
- ganz innovative: evolution
  - compeople leute extern, reine frontend entwickler
  - wird extern nachgestafft

- scrum master stelle ausgeschrieben
  - aber nur intern (badenia und konzern)
  - keine bewerbung

# code review vorbereitung, 28.5.2025

- ingo
- florian adler
    - architekt/entwickler
    - darlehensteam
    - seit 15 jahren badenia
    - viel neu versucht
    - sachen rauslösen

- fachlich
  - post wird gescannt, als xml weiterreichen

- monorepo

- clean architecture
- DDD, aber nicht im Fokus
- das system ist ca 5 monate alt
  - kommt am donnerstag produktiv
- ein repo, darlehensvertrag

ingo braucht
- repo mit githistorie

- wie viele entwickler
- 3 interviews
- tabellen über liquibase, oracle db, openshift
- spring boot

- hauptkonsumenten: entwickler
  - führungsebene könnte ist aber egal
  - hauptfokus: ist die basis gut?

- nächste schritte
  - 

# wochentelefonat, 17.4.2025

- wenig neues
- thema "die kriegens nicht gebacken"
- code review
  - ingo anrufen!!, alternative
  - technical agile coaches
  - nächste woche flo adler da
- elternzeit: canceln, aber viel urlaub

# wochentelefonat, 3.4.2025

- mal draufgucken
  - was davon zu halten
  - kein testkonzept
  - stack
    - java
    - openshift
    - spring
  - clean code violations
    - sep of concerns
    - tests nicht wiederverwendbar
    - copy paste kram
  - wann mocken, wann echte db verwenden, stages
  - 7 Tage
  - termin mit vorstand, pfalz, mit markus neidhardt
    - robin weiter drin
    - paar tage vom vorstand rausleiern
  - 1 woche begleiten
    - ASE coaches
  - ide team macht die pipelines
  - es gibt testumgebung
    - flaky

- stack betrachten, mini code assessment
  - an ingo
  - technologisch
  - architektur
  - läuft 2 monate
  - rein intern, keinen externe
  - florian adler mal mit ingo verdrahten für vorgespräch
  - nächste woche wieder da
  - ohne einkaufsprozess einfach auf laufendes budget

- auf andre zugehen, sinnvolle optionen anbieten in gespräch mit florian

- vorstandsworkshop als gut empfunden
  - einer vorstand war mit ergebnis nicht zufrieden (letzt 1.5 h), volker kreuziger
- hatten leute für ki strategie da
  - aber war nicht gut (adesso)
  - 3 von badenia waren bei mustafas webinar
    - robin versucht nachzubohren

- olli bescheid geben, dass wir nächste woche auf florian zugehen
- olli fragen ob er freikarten annehmen darf
- unsere KI vorträge anmelden auf dem etka


# jahresfeedback 11.3. olli kühn

- weiterempfehlung
  - markus 10 
  - robin 8:9

- markus
  - cht noch was bewirkt
- robin und sebastian
  - sebastian : falsches team
  - erfahrungskurve: scrum anfänger team

# wochentelefonat, 6.3.2025

- mit olli zusammengesetzt
  - auftragsklärung für dieses jahr
  - es geht weiter, langsam, aber sie sind zufrieden damit

- nachklapp management workshop
  - robin und alle drei vorstände
  - anfang april workshop in der pfalz, robin und markus
- forst (vorstandsanwärterin)

- parallel workshop 19.3. , it führung
  - vision, workshopserie

- Trainings ans herz gelegt
  - kundenrabatt für trainings?

- umfrage, zufriedenheit
  - immer alles furchtbar schlecht
  - 75% denken über job wechsel
  - fortbildung oben riesen topf unten nie geld da

- was kam denn vom konzern
  - 2 typescript schulungen aus dem konzern für ein team, sonst nix

- schulungen selber kostenlos, reisekosten aber kein budget

- ASE wäre wirklich wichtig, aber nix mehr gekommen
  - olli fragen im feedback gespräch

- ein projekt mit negativem roi
  - vorstand hatte eigentlich abgelehnt
  - strategie moderne anwendungslandschaft
  - neuentwicklung rausziehen aus dem monolith
  - befürchtung insta legacy
  - code review für neuen teil?
    - soap schnittstellen im neuen teil
  - ab juni gute projekte
  - sqi messung für den neuen teil
    - irgendeine form von feedback hilfreich?, ingo aus budget von robin markus 2/3 tage ransetzen?
  - alex schleif federführend
    - erstellt 5 KPIs 
  - modernisierung das hauptding in ihrer IT strategie
  - ollis zukunft: gerade programmmanagerposten bis 2027


# wochentelefonat, 20.2.2025

- "alleine ist es zäh": ich dran denken mit olli zu sprechen, für nächstes jahr

- elternzeit ab 14.5.-14.6.

- olli etka freikarten fragen ob rüberwerfen

robin
- ziele transformation weiter klären, ollis rückendeckung nötig
- stimmung gerade gut richtung andrena
  - umfrage in badenia mitarbeiterzufriedenheit
    - gesamt badenia 51% überlgen job zu wechseln
    - in IT 75%
    - nutzung von KI in IT strategie -> olli ansprechen
    - weiterbildungsbudget ist da (vorstand), kommt aber unten nicht an, harald blockt das?

entwicklertag
- bewusst dagegen entschieden

# wochentelefonat, 28.11.2024

- ersatz markus neidhardt
- frank?
- oliver am pzo event zur seite nehmen
    - "die zukunft"

- elternzeit robin
    - mai und evtl Juni

- robin ab 13.12. in urlaub

- workshop im januar
    - chance für robin, 2 ebenen zu bespielen

- weihnachtsbäckerei am donnerstag?
    - jetzt wo kein reiten mehr ist 

- optionen ersatz markus neidhard
    - stephan hesse - KA, aber wahrscheinlich jan auch weg
    - christoph jung - FFM, vielleicht?
    - björn günther - MA, eher nicht
    - christian pauschert - MUC, eher nicht

# oliver kühn, 25.11.2024


- mehr leute in der führung die dahinter stehen nötig
- 5 tage passen
- überhitzt als organisation
    - schwertun: priorisierung
- frau forster wird nachfolger von hütten
- feedback gespräch angekündigt


# robin

- budget aus
- olli: 5 tage von harald

# wochentelefonat, 14.11.2024

Markus Neidhardt
- Wiebke: einreichung
- über mich text

badenia
- olli voller energie, der rest der organisation schafft es nicht das thema voranzutreiben
- montag termin mit olli
    - agile reise kommt nicht so voran, wie er das gerne hätte
    - olli treibt das im moment alleine
    - viele änderungen in den teams, aber keine änderung bei den führungskräften
- teamleiter "wir sind land unter"
- pos "teams liefern nicht"
markus
- workshopreihe zielbild agile reise
- robin muss zumindest fäden aufsammeln können

feedback-gespräch: mit olli

# wochentelefonat, 25.9.2024

- olli frustriert
    - strategietreffeng gestern
        - gekracht -> urgency daraus?
    - müssen überlegen, ob sie damit weitermachen

- erik
    - hat sich unterstützung gewünscht
    - markus geht in führungskräfte coaching
- führungsteam braucht eventuell scrum master

- fokus aber auf teams von danny
    - darlehen
    - vertrieb

- erik ziehsohn von danny

# olli, 25.9.2024

- agile reise gerade schwierig
- gestern führugsklausreu
    - agile reise war thema, weil gerade knirscht
    - POs stimmung miserabel, alle viel zu tun, jetzt noch change
    - zielsetzungen: warum machen wir das eigentlich?
    - agile leader tun sich schwer (3 stück), 
        - danny raschke, evtl dagegen
    - wir müssen momentum hinkriegen, dass thema nicht kippt
    - cross team refinements
    - olli überzeugt, dass weg der richtige ist
- budget für nächstes jahr bekommen
    - für 2 themen
        - agile reise: 200k
        - ase programm
- olli wird abteilung nur übernehmen, wenn agile reise was wird
- mit den leuten arbeiten, die mitmachen wollen
- robin hats schwer
    - olli steht voll zu robin
    - austausch wertvoll
    - liegt nicht an robin

- robin weiter als sm, 200PT: 200k
    - darlehensteam
    - fix

- systembetriebsverlagerung gerade,
    - danach mehr zeit von olli
- austausch mit markus n. / andreas
    - wertvoll, aber keine vollzeit

- ob wieder ausschreiben?
    - olli versucht zu vermeiden

- ase trainings
    - 100k
    - nicht im januar

- evolution projekt
    - angular
    - gerade über konzern angular schulung
    - robin, als berater von heibel
    - compeople, extern, dvg framework
    - kommt eh als ausschreibung
    - strategisch wichtig
        - moreva wird abelöst
    - ganzer konzern auch devg, 
    - strategisch po, agile leader, sm
        - teams noch dahin kriegen

- planung: robin: 200PT
    - gesetzt
- ase trainings
    - reden im januar
- olli heute abend nicht da
    - 

# wochentelefonat, 11.9.2024

- olli anpingen!!!

- darlehensteam aufgefangen
    - mit danny (agile leader) kurzgeschlossen
    - 2 alte entwickler aus team rausgenommen
    - 5 als effektives scrum team aufgestellt
    - 1er noch drin, wackelkandidat
    - robin da jetzt scrum master
- dicke luft hat sich aufgelöst
    - auch gut für leute, die jetzt aus dem team raus sind

- arthur / corinna bauspartechnik
    - am motzen
    - robin stellt nur noch fragen

- in 4 Wochen: termin rollenklärung

- agile leader leben "egal" vor
- alles was robin macht, hält sie vom arbeiten ab
- keine zeit die säge zu schärfen, sägen wie verrückt
- wenn sie nicht sehen, dass der verbesserungsprozess nötig ist isses noch weit
- offenheit fehlt
- bauspartechnik sorgenkind
    - artur als leiter blind dafür
- veränderungsbereitschaft gering bei bauspartechnik
- sebastians weichere art kam da besser an?

- probleme auf strategischer ebene?
    - keine dringlichkeit
    - kein grund
    - sehen keine risiken
    - keine fluktuation

- alle diskussionen auf bauchgefühlen
    - metriken, metriken, metriken

- robin kann nicht einschätzen, wie dramatisch die situation ist
    - schritt 1, dringlichkeitsgefühl
    - nicht da

- aber hierarchiegetrieben
    - leute motzen halt, machen aber mit
    - wird nicht zusammenbrechen
    - nachjustieren aber wichtig
    - urgency herstellen
        - olli coachen

- robin: was ist meine rolle im inner circle?
    - hätte gerne scheiß ideen gerne abgelehnt
- das ist nicht deine transformation, du bist nicht teil des inner circle, vielleicht scrum master des inner circles, inhaltlich nicht?
- vorzeige team aufbauen
    - sogeffekt, hier mit darlehen eine menge zu erreichen
    - neideffekt, hoffentlich ohne sabotage

- dieses jahr kompetenzaufbau
    - axel (der auch sm ist), macht privat angular, soll die teams mitnehmen

- angular, cloud kompetenz bei olli zeige



# badenia wochentelefonat 15.8.2024

- evolution heißt das projekt, das mit externer unterstützung starten sollte
    - nichts vor januar??? einkauf braucht ewig
    - budget noch nicht da

- cross team refinement gestern
    - olli paar mal erwähnt:
        - andrena sündenbock
        - nicht besser sondern teurer
        - transformationsgegner machen mobil
        - momentum der ersten euphorie ist weg
            - frust?
            - kippt die stimmung

- mit olli termin ausmachen!!!

# andreas roth, 31.7.2024

mit olli zusammensetzen
- bei konzeption jemanden mitmachen lassen
- schonmal 1 oder 2 starten lassen
- experte mitnehmen
- proof
- Wermke, Lange
- Scheel, Wagner

mein gesicht bei ansprechpartnern bekannt machen


# wochentelefonat, 17.7.2024

markus macht so viel wie nötig ist bei badenia
- workshop am freitag, lego scrum
- nächste woche erstes cross team refinement

- umfrage
    - 17 fragen
    - zahlenwerte ohne kontext schwierig
    - wenige leute die kommentare hinterlassen
- am anfang viel motivation
    - jetzt stark abgeflacht
- stand
    - pro forma scrum eingeführt
    - aber immer noch projektgetrieben

- agile leader
    - beklagt dass es so viele termine gäbe
    - danny
    - reiten welle mit, gehen aber nicht voran
    - umfrageergbenisse werden die führungskräfte zum handeln zwingen


# wochentelefonat, 3.7.2024

- budget für nächstes jahr: 250k für begleitung, 70k für trainings
- DVEG: wollen externe unterstützung, robin nießner
    - kompletter berechnungskern, bausparverträge
    - in webtechnologie umsetzen

- für umfrage betriebsrat um erlaubnis bitten
- inner circle wird umstruktiert
    - mehr PO, mehr Führungskräfte beteiligung
    - ist in den letzten zwei monaten etwas eingeschlafen

- sebastian hat komuniziert dass er rausgeht, entspannt

- markus neidhardt kommt morgen mit zur badenia, wird für andreas übernehmen

# wochentelefonat, 19.06.2024

- sebastian
    - 26.7. letzter Tag für Sebastian
    - ab 23.9. wieder da
- robin
    - ca. ab 14.7. für 1 monat weg (elternzeit)

- budgets für nächstes jahr
    - sieht wohl gar nicht so gut aus

- engineering skills fehlen stärker als agile coaching
    - keine statische code analyse
    - mocks in tests
    - jemand der sich aktiv um ausbildung kümmert fehlt
    - handwerkszeug fehlt

- empfehlung sebastian
    - eher engineering know-how rein als agile coaching

- nächste wochen
    - übergabe, dann 2 monate chaos

- frusttag, alle warten auf das nächste große planungsding


# wochentelefonat, 22.05.2024

- no show

# wochentelefonat, 27.03.2024

- SQI Messung
    - haben sie schonmal gemacht
    - können wir wieder anbieten
- 50% der Zeit für Softwareverbesserung eingeplant
- Tests laufen 5h
    - beschleunigung als punktuelles angebot?
- code assessment
- agile basics schulung
- termin mit vorstand
- jedes team hat jetzt ein planning
- termin mit ralf schlegel, projektkoordination

- stressig, aber spaß weil sichs lohnt


# wochentelefonat, 13.03.2024

agile basics schulung halten marvin und sebastian/robin
- 27.3.
- 15./16.4.
- 29./30.4.
- 13PT für Marvin mit Olli ausgemacht

- sprintziele
- po schulung
- sm schulung
    - jetzt noch keine psm schulung
    - zertifizierung im konzern nicht möglich
    - option für 5 Leute, die das dann bei uns machen könnten
- alleine stemmen unrealistisch

- transparenz über budgetverbrauch richtung olli

- "bessere retrospektiven" training anbieten?


# wochentelefonat, 31.01.2023

- 7-8/10
- aktuell cool
- sehr viel zu tun
- läuft es schnell genug aus unserer perspektive
- es ist halt kein produkt da

- nicht nur beobachten
- wie kommen wir an leute, an teams
- wie sind strukturen, hierarchie
- danny raschke, arthur ott: GL
    - robin bei danny teams
    - sebastian bei arthurs
- viel orga kram, externe leute reinholen viel manuelle arbeit
- 3-4 verschiedene logins
- emails, teams, schwierig
    - manches von generali, manches badenia, manches dienstleister
- strategisch
    - agile reise von olli
    - steps von andreas
    - begleitet von beiden, und dem inner circle
- harald
    - it strategie badenia
        - ziele, metriken sind drin kann man sich ranhängen - legitimation
        - moderne software landschaft
        - mitarbeiter schulen
        - wissen von extern, wenn fehlt
            - budget für uns aber nicht leicht zu kriegen
- wer ist inner circle
    - fast 20 leute
    - unser change team
- ausbildung scrum master badenia
    - interne weiterentwicklung von interessierten personen
    - bekommen trainings von generali
- erste Termine für PO coaching

- unter danny, POs
    - stefan rentschler
    - stefan wernke
- unter arthur
    - alex schleiff
    - berthold, corinna hauser geteilt team bauspartechnik

Hierarchie
- Vorstand, Abteilungsleiter
- GL: Gruppenleiter
- PL: Projektleiter, 
- PO auf papier keine Führungsposition, oft in personalunion mit PL

- Boni könnten in Konflikt mit agiler Transition stehen

- landschafts- mural
https://app.mural.co/t/andrenaobjectsag8541/m/andrenaobjectsag8541/1704825292843/a5cc06fb329083d86cebb09f0497cb83797c22aa?sender=u46771088913b9ee93c718422



# gespräch sebastian, robin, 19.01.2024

- ktt: essen gehen

- nachfragen wegen budget, mitte des jahres



- TODO: badenia teams team
    - wochentelefonat, 2 wöchig, terminsuche im chat


# deep dive 20.11.2023

- it und fachbereiche eng beieinander
- po schulungen intern / generali
- sm schulungen extern
- value orientierte planung
- software entwicklung hier nicht drin
- vertriebsteam
    - externer sm noch unklar
    - dvg-systeme
    - moreva -> java
        - 2-3 leute
    - antragsverfahren
- sm kandidaten, 2 aus dem hut gezogen
- synergien
    - basissysteme: auf sm verzichten?
- 100 Tage extern
- 100 Tage sm coach
- 75 Tage Agile Coach
- basis
    - pipelines
    - gitlab
    - frameworks
- budgettopf, was wir draus machen entsteht auf der reise
- wir sind die ersten
- große anbieter sind konkurrenz
- wie bewertung
    - was tagessätze
    - remote/vor ort
        - identisch->vorteil für uns
    - reisekosten so und so viel
    - ein anbieter vom konzern "können alles", konzernpartner, will niemand haben
    - 30%/70% home/vor ort
    - preise gehen an einkauf, oli kriegt die zum schluß
- 27.11. abgabe
- entwicklertag.de, auftrag an diese adresse
- 11.12. einaldung

# telefonat alexander schleif

- brutto mit netto verwechselt, preis reduzieren
- rechnung vor dem 13.12. (pauschal)

# gespräch mit andreas 7.7.2023

- abschlusspräsi gehalten
    - scrum.org maturity level 0.75/5
- code assessment
    - ca 6. mio loc
    - konvertierter code
    - erweiterbarkeit problematisch
    - ingo schaut mal drauf
        - danach angebot zu code assessment, weniger als 10.000€

# update 22.6.2023

- was ist bisher gelaufen
    - interviews durch
    - mit beteiligten gesprochen
    - beobachtungen von planungnen dailies
    - keine umfrage
    - workshop mit inner circle
        - knapp 15 personen
        - zukünftige early adopters
        - was bedeutet agilität, vorteile, commitment zum mitmachen
    - führungskräfte
        - erst-interview

- was kommt noch
    - nächste woche gespräche mit vorstand, management
    - ergebnispräsentation, workshop
        - wo stehen wir gerade
    - beobachtungen aus interviews geteilt mit oli, harald, 2 andere
        - sie wollen gerne große transition (entgegen empfehlung klein zu starten)
        - dazu begleitung von 2 SM und 1 Coach nötig
            - relevant ab 2024, und jetzt für budgetplanung
            - aufbereitung für gespräche in badenia (alle F1)
            - workshop mit F1
                - was ist euch wichtig
                - verständnis agilität
                - ziele
    - von generali angebotene basisschulungen
        - dabei plan für nächstes jahr
        - mit den teams schon anfangen zu arbeiten (wenn auch nicht vollzeit sm)
    - change team
    - knowhow java/agile software entwicklung
        - führung sieht keinen bedarf
        - alex schleiff sieht durchaus bedarf
            - möchte das in kleiner runde mit oli und harald hauser
            - ase coaching oder so möglich?
            - bei oli und harald eher kein thema
            - 20 von 80: alte mainframe haudegen, die eher nicht mehr java lernen werden
        - politisch heikel

    - langfristig ab 2024 1 coach und 2 SM
        - empfehlung: selber interne SM schaffen

- was sind die empfehlungen

# fahd, personaldispo, 15.5.2023
- oliver kühn, erwartete bedarfe für transition start
    - 1 senioriger consultant
    - 1 junioriger fürs team

# Abstimmung Fahrplan 25.4.2023

- nicht agile reise olli kühn badenia, sondern alle mitarbeiter
- agilität gedultet (ab 2006)
    - guerilla taktik/uboote
    - 1/3 kann mit agilität was anfangen
    - hierarchisch organisiert, klassisch bank
- 2017-2020
    - Generali IT (ca 1000 Leute) mit viel budget agil ausgerichtet
    - agile basecamp ins leben gerufen
    - neuer impuls für die badenia IT
- Führungsklausur
- 3 Teams
- Kollegen ängstlich vorsichtig
- olli war der treiber der agilität
- jetzt komplett auf java/oracle
- was muss ich dem management/vorstand erzählen, um agilität einzuführen
- schmerzpunkte:
    - projekte dauern lange
- 80% regulatorik
- business value - vortrag objekt forum von fahd
    - schnell liefern
    - weniger wertvolle dinge weglassen
- management möchte die richtung ändern können
- recruiting über ausbildung, neue aufgeschlossen
- alte mitarbeiter, die agilität eher ablehnen mittlerweile größtenteils raus
- fachbereich
    - alles bis zum ende durchdenken und machen
    - klein anfangen fehlt
- goldnuggets
- methodiken nicht der primäre fokus: mindset wichtiger

- im juni budgetabgage für vorgehensmodell

- christop hütt hört auf
- dr kreuziger (jurist), hat marketing vertrieb aufgebaut, möglicher unterstützer
- edgar hütten
- vorstand muss überzeugt werden, den weg mitzugehen und budget für 2024 zu verkaufen
- schulungsprogamm über agile basecamp, quersubventioniert

- letzte woche workshop mit abteilungsleitern (AL)
    - pain points gesammelt
    - wo kann ich mit wenig aufwand etwas verbessern
    - 1 Thema finden um es schnell umzusetzen für 2023
    - abteilungsleiter hören zu, aber sehr klassisches mindset

- IT
    - fachliche leute und entwickler in den teams
    - Projektleiter heißen hier PO, sind fachliche experten, POs führen Teams
        - entwickler werden angewiesen
    - sehr viele kleine Themen, sehr viele Anwendungen
- lieferfähigkeit
    - testpyramide
    - automatisierte tests
    - build zeiten 3-4 stunden
    - ein großes system 30.000-40.000 Klassen
- ALs und POs zusammenbringen

- Analyse gemeinsam mit Oliver Kühn, dann passt das mit einkauf
    - mit relevanten stakeholdern zusammensetzen
        - welche fragen bei badenia sinnvoll?
            - wo seht ihr verbesserungspotential
            - wie läuft der prozess gerade
    - beobachten, bei meetings mitlaufen
        - dailies
        - abstimmungsmeetings
        - andere meetings?
        - momentan gibt es keine reviews, keine planings
    - fragebogen
        - wahrscheinlich sinnfrei, weil gar kein scrum prozess

Fokus auf beobachtung und interviews, nicht fragebogen

- andere IT nahe Themen einbeziehen
- operating
- datawarehouse
- systembetrieb macht generali

- konzernworkshops möglich, müssen aber eingeplant werden
    - langsame prozesse

- vor ort meetings/workshops problemlos möglich

- zeitlicher ablauf, andreas
    - ca. 9:00 starten, 9.5. / 10.5. koordinieren und planen mit oliver und alex schleiff
    - vor ort
        - mit welchen leuten sprechen, welche teams beobachten, welche meetings
    - vollfokus ab 22.5.

- 25.5 - 3.6. ist oliver weg
- alex schleiff mit ins boot holen


# Angebotstext Badenia

Leistungsbeschreibung



# 13.03.2023 Oliver Kühn, Deep Dive Badenia

per Du
seit 96 bei der badenia
architekt
seit 2003 leitungsfukntion alle teams mal geleitet
mainframe, abas, badok, morewa, fahd
alex schleiff, 2016 weg from mainframe sether beschäftigt
leiter bauspartechnik
wird harald wagner abteilungsleitung übernhem
rehcnzentrum überlageer,
wird leitungsfunktion abgeben
15 leute + grioßprojket zuviel:
agilität wird er wieter treiben

wir sind nicht die einzigen
auf fahd gekommen, value vortrag objektforum

agil in IT stragtegie
siene kollegen wollen nciht, angst
chefs nciht so wichtig
eigenes team mitgeniommen
ohne strategische asurichtung kein drive
IT strategie,
wirtschaftsprüfer: konkretere IT strategie, nachvollziehbar verfolgen
risikomanager melden
effizienzsteigerung
systembetriebsverlagerung: zur generali, neues thema von kühn
upskilling: entwickler, architekten POs

agile in it strategie verankert

generali 2017-2020 agile transition
badenia: eigenständige entwicklungsabteilung

neuer vorstand dr. kreuziger
christoph schick hört auf
edgar hütten IT vorstand: in 2-3 Jahren Ruhestand
    - hat agile erfahrung +/-


- DL Kollegen abgeholt, aber Angst zu scheitern
- junge Leute aus eigener ausbildung
- begeisterung unklar
- ziel:
    - mehr business value
        - 80% bafin anforderungen
        - rest fällt immer runter, verbesserungen in fachbereichen kommen nicht
    - effizienzsteigerung
    - flexibel
    - empowerment mitarbeiter

IT
30 Entwickler
insgesamt 80 leute

kein Qualitätsproblem?
Problem: schnell ausliefern
schlecht:
    - klassische budgetierung
fachbereich kostet IT nichts

workshop RF1
    - business value greifen

selbstorganisierte teams werden lange brauchen

leistungsbeschreibung.
- vorgehensmodell entwickeln
- 25 PT
- F1, Topmanagement abholen, wie auf agile reise gehen?
- wie zielbild schärfen
    - tz.B liefergeschwindigkeit
- Quickwin leuchttürme finden (Idee)
    - quersubvention: nicht in 25PT
- Ideen generieren:
    - bis Juni: braucht Oliuver groben fahrplan bis 2024
- budgets maximal unterer 6stelliger breich
- management überzeugen, referenzen?,

- POs jetzt schon,

entweder agile leader/people, oder fachlich PO

- agilität wieder eingeschlafen, leute abgeschossen in der vergangenheit

schulung über konzern abgedeckt
- agile spielwiese : agile base camp, eigene trainer
- wir nicht in schulung

- für uns badenia

- startpunkt für 2024 finden , budget verkaufen
- methoden anwenden: leute sehr resistent
- meisten leute: wie immer weiter machen


















# 9.3.2023 Fahd - Vorbereitung Termin Montag

- habt ihr schon analyse gemacht?
    - wie bringen wir unsere maßnahmen dazu
    - maßnahmen erarbeiten
    - was vorgehensmodell erarbeiten
        - agile transition erstes Projekt starten in 2023

1. management, produktportfolio, produktmanagement professionalisieren, strukturieren
2. strategische entscheidungen mit metriken unterfüttern
3. aus strategischer ebene projekte führen
    - agile vorgehensweise etablieren
    - aus der erfahrung in 2023 rest der transition weiter treiben
4. Konzept erstellen in 25PT:

- wie sieht agilität bei Generali/GD-IT aus?
- wie ist die Badenia IT aktuell aufgestellt
    - was leistet sie
    - wie ist sie organisiert
- welches sind die Fachbereiche
    - wie i
- was sind die Badenia Gegebenheiten, die berücksichtigt werden sollen
- Motivation für die Veränderung
    - wer hat diese Motivation?
    - was ist mit anderen Motivationen/Leuten?
- Ziel der Veränderung


# 22.2.2023 Fahd

- kontakt mit oliver kühn aufnehmen
    - persöliches gespräch anbieten
    - eure herausforderungen, wie kann ich helfen
Fahd
-

# Events

Angebot anders gestalten:
- Durchführung direkt beauftragen
- Analyse rabattiert/anrechnen bei durchführung
    - analyse selbst pro forma teurer

# 10.02.2023

- iso 14001: ebe besorgt bescheinigung, dass wir im prozess sind
- präsenz: default
- nicht über partner


Punkte für die Ausschreibung
- scrum.org zertifizierte Trainingsangebote für Product Owner, Scrum Master, Entwickler und Management
- mehrere scrum.org Trainer in der Organisation (min. 5)
- längerfristige Begleitung nach der IST-Analyse
- Empowerment auf allen Ebenen der Badenia Organisation um
    - langfristig hochwertige Software zu liefern
    - auf Wertschöpfung zu fokussieren
    - die Wertschöpfungskette zu optimieren
- ISO 27001 zertifiziert
- ISO 9001 zertifiziert
- Referenzen aus der Versicherungs- oder Finanzindustrie

## 8.2.2023

ISO 9001,27001?
umweltmanagementsystem ode 14001 lizenziert
mehrere scrum.org trainer in der organisation (min 5)
trainingsprogramme für coaches und entwickler nach scrum.org
referenzen in der finanzindustrie (mengengerüst?)

## 06.02.2023

Ausschreibung
- Zertifizierungen
- größe der Firma
- ASE, Scrum Trainings

- Empowerment richtung quality und del

- Analyse
    - wir analysieren die umgebung
    - bringen auch unsere eigene meinung
    - fragen sind nur selbsteinschätzung

- adapt schritt nach den analysen nur gut gelaufen wenn wir die danach begleitet haben
-> agile analysis program, es geht um begleitung
- längerfristige begleitung nachd er analyse
- für management, coaching, consulting, softfware engineering

Ausschreibung ist nur für Analyse
- know-how in der IT und Finanzbranche
- größe des unternehmens
- fähigkeit auch im nachhinein zu liefern
- iso zertifizierungen
- durchführende: experten in agile change
    - agilität und agilen vorgehensweisen

vor dem 16.2. an fahd




## 20.12.2022
Fahd telefonat
- vortrag für vorstand
- Oliver Kuhn, Alexander Schleiff
- Ausbildung (4 neue Leute)
- schneller liefern, höhere Qualität
    - empowerment
- im nächsten Jahr (Januar)
    - Analyse
    - Coaching
- DVAG (Mutter)
    - initiative richtung it strategie
    - alles in der cloud/webapplikation
    - framework: "microservice"
        - luigi (SAP)
    - mehr empowerment für die teams
    - react oder andere weboberfläche

## 22.02.2022


- code wird neugeschrieben
- noch ein thema dazwischengeschoben,
    - starttermin 1.9. oder 15.9. (egal)
    - tandem



## TODO

- CRM Lead pflegen (mit daniel)
- java version?

## Kennenlerntermin
Timm ist für delivery dabei

alex seit 2002 bei badenia
java entwickler
bis2014
migration von mainframe im mai zu ende
voll auf java
oo erfahrung, agile entwicklung
java, spring boot, openshift, spring boot batch
ab 1.6./1.7
1-2 jahre
vorstellung bei team
kein webfrontend, kleines java fx, für innendienst
tandem? mitnehmen in interne runde
integration in team 3-4 devs
    - git, java ein fitter, kennt alte welt noch
    - ein junger
    - ein älterer der umstieg mitgemacht hat
testen tun sich leute schwer
java ist noch neu
dev ops?
    -  erstes neues team, es gibt aber ops team
erfahrung ca 5 jahre
konzern macht openshift, erste ansätze aws
gerade alles remote, mischbetrieb wahrscheinlich
PP über teams üblich
hardware wird gestellt
intellij
einkauf:
    - ausschreibung
    - außer vorstand
    - alex fragt einkauf an
    - eher dienstleistung
folgetermin 15. februar

### Punkte fürs Gespräch:
- Umfeld/Kontext
    - "Darlehen"=Baufinanzierung?
    - mission critical?
    - Wer sind die Nutzer, wie viele?
- Projekt
    - Name?
    - Projektlaufzeit?
    - Weiterentwicklung, Ablösung, Neuentwicklung?
    - wie viele Entwickler insgesamt?
        - interne
        - externe
    - Agilität/Prozess (existiert?, wer nimmt an Meetings teil?)
        - Scrum?
        - PO?
        - Scrum Master?
        - Review?
        - Retro?
    - Engineering
        - Qualität
        - Metriken
- Erwartungen an Entwickler?
    - "Java, OO, TDD, Agilität"
    - "Container-Technologie, Spring Boot"
    - reiner Backendentwickler?
    - erwartetes Erfahrungslevel?
        - andrena arbeitet gerne mit 5 Levels (Spanne 750€-1200€/PT a 8h)
            - Junior 0-1
            - Young Professional 1-2
            - Professional 2-5
            - Senior 5-8
            - Expert 8+
    - Prozess Know-How?
    - remote oder vor Ort?
- Vertragsmodell
    - Dienstleistung?
    - AÜ?
- Zeitrahmen der Beauftragung
    - ab dem 2. Quartal, wann genau?
    - für 1-2 Jahre?
    - konkrete Beauftragung für x Monate?
- Weitere Schritte
    - Tandem vorstellbar?
    - weiterer Unterstützungsbedarf?
    - Ansprechpartner?
    - wer stellt hardware?
    - konkretes Angebot?
