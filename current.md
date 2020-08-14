---
title: Adobe Experience Cloud – Versionshinweise
description: Adobe Experience Cloud – Versionshinweise
doc-type: release notes
last-update: August 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 1fc011a1dbdc71052547679e69ac4f853f7fa4c2
workflow-type: tm+mt
source-wordcount: '6445'
ht-degree: 41%

---


# Adobe Experience Cloud Versionshinweise - August 2020

![Banner](/assets/experience-cloud-banner-3.png)

Auf dieser Seite sind neue Funktionen, Fehlerbehebungen und wichtige Hinweise in [!DNL Adobe Experience Cloud] beschrieben. Außerdem werden neue Dokumentationen, Schulungen und Videoschulungen vorgestellt, die Ihnen helfen, Experience Cloud optimal zu nutzen.

>[!NOTE]
>
>Abonnieren Sie das [Prioritätsprodukt-Update von Adobe](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bevorstehende Versionen benachrichtigt zu werden.

**Releasedatum: 13. August 2020**

Die Veröffentlichungsdaten einzelner Produkte können variieren. Suchen Sie regelmäßig nach Updates.

Neueste Aktualisierung: **13. August 2020**

* [Systemstatus von Adobe](#status)
* [Experience Cloud-Benutzeroberfläche ](#ecloud)
* [Experience Platform](#platform)
* [Journey-Orchestrierung](#journey-orch)
* [Analytics](#analytics) (Aktualisiert 13. August 2020) und [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Kampagne](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/de-DE/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://docs.adobe.com/content/help/de-DE/primetime/release-notes/home.translate.html)

Benötigen Sie Hilfe? Besuchen Sie [Adobe Experience League](https://experienceleague.adobe.com/#home), um Produkt- und technische Dokumentation, von Adobe kuratierte Kurse, Videoschulungen, schnelle Antworten, Community-Einblicke und von Schulungsleitern geführte Kurse zu erhalten.

## ![Symbol](/assets/adobe.png) Systemstatus von Adobe {#status}

[!UICONTROL Der Adobe-Systemstatus] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe Cloud-Produkten und -Diensten. Weitere Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/).

Aktuelle Versionsinformationen finden Sie unter 21. [Mai 2020](c-legacy-releases/2020/05212020.md#status) .

## ![Symbol](/assets/ec_appicon_24.png) Experience Cloud-Benutzeroberfläche {#ecloud}

Aktuelle Versionsinformationen zur aktualisierten Benutzeroberfläche und zur einheitlichen Produktdomäne finden Sie in den [vorherigen Versionshinweisen](c-legacy-releases/2020/07162020.md#ecloud) vom Juli.

## ![Symbol](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Versionshinweise für [!DNL Experience Platform] und Anwendungsdienste, einschließlich [!DNL Experience Platform Launch,] [!UICONTROL Angeboten], [!UICONTROL Personen], [!UICONTROL Places], [!UICONTROL Mobile Services] und Sicherheitsbulletins.

Latest release date: **July 15, 2020**

Aktuelle Informationen zu Experience Platform finden Sie in den Versionshinweisen zu [Experience Platform](https://docs.adobe.com/content/help/de-DE/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md).

## ![Symbol](/assets/experience_platform_appicon_24.png) Customer Journey Orchestration {#journey-orch}

Mithilfe der Adobe Experience Platform können Sie individuelle Customer Journeys maßstabsgetreu über verschiedene Erlebniskanäle orchestrieren, indem Sie die Bedürfnisse jedes einzelnen Kunden in Echtzeit und unabhängig vom Zielort intelligent antizipieren.

### Neue Campaign-Kurse und -Tutorials

Nachfolgend sind die im vergangenen Monat neu veröffentlichten Videos, Tutorials und Kurse aufgeführt.

| Veröffentlicht | Name | Typ | Beschreibung |
| ----------- | ---------- | ---------- |---------- |  
| 10. Juli 2020 | [Berichte-Reise-Ereignisse nach Adobe Experience Platform](https://docs.adobe.com/content/help/en/journey-orchestration-learn/tutorials/reporting-step-events-to-adobe-experience-platform.html) | Tutorial | Erfahren Sie, welche Ereignis für Reiseschritte und welche Datenschritte automatisch bei der Experience Platform erstellt werden und wie Sie diese untersuchen. |

### Zusätzliche Ressourcen für Journey Orchestration

[Dokumentation](https://docs.adobe.com/content/help/de-DE/journeys/using/journey-orchestration-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/journeys/using/release-notes/release-notes.html) – [Videoanleitungen](https://docs.adobe.com/content/help/de-DE/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Symbol](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

* [Neue Funktionen in Adobe Analytics](#aa-features)
* [Neue Funktionen in Customer Journey Analytics](#cust-journey)
* [Neue Funktionen in Media Analytics](#media-aa)
* [Fehlerbehebungen in Adobe Analytics](#aa-fixes)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [AppMeasurement](#appm)

### Neue Funktionen in Adobe Analytics {#aa-features}

(Aktualisiert 13. August 2020)

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/de-DE/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| ----------- | ---------- | ------- |
| [!UICONTROL Geräteübergreifende Analyse]: Verfügbarkeit in EMEA und APAC | 31. August 2020 | [Geräteübergreifende Analysen](https://docs.adobe.com/content/help/en/analytics/components/cda/overview.html) und private Diagramme stehen Kunden in EMEA und APAC zur Verfügung. |
| Verbesserung der feldbasierten Suche in [!UICONTROL geräteübergreifender Analyse] (verfügbar in Amerika und EMEA) | 31. August 2020 | Diese vereinfachte Implementierung für neue [!UICONTROL geräteübergreifende Analytics] -Kunden bietet Ihnen die Möglichkeit, die Suche auf der Grundlage einer Benutzer-ID durchzuführen, die in einem Analytics-Feld (prop oder eVar) gespeichert ist, anstatt das Gerätediagramm (co-op oder private) zu verwenden. Durch die Verbesserung wird die Anforderung der ECID-Implementierung aufgehoben und die Anforderung, die ID-Synchronisierung für CDA-Zwecke zu implementieren, entfällt. (Die ECID- und ID-Synchronisierung sind für bestimmte andere Funktionen weiterhin erforderlich.) |
| (Frühzeitige Mitteilung) Arbeitsbereich: 50.000 Artikel für eine einzelne Dimension herunterladen | 17. September 2020 | Sie können 50.000 Elemente für eine Dimension in einer Freiformtabelle herunterladen, wobei Segmente und Filter angewendet werden. Auf diese Weise können Sie auf mehr als 400 Datenzeilen außerhalb von Analysis Workspace zugreifen. |

### Neue Funktionen in Customer Journey Analytics {#cust-journey}

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/de-DE/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| ----------- | ---------- | ----- |
| [!UICONTROL Identity Map-Option für Personen-IDs] | 26. Juni 2020 | [!UICONTROL Identity Map] is a map data structure that allows you to upload key-value pairs as part of creating a connection in [!UICONTROL Customer Journey Analytics]. Die Schlüssel sind Identity-Namespaces und der Wert ist eine Struktur, die den Identitätswert enthält. [Mehr Infos...](https://docs.adobe.com/content/help/de-DE/analytics-platform/using/cja-connections/create-connection.html#use-identity-map-as-a-person-id) |

### Neue Funktionen in [!UICONTROL Media Analytics] {#media-aa}

Versionsdatum: **16. Juli 2020**

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/de-DE/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| ----------- | ---------- | ---------- |
| [Unterstützte Geräte und Plattformen](https://docs.adobe.com/content/help/de-DE/media-analytics/using/supported-devices.html) | 18. Juni 2020 | The [!UICONTROL Media Launch Extension] with AEP SDK now supports the following OTT devices:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Player-Status-Tracking](https://docs.adobe.com/content/help/de-DE/media-analytics/using/player-state-tracking/player-state-overview.html) | 29. Mai 2020 | [!UICONTROL Media Analytics]-Kunden können die Interaktion mit dem Besucher während der Wiedergabe mit einem Standardsatz von Lösungsvariablen für Vollbild, verdeckte Untertitel, Stummschaltung, Bild-in-Bild und im Fokus erfassen. Sie haben auch die Möglichkeit, benutzerdefinierte Player-Status zu erstellen. Player-Status-Tracking-Variablen sind jetzt für Berichte in [!UICONTROL Analysis Workspace verfügbar]. Diese Funktion erfordert eine der folgenden Voraussetzungen: <ul><li>Media [!DNL JavaScript] SDK 3.0 oder höher</li><li>Zur Verwendung mit dem [!DNL Adobe Experience Platform] (AEP)-SDK:</li><li>[!UICONTROL Media Analytics-Erweiterung] (für Web): [!UICONTROL Adobe Media Analytics] (3.x SDK) für Audio und Video v1.0 oder höher</li><li>[!UICONTROL Media Analytics-Erweiterung] (für Smartphone und Tablet): [!UICONTROL Adobe Media Analytics für Audio] und Video v2.0 oder höher</li><li>[!UICONTROL Mediensammlung]</li></ul> |

### Fehlerbehebungen in Adobe Analytics {#aa-fixes}

* Es wurde ein Problem behoben, bei dem die Berichte-API keine aktuellen Metrikwerte zurückgab. (AN-225617)
* Es wurde ein Fehler behoben, der verhinderte, dass [!UICONTROL Classification-Regeln] Daten für [!UICONTROL Marketing-Kanal-Details]klassifizieren konnten. (AN-224832)
* Es wurde ein Fehler behoben, der beim Erstellen neuer Projekte in einer _Virtual Report Suite_ den Fehler &quot; [!UICONTROL Fehlende Komponenten]&quot;verursachte.(AN-226808)
* Es wurde ein Fehler behoben, der beim Kuratieren einer Virtual Report Suite den Fehler &quot; _Fehlende Komponenten_ &quot;verursachte. (AN-228257)
* Es wurde ein Fehler behoben, der die Erstellung neuer [!UICONTROL Reports &amp; Analysen] -Zielgruppen und Kalenderdaten verhinderte. (AN-224872, AN-224890, AN-224914, AN-226661)
* Es wurde ein Problem behoben, das zu fehlenden Aktivitäten im A4T-Bedienfeld in [!UICONTROL Workspace]führte. (AN-224606)
* Es wurde ein Problem mit Duplikat-Treffern in [!UICONTROL Data Feeds]behoben. (AN-226308)
* Es wurde ein Problem behoben, bei dem berechnete Metriken mit Beitragszuordnung keine korrekten Werte zurückgaben. (AN-224642, AN-225190)
* Es wurde ein Problem behoben, bei dem Segmentdaten, die freigegeben wurden, von mehr als drei Tagen in [!DNL Analytics] Anspruch genommen wurden, um in angezeigt zu werden [!DNL Audience Manager] [!DNL Audience Manager].(AN-226649)
* Es wurde ein Problem behoben, durch das der Link [!UICONTROL Weitere] Analysen in [!UICONTROL Intelligente Warnhinweise] -E-Mails nicht verwendet werden konnte. (AN-226823)
* Es wurde ein Fehler behoben, der dazu führte, dass keine Segmente in einer [!UICONTROL Virtual Report Suite]erstellt werden konnten. (AN-227039)
* Fixed an issue with not being able to edit intelligent alerts. (AN-227162)

#### Weitere Fehlerbehebungen in Adobe Analytics

AN-219351; AN-220960; AN-223788; AN-224630; AN-224948; AN-225618; AN-226261; AN-226828; AN-226845; AN-226937; AN-226961; AN-227070; AN-227079; AN-227521; AN-227610; AN-228203; AN-228451; AN-228466; AN-228538

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| ----------- | ---------- | ---------- |
| EOL von Adobe Data Connectors | 13. Juli 2020 | Adobe [!UICONTROL Data Connectors] are powered by legacy technology that is no longer viable or supported. Im [Adobe Exchange Partner-Programm](https://partners.adobe.com/exchangeprogram/experiencecloud) gibt es einen neuen Standard, der für alle Integrationen übernommen werden sollte, die weiterhin angeboten und unterstützt werden sollen. Das offizielle Ende des Lebenszyklus wurde noch nicht festgelegt, aber wir gehen davon aus, dass es in den nächsten 12 bis 18 Monaten (Mitte 2021 bis Ende 2021) sein wird. [Weitere Informationen...](https://docs.adobe.com/content/help/de-DE/analytics/import/dataconnectors/data-connectors-eol.html) |
| Report Suite-Zuordnung zu IMS-Organisation | Juli 2020 | Das Tool für die Zuordnung von Report Suites wird im November 2020 eingestellt. Über diese Funktion werden Integrationen wie die Veröffentlichung von Segmenten aus Advertising Analytics und Experience Cloud in Adobe Analytics ermöglicht. Zur Aktivierung dieser und anderer Services muss eine Report Suite einer IMS-Organisation zugeordnet werden. Neuere Report Suites werden bei ihrer Erstellung automatisch zugeordnet. Ältere Report Suites hingegen müssen einer IMS-Organisation manuell zugeordnet werden. See [Map report suites to an organization](https://docs.adobe.com/content/help/de-DE/core-services/interface/about-core-services/report-suite-mapping.html) in the Experience Cloud interface (Core Services) user guide to make sure all report suites belong to an IMS org. |
| Migration zu einer einheitlichen Produkt-Domain | Datum des Inkrafttretens: 28. Mai 2020 | Die Migration zu einer einheitlichen Produkt-Domain für Adobe Analytics, die im Januar 2020 begann, wurde am 28. Mai 2020 abgeschlossen. Adobe Analytics entfernt alle `omniture.com` Domain-Verweise aus seiner Architektur. Gleichzeitig muss `omniture.com` als Drittanbieter-Cookie auf die Zulassungsliste gesetzt werden. Wenn die Migration der vollständigen Architektur (bald) abgeschlossen ist, werden wir Sie in den Versionshinweisen darüber benachrichtigen. Dann ist dieser Schritt mit der Zulassungsliste nicht mehr erforderlich. [Hier](https://helpx.adobe.com/de/analytics/kb/adobe-ip-addresses.html) finden Sie eine vollständige Liste der empfohlenen IP-Adressen und Domänen, die Sie auf die Zulassungsliste setzen sollten.<br>Wenn Ihr Unternehmen Drittanbieter-Cookies blockiert, wenden Sie sich an die Kundenunterstützung, um wieder Zugriff auf Adobe Analytics zu erhalten. |
| Neue Standard-Landingpage von Adobe Analytics | Datum des Inkrafttretens: 18. Juni 2020 | Am 18. Juni 2020 ändert sich die standardmäßige Landingpage für Adobe Analytics von [!UICONTROL Reports] in [!UICONTROL Workspace]. Diese Änderung wird für alle Benutzer sichtbar sein, die zuvor keine benutzerdefinierte Landingpage festgelegt haben. |
| Zulassungsliste für Drittanbietertechnologie | 12. März 2020 (Datum des Inkrafttretens) | Adobe Analytics hat begonnen, Technologien von Drittanbietern für die Verwaltung des Funktions-Rollouts und die Unterstützung innerhalb von Produkten zu nutzen. Die folgenden URLs sollten zu allen erforderlichen Netzwerk-Firewall-Zulassungslisten hinzugefügt werden, um den Zugriff auf alle Funktionen sicherzustellen:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Die Redundanz für die [!UICONTROL Analysis Workspace]-Verfügbarkeit wurde verbessert | 21. Mai 2020 | Um die Verfügbarkeit von [!UICONTROL Analysis Workspace] sicherzustellen, fügen wir ein sekundäres CDN (Content Delivery Network) hinzu, das die Redundanz verbessert. Die folgenden URLs sollten allen erforderlichen Netzwerk-Firewall-Zulassungslisten hinzugefügt werden:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Änderung der Berechnung von [!UICONTROL Einstiegen/Ausstiegen] in [!UICONTROL Workspace] | 7. April 2020 | In [!UICONTROL Analysis Workspace] wurde im März 2020 die Weise geändert, wie der Wert _Keine_ in Bezug auf [!UICONTROL Einstiege/Ausstiege] verwendet wird. Da Sie jetzt _Keine_ in [!UICONTROL Analysis Workspace] aktivieren und deaktivieren können, wird _Keine_ jetzt erst nach einem Ein- oder Ausstieg angewendet, während dieser Wert früher (bei eVars) vor einem Ein- oder Ausstieg angewendet wurde. Angenommen, der erste Treffer eines Besuchs liefert keinen Wert für eVars, der zweite aber schon. In [!UICONTROL Reports &amp; Analytics] wird der erste Treffer als _Nicht angegeben_ für den Einstieg angezeigt, aber in [!UICONTROL Analysis Workspace] wird dieser Wert beim zweiten Treffer angezeigt. |
| Entfernung des **[!UICONTROL Dashboard-Archivs]** | 27. März 2020 | Ab Oktober 2020 ist die Einstellung **[!UICONTROL Archiv anzeigen]** unter **[!UICONTROL Dashboards verwalten]** in [!UICONTROL Reports &amp; Analytics] nicht mehr verfügbar. |
| EOL von Analytics Legacy APIs | 9. Januar 2020 | Im November 2020 werden die folgenden Legacy-API-Dienste von Analytics eingestellt. Aktuelle Integrationen, die mit diesen Diensten erstellt wurden, funktionieren dann nicht mehr. <ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Wir haben [FAQ zu Legacy API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) bereitgestellt, die Ihnen bei der Beantwortung Ihrer Fragen helfen und Anleitungen zum weiteren Vorgehen geben sollen. API-Integrationen, die diese Dienste nutzen, können zu den [Analytics-REST-APIs 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) oder den [Analytics-APIs 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) migrieren. Ältere OAuth-Konten können zu einem [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-Integrationskonto migrieren, das für den Zugriff auf sowohl Analytics-APIs 1.4 als auch Analytics-APIs 2.0 verwendet werden kann. |
| FTP-Broker in San Jose endet für London und Singapur | Juli 2020 | Für Kunden in London und Singapur wird die Datenvermittlung zwischen den beiden Städten und dem Rechenzentrum in San Jose ([ftp.omniture.com](ftp://ftp.omniture.com/)) nicht mehr unterstützt.<br/><ul><li>Für London verwenden Sie [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Für Singapur verwenden Sie [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ende von Ad Hoc Analysis | 6. August 2018 | Adobe kündigte die Absicht an, Ad Hoc Analysis einzustellen. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist. Weiterführende Informationen finden Sie unter [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### AppMeasurement

Die neuesten Aktualisierungen zu AppMeasurement-Versionen finden Sie in den Versionshinweisen zu [AppMeasurement für JavaScript](https://docs.adobe.com/content/help/de-DE/analytics/implementation/appmeasurement-updates.html).

#### Neue Analytics-Kurse und -Tutorials {#tutorials-analytics}

Neue Kurse, Tutorial-Videos und Artikel in Analytics und Customer Journey Analytics.

| Veröffentlicht | Name | Typ | Beschreibung |
| ----------- | ----------- | ---------- | ---------- |
| 30. Juli 2020 | [Report Suite-Zugriff in der Admin Console beschränken](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/administration/user-management/limit-report-suite-access-in-the-admin-console.html) | Tutorial | Erfahren Sie, wie Sie mit der [!UICONTROL Admin Console] sicherstellen können, dass Benutzer nur auf die Report Suite(s) zugreifen können, die für ihre Rolle erforderlich sind. |
| 24. Juli 2020 | [Hinzufügen eines Administrators zu Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/administration/user-management/adding-an-administrator-to-adobe-analytics.html) | Tutorial | Learn how to add a user as an Administrator in the Adobe [!UICONTROL Admin Console]. |
| 17. Juli 2020 | [Quick Insight-Bedienfeld in Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/quick-insights-panel-in-analysis-workspace.html) | Tutorial | Quick Insights bietet Nicht-Analytikern und neuen Benutzern von Analysis Workspace eine Möglichkeit, betriebliche Fragen schnell und einfach zu beantworten. |
| 17. Juli 2020 | [Analytics for Target (A4T) Panel in Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/target/analytics-for-target-a4t-panel-in-analysis-workspace.html) | Tutorial | The [!UICONTROL Analytics for Target] (A4T) panel lets you analyze your Adobe Target activities and experiences, with lift and confidence, in Analysis Workspace. |
| 6. Juli 2020 | [Create Advertising Cloud Dashboards with Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-advertising-cloud-dashboards-with-adobe-analytics.html?lang=en#tutorials) | Tutorial | Techniques for creating an Advertising Cloud dashboard for live campaign monitoring. |
| 6. Juli 2020 | [Benutzerspezifische Analytics-Metriken mit Advertising Cloud-Daten erstellen](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-custom-metrics-with-advertising-cloud-data.html?lang=en#tutorials) | Tutorial | Nützliche benutzerspezifische Metriken, die bei der Verwendung von Advertising Cloud-Daten in Adobe Analytics erstellt werden. |
| 6. Juli 2020 | [Erstellen von Analytics Site Journey-Profilen](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-site-journey-profiles.html?lang=en#tutorials) | Tutorial | Verwendung von Adobe Analytics zur Erstellung robuster Site-Retargeting-Pools für Advertising Cloud-Remarketing. |
| 6. Juli 2020 | [Erstellen von Analytics-Segmenten für Aktivierung und Berichte](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-segments-for-activation-and-reporting.html?lang=en#tutorials) | Tutorial | Segmentaufbau mit Advertising Cloud-Dimensionen für eine sauberere Berichte- und Analyse. |
| 6. Juli 2020 | [Create a Pre-launch Campaign Analysis with Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/reporting-with-advertising-cloud-marketing-channels.html?lang=en#tutorials) | Tutorial | How to use Adobe Analytics to set the foundation for launching an Advertising Cloud paid media campaign. |
| 6. Juli 2020 | [Project Sharing in Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/project-sharing-in-analysis-workspace.html?lang=en#tutorials) | Tutorial | Project sharing is one way to democratize data and insights from Analysis Workspace to users in your organization. Sie können Empfänger je nach Projekterfahrung - Bearbeiten, Duplikat und Ansicht - in eine der drei Rollen setzen. |
| 26. Juni 2020 | [Custom Look-back Windows in Attribution IQ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/attribution-iq/custom-lookback-windows-in-attribution-iq.html?lang=en#tutorials) | Tutorial | Custom look-back windows let you to expand the attribution window beyond the reporting range (up to a maximum of 90 days), and applies to each conversion in the reporting range. |
| 26. Juni 2020 | [Nur-Ansichten-Projekte in Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/view-only-projects-in-analysis-workspace.html?lang=en#tutorials) | Tutorial | Workspace projects can be shared to users as _Can view_ only. When a _View_ recipient opens the shared project, they receive a more restrictive project experience, with no left rail and limited interactions. |
| 26. Juni 2020 | [Algorithmisches Modell im Attribution IQ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/attribution-iq/algorithmic-model-in-attribution-iq.html?lang=en#tutorials) | Tutorial | Das [!UICONTROL algorithmische Zuordnungsmodell] in Analysis Workspace verwendet statistische Verfahren, um für die ausgewählte Metrik die optimale Zuordnung dynamisch zu bestimmen. |

#### Analytics-Hilferessourcen

* [Adobe Analytics-Tutorials](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics-Produktdokumentation](https://docs.adobe.com/content/help/de-DE/analytics/landing/home.html)

## ![Symbol](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Neue Funktionen, Fehlerbehebungen, Dokumentationen und Tutorials in Audience Manager.

Releasedatum: **13. August 2020**

### Neue Funktionen und Fehlerbehebungen in Adobe Audience Manager

* You can now use [People-Based Destinations](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-prerequisites.html) to target users via [!DNL Google Customer Match]. Before you can use [!UICONTROL People-Based Destinations] to send your first-party audience segments to a [!DNL Google Customer Match] destination, it is mandatory that [!DNL Google] adds you to their allow list. Check the [People-Based Destinations](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-prerequisites.html) documentation for details. (PLAT-53962)
* [Predictive Audiences](https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences.html) now supports the selection of a [!UICONTROL Profile Merge Rule] per model, during model creation. (AAM-55178)
* Zielzuordnungs-Beginn und Enddaten sind jetzt auf jeder Segmentseite sichtbar. (AAM-40056)
* Es wurde ein Problem behoben, bei dem der [!UICONTROL Gerätetyp] einer Eigenschaft beim Erstellen einer neuen Eigenschaft automatisch auf [!UICONTROL geräteübergreifend] eingestellt wurde. (AAM-55368)
* Es wurde ein Problem behoben, bei dem das [!UICONTROL Audience Marketplace] nicht geladen werden konnte. (AAM-55549)
* Sie können nun die Zuordnung von Segmenten zu [!DNL Google] Zielen aufheben, wenn der [!DNL Google UserList] Parameter nicht abgerufen werden kann. (AAM-42655)
* Es wurde ein Problem behoben, bei dem das Hinzufügen mehrerer Segmente zu einem Ziel nicht immer ordnungsgemäß funktionierte. (AAM-55651)
* Es wurde ein Problem behoben, bei dem Benutzern mit erhöhtem [!DNL Profile Merge Rules] Grenzwert die Schaltfläche [!UICONTROL Hinzufügen Neue Regel] nicht angezeigt wurde. (AAM-55700)
* Es wurde ein Problem behoben, bei dem der Titel &quot; [!UICONTROL 30-Tage-Überlappende Unique Users] &quot;in den [!UICONTROL Datenfeed-Berichtsmetriken]fehlte. (AAM-55801)
* Lebensdauermetriken werden jetzt aus der [!UICONTROL Ziel] -Ansicht ausgeschlossen, wenn das Ziel für den Export von [!DNL UUID]s konfiguriert ist. (AAM-54196)
* Es wurde ein Problem behoben, bei dem Benutzer keine [!DNL Tableau] Berichte Ansicht haben konnten. (AAM-55868)
* Es wurde ein Problem behoben, bei dem Benutzer beim Erstellen eines neuen [!UICONTROL Prognosemodells] eine Fehlermeldung erhielten. (AAM-55921)
* Mehrere Verbesserungen hinsichtlich der Barrierefreiheit auf der gesamten Benutzeroberfläche. (AAM-49062, AAM-49063, AAM-49365).

### Neue Audience Manager-Tutorials {#tutorials-aam}

| Veröffentlicht | Name | Typ | Beschreibung |
| ----------- | ----------- | ---------- | ---------- |
| 7. August 2020 | [Sparen Sie Geld und optimieren Sie das Kundenerlebnis, indem Sie Anzeigen an Konverter unterdrücken.](https://experienceleague.adobe.com/?recommended=AudienceManager-A-1-2020.1) | Tutorial | Lernen Sie in diesem Kurs alle Konzepte, die von Beginn zu Ende gehen müssen, mit dem Verwendungsfall, Geld zu sparen und das Kundenerlebnis zu optimieren, indem Sie bestehende Kampagnen aus Ihren Reichweitenzielen entfernen. Dazu gehören das Erstellen von Eigenschaften und Segmenten, das Hinzufügen der richtigen Profil-Zusammenführungsregeln, das Hinzufügen von Segmenten zu Zielen und sogar die Berechnung des ROI während der Verwendung dieses Anwendungsfalls. |
| 7. August 2020 | [Auswählen der Regel zum Zusammenführen des richtigen Profils](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/choosing-the-right-profile-merge-rule.html) | Tutorial | In diesem Video werden drei der häufigsten Anwendungsfälle für [!UICONTROL Profil Merge Rules]aufgezeigt und wie diese Ihnen bei Ihren Marketingbemühungen helfen können. |
| 5. August 2020 | [Erstellen einer Segmenttaxonomie](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-a-segment-taxonomy.html) | Tutorial | Wenn Sie ein Segment in Audience Manager erstellen, speichern Sie es in einer ordnerbasierten Struktur oder einer _Taxonomie_. Hier finden Sie einige Tipps zum Erstellen und Verwalten der Segmenttaxonomie. |
| 4. August 2020 | [API-Anmeldeinformationen in Adobe I/O abrufen](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/api/retrieve-api-credentials-in-adobe-io.html) | Tutorial | Anstatt sich an Adobe Consulting oder den Kundendienst zu wenden, um Anmeldeinformationen für die REST-API zu erhalten, können Sie einfach `Adobe.io` in einem Browser aufrufen und Ihre eigenen Anmeldeinformationen abrufen oder registrieren. |
| 31. Juli 2020 | [Verwenden von Neuigkeit und Häufigkeit in Segmenten](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-recency-and-frequency-in-segments.html) | Tutorial | Verwenden Sie [!UICONTROL Neuigkeit] und [!UICONTROL Häufigkeit] , um Segmentparameter anzugeben, wie oft ein Besucher sich innerhalb eines bestimmten Zeitraums für eine Eigenschaft qualifizieren muss. Optimale Lösung für die Affinität von Inhalten und für die Festlegung von Häufigkeitsangaben sowie für andere Anwendungsfälle. |
| 22. Juli 2020 | [Grundlagen zum Erstellen von Segmenten](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/the-basics-of-creating-segments.html) | Tutorial | Gehen Sie durch die Felder in der Benutzeroberfläche, um ein Segment in Audience Manager zu erstellen. |
| 22. Juli 2020 | [Praktische Segmentdefinition und -erstellung](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/practical-segment-definition-and-creation.html) | Tutorial | Dieses Video führt Sie durch den Prozess der Definition Ihrer Segmente und deren anschließende Unterteilung nach den Eigenschaften und Signalen, die Sie für ihre Erstellung benötigen. |
| 17. Juli 2020 | [Unterdrücken von Anzeigen zu Konvertern](https://video.tv.adobe.com/v/36658?captions=ger) | Tutorial | Sparen Sie Geld und optimieren Sie das Kundenerlebnis, indem Sie Anzeigen an Konverter unterdrücken. |
| 15. Juli 2020 | [Messung des ROI in einem Anwendungsfall zur Kundenunterdrückung](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/value-realization/measuring-roi-in-a-customer-suppression-use-case.html) | Tutorial | Erfahren Sie, wie Sie mit einer Reihe von Formeln die Kosteneinsparungen Ihrer Kampagne ermitteln können, indem Sie Anzeigen für bestehende Kunden unterdrücken. |
| 10. Juli 2020 | [Erstellen eines Segments zur Unterdrückung von Anzeigen für Kunden](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/building-a-segment-to-suppress-ads-to-customers.html) | Tutorial | In diesem Video werden Optionen zum Erstellen von Segmenten erläutert, um diejenigen auszuschließen, die bereits in den Kundenstatus konvertiert wurden. |

## ![Symbol](/assets/aem.png) Adobe Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### **Produktversionen**

* **AEM as a Cloud Service**

   Was ist neu auf AEM als Cloud Service? Zu den hervorgehobenen Highlights zählen:

   * AEM Commerce ist jetzt auf dem Cloud Service verfügbar. Siehe [Erste Schritte mit AEM Commerce als Cloud Service.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/commerce/getting-started.html)
   * Die Erweiterungen für Connectors für Adobe Target und Adobe Analytics umfassen Verbesserungen der Benutzeroberfläche, den klassischen UI-Austausch und die Integration von Adobe Launch. Siehe [Integration von Adobe Analytics](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/integrations/integrating-adobe-analytics.html) und [Integration von Adobe Target.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/integrations/integrating-adobe-target.html)
   * Asset Compute Service is a scalable and extensible service to process assets. Administrators can configure Experience Manager to invoke custom worker created using the Asset Compute Service. Developers can use the service to create specialized custom workers that cater to complex use cases. This web service can generate thumbnails for different file types, high-quality image renderings from Adobe file formats, encode videos (future), extract metadata, extract full text as precursor for indexing, and run an asset through all available Sensei services. Siehe [Verwenden von Asset-Mikrodiensten und Profilen zur Verarbeitung.](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/assets/manage/asset-microservices-configure-and-use.html)
   * [Der Asset Compute-Dienst](https://docs.adobe.com/content/help/en/asset-compute/using/home.html) steht zur Verfügung, um erweitert zu werden und eine benutzerdefinierte Anwendung zu erstellen. Es handelt sich um einen skalierbaren und erweiterbaren Dienst [!DNL Adobe Experience Cloud] zur Verarbeitung digitaler Assets. Sie können Bild-, Video-, Dokument- und andere Dateiformate in verschiedene Darstellungen umwandeln, einschließlich Miniaturansichten, extrahiertem Text und Metadaten, Archiven und mehr. Entwickler können benutzerdefinierte Anwendungen (auch als benutzerdefinierte Mitarbeiter bezeichnet) erstellen, um benutzerdefinierte Anwendungsfälle zu bearbeiten. Es wurde mit [Project Firefly](https://www.adobe.io/apis/experienceplatform/project-firefly/docs.html) gebaut und arbeitet in serverless [Adobe I/O Runtime](https://www.adobe.io/apis/experienceplatform/runtime.html).
   * Multiple improvements for Workflow models and Dynamic Media in AEM as a Cloud Service.
   * Release 2.11.0 of the [AEM Core Components](https://docs.adobe.com/content/help/de-DE/experience-manager-core-components/using/introduction.html) is now available as part of AEM Sites including the following:
      * Introduction of a new [PDF Viewer Component.](https://aemcomponents.dev/content/core-components-examples/library/page-authoring/pdf-viewer.html)
      * Accelerated Mobile Pages (AMP) support of Core Components. It helps to produce faster customer experiences by making the page transition instantaneously when entering the site from a Google mobile search result, which improves user engagement and SEO. See [AMP Support for the Core Components.](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/data-layer/overview.html)
      * Kompatibilität mit Version 1.0.2 der [Adobe Client Data Layer](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/data-layer/overview.html).
   * Multiple UI improvements in Cloud Manager.
   * Cloud Manager-Pipelines unterstützen jetzt benutzerspezifische Variablen und Geheimnisse. See [Pipeline Variables.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/getting-access/creating-aem-application-project.html#pipeline-variables)
   * [Logs can be forwarded to Splunk accounts](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/logging.html#splunk-logs), which lets organizations leverage their [!DNL Splunk] investment.
   * You can assign [a static, dedicated egress IP address](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/development-guidelines.html#dedicated-egress-ip-address) for outbound traffic programmed in Java code, which may be useful for some integrations.
   * [!UICONTROL Cloud Readiness Analyzer] v1.0.2 was released. See detailed [Release Notes](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-2020-7-0.html#cloud-readiness-analyzer) for more information. To get started with [!UICONTROL Cloud Readiness Analyzer], see [Using Cloud Readiness Analyzer](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/moving/cloud-migration/cloud-readiness-analyzer/using-cloud-readiness-analyzer.html).
   * See the [full release notes for AEM as a Cloud Service.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?mkt_tok=eyJpIjoiWm1SallqTmtOekF6WldZMCIsInQiOiJoTTZ3Qm9LNVRXc1lsbjExdlpNMGdQNFE2UGM5ejZob1EwZXlPZHp2MEZJa1BPTHhybHBYcUxFWTgwVjNFajlzYU1Fb1NoVXRwMTc3U2IrbHZKeTVSOG02MUErbWpIb1pjNU8zYkdTbW5MZHVIRUUyNk9vUU9SckdOeUJmbXlObSJ9)

### Selbsthilfe

* **AEM Assets**

   * Es wurden weitere Tipps zur [Fehlerbehebung](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/troubleshoot.html) für die Desktop-App von Experience Manager hinzugefügt.

* **AEM Forms**

   * AEM Forms Add-On-Pakete sind jetzt unter [AEM Softwareverteilung](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?2_group.propertyvalues.property=.%2Fjcr%3Acontent%2Fmetadata%2Fdc%3Asolution&amp;2_group.propertyvalues.operation=equals&amp;2_group.propertyvalues.0_values=Zielgruppe-solution%3Aaem%2Fforms&amp;orderby=%40jcr%3Acontent%2Fjcr%3AlastModified&amp;orderby.sort=desc&amp;layout=Liste&amp;p.offset=0&amp;p.limit=24)verfügbar. Direkte Links zu Paketen der einzelnen unterstützten Versionen finden Sie im Artikel [AEM Forms-Versionen](https://helpx.adobe.com/de/aem-forms/kb/aem-forms-releases.html) .
   * Auf der [Referenz-Website](https://docs.adobe.com/content/help/en/experience-manager-65/forms/getting-started/aem-forms-reference-collaterals/forms-gov-reference-site-user-demo.html) erfahren Sie, wie Sie den kompletten Arbeitsablauf des Dienstes &quot;Automatisierte Forms-Konvertierung&quot;durchlaufen.
   * Es stehen Javadocs für AEM [6.5.5.0](https://helpx.adobe.com/experience-manager/6-5/forms/javadocs/index.html) und AEM [6.4.8.1](https://helpx.adobe.com/experience-manager/6-4/forms/javadocs/index.html) Versionen zur Verfügung.
   * [Importieren Sie vertrauenswürdige Zertifikate](https://docs.adobe.com/content/help/en/experience-manager-65/forms/manage-administer-aem-forms/hardening-aem-forms-environment/hardening-aem-forms-jee-environment.html#configuring-ssl) in JVM, während Sie eine AEM Forms on JEE-Umgebung härten.
   * Verbesserte Dokumentation zum Einrichten von [PDF Generator.](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/osgi-installation/install-configure-document-services.html)

* **Kernkomponenten**

   Core Componentes Release 2.11.0 bietet Unterstützung für AMP und ist jetzt zusammen mit [Authoring-Dokumentation](https://docs.adobe.com/content/help/de-DE/experience-manager-core-components/using/introduction.html) und [Entwicklerdetails sowie Projektdownload verfügbar auf GitHub.](https://github.com/adobe/aem-core-wcm-components)

### **Community**

* **Die neuesten AEM zum Experience League**

   Dies ist die offizielle Quelle für technische Inhalte von Digital Experience, die von der Adobe produziert werden. Die vollständige Liste [finden Sie hier.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/qaq-p/373396)

### Neue Experience Manager-Kurse und -Tutorials

Nachfolgend sind die im vergangenen Monat neu veröffentlichten Videos, Tutorials und Kurse aufgeführt.

| Veröffentlicht | Name | Typ | Beschreibung |
| ----------- | ---------- | ---------- | ---------- |
| 7. August 2020 | [Erste Schritte mit Multi-Site-Management für Geschäftsbenutzer](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites.msm) | Kurs | Erfahren Sie, wie Sie eine solide Grundlage für Ihre AEM Assets-Implementierung schaffen können, indem Sie die wichtigsten Anliegen konfigurieren, von der Einrichtung einer grundlegenden Inhaltsarchitektur und -taxonomie bis zur Anpassung von Metadaten und Asset-Verarbeitung. |
| 7. August 2020 | [AEM Assets für Administratoren konfigurieren](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2020.1.assets) | Tutorial | Beschreibung |
| 19. Juli 2020 | [Verwenden des Inhaltsübermittlungstools](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/migration/content-transfer-tool.html) | Tutorial | Das [!UICONTROL Content Transfer] Tool ist die empfohlene Methode, um Inhalte von einer lokalen oder AMS-gehosteten Version des Experience Managers auf eine [!UICONTROL AEM als Cloud Service] -Umgebung zu migrieren. |
| 21. Juli 2020 | [Erstellen einer Live-Kopie](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-live-copy.html) | Tutorial | Verstehen Sie, wie Sie mithilfe des Assistenten &quot;Live Copy  erstellen&quot;eine [!UICONTROL Live Copy] für Ihre Site aus einem [!UICONTROL Blueprint] erstellen. |
| 21. Juli 2020 | [Live Copy-Konsole](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/live-copy-overview-console.html) | Tutorial | Erfahren Sie, wie die Vererbung auf einer Site Ansicht oder verwaltet wird oder wie Rollout-Vorgänge mithilfe der Live Copy-Übersichtskonsole durchgeführt werden. |
| 21. Juli 2020 | [Übersetzungsprojekte](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-translation-projects.html) | Tutorial | Erfahren Sie, wie Sie ein Übersetzungsprojekt für Ihre [!UICONTROL Sprachkopie]erstellen, bearbeiten und verwalten. |
| 21. Juli 2020 | [Übersetzungsaufträge](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-translation-projects.html) | Tutorial | Erfahren Sie, wie Sie einem vorhandenen Übersetzungsprojekt einen Übersetzungsauftrag hinzufügen. |
| 21. Juli 2020 | [Aktualisieren der Sprachkopie mit Starts](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/updating-language-copy.html) | Tutorial | Erfahren Sie, wie Sie mithilfe von Launches Änderungen in einer [!UICONTROL Sprachkopie] aktualisieren, überprüfen und genehmigen. |
| 21. Juli 2020 | [Überblick über die Verwaltung mehrerer Sites](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/language-copy-overview.html) | Tutorial | Verschaffen Sie sich einen Überblick darüber, wie eine mehrsprachige Site mit [!UICONTROL Sprachkopie] in [!UICONTROL AEM Sites]erstellt wird. |
| 21. Juli 2020 | [Live Copy und Blueprint](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/live-copy-and-blueprint.html) | Tutorial | Verstehen Sie die Beziehung zwischen einer [!UICONTROL Live Copy] und ihrem [!UICONTROL Blueprint] in [!UICONTROL AEM Sites]. |
| 21. Juli 2020 | [Live Copy-Vererbung auf einer Seite verwalten](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-page-inheritance-live-copy.html) | Tutorial | Erfahren Sie, wie Sie die Vererbung zwischen einer [!UICONTROL Live Copy] und ihrem [!UICONTROL Blueprint] auf Seitenebene verwalten. |
| 21. Juli 2020 | [Live Copy-Vererbung für eine Komponente verwalten](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-component-inheritance-live-copy.html) | Tutorial | Verstehen Sie, wie die Vererbung zwischen einer [!UICONTROL Live Copy] und ihrem [!UICONTROL Blueprint] auf Komponentenebene verwaltet wird. |
| 21. Juli 2020 | [Sprachkopie erstellen](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-component-inheritance-live-copy.html) | Tutorial | Beschreibung |
| 21. Juli 2020 | [Sprachkopie erstellen](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-launguage-copy.html) | Tutorial | Erfahren Sie, wie Sie mithilfe des Assistenten &quot;Sprachkopie [!UICONTROL erstellen&quot;eine] Sprachkopie [!UICONTROL für Ihre AEM Website erstellen können]. |
| 21. Juli 2020 | [Mehrsprachiges Übersetzungsprojekt erstellen](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-multinational-translational-project.html) | Tutorial | Erfahren Sie, wie Sie ein mehrsprachiges Übersetzungsprojekt für Ihre [!UICONTROL Sprachkopie] in AEM Projektkonsole erstellen, bearbeiten und verwalten. |
| 21. Juli 2020 | [Eine Ländersite erstellen](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-new-site.html) | Tutorial | Erfahren Sie, wie Sie mithilfe des Assistenten &quot;Site [!UICONTROL erstellen&quot;eine Ländersite aus vorhandenen] Sprachkopien  erstellen. |
| 21. Juli 2020 | [Create a Language Copy page](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-new-page-language-copy.html) | Tutorial | Learn how to create a page in an existing [!UICONTROL Language Copy], and then translate the content to another [!UICONTROL Language Copy]. |
| 21. Juli 2020 | [Status des Übersetzungsauftrags](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/translation-job-status.html) | Tutorial | Understand the different statuses associated with a Translation Job or an item in the job. |
| 21. Juli 2020 | [Introduction to Multi Site Management](https://video.tv.adobe.com/v/36686?captions=ger) | Tutorial | Einführung in den Kurs Erste Schritte mit Multi-Site-Management für Geschäftsbenutzer. |
| 21. Juli 2020 | [Erstellen von adaptiven Formularfragmenten](https://video.tv.adobe.com/v/37325?captions=ger) | Tutorial | Adaptive Formulare bieten einen bequemen Mechanismus, um Formularsegmente wie Bereiche oder Gruppen von Feldern nur einmal zu erstellen und sie in adaptiven Formularen wiederzuverwenden. Diese wiederverwendbaren und eigenständigen Segmente werden als adaptive Formularfragmente bezeichnet. |
| 21. Juli 2020 | [AEM](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/inbox-customization/introduction.html) | Tutorial | [!UICONTROL AEM Inbox] consolidates notifications and tasks from various AEM components, including Forms workflows. |
| 21. Juli 2020 | [Debuggen des lokalen Schnellstarts des AEM-SDK mit Protokollen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Tutorial | Protokolle dienen als Frontline für das Debugging AEM Anwendungen, sind jedoch von einer angemessenen Anmeldung in der bereitgestellten AEM abhängig. |
| 21. Juli 2020 | [SPA Editor Introduction](https://video.tv.adobe.com/v/37705?quality=12&learn=on&captions=ger) | Tutorial | A course introduction to the Getting started with AEM SPA Editor for developers. |
| 21. Juli 2020 | [Baseline permissions](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/baseline-permissions.html) | Tutorial | Managing user access on the baseline asset folders is a critical aspect in governance, and ensures the processes can be properly supported. |
| 21. Juli 2020 | [Workflows](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/auto-start-workflows.html) | Tutorial | Auto-start workflows extend asset processing in AEM as a Cloud Service by automatically invoking custom workflow upon upload or re-processing. |
| 21. Juli 2020 | [Debuggen des lokalen Schnellstarts des AEM-SDK mit Protokollen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Tutorial | Protokolle dienen als Frontline für das Debugging AEM Anwendungen, sind jedoch von einer angemessenen Anmeldung in der bereitgestellten AEM abhängig. |
| 21. Juli 2020 | [Create adaptive form template](https://video.tv.adobe.com/v/37324?captions=ger) | Tutorial | When authors use the template to create an adaptive form, the new form inherits the structure and components you have specified in the template. |
| 21. Juli 2020 | [Create Apache Sling Connection Pooled DataSource](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/prefill-fdm-db/create-form-data-model.html) | Tutorial | The first step in creating RDBMS backed form data model is to configure Apache Sling Connection Pooled DataSource. |
| 21. Juli 2020 | [Pre-filling adaptive forms using form data model](https://video.tv.adobe.com/v/36387?captions=ger) | Tutorial | Einführung in das Vorausfüllen von Formularen mit dem Formulardatenmodell. |
| 21. Juli 2020 | [Erstellen des ersten adaptiven Formulars](https://video.tv.adobe.com/v/37701?captions=ger) | Tutorial | In diesem Video erfahren Sie, wie Sie Ihr erstes adaptives Formular erstellen. |

### Versionsinformationen zu Experience Manager

Die nachfolgend aufgeführten Seiten umfassen alle Versionshinweise zu Experience Manager:

* [Versionsinformationen zu AEM as a Cloud Service](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/release-notes/home.html)
* [Versionshinweise zu AEM Cloud Manager](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Versionshinweise zum Dienst für die automatische Formularkonvertierung](https://docs.adobe.com/content/help/de-DE/aem-forms-automated-conversion-service/using/release-notes.html)
* [Versionshinweise zum AEM 6.5 Cumulative Fix Pack](https://docs.adobe.com/content/help/de-DE/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Versionshinweise zum AEM 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/de-DE/experience-manager-64/release-notes/cfp-release-notes.html)
* [Versionshinweise zu AEM Assets Dynamic Media](https://docs.adobe.com/content/help/de-DE/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Versionshinweise zu AEM Brand Portal](https://docs.adobe.com/content/help/de-DE/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Versionshinweise zum AEM-Desktop-Programm](https://docs.adobe.com/content/help/de-DE/experience-manager-desktop-app/using/release-notes.html)
* [Versionshinweise zu AEM Dispatcher](https://docs.adobe.com/content/help/de-DE/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Versionshinweise zu Adobe Primetime](https://docs.adobe.com/content/help/de-DE/primetime/release-notes/home.translate.html)
* [Versionshinweise zu Livefyre](https://docs.adobe.com/content/help/de-DE/livefyre/using/release-notes/c-rn.html)

### Zusätzliche Hilferessourcen für AEM

* [Benutzerhandbücher für AEM as a Cloud Service](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-5.html)
* [AEM 6.4 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-4.html)
* [AEM 6.3 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-3.html)
* [AEM 6.2 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-2.html)
* [Cloud Manager-Benutzerhandbuch](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Ältere Versionen der AEM-Dokumentation](https://helpx.adobe.com/de/experience-manager/aem-previous-versions.html)
* [Startseite der Hilfe zu Dynamic Media Classic](https://docs.adobe.com/content/help/de-DE/dynamic-media-classic/using/home.html)

## ![Symbol](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Neue Produktversionen

Versionsinformationen zu Campaign Classic, Campaign Standard und Control Panel.

#### Campaign Classic

* 20.2.1 Version - [Mehr dazu](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/release-notes/latest-release.html#release-20-2-2-build-9180)

### Neue Campaign-Kurse und -Tutorials

Nachfolgend sind die im vergangenen Monat neu veröffentlichten Videos, Tutorials und Kurse aufgeführt.

| Veröffentlicht | Name | Typ | Beschreibung |
| ----------- | ----------- | ---------- | ---------- |
| 10. Juli 2020 | [Systemsteuerung - Verwaltung der GPG-Schlüssel - Entschlüsselung von Daten](https://docs.adobe.com/content/help/de-DE/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/decrypting-data.html) | Campaign Classic | Erfahren Sie, wie ein öffentlicher Schlüssel erstellt und importiert und in einer Campaign-Instanz zur Entschlüsselung von eingehenden Daten installiert wird. |
| 10. Juli 2020 | [Systemsteuerung - GPG-Schlüsselverwaltung - Verschlüsseln von Daten mit einem GPG-Schlüssel](https://docs.adobe.com/content/help/de-DE/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/using-a-gpg-key-to-encrypt-data.html) | Campaign Classic | Erfahren Sie, wie Sie Daten mit einem im Control Panel installierten GPG-Schlüssel exportieren. |
| 10. Juli 2020 | [Systemsteuerung - Generieren und Installieren von GPG-Schlüsseln für die Datenverschlüsselung](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.html) | Campaign Classic | Erfahren Sie, wie Sie ein öffentliches/privates GPG-Schlüsselpaar generieren und den öffentlichen Schlüssel in der Systemsteuerung installieren, um Daten verschlüsseln zu können, bevor Sie sie von Ihrer Instanz senden. |
| 21. Juli 2020 | [Verwalten von Marketing-Kampagnen](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/managing-marketing-campaigns.html) | Campaign Classic | Verstehen Sie die Schlüsselkonzepte von Adobe Campaign, die eine effektive Planung, Ausführung und Messung von Cross-Kanal-Marketing-Kampagnen ermöglichen. |
| 22. Juli 2020 | [Erstellen von Marketingplänen, Programmen und Kampagnen](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/creating-a-marketing-plan-programs-and-campaigns.html) | Campaign Classic | Erfahren Sie, wie Sie einen Marketingplan, ein Programm und eine Kampagne erstellen, Eigenschaften für eine Kampagne festlegen und wie Sie den Zeitplan verwenden. Das Video führt Sie durch eine Übung, der Sie folgen können. |
| 23. Juli 2020 | [Erstellen und Verwalten von Profilen](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/profile-management/create-and-manage-profiles.html) | Campaign Classic | Verstehen Sie das Konzept der Profile in Adobe Campaign Classic. Erfahren Sie, wie Sie auf Profil-Daten zugreifen, Profil sortieren und filtern und Profil manuell erstellen und verwalten können. |
| 28. Juli 2020 | [Personalisieren von E-Mails mit bedingtem Inhalt](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/email-channel/personalizing-emails-create-a-multi-lingual-newsletter-using-conditional-content.html) | Campaign Classic | Hier erfahren Sie, wie Sie einem Versand Bedingungsinhalte hinzufügen, z. B. einen mehrsprachigen Newsletter. |
| 28. Juli 2020 | [Personalisieren von E-Mails mit Personalisierungsfeldern](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/email-channel/personalizing-emails-using-personalization-fields.html) | Campaign Classic | Erfahren Sie, wie Sie der Betreffzeile und dem Inhalt eines E-Mail-Versands ein Personalisierungsfeld hinzufügen. |
| 28. Juli 2020 | [Targeting von Profilen in einem Workflow](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/targeting-profiles-in-a-workflow.html) | Campaign Classic | Machen Sie sich mit der Verwendung von Kampagnen-Workflows vertraut und lernen Sie, wie Sie mit Filterbedingungen Workflow- und Zielgruppe-Profil in einem Workflow erstellen. |
| 31. Juli 2020 | [Erstellen eines beschreibenden Berichts zur Analyse](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/reporting/generating-a-descriptive-analysis-report.html) | Campaign Classic | Erfahren Sie, wie Sie einen beschreibenden Bericht zur Analyse erstellen. |
| 9. Juli 2020 | [Systemsteuerung - GPG-Schlüsselverwaltung - Verschlüsseln von Daten mit einem GPG-Schlüssel](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/using-a-gpg-key-to-encrypt-data.html) | Campaign Standard | Erfahren Sie, wie Sie Daten mit einem im Control Panel installierten GPG-Schlüssel exportieren. |
| 9. Juli 2020 | [Systemsteuerung - Verwaltung der GPG-Schlüssel - Entschlüsselung von Daten](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/decrypting-data.html) | Campaign Standard | Erfahren Sie, wie ein öffentlicher Schlüssel erstellt und importiert und in einer Campaign-Instanz zur Entschlüsselung von eingehenden Daten installiert wird. |
| 9. Juli 2020 | [Systemsteuerung - GPG-Key-Management - Generieren und Installieren von GPG-Schlüsseln zur Datenverschlüsselung](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.html) | Campaign Standard | Erfahren Sie, wie Sie ein öffentlich-privates Schlüsselpaar für die Verschlüsselung von ausgehenden Daten in einer bestimmten Campaign-Instanz generieren und installieren. |

### Hilfe-Ressourcen

* Adobe Campaign Standard: [Hilfe-Center](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/campaign-standard-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-notes.html) – [Anleitungsvideos](https://docs.adobe.com/content/help/de-DE/campaign-standard-learn/tutorials/overview.html) – [Versionsplanung](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-planning.html) – [Neueste Aktualisierungen der Dokumentation](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Hilfe-Center](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/campaign-classic-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/release-notes/latest-release.html) – [Anleitungsvideos](https://docs.adobe.com/content/help/de-DE/campaign-classic-learn/tutorials/overview.html) – [Neueste Aktualisierungen der Dokumentation](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/documentation-updates.html)
* Control Panel von Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/de-DE/control-panel/using/control-panel-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/control-panel/using/release-notes.html) – Anleitungsvideos für [Campaign Standard](https://docs.adobe.com/content/help/de-DE/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/de-DE/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Symbol](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Versionshinweise für Adobe Advertising Cloud.

* [Neue Funktionen in Advertising Cloud DSP](#adcloud-dsp)
* [Neue Funktionen in Advertising Cloud Search](#adcloud-search)

### New features in [!UICONTROL Advertising Cloud DSP] {#adcloud-dsp}

| Funktion | Beschreibung |
| -----------| ---------- |
| Interaktives Pre-Roll erweitert um VAST-Inventar | Jede interaktive Pre-Roll-Platzierung und Anzeige kann jetzt sowohl VPAID- als auch VAST-Inventar unterstützen. **Hinweis:** Wenn Ihr primärer KPI die Sichtbarkeit ist, erstellen Sie weiterhin separate VPAID- und VAST-Platzierungen und Anzeigen, da für VAST-Anzeigen keine sichtbaren Impressionen verfügbar sind. |

### Neue Funktionen in [!UICONTROL Advertising Cloud Search] {#adcloud-search}

**Version 8** . August

| Funktion | Beschreibung |
| ----------- | ---------- |
| [!UICONTROL Portfolios] | Positionslimits auf Portfolio-Ebene sind in den Portfolioeinstellungen nicht mehr verfügbar. Alle zuvor erstellten Positionslimits wurden entfernt. |
| [!UICONTROL Begrenzungen] | Positionsbasierte Beschränkungen und Einschränkungen werden nicht mehr unterstützt: <br/> <ul><li>Min-Pos- und Max-Pos-Beschränkungen sind nicht mehr verfügbar und wurden aus allen zuvor erstellten Angebotsbeschränkungen und Impressions-Share-Beschränkungen entfernt.</li><li>Bestehende Beschränkungen für Angebot und Position, die zwar Positionsbeschränkungen, aber keine Angebotsbeschränkungen enthielten, wurden angehalten. Sie stehen weiterhin in der Benutzeroberfläche und in Berichten zur Verfügung.</li><li>Beschränkungen für Angebot und Position wurden in Angebotsbeschränkungen umbenannt.</li><li>Alle positionsbasierten Bedingungen (unter Verwendung der Metriken &quot;Durchschnittliche Position&quot;, &quot;Gewogene durchschnittliche Position&quot;oder &quot;Letzte bekannte POS&quot;) in einer beliebigen Beschränkung wurden entfernt.</li></ul> <br/> **Hinweis:** Positionsdaten werden solange ausgefüllt, wie sie in den Suchmaschinen verfügbar sind. Microsoft Ads will retire position in September 2020. |
| [!UICONTROL Kampagnen] | (Google Ads campaigns) Advertising Cloud Search now supports ad customizers in responsive search ads (RSAs). Previously, they were supported in all ad types except for RSAs. |

## ![Symbol](/assets/magento.png) [!DNL Magento] {#magento}

Magento-Versionshinweise finden Sie unter:

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![Symbol](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] ist eine Komplettanwendung für das Lead-Management. B2B-Marketer können damit Kundenerlebnisse transformieren, indem sie in allen Phasen komplexer Customer Journeys Interaktionen ermöglichen.

### Aktualisierungen von Core Marketo Engage

Die aktuellen Versionsinformationen finden Sie in den [!DNL Marketo] [Versionshinweisen](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+July+%2720).

### Bevorstehende Funktionen

Die folgenden Funktionen werden im Laufe dieses Quartals veröffentlicht:

| Funktion | Beschreibung |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>Neue kontobasierte Segmentierung</li><li>Speichern von Dashboard-spezifischen Filtern</li><li>Export von Bizible Dashboards als PDF</li></ul> |
| Sales Connect | Aktualisierungen/Verbesserungen für Compose Window und Command Center |

### Ankündigungen

**Marketo Engage Success Center:** Start im Februar 2020. Das Success Center ist ein produktinternes Hilfesystem, mit dem Sie u. a. Produktdokumente und die Community durchsuchen, Anleitungen aufrufen und auf Adoptionsinhalte zugreifen können. Hinweis: Diese Funktion wird als Betaversion in ANZ gestartet und später in diesem Quartal in Nordamerika eingeführt.

### Veraltete und entfernte Funktionen

* **Asset-API-Parameter „_method“:** Ab September 2020 wird `_method` nicht mehr vom Asset-API-Endpunkten akzeptiert, um Abfrageparameter zu einem POST-Textkörper weiterzuleiten und URI-Längenbeschränkungen zu umgehen.
* **Einstellung der Unterstützung für Internet Explorer:** Ab der Juli-Version vom 31. Juli 2020 wird die Benutzeroberfläche von Marketo Engage in Internet Explorer nicht mehr unterstützt.

Eine Sammlung historischer Versionshinweisen finden Sie unter [Marketo-Versionshinweise](https://docs.marketo.com/x/CgA6Ag).
