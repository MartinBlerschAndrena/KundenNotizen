# angebotsvorstellung, 22.7.2026

- regressionstest, nicht bester stand, nicht wohldefinierte testpyramide
- richtige technologie
- wunsch
  - transparenz
  - was ist abgedeckt an fachlichkeit
- nicht die interne kapa
- externe expertise
- nicht externe qa aufbauen
- qa, ui tester, leute die end to end cypress automatisieren

- plattformtam
- 1 qa pro team
- 2 tage bis getestet
- den tests traut niemand
- keine strategie, für welches problem ein test der richtige

- management tauglich
- reporting: richtung management zusatnd
  - c level traum
    - compliance business processes bpmn abgebildet
    - kritische identifizieren
    - c level hat report: die sind alle heile
    - prozesse haben bewusst hohes abstraktionslevel
  - schneller deployen
    - statt in 3 in 1 tag
- fehler finden bevor der anwender sie sieht?
- post mortems nach downtimes, oft schlampig

- mangel an resilienz
- wiederkehrende themen

-


# Angebot 

- es fühlt sich niemand für die e2e tests verantwortlich
  - QA wird uns wahrscheinlich sagen, dass sie mit manuellen tests ausgelastet sind
  - müssen die nicht bafin reporting ihrer tests machen?
- roter balken für fehlgeschlagene e2e tests sehr gut versteckt
- 

- QA Assessment

- Szenario 1
  - nach übergangszeit: fehlgeschlagene e2e tests verhindern prod gang
  - zusätzliches Tooling: keines
  - auftrag an teams: löst das problem
- Lösung wird wahrscheinlich enthalten
  - flaky tests isolieren / taggen  
  - e2e tests in review einbinden
  - nach und nach fixen, als team aufgabe
- was hält uns davon ab das genau so zu tun?

- gibt es eine ende zu ende verantwortung für funktionen?
- domänen sind wahrscheinlich technische komponenten


# gespräch 14.07.2026
- michael, phillip
  - dokument geschrieben als teststrategie
  - beide drin

- michael
  - enablement 
  - kunden ebale für self service
  - domänen spezifische teams
  - cross funktional, mit qa
  - ein plattformteam
    - test infra
  - 5 monate

- philipp röben
  - von anfang an mit dabei, kennt die ganze historie
  - staff engineer, team übergreifend, libero
    - monitoring, reporting, PO aufgabne
    - testumgebung aufbau
      - mit verantwortlich wo wir da stehen

- rein innerlicher druck
  - management druck
- teams bauen unit tests
- cypress
  - instabil
- in manchen teams gut, in manchen teams schlecht
- in manchen teams viele fehlschlagdende tests
- in andern wenig
- manuelle tests
- was wird wo gestestet
- viel zu viel in e2e test
- was ist getestet was nicht
- keine geile doku
- bpmns
- teststrategie
  - wildwuchs
- keinen der das thema als ganzes diskutiert
- was kann man bei deployment weglassen etc

- ausagekraft an management: geschäftsführung

- besser werden und beschleunigen

- strategische sciht und implementierung
  - vorerfahrung
  - best practices
  - tools

- cypress ergebnisse

- api test framework mit externen

- e2e setup

- "wir wollen alles haben"
- wohlfühlen: unit tests, die integrativer wurden
- alles darüber hinaus unbefriedigend, bis nicht vorhanden

- e2e tests
  - aufgegeben
- daten
  - problemfälle
    - zeitreisen

- idee mehrstufig
  - t&m
  - QA engineers reden
  - wo stehen wir

- es gibt leute die an infra arbeiten

- trunk based development umgestellt
  - pipeline aufgebaut
  - testautomatisierung wichtig, sonst bringt es nix
  - vor prod muss alles manuell getestet werden
  - aber pipeline geht noch nciht nahc prod durch

- zahl der integrationstests

- web und app
  - web / app, 50/50 mit steigend in der app
  - orders auch mehr in der app

- ca 600 tests, die hälfte zum wegschmeißen?
- kein page
- QA engineer in den teams baut die tests
- silos
- end to end test als teil der stories nicht drin

- monolith, deployment monolith
  - teilweise griffe in fremde datenbanken

- security team
  - CISO: nicht chef davon
  - team fokussiert auf entwicklung, libs checken
  - überwachung
  - silo
  - thread modelling
  - tools wie aikido
  - security champion in jedem team, ansprechperson
  - hohe integration? eher nicht

- performance/last tests
  - bafin anforderungen
  - long term thema

- nur DACH
  - also kein US thema
  - transaktionen nicht nano sekunden bereich
  - aws

- live erfahrung
  - 10 fache lasts problemlos ausgehalten

- code kann in claude
- daten nicht, aber es gibt nur synthetische daten

- keine wegwerf testsysteme
- entwickler haben nie in cypress reingekuckt
  - eigenes silo
  - backendler haben genug zu tun
  - mind set change

- interner QA lead
  - ownership statt QA team
- entwickler sehr gute erfahrene leute
  - viel zu tun

- proaktiv dinge pushen
- passiv

- fokus auf cypress

- tooling
  - für reporting
  - wie integriere ich teststrategie

- assessment phase teil des angebots

- stell dir vor firma wird gekauft
- QA Assessment
  - geld drauf werfen
  - gesamtpacket
- "kein kleiner auftrag"

- minimum 4 augen prinzip
  - vor allem pull requests
  - teamspezifisch unterschiedlich

- QA

- angebot: wie kanns danach weitergehen
- kapazitäten
  - leute
- szenario annehmen

# fragen

## background

- wie auf andrena gekommen
- was weißt du schon über andrena

 - gründe
   - warum jetzt?
   - warum nicht warten auf Head of QA

- woran macht ihr fest, dass euch bei tests etwas fehlt?
- gibt es aktuell eine teststrategie? (für die gesamte gruppe?)
- wie lange sind die QA engineers schon an bord?
  - sind die im rahmen dieser initiative eingestellt oder schon lange dabei?
- wie lange sucht ihr schon und wie lange erwartet ihr zu suchen bis QA Lead da ist?
  - abwerbeverbot

- transparency for leadership: misstrauen? oder reporting pflichten?
- was ist "good unit test coverage" für euch?
- was ist eine small cypress suite?


- 12. 'including technical approach' vs 3.1 'approach agnostic'

## angebot
- warum so ein formales angebot?
  - ist das überhaupt der plan?
  
- seriöse schätzungen sind so unmöglich (8.2 Effort per deliverable in person days)
  - abstimmungen
  - unbekannte abhängigkeitn (und das wird durch mehr angebotspapier nicht besser)
  - unbekannter umfang
- was braucht ihr da


## orga
- zeitrahmen
 - bis wann entscheiden
 - bis wann starten


## KI
- was dürft ihr denn? was macht ihr schon?
- was sagt claude zu den flaky tests?
- tests aus anforderungen mit KI erzeugen
  - machen wir gerade in einem anderen projekt

# erste idee
- code review auf test qualität
  - handlungsempfehlungen


