<!--
author:   Sophie Matter, Jörg Lohrer

version:  0.1.0
language: de

date:     2024-04-18

logo:     https://raw.githubusercontent.com/rpi-virtuell/oer-github-tutorial-liascript/main/img/preview.png

tags:     OER, Git, GitHub, Tutorial, LiaScript

comment:  Dieses Tutorial zeigt, wie man OER einfach auf GitHub mit LiaScript veröffentlicht.
          Indem du nur ein paar einfache Schritte befolgst, kannst du deine eigenen OER erstellen, kostenlos
          auf GitHub veröffentlichen und sie in unserem OER-Suchindex OERSI in weniger als fünf Minuten aufnehmen!

@attribute

Technische Informationsbibliothek (TIB) - Leibniz-Informationszentrum
Technik und Naturwissenschaften - Universitätsbibliothek
<hr>
Lizenz: <a target="_blank" href="https://creativecommons.org/licenses/by/4.0/deed.de">CC BY 4.0 DEED</a>

@end

@style
section {
  margin-top: 1em;
  margin-bottom: 1em;
}
@end

-->

# Erstelle und veröffentliche OER auf GitHub mit LiaScript

Wir glauben, dass offene Bildungsressourcen (OER) mit Werkzeugen erstellt werden können, die die Open-Source-Community seit vielen Jahren erfolgreich verwendet. Dieses Tutorial führt dich durch die Erstellung von offenen Bildungsressourcen (OER) mit GitHub. Mit unserer GitHub-Vorlage kannst du in nur wenigen Minuten deine eigenen OER erstellen und veröffentlichen.

> Dies ist nur eine technische Anleitung.
> Bitte überprüfe und beachte die gesetzlichen Vorschriften deines Landes, z. B. ob und wie du ein Impressum bereitstellen musst.

<section>

## Was ist in diesem Tutorial enthalten:

