---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 8296d1788e4768e12b7dcbb6b520c534419d6360
workflow-type: tm+mt
source-wordcount: '5161'
ht-degree: 37%

---


# Versionshinweise zu Adobe Experience Cloud - Mai 2020

![Banner](/assets/experience-cloud-banner-3.png)

Diese Seite enthält neue Funktionen, Fehlerbehebungen und wichtige Hinweise in [!DNL Adobe Experience Cloud]. Das Release-Datum der Lösung kann unterschiedlich sein. Hier finden Sie die neuesten Updates.

>[!NOTE]
>
>Abonnieren Sie [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bald verfügbare Versionen benachrichtigt zu werden.

**Veröffentlichungsdatum: 2020. Mai**

Neueste Aktualisierung: **27. Mai 2020**

* [Systemstatus von Adobe](#status)
* [Experience Cloud-Benutzeroberfläche](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**Aktualisiert am 27. Mai 2020**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/de-DE/target/using/release-notes/target-release-notes.html) (Link zur Target-Hilfeseite)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/de/primetime/user-guide.html) (Link zur Primetime-Hilfeseite)

Benötigen Sie Hilfe? Besuchen Sie [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) , um von Adobe kuratierte Kurse, technische Dokumentation, schnelle Antworten, Einblicke in die Community und Schulungen unter Kursleitern zu erhalten.

## ![Symbol](/assets/adobe.png) Systemstatus von Adobe {#status}

[!UICONTROL Der Adobe-Systemstatus] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe Cloud-Produkten und -Diensten. Weitere Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/).

Releasedatum: **21. Mai 2020**

**Neuigkeiten**

