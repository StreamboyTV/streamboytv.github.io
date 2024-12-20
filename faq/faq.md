---
label: Häufig gestellte Fragen
order: -1
icon: comment-discussion
---

# Häufig gestellte Fragen

<h2>Was findest du in dieser FAQ?</h2>

**In dieser FAQ findest du Antworten auf häufig gestellte Fragen.**  
**Wir haben die am häufigsten gestellten Fragen sorgfältig gesammelt und in klaren, leicht verständlichen Antworten zusammengefasst.**

---

==- Ich habe ein Problem mit "XY"

Zuerst schauen wir, ob wir im `Streamboy Discord` etwas dazu finden.

Bitte schaut zuerst in den `#neuigkeiten` Kanal.

Wenn ihr dort nichts findet, dann benutzt bitte den `#Allgemein` Kanal und beschreibt dort euer Problem.

===

==- Was ist denn eine AppBox?

Der Betreiber verwendet einen `leistungsstarken Server`, auf dem nicht nur ein Plex Media Server, sondern mehrere Plex Media Server `virtualisiert` installiert sind.  
Das bedeutet, dass sich auf diesem Server mehrere separate Plex Media Server befinden.  

Der Nutzer erhält von dem Betreiber einen virtuellen Plex Media Server, der ihn zum `Besitzer einer AppBox` macht.  
Dadurch kann der Benutzer seinen eigenen Server verwalten und hat `Administratorrechte`.  

Obwohl der Betreiber nur eine begrenzte Anzahl gleichzeitiger Streams erlaubt, kann der Nutzer seine Freunde oder Bekannte auf seinen Server einladen, unabhängig davon, wo man sich befindet.  
Der Nutzer kann für diese eingeladenen Personen eigene Profile einrichten und festzulegen was für welche Inhalte sie sehen dürfen.  

Der Nutzer kann sogar die AppBox selbst `neu starten` oder `neu aufbauen` wenn mal Probleme auftreten.  
Auf der Plex-Plattform kann der Nutzer auch über das `Dashboard` sehen, wer gerade was anschaut.  

Zusammengefasst:  
Man kann den Server `ausschalten`, `einschalten`, `neustarten` oder `neu aufbauen`.  
Man kann `Profile` erstellen, z.B. für `Familie oder Bekannte`.  
Man kann `andere Plex-Benutzer` per `E-Mail` einladen.  
Man kann sehen, wer gerade was `anschaut`.  
`Downloads` sind möglich.  
Man kann die `Mediatheken` verwalten und vieles mehr...  

===


==- Warum bekomme ich täglich keine neuen Inhalte?

Es ist wichtig, diese Schritte zu befolgen, damit täglich neue Medien auf der Startseite erscheinen.  