* [Schnellstart](#quick-start)
* [Schritt für Schritt](#requirements)
* [Referenz](#reference)
* [Fehlerbehebung](#troubleshooting)
* [FAQ](#faq)

</section>

<section>

## Mögliche Formate für deine OER

Dieses Tutorial konzentriert sich auf unsere Vorlage.
Du könntest jedoch auch andere Formate verwenden.

</section>

<section>

## LiaScript

![LiaScript](img/preview.png)

LiaScript ist das, womit dieses Tutorial erstellt wurde. Alles, was für die Anzeige deiner OER mit LiaScript erforderlich ist, ist eine Markdown-Datei, die irgendwo gehostet wird. Es ist der schnellste und einfachste Weg zu deinem ersten OER.

[Gehe zu LiaScript](https://liascript.github.io)

</section>

<section>

## Markdown-Dokumentenvorlage

<a href="https://tibhannover.github.io/oer-github-tutorial-template/" target="_blank"><img src="img/template.png"/></a>
<br>
<br>

Unsere Markdown-Dokumentenvorlage ermöglicht es dir, deine OER schnell auf GitHub Pages mit nur wenigen Schritten zu hosten. Eine Webseite sowie verschiedene Formate wie PDF und ePub werden automatisch mit jeder Änderung an deinem OER generiert.

Du kannst dieses Tutorial, das mit unserer Vorlage erstellt wurde, hier sehen: [Vorlage OER Tutorial](https://tibhannover.github.io/oer-github-tutorial-template/)

[Unsere Vorlage auf GitHub ansehen](https://github.com/tibhannover/oer-github-tutorial-template/)

</section>

<section>

## JupyterBook

<a href="https://smatts.github.io/oer-tutorial-jupyter-book/00_intro.html" target="_blank"><img src="img/jupyterbook.png" /></a><br><br>

JupyterBook ist ein Programm, das schnell anpassbare Bücher erstellen kann. Es erlaubt sogar die Ausführung von Python-Code in Form von Jupyter-Notebooks.

Du kannst dieses Tutorial, das mit JupyterBook erstellt wurde, hier sehen: [Jupyter OER Tutorial](https://smatts.github.io/oer-tutorial-jupyter-book/00_intro.html)

[Gehe zu JupyterBook](https://jupyterbook.org)

> Nach Abschluss dieses Tutorials wirst du ein automatisch generiertes OER mit deinem eigenen Inhalt und Metadaten haben, das kostenlos auf GitHub veröffentlicht wird und bereit ist, in unseren OER-Suchindex [OERSI](https://oersi.org) aufgenommen zu werden.

</section>

## Schnellstart

> Wenn du schnell loslegen möchtest, kannst du diesem Schnellstart-Tutorial folgen und in nur wenigen Minuten ein einfaches OER erstellen.

<section>

### 1. Erstelle ein GitHub-Konto, falls du noch keines hast

Da wir unsere OER auf [GitHub](https://github.com/) hosten werden, ist ein kostenloses GitHub-Konto erforderlich. Falls du noch kein Konto hast, gehe zur Anmeldeseite von GitHub und erstelle ein kostenloses Konto: [https://github.com/signup](https://github.com/signup). Logge dich anschließend in dein Konto ein.

</section>

<section>

### 2. Erstelle dein Projekt

Erstelle ein neues Repository auf [GitHub](https://github.com) oder [GitLab](https://gitlab.com). Weise den Besitzer des Repositories dir selbst (oder einer Gruppe deiner Wahl, falls du Mitglied einer bist) zu und gib ihm einen kurzen, aber aussagekräftigen Namen, der dein OER beschreibt. Dieser Name wird auch für die URL zu deinem OER verwendet. Optional kannst du eine Beschreibung hinzufügen. Stelle sicher, dass das Repository auf **öffentlich** gesetzt ist.

</section>

<section>

### 3. Fülle das Projekt mit deinem Inhalt

Erstelle eine Markdown-Datei in deinem Repository und fülle sie mit deinem Inhalt.

Du kannst die Datei entweder lokal erstellen und auf GitHub hochladen oder sie direkt auf GitHub erstellen.

</section>

<section>

### 4. Generiere das OER

Gehe einfach zur [LiaScript-Website](https://liascript.github.io) und füge die **rohe** URL deiner Markdown-Datei dort ein. LiaScript generiert nun dein OER.

</section>

<section>

### 5. Füge deine Metadaten hinzu

Gehe zu unserem [Metadatengenerator](https://oersi.gitlab.io/metadata-form/metadata-generator.html) und füge die Metadaten ein, die dein OER beschreiben. In der oberen rechten Ecke hast du die Möglichkeit, die Sprache zwischen **Deutsch** ("DE") und **Englisch** ("EN") zu wechseln.

Sobald du fertig bist, klicke unten auf der Seite auf die Schaltfläche "Generieren". Die Metadaten werden nun in einem Format generiert, das unsere Vorlage versteht. Kopiere nun alles in deine Zwischenablage. Dafür kannst du auf "Kopieren" klicken.

In deinem Repository klicke auf die Datei `metadata.yml` und dann auf das Stiftsymbol ("Diese Datei bearbeiten"), um die Datei zu bearbeiten. Lösche den Inhalt der Datei und füge die Metadaten aus deiner Zwischenablage ein. Klicke nun auf die grüne Schaltfläche "Änderungen übernehmen..." und bestätige mit "Änderungen übernehmen".

Nun kannst du unten auf der Seite auf `Generate` klicken. Dies generiert die Metadaten im richtigen Format. Du kannst die Ausgabe dann entweder durch Klicken auf die Schaltfläche `Kopieren` in deine Zwischenablage kopieren oder indem du den gesamten Text markierst (<kbd>Ctrl</kbd> + <kbd>A</kbd>) und kopierst (<kbd>Ctrl</kbd> + <kbd>C</kbd>).

!?[Metadaten hinzufügen](videos/metadata-placeholder.mp4)

</section>

<section>

### Fertig!

Auf der Startseite deines Repositories, im Inhalt der Datei `README.md`, gibt es mehrere Links, mit denen du deine generierten Dokumente anzeigen kannst. Klicke auf den Link `landing page`, um eine Seite anzuzeigen, die Metadaten über dein OER auflistet und mehrere Links zu verschiedenen Ausgabeformaten bereitstellt (wie eine Webversion, eine PDF-Version, ...).

> Um dein OER in den OER-Suchindex [oersi.org](https://oersi.org) aufzunehmen, gehe zum Abschnitt `About` im Index deines Repositories, klicke auf das Einstellungs-Symbol und füge `open-educational-resources` zu den `Topics` hinzu. Dein Kurs wird über Nacht indiziert und am nächsten Tag angezeigt.

</section>

## Schritt-für-Schritt-Tutorial

Das Schritt-für-Schritt-Tutorial besteht aus den folgenden Schritten, die du entweder über die Seitenleiste, die Pfeile unten oder einfach mit den Pfeiltasten auf deiner Tastatur durchklicken kannst.

* [Anforderungen](#requirements)
* [Erstelle ein Projekt](#create-a-project)
* [Fülle es mit deinem eigenen Inhalt](#fill-with-content)
* [Generiere die Ausgabe](#generate-liascript)
* [Füge deine Metadaten hinzu](#add-your-metadata)
* [In OERSI einfügen](#insert-your-oer-in-oersi)

### Anforderungen

> Für dieses Tutorial **benötigst du ein GitHub-Konto**.
> Es wird auch empfohlen, sich mit Markdown vertraut zu machen, einer Auszeichnungssprache, mit der formatierter Text unter Verwendung von nur einfachem Text erstellt werden kann, da Markdown zur Erstellung und Formatierung deines Inhalts verwendet wird.
>
> Wenn du bereits ein GitHub-Konto hast und die grundlegende Markdown-Syntax kennst, kannst du diesen Teil überspringen und direkt zum Abschnitt [Projekt erstellen](#create-a-project) gehen.

<section>

### Erstelle ein GitHub-Konto

Wenn du noch kein Konto hast, gehe zu [GitHub](https://github.com/) und melde dich an. Bestätige deine E-Mail-Adresse und logge dich ein.

</section>

<section>

### Markdown

Aus Matt Cones [Markdown-Guide](https://www.markdownguide.org/getting-started/):

> Markdown ist eine leichte Markup-Sprache, die du verwenden kannst, um Formatierungselemente zu Klartext-Dokumenten hinzuzufügen. Markdown wurde 2004 von John Gruber erstellt und ist heute eine der weltweit beliebtesten Markup-Sprachen.
>
> Die Verwendung von Markdown unterscheidet sich von der Verwendung eines WYSIWYG-Editors. In einer Anwendung wie Microsoft Word klickst du auf Schaltflächen, um Wörter und Phrasen zu formatieren, und die Änderungen sind sofort sichtbar. Markdown ist nicht so. Wenn du eine Markdown-formatierte Datei erstellst, fügst du dem Text Markdown-Syntax hinzu, um anzugeben, welche Wörter und Phrasen anders aussehen sollen.
>
> Zum Beispiel, um eine Überschrift zu kennzeichnen, füge ein Nummernzeichen davor ein (z. B. # Überschrift eins). Oder um eine Phrase fett zu machen, füge zwei Sternchen davor und danach ein (z. B. **dieser Text ist fett**). Es kann eine Weile dauern, bis du dich daran gewöhnt hast, Markdown-Syntax in deinem Text zu sehen, insbesondere wenn du an WYSIWYG-Anwendungen gewöhnt bist.

Wenn du mehr über Markdown erfahren möchtest, was es ist und was du damit machen kannst, kannst du diesen Leitfaden lesen: [Loslegen](https://www.markdownguide.org/getting-started/).

Um grundlegende Formatierungsoptionen zu sehen, sieh dir das [Cheat Sheet](https://www.markdownguide.org/cheat-sheet/) an. Weitere grundlegende Syntax findest du im Leitfaden [Grundlegende Syntax](https://www.markdownguide.org/basic-syntax/).

Einige der grundlegenden Markdown-Syntaxen werden im Referenzteil dieses Tutorials gezeigt: [Referenz: Markdown](#markdown-1).

</section>

### Erstelle ein Projekt

> Der Ort, an dem du dein OER ablegst, wird als `Repository` bezeichnet. Du kannst es dir als ein Projekt vorstellen, in dem sich alle deine Dateien befinden.

Sobald du bei GitHub eingeloggt bist, erstelle ein neues Repository, indem du auf das Pluszeichen in der oberen rechten Ecke der Webseite klickst und "Neues Repository" auswählst.

<center>
![Repository erstellen](img/new_repository_button.png)
</center>

Jetzt musst du einige Details eingeben.

<center>
![Repository-Erstellungsformular](img/new_repository_form.png)
</center>

Weise das Repository dem richtigen Besitzer zu und gib ihm einen kurzen, aber aussagekräftigen Namen. Der Name wird auch die URL des Repositories sein. Du kannst optional eine Beschreibung hinzufügen. Stelle jetzt sicher, dass die Sichtbarkeit des Repositories auf **öffentlich** eingestellt ist. Dies hat zwei Hauptgründe: erstens, damit Leute dein OER sehen können, und zweitens, um die GitHub Pages-Funktionalität zu nutzen, auf die wir später eingehen werden.

Wenn du die Option "README-Datei hinzufügen" aktivierst, erstellt GitHub automatisch eine Datei namens `README.md` in deinem Repository, in der du das Repository beschreiben kannst. Diese wird im Index deines Repositories angezeigt.

Du kannst jetzt auch eine Lizenz auswählen.

<center>
![Lizenz auswählen](img/license_selector.png)
</center>

Bestätige zuletzt, indem du auf "Repository erstellen" klickst.

### Mit Inhalt füllen

LiaScript interpretiert `Markdown`-Dateien. Du musst also **eine** Markdown-Datei in deinem neuen Repository erstellen. Weitere Informationen zu Markdown findest du im [Markdown-Abschnitt](#markdown-1) im Referenzteil dieses Tutorials.

Um eine neue Datei zu erstellen, gehe zu deinem Repository und klicke auf `Datei hinzufügen` und dann auf `Neue Datei erstellen`.

![Neue Datei erstellen](img/create-new-file-cropped.png)

Gib deiner neuen Datei einen Dateinamen. **Stelle sicher, dass es sich um eine Markdown-Datei handelt, indem du den Dateinamen mit `.md` endest**. Gib nun deinen Inhalt in der Markdown-Auszeichnungssprache ein.

![Dateiinhalt eingeben](img/new-file-filename-cropped.png)

Sobald du fertig bist, kannst du deine Änderungen speichern, indem du in der oberen rechten Ecke auf die grüne Schaltfläche `Änderungen übernehmen...` klickst.

![Inhalt ändern](img/commit-changes-1.png)

Füge eine aussagekräftige, aber kurze Commit-Nachricht hinzu, die eine Nachricht ist, die die vorgenommenen Änderungen beschreibt, und optional eine längere Beschreibung. Bestätige dann, indem du auf die grüne Schaltfläche `Änderungen übernehmen` klickst.

<center>
![Inhalt ändern](img/commit-changes-2.png)
</center>

<section>

#### Warum kann ich den aktualisierten Inhalt nicht sehen?

Wenn du alle deine Änderungen übernommen hast und sie immer noch nicht auf deiner generierten Landing Page und in den Dokumenten sehen kannst, versuche, den Cache zu löschen und die Seite neu zu laden (oder öffne deine Seite in einem neuen privaten Tab). Eine Abkürzung zum Neuladen und gleichzeitigen Auffrischen ist <kbd>Ctrl</kbd> + <kbd>F5</kbd>.

Bitte beachte, dass es einige Minuten dauern kann, bis die Änderungen in den generierten Dokumenten eingebaut werden.

Wenn es immer noch nicht funktioniert, überprüfe dein Dokument auf verbotene Zeichen (wie Emojis oder andere Unicode-Zeichen) und stelle sicher, dass die Namen deiner Markdown-Dateien keine Leerzeichen oder andere ungeeignete Zeichen für Dateinamen enthalten, da beides die Dokumentengenerierungsskripte brechen kann.

</section>

### Generiere LiaScript

Um deinen Inhalt in LiaScript anzuzeigen, musst du einfach einen Link zu deiner Markdown-Datei eingeben. Um diesen Link zu erhalten, gehe zu deinem Repository und klicke auf die gerade erstellte Datei. Kopiere nun einfach den Link in der Adressleiste deines Browsers.

![Link kopieren](img/copy-link-cropped.png)

Alles, was du jetzt tun musst, ist, zu <a href="https://liascript.github.io/" target="_blank">liascript.github.io</a> zu gehen und den Link einzufügen.

![Link einfügen](img/paste-link-marked.png)

Jetzt solltest du deinen Inhalt in LiaScript sehen!

<section>

#### Den Link für später speichern

Du kannst den Link zu deinem LiaScript OER aus der Adressleiste deines Browsers kopieren und in deine `README.md`-Datei einfügen, damit du jederzeit darauf zugreifen kannst, indem du einfach auf einen einfachen Link in deinem Repository klickst.

![LiaScript-Link kopieren](img/copy-liascript-link.png)

Bearbeite die `README.md`, indem du auf die Datei klickst und dann auf die Schaltfläche mit dem Bleistift in der oberen rechten Ecke der Dateivorschau klickst.

![README bearbeiten](img/edit-readme.png)

Füge deinen Link ein und übernehme die Datei.

</section>

### Füge deine Metadaten hinzu

> Metadaten sind die Daten, die dein OER beschreiben. Dazu gehören Informationen wie Titel, Autor, Lizenz und vieles mehr. Wenn du deinem Repository keine Metadaten hinzufügst, ist unklar, worum es bei deinem OER geht, von wem es stammt, ob und wie dein OER verwendet werden kann usw. Aus diesem Grund haben wir eine `metadata.yml`-Datei in unserem Repository. Mit dieser Datei können wir die Informationen über das OER direkt im Repository einfügen. Dies ist auch notwendig, um dein OER in einen Suchindex wie [OERSI](https://oersi.org) einzufügen.
> Dieser Abschnitt zeigt, wie du die Dummy-Metadaten im Repository durch die richtigen Metadaten ersetzen kannst, die dein OER beschreiben.

Vielleicht ist der einfachste Weg, deine eigenen Metadaten für dein Repository im richtigen Format zu generieren, den [OERSI-Metadatengenerator](https://oersi.gitlab.io/metadata-form/metadata-generator.html) zu verwenden und mindestens alle erforderlichen Felder auszufüllen, aber versuche, so viel wie möglich auszufüllen.

![Metadatengenerator](img/metadata-form.png "Metadatengenerator")

Nun kannst du unten auf der Seite auf `Generate` klicken. Dies generiert die Metadaten im richtigen Format. Du kannst die Ausgabe dann entweder durch Klicken auf die Schaltfläche `Kopieren` in deine Zwischenablage kopieren oder indem du den gesamten Text markierst (<kbd>Ctrl</kbd> + <kbd>A</kbd>) und kopierst (<kbd>Ctrl</kbd> + <kbd>C</kbd>).

![Ausgabe in die Zwischenablage kopieren](img/metadata-copy-to-clipboard.png)

In deinem GitHub-Repository bearbeite die Datei `metadata.yml`. Lösche nun den gesamten Dateiinhalt und füge die Ausgabe des Generators ein. Zum Speichern klicke in der oberen rechten Ecke auf `Änderungen übernehmen...`. Bestätige, indem du auf `Änderungen übernehmen` klickst.

<section>

#### Video: Aktualisiere die Metadaten

!?[Metadaten aktualisieren](videos/metadata-placeholder.mp4)

</section>

### Füge dein OER in OERSI ein

> Angenommen, dass...
>
> * du deinen gesamten fertigen Kurs- oder Dokumenteninhalt ins Repository gestellt hast und er entweder alphabetisch geordnet ist oder du die richtige Reihenfolge in der Datei `config.yml` definiert hast,
> * du die `Pages` für `GitHub Actions` aktiviert hast und es während der Action-Ausführung keine Fehler gibt, so dass du eine veröffentlichte Seite hast, die die aktuelle Version deines Repositories darstellt,
> * du vollständige und korrekte Metadaten eingegeben hast, die sicherstellen, dass die Lizenz korrekt ist und du nicht gegen die Lizenz eines anderen Werks verstößt,
> * du in deiner Datei `metadata.yml` den Status deines kreativen Werks auf `Veröffentlicht` und das Bildungsniveau auf `Universität` gesetzt hast,
>
> **dann bist du bereit, dein OER in OERSI einzufügen!**

Um deinen Kurs in den Open Educational Resources Search Index (OERSI) einzufügen, gehe zu den `About`-Einstellungen im Index deines Repositories. Füge dann bei `Topics` `open-educational-resources` hinzu.

![About-Einstellungen](img/about.png)

![Thema festlegen](img/about-topics.png)

Der [OERSI](https://oersi.org) aktualisiert seinen Index jede Nacht. So kannst du dein OER am nächsten Tag entweder über die Suchleiste finden oder indem du die Filter auf der linken Seite verwendest (z. B. nach deinem Namen unter `Autor` suchen oder den `Anbieter` auf GitHub setzen, um nur OER von GitHub anzuzeigen).

Wenn du deine Änderungen im OERSI sofort sehen möchtest, kannst du den [Datensatz-Aktualisierer](https://oersi.org/resources/pages/de/record_update/) verwenden.

Um das OER aus OERSI zu entfernen, setze einfach den Status (`creativeWorkStatus`) in der `metadata.yml`-Datei auf `Entwurf` oder `Unvollständig` (oder alternativ könntest du das Thema `open-educational-resources` entfernen).

### Fertig!

Herzlichen Glückwunsch, du hast es geschafft!

Wenn du mehr darüber erfahren möchtest, was du mit dieser Vorlage machen kannst, kannst du mit dem [Referenzteil](#reference) fortfahren.

## Referenz

> Du hast dein OER in verschiedenen Ausgabeformaten, komplett mit deinem eigenen Inhalt und Metadaten, und es ist sogar bereits im [oersi](https://oersi.org) indexiert,
> aber du möchtest mehr darüber erfahren, was du mit dieser Vorlage machen kannst?

In diesem Teil des Tutorials heben wir weitere Konfigurationsoptionen, Markdown-Grundlagen, Workflows in GitHub und vieles mehr hervor.

* [Markdown](#markdown-1)
* [Git](#git)
* [Offline arbeiten](#working-offline)
* [Sofortige Aktualisierung in OERSI](#immediate-update-in-oersi)
* [Verschiedene Formate](#different-formats)

### Markdown

> Für einen guten Überblick darüber, was Markdown ist und was du damit machen kannst, kannst du den Markdown-Guide von Matt Cone überprüfen:
>
> * [Was ist Markdown und warum sollte ich es verwenden?](https://www.markdownguide.org/getting-started/)
>
> * [Grundlegende Syntax](https://www.markdownguide.org/basic-syntax/)

<section>

#### Überschriften

Um eine Überschrift zu erstellen, füge vor einem Wort oder einer Phrase Nummernzeichen (`#`) hinzu. Die Anzahl der Nummernzeichen, die du verwendest, sollte der Überschriftenebene entsprechen. Zum Beispiel, um eine Überschriftenebene drei (`<h3>`) zu erstellen, verwende drei Nummernzeichen (z. B. `### Meine Überschrift`) [[1](https://www.markdownguide.org/basic-syntax/)].

<!-- data-type="none" -->
| Überschriftenebene   | Wie man es schreibt        | Wie es aussieht             |
| --------------- | ---------------------- | ------------------------ |
| Überschriftenebene 1 | # Überschriftenebene 1      | <h1>Überschriftenebene 1</h1> |
| Überschriftenebene 2 | ## Überschriftenebene 2     | <h2>Überschriftenebene 2</h2> |
| Überschriftenebene 3 | ### Überschriftenebene 3    | <h3>Überschriftenebene 3</h3> |
| Überschriftenebene 4 | #### Überschriftenebene 4   | <h4>Überschriftenebene 4</h4> |
| Überschriftenebene 5 | ##### Überschriftenebene 5  | <h5>Überschriftenebene 5</h5> |
| Überschriftenebene 6 | ###### Überschriftenebene 6 | <h6>Überschriftenebene 6</h6> |

</section>

<section>

### Markdown-Elemente

<!-- data-type="none" -->
| Element         | Wie man es schreibt                   | Wie es aussieht                                                                        |
| --------------- | --------------------------------- | ----------------------------------------------------------------------------------- |
| Fett            | \*\*Fetter Text\*\*                 | **Fetter Text**                                                                       |
| Kursiv          | \*Kursiver Text\*               | *Kursiver Text*                                                                       |
| Blockquote      | > Blockquote                      | <blockquote class="lia-quote"> Zu sehen oben in diesem Abschnitt  </blockquote> |
| Geordnete Liste    | 1. Erstes Element <br> 2. Zweites Element | <ol class="lia-list--ordered"><li>Erstes Element</li><li>Zweites Element</li></ol>          |
| Ungeordnete Liste  | - Erstes Element <br> - Zweites Element   | <ul class="lia-list--unordered"><li>Erstes Element</li><li>Zweites Element</li></ul>        |
| Code            | \`code\`                          | `code`                                                                              |
| Horizontale Linie | \-\-\-                            | <hr>                                                                                |
| Link            | [Link-Text](Link-URL)             | [Markdown Guide](https://www.markdownguide.org)                                     |
| Bild           | ![Alt-Text](Bild-URL)            | ![Bild zeigt den Textplatzhalter](http://via.placeholder.com/50x50)             |

[1] Matt Cone, [markdownguide.org](https://www.markdownguide.org), [Grundlegende Syntax](https://www.markdownguide.org/basic-syntax/)

</section>

<section>

### Links zu anderen Abschnitten

Du kannst innerhalb deines Dokuments zu Abschnitten verlinken, indem du die im obigen Tabellenabschnitt gezeigte Link-Syntax verwendest. Die Links werden aus der Überschrift generiert:

* `# Überschrift` -> `#ueberschrift` (Du kannst darauf wie folgt verweisen: `[Überschrift](#ueberschrift)`)
* `# Überschrift 1` -> `#ueberschrift-1`
* `### Niedrigere Überschriftenebene!` -> `#niedrigere-ueberschriftenebene`

Du kannst auch benutzerdefinierte Links wie folgt setzen:

`## Meine Überschrift {#custom-id}`

Jetzt ist der Link zu diesem Abschnitt `#custom-id`.

</section>

### Git

> Hier findest du nur einen sehr kurzen Überblick über Git.
> Wenn du mehr über Git erfahren möchtest, findest du online eine Fülle von kostenlosen Tutorials, Büchern und Videos über Git, wie es funktioniert und wie man es verwendet.
> Wir empfehlen dir, das kostenlose Online-Lehrbuch [Pro Git](https://git-scm.com/book/en/v2) zu überprüfen.

<section>

### Was ist Git und warum solltest du es verwenden?

Hast du jemals an verschiedenen Versionen eines Dokuments gearbeitet oder sogar mit anderen Leuten zusammengearbeitet? Dann weißt du wahrscheinlich, wie schwer es ist, den Überblick über Änderungen zu behalten, und wie einfach es ist, sie versehentlich zu überschreiben. Git ist ein Werkzeug, das dabei hilft. **Es ist ein sogenanntes *Versionskontrollsystem*.**
Um mehr über Versionskontrolle zu erfahren, kannst du den [Versionskontroll-Abschnitt des Pro Git-Buchs](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) überprüfen.

> Durch das Abspielen des Videos erklärst du dich damit einverstanden, dass YouTube Informationen über dich in Form von Cookies abruft und speichert.

!?[YouTube: Git in 100 Sekunden erklärt](https://www.youtube.com/watch?v=hwP7WQkmECE)

</section>

<section>

### Wie funktioniert Git?

Git wird verwendet, um Änderungen an den Dateien in deinem Repository nachzuverfolgen. Sobald du eine Datei zu Git hinzufügst, wird sie verfolgt. Git erkennt nun automatisch, ob die Datei geändert wurde oder nicht. Du kannst dann Dateien stagen und sie einem Commit hinzufügen. All diese Commits bilden deine Historie, du kannst sehen, welche Änderungen wann von wem vorgenommen wurden und du kannst sogar Dateien auf bestimmte Commits zurücksetzen.

Es ist auch möglich, mehrere Branches zu haben. Du beginnst mit einem Branch, normalerweise genannt **main** oder **master**. Zu jedem beliebigen Zeitpunkt kannst du jedoch von jedem Branch aus einen neuen Branch erstellen. Dort kannst du Dateien ändern, ohne dass auf dem Haupt-Branch irgendetwas davon betroffen ist - du arbeitest im Grunde parallel, als ob du dein gesamtes Repository an einem anderen Ort kopiert hättest, aber viel effizienter. Außerdem kannst du problemlos zwischen den Branches wechseln und Änderungen von einem Branch in einen anderen mergen. Dies macht es einfach, nicht nur eine stabile Version auf dem Haupt-Branch zu haben, während Änderungen auf anderen Branches vorgenommen werden, sondern auch mit anderen zusammenzuarbeiten, ohne dass die Änderungen der anderen irgendetwas überschreiben.

Das Arbeiten an verschiedenen Branches und schließlich deren Zusammenführung kann zu Merge-Konflikten führen. Merge-Konflikte entstehen, wenn zwei Änderungen an denselben Zeilen einer Datei vorgenommen wurden. Sie werden gelöst, indem entschieden wird, welche Änderungen beibehalten werden sollen, oder indem sie manuell zusammengeführt werden.

> Durch das Abspielen des Videos erklärst du dich damit einverstanden, dass YouTube Informationen über dich in Form von Cookies abruft und speichert.
>
> !?[Wie Git funktioniert: In 4 Minuten erklärt](https://www.youtube.com/watch?v=e9lnsKot_SQ)

</section>

### Offline arbeiten

> In diesem Tutorial arbeiten wir die ganze Zeit online. Wir erstellen alle Dateien direkt auf GitHub. Eine andere Möglichkeit zu arbeiten ist, offline in einem lokalen Ordner auf deinem Computer zu arbeiten und *dann* deine Dateien in ein Git-Repository hochzuladen. Dies erfordert jedoch einige Kenntnisse über Git und einen Texteditor.

Da wir mit `Git` arbeiten (siehe [Git-Abschnitt](#git) für weitere Informationen) und unser Material auf `GitHub` veröffentlichen möchten (siehe [GitHub-Abschnitt](#github)), müssen wir einen Weg finden, unsere Offline-Arbeit online zu bringen. Dafür solltest du den [Git-Abschnitt](#git) überprüfen.

<section>

### Editoren

Du kennst Texteditoren wie Word oder LibreOffice. Wir möchten jedoch *reinen Text* verwenden, der für Maschinen lesbar ist. Deshalb arbeiten wir mit [Markdown](#markdown-1), um unseren *reinen Text* zu formatieren.

Es gibt viele Editoren, die dir beim Schreiben von Texten mit der Markdown-Syntax helfen. Sie verwenden Syntax-Hervorhebung, um die Struktur von Markdown besser zu verstehen, und können eine Live-Vorschau anzeigen, während du tippst.

![Editor](img/vscode.png "VSCodium, die Open-Source-Version des beliebten Editors VSCode")

Der Editor, den du im Screenshot sehen kannst, heißt **VSCodium**, die Open-Source-Version eines beliebten Editors **VSCode** von Microsoft. In diesem Editor kannst du Plugins installieren, die dir helfen können. Zum Beispiel kannst du ein Plugin installieren, das eine Vorschau deines LiaScript-Kurses in deinem Browser rendert, ohne dass du deine Änderungen hochladen musst. Es verfügt auch über eine integrierte Git-Funktionalität, die dir hilft, deine Änderungen zu veröffentlichen.

</section>

<section>

### Bring deine Änderungen online

Du *könntest* deine lokal bearbeiteten Dateien auf GitHub hochladen, entweder indem du einfach diese Datei hochlädst oder indem du die Datei, die du ändern möchtest, bearbeitest und den Inhalt dieser Datei durch deinen lokalen Inhalt ersetzt.

Der bessere Weg ist jedoch, dafür Git zu verwenden - entweder durch die integrierte Git-Funktionalität deines Editors oder durch die Verwendung des Git-Programms selbst. Bitte überprüfe die Fülle an kostenlosen Online-Ressourcen, wie man dies tut.

> Durch das Abspielen des Videos erklärst du dich damit einverstanden, dass YouTube Informationen über dich in Form von Cookies abruft und speichert.
>
> !?[YouTube: Git mit Visual Studio Code verwenden (Offizielles Anfänger-Tutorial)](https://www.youtube.com/watch?v=i_23KUAEtUM)

</section>

### Sofortige Aktualisierung in OERSI

> Dein OER wird automatisch in den [OERSI](https://oersi.org) eingefügt, wenn du die im Abschnitt [Füge dein OER in OERSI ein](#insert-your-oer-in-oersi) aufgeführten Anforderungen erfüllst. Die Ressourcen werden jede Nacht aktualisiert. Wenn du **sofort** Änderungen sehen möchtest, kannst du den (experimentellen) Datensatz-Aktualisierer verwenden.

Gehe zur [Datensatz-Aktualisierer-Seite](https://oersi.org/resources/pages/de/record_update/) auf [oersi.org](https://oersi.org). Füge den Link zu deinem GitHub-Repository oder zur generierten Landing Page deines OER ein.

![Datensatz-Aktualisierer](img/record-updater.png)

Klicke dann auf Aktualisieren. Dein OER sollte jetzt im OERSI aktualisiert sein.

### Verschiedene Formate

> Nachdem du diesem Tutorial gefolgt bist, hast du dein OER von LiaScript gerendert. Du könntest jedoch auch ein anderes Format für dein OER verwenden.

Die Verwendung dieser Vorlage ist nicht die einzige Möglichkeit, OER mit GitHub zu hosten. Zum Beispiel läuft dieses Tutorial mit LiaScript. Außerdem musst du nicht *unbedingt* GitHub als deine Hosting-Plattform verwenden - andere git-basierte Plattformen wie GitLab können ebenfalls verwendet werden (für die meisten Formate ist es jedoch erforderlich, dass einige CI-Pipelines beim Git-Hoster automatisch ausgeführt werden). Derzeit haben wir jedoch keine Vorlagen mit automatischer Generierung für andere Plattformen.

Unten findest du eine kurze Liste mehrerer möglicher Formate, die dein OER verwenden könnte.

<section>

#### [Markdown-Dokumentenvorlage](https://github.com/TIBHannover/markdown-documents-template)

Dies ist die Vorlage, die in diesem Tutorial beschrieben wird. Wie du jetzt weißt, nimmt sie deine Markdown-Dateien, fügt sie zusammen und generiert verschiedene Formate daraus. Diese Formate sind verlinkt und können von der Landing Page heruntergeladen werden, die mit GitHub Actions und GitHub Pages generiert wird.

<!--  style="background-color:unset;" -->
> ✅ Einfache Einrichtung mit unserer Vorlage
> 
> ✅ Automatische Generierung verschiedener Formate
> 
> ✅ Kann interaktive Elemente enthalten
> 
> ✅ Immer die neuesten Änderungen online
> 
> ✅ GitHub verfolgt automatisch Änderungen an deinen Dateien
> 
> ✅ Einfache Zusammenarbeit mit anderen auf GitHub
>
> ✅ Anpassbar mit CSS
> 
> ❌ Benötigt ein GitHub-Konto
> 
> ❌ Anpassungen können knifflig sein

</section>

<section>

#### [Markdown-Folienvorlage](https://github.com/TIBHannover/markdown-slides-template)

Die Markdown-Folienvorlage ist der Markdown-Dokumentenvorlage aus diesem Tutorial sehr ähnlich. Aber anstelle eines einzigen Textdokuments erstellt die Folienvorlage mehrere Folien. Dazu erstellst du eine Markdown-Datei für einen Satz Folien, und die Vorlage generiert die Folien sowohl im HTML- als auch im PDF-Format und zeigt eine Liste aller generierten Folien zusammen mit Vorschau-Bildern auf einer GitHub-Seite an.

<!--  style="background-color:unset;" -->
> ✅ Einfache automatisch generierte Folien in zwei Formaten
> 
> ✅ Einfache Einrichtung mit unserer Vorlage
> 
> ✅ Automatisch aktualisierte Übersichtsseite
> 
> ✅ Immer die neuesten Änderungen online
> 
> ✅ Verfolgt automatisch Änderungen an deinen Dateien
> 
> ✅ Einfache Zusammenarbeit mit anderen
> 
> ❌ Folien sind nur teilweise anpassbar
> 
> ❌ Benötigt ein GitHub-Konto

</section>

<section>

#### [LiaScript](https://liascript.github.io)

LiaScript nimmt eine Markdown-Datei und generiert automatisch ein Kursformat daraus. Das Tutorial, das du gerade ansiehst, wurde tatsächlich mit LiaScript erstellt! Oder vielmehr, die Markdown-Datei, in der dieses Tutorial geschrieben ist, wird von LiaScript interpretiert, das diesen Kurs erstellt hat. Also alles, was du wirklich brauchst, ist eine Markdown-Datei.

<!--  style="background-color:unset;" -->
> ✅ Super einfach einzurichten, du brauchst nur eine Markdown-Datei irgendwo im Internet!
> 
> ✅ Läuft überall 
> 
> ✅ Große Anzahl an Elementen, die du verwenden kannst, wie Diagramme, Quizfragen, ...
> 
> ✅ Keine Installation, alles geschieht live & online
> 
> ✅ Einfaches Durchklicken der verschiedenen Abschnitte
> 
> ✅ Automatische Übersetzung in viele verschiedene Sprachen
> 
> ✅ Interaktive Elemente und erweitertes Markdown können verwendet werden
> 
> ✅ Responsive Website
> 
> ❌ Nur online, kein Download
> 
> ❌ Abhängig von einem einzigen Dienst
> 
> ❌ Nur eine Markdown-Datei gleichzeitig

</section>

<section>

#### [Static Site Generators](https://github.com/collections/static-site-generators)

Ein statischer Site-Generator generiert eine statische Site. In der Regel wird es möglich sein, deinen Inhalt auch mit Markdown zu schreiben, aber gleichzeitig wirst du in der Lage sein, dein Layout zu bearbeiten und mehr Elemente selbst hinzuzufügen, die der statische Site-Generator dann verwendet, um deine Webseite zu erstellen. Natürlich erfordert dies einige Grundkenntnisse in HTML, CSS und dem statischen Site-Generator, den du verwendest. Du solltest auch mit der Befehlszeile oder der Verwendung von GitHub Actions vertraut sein.

<!--  style="background-color:unset;" -->
> ✅ Erstellt eine leichte Webseite
> 
> ✅ Sehr anpassbar
> 
> ❌ Nicht für absolute Anfänger - du brauchst einige Kenntnisse in Webentwicklung
> 
> ❌ Es dauert länger, eine erste Version zum Laufen zu bringen / mehr Konfiguration und technisches Wissen erforderlich

</section>

<section>

#### [JupyterBooks](https://jupyterbook.org/en/stable/intro.html)

Jupyter Book ist ein kostenloses und Open-Source-Tool zur Erstellung von Online-Büchern. Du kannst Abschnitte und Unterabschnitte erstellen, durch die du klicken kannst. Diese werden einem Inhaltsverzeichnis hinzugefügt, das in einer Seitenleiste angezeigt oder über ein Menü aufgerufen werden kann. Es ist auch möglich, ausführbare Inhalte einzuschließen. Darüber hinaus kannst du dein Buch sowohl im Markdown- als auch im PDF-Format herunterladen. Du kannst mit einer von der Software selbst bereitgestellten Vorlage beginnen.

<!--  style="background-color:unset;" -->
> ✅ Erstellt Online-Bücher mit Abschnitten und Inhaltsverzeichnis zum Durchklicken
> 
> ✅ Ermöglicht viel Konfiguration und Strukturierung
> 
> ✅ Bietet den Download als Markdown und PDF
> 
> ✅ Kann ausführbare Inhalte enthalten
> 
> ❌ Nicht für absolute Anfänger (du wirst Befehle von der Befehlszeile ausführen oder eine GitHub Action erstellen müssen)
> 
> ❌ Die Konfiguration erfolgt über Konfigurationsdateien, was schwierig zu lernen sein kann, wenn du mit dem Programmieren nicht vertraut bist

</section>

## Fehlerbehebung

Etwas funktioniert nicht? Vielleicht findest du dein Problem genau hier.

<section>

### Ich sehe meine Änderungen nicht

Du hast deinen Inhalt und deine Metadaten hinzugefügt, kannst deine Änderungen aber nicht auf deiner Landing Page und in den generierten Dokumenten sehen? Die folgenden Schritte könnten dir helfen.

1. Lösche deinen Cache und lade deine Seite/das Dokument neu

   Oft wird die alte Version der Seite noch im Cache deines Browsers geladen. Wenn du die Seite oder das Dokument durch gleichzeitiges Drücken von <kbd>Ctrl</kbd> + <kbd>F5</kbd> neu lädst, kannst du deine Seite neu laden und gleichzeitig den Cache dieser Seite löschen. Du kannst deine Seite oder dein Dokument auch in einem neuen privaten Tab oder Fenster öffnen, da der Browser dort normalerweise keinen Cache verwendet.

2. Überprüfe deine Dateinamen und Inhalte

   Überprüfe, ob dein Dateiname Zeichen wie **Leerzeichen** enthält. Diese sind nicht erlaubt und können dazu führen, dass LiaScript die URL nicht versteht.

   Stelle außerdem sicher, dass keine Skripte oder andere Dinge vorhanden sind, die den LiaScript-Interpreter zum Absturz bringen könnten.

3. Überprüfe deine Medien

   Manchmal können Bilder oder Videos dazu führen, dass die Dokumentengenerierung fehlschlägt. Normalerweise passiert dies, wenn du ein nicht unterstütztes Format verwendest. Halte dich an weit verbreitete Formate wie `png` und `jpg`, um sicher zu gehen.

</section>

<section>

### Meine Videos können nicht abgespielt werden

Wenn du deine Videos auf einer anderen Plattform als GitHub hostest, kannst du Probleme beim Abspielen deiner Videos bekommen. Dies liegt an einem Schutz von LiaScript, um nicht vertrauenswürdigen Code oder Medien auszuführen. Du kannst dies leicht beheben, indem du deine Videos in deinem Git-Repository speicherst. Es könnte sein, dass du deine Videos in einem iframe einbetten oder es auf andere Weise zum Laufen bringen kannst, die hier nicht beschrieben ist.

</section>

## FAQ

<section>

### Kann ich nicht-textuelle Dateien wie PDF-Dateien hochladen?

Ja, das kannst du! Git kann jedoch keine Änderungen an diesen Dateien nachverfolgen, es kann nur nachverfolgen, _dass_ sie geändert wurden.

</section>

<section>

### Warum sind die direkten Pfade zu meinen Dateien anders?

Du bist möglicherweise auf Links gestoßen, die `https://raw.githubusercontent.com/` enthalten. Wenn du dich fragst, was das bedeutet und warum GitHub deine URL auf diese Weise ändert, liegt der Grund darin:

Wenn du durch die Dateien deines Repositories auf GitHub gehst, siehst du sie eingebettet in die GitHub-Webseite, die es dir ermöglicht, mehrere Dinge zu tun, wie bearbeiten, löschen, den Verlauf anzeigen usw. Wenn du also einen Link zu dieser Datei hast, zeigt der Link auf diese Webseite und nicht auf die Datei selbst (die als *raw* Datei bezeichnet wird). Wenn du nur auf die Datei zugreifen möchtest, also die raw Datei, ermöglicht es dir GitHub, dies zu tun, indem du die URL in `https://raw.githubusercontent.com/` änderst.

</section>

<section>

### Wie kann ich einen neuen Ordner erstellen?

Du kannst keinen leeren Ordner erstellen. Das bedeutet, dass du Dateien in GitHub *in* diesem neuen Ordner hinzufügen musst. Entweder erstelle eine neue Datei und ändere den Pfad zu diesem neuen Ordner (d. h. anstatt eine neue Datei `file.md` zu erstellen, schreibe es mit einem neuen Ordner wie `newfolder/file.md`, ein neuer Ordner wird automatisch erstellt) oder lade einen nicht-leeren Ordner hoch.

</section>
