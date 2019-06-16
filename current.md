---
title: Adobe Experience Cloud – Versionshinweise
description: Juni 2019 Experience Cloud - Versionshinweise
doc-type: Versionshinweise
last-update: Juni 2019
author: mfrei
translation-type: tm+mt
source-git-commit: a4233ae2bcb89b8695b92385142ee25b654a2300

---


# Adobe Experience Cloud – Versionshinweise

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

>[!NOTE]
>Abonnieren Sie das [Prioritätsprodukt-Update von Adobe](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bevorstehende Versionen benachrichtigt zu werden. Sie erhalten drei bis fünf Werktage vor der Veröffentlichung der Version eine Benachrichtigung. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Releasedatum: 13. Juni 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [! DNL [Campaign](#ac)]
* [Mobile Services](#mobile)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Adobe Experience Platform – Versionshinweise

* See [[!DNL Experience Platform] release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) on Adobe.io for the latest updates to [!DNL Experience Platform].

### [!DNL Experience Platform Launch]

* Siehe [[! DNL Experience Platform Launch]](https://docs.adobelaunch.com/) für die neuesten Informationen.

## Analytics {#analytics}

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen und Fehlerbehebungen in Adobe Analytics](#aa-features)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)

Eine Produktdokumentation finden Sie auf der [Startseite der Hilfe zu Analytics](https://marketing.adobe.com/resources/help/en_US/reference/).

### Neue Funktionen und Fehlerbehebungen in Adobe Analytics {#aa-features}

| Funktion | Beschreibung |
| -----------| ---------- |  
| **Segmentierung** | Neue Zuordnungsmodelle für Dimensionen in der Segmentierung:<ul><li>Wiederholen (Standard): Umfasst Instanzen + beibehaltene Werte für die Dimension.</li><li>Instanz: Umfasst Instanzen für die Dimension.</li><li>Nicht wiederholende Instanz: Enthält eindeutige Instanzen (nicht wiederholend) für die Dimension.</li></ul> [Mehr](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-build.html) |
| **Segmentierung** | Neue Segmentoperatoren: **[!UICONTROL Entspricht]** beliebig und **[!UICONTROL entspricht keiner von]**. [Mehr...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segment-reference/seg-operators.html) |
| **Debugger** | Wenn Sie mit Ihrer Adobe ID angemeldet sind, haben Sie jetzt die Option, nach der Verarbeitung verarbeitete Treffer im Experience Cloud-Debugger abzurufen. Post-verarbeitete Treffer sind Serveraufrufe, nachdem sie [!UICONTROL die Verarbeitungsregeln] und VISTA-Regeln durchlaufen haben, sodass [!UICONTROL Sie Verarbeitungsregeln] und Ihre VISTA-Regeln validieren können. **Hinweis**: Wenn Sie A 4 T (supplementaldataid) verwenden, können die Nachbearbeitungsdaten einige Minuten zurückgehen. |
| **Analysis Workspace:** | Es wurden neue standardfilter zur linken Leiste hinzugefügt. Neue Filter (Dimensionen, Metriken, Genehmigt usw.), neue Filter wie Berechnete Metriken, Kundenattribute, evars, Props, Video usw. hinzugefügt, um die benötigten Komponenten leichter zu finden. |
| **Analysis Workspace** | Wir haben eine Warnung zur Fallout-Visualisierung hinzugefügt, die angezeigt wird, wenn Sie ein Segment als Touchpoint hinzufügen - bestimmte ungültige Segmentbehälterkombinationen führen zu ungültigen Fallout-Diagrammen, wie zum Beispiel <ul><li>Verwenden eines besucherbasierten Segments als Touchpoint innerhalb einer Fallout-Visualisierung des Besuchers</li><li>Verwenden eines besucherbasierten Segments als Touchpoint innerhalb eines Besuchs-Context-Fallout-Visualisierung</li><li>Verwenden eines besuchsbasierten Segments als Touchpoint innerhalb eines Besuchs-Context-Fallout-Visualisierung</li></ul> <br> [Mehr …](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/fallout/compare-segments-fallout.html)</br> |
| **Verbesserungen an der Analytics-Dokumentation** | Die Analytics-Dokumentation wurde neu organisiert und enthält jetzt Funktionen für die Zusammenarbeit, mit denen Sie den Inhalt verbessern können! Sie können Probleme mit der Dokumentation protokollieren und Änderungen vorschlagen. Der doc-Satz wurde in eine [neue Domäne verschoben](https://docs.adobe.com/content/help/en/analytics/landing/home.html). Umleitungen sollten vorhanden sein. |
| **Neues Technologienotizen Benutzerhandbuch** | Das [Technische Notizenhandbuch](https://docs.adobe.com/content/help/en/analytics/technotes/home.html) ist jetzt verfügbar. Derzeit ist es darauf ausgerichtet, Benutzer zu unterstützen, die mit Analysetools von Drittanbietern wie Google Analytics vertraut sind, um sich besser mit Adobe Analytics vertraut zu machen. Das Benutzerhandbuch für technische Hinweise erweitert sich in den kommenden Monaten, um weitere Inhalte einzubinden. |

**Korrekturen an Analysis Workspace**

* Es wurde ein Problem mit lokalisierten japanischen Datumsinformationen in [!DNL Analysis Workspace] Visualisierungen behoben. (AN-180114)
* Es wurde ein Problem behoben, das nach dem Kopieren und Einfügen von Dimensionselementen auftrat. Bei nachfolgenden Suchen im Element wurde ein Fehler ausgegeben. (AN-177394)
* Es wurde ein Problem behoben, durch das die Option zur Bearbeitung in Segmentbereichen in Freiform-Tabellen fehlte. (AN-171703)
* Es wurde ein Problem behoben, durch das **[!UICONTROL die Funktion Als Landingpage]** festlegen nicht funktioniert, wenn sie für eine große Menge an Empfängern freigegeben wurde. (AN-163922)
* Es wurde ein Problem behoben, durch das Zeichenfolgen in Echtzeitberichten vertikal abgeschnitten wurden. (AN-175980)

**Andere Fehlerbehebungen in Analytics**

* Es wurde ein Problem behoben, durch das Administratoren keine Erfolgsereignisse aktivieren **[!UICONTROL ]** konnten. (AN-176689)
* Es wurde ein Problem behoben, das beim Erstellen einer Warnung mit der Metrik **[!UICONTROL Ausstiegsrate]** auftrat. (AN-177476)

### Wichtige Hinweise für Analytics-Administratoren {#aa-notices}

| Hinweis | Datum hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Einschränkungen des Classification Rule Builder | Hinzugefügt am 5. Juni 2019 | Diese Beschränkungen sind nicht neu, wurden aber zur Dokumentation [hier hinzugefügt](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| Einschränkungen des neuen Segmentoperators | Hinzugefügt am 31. Mai 2019 | Ab dem 18. Juli 2019 werden die Segmentoperatoren &quot;enthält beliebige&quot; ,&quot; enthält keine&quot; , &quot;enthält alle&quot; und&quot; enthält nicht alle&quot; auf 100 Wörter pro Eingabefeld beschränkt. Die Beschränkung wird nach diesem Datum auf alle neuen und geänderten Segmente angewendet. Vorhandene Segmente, die die Beschränkung überschreiten, werden weiterhin unterstützt, können jedoch erst geändert oder gespeichert werden, wenn das Eingabefeld reduziert wurde. Diese Beschränkungen werden im Rahmen eines fortlaufenden Bemühungsaufwands angewendet, um die Abfrageleistung zu verbessern. |
| Bevorstehende Änderungen der Unterstützung für die Klassifizierungen **[!UICONTROL Datumsaktiviert]** und **[!UICONTROL Numerisch 2]** | Aktualisiert am 28. Mai 2019 | Die Möglichkeit, die Klassifizierungen „Numerisch 2“ und „Datumsaktiviert“ zu importieren, wurde aus der Codebasis entfernt. Diese Änderung wird mit der Wartungsversion vom Juli 2019 wirksam. Wenn die Importdatei die Spalte „Numerisch“ oder „Datumsaktiviert“ enthält, werden diese Zellen still ignoriert und alle anderen Daten in dieser Datei werden normal importiert. <br/>Vorhandene Classifications können weiterhin über den Standard-Classification-Arbeitsablauf exportiert werden und sind weiterhin in Berichten verfügbar. |
| Bevorstehende Änderung bei Berechnungen der _Berichtssumme_ | Aktualisiert am 2. Mai 2019 | Ab **13. Juni 2019** werden in Adobe Analytics Berechnungen von _Berichtssummen_ für alle Dimensionen und Metriken vereinheitlicht. Dadurch werden sich die Gesamtsummen bei manchen Berichten ändern (vor allem bei Berichten zu Eigenschaften oder Kundenattributen). Vor dieser Änderung kam es vor, dass in manchen Berichtssummen der Zeileneintrag _Unspecified_ uneinheitlich ein- oder ausgeschlossen wurde, und zwar unabhängig davon, ob _Unspecified_ im Bericht vorkam oder nicht. <br/>Ab 13. Juni 2019 wird _Nicht angegeben_ immer in Berichtssummen angezeigt, auch wenn dieser Wert nicht als Zeileneintrag im Bericht zu sehen ist. Außerdem kann es vorkommen, dass Segmente, die die _ist vorhanden_- oder _ist nicht vorhanden_-Logik nutzen, nach dieser Änderung andere Ergebnisse für einige Dimensionen aufweisen. Diese Änderung betrifft Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder und die Reporting-API. |
| Aktualisierung von CSV-Downloads aus [!DNL Analysis Workspace] | 10. April 2019 | Ab dem 11. April 2019 wurden mehrere Änderungen an **[!UICONTROL CSV-Downloads]** (und **[!UICONTROL In Zwischenablage kopieren]**) in [!DNL Analysis Workspace] vorgenommen, um die Formatierung aus den exportierten Daten zu entfernen.  <ul><li>Das Tausendertrennzeichen ist nicht mehr enthalten. Das Dezimaltrennzeichen wird weiterhin enthalten sein und dem unter **[!UICONTROL Komponenten &gt; Berichtseinstellungen &gt; Tausendertrennzeichen]** definierten Format entsprechen. Hinweis: Numerische Werte, die ein Komma als Dezimaltrennzeichen verwenden, werden weiterhin in der exportierten CSV angegeben.</li><li>Es werden keine Währungssymbole angezeigt.</li><li>Es werden keine Prozentsymbole angezeigt. Prozentangaben werden in Dezimalform angezeigt. Zum Beispiel werden 75 % als 0,75 dargestellt.</li><li>Die Zeit wird in Sekunden angezeigt.</li><li>Kohortentabellen zeigen nur Rohwerte an. Prozentsätze werden entfernt.</li><li>Wenn eine Nummer ungültig ist, wird eine leere Zelle angezeigt.</li></ul> |
| Anstehende Änderung am Befehl „[!DNL Analysis Workspace] Debugger“. | 4. April 2019 | Der Konsolenbefehl zum Aktivieren des [!DNL Analysis Workspace] Debuggers wird am **13. Juni 2019** in adobeTools.debug.includeOberonXml geändert. adobe.tools.debug.includeOberonXml wird nach diesem Datum nicht mehr funktionieren. |
| Mobile Browser – Versionsnummern | 7. Februar 2019 | Am 8. Januar 2019 haben wir die Abschnittsebene bei den Versionsnummern mobiler Browser von 2 zu 1 geändert. Seit diesem Datum zeigen die Versionen nur die ersten beiden Ebenen an (Beispiel: _Firefox 64.0.2_ wird jetzt als _Firefox 64.0_ angegeben). |
| wird eingestellt [!DNL Ad Hoc Analysis] | 29. Januar 2019 | Am 6. August 2018 kündigte Adobe die Absicht an, [!DNL Ad Hoc Analysis] einzustellen. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist.<br/>Weitere Informationen dazu, welche Versionen von Java während dieses Zeitraums kompatibel sind, finden Sie unter [Arbeitsbereich entdecken](https://adobe.ly/discoverworkspace). |
| Kurz-Links für Analytics-Berichte | 14. Januar 2019 | Kurz-Links für Analytics-Berichte, die innerhalb eines Jahres nicht aufgerufen wurden, werden entfernt und ab Donnerstag, den 17. Januar 2019 fortlaufend gelöscht. |
| Ende der Unterstützung für TLS 1.0 | Aktualisiert am 10. Januar 2019 | Ab dem 11. Februar 2019 unterstützt die Adobe Analytics-Berichterstellung die Verschlüsselung mit TLS (Transport Layer Security) 1.0 nicht mehr. Diese Änderung ist Teil unserer ständigen Bemühungen, die höchsten Sicherheitsstandards einzuhalten und die Daten unserer Kunden zu schützen. Wenn Sie nach dem 11. Februar 2019 keine Verbindung zu Adobe Analytics-Berichten herstellen können, sollten Sie den Browser auf die [neueste Version aktualisieren](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> Ab dem 20. Februar 2019 bietet die Adobe Analytics-Datenerfassung keine Unterstützung für TLS 1.0 mehr. Aufgrund dieser Änderung werden von Adobe keine Analytics-Daten von Endbenutzern mit älteren Geräten oder Webbrowsern ohne Unterstützung für TLS 1.1 oder höher erfasst. Wir gehen davon aus, dass dies keine wesentlichen Auswirkungen auf Kundendaten oder die Berichterstattung haben wird. (Wenn Ihre Website TLS 1.0 bereits nicht mehr unterstützt, sind Sie nicht betroffen.) <br/>Ab dem 11. April 2019 bietet die Reporting-API von Adobe Analytics keine Unterstützung mehr für die TLS 1.0-Verschlüsselung. Kunden, die auf die API zugreifen, sollten sicherstellen, dass sie nicht von den Auswirkungen betroffen sind. <ul><li>Für API-Clients, die Java 7 mit den Standardeinstellungen verwenden, müssen einige [Änderungen zur Unterstützung von TLS 1.2](https://www.java.com/en/configure_crypto.html) vorgenommen werden (siehe _„Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2“_).  </li><li>API-Clients, die Java 8 verwenden, sollten nicht beeinträchtigt sein, da die Standardeinstellung TLS 1.2 ist.</li><li> Bei API-Clients, die andere Frameworks verwenden, müssen Sie die Details zur Unterstützung von TLS 1.2 beim jeweiligen Anbieter erfragen.</li></ul> |
| Daten-Feed: Spalte „post_product_list“ – Änderung der Größe | 9. Januar 2019 | Adobe hat die Größe der Spalte „post_product_list“ am dem 7. Februar 2019 von 64 KB auf 16 MB erweitert. Diese Änderung stellt sicher, dass bei der Verarbeitung zu „post_product_list“ hinzugefügte Merchandising-eVar-Werte nicht zu abgeschnittenen Produkt- und Umsatzwerten führen. Wenn Sie über Prozesse verfügen, bei denen post_product_list-Werte erfasst werden, stellen Sie sicher, dass diese Prozesse Werte mit einer Länge von bis zu 16 MB verarbeiten können (ansonsten werden Werte bei 16 KB abgeschnitten), um Datenerfassungsfehler zu vermeiden. |
| Verwaltungsänderungen mit Auswirkung auf inaktive [!DNL Analytics Live Stream]-Endpunkte | 20. Dezember 2018 | Ab dem 1. Februar 2019 können [!DNL Live Stream]-Endpunkte, die 90 Tage lang keine aktive Verbraucherverbindung aufweisen, deaktiviert werden. Sie können sich an die Kundenunterstützung wenden, um sich über Ihre [!DNL Live Stream]-Endpunkte zu informieren und diese bei Bedarf wieder zu aktivieren. Stellen Sie außerdem sicher, dass für Ihre Verbraucherprozesse eine dauerhafte Verbindung besteht, wie es das Konzept des Dienstes vorsieht, und dass sie so implementiert sind, dass sie sich wieder verbinden, wenn die Verbindung getrennt oder unterbrochen wird. |
| Aktualisieren von Adobe [!DNL Report Builder] aufgrund der Einstellung des Supports für TLS 1.0 | 7. Sept. 2018 | Aufgrund der Unterstützung für TLS 1.0 sollten Benutzer von [!DNL Report Builder] die Version 5.6.21 vor Februar 2019 herunterladen. Nach diesem Datum sind frühere Versionen von [!DNL Report Builder] nicht mehr funktionstüchtig. |

## Audience Manager {#aam}

**Fehlerbehebungen, Verbesserungen und veraltete Elemente**

* Audience Manager zählt jetzt nur aktive algorithmische Modelle für die Nutzungsgrenze.
* Behebung eines Problems, bei dem die Reichweite des algorithmischen Modells nicht für Eigenschaften angezeigt wurde, die das entsprechende Modell verwenden.
* Es wurde ein Problem behoben, durch das der Inhalt von Eigenschaftenordnern nicht angezeigt wurde, wenn die Ordnernamen Paranthese und/oder Klammern enthielten.
* Es wurde ein Fehler behoben, der dazu führte, dass Eigenschaften bei der Auswahl nur eines Eigenschaftstyps fehlschlugen.
* Es wurde ein Problem behoben, durch das die Baumstruktur des Eigenschaftenordners jedes Mal, wenn Sie einen neuen Unterordner erstellt oder aktualisiert haben, in der [!UICONTROL Eigenschaftenansicht] minimiert wurde.
* Es wurde ein Problem behoben, durch das [!DNL VIEW_DATASOURCES] die Berechtigung zum Löschen eines Partners erforderlich war.
* Es wurde ein Problem behoben, durch das das [!UICONTROL Suchfeld] auf der [!UICONTROL Seite &quot;Segmente] &quot; in allen Ordnern anstelle der ausgewählten Suche durchsucht wurde.
* Behebung eines Problems, durch das die Tabelle [!UICONTROL &quot;Eigenschaften] ausschließen&quot; nicht durch die Kopfzeilensteuerelemente sortiert wurde, wenn ein neues algorithmische Modell erstellt wurde.
* Es wurde ein Problem behoben, durch das Audience Manager beim Ausführen eines Berichts mit leeren Intervall-Daten abstürzte.

## Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktversionen

**Cloud Manager 2019.5.0**

Die neueste Version von Cloud Manager (2019.5.0) enthält keine signifikanten Funktionsänderungen, obwohl sie einige Fehlerkorrekturen liefert.

* [Versionshinweise für Cloud Manager 2019.5.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**XML-Dokumentation für AEM**

Die Version 3.3 für die XML-Dokumentation ist jetzt verfügbar. Siehe folgende Versionshinweise:

***Erweiterte Zuordnungsfunktionen***
* Fügen Sie Themenverweise entweder per Drag &amp; Drop aus der Repository-Ansicht oder über die horizontale Leiste und den Elementkatalog hinzu.
* Fügen Sie Metadaten zu Themen-ref, Chunk, wie nav-Titel, Format, Scope usw. hinzu.
* Durch Klicken auf die Themenref sollte das Thema im Editor geöffnet werden (Vorschaumodus, wenn nicht ausgecheckt, und die Bearbeitung mit Kasse deaktiviert ist).
* Themenkopf und Themengruppe hinzufügen.
* Hinzufügen von Bookmaps mit der Vorderseite (Themen, Vorwort, Buchliste, Hinweise usw.) und Backmatter (Themen, Anhänge, Glossar usw.)
* Im Autorenmodus werden fehlerhafte Links hervorgehoben, Breadcrumbs werden angezeigt und die vollständige Tags-Ansicht ist verfügbar.
* Möglichkeit zur Festlegung von Attributebenenattributen.
* Möglichkeit, Titel/booktitle festzulegen.
* Unterstützung für Reltables mit der Möglichkeit, Gulden, Spalten, Drag-/Drop-Themen aus der Map und Repository in die Rel-Tabelle einzufügen, Verknüpfungen, Scope und andere Parameter für die Links festzulegen, Links in der Zelle neu anzuordnen.
* Symbolleistenwidget, bevor es eingefügt werden kann, einfügen nach und einfügen.
* Heben Sie hervor, ob eine Bedingung auf ein Thema angewendet wird.
* Möglichkeit, mehrere Maps gleichzeitig zu bearbeiten (jede Karte wird als Registerkarte im selben Browser geöffnet).
* Zeigen Sie im Imagemap-Bedienfeld und in der Repository-Ansicht nach dem Hover den vollständigen Thementitel und den Dateinamen an.

***Vollständige Tag-Ansicht***

* Fügen Sie neue Tags zwischen zwei Elementen ein.
* Tags kopieren und einfügen.
* Ziehen Sie Tags an zulässigen und nicht zulässigen Positionen in einer Datei per Drag &amp; Drop.
* Reduzieren und reduzieren Sie Tags.

***DITA-spezifische Suchverbesserungen***

* Es wurde ein Serialisierungstool zur Neuindizierung ausgewählter Inhalte bereitgestellt
* Benutzer können verwenden `contains` und `exact match` in ihrer Suche. Sie können auch mithilfe der folgenden Parameter suchen. :
   * Asset-Metadaten. Zum Beispiel oder `file name``title`alle vom Kunden definierten benutzerspezifischen Metadaten.
   * DITA-Attributname und sein Wert. Beispiel, `platform=winOS`.
   * DITA-Elementname und sein Wert. Beispiel, `author = Joe Smith`.
   * DITA-Elementname und sein angewendetes Attribut. Beispiel: Tabelle mit dem Attribut product = spacebase Attributname/Wert.
   * Metadaten für DITA-Themen und -zuordnungen.
   * DITA-Informationstyp. Für Prüfung [ple, map, topic, concept usw.
   * Pfad zum Stammordner, in dem sich das Asset befindet.
   * Dokumentstatus.
   * Ausgecheckter Status.
   * Änderung des Datumsbereichs.
   * CQ-Tags.
* Sie können komplexe Abfragen erstellen, indem Sie eines oder mehrere der oben genannten Suchparameter kombinieren.

***Änderungen an der Funktion überprüfen***

* Tipps für einen Überprüfer:
   * Importieren Sie alle Kommentare und nehmen Sie die Änderungen vor, bevor Sie auf den 3.3-Build aktualisieren.
   * Stellen Sie sicher, dass mehrere Registerkarten für den Editor nicht geöffnet sind.
   * Stellen Sie sicher, dass die Ansicht &quot;Vollständige Tags&quot; nicht aktiviert ist.
   * Wechseln Sie während der Überprüfung nicht zwischen dem Autorenmodus und dem Quellmodus.
* Möglichkeit, die Version meines Inhalts anzugeben, der überprüft werden soll.
* Möglichkeit, die Versionen der ausgewählten Themen basierend auf einer Grundlinie, einem Datum, einer Beschriftung oder einer aktiven Version auszuwählen oder die Versionen der einzelnen Themen festzulegen, während Sie eine Überprüfung erstellen.
* Möglichkeit, gleiche Themen/Maps zur Überprüfung zu senden, und Autor können im Review-Bedienfeld des Editors auf alle Reviews zugreifen.
* Als Initiator können Sie eine spätere Version des Inhalts für die Prüfer veröffentlichen. Die Prüfer erhalten eine Benachrichtigung, wenn ein neuer Inhalt zur Überprüfung gesendet wird.
* Als Autor kann der Benutzer die Überprüfungskommentare für alle Versionen ihres Inhalts im Review-Bereich des Editors anzeigen. Autoren können die Kommentare nach Versionsnummer filtern.
* Als Autorenbenutzer können Kommentare zu einer älteren Version des Inhalts im bearbeiteten Editor angezeigt und importiert werden.

***Sonstiges***

* Erstellen Sie in der Repository-Ansicht einen neuen Ordner, ein neues Thema oder eine neue Map.
* In der Asset-Benutzeroberfläche anzeigen: Fügen Sie eine Menüoption für sowohl Ordner als auch Themen hinzu - &quot;In Assets-UI anzeigen&quot; . Mit dieser Option wird die Assets-Benutzeroberfläche geöffnet, in der der Benutzer die Inhaltsstruktur auf der linken Seite und alle Dateien in der Listenansicht auf der rechten Seite mit allen Assets-Menüs oben sehen kann.
* Ein Review-Dashboard ist jetzt als Kachel im DITA-Projekt verfügbar, das den Review auf Prüfebene und auf einer Review-Aufgabenebene verfolgt.
* Es wurde die Möglichkeit hinzugefügt, IDML in DITA zu konvertieren.
* Stellen Sie API bereit, um die angegebene Beschriftung in allen angegebenen Versionen einer Grundlinie anzuwenden.
* Aktivieren Sie ein Ereignis, nachdem XHTML/DOCX für DITA-Konvertierung abgeschlossen ist. Mit diesem Ereignis können Sie dem konvertierten Inhalt spezielle Attribute hinzufügen oder für jede andere benutzerdefinierte Logik, die Sie implementieren möchten.
* Die Verbesserungen an der Grundleistung wurden vorgenommen. Der Benutzer muss zunächst in allen vorhandenen Ausgangspunkten ein Skript ausführen.
* An der XHTML-Konvertierung wurden Verbesserungen vorgenommen.
* DITA-OT-Download für die Veröffentlichung von Veröffentlichungen.
* Die Sortierung in der Spalte &quot;Typ&quot; in der Listenansicht wurde korrigiert.
* Möglichkeit, übernommene Stile in Word in DITA-Konvertierungen zu verarbeiten.

### Community

**[Cloud Manager-Webinar-Webinar-Reihe](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)**

Möchten Sie wissen, wie devops-Prozesse tägliche Aktivitäten für Adobe Experience Manager-Verwaltung in der Cloud vereinfachen können? Cloud Manager bietet die erste Generation cloud-nativer Funktionen für Adobe Experience Manager, die die Cloud-Beweglichkeit aktiviert, ob Ihre Organisation die devops-Transformation beginnt oder Strategien zur Erweiterung vorhandener devops-Prozesse sucht.

[In dieser monatlichen Reihe](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)können Sie direkt vom Produktteam von Adobe erfahren, wie Sie Einstieg erhalten und wie Sie mit Cloud Manager-Funktionen die Verwaltung von Adobe Experience Manager in der Cloud vereinfachen.

Hier lernen Sie Folgendes kennen:
* Erste Schritte mit Cloud Manager und Einrichten der CI-/CD-Pipeline
* Funktionsweise der automatischen Skalierung und des transparenten Service-Managements und Vereinfachung der Adobe Experience Manager-Umgebungsverwaltung in der Cloud
* Verwenden der Cloud Manager-API und Integrieren vorhandener devops-Prozesse

### Zusätzliche Ressourcen

* [AEM 6.5 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager-Benutzerhandbuch](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Ältere Versionen der AEM-Dokumentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System – Versionshinweise](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre-Versionshinweise](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### [!DNL Campaign Classic] 19.1 Frühlingsversion

| Funktionalität | Beschreibung |
| ------------- | ----------- |
| Systemsteuerung | Um die Effizienz Ihrer Arbeit als Administrator zu erhöhen, verwalten Sie die Einstellungen Ihrer SFTP-Server, indem Sie die Speicherung, die Whitelisting-IP-Adressen und die Installation von SSH-Schlüsseln für jede Instanz überwachen. Bitte beachten Sie, dass Systemsteuerung nur für Kunden verfügbar ist, die seit heute auf AWS gehostet sind. [Melden Sie sich über die Experience Cloud](https://experiencecloud.adobe.com/campaign/controlpanel/)an. <br> Weitere Informationen finden Sie in der [detaillierten Dokumentation](https://helpx.adobe.com/campaign/kb/control-panel.html) und in der [Videoanleitungen](https://helpx.adobe.com/campaign/kt/acc/using/acc-control-panel-video-use.html). |
| Prüfprotokoll | Steigern Sie die Produktivität als Administrator, indem Sie die Änderungen überwachen und verwalten, die innerhalb der Adobe Campaign Classic-Instanz vorgenommen wurden. Der Audit-Protokoll protokolliert Aktionen, die auf dem Quellschema, dem Arbeitsablauf und der Option vorgenommen wurden. Sie können schnell sehen, ob ein Element erstellt, geändert oder gelöscht wurde.<br>Weitere Informationen finden Sie in der [detaillierten Dokumentation](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Audit_trail.html) und in der [Videoanleitungen](https://helpx.adobe.com/campaign/kt/acc/using/acc-audit-trail-feature-video-use.html). |
| Guardrail, Stabilität und Skalierbarkeit | Eine Reihe von Verbesserungen [!DNL Campaign Classic]wurde hinzugefügt. Verbesserungen an der Speicherung, Stabilität und Skalierbarkeit werden in den [Versionshinweisen](https://docs.campaign.adobe.com/doc/AC/en/RN.html)zu Adobe Campaign Classic aufgeführt. |
| Secure SMS Messaging (TLS) | Secured SMS wird jetzt über den erweiterten generischen SMPP Connector unterstützt. Dies ermöglicht eine verschlüsselte Verbindung zum Anbieter. <br>Weitere Informationen finden Sie in der [ausführlichen Dokumentation](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html). |
| Update der Kompatibilitätsmatrix | Mit dieser neuen Version unterstützt Adobe Campaign jetzt die folgenden Datenbanksysteme. Siehe [Kompatibilitätsmatrix](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html) <ul><li>Oracle 18 c</li><li>Mysql 5.7 (FDA)</li><li>SQL Server 2017</li><li>Teradata 16 (FDA)</li><li>Postsession 11</li></ul> |

Fehlerbehebungen und Verbesserungen finden Sie unter [Adobe Campaign Classic – Versionshinweise](http://docs.campaign.adobe.com/doc/AC/en/RN.html).

### [!DNL Campaign Standard] 19.2 Frühlingsversion

| Funktionalität | Beschreibung |
| ------------- | ----------- |
| Systemsteuerung | Um die Effizienz Ihrer Arbeit als Administrator zu verbessern, können Sie die Kapazität und die Einstellungen Ihrer Instanzen einfach überwachen (beginnend mit der SFTP-Serververwaltung). <br> Weitere Informationen finden Sie in der [detaillierten Dokumentation](https://helpx.adobe.com/campaign/kb/control-panel.html) und in der [Videoanleitungen](https://helpx.adobe.com/campaign/kt/acs/using/acs-control-panel-video-use.html). |
| Lokale Benachrichtigungen | Mit der Benachrichtigung über lokale Benachrichtigungen können Sie Ihre Benutzer benachrichtigen, wenn neue Daten in ihren mobilen Anwendungen verfügbar werden, auch ohne Zugriff auf das Internet oder die Mobilanwendung, die im Vordergrund ausgeführt wird. Lokale Benachrichtigungen werden von einer mobilen Anwendung zu einem bestimmten Zeitpunkt und je nach Ereignis ausgelöst.<br>Weitere Informationen finden Sie in der [ausführlichen Dokumentation](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type). |
| Verbesserung des Workflows: Fügen Sie einer externen Signalaktivität eine Nutzlast hinzu. | Starten Sie einen Workflow mit Nutzlast, wenn definierte Bedingungen erfolgreich aus einem anderen Workflow oder einem REST-API-Aufruf für die Integration in Ihre externen Systeme erfüllt wurden. Dies umfasst auch eine neue Testaktivität, in der Sie Tests für diese Funktion ausführen können. <br>Weitere Informationen finden Sie in der [detaillierten Dokumentation](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type) und in der [Videoanleitungen](https://helpx.adobe.com/campaign/kt/acs/using/acs-external-signal-activity-feature-video-use.html). |
| Verbesserung der Einstiegsseiten - Google recaptcha | Nutzen Sie Google recaptcha, um Spam auf Ihren Einstiegsseiten zu verhindern, ohne dass eine Aktion von Ihren Kunden erforderlich ist. <br>Weitere Informationen finden Sie in der [ausführlichen Dokumentation](https://helpx.adobe.com/campaign/standard/channels/using/designing-a-landing-page.html#setting-google-recaptcha). |

Eine Produktdokumentation finden Sie hier:

* Adobe Campaign Standard: [Dokumentation](https://helpx.adobe.com/support/campaign/standard.html) – [ Versionshinweise](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) – [Videos zu Funktionen](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Dokumentation](https://helpx.adobe.com/support/campaign/classic.html) – [Versionshinweise](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Videos zu Funktionen](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Mobile Services {#mobile}

* TLS 1.0 wurde auf allen Adobe-Servern deaktiviert. Damit Android 4. x-Geräte über SSL eine Verbindung zu Adobe-Diensten herstellen können, erzwingt das SDK jetzt TLS 1.1/TLS 1.2, wenn ein Handshake erstellt wird.

## Advertising Cloud {#adcloud}

Aktualisiert: 5. Juni 2019, für die Version vom 8. Juni

| Produkt | Funktion | Beschreibung |
| -----------| ---------- | ----------  |
| Suchkampagnen, Beschriftungen und Einschränkungen | Tastaturbefehle | Mit <b>Umschalt + Klicken</b> können Sie jetzt mehrere, aufeinander folgende Zeilen auswählen und <b>Strg + Klicken</b> , um mehrere, nicht aufeinander folgende Zeilen auszuwählen. |
|  | Alle auswählen und Alle auf Seite auswählen | Wenn Sie in Datentabellen das oberste Kontrollkästchen zur Auswahl aller Zeilen auswählen, wird der neue Standardwert für alle Zeilen auf der Seite ausgewählt (je nachdem, ob Sie 25 Zeilen, 50 Zeilen, 100 Zeilen, 200 Zeilen oder fortlaufende Bildlaufleisten anzeigen). Sie haben weiterhin die Möglichkeit, alle verfügbaren Zeilen auszuwählen. |
| Standardansichten, benutzerdefinierte Ansichten und eigenständige Spaltenanpassung | Spaltenneuanordnung | Mit den Schaltflächen Nach oben und Unten können Sie Spalten neu anordnen. Sie können nach wie vor Spalten per Drag &amp; Drop neu ordnen, wie Sie dies zuvor tun konnten. |

## Target Standard/Premium 19.6.1 (25. Juni 2019) {#target}

Informationen zu den neuesten Versionen finden Sie in den Adobe Target-Versionshinweisen:

[Target-Versionshinweise (Vorabversion)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)

[Target-Versionshinweise (aktuell)](https://docs.adobe.com/content/help/en/target/using/release-notes/release-notes.html)

## Magento {#magento}

Magento ist eine E-Commerce-Plattform, die Online-Händlern ein flexibles Warenkorbsystem und Kontrolle über den Look, den Inhalt und die Funktionalität des Online-Geschäfts bietet. Magento ist in einer Open-Source-Version und in einer umfassenderen Commerce-Version verfügbar.

Magento Commerce ist Teil der Adobe Commerce Cloud und bietet eine E-Commerce-Lösung mit Enterprise-Power, unbegrenzter Skalierbarkeit und Open-Source-Flexibilität für B2C- und B2B-Anwendungen.

Versionshinweise für unsere Open Source- und Commerce-Editionen finden Sie auf der Seite [&quot;Versionsinformationen](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) &quot; .

## Primetime {#primetime}

Adobe Primetime ist eine Multiscreen-TV-Plattform, mit der Medienunternehmen ein ansprechendes, personalisiertes Fernseherlebnis schaffen und profitabel einsetzen können.

[Primetime – Versionshinweise](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Startseite der Primetime-Hilfe](http://help.adobe.com/en_US/primetime/)
