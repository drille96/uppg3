# uppg3
Inlämningsuppgift 3

Övergripande beskrivning
I uppgiften så ska du implementera ett program i Java baserat på MVC-modellen och med ett
GUI (Graphical User Interface) i Swing.
Uppgiften innebär att du skall öva på att ta fram en objektorienterad lösning med inkapsling,
generalisering och polymorfism (F18 och F19). Du skall även göra ett klassdiagram med
generalisering och MVC (Model View Controller), samt ett sekvensdiagram för din lösning.
Uppgiften är inte lika hårt specificerad som de föregående så det är upp till varje student att
bestämma vilka klasser din lösning behöver och hur ditt GUI skall se ut (även om det gess viss
ledning nedan). Det ställs dock vissa krav på arkitekturen och vad denna ska innehålla.
Ditt uppdrag i denna uppgift är att skriva en Java-applikation som kan vara förberedd för
användning av en generell restaurang, men ska fungera specifikt för en pizzeria. Applikationen
ska hantera beställningar hos restaurangen. Applikationen ska ha en arkitektur som stöder
eventuell utbyggnad av denna till att hantera fler typer av maträtter och meny-val än pizzor.

Krav på funktionalitet för betyg G
Det program du skapar ska uppfylla följande krav på funktionalitet i programmet:

Id för krav Kravbeskrivning
IU3FG1
      Applikationen skall ha ett sammanhängande grafiskt gränssnitt (det vill säga
      ett huvud-fönster i form av ett JFrame-objekt och kan inte endast byggas upp
      med pop-up-fönster typ JOptionPane, JOptionPane kan däremot användas
      för enstaka saker som exempelvis felmeddelande)

IU3FG2
      GUI skall visa en lista på vilka pizzor man kan beställa. Varje pizza ska
      listas med vilken topping den innehåller (tomatsås, ost, skina som exempel
      på toppingar) och pris.

IU3FG3
      Användaren skall kunna välja en pizza att beställa från listan med pizzor.

IU3FG4
      Användaren ska kunna ange hur många pizzor av en viss typ som ska
      beställas.

IU3FG5
      Användaren ska i en order beställa minst 1 stycken pizza av 1 sort.

IU3FG6
      Applikationen ska inte begränsa hur många olika sorters pizza användaren
      kan beställa så länge sorten finns i menyn.

IU3FG7
      För en beställning så ska det visas hur många pizzor av vilken typ som
      beställts och vad den totala kostnaden blir för beställningen.

IU3FG8
      Användaren ska kunna välja att se en lista på beställningar som listar ett id
      för beställningen, vad denna innehåller och den totala kostnaden.



Krav på implementation för betyg G och VG
Följande krav ställs på din implementation av uppgiften:
Id för krav Kravbeskrivning
IU3I1
      Källkoden ska vara väl formaterad med lämplig indentering som presenterats
      på kursen.

IU3I2
      Högst upp i alla .java-filer ska det finnas en kommentar som innehåller:
      • Förnamn och efternamn
      • Datorid
      • Vilket program du läser

IU3I3
      Källkoden ska gå att kompilera och exekvera.
      IU3I4
      Uppgiften ska vara löst på rimligt sätt utifrån de verktyg för problemlösning
      som presenterats på kursen till och med F20.

IU3I5
       Samtliga instansvariabler skall vara privata.

IU3I6
      Metoderna i Controller-klassen skall dokumenteras kort ovanför
      metoddeklarationen gällande metodens syfte och namn, datatyp och kort
      beskrivning ges för varje parametrar samt datatyp och beskrivning för
      eventuellt returvärde (se L17 och Forumtest.java för exempel).

IU3I7
      Applikationen skall programmeras med en strikt MVC-struktur där view och
      model inte skall känna till varandra (de ska inte importera varandras paket).

IU3I8
      Minst ett interface skall ingå i lösningen.

IU3I9
      Minst en abstrakt klass med minst en abstrakt operation/metod skall ingå i
      lösningen.

