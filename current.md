---
title: Versionshinweise zu Adobe Experience Cloud - Technische Dokumentation
description: Version von Juli 2019 Experience Cloud - Versionshinweise
doc-type: Versionshinweise
last-update: Juli 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 41b4cbb1b93fe857c80cebd631a785e234e2ce07

---


# Adobe Experience Cloud – Versionshinweise

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

>[!NOTE]
>
>Abonnieren Sie das [Prioritätsprodukt-Update von Adobe](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bevorstehende Versionen benachrichtigt zu werden. Sie erhalten drei bis fünf Werktage vor der Veröffentlichung der Version eine Benachrichtigung. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Releasedatum: 18. Juli 2019**

* [Experience Cloud Core Services und Administration](#experiencecloud)
* [!DNL Analytics](#analytics) - **(Aktualisiert am 15. Juli)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)

## Core Services und Administration {#experiencecloud}

Versionshinweise für die Experience Cloud-Schnittstelle, einschließlich [!UICONTROL der Plattform]-Core-Services und der Produktverwaltung.

* [Experience Cloud ID-Dienst](#ecid)
* [Mobile Services und Mobile SDK](#mobile)
* [Experience Platform Launch](#launch)
* [Sicherheitsbulletins und -hinweise](#security)

### Experience Cloud ID-Dienst {#ecid}

**Fehlerbehebungen und Verbesserungen**

* `cookieDomain` Konfigurationsaktualisierung: Die Bibliothek weist automatisch eine Cookie-Domäne auf oberster Ebene zu, wenn `cookieDomain` in `initConfig` nicht festgelegt ist. (CORE-29223)
* Ein Fehler bei wurde `getVisitorValue` in `localVisitor` behoben. (CORE-31287)
* Eine Unstimmigkeit zwischen dem `MCOPTOUT`-Wert im übergeordneten Besucher und im untergeordneten iframe-Besucher in der `getVisitorValue`-Methode wurde behoben. (CORE-29719)
* Ein Problem mit Sicherheitslücken in jQuery 3.2.1 wurde behoben. (CORE-31183)
* Aktualisierung des Opt-ins: wurde `optIn.off` zur Abmeldung von Ereignissen hinzugefügt.
* Ein Problem mit der `setTimeout`-Funktion wurde behoben. (CORE-30623)

See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services und Mobile SDK {#mobile}

iOS und Android wurden wie folgt aktualisiert:

**iOS**

* Adobe Target: Bei allen Anfragen sind jetzt Client und `sessionId` in den URL-Abfrageparametern enthalten.
* Adobe Target: Ein Speicherleck wurde behoben.
* Besucher-ID-Service: Die APIs `visitorAppendToURL` und `visitorGetUrlVariablesAsync` kodieren ihre Rückgabewerte jetzt nicht mehr doppelt. Die Doppelkodierung führte dazu, dass die Rückgabewerte von diesen APIs von bestimmten Sicherheitsprüfungen als falsch gekennzeichnet wurden.

**Android**

* Target: Bei allen Anfragen sind jetzt Client und sessionId in den URL-Abfrageparametern enthalten.
* In-App-Messaging: Ein Problem wurde behoben, bei dem beim Auslösen einer Nachricht mit einer leeren Clickthrough-URL Android-Apps abgestürzt sind.
* Besucher-ID-Service: Die APIs `Visitor.appendToURL` und `Visitor.getUrlVariablesAsync` kodieren ihre Rückgabewerte jetzt nicht mehr doppelt. Die Doppelkodierung führte dazu, dass die Rückgabewerte von diesen APIs von bestimmten Sicherheitsprüfungen als falsch gekennzeichnet wurden.

Informationen zur Produktdokumentation finden Sie unter [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html).

Weitere Informationen zu den Mobile-SDKs finden Sie unter [Android-SDK 4.x für Experience Cloud-Lösungen](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) und [iOS-SDK 4.x für Experience Cloud-Lösungen](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### Sicherheitsbulletins und -hinweise {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## [!DNL Analytics] {#analytics}

* [Neue Funktionen und Fehlerbehebungen in Adobe Analytics](#aa-features) **(aktualisiert am 15. Juli)**
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)

### Neue Funktionen in [!DNL Analytics] {#aa-features}

Eine Produktdokumentation finden Sie auf der [Startseite der Hilfe zu Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

| Komponente | Beschreibung |
| -----------| ---------- |   
| Analysis Workspace – Verbesserungen der Kohortenanalyse | New [Cohort Analysis settings](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/cohort-table/t-cohort.html) have been added: <ul><li>Nur Prozentwert anzeigen</li><li>Prozentwert auf nächste Ganzzahl runden</li><li>Zeile mit durchschnittlichem Prozentwert anzeigen</li></ul> |
| Analysis Workspace | In der linken Leiste haben Benutzer jetzt die Möglichkeit, _Elemente aus den letzten 18 Monaten anzuzeigen_. Zuvor betrug der Anzeigezeitraum maximal 6 Monate. Dies erleichtert den Vergleich mit Seiten oder Kampagnen aus dem Vorjahr bzw. bis vor maximal 18 Monaten. |
| Neue Vorlage für Analysis Workspace | We added a new template called ["Magento: Marketing &amp; Commerce"](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html) to Analysis Workspace. Sie wurde speziell für E-Commerce-Kunden von Magento konzipiert, aber alle anderen Händler können sie ebenfalls verwenden, um nützliche Einblicke in ihre Commerce-Aktivitäten zu erhalten. |

#### [!DNL Analysis Workspace]Fehlerbehebungen

* Ein Problem wurde behoben, bei dem Multi-Byte-Zeichen beim Unterteilen von Dimensionen verkehrt angezeigt wurden. (AN-180112)
* Bei Visualisierungsfehlern wurde ein Problem behoben. Jetzt wird eine rote Fehlerleiste angezeigt, wenn ein Visualisierungsfehler auftritt.(AN-175542)
* Ein Problem wurde behoben, bei dem Dimensionsnamen in lokalisierten Umgebungen auf Englisch angezeigt wurden.(AN-178695)

#### [!DNL Analytics]Fehlerbehebungen

* Ein Problem wurde behoben, bei dem der Kantengraph in Echtzeit-Drilldown-Berichten leer war. (AN-181690)
* Ein Problem wurde behoben, bei dem Teile des Daten-Feed-Verlaufs in einigen Fällen nicht in der Benutzeroberfläche der Admin Console angezeigt wurden. (AN-176219)

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Einschränkungen für den Builder für Klassifizierungsregeln | Hinzugefügt am 5. Juni 2019. | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| Einschränkungen des neuen Segmentoperators | Hinzugefügt am 31. Mai 2019. | Ab dem 18. Juli 2019 sind die Segmentoperatoren „enthält beliebig viele“, „enthält keinerlei“, „enthält alle von“ und „enthält nicht alle“ auf 100 Wörter pro Eingabefeld beschränkt. Die Beschränkung wird nach diesem Datum auf alle neuen und geänderten Segmente angewendet. Vorhandene Segmente, die die Beschränkung überschreiten, werden weiterhin unterstützt, können jedoch erst geändert oder gespeichert werden, wenn das Eingabefeld reduziert wurde. Diese Grenzwerte werden im Rahmen kontinuierlicher Bemühungen zur Verbesserung der Abfrageleistung angewendet. |
| Bevorstehende Änderungen der Unterstützung für die Klassifizierungen **[!UICONTROL Datumsaktiviert]** und **[!UICONTROL Numerisch 2]** | Aktualisiert am 28. Mai 2019 | Die Möglichkeit, die Klassifizierungen „Numerisch 2“ und „Datumsaktiviert“ zu importieren, wurde aus der Codebasis entfernt. Diese Änderung wird mit der Wartungsversion vom Juli 2019 wirksam. Wenn die Importdatei die Spalte „Numerisch“ oder „Datumsaktiviert“ enthält, werden diese Zellen still ignoriert und alle anderen Daten in dieser Datei werden normal importiert. <br/>Vorhandene Classifications können weiterhin über den Standard-Classification-Arbeitsablauf exportiert werden und sind weiterhin in Berichten verfügbar. |
| Bevorstehende Änderung bei Berechnungen der _Berichtssumme_ | Aktualisiert am 9. Juli 2019 | Ab **18. Juni 2019** werden in Adobe Analytics Berechnungen von _Berichtssummen_ für alle Dimensionen und Metriken vereinheitlicht. Dadurch werden sich die Gesamtsummen bei manchen Berichten ändern (vor allem bei Berichten zu Eigenschaften oder Kundenattributen). Vor dieser Änderung kam es vor, dass in manchen Berichtssummen der Zeileneintrag _Unspecified_ uneinheitlich ein- oder ausgeschlossen wurde, und zwar unabhängig davon, ob _Unspecified_ im Bericht vorkam oder nicht. <br/>Ab 18. Juni 2019 wird _Nicht angegeben_ immer in Berichtssummen angezeigt, auch wenn dieser Wert nicht als Zeileneintrag im Bericht zu sehen ist. Darüber hinaus können Segmente, die die Logik _existiert_ oder _existiert nicht_ verwenden, für einige Dimensionen nach dieser Änderung andere Ergebnisse anzeigen, insbesondere Dimensionen, bei denen _Nicht angegeben_ einen speziellen Namen wie den Zeileneintrag „Eingegeben/Mit Lesezeichen versehen“ für die Dimension „Typ der verweisenden Stelle“ oder den Zeileneintrag „Sonstige“ für die Dimension „Gerätetyp“ verwendet werden. Diese Änderung betrifft Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder und die Reporting-API. |
| Aktualisierung von CSV-Downloads aus [!DNL Analysis Workspace] | 10. April 2019 | Ab dem 11. April 2019 wurden mehrere Änderungen an **[!UICONTROL CSV-Downloads]** (und **[!UICONTORL In Zwischenablage kopieren]**) in [!DNL Analysis Workspace] vorgenommen, um die Formatierung aus den exportierten Daten zu entfernen.  <ul><li>Das Tausendertrennzeichen ist nicht mehr enthalten. Das Dezimaltrennzeichen wird weiterhin enthalten sein und dem unter **[!UICONTROL Komponenten &gt; Berichtseinstellungen &gt; Tausendertrennzeichen]** definierten Format entsprechen. Hinweis: Numerische Werte, die ein Komma als Dezimaltrennzeichen verwenden, werden weiterhin in der exportierten CSV angegeben.</li><li>Es werden keine Währungssymbole angezeigt.</li><li>Es werden keine Prozentsymbole angezeigt. Prozentangaben werden in Dezimalform angezeigt. Zum Beispiel werden 75 % als 0,75 dargestellt.</li><li>Die Zeit wird in Sekunden angezeigt.</li><li>Kohortentabellen zeigen nur Rohwerte an. Prozentsätze werden entfernt.</li><li>Wenn eine Nummer ungültig ist, wird eine leere Zelle angezeigt.</li></ul> |
| Anstehende Änderung am Befehl „[!DNL Analysis Workspace] Debugger“. | 4. April 2019 | Der Konsolenbefehl zum Aktivieren des [!DNL Analysis Workspace] Debuggers wird am **13. Juni 2019** in adobeTools.debug.includeOberonXml geändert. adobe.tools.debug.includeOberonXml wird nach diesem Datum nicht mehr funktionieren. |
| Mobile Browser – Versionsnummern | 7. Februar 2019 | Am 8. Januar 2019 haben wir die Abschnittsebene bei den Versionsnummern mobiler Browser von 2 zu 1 geändert. Seit diesem Datum zeigen die Versionen nur die ersten beiden Ebenen an (Beispiel: _Firefox 64.0.2_ wird jetzt als _Firefox 64.0_ angegeben). |
| wird eingestellt [!DNL Ad Hoc Analysis] | 29. Januar 2019 | Am 6. August 2018 kündigte Adobe die Absicht an, [!DNL Ad Hoc Analysis] einzustellen. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist.<br/>Weitere Informationen dazu, welche Versionen von Java während dieses Zeitraums kompatibel sind, finden Sie unter [Arbeitsbereich entdecken](https://adobe.ly/discoverworkspace). |
| Kurz-Links[!DNL Analytics] für Berichte | 14. Januar 2019 | Kurz-Links [!DNL Analytics]für Berichte, die innerhalb eines Jahres nicht aufgerufen wurden, werden entfernt und ab Donnerstag, den 17. Januar 2019 fortlaufend gelöscht. |
| Ende der Unterstützung für TLS 1.0 | Aktualisiert am 10. Januar 2019 | Ab dem 11. Februar 2019 unterstützt die Adobe Analytics-Berichterstellung die Verschlüsselung mit TLS (Transport Layer Security) 1.0 nicht mehr. Diese Änderung ist Teil unserer ständigen Bemühungen, die höchsten Sicherheitsstandards einzuhalten und die Daten unserer Kunden zu schützen. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> Ab dem 20. Februar 2019 bietet die Adobe Analytics-Datenerfassung keine Unterstützung für TLS 1.0 mehr. Aufgrund dieser Änderung werden von Adobe keine [!DNL Analytics]Analytics-Daten von Endbenutzern mit älteren Geräten oder Webbrowsern ohne Unterstützung für TLS 1.1 oder höher erfasst. Wir gehen davon aus, dass dies keine wesentlichen Auswirkungen auf Kundendaten oder die Berichterstattung haben wird. (Wenn Ihre Website TLS 1.0 bereits nicht mehr unterstützt, sind Sie nicht betroffen.) <br/>Ab dem 11. April 2019 bietet die Reporting-API von Adobe Analytics keine Unterstützung mehr für die TLS 1.0-Verschlüsselung. Kunden, die auf die API zugreifen, sollten sicherstellen, dass sie nicht von den Auswirkungen betroffen sind. <ul><li>Für API-Clients, die Java 7 mit den Standardeinstellungen verwenden, müssen einige [Änderungen zur Unterstützung von TLS 1.2](https://www.java.com/en/configure_crypto.html) vorgenommen werden (siehe _„Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2“_). </li><li>API-Clients, die Java 8 verwenden, sollten nicht beeinträchtigt sein, da die Standardeinstellung TLS 1.2 ist.</li><li> Bei API-Clients, die andere Frameworks verwenden, müssen Sie die Details zur Unterstützung von TLS 1.2 beim jeweiligen Anbieter erfragen.</li></ul> |
| Daten-Feed: Spalte „post_product_list“ – Änderung der Größe | 9. Januar 2019 | Adobe hat die Größe der Spalte „post_product_list“ am dem 7. Februar 2019 von 64 KB auf 16 MB erweitert. Diese Änderung stellt sicher, dass bei der Verarbeitung zu „post_product_list“ hinzugefügte Merchandising-eVar-Werte nicht zu abgeschnittenen Produkt- und Umsatzwerten führen. Wenn Sie über Prozesse verfügen, bei denen post_product_list-Werte erfasst werden, stellen Sie sicher, dass diese Prozesse Werte mit einer Länge von bis zu 16 MB verarbeiten können (ansonsten werden Werte bei 16 KB abgeschnitten), um Datenerfassungsfehler zu vermeiden. |
| Verwaltungsänderungen mit Auswirkung auf inaktive [!DNL Analytics Live Stream]-Endpunkte | 20. Dezember 2018 | Ab dem 1. Februar 2019 können [!DNL Live Stream]-Endpunkte, die 90 Tage lang keine aktive Verbraucherverbindung aufweisen, deaktiviert werden. Sie können sich an die Kundenunterstützung wenden, um sich über Ihre [!DNL Live Stream]-Endpunkte zu informieren und diese bei Bedarf wieder zu aktivieren. Stellen Sie außerdem sicher, dass für Ihre Verbraucherprozesse eine dauerhafte Verbindung besteht, wie es das Konzept des Dienstes vorsieht, und dass sie so implementiert sind, dass sie sich wieder verbinden, wenn die Verbindung getrennt oder unterbrochen wird. |
| Aktualisieren von Adobe [!DNL Report Builder] aufgrund der Einstellung des Supports für TLS 1.0 | 7. Sept. 2018 | Aufgrund der Unterstützung für TLS 1.0 sollten Benutzer von [!DNL Report Builder] die Version 5.6.21 vor Februar 2019 herunterladen. Nach diesem Datum sind frühere Versionen von [!DNL Report Builder] nicht mehr funktionstüchtig. |

### AppMeasurement {#appm}

Veröffentlicht am 15. Juli 2019:

**AppMeasurement für JavaScript 2.15.0**

* Scroll-Reichweitenverfolgung für Activity Map zur Activity Map-Erweiterung hinzugefügt (AN-172949)
* DIL 9.2 zu AppMeasurement hinzugefügt. (AN-182472)

In der [Versionshistorie zu AppMeasurement](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html) finden Sie Informationen zu den verschiedenen Versionen von AppMeasurement auf den folgenden Plattformen:

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone, XBOX, Silverlight und .NET
* [!DNL BlackBerry]
* Java
* PHP
* Symbian

### Data Workbench {#aa-dwb}

* Updated the help definition for [log (X, B)](https://marketing.adobe.com/resources/help/en_US/insight/client/c_syntx_mtrc_exp.html) metric syntax documentation. (AN-180527)

Die neuesten Versionsinformationen finden Sie in den [Datenbasis-Versionshinweisen](https://marketing.adobe.com/resources/help/en_US/insight/whatsnew/).

## Audience Manager {#aam}

**Korrekturen und Verbesserungen**

* Auf der Seite [!UICONTROL Segmentübersicht] ist die Breite des Segmentspeicherordners jetzt flexibel. Dadurch werden jetzt auch Segmente mit längeren Namen angezeigt. (AAM-48400)
* In [!UICONTROL algorithmischen Modellen] wurde ein Problem behoben, bei dem das Verschieben des Reglers **Reichweite und Genauigkeit anpassen** keine Wirkung auf die Reichweite oder Genauigkeit des Modells hatte. (AAM-47996)
* In Analytics-Zielen wurde ein Problem behoben, bei dem die Schaltfläche zum Herunterladen einer CSV-Datei mit Segmenten, die einen Konflikt mit Datenexport-Steuerelementen und/oder Datenfreigaberichtlinien von Drittanbietern verursachten, fehlerhaft war. (AAM-48100)
* Ein Problem wurde behoben, bei dem Kunden beim Anmelden bei der Audience Manager-Benutzeroberfläche Fehlermeldungen angezeigt wurden, laut denen der Zugriff fälschlicherweise untersagt war. (AAM-47632)

## Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktversionen

Informationen zu neuen Funktionen für die folgenden Produkte:

#### Cloud Manager 2019.6.0

The latest Cloud Manager release (2019.6.0) contains a new [Product Update Wizard](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/product-update-wizard/overview-productupdate-wizard.html) to help customers successfully run an AEM update.

* [Versionshinweise für Cloud Manager 2019.6.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

#### XML-Dokumentation 3.4

Die XML-Dokumentation 3.4 ist jetzt verfügbar.

***Versionshinweise***

* Unterstützung für AEM 6.5 wurde hinzugefügt.
* Editor-Änderungen:
   * Vorschau der Map-Ebenen
   * Tabellen: Eine Option zum Kopieren einer `entry`- oder `complete`-Zeile in einer Tabelle mit der Kopieren-und-Einfügen-Funktion wurde hinzugefügt.
   * Tabellen: Eine Option zur Auswahl und Zusammenführung mehrerer Zellen in einer Spalte wurde bereitgestellt.
   * Tabellen: Eine Möglichkeit wurde bereitgestellt, die Eigenschaften von Tabellenspalten im Autorenmodus des Webeditors zu definieren.
   * Tabellen: Eine Möglichkeit wurde bereitgestellt, Spaltenproportionen und -größen in einer Standardtabelle anzupassen.
   * Tabellen: Zeilen und Spalten können jetzt in der Autorenansicht ausgewählt werden.
   * Tabellen: Stile und Eigenschaften (align, valign) wurden im Webeditor zur Ausrichtung von Tabellenzellen aktiviert.
   * In der Tags-Vollansicht wurden Fehler beim Kopieren und Einfügen sowie Ziehen und Ablegen von Inhalten behoben.
   * In Editor-Tabs werden Thementitel angezeigt.
   * Im Webeditor wurden Leistungsprobleme behoben.
* Während der Übersetzung wird die Grundlinie auf den übersetzten Inhalt übertragen.
* Vorabdefinition der Bedingungen wird während des Übersetzungs-Workflows übertragen.
* Es wurde die Möglichkeit geschaffen, Beschriftungen auf alle abhängigen Elemente einer Map von der Grundlinie aus anzuwenden.
* Eine Schaltfläche zum Herunterladen der Map mit allen abhängigen Elementen als ZIP-Datei wurde bereitgestellt.
* Bei der Konversion von XHTML in DITA wurden in folgenden Bereichen Verbesserungen bereitgestellt:
   * Name der generierten DITAMAP ist nun mit dem Namen der hochgeladenen ZIP-Datei identisch.
   * Zusätzliche Unterstützung von HTML-Elementen und -Attributen.
   * Unterstützung von gleichzeitiger Erfassung von HTML-ZIP-Dateien.
   * Die Hierarchie des Unterordners, in die die ZIP-Datei hochgeladen wird (*unter dem in h2d_io.xml konfigurierten Eingabepfad*), wird für die generierte Ausgabe beibehalten (*unter dem konfigurierten Ausgabepfad*).
* Audit-Protokolle werden bereitgestellt, anhand deren erkennbar ist, wer zu welcher Version zurückkehrt ist und warum.
* AEM-Site-Neuerstellung:
   * Die Neuerstellung kann für untergeordnete Maps deaktiviert werden.
   * Für die Neuerstellung wurden Post-Generation-Workflows aktiviert.
   * Die Neuerstellungsoption kann für ein Chunked-Thema deaktiviert werden und die Option kann für ein übergeordnetes Thema verfügbar gemacht werden, in dem das Chunked-Attribut verwendet wird.
* DITA-Suche funktioniert jetzt in der AEM Asset-Suche mit der AND-Logik.
* In den Ergebnissen werden nicht die im Ausgabeordner für die Übersetzung gespeicherten temporären Dateien angezeigt.
* Grundlinien-Tab:
   * Leistungsverbesserungen beim Erstellen einer Grundlinie.
   * Themen können nach Datum für den Client-Zeitstempel ausgewählt werden.
* API zum Löschen von Bezeichnungen.

#### Produktwartung

**AEM 6.2 SP1-CFP20**

AEM 6.2 Service Pack 1 – Cumulative Fix Pack 20 (6.2.1.20) vom 6. Juni 2019 ist eine wichtige Aktualisierung, die für Kunden wichtige Fehlerbehebungen enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.2 SP1 im Dezember 2016 veröffentlicht wurden.

* [Versionshinweise](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

AEM 6.3.3.5 vom 3. Juli 2019 ist eine Aktualisierung, die für Kunden wichtige Fehlerbehebungen enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.3 im April 2017 veröffentlicht wurden.

* [Versionshinweise](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

AEM 6.4.5.0 vom 3. Juli 2019 ist eine Aktualisierung, die für Kunden wichtige Fehlerbehebungen enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.4 im April 2018 veröffentlicht wurden.

* [Versionshinweise](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

AEM 6.5.1.0 vom 3. Juli 2019 ist eine Aktualisierung, die für Kunden wichtige Fehlerbehebungen enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.5 im April 2019 veröffentlicht wurden.

* [Versionshinweise](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Selbsthilfe

**Aktualisierung der Cache-Invalidierung in AEM**

An important AEM patch for the AEM 6.5 clientlibs cache invalidation is available by way of the [AEM 6.5.1.0 update](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html) or this [KB article](https://helpx.adobe.com/experience-manager/kb/avoid-crx-quickstart-deletion-in-aem-6-5.html).

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

Versionshinweise finden Sie unter:

* Adobe Campaign Classic [19.1.2](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – build 9029
* Adobe Campaign Standard [19.2.3](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-3---june-2019)
* Adobe Campaign Standard [19.2.4](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-4---june-2019)
* Adobe Campaign Standard [19.2.7](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html#release-19-2-7---july-2019)

Eine Produktdokumentation finden Sie hier:

* Adobe Campaign Standard: [Dokumentation](https://helpx.adobe.com/support/campaign/standard.html) – [ Versionshinweise](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) – [Videos zu Funktionen](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Dokumentation](https://helpx.adobe.com/support/campaign/classic.html) – [Versionshinweise](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Videos zu Funktionen](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## [!DNL Target] {#target}

See [Target release notes (pre-release)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release information about Target.

## Magento {#magento}

Informationen zu den Versionshinweisen zu Magento Commerce und Magento Open Source finden Sie unter:

* [Magento Open Source 2.3.2 - Versionshinweise](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Magento Commerce 2.3.2 - Versionshinweise](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)
