---
title: Adobe Experience Cloud – Versionshinweise
description: Mai 2019 Experience Cloud - Versionshinweise
doc-type: Versionshinweise
last-update: Juli 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 9d10de6924f3c40435d172602746f312195a675e

---


# Frühzeitiger Zugriff – Versionshinweise zur Adobe Experience Cloud

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

>[!IMPORTANT]
>
>Diese Seite enthält Inhalte einer Vorabversion und kann vor der geplanten Veröffentlichung der Version geändert werden.

>[!NOTE]
>
>Abonnieren Sie das [Prioritätsprodukt-Update von Adobe](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bevorstehende Versionen benachrichtigt zu werden. Sie erhalten drei bis fünf Werktage vor der Veröffentlichung der Version eine Benachrichtigung. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Releasedatum: 18. Juli 2019**

* [Experience Cloud Core Services und Administration](#experiencecloud)
* [!DNL Analytics](#analytics)**(Aktualisiert am 15. Juli)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)

## Core services and administration {#experiencecloud}

Versionshinweise für die Experience Cloud-Schnittstelle, einschließlich [!UICONTROL der Plattform]-Core-Services und der Produktverwaltung.

* [Experience Cloud ID-Dienst](#ecid)
* [Mobile Services und Mobile SDK](#mobile)
* [Experience Platform Launch](#launch)
* [Sicherheitsbulletins und -hinweise](#security)

### Experience Cloud ID-Dienst {#ecid}

**Fehlerbehebungen und Updates**

* `cookieDomain` config update: Die Bibliothek weist automatisch eine Cookie-Domäne auf oberster Ebene zu, wenn `cookieDomain` sie nicht `initConfig` eingestellt ist. (CORE-29223)
* Fixed an issue for `getVisitorValue` in `localVisitor`. (CORE-31287)
* Fixed an inconsistency of `MCOPTOUT` value in parent visitor versus iframe child visitor from `getVisitorValue` method. (CORE-29719)
* Problem mit Sicherheitslücken in jquery 3.2.1 behoben. (CORE-31183)
* Opt-in update: added `optIn.off` to unsubscribe from events.
* Fixed an issue related to `setTimeout` function. (CORE-30623)

See [Experience Cloud ID Service](https://marketing.adobe.com/resources/help/en_US/mcvid/mcvid-release-notes.html) for cumulative release notes.

### Mobile Services und Mobile SDK {#mobile}

Ios und Android wurden wie folgt aktualisiert:

**iOS**

* Adobe Target: All requests now include the client and the `sessionId` in the URL query parameters.
* Adobe Target: Ein Speicherleck wurde behoben.
* Visitor ID Service: The `visitorAppendToURL` and `visitorGetUrlVariablesAsync` APIs no longer double-encode their return values. Die Doppelkodierung führte dazu, dass die Rückgabewerte aus diesen apis durch bestimmte Sicherheitsprüfungen gekennzeichnet wurden.

**Android**

* Ziel: Alle Anforderungen enthalten jetzt den Client und die sessionid in den URL-Abfrageparametern.
* In-App-Nachrichten: Es wurde ein Problem behoben, durch das beim Auslösen einer Nachricht mit einer leeren Clickthrough-URL Android-Apps abgestürzt wurden.
* Visitor ID Service: The `Visitor.appendToURL` and `Visitor.getUrlVariablesAsync` APIs no longer double-encode their return values. Die Doppelkodierung führte dazu, dass die Rückgabewerte aus diesen apis durch bestimmte Sicherheitsprüfungen gekennzeichnet wurden.

Informationen zur Produktdokumentation finden Sie unter [Mobile Services](https://docs.adobe.com/content/help/en/mobile-services/using/home.html).

Weitere Informationen zu den Mobile-SDKs finden Sie unter [Android-SDK 4.x für Experience Cloud-Lösungen](https://docs.adobe.com/content/help/en/mobile-services/android/overview.html) und [iOS-SDK 4.x für Experience Cloud-Lösungen](https://docs.adobe.com/content/help/en/mobile-services/ios/overview.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) (links to product help) for release notes and product documentation.

### Security bulletins and advisories {#security}

See [Security bulletins and advisories](https://helpx.adobe.com/security.html) for important information regarding security vulnerabilities that could affect specific versions of Adobe products.

## [!DNL Analytics] {#analytics}

* [Neue Funktionen und Fehlerbehebungen in Adobe Analytics](#aa-features) **(Aktualisiert am 15. Juli)**
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)

### Neue Funktionen in Version [!DNL Analytics] {#aa-features}

Eine Produktdokumentation finden Sie auf der [Startseite der Hilfe zu Analytics](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

| Komponente | Beschreibung |
| -----------| ---------- |   
| Analysis Workspace - Verbesserungen der Kohortenanalyse | Neue Einstellungen für Kohortenanalyse wurden hinzugefügt: <ul><li>Nur % anzeigen</li><li>Runde % bis nächstem Ganzes</li><li>Eine durchschn. % Zeile am oberen Rand anzeigen</li></ul> |
| Analysis Workspace | In the left rail, users now have the option to _Show items from last 18 months_. Zuvor lag der Lookback-Zeitraum maximal 6 Monate. Dies erleichtert das Vergleichen mit Seiten oder Kampagnen aus dem letzten Jahr, bis zu 18 Monate. |
| Neue Vorlage für Analysis Workspace | Wir haben eine neue Vorlage namens "Magento: Marketing &amp; Commerce "in den Analysis Workspace. Es ist speziell für Magento e-commerce-Kunden konzipiert, aber jeder Einzelhändler kann ihn verwenden, um einzigartige Einblicke in seine Commerce-Aktivitäten zu erhalten. |

#### [!DNL Analysis Workspace] Fehlerbehebungen

* Es wurde ein Problem behoben, durch das Multibyte-Zeichen beim Unterteilen von Dimensionen nach unten angezeigt wurden. (AN-180112)
* Es wurde ein Problem mit Visualisierungsfehlern behoben - jetzt wird eine rote Fehlerleiste angezeigt, wenn ein Visualisierungsfehler auftritt.(AN-175542)
* Es wurde ein Problem behoben, durch das Dimensionsnamen in lokalisierten Umgebungen als Englisch angezeigt wurden.(AN-178695)

#### [!DNL Analytics] Fehlerbehebungen

* Es wurde ein Problem behoben, durch das das Liniendiagramm in Echtzeit-Drilldown-Berichten leer war. (AN-181690)
* Es wurde ein Problem behoben, bei dem Teile des Datenfeedverlaufs in einigen Fällen nicht in der Benutzeroberfläche der Admin-Konsole angezeigt wurden. (AN-176219)

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt  oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Einschränkungen für den Builder für Klassifizierungsregeln | Hinzugefügt am 5. Juni 2019. | These limits are not new, but have been added to the documentation [here](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| Einschränkungen des neuen Segmentoperators | Hinzugefügt am 31. Mai 2019. | Ab dem 18. Juli 2019 sind die Segmentoperatoren „enthält beliebig viele“, „enthält keinerlei“, „enthält alle von“ und „enthält nicht alle“ auf 100 Wörter pro Eingabefeld beschränkt. Die Beschränkung wird nach diesem Datum auf alle neuen und geänderten Segmente angewendet. Vorhandene Segmente, die die Beschränkung überschreiten, werden weiterhin unterstützt, können jedoch erst geändert oder gespeichert werden, wenn das Eingabefeld reduziert wurde. Diese Grenzwerte werden im Rahmen kontinuierlicher Bemühungen zur Verbesserung der Abfrageleistung angewendet. |
| Bevorstehende Änderungen der Unterstützung für die Klassifizierungen **[!UICONTROL Datumsaktiviert]** und **[!UICONTROL Numerisch 2]** | Aktualisiert am 28. Mai 2019 | Die Möglichkeit, die Klassifizierungen „Numerisch 2“ und „Datumsaktiviert“ zu importieren, wurde aus der Codebasis entfernt. Diese Änderung wird mit der Wartungsversion vom Juli 2019 wirksam. Wenn die Importdatei die Spalte „Numerisch“ oder „Datumsaktiviert“ enthält, werden diese Zellen still ignoriert und alle anderen Daten in dieser Datei werden normal importiert. <br/>Vorhandene Classifications können weiterhin über den Standard-Classification-Arbeitsablauf exportiert werden und sind weiterhin in Berichten verfügbar. |
| Bevorstehende Änderung bei Berechnungen der _Berichtssumme_ | Aktualisiert am 9. Juli 2019 | Ab **18. Juni 2019** werden in Adobe Analytics Berechnungen von _Berichtssummen_ für alle Dimensionen und Metriken vereinheitlicht. Dadurch werden sich die Gesamtsummen bei manchen Berichten ändern (vor allem bei Berichten zu Eigenschaften oder Kundenattributen). Vor dieser Änderung kam es vor, dass in manchen Berichtssummen der Zeileneintrag _Unspecified_ uneinheitlich ein- oder ausgeschlossen wurde, und zwar unabhängig davon, ob _Unspecified_ im Bericht vorkam oder nicht. <br/>Ab 18. Juni 2019 wird _Nicht angegeben_ immer in Berichtssummen angezeigt, auch wenn dieser Wert nicht als Zeileneintrag im Bericht zu sehen ist. Additionally, segments using _exists_ or _does not exist_ logic may see different results for some dimensions after this change, specifically dimensions where _Unspecified_ has a special name such as the "Typed/Bookmarked" line item for Referrer Type dimension or the "Other" line item for the Device Type dimension. Diese Änderung betrifft Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder und die Reporting-API. |
| Aktualisierung von CSV-Downloads aus [!DNL Analysis Workspace] | 10. April 2019 | Ab dem 11. April 2019 wurden mehrere Änderungen an **[!UICONTROL CSV-Downloads]** (und **[!UICONTORL In Zwischenablage kopieren]**) in [!DNL Analysis Workspace] vorgenommen, um die Formatierung aus den exportierten Daten zu entfernen.  <ul><li>Das Tausendertrennzeichen ist nicht mehr enthalten. Das Dezimaltrennzeichen wird weiterhin enthalten sein und dem unter **[!UICONTROL Komponenten &gt; Berichtseinstellungen &gt; Tausendertrennzeichen]** definierten Format entsprechen. Hinweis: Numerische Werte, die ein Komma als Dezimaltrennzeichen verwenden, werden weiterhin in der exportierten CSV angegeben.</li><li>Es werden keine Währungssymbole angezeigt.</li><li>Es werden keine Prozentsymbole angezeigt. Prozentangaben werden in Dezimalform angezeigt. Zum Beispiel werden 75 % als 0,75 dargestellt.</li><li>Die Zeit wird in Sekunden angezeigt.</li><li>Kohortentabellen zeigen nur Rohwerte an. Prozentsätze werden entfernt.</li><li>Wenn eine Nummer ungültig ist, wird eine leere Zelle angezeigt.</li></ul> |
| Anstehende Änderung am Befehl „[!DNL Analysis Workspace] Debugger“. | 4. April 2019 | Der Konsolenbefehl zum Aktivieren des [!DNL Analysis Workspace] Debuggers wird am **13. Juni 2019** in adobeTools.debug.includeOberonXml geändert. adobe.tools.debug.includeOberonXml wird nach diesem Datum nicht mehr funktionieren. |
| Mobile Browser – Versionsnummern | 7. Februar 2019 | Am 8. Januar 2019 haben wir die Abschnittsebene bei den Versionsnummern mobiler Browser von 2 zu 1 geändert. Seit diesem Datum zeigen die Versionen nur die ersten beiden Ebenen an (Beispiel: _Firefox 64.0.2_ wird jetzt als _Firefox 64.0_ angegeben). |
| wird eingestellt [!DNL Ad Hoc Analysis] | 29. Januar 2019 | Am 6. August 2018 kündigte Adobe die Absicht an, [!DNL Ad Hoc Analysis] einzustellen. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist.<br/>Weitere Informationen dazu, welche Versionen von Java während dieses Zeitraums kompatibel sind, finden Sie unter [Arbeitsbereich entdecken](https://adobe.ly/discoverworkspace). |
| Short [!DNL Analytics] report links | 14. Januar 2019 | Any short [!DNL Analytics] report links that have not been visited within one year will be cleaned up and deleted starting on Thursday, January 17, 2019, on a rolling schedule. |
| Ende der Unterstützung für TLS 1.0 | Aktualisiert am 10. Januar 2019 | Ab dem 11. Februar 2019 unterstützt die Adobe Analytics-Berichterstellung die Verschlüsselung mit TLS (Transport Layer Security) 1.0 nicht mehr. Diese Änderung ist Teil unserer ständigen Bemühungen, die höchsten Sicherheitsstandards einzuhalten und die Daten unserer Kunden zu schützen. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> Ab dem 20. Februar 2019 bietet die Adobe -Datenerfassung keine Unterstützung für TLS 1.0 mehr. Aufgrund dieser Änderung werden von Adobe keine [!DNL Analytics]Analytics-Daten von Endbenutzern mit älteren Geräten oder Webbrowsern ohne Unterstützung für TLS 1.1 oder höher erfasst. Wir gehen davon aus, dass dies keine wesentlichen Auswirkungen auf Kundendaten oder die Berichterstattung haben wird. (Wenn Ihre Website TLS 1.0 bereits nicht mehr unterstützt, sind Sie nicht betroffen.) <br/>Ab dem 11. April 2019 bietet die Reporting-API von Adobe Analytics keine Unterstützung mehr für die TLS 1.0-Verschlüsselung. Kunden, die auf die API zugreifen, sollten sicherstellen, dass sie nicht von den Auswirkungen betroffen sind. <ul><li>Für API-Clients, die Java 7 mit den Standardeinstellungen verwenden, müssen einige [Änderungen zur Unterstützung von TLS 1.2](https://www.java.com/en/configure_crypto.html) vorgenommen werden (siehe _„Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2“_). </li><li>API-Clients, die Java 8 verwenden, sollten nicht beeinträchtigt sein, da die Standardeinstellung TLS 1.2 ist.</li><li> Bei API-Clients, die andere Frameworks verwenden, müssen Sie die Details zur Unterstützung von TLS 1.2 beim jeweiligen Anbieter erfragen.</li></ul> |
| Daten-Feed: Spalte „post_product_list“ – Änderung der Größe | 9. Januar 2019 | Adobe hat die Größe der Spalte „post_product_list“ am dem 7. Februar 2019 von 64 KB auf 16 MB erweitert. Diese Änderung stellt sicher, dass bei der Verarbeitung zu „post_product_list“ hinzugefügte Merchandising-eVar-Werte nicht zu abgeschnittenen Produkt- und Umsatzwerten führen. Wenn Sie über Prozesse verfügen, bei denen post_product_list-Werte erfasst werden, stellen Sie sicher, dass diese Prozesse Werte mit einer Länge von bis zu 16 MB verarbeiten können (ansonsten werden Werte bei 16 KB abgeschnitten), um Datenerfassungsfehler zu vermeiden. |
| Verwaltungsänderungen mit Auswirkung auf inaktive [!DNL Analytics Live Stream]-Endpunkte | 20. Dezember 2018 | Ab dem 1. Februar 2019 können [!DNL Live Stream]-Endpunkte, die 90 Tage lang keine aktive Verbraucherverbindung aufweisen, deaktiviert werden. Sie können sich an die Kundenunterstützung wenden, um sich über Ihre [!DNL Live Stream]-Endpunkte zu informieren und diese bei Bedarf wieder zu aktivieren. Stellen Sie außerdem sicher, dass für Ihre Verbraucherprozesse eine dauerhafte Verbindung besteht, wie es das Konzept des Dienstes vorsieht, und dass sie so implementiert sind, dass sie sich wieder verbinden, wenn die Verbindung getrennt oder unterbrochen wird. |
| Aktualisieren von Adobe [!DNL Report Builder] aufgrund der Einstellung des Supports für TLS 1.0 | 7. Sept. 2018 | Aufgrund der Unterstützung für TLS 1.0 sollten Benutzer von [!DNL Report Builder] die Version 5.6.21 vor Februar 2019 herunterladen. Nach diesem Datum sind frühere Versionen von [!DNL Report Builder] nicht mehr funktionstüchtig. |

### AppMeasurement {#appm}

Veröffentlicht am 15. Juli 2019:

**Appmeasurement für javascript 2.15.0**

* Activity Map-Bildlaufverfolgung zur Activity Map-Erweiterung hinzugefügt (AN -172949)
* DIL 9.2 zu appmeasurement hinzugefügt. (AN-182472)

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

* On the [!UICONTROL Segments Overview] page, the width of the segment storage folder is now flexible. Dadurch können Sie zwischen Segmenten mit längeren Namen unterscheiden. (AAM-48400)
* Fixed an issue in [!UICONTROL Algorithmic Models], where moving the **Adjust Reach &amp; Accuracy** slider did not affect the model's reach or accuracy. (AAM-47996)
* Es wurde ein Problem in Analytics-Zielen behoben, bei dem die Schaltfläche zum Herunterladen einer. csv-Datei von Segmenten, die Konflikte mit Datenexportsteuerelementen und/oder Datenfreigaberichtlinien von Drittanbietern verursachten, beschädigt war. (AAM-48100)
* Es wurde ein Problem behoben, durch das Kunden beim Anmelden bei der Audience Manager-Benutzeroberfläche fehlerhafte Fehlermeldungen angezeigt hatten. (AAM-47632)

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

* Unterstützung für AEM 6.5 hinzugefügt.
* Editor-Änderungen:
   * Ebenenvorschau anzeigen.
   * Tables - provided an option to copy an `entry` or a `complete` row within a table using copy and paste.
   * Tabellen: Stellt eine Option bereit, um mehrere Zellen in einer Spalte auszuwählen und diese zusammenzuführen oder zusammenzuführen.
   * Tabellen: Stellt eine Möglichkeit bereit, die Tabellenspalteneigenschaften im Autorenmodus des Webeditors festzulegen.
   * Tabellen - bietet eine Möglichkeit, Spaltenproportionen und -größen in einer Standardtabelle anzupassen.
   * Tabellen - Auswahl von Zeilen und Spalten in der Autorenansicht.
   * Tabellen - Aktivierte Stile und Eigenschaften (Ausrichten, Valign) im Webeditor für die Tabellenzellenausrichtung.
   * Fehlerbehebungen in der vollständigen Tags-Ansicht, einschließlich Szenarien zum Kopieren und Einfügen sowie Ziehen und Ablegen von Inhalten.
   * Thementitel in Editor-Registerkarten anzeigen.
   * Es wurden Leistungsprobleme im Webeditor behoben.
* Übermittlungsgrundlinie während der Übersetzung auf den übersetzten Inhalt übertragen.
* Übertragungsbedingung während des Übersetzungs-Workflows.
* Es wurde die Möglichkeit hinzugefügt, Beschriftungen auf alle abhängigen Elemente einer Karte von Grundlinie anzuwenden.
* Eine Schaltfläche zum Herunterladen der Karte mit allen abhängigen Elementen als ZIP-Datei.
* XHTML zu DITA-Konversionsverbesserungen:
   * Der Name der generierten DITAMAP ist nun mit dem Namen der hochgeladenen ZIP-Datei identisch.
   * Zusätzliche Unterstützung für zusätzliche HTML-Elemente und -attribute.
   * Unterstützung für gleichzeitige Erfassung von HTML-Zip-Dateien.
   * The sub-folder hierarchy where the zip is uploaded (*under input path as configured in h2d_io.xml*), is retained for the generated output (*under the configured output path*).
* Anhand von Audit-Protokollen können Sie erkennen, wer auf welche Version zurückkehrt und warum.
* AEM-Site-Regeneration:
   * Deaktivieren Sie die Regeneration für Untergeordnete Maps.
   * Arbeitsabläufe für die Post-Generierung, die für Anwendungsfälle aktiviert wurden.
   * Deaktivieren Sie die Option "Neu generieren" für ein angegebenes Thema und machen Sie die Option für übergeordnetes Thema verfügbar, auf das das chunked-Attribut angewendet wird.
* DITA-Suche funktioniert in der AEM Asset-Suche jetzt auf der AND-Logik.
* Die Ergebnisse sollen nicht die im Ausgabeordner für die Übersetzung gespeicherten temporären Dateien anzeigen.
* Grundlinienregisterkarte:
   * Leistungsverbesserungen beim Öffnen einer Grundlinie.
   * Auswählen von Themen nach Datum, um auf dem Client-Zeitstempel zu funktionieren.
* API zum Löschen von Bezeichnungen.

#### Produktwartung

**AEM 6.2 SP1-CFP20**

AEM 6.2 Service Pack 1 - Cumulative Fix Pack 20 (6.2.1.20), veröffentlicht am 6. Juni 2019, ist ein wichtiges Update, das wichtige Fehlerbehebungen in Kunden enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.2 SP 1 Dezember 2016 veröffentlicht wurden.

* [Versionshinweise](https://helpx.adobe.com/experience-manager/release-notes--aem-6-2-cumulative-fix-pack.html)
* [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.3.3.5**

AEM 6.3.3.5, veröffentlicht am 3. Juli 2019, ist ein wichtiges Update, das wichtige Fehlerbehebungen in Kunden enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.3 April 2017 veröffentlicht wurden.

* [Versionshinweise](https://helpx.adobe.com/experience-manager/6-3/release-notes/sp3-release-notes.html)
* [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.4.5.0**

AEM 6.4.5.0, veröffentlicht am 3. Juli 2019, ist ein wichtiges Update, das wichtige Fehlerbehebungen in Kunden enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.4 im April 2018 veröffentlicht wurden.

* [Versionshinweise](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
* [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM 6.5.1.0**

AEM 6.5.1.0, veröffentlicht am 3. Juli 2019, ist ein wichtiges Update, das wichtige Fehlerbehebungen in Kunden enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.5 im April 2019 veröffentlicht wurden.

* [Versionshinweise](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
* [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Selbsthilfe

**Aktualisierung der AEM-Cache-Speicherung**

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

See [Target release notes (pre-release)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) for the latest release infomration about Target.

## Magento {#magento}

Informationen zu den Versionshinweisen zu Magento Commerce und Magento Open Open finden Sie unter:

* [Magento Open Source 2.3.2 - Versionshinweise](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2OpenSource.html)
* [Magento Commerce 2.3.2 - Versionshinweise](https://devdocs.magento.com/guides/v2.3/release-notes/ReleaseNotes2.3.2Commerce.html)