IU3I10
      Lösningen ska innehålla en hierarki med generalisering i minst två nivåer.

IU3I11
       Arkitekturen ska vara förberedd för att programmet ska kunna utökas med
      fler typer av maträtter och drycker i menyn för beställningar. Detta ska göras
      genom att skapa en lämplig arkitektur med generalisering, abstrakta klasser
      och interface. Alla dessa klasser används kanske inte i applikationen i
      nuläget (mer av detta används nu om man gör delen för VG) men ska finnas
      förberedda med kod-skelett och synas i klassdiagram (även om man endast
      implementerar G-delen).

IU3I12
      När programmet startas så skapas minst 5 olika sorters pizzor och läggs in i
      programmet som pizzor man kan beställa. Detta görs inte i GUI utan görs
      lämpligtvis i konstruktion till control-klassen.

IU3I13
      Det som går att beställa ska hanteras som en eller flera arrayer via controlklassen (klassen Array och/eller ArrayList är tillåtet att använda för den som önskar).

IU3I14
      Beställningar ska sparas och hanteras som en array av beställningar via
      control-klassen (klassen Array och/eller ArrayList är tillåtet att använda för
      den som önskar).

IU3I15
      Lösningen ska använda dynamisk bindning där detta går att tillämpa.

IU3I16
      Lösningen ska använda polymorfism där detta går att tillämpa.


Krav på diagram för betyg G
Din lösning ska dokumenteras med ett klassdiagram och ett sekvensdiagram. Säkerställ att
diagrammen du lämnar in stämmer överens med varandra och den kod du lämnar in.

Följande krav ställs på diagrammen:
Id för krav Kravbeskrivning
IU3D1
      Klassdiagrammet ska följa den UML-notation som presenterats på kursen.

IU3D2
      Klassdiagrammet ska visa huvudklassen för GUI-delen, dvs. den klassen
      som anropas av någon klass av typen Control. Control-klasser och alla
      entity-klasser skall visas i klassdiagrammet.

IU3D3
      Klassdiagrammet behöver inte ta hänsyn till att klasserna ligger i olika paket.
      Alla klasser visas i ett och samma klassdiagram utan paket i diagrammet.

IU3D4
      De klasser som ska visas i klassdiagrammet ska visas med alla attribut och
      namn och datatyp/klass för attributen. Operationer/metoder behöver inte
      visas i klassdiagrammet.

IU3D5
      För alla klasser i klassdiagrammet ska det anges om klassen är av typen
      boundary, control eller entity.

IU3D6
      Klassdiagrammet ska visa om en klass eller en operation/metod är abstract.

IU3D7
      Klassdiagrammet ska visa interface som du skapat och som används.

IU3D8
      Associationer mellan klasser i klassdiagrammet ska visas med multiplicitet i
      bägge ändarna och lämpliga typer av associationer (exempelvis
      generalisering, aggregation eller komposition - överanvänd dock inte detta).

IU3D9
      Det ska finnas ett sekvensdiagram som visar vad som sker när en användare
      vill se en lista över alla pizzor.

IU3D10
      I sekvensdiagrammet ska alla parametrar i operationer/metoder visas med
      namn och datatyp/klass och returvärden ska visas med datatyp/klass.

IU3D11
      Sekvensdiagrammet ska visa alla anrop som sker mellan klasserna i
      klassdiagrammet för den aktivitet som sekvensdiagrammet gäller. Alla
      iterationer och selektioner i anropade operationer/metoder ska visas i
      sekvensdiagrammet.

IU3D12
      Sekvensdiagram och klassdiagram måste vara konsistenta – det vill säga de
      måste stämma överens och om ett anrop sker från ett objekt av klass A till ett
      objekt av klass B så måste klass A och B vara associerade i
      klassdiagrammet.

IU3D13
      Diagrammen ska vara ritade med något verktyg som Visual Paradigm eller
      liknande och får inte vara en handritad skiss på papper som sedan skannats
      in.