[Einstellungen -> Geplante Aufgaben](https://u3known.github.io/sb-wiki/appbox/plex-settings/#geplante-aufgaben)<br/>
[Verwalten -> Mediatheken](https://u3known.github.io/sb-wiki/appbox/plex-settings/#verwalten---mediatheken)<br/>

Nach diesen Schritten ist lediglich ein Neustart des Servers erforderlich.  
Nach dem Neustart wird die Mediathek automatisch alle 12 Stunden gescannt.    

===

==- Meine gespeicherten Inhalte sind nach einem Serverwechsel verschwunden?

Sie werden nur gelöscht, wenn man die Inhalte in der Wiedergabeliste speichert, da diese servergebunden sind.  
Wenn man sie in die Merkliste verschiebt, werden sie nicht gelöscht, da diese an deinem Konto gebunden sind.

Voraussetzung ist, dass `Einstellungen Synchronisieren` aktiviert ist.  
Wenn diese Einstellung nicht aktiviert ist, werden die Merklisten nicht gespeichert.<br/>
[Plex AppBox](https://u3known.github.io/sb-wiki/appbox/plex-settings/#plex-web---allgemein)<br/>
[Plex Share](https://u3known.github.io/sb-wiki/share/plex-share-settings/#plex-web---allgemein)<br/>

===

==- Fehler: Dieser Server ist nicht leistungsfähig genug, um Videos konvertieren zu können

Es wird versucht, den ausgewählten Inhalt zu transkodieren, da eine `Inkompatibilität` mit der `Hardware` festgestellt wurde.

Derzeit können nur `1080p-Inhalte` transkodiert werden.

Bei `4K Inhalten` ist dies `nicht möglich`, da der Betreiber dies deaktiviert hat.  
Der Grund dafür ist, dass der Server dafür sehr viel `Performance` benötigt.

Optimal wäre es, wenn gar nicht transkodiert wird.

Wenn zu viel transkodiert wird, sollte man sich nach einem neuen TV Stick/Box umsehen.

===

==- Kann ich 4K-Inhalte Transkodieren?

Nein!  

Derzeit können nur `1080p-Inhalte` transkodiert werden.

Bei `4K Inhalten` ist dies `nicht möglich`, da der Betreiber dies deaktiviert hat.  
Der Grund dafür ist, dass der Server dafür sehr viel `Performance` benötigt.

Optimal wäre es, wenn gar nicht transkodiert wird.

Wenn zu viel transkodiert wird, sollte man sich nach einem neuen TV Stick/Box umsehen.

===

==- Kann ich 4K-Inhalte im Browser abspielen?

`4K-Inhalte` können leider `nicht` im Browser abgespielt werden!

===

==- Auf welcher Platform kann Plex installiert werden?

Plex kann auf einer Vielzahl von `Plattformen` installiert werden, darunter:
- Windows
- macOS
- Linux
- Android
- iOS
- Roku
- Android TV
- Apple TV
- Amazon Fire TV
- Xbox
- PlayStation
- Smart TVs (bestimmte Modelle)
- Kodi / CoreELEC

===

==- Kann ich Plex auch von unterwegs verwenden?

Das ist weltweit ohne Probleme möglich!

Einfach aus dem `Google Play Store` oder aus dem `Apple App Store` die App `Plex` installieren.

===

==- Kostet die Nutzung von Plex etwas?

Grundsätzlich nein.

Es gibt eine `einmalige Gebühr` für `mobile Geräte`.  
Wenn man einen `Plex Pass` besitzen, muss man diese Gebühr nicht bezahlen für mobile Geräte.

Für `Fernseher` oder `Tablets` muss man `keine Gebühr zahlen`, egal ob man einen `Plex Pass` besitzt oder nicht.  
Das ist kostenlos.

===

==- Braucht man einen Plex Pass?

Nein.

Der `Plex Pass` bietet nur sehr wenige Vorteile bei der Nutzung von Streamboy.

Welche Vorteile habe ich bei der Nutzung von Streamboy in Kombination mit dem Plex Pass?
- `Mehr Designs` stehen zur Auswahl.
- Du kannst `Trailer` sehen.
- Es entfällt die `einmalige Gebühr` für `mobile Geräte`.

===

==- Kann ich bei Serien das Intro überspringen?

Nein, das geht nicht.

Dies ist auch mit dem dafür notwendigen `Plex Pass` nicht möglich.

===

==- Kann ich Filme oder Serien anfragen?

Ja, das ist möglich!  
Im `Streamboy Discord` unter:  

- ***#film-wünsche***
  - Befehl: `/request movie titel:John Wick`
  - Alternativ Befehl: `/request movie-tmdb id:tt2911666`<br/><br/>
  
- ***#serien-wünsche***
  - Befehl: `/request tv titel:Prison Break`
  - Alternativ Befehl: `/request tv-tvdb id:360115`

===

==- Kann ich Filme oder Serien für Reisen herunterladen?

Ja, das ist möglich!  
Bitte beachte, dass dies unter Fair-Use erfolgen muss, da es die Serverleistung für andere Nutzer beeinträchtigt.


===

==- Warum werden Cover und Beschreibungen nicht richtig angezeigt?

Dazu muss die AppBox einmal neu gestartet und die Metadaten neu eingelesen werden.  

[!badge icon="warning" text="Wichtig:"]  
Nicht die Mediathek, sondern die Metadaten müssen neu eingelesen werden!

<h3>In Plex einloggen</h3>

1. [Plex Login](https://app.plex.tv/desktop/#!/login) öffnen.
2. Meldet euch in Plex mit eurer `E-Mail-Adresse` und `Passwort` ein.

<h3>Verwalten -> Mediatheken</h3>

1. `Mediatheken` öffnen.
2. In den Mediatheken auf die `3 Punkte` klicken.
3. `Alle Metadaten aktualisieren` anklicken.

===

==- Kann ich die Mediatheken mit Freunden oder Familie teilen?

Ja, das ist möglich!  


1. [Plex Login](https://app.plex.tv/desktop/#!/login) öffnen.
2. Meldet euch in Plex mit eurer `E-Mail-Adresse` und `Passwort` ein.
3. [Plex Home](https://app.plex.tv/desktop/#!/settings/plex-home) öffnen.
4. Auf `Plex-Benutzer einladen` klicken.
5. Nun wird der Plex `Benutzername` oder die `E-Mail-Adresse` des Freundes oder des Familienmitglieds eingegeben.
6. Jetzt `Bestätigen`.

===

==- Wie installiere ich ein Plex Media Server Update?

Wenn ein Update angeboten wird, wird es in `plex.tv` unter `Einstellungen -> Allgemein` angezeigt.

Um das Update zu installieren, gehe dazu in das Dashboard und starte den Server neu.

1. Logge dich mit den per `Email erhaltenen Daten` in `Kronos` ein.
2. Klicke nun auf den Server, als Beispiel: `Server #1245`
3. Jetzt auf `Restart` klicken.

Nach dem Neustart sollte das Update installiert sein.

===

==- Wie lasse ich den Discover Reiter für weitere Benutzer anzeigen?

Dies ist nur durch einen "Trick" möglich, indem der Quellcode der Seite bearbeitet wird.

1. [Plex Login](https://app.plex.tv/desktop/#!/login) öffnen.
2. Meldet euch in Plex mit eurer `E-Mail-Adresse` und `Passwort` ein.
3. [Plex Online Medienquellen](https://app.plex.tv/desktop/#!/settings/online-media-sources) öffnen.
4. Bei `Discover Medienquellen` auf Bearbeiten klicken.
5. Klicke in der Dropdown-Liste mit der rechten Maustaste auf `Untersuchen`.
6. Suche nach der ID: `includeDiscoverSource`.

``` Ändere folgenden Wert von:
<option value="opt_out_managed">Disabled for Managed Users</option>

auf:

<option value="opt_in">Enabled</option>
```

7. Jetzt auf `Speichern` klicken.

===

==- Wie entferne ich den Server von meinem Plex Konto?

Bitte beachte, dass dadurch der Server neu verbunden (geclaimt) werden muss und einige Einstellungen verloren gehen.

1. [Plex Login](https://app.plex.tv/desktop/#!/login) öffnen.
2. Meldet euch in Plex mit eurer `E-Mail-Adresse` und `Passwort` ein.
3. [Zugelassene Geräte](https://app.plex.tv/desktop/#!/settings/devices/pms) öffnen.
4. `Plex Media Server` suchen und rechts auf das `X` klicken.
5. Mit der Schaltfläche `Entfernen` bestätigen.

===

---