* Mit Ihrer Adobe ID können Sie Ereignisbenachrichtigungen mit größerer Granularität bis hinunter zur Produktangebot- und Add-on-Ebene abonnieren. Damit Sie Ihr Abonnement schneller einrichten können, empfiehlt das Self-Abonnement-Verfahren jetzt eine Auswahl von Produkten und Angeboten, die auf Ihren Produktberechtigungen basieren. Dadurch wird die Anzahl der E-Mails, die Sie erhalten, verringert und relevantere Benachrichtigungen in Ihrem Posteingang bereitgestellt. Weitere Informationen erhalten Sie unter [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Ab heute verfügbare neue Funktionen und Verbesserungen**

| Funktion | Beschreibung |
| -----------| ---------- |
| Verbesserte Benutzererfahrung bei Abonnements und Benachrichtigungen | <ul><li>[!DNL Marketo Engage] Regionale Standorte werden nun basierend auf der Liste der ausgewählten Produktangebote gefiltert.</li><li>[!DNL Marketo Engage] E-Mail-Benachrichtigungen sind für die Benutzerregion, den Standort und die Umgebung relevant.</li></ul> |
| Bestätigung des Ereignis-Abonnements | <ul><li>Sie können jetzt eine E-Mail-Bestätigung erhalten, wenn Sie laufende Updates für einzelne Ereignis abonnieren.</li></ul> |
| Verbesserungen der Benutzerfreundlichkeit der globalen Navigation | <ul><li>Konsistente Benutzererfahrung mit `Adobe.com` im Navigationsmenü auf der obersten Navigationsebene.</li></ul> |

## ![Symbol](/assets/ec_appicon_24.png) Experience Cloud-Benutzeroberfläche {#ecloud}

Allgemeine Aktualisierungen der Experience Cloud-Oberfläche.

**Einheitliche Produktdomäne**

Adobe hat die Domäne und die Kopfzeile der Benutzeroberfläche aktualisiert, um Ihre Erfahrung in allen Experience Cloud-Anwendungen zu vereinheitlichen und zu verbessern. Diese simplen Aktualisierungen sollen die Benutzerfreundlichkeit vereinfachen und verbessern. Diese Verbesserungen ändern Ihre aktuelle Workflows nicht.

Zu den Aktualisierungen gehören:

* Neue Anwendungs-URLs: `experience.adobe.com/<application name>`:
   * Dieses URL-Muster wird schließlich von allen Produkten übernommen. Im Laufe des Monats werden neue URLs hinzugefügt werden.
   * Browserunterstützung: Unterstützte Browser sind [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] und [!DNL Opera] (neueste Versionen). **Hinweis:** Obwohl die Experience Cloud-Oberfläche diese Browser unterstützt, unterstützen einzelne Anwendungen möglicherweise nicht alle Browser. ([Analytics](https://docs.adobe.com/content/help/de-DE/analytics/admin/sys-reqs.html) unterstützt beispielsweise nicht [!DNL Opera] und [Target](https://docs.adobe.com/help/de-DE/target/using/implement-target/before-implement/supported-browsers.html) unterstützt nicht [!DNL Safari].)
   * (Nur [!DNL Safari]) Die Domänenänderung kann bei [!DNL Safari] zu Cookie-Problemen führen. Wenn Sie in den Datenschutzvoreinstellungen von [!DNL Safari] die Option _Prevent cross-site tracking_ (Website-übergreifendes Tracking verhindern) deaktivieren, werden domänenübergreifende Cookies (und alle Site-übergreifenden Ereignisse) aktiviert, sodass Experience Cloud in dieser neuen Domäne funktionieren kann.
* Einfacherer Wechsel zwischen Ihren Organisationen oder zu einer anderen Anwendung.
* Verbesserte Produkthilfe: [!UICONTROL Experience League] ist in das Produkt integriert, sodass bei einer Hilfesuche auch Ergebnisse aus Community-Foren und Videos berücksichtigt werden. Diese Änderung vereinfacht den Zugriff auf weitere Inhalte und hilft Ihnen, Experience Cloud optimal zu nutzen. Zusätzlich können Sie unter **[!UICONTROL Hilfe]** > **[!UICONTROL Feedback]** Probleme melden oder Ihre Ideen mit Adobe teilen.

Die folgenden Apps verwenden die neue Domäne &quot;experience.adobe.com&quot;:

| App oder Dienst | Domäne |
| -----------| ---------- |
| Experience Cloud-Startseite | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Reisemanagement | `experience.adobe.com/journeys` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Control Panel von Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Softwareverteilung | `experience.adobe.com/downloads` |
| Admin Tool (Beta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Pinnwand und Sammlungen]**, ein älterer Filter in der [!UICONTROL Marketing Cloud-Asset] -Auswahl, werden derzeit stillgelegt.

## ![Symbol](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Versionshinweise für [!DNL Experience Platform,] einschließlich [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL Angebote], [!UICONTROL Personen], [!UICONTROL Places], [!UICONTROL Mobile Services] und Sicherheitsbulletins.

### Verbesserungen an der Benutzeroberfläche

Updated: **May 15, 2020**

[!DNL Adobe Experience Platform] veröffentlicht Updates für die Domäne und Kopfzeilenleiste, um Ihr Erlebnis zu verbessern und die Verbindung mit anderen Experience Cloud-Anwendungen herzustellen. Zu den Aktualisierungen gehören:

* Einfacherer Wechsel zwischen Ihren Organisationen oder zu einer anderen Anwendung.
* Verbesserte Hilfe für Benutzer, einschließlich spezieller Artikel und kontextbezogener Dokumentation im Hilfemenü.
* Möglichkeit zur Rückmeldung über die Experience Platform und Dateiunterstützungskarten.

See [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) for more information.

### Kundenattribute - neue Dokumentation

Updated: **May 15, 2020**

* [Unterstützung von Kundenattributen für CCPA](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)
* [Unterstützung von Kundenattributen für GDPR](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/gdpr.html) (Allgemeine Datenschutzverordnung)

### Journey-Orchestrierung {#journey}

Mithilfe der Adobe Experience Platform können Sie individuelle Customer Journeys maßstabsgetreu über verschiedene Erlebniskanäle orchestrieren, indem Sie die Bedürfnisse jedes einzelnen Kunden in Echtzeit und unabhängig vom Zielort intelligent antizipieren.

* [Dokumentation](https://docs.adobe.com/content/help/de-DE/journeys/using/journey-orchestration-home.html)
* [Versionshinweise](https://docs.adobe.com/content/help/de-DE/journeys/using/release-notes/release-notes.html)
* [Anleitungsvideos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Zusätzliche Versionsinformationen zu Experience Platform

* [Experience Platform Launch – Versionshinweise](https://docs.adobe.com/content/help/de-DE/launch/using/intro/release-notes/current.html)
* [Experience Platform – Versionshinweise](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/de/security.html) (alle Adobe-Produkte)

## ![Symbol](/assets/analytics.png) [!DNL Analytics] {#analytics}

Updated **May 27, 2020**

* [Neue Funktionen in Customer Journey Analytics](#cust-journey)
* [Neue Funktionen in Adobe Analytics](#aa-features)
* [Neue Funktionen in Media Analytics](#media-aa) (**aktualisiert am 27. Mai 2020**)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices) (**aktualisiert am 26. Mai 2020**)
* [Fehlerbehebungen](#aa-fixes) in Adobe Analytics (**Aktualisiert 21. Mai 2020**)
* [AppMeasurement](#appm)
* [Neue Analytics-Tutorials](#tutorials-analytics)

### Neue Funktionen in Customer Journey Analytics {#cust-journey}

| Funktion | Beschreibung |
| -----------| ---------- |
| [!UICONTROL Customer Journey Analytics]: Globale Verfügbarkeit | Stellt [!UICONTROL Customer Journey Analytics] für Kunden in EMEA und APAC zur Verfügung. |
| [!UICONTROL Customer Journey Analytics]: Unterstützung für [!UICONTROL Adobe Experience Platform-Sandboxes] | Ermöglicht die Auswahl bestimmter [!UICONTROL Adobe Experience Platform-Sandboxes] zum Erstellen von CJA-Verbindungen. [Mehr Infos...](https://docs.adobe.com/content/help/de-DE/analytics-platform/using/cja-connections/create-connection.translate.html) |

### Neue Funktionen in Adobe Analytics {#aa-features}

<!-- Bulk Ingest: Enables you to ingest batches of Analytics data. Useful for server-side and offline data. Learn more...
First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| Funktion | Beschreibung |
| -----------| ---------- |
| Analytics-Unterstützung für [!UICONTROL Adobe Experience Platform Edge Network] | Ermöglicht die Verwendung eines einzelnen Tags zum Senden von Daten an mehrere Adobe-Lösungen, z. B. Adobe Analytics, Adobe Zielgruppe, Adobe Audience Manager, Adobe Experience Platform Data Lake, Unified Profil und Experience Cloud ID Service. [Mehr Infos...](https://docs.adobe.com/content/help/en/experience-platform/edge/solutions/analytics/analytics-overview.html) |
| [!UICONTROL Adobe Analytics-Dashboard] | [!UICONTROL Adobe Analytics-Dashboard] sind eine mobile App, mit der Benutzer jederzeit und überall auf Einblicke aus Adobe Analytics zugreifen können. Diese App ist für Führungskräfte gedacht, die unterwegs nach Schlüsselmetriken suchen. Es ermöglicht den Zugriff auf kuratierte, interaktive Scorecards und ist für iOS- und Android-Betriebssysteme verfügbar. [Mehr Infos...](https://docs.adobe.com/content/help/en/analytics/analyze/mobapp/home.html) |
| [!UICONTROL Workspace][!UICONTROL : Freiformtabellen können automatisch in einem leeren Projekt erstellt werden.] | Previously, you could not drop components directly into a blank project or blank panel; you had to add a [!UICONTROL Freeform Table] first. You can now drop components directly into a blank project or panel, and a [!UICONTROL Freeform Table] is automatically built for you in a recommended format. Darüber hinaus wurden Verbesserungen daran vorgenommen, wie gemischte Komponententypen (wie Dimensionen und Metriken) behandelt werden, wenn sie zusammen in eine leere Freiformtabelle abgelegt werden. |
| [!UICONTROL Adobe Analytics-Paket] zur Seite &quot; [!UICONTROL Funktionenzugriffsstufe] &quot;hinzugefügt | Sie können jetzt Ansichten darüber erstellen, für welches [!UICONTROL Adobe Analytics-Paket] (SKU) Ihre Firma unter **[!UICONTROL Admin]** > **[!UICONTROL Firma-Einstellungen]** > **[!UICONTROL Funktionenzugriffsstufe]** berechtigt ist. |
| Verbesserungen der Zugänglichkeit | Das Adobe Analytics-Team hat verschiedene Verbesserungen an der Barrierefreiheit in Analyse Workspace vorgenommen, darunter verbesserte Tastaturnavigation, Farbkontrast und Unterstützung für Bildschirmlesehilfen. |

#### New features in [!UICONTROL Media Analytics] {#media-aa}

Date added: **May 27, 2020**

**Player-Statusverfolgung:** [!UICONTROL Media Analytics] -Kunden können die Interaktion mit dem Viewer während der Wiedergabe mit einem Standardsatz von Lösungsvariablen für Vollbild, Untertitel, Stummschaltung, Bild-in-Bild und im Fokus erfassen. Sie haben auch die Flexibilität, benutzerdefinierte Player-Status zu erstellen. Player-Statusverfolgungsvariablen sind jetzt für den Berichte in [!UICONTROL Analyse Workspace]verfügbar. Diese Funktion erfordert eine der folgenden Funktionen:

* Media [!DNL JavaScript] SDK 3.0 oder höher
* Zur Verwendung mit dem [!DNL Adobe Experience Platform] (AEP-)SDK:
   * [!UICONTROL Media Analytics Extension] (für Web): [!UICONTROL Adobe Media Analytics] (3.x SDK) für Audio und Video v1.0 oder höher
   * [!UICONTROL Media Analytics Extension] (für Mobilgeräte): [!UICONTROL Adobe Media Analytics für Audio] und Video v2.0 oder höher
* [!UICONTROL Mediensammlung]

Inhaltslink verfügbar.

#### Fehlerbehebungen in Adobe Analytics {#aa-fixes}

* Adobe hat die Metrik &quot; [!UICONTROL Besuchszeit] &quot;geändert, um &quot;Nicht angegeben&quot;nie in die Berechnung aufzunehmen. Das bedeutet, dass wir unabhängig davon, ob in der Benutzeroberfläche angegeben wird, dass &quot;Nicht angegeben&quot;enthalten sein soll, eine besondere Ausnahme machen, um &quot;Nicht angegeben&quot;in der Berechnung der [!UICONTROL Besuchszeit] immer auszuschließen. Selbst wenn Sie einen Bericht konfiguriert haben, der die Metrik &quot; [!UICONTROL Besuchszeit] &quot;enthält, um &quot;Nicht angegeben&quot;einzuschließen, wird daher immer 0 Besuchszeit für den Zeileneintrag &quot;Nicht angegeben&quot;zurückgegeben. Beachten Sie, dass sich dadurch der historische Berichte in Reports &amp; Analysen sowie die Berichte-API v1.4 ändern kann. (AN-197958)
* Es wurde ein Problem behoben, bei dem die Metriken &quot;Instanz&quot;/&quot;Besuch&quot;und &quot;Besucher&quot;nicht im Nenner für die Metriken &quot; [!UICONTROL Besuchszeit] &quot;gezählt wurden.  Dies geschieht, wenn ein Treffer ohne Wert für die Dimension (z. B. [!UICONTROL Seitenname]) in derselben Sekunde gefolgt wird. (AN-211074)
* Fixed an issue that caused missing [!DNL Analytics] segment data in Audience Manager. (AN-206221)
* Es wurde ein Problem mit [!UICONTROL Data Sources] behoben, durch das bei der Verarbeitung die falschen Daten angezeigt wurden. (AN-213604)
* Es wurde ein Problem behoben, durch das Klassifizierungsdateien nicht ordnungsgemäß auf FTP hochgeladen wurden. (AN-214102)
* Es wurde ein Problem behoben, bei dem die API-Methode `Segments.Get` keine vollständige Antwort zurückgab. (AN-206210)
* Es wurde ein Problem behoben, bei dem Tabellenzeilenelemente beim [!DNL Workspace] PDF-Download in Sonderzeichen umgewandelt wurden. (AN-196153)
* Es wurde ein Problem behoben, bei dem der Aufruf der Adobe Analytics API 1.4 `visattrcustomeridcustomerattributes` nicht ordnungsgemäß funktionierte. (AN-186873)
* Es wurde ein Problem behoben, bei dem Daten in Berichten angezeigt wurden, die aber im [!UICONTROL Daten-Feed] fehlten. (AN-211923)
* Es wurde ein Fehler behoben, der dazu führte, dass Berechtigungen für [!UICONTROL Produktprofile] nicht kopiert werden konnten. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to [!UICONTROL Report Builder]. (AN-207750)
* Es wurde ein Problem behoben, bei dem [!UICONTROL AdWords]-Daten nicht in [!UICONTROL Advertising Analytics] angezeigt wurden. (AN-213249)
* Es wurde ein Problem behoben, bei dem Klassifizierungsdaten nicht in der Trend-Ansicht dargestellt wurden. (AN-212761)
* Es wurde ein Fehler behoben, der dazu führte, dass in [!UICONTROL Segment Manager] eine falsche Anzahl veröffentlichter Segmente ausgegeben wurde. (AN-213374)
* Es wurde ein Problem mit dem Trend **[!UICONTROL nach oben anzeigen unter ... behoben.]** im Editor für [!UICONTROL berechnete Metriken] - es funktionierte nicht, wenn Filter angewendet wurden. (AN-214223)
* Mehrere Probleme mit [!UICONTROL Classification] Import und Export wurden behoben. (AN-213488, AN-215309, AN-216345, AN-215307, AN-216671)
* Mehrere Probleme mit [!UICONTROL Classification Rule Builder]wurden behoben. (AN-213826, AN-213550, AN-213095)
* Es wurden Probleme bei der Verarbeitung von [!UICONTROL Datenquellen] behoben. (AN-218083, AN-213604, AN-214102, AN-215485, AN-215339, AN-212911, AN-217551, AN -217947, AN-219018, AN-214691, AN-218401)
* Es wurden FTP-Verbindungsprobleme behoben. (AN-115525)
* Korrektur mehrerer [!DNL Analytics] Datenfeeds  -Probleme. (AN-176769, AN-160480, AN-211923, AN-204286, AN-212977, AN-214528, AN-215080, AN -217784, AN-219093, AN-218817, AN-217798, AN-218267, AN-218382)
* Es wurden Probleme mit [!UICONTROL Data Warehouse] -Anforderungen behoben. (AN-181836)
* Es wurden Probleme in PDF-heruntergeladenen [!UICONTROL Workspace] -Projekten behoben, bei denen Werte in Sonderzeichen umgewandelt wurden. (AN-196153)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions in [!UICONTROL Admin Console]. (AN-211113)
* Korrektur des Problems, bei dem Zeitformate in berechneten Metriken für negative Werte beschädigt wurden. (AN-210900)
* Es wurde ein Fehler behoben, der verhinderte, dass Benutzer das [!UICONTROL Zuordnungsmodell] für statische Zeilenmetriken ändern konnten. (AN-207872)
* Es wurde ein Fehler behoben, der dazu führte, dass der [!UICONTROL Builder für terminierte Berichte] in einem Warteschlangenstatus feststeckte. (AN-215317)
* Korrektur des [!UICONTROL ExactTarget Data Connector]. (AN-210794)
* Korrektur von Latenzproblemen in der [!UICONTROL Bulk Ingestion API]. (AN-210165)
* Es wurde ein Problem behoben, bei dem Benutzer sich nicht mit einer Federated ID bei [!UICONTROL ReportBuilder] anmelden konnten. (AN-207750)
* Es wurde ein Problem in [!UICONTROL Advertising Analytics] behoben, das die Anzeige von [!DNL Google AdWords] Daten verhinderte. (AN-213249)
* Es wurde ein Fehler behoben, der verhinderte, dass [!UICONTROL Workspace] [!UICONTROL Project Viewed] -Ereignis in Protokollen angezeigt wurden. (AN-214134)
* Es wurde ein Problem behoben, das beim Ändern des Datumsbereichs in [!UICONTROL Workspace] und der Auswahl von **[!UICONTROL Anwenden auf alle Bereiche]** auftrat. Das Datum wurde in einigen Bereichen nicht geändert. (AN-214944)
* Es wurde ein Problem behoben, durch das Warnhinweise nicht erstellt oder bearbeitet werden konnten. (AN-215920)
* Es wurde ein Problem behoben, bei dem alle dynamischen Datumsbereiche in [!UICONTROL Workspace] aufgrund der sporadischen Umstellung auf einen Sonntag von einem Montag falsche Daten anzeigten. (AN-218835)

#### Weitere Fehlerbehebungen in Adobe Analytics

AN-101871, AN-115525; AN-123869; AN-152580; AN-160480; AN-178128; AN-186907; AN-199299; AN-201342; AN-201397; AN-204286; AN-204518; AN-206045; AN-206948; AN-208607; AN-209486; AN-210743; AN-211550; AN-211539; AN-211826; AN-211943; AN-212130; AN-212151; AN-212653; AN-212673; AN-212709; AN-212833; AN-212961; AN-212977; AN-213095; AN-213422; AN-213450; AN-213490; AN-213752; AN-213827; AN-214094; AN-214153; AN-214214; AN-214234; AN-214253;  AN-214255; AN-214343; AN-214355; AN-214401; AN-214427; AN-214528; AN-214642; AN-214691; AN-214772; AN-214793; AN-214924; AN-215017; AN-215080; AN-215212; AN-215312; AN-215377; AN-215402; AN-215545; AN-215905; AN-215963; AN-216447; AN-216676; AN-216880; AN-216999; AN-217245; AN-218450; AN-218899; AN-219487; AN-219677

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Whitelist zur Drittanbieter-Technologie | 12. März 2020 (Datum des In-Kraft-Tretens) | Adobe Analytics hat begonnen, Technologien von Drittanbietern für die Verwaltung von Funktionen und die Unterstützung von In-Produkt-Produkten zu nutzen. Die folgenden URLs sollten zu allen erforderlichen Netzwerk-Firewall-Whitelists hinzugefügt werden, um den vollen Funktionenzugriff sicherzustellen:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Verbesserte Redundanz für Analyse Workspace-Verfügbarkeit | 21. Mai 2020 | Um die Verfügbarkeit von Analyse Workspace sicherzustellen, fügen wir ein sekundäres CDN (Content Versand Network) hinzu, um die Redundanz zu verbessern. Die folgenden URLs sollten zu allen erforderlichen Netzwerk-Firewall-Whitelists hinzugefügt werden:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Änderung der Berechnung von [!UICONTROL Einstiegen/Ausstiegen] in [!UICONTROL Workspace] | 7. April 2020 | In [!UICONTROL Analysis Workspace] wurde im März 2020 die Weise geändert, wie der Wert _Keine_ in Bezug auf [!UICONTROL Einstiege/Ausstiege] verwendet wird. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before entry or exit. Angenommen, der erste Treffer eines Besuchs hat keinen Wert für eVars, der zweite Hit jedoch. In [!UICONTROL Reports &amp; Analytics] the first hit will show as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
| Ende der **[!UICONTROL Konversionsebenen]**-Einstellung | 3. März 2020 | Die nicht funktionierende Einstellung der [Konversionsebene](https://docs.adobe.com/content/help/de-DE/analytics/admin/admin-tools/general-acct-settings-admin.html) unter **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL Allgemeine Kontoeinstellungen]** wird am 12. März 2020 aus der Benutzeroberfläche entfernt. |
| Entfernung des **[!UICONTROL Dashboard-Archivs]** | 27. März 2020 | Ab Oktober 2020 ist die Einstellung **[!UICONTROL Archiv anzeigen]** unter **[!UICONTROL Dashboards verwalten]** in [!UICONTROL Reports &amp; Analytics] nicht mehr verfügbar. |
| Ende der Unterstützung für TLS 1.1 | 3. Oktober 2019 | Ab dem 31. März 2020 unterstützt Adobe Analytics TLS 1.1 nicht mehr. Diese Änderung ist Teil unserer laufenden Bemühungen, höchstmögliche Sicherheit von Kundendaten zu gewährleisten. |
| Neue Adobe Analytics-Domäne | 18. Dezember 2019 | Am 16. Januar 2020 begann Adobe Analytics mit der Umstellung auf eine neue Domäne – `https://experience.adobe.com/analytics.`<br>**Hinweis:** Diese Änderung gilt für alle Benutzer, die mit ihrer Adobe ID oder Enterprise ID auf Analytics zugreifen.<ul><li>Diese Änderung kann zu Problemen mit Cookies führen, wenn Analytics in Safari geladen wird. Wenn Sie in den Datenschutzvoreinstellungen von [!DNL Safari] die Option _Prevent cross-site tracking_ (Website-übergreifendes Tracking verhindern) deaktivieren, werden domänenübergreifende Cookies (und alle Site-übergreifenden Ereignisse) aktiviert, sodass Analytics in dieser neuen Adobe Experience Cloud-Domäne funktionieren kann. Sie können problemlos andere Browser verwenden, da dies nur [!DNL Safari]-Anwender betrifft.</li><li>Die Domänenänderung kann dazu führen, dass [!UICONTROL Activity Map] bei einigen Kunden [in bestimmten Fällen](https://docs.adobe.com/content/help/de-DE/analytics/analyze/activity-map/activity-map.html) nicht mehr funktioniert.</li></ul> |
| End of Life – veraltete Analytics-APIs | 9. Januar 2020 | Im November 2020 werden die folgenden Legacy-API-Dienste von Analytics eingestellt. Aktuelle Integrationen, die mit diesen Diensten erstellt wurden, funktionieren dann nicht mehr. <ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Wir haben [FAQ zu Legacy API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) bereitgestellt, die Ihnen bei der Beantwortung Ihrer Fragen helfen und Anleitungen zum weiteren Vorgehen geben sollen. API-Integrationen, die diese Dienste nutzen, können zu den [Analytics-REST-APIs 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) oder den [Analytics-APIs 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) migrieren. Ältere OAuth-Konten können zu einem [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-Integrationskonto migrieren, das für den Zugriff auf sowohl Analytics-APIs 1.4 als auch Analytics-APIs 2.0 verwendet werden kann. |
| FTP-Broker in San Jose endet für London und Singapur | Juli 2020 | Für Kunden in London und Singapur wird die Datenvermittlung zwischen den beiden Städten und dem Rechenzentrum in San Jose ([ftp.omniture.com](ftp://ftp.omniture.com/)) nicht mehr unterstützt.<br/><ul><li>Für London verwenden Sie [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Für Singapur verwenden Sie [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ende von Ad Hoc Analysis | 6. August 2018 | Adobe kündigte die Absicht an, Ad Hoc Analysis einzustellen. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist. Weiterführende Informationen finden Sie unter [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Siehe [Versionshinweise zu AppMeasurement für JavaScript](https://docs.adobe.com/content/help/de-DE/analytics/implementation/appmeasurement-updates.html). Version 2.20.0 wurde am 5. März 2020 veröffentlicht.

### Neue Analytics-Tutorials {#tutorials-analytics}

| Inhalt | Beschreibung |
| -----------| ---------- |
| [Schulungslehrvorlage im Arbeitsbereich für Analysen](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | Das Schulungslehrgang zum [!UICONTROL Arbeitsbereich] für Analysen führt Sie durch die gängige Terminologie und die Schritte zum Erstellen Ihres ersten Projekts in [!UICONTROL Workspace]. |
| [Hinzufügen von Vergleichen mit vorherigen Monaten und Jahren zu Trends](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | Erfahren Sie, wie Sie benutzerspezifische Datumsbereiche anwenden, um monatliche und jährliche Trendvergleiche für Metriken in [!UICONTROL Analyse Workspace]zu erstellen. |
| [Dark Mode Extension for Analyse Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Aktivieren Sie die Chrome-Erweiterung für Dark Reader, um den Arbeitsbereich für Analysen dunkel zu machen. |
| [Farb-Pipettenerweiterung zum Definieren benutzerdefinierter Paletten](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | Erfahren Sie, wie Sie mit der ColorPick EyeDropper Chrome-Erweiterung die Hex-Werte, die Sie für eine benutzerdefinierte Farbpalette in Ihren [!UICONTROL Workspace] -Projekten benötigen, einfach finden. |

#### Analytics-Hilferessourcen

* [Adobe Analytics-Übungen](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics-Produktdokumentation](https://docs.adobe.com/content/help/de-DE/analytics/landing/home.html)

## ![Symbol](/assets/audience-manager.png) Audience Manager {#aam}

Neue Funktionen, Fehlerbehebungen, Dokumentation und Lernprogramme in Audience Manager.

### Aktualisierungen der Benutzeroberfläche

Audience Manager veröffentlicht Updates für die Domäne und Kopfzeilenleiste, um Ihr Erlebnis zu verbessern und mit anderen Experience Cloud-Anwendungen zu vereinen.

* Einfacherer Wechsel zwischen Ihren Organisationen oder zu einer anderen Anwendung.
* Verbesserte Hilfe für Benutzer, einschließlich Artikel und kontextbezogene Videos im Hilfemenü.
* Möglichkeit zur Rückmeldung über die Experience Platform und Dateiunterstützungskarten.
* Ein neues einfacheres URL-Muster. Aktualisieren Sie Ihre Lesezeichen auf die neue URL: `experience.adobe.com/audience-manager`.

Diese Updates stehen nur Benutzern zur Verfügung, die sich mit der Adobe ID anmelden. Informationen zum Wechsel zu einer Adobe ID-Anmeldung finden Sie unter [Verwalten von Experience Cloud-Benutzern und -Produkten](https://docs.adobe.com/content/help/de-DE/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Neue Funktionen und Fehlerbehebungen in Adobe Audience Manager verfügbar

| Funktion | Beschreibung |
| -----------| ---------- |  
| [Bulk Management Tools (BAAAM)](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | Wir haben ein neues Arbeitsblatt für Massen-Management-Tools hochgeladen, das Folgendes beinhaltet: <br><br><ul><li>Ermöglicht die Liste der Unterordner in Ihrer Eigenschaftenhierarchie (AAM-51528)</li><li>Ruft Metriken ab, wenn Sie nach Eigenschaften für CRM-IDs (geräteübergreifende IDs) (AAM-52135) gefragt werden</li><li>Behebung eines Sprachkodierungsfehlers für koreanische Zeichen (AAM-AAM-54006)</li></ul> |

**Fehlerbehebungen**

* Es wurde ein Problem behoben, bei dem Trendberichte für Ordner mit einer großen Anzahl von Eigenschaften ausliefen. (AAM-54457)
* Es wurde ein Problem behoben, bei dem Kunden den [!UICONTROL Ausdruck-Builder] im Arbeitsablauf zum Erstellen/Bearbeiten von Eigenschaften nicht sehen konnten. (AAM-54255)
* Es wurde ein Problem behoben, bei dem Fehlermeldungen in der Benutzeroberfläche nur für kurze Zeit angezeigt wurden und verschwanden, bevor Kunden die Möglichkeit hatten, sie zu lesen. Dies trat beispielsweise beim Versuch auf, ein Segment zu löschen, das einem Ziel zugeordnet wurde. (AAM-54031)
* Es wurde ein Problem behoben, bei dem Kunden, die den [!UICONTROL Audience Marketplace] nicht mehr verwenden, monatliche E-Mails zur Rechnungsstellung erhielten. (AAM-54602)
* Es wurde ein Problem behoben, bei dem Kunden, die von anderen Stellen in der Benutzeroberfläche auf bestimmte Eigenschaften klickten, fehlerhafte Links anstelle der Eigenschaften sahen. (AAM-54768)
* Es wurde ein Problem behoben, durch das beim Bearbeiten des Ausdrucks Eigenschaften durch Drücken der EINGABETASTE die Seite aktualisiert und der Ausdruck der Eigenschaft verloren ging. (AAM-54210)
* Mehrere Verbesserungen hinsichtlich der Barrierefreiheit auf der gesamten Benutzeroberfläche. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550, AAM-54660).

### Neue Audience Manager-Lernprogramme {#tutorials-aam}

| Inhalt | Beschreibung |
| -----------| ---------- |  
| [Grundlegende Begriffe und Konzepte in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | In diesem Video werden einige der grundlegenden Begriffe und Konzepte behandelt, die Sie in Audience Manager verwenden, darunter Signale, Eigenschaften, Segmente usw. |
| [Datenfluss in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | In diesem Video erfahren Sie mehr über Adobe Audience Manager, indem Sie den Datenfluss in die, durch und aus der Anwendung beschreiben. |
| [Audience Manager - Übersicht über ein DMP](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | Machen Sie sich mit den wichtigsten Herausforderungen bei der Personalisierung von Kanälen vertraut und erfahren Sie, wie Adobe Audience Manager die Customer Journey optimiert. Erfahren Sie außerdem, welche Datentypen in Audience Manager integriert werden können, und identifizieren Sie die Ad-Tech-Ökosystempartner, die in Audience Manager integriert sind. |
| [Anwendungsfälle von Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | In diesem Video identifizieren wir vier gängige Anwendungsfälle von Audience Manager und beschreiben die damit verbundenen Best Practices. |
| [Geräteübergreifende Metriken im Audiencen-Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | In diesem Video besprechen wir den Unterschied zwischen Profilen und geräteübergreifenden Profilen und zeigen, wo die Zahlen in der Benutzeroberfläche mit den verschiedenen Profilen übereinstimmen. |
| [Prognostische Audiencen in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | In diesem Video besprechen wir, was die Predictive Audiencen von Audience Manager sind, erläutern Einzelheiten zu ihrer Funktionsweise und zeigen Anwendungsfälle auf. |
| [Prognostische Audiencen konfigurieren und in Audience Manager Bericht erstatten](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | In diesem Video gehen wir durch die Konfiguration von Predictive Audiencen in der Audience Manager-Oberfläche. Es werden auch die Berichte angezeigt, die die Ergebnisse des Modells anzeigen. |

## ![Symbol](/assets/aem.png) Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktaktualisierungen

* **AEM als Cloud-Dienst**

   * Verbesserungen und Fehlerbehebungen bei der Asset-Verarbeitung. Das Dialogfeld &quot;Asset-Wiederaufarbeitung&quot;bietet mehr Kontrolle, ermöglicht die Auswahl eines bestimmten Profils und stellt fest, ob der Arbeitsablauf für die Nachbearbeitung ausgelöst werden soll.
   * Leistungsverbesserungen bei der Erfassung dynamischer Medienelemente.

### Selbsthilfe

* **Automatisierter Forms-Konvertierungsdienst - Version AFC-2020.03.1**

   Eine neue Option ist verfügbar, wenn Sie den neuesten Connector installieren:

   **[!UICONTROL Logische Abschnitte]** automatisch erkennen: Sie können die Option &quot;logische Abschnitte  automatisch erkennen&quot;verwenden, um Bedienfelder auf Seitenebene (auf Seitenzahlen basierende Bedienfelder) abzulegen und nur logische Bedienfelder zu erstellen. Außerdem werden die Felder, die keinem Abschnitt mit vorhergehenden logischen Abschnitten und Feldern eines logischen Abschnitts angehören, der sich über zwei nebeneinander liegende Seiten verteilt, in einen einzigen logischen Abschnitt zusammengefasst. Wenn sich beispielsweise einige Felder eines logischen Abschnitts am Ende der ersten Seite und einige im Beginn der zweiten Seite befinden, werden alle diese Felder in einen einzigen logischen Abschnitt unterteilt.

* **Nicht unterstützte Bildformate in dynamischen Medien**

   Informationen zu den Untertypen von Rasterbilddateiformaten, die in [!UICONTROL dynamischen Medien]nicht unterstützt werden.

   Siehe [Nicht unterstützte Rasterbildformate in dynamischen Medien](https://docs.adobe.com/content/help/en/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media).

* **Inhaltsfragmente**

   Informationen zur Unterstützung von [Inhaltsfragmenten in der AEM Assets-HTTP-API](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html)sowie zum [Anpassen und Erweitern von Inhaltsfragmenten](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)und zu [Inhaltsfragmenten Konfigurieren von Komponenten für die Wiedergabe](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

* **AEM Experience League-Community**

   Verbindung mit der [AEM Experience League-Community](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community): Stellen Sie Fragen an andere Lernende und AEM-Experten, durchsuchen Sie Threads und teilen Sie Ihre Tipps und Erfahrungen mit!

* **AEM-Newsletter**

   Der AEM-Newsletter von [!UICONTROL Experience League] hilft Ihnen, sich mit AEM auf den neuesten Stand zu bringen, damit Sie sofort Beginn die Wertschöpfung realisieren können. Der aktuelle Newsletter:

   * [Volume 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): Experience Manager ist jetzt als Cloud-Dienst verfügbar.
   * [Abonnieren](https://adobeeventsonline.com/AEM/2017/NL/Optin/) Sie den Experience Insider-Newsletter.
   * Ansicht Newsletter-Archive im Bereich [AEM-Ressourcen](https://helpx.adobe.com/de/support/experience-manager/6-5.html) auf der Seite &quot;Training &amp; Support&quot;von Adobe Experience Manager 6.5.

### Neue Experience Manager-Tutorials

| Inhalt | Beschreibung |
| -----------| ---------- |  
| [Lokale AEM-Laufzeit einrichten](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) can be run locally using the [!UICONTROL AEM as a Cloud Service] SDK&#39;s [!UICONTROL Quickstart Jar]. This allows developers to deploy to, and test custom code, configuration, and content prior to committing it to source control, and deploying it to a [!UICONTROL AEM as a Cloud Service] environment. |
| [Erste Schritte mit AEM Assets](https://video.tv.adobe.com/v/33624?captions=ger) | Ein Einführungsvideo zu den ersten Schritten mit AEM Assets für Geschäftsbenutzer. |
| [Schema des Metadatenordners](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | Mit den Metadaten-Ordnern können Schema Metadaten verwalten und überprüfen, die mit Asset-Ordnern selbst verknüpft sind, und nicht direkt auf Assets. |
| [Tagging](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | Tags sind ein integrales Werkzeug zur Verwaltung von Assets in der Ordnerhierarchie von Assets. Die Einrichtung einer Tagging-Taxonomie ist entscheidend, damit Benutzer Assets in AEM finden und organisieren können. |
| [Metadatenprofile](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | Metadaten-Profil ermöglichen die automatische Anwendung von Standardmetadaten auf Assets in Asset-Ordnern. Dadurch wird die Belastung der AEM-Benutzer durch das Metadatenmanagement verringert und die Konsistenz der Metadaten erhöht. |
| [Metadatenschemata](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | Metadaten-Schema definieren die Schnittstelle, über die Asset-Metadaten in AEM verfügbar gemacht werden. In diesem Video wird die Kombination von Ansätzen zum Anwenden von Assets untersucht. |

### Zusätzliche Ressourcen

* [Versionshinweise zu AEM als Cloud-Dienst](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [Dokumentation zu AEM as a Cloud Service](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-5.html)
* [AEM 6.4 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-4.html)
* [AEM 6.3 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-3.html)
* [AEM 6.2 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-2.html)
* [Cloud Manager-Benutzerhandbuch](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Versionshinweise zu AEM Cloud Manager](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Ältere Versionen der AEM-Dokumentation](https://helpx.adobe.com/de/experience-manager/aem-previous-versions.html)
* [Startseite der Hilfe zu Dynamic Media Classic](https://docs.adobe.com/content/help/de-DE/dynamic-media-classic/using/home.html)
* [Versionshinweise zu Dynamic Media](https://docs.adobe.com/content/help/de-DE/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Livefyre-Versionshinweise](https://docs.adobe.com/content/help/de-DE/livefyre/using/release-notes/c-rn.html)

## ![Symbol](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Campaign Standard

* [Adobe Campaign Standard Version 20.3](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Kampagne-Systemsteuerung

| Funktion | Beschreibung |
| -----------| ---------- |  
| GPG-Schlüsselverwaltung | Installieren und/oder Generieren von GPG-Schlüsseln in einer Marketing-Instanz, um von Campaign gesendete Daten zu verschlüsseln und eingehende Daten zu entschlüsseln. |
| Zertifikatverwaltung für CNAME-Subdomains | Das Control Panel ermöglicht es Ihnen jetzt, die SSL-Zertifikate Ihrer Subdomains zu erneuern, die mit der CNAME-Methode zugewiesen wurden. |

### Neue Kampagnenübungen

* Neue Tutorials für Campaign Standard

| Inhalt | Beschreibung |
| -----------| ---------- |  
| [Systemsteuerung - Google TXT-Datensatzverwaltung](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Erfahren Sie, wie Sie Google TXT-Site-Überprüfungsdatensätze zu allen Subdomänen hinzufügen, die zum Senden von E-Mails an GMAIL-Adressen mit der Kampagne Control Panel verwendet werden. |
| [Konfigurieren und Ausführen eines Workflows mit der Aktivität &quot;Externe API&quot;](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Erfahren Sie, wie Sie einen externen REST-API-Endpunkt mit der Aktivität &quot;External API&quot;aufrufen. |
| [Erste Schritte mit Push-Benachrichtigungen für Android-Tutorial](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | In diesem Lernprogramm werden die Schritte erläutert, die zum Einrichten von Push-Benachrichtigungen mit Campaign Standard und der Android-App erforderlich sind. |

* Neue Kampagnen-Classic-Tutorials

| Inhalt | Beschreibung |
| -----------| ---------- |  
| [Großes Data Management auf Schneeflocke](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Erfahren Sie, wie Sie den Snowflake-Connector in Adobe Campaign Classic nutzen können. |
| [Systemsteuerung - Google TXT-Datensatzverwaltung](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Erfahren Sie, wie Sie Google TXT-Site-Überprüfungsdatensätze zu allen Subdomänen hinzufügen, die zum Senden von E-Mails an GMAIL-Adressen mit der Kampagne Control Panel verwendet werden. |

### Kampagne-Hilferessourcen

* Adobe Campaign Standard: [Hilfe-Center](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/campaign-standard-home.html) - [Versionshinweise](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-notes.html) - [Anleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Versionsplanung](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.html) - [Neueste Dokumentationsaktualisierungen](https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Hilfe-Center](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/campaign-classic-home.html) - [Versionshinweise](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/release-notes/latest-release.html) - [Anleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)- [Neueste Aktualisierungen der Dokumentation](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/documentation-updates.html)
* Control Panel von Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/de-DE/control-panel/using/control-panel-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/control-panel/using/release-notes.html)

## ![Symbol](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Neue Funktionen in Advertising Cloud DSP](#adcloud-dsp)
* [Neue Funktionen in der Advertising Cloud-Suche](#adcloud-search)

### Neue Funktionen in Advertising Cloud DSP {#adcloud-dsp}

| Funktion | Beschreibung |
| -----------| ---------- |
| [!UICONTROL Kampagnen Classic] und [!UICONTROL Kampagnen Beta] | Die IAS-Messungseinstellungen für Betrug und Markensicherheit, die Sie optional für jede Kampagne konfigurieren können, enthalten nun Optionen zur Messung des VAST- und VPAID-Bestands. |
| [!UICONTROL Kampagnen Beta] | Datenvisualisierungen und Seitenladezeiten wurden verbessert. |
|  | Auf allen Seiten können Sie jetzt Excel-Berichte herunterladen, die auf den aktuellen Filtern und Ansichten basieren. |
|  | (Version vom 22. Mai) Zu den neuen Metriken zählen &quot;Allzeitmetriken&quot;, &quot;Aktuelles Intervall&quot;, &quot;Datumsspezifische OTS&quot;. |
| [!UICONTROL Blacklists] | Das Prognosesystem verwendet nun automatisch die schwarze Liste auf Advertiser- oder Kontoebene. Benutzer müssen die schwarze Liste nicht mehr in die Platzierungseinstellungen einfügen. |
| [!UICONTROL Lagerbestandsgeschäfte] | (Geschlossene Betaversion) Mit einem neuen vereinfachten Formular können Sie schnell und einfach angebotsseitige Plattformgeschäfte (SSPs) einrichten, bearbeiten und beheben, die nicht im Posteingang &quot;Deal ID&quot;verfügbar sind. |
|  | Wenn Sie ein Paket mit programmgesteuerten, garantierten Deals im Deal-ID-Posteingang akzeptieren, werden Sie jetzt darauf hingewiesen, dass Sie für jede der Deal-IDs eine Standardplatzierung erstellen müssen. |

### Neue Funktionen in der [!UICONTROL Advertising Cloud-Suche] {#adcloud-search}

| Funktion | Beschreibung |
| -----------| ---------- |
| [!UICONTROL Kampagnen] | (Google Ads-Konten; Beta-Dienst) Ab Ende Mai kann die Advertising Cloud Search Daten für Ihre Google Gmail-Display-Kampagnen und Ihre Google Smart Shopping-Kampagnen mit Google-Konversionen für die Verfolgung und den Berichte synchronisieren. Der Dienst ermöglicht Ihnen auch, die Einstellungen für die Kampagne und die Anzeigengruppen für Ihre bestehenden Kampagnen in den Ansichten &quot;Kampagnen&quot;und &quot;Anzeigengruppen&quot;zu bearbeiten. Der Dienst ist optional. Sobald der Service allgemein verfügbar ist, wird eine zusätzliche Gebühr erhoben.<br>Weitere Informationen zum Dienst, einschließlich des Beta-Programms und des zukünftigen Anwendungsbereichs, erhalten Sie von Ihrem Adobe-Kundenbetreuer. |

## ![Symbol](/assets/magento.png) [!DNL Magento] {#magento}

Magento-Versionshinweise finden Sie unter:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Symbol](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] ist eine Komplettanwendung für das Lead-Management. B2B-Marketer können damit Kundenerlebnisse transformieren, indem sie in allen Phasen komplexer Customer Journeys Interaktionen ermöglichen.

### Aktualisierungen von Core Marketo Engage

Aktuelle Versionsinformationen finden Sie in den [!DNL Marketo] Versionshinweisen [](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) .

### Bevorstehende Funktionen

Die folgenden Funktionen werden im Laufe dieses Quartals veröffentlicht:

| Funktion | Beschreibung |
|------|---------|
| [!DNL Bizible] | <ul><li>Neue kontobasierte Segmentierung</li><li>Speichern von Dashboard-spezifischen Filtern</li><li>Export von Bizible Dashboards als PDF</li></ul> |
| Sales Connect | Aktualisierungen/Verbesserungen für Compose Window und Command Center |

### Ankündigungen

**Marketo Engage Success Center:** Start im Februar 2020. Das Success Center ist ein produktinternes Hilfesystem, mit dem Sie u. a. Produktdokumente und die Community durchsuchen, Anleitungen aufrufen und auf Adoptionsinhalte zugreifen können. Hinweis: Diese Funktion wird als Betaversion in ANZ gestartet und später in diesem Quartal in Nordamerika eingeführt.

### Veraltete und entfernte Funktionen

* **Asset-API-Parameter „_method“:** Ab September 2020 wird `_method` nicht mehr vom Asset-API-Endpunkten akzeptiert, um Abfrageparameter zu einem POST-Textkörper weiterzuleiten und URI-Längenbeschränkungen zu umgehen.
* **Einstellung der Unterstützung für Internet Explorer:** Ab der Juli-Version vom 31. Juli 2020 wird die Benutzeroberfläche von Marketo Engage in Internet Explorer nicht mehr unterstützt.

Eine Sammlung historischer Versionshinweisen finden Sie unter [Marketo-Versionshinweise](https://docs.marketo.com/x/CgA6Ag).
