---
title: Adobe Experience Cloud – Versionshinweise
description: Adobe Experience Cloud – Versionshinweise
doc-type: release notes
last-update: January 2021
author: mfrei
translation-type: tm+mt
source-git-commit: 026ae3842b9683ac8c55658964969d5deca75340
workflow-type: tm+mt
source-wordcount: '6618'
ht-degree: 41%

---


# Adobe Experience Cloud – Versionshinweise, Januar 2021

![Banner](/assets/experience-cloud-banner-3.png)

Auf dieser Seite sind neue Funktionen, Fehlerbehebungen und wichtige Hinweise in [!DNL Adobe Experience Cloud] beschrieben. Außerdem werden neue Dokumentationen, Schulungen und Videoschulungen vorgestellt, die Ihnen helfen, Experience Cloud optimal zu nutzen.

>[!NOTE]
>
>Abonnieren Sie die monatliche Produktaktualisierung [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html), um E-Mail-Benachrichtigungen über Updates auf dieser Seite zu erhalten. Diese Seite wird den ganzen Monat lang gepflegt. Informieren Sie sich daher regelmäßig über die neuesten Adoben zu Unternehmensprodukten und der Experience League-Dokumentation.

Neueste Aktualisierung: **14. Januar 2021**

* [Systemstatus](#status)  der Adobe (nicht aktualisiert)
* [Experience Cloud Services und Administration](#ecloud)
* [Experience Platform](#platform)  (Aktualisiert  **am 14. Januar 2021**)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) und [Customer Journey Analytics](#cust-journey) (Aktualisiert: **12. Januar 2021**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Kampagne](#ac)  (Aktualisiert  **am 12. Januar 2021**)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo) (Aktualisiert:  **11. Januar 2021**)
* [Document Cloud](#doc-cloud)

Benötigen Sie Hilfe? Besuchen Sie [Adobe Experience League](https://experienceleague.adobe.com/?lang=de-DE#home), um Produkt und technische Dokumentation, von Adobe kuratierte Kurse, Videoschulungen, schnelle Antworten, Community-Einblicke und von Schulungsleitern geführte Kurse zu erhalten. Inhalt wurde von `docs.adobe.com` an diesen Speicherort verschoben. Bitte aktualisieren Sie die Lesezeichen entsprechend.

## ![Symbol](/assets/adobe.png) Systemstatus von Adobe {#status}

[!UICONTROL Der Adobe-Systemstatus] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe Cloud-Produkten und -Diensten. Weitere Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/).

Kein Update in diesem Monat.

Aktuelle Versionshinweise finden Sie unter [Systemstatus von Adobe – 21. Mai 2020](https://docs.adobe.com/content/help/de-DE/release-notes/experience-cloud/previous/2020/05212020.html#status).

## ![Symbol für](/assets/ec_appicon_24.png) Experience Cloud Services und Administration {#ecloud}

[Zu den Experience Cloud Services- und ](https://docs.adobe.com/content/help/de-DE/core-services/interface/experience-cloud.html) Administratordokumenten gehören Kundenattribute, Audience Library ( PeopleService), Aktivierung-, Benutzer- und Produktverwaltung sowie Experience Cloud-Cookies.

Kein Update in diesem Monat.

**Siehe auch**

* [Gesammelte Versionshinweise zu Experience Cloud-](https://docs.adobe.com/content/help/de-DE/core-services/interface/release-notes/release-notes.html) Services für die neuesten Versionsinformationen.
* [Experience Cloud-ID-](https://experienceleague.adobe.com/docs/id-service/using/release-notes/release-notes.html) Servicerelease-Hinweise

## ![Symbol](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Enthält Versions-Updates für Experience Platform und Experience Platform Launch.

| Funktion | Releasedatum | Beschreibung |
| ------- | ------| ------- |
| Verbesserte Interaktion mit der Produktunterstützung für die Experience Platform | 15. Januar 2021 | Sie können jetzt eine Frage stellen oder ein Problem zur Experience Platform melden, ohne die Benutzeroberfläche Ihrer Experience Platform zu verlassen. Navigieren Sie zu **[!UICONTROL Hilfe]** > **[!UICONTROL Support]** > **[!UICONTROL Erstellen Sie ein Support-Ticket]**, geben Sie Ihre Anfrage ein und senden Sie Ihren Fall direkt an den Kundensupport. Sie erhalten eine E-Mail-Benachrichtigung mit einer Fallnummer, und das Kundendienstteam wird Sie per Ticket kontaktieren, um Ihre Anfrage zu bearbeiten. |

Letzte Aktualisierung: **9. Dezember 2020**

Die neuesten Aktualisierungen für:[](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=en)

* [!UICONTROL Datenflüsse]
* [!UICONTROL Data Science Workspace]
* [!UICONTROL Quellen]

### Experience Platform Launch

Releasedatum: **13. Januar 2021**

**[!UICONTROL Serverseite] starten: Daten auf Ereignis-Ebene an das AEP Edge Network** senden. Verwenden Sie dann die Seite &quot;Launch&quot;, um die Daten zu transformieren, zu erweitern und an einen Endpunkt ohne Adobe zu senden, indem Sie die Server der Adobe und nicht den Client mit niedriger Latenz verwenden. [Mehr...](https://experienceleague.adobe.com/docs/launch/using/server-side-info/server-side-overview.html?lang=en#server-side-info)

**Siehe auch**

* [Versionshinweise ](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html) zu Experience Platform Launchs.
* [Versionshinweise zum Experience Cloud-ID-Dienst ](https://experienceleague.adobe.com/docs/launch/using/extensions-ref/adobe-extension/id-service-extension/experience-cloud-id-release-notes.html) für Erweiterung

### Adobe Mobile

Aktualisiert **14. Januar 2021**

iOS-Version 4.21.1

* Allgemein - Es wurde ein Problem behoben, das beim Herunterfahren der App SQLite-Ausnahmen verursachte.

iOS-Version 4.21.0

* Allgemein - Das SDK wird jetzt mit [!DNL XCFrameworks] verteilt, um Hardware mit der neuen Apple M1-Architektur zu unterstützen und gleichzeitig die Unterstützung der bestehenden Intel Architektur beizubehalten.

* WICHTIG: Für die Aktualisierung auf AdobeMobile [!DNL XCFrameworks] ist Xcode 12.0 oder höher erforderlich.
* WICHTIG: Bei Verwendung von [!DNL Cocoapods] ist für das Upgrade auf AdobeMobile [!DNL XCFrameworks] [!DNL Cocoapods] &lt;1.10.0 oder höher erforderlich.

### Schulungen und Kurse zu Experience Platform und Services

Neue Videos, Tutorials oder Kurse, die für Experience Platform und Services veröffentlicht wurden.

Aktualisiert: **6. Januar 2021**

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| 23. Dezember 2020 | [Übersicht über Vereinigung Schema](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/union-schemas-overview.html) | Video | Erfahren Sie mehr über die Schema der Vereinigung, die Adobe Experience Platforms Echtzeit-Customer-Profil verwendet. |
| 22. Dezember 2020 | [Segmente mit mehreren Entitäten erstellen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/create-multi-entity-segments.html) | Video | Erfahren Sie, wie Sie im Segmentaufbau von Adobe Experience Platform Segmente mit mehreren Entitäten erstellen. |
| 21. Dezember 2020 | [Angebotsaktivitäten erstellen](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-offer-activities.html) | Video | Erfahren Sie, wie Sie Angebot-Aktivitäten in [!UICONTROL Offer Decisioning] erstellen. Eine Angebot-Aktivität kombiniert Ihre Platzierungen und Sammlungen zu einer Einheit, sodass eine Entscheidung getroffen werden kann, dem Kunden das relevanteste Angebot zu liefern. |
| 21. Dezember 2020 | [Kollektionen erstellen](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-collections.html) | Video | Erfahren Sie, wie Sie Sammlungen in [!UICONTROL Offer Decisioning] erstellen. Sammlungen werden zur Verwaltung von Angeboten in logischen Gruppen verwendet und sind zum Erstellen von Offer Decisioning-Aktivitäten erforderlich. |
| 21. Dezember 2020 | [Bereitstellen von Angeboten mit der Entscheidungs-API](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/deliver-offers-with-the-decisions-api.html) | Video | Erfahren Sie, wie Sie mit der Entscheidungs-API [!UICONTROL Offer Decisioning]-Angebot bereitstellen. |
| 15. Dezember 2020 | [Personalisierte Angebote erstellen](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-personalized-offers.html) | Video | Erfahren Sie, wie Sie personalisierte Angebot in [!UICONTROL Offer Decisioning] erstellen. |
| 15. Dezember 2020 | [Fallback-Angebote erstellen](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-fallback-offers.html) | Video | Erfahren Sie, wie Sie Ausweich-Angebot in [!UICONTROL Offer Decisioning] erstellen. |
| 14. Dezember 2020 (aktualisiert) | [Konzept des Echtzeit-Kundenprofils](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/understanding-the-real-time-customer-profile.html) | Video | In diesem Video wird erläutert, wie Adobe Experience Platform Echtzeit-Profil von Kunden zusammenstellt und aktualisiert und wie Sie auf diese Profil zugreifen und sie verwenden können. |
| 10. Dezember 2020 | [Erstellen von Tags](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-tags.html)   | Video | Erfahren Sie, wie Sie Tags in [!UICONTROL Offer Decisioning] erstellen. Tags sind optionale Bausteinkomponenten von Angeboten. Sie können verwendet werden, um Angebote zu organisieren und sie in dynamischen Sammlungen zu gruppieren. |
| 9. Dezember 2020 | [Regeln in Offer Decisioning erstellen](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-rules.html) | Video | Erfahren Sie, wie Sie Regeln in [!UICONTROL Offer Decisioning] erstellen. Regeln werden unter Verwendung der Ereignis und Attribute im [!UICONTROL Echtzeit-Profil] der Plattform erstellt und bilden die Berechtigungseinschränkungen von Angeboten. |
| 9. Dezember 2020 | [Platzierungen erstellen](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/create-placements.html) | Video | Erfahren Sie, wie Sie Platzierungen in Offer Decisioning erstellen. Eine Platzierung ist eine Kombination aus Inhaltstyp und Kanal, z. B. ein Bild in einer E-Mail oder einem HTML-Code auf einer Website. |
| 29. Oktober 2020 (aktualisiert) | [Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/demo-of-offer-decisioning.html?lang=de-DE) | Video | Hier erfahren Sie, wie Marken mit dem neuen [!UICONTROL Offer Decisioning]-Dienst von Adobe ihre Angebote bestimmen und verwalten und ihren Kunden unter Verwendung von Echtzeit-Kundendaten auf ihre Bedürfnisse abgestimmte Erlebnisse bereitstellen können. |
| 26. Oktober 2020 (aktualisiert) | [Einführung in Offer Decisioning](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/introduction-to-offer-decisioning.html) | Video | In diesem Video erhalten Sie einen Überblick über [!UICONTROL Offer Decisioning], einen Anwendungsdienst, der auf Adobe Experience Platform aufbaut. In diesem Video werden die von [!UICONTROL Offer Decisioning] gelösten geschäftlichen Herausforderungen, die wichtigsten Funktionen, die grundlegende Architektur und die wichtigsten Anwendungsfälle behandelt. |
| 26. Oktober 2020 (aktualisiert) | [Daten mit dem Salesforce CRM Source Connector erfassen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-salesforce-crm.html) | Video | Mit dem Salesforce CRM Source Connector können Sie Daten aus Salesforce CRM problemlos in Adobe Experience Platform&#39;s Echtzeit-Customer Profil and Experience Data Lake stapeln, und zwar auf nahtlose und skalierbare Weise. |
| 13. Oktober 2020 (aktualisiert) | [Daten mit dem Salesforce CRM Source Connector erfassen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html) | Video | Mit dem Salesforce CRM Source Connector können Sie Daten aus Salesforce CRM problemlos in Adobe Experience Platform&#39;s Echtzeit-Customer Profil and Experience Data Lake stapeln, und zwar auf nahtlose und skalierbare Weise. |
| 23. Oktober 2020 (aktualisiert) | [Daten in Echtzeit-Kundendaten einbinden](https://experienceleague.adobe.com/docs/platform-learn/tutorials/profiles/bring-data-into-the-real-time-customer-profile.html) | Video | Echtzeit-Kundendaten-Profile ermöglichen die umfassende Personalisierung von Kanälen in jeder Phase der Journey. |
| 13. Oktober 2020 (aktualisiert) | [Konfigurieren von Attribution AI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-attribution-ai.html) | Video | Erfahren Sie, wie Sie eine Instanz von Attribution AI erstellen, um die Auswirkungen Ihrer Marketing-Kanäle und -Kampagnen zu verstehen. |
| 13. Oktober 2020 (aktualisiert) | [Konfigurieren von Kunden-KI](https://experienceleague.adobe.com/docs/platform-learn/tutorials/intelligent-services/configure-customer-ai.html) | Video | Erfahren Sie, wie Sie eine Instanz der Kunden-AI erstellen, um das Kundenverhalten vorherzusagen. |

## ![Symbol](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Verwenden Sie Adobe Experience Platform, um die Journey im Maßstab eines Kunden über Erlebnis-Kanal hinweg zu orchestrieren, indem Sie die Bedürfnisse jedes Einzelnen intelligent in Echtzeit vorhersehen.

### Neue Produktversionen

* November-Version - [Weitere Informationen](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html#november-release)
* Oktober-Version - [Weitere Informationen](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html#october-release)

### Zusätzliche Ressourcen für Journey Orchestration

[Dokumentation](https://docs.adobe.com/content/help/de-DE/journeys/using/journey-orchestration-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/journeys/using/release-notes/release-notes.html) – [Videoanleitungen](https://docs.adobe.com/content/help/de-DE/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Symbol](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Releasedatum: **14. Januar 2021**

* [Neue Funktionen in Adobe Analytics](#aa-features)
* [Neue Funktionen in Customer Journey Analytics](#cust-journey)
* [Fehlerbehebungen in Adobe Analytics](#aa-fixes)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [AppMeasurement](#appm)
* [Report Builder ](#arb)

### Neue Funktionen in Adobe Analytics {#aa-features}

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/de-DE/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| ----------- | ---------- | ------- |
| Analysis Workspace - Bild-URLs | 14. Januar 2021 | Sie können Bilder zu [!UICONTROL Workspace]-Projekten hinzufügen, indem Sie auf eine öffentliche Bild-URL verweisen. [Weitere Infos](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/visualizations/text.html?lang=en#analysis-workspace) |
| Analysis Workspace - Kombinierter Quell- und Einstellungsmanager | 14. Januar 2021 | Der Datenquellen-Manager (Punkt) und der Einstellungsmanager (Zahnrad) für Visualisierungen wurden zu einem einzigen Dialog zusammengefasst, sodass Sie Ihre Quelle und Einstellungen einfach vom gleichen Ort aus verwalten können. |
| Analysis Workspace - Komponentenauswahl | 4. Februar 2021 | Die Dropdown-/Dropzone-Komponente in [!UICONTROL Quick Insights] wurde zu allen Ablagebereichen in [!UICONTROL Workspace] hinzugefügt. Diese Verbesserung ermöglicht es Ihnen, aus einer Dropdown-Liste kompatibler Komponenten auszuwählen oder den Raum weiterhin als Dropzone zu verwenden. |

### Neue Funktionen in Customer Journey Analytics {#cust-journey}

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| ----------- | ---------- | ----- |
| [!UICONTROL Geräte]- und [!UICONTROL Geografie]-Dimensionen | 30. Oktober 2020 | Diese Dimensionen sind jetzt standardmäßig im Rahmen des Unterstützungsprojekts [Globale Suche](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-usecases/global-lookups.html?lang=en#use-global-lookups-with-adobe-data-connector-datasets) im Adobe Analytics [!UICONTROL Source Connector] verfügbar. Dieser dringend benötigte Zusatz erhöht die [Parität zwischen Adobe Analytics und CJA](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-overview/cja-aa.html?lang=en#cja-overview). |
| Journey IQ: [!UICONTROL Cross-Kanal Analytics] | 11. Januar 2021 | Journey IQ: [!UICONTROL Cross-Kanal Analytics] ermöglicht Ihnen die erneute Eingabe eines Adobe Analytics- (oder anderen) Ereignis-Datensatzes in den Daten-See der Experience Platform von einem ID-Namensraum zum anderen. Dies bedeutet in der Regel, dass der Ereignis-Datensatz von einer Cookie-basierten ID in eine personenbasierte ID erneut verschlüsselt wird. Auf diese Weise kann der neu eingegebene Datensatz mit anderen personenbezogenen Daten in einer CJA-Verbindung kombiniert werden, sodass geräteübergreifende und geräteübergreifende Analyse in Analysis Workspace möglich ist. [Weitere Infos](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-connections/cca/overview.html?lang=de-DE#cja-connections) |
| Analysis Workspace - Bild-URLs | 14. Januar 2021 | Sie können Bilder zu Workspace-Projekten hinzufügen, indem Sie auf eine öffentliche Bild-URL verweisen. |
| Analysis Workspace - Kombinierter Quell- und Einstellungsmanager | 14. Januar 2021 | Der Datenquellen-Manager (Punkt) und der Einstellungsmanager (Zahnrad) für Visualisierungen wurden zu einem einzigen Dialog zusammengefasst, sodass Sie Ihre Quelle und Einstellungen einfach vom gleichen Ort aus verwalten können. |
| Analysis Workspace - Komponentenauswahl | 4. Februar 2021 | Die Dropdown-/Dropzone-Komponente in [!UICONTROL Quick Insights] wurde zu allen Ablagebereichen in [!UICONTROL Workspace] hinzugefügt. Diese Verbesserung ermöglicht es Ihnen, aus einer Dropdown-Liste kompatibler Komponenten auszuwählen oder den Raum weiterhin als Dropzone zu verwenden. |

### Fehlerbehebungen in Adobe Analytics {#aa-fixes}

* Korrektur von Formatierungs-, Download- und Senden-Problemen mit heruntergeladenen CSV-Berichten in Workspace. (AN-224844)
AN-240295)
* Es wurde ein Fehler behoben, der dazu führte, dass in Livestream keine Daten für mobile Attribute angezeigt wurden, obwohl die Analytics Report Suite Daten enthielt. (AN-241169)
* Es wurde ein Fehler behoben, der dazu führte, dass im Echtzeitbericht keine Daten angezeigt wurden. (AN-242477)
* In Reports &amp; Analysen wurde ein Problem behoben, bei dem keine Daten angezeigt wurden, wenn der Filter _contains_ verwendet wurde. (AN-237354)
* Es wurde ein Fehler behoben, der dazu führte, dass aus Adobe Analytics gelöschte Segmente weiterhin im Data Connector der Kampagne verwendet wurden. (AN-236713)
* Es wurden Probleme behoben, die dazu führten, dass eingeplante Berichte in der Berichtwarteschlange steckten. (AN-242599, AN-242554, AN-242900, AN-243329)
* Es wurden Probleme mit Berichten zur freigegebenen Zielgruppe in Reports &amp; Analysen behoben. (AN-234638)
* Es wurde ein Problem behoben, bei dem Balkendiagramme keine Daten in Workspace anzeigen. (AN-232127)
* Es wurden Probleme behoben, durch die Kunden sich nicht bei Adobe Analytics anmelden konnten. (AN-241882 AN-238802)
* Der Bericht &quot;Mobilgeräte&quot;wurde aktualisiert und enthält jetzt Samsung Galaxy Z Falten2 5G. (AN-238246)
* Korrektur von Fehlern in eingeplanten Berichten in Workspace. (AN-236707, AN-243449)
* Es wurde ein Problem behoben, bei dem Datenquellendateien nicht per FTP abgerufen wurden. (AN-240347)
* Es wurde ein Fehler behoben, der beim Versuch, auf [!UICONTROL Advertising Analytics] zuzugreifen, einen Fehler verursachte. (AN-241478)
* Es wurde ein Problem behoben, durch das Dateien nicht vom Classification FTP abgerufen wurden. (AN-242490)
* Es wurde ein Fehler beim Rendern der Benutzeroberfläche in Workspace behoben. (AN-243123)
* Es wurde ein Fehler behoben, der dazu führte, dass Data Warehousen vom SFTP-Server nicht empfangen werden konnten. (AN-244679)
* Es wurde ein Fehler behoben, der dazu führte, dass der Link [!UICONTROL Bericht herunterladen] nicht funktionierte, der unter [!UICONTROL Admin] > [!UICONTROL Protokolle] > [!UICONTROL Nutzungs- und Zugriffsprotokolle] gefunden wurde. (AN-238058)

#### Weitere Fehlerbehebungen in Adobe Analytics

AN-204659; AN-221726; AN-230949; AN-231984; AN-232835;  AN-233989; AN-235593; AN-235989; AN-236823; AN-236840; AN-237168; AN-237262; AN-237265; AN-237633; AN-237740; AN-238523; AN-238870; AN-238941; AN-239414; AN-239649; AN-239652; AN-239676; AN-239703; AN-240184; AN-240219; AN-240412; AN-240530; AN-240609; AN-240625; AN-240664; AN-240682; AN-240715; AN-241052; AN-241077; AN-241112; AN-241149; AN-241578; AN-241714; AN-242157; AN-242485; AN-242535; AN-242573; AN-242608; AN-242728; AN-242818; AN-242820; AN-242963; AN-242978; AN-243013; AN-243054; AN-243105; AN-243172; AN-243181; AN-243255; AN-243326; AN-243418; AN-243449; AN-243463; AN-243507; AN-243518; AN-243519; AN-243598; AN-243805; AN-243814; AN-243910; AN-243929; AN-244009; AN-244012; AN-244105; AN-244121; AN-244137; AN-244188; AN-244225; AN-244305; AN-244357; AN-244363; AN-244419; AN-244607; AN-244695; AN-244713; AN-244828; AN-244843; AN-244876; AN-244877; AN-245388; AN-245470

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| ----------- | ---------- | ---------- |
| Erforderliches [!UICONTROL Report Builder]-Update | 8. Januar 2021 | Bis zum 30. April 2021 müssen alle [!UICONTROL Report Builder]-Benutzer das [!UICONTROL Report Builder]-Add-In auf Version 5.6.47 oder höher aktualisieren. Diese Version enthält eine wichtige Aktualisierung des Anmeldeprozesses. Benutzer, die nicht auf Version 5.6.47 oder höher aktualisieren, können sich nach dem 30. April 2021 nicht mehr anmelden. [!UICONTROL Report ] Builder Version 5.6.47 und höher unterstützt nur die Experience Cloud-Anmeldung und unterstützt keine Legacy-Anmeldungen wie SiteCatalyst Single Sign-On oder die Standard-Anmeldung. Weitere Informationen finden Sie unter [Report Builder-Anmeldung](https://experienceleague.adobe.com/docs/analytics/analyze/report-builder/report-builder-setup/login.html?lang=en#section_6D54B8ADAE7F416BB83F5082B3771CFA). |
| Ende der Laufzeit für drei Analytics-API-Dienste | 6. Januar 2021 | Am 30. April 2021 werden die folgenden Analytics Legacy-API-Dienste auf das Enddatum eingestellt und geschlossen. Alle aktuellen Integrationen, die mit diesen Diensten erstellt wurden, funktionieren an diesem Tag nicht mehr.<ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Wir haben eine [Ältere API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) bereitgestellt, die Ihnen bei der Beantwortung Ihrer Fragen hilft und Anleitungen zum Fortfahren gibt. API-Integrationen, die diese Dienste verwenden, können zu den Analytics REST-APIs [1.4 und/oder den Analytics-APIs [2.0 migrieren. ](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email)](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) Ältere OAuth-Konten können zu einem [Adobe IO](https://console.adobe.io/home?mv=email#) Analytics-Integrationskonto migrieren, das für den Zugriff auf sowohl Analytics-APIs 1.4 als auch Analytics-APIs 2.0 verwendet werden kann. |
| Hinzufügen der HSTS-Kopfzeile zu allen eingehenden HTTPS-Anfragen | 29. Sept. 2020 | Am 29. September 2020 haben wir begonnen, allen eingehenden Anfragen, die HTTPS verwenden, die HSTS-Kopfzeile hinzuzufügen. Dadurch wird der Browser/Client angewiesen, alle zukünftigen Anfragen in HTTPS durchzuführen, was als Best Practice für die Sicherheit gilt. Aktuell werden wir dies nicht für eingehende Anfragen unter Verwendung von HTTP durchführen. |
| Ändern Sie die Cookie-Einstellung in [!UICONTROL Experience Cloud-ID-Dienst] | 22. Sept. 2020 | Eine Aktualisierung der Datenschutzeinstellungen für Chrome Version 80 führte zur Beeinträchtigung der Fähigkeit von Adobe Analytics, manche Benutzer zu tracken, die Google AMP-Seiten betrachten. Insbesondere verhindert sie das domänenübergreifende Tracking von Benutzern, die Google-gehostete AMP-Seiten anzeigen. Dies könnte zu einer erhöhten Anzahl von Unique Visitors führen. Mit dieser Korrektur können Benutzer dieses Problem lösen, indem sie die Einstellungen für ihre ECID-Cookies ändern.<br>Derzeit setzt Analytics Experience Cloud ID Service (ECID)-Cookies mit der Einstellung `SameSite = Lax`, was vor Version 80 von Chrome ein domänenübergreifendes Tracking ermöglichte. Das ist nicht mehr der Fall. Diese Änderung ermöglicht es jetzt Benutzern, die SameSite-Einstellung für ECID-Cookies auf `None` zu aktualisieren.<br>Beachten Sie, dass dadurch Analytics-Cookies in zusätzlichen Situationen geteilt werden können, sie jedoch keine vertraulichen Daten enthalten. Darüber hinaus müssen bei der Auswahl dieser Einstellung Cookies auf `Secure` gesetzt werden, damit Daten nur über HTTPS-Verbindungen weitergeleitet werden können. Wenn Sie diese Änderung vornehmen möchten, bitten Sie einen unterstützten Benutzer, ein Ticket beim Kundendienst zu öffnen. |
| Migration von der Domain `omniture.com` zu `adobe.com` | 21. August 2020 | Am 13. August 2020 migrierte Adobe Analytics seine Frontend-Architektur von der Domain `omniture.com|http://omniture.com/` zu `adobe.com|http://adobe.com/`. Diese Änderung soll Probleme mit Drittanbieter-Cookies beheben, die nach der ersten Änderung der einheitlichen Produkt-Domain am 28. Mai 2020 aufgetreten sind. Aufgrund dieser Aktualisierung wird der Browser die Benutzer möglicherweise auffordern, der neuen Domain `.adobe.com|http://an.adobe.com/` oder `experience.adobe.com|http://experience.adobe.com/` zu vertrauen. |
| Aktualisierung der Kompatibilität mit Ad Hoc Analysis Java 8 | 21. August 2020 | Ad Hoc Analysis ist derzeit nicht mit Java 8 Version 1.8.0_261 und höher kompatibel. Um sicherzustellen, dass Ihr Zugriff auf dieses Tool nicht unterbrochen wird, bevor das [Ende des Lebenszyklus](https://spark.adobe.com/page/S9Bhp66VJ2fEn/) erreicht ist, sollten Sie eine Java 8-Version niedriger als 1.8.0_261 beibehalten. |
| EOL von Adobe Data Connectors | 13. Juli 2020 | Adobe [!UICONTROL Data Connectors] basieren auf einer älteren Technologie, die nicht mehr funktionsfähig ist oder unterstützt wird. Im [Adobe Exchange Partner-Programm](https://partners.adobe.com/exchangeprogram/experiencecloud) gibt es einen neuen Standard, der für alle Integrationen übernommen werden sollte, die weiterhin angeboten und unterstützt werden sollen. Das offizielle Ende des Lebenszyklus wurde noch nicht festgelegt, aber wir gehen davon aus, dass es in den nächsten 12 bis 18 Monaten (Mitte 2021 bis Ende 2021) sein wird. [Weitere Infos...](https://docs.adobe.com/content/help/de-DE/analytics/import/dataconnectors/data-connectors-eol.html) |
| Ende von Ad Hoc Analysis | 6. August 2018 | Adobe kündigte die Absicht an, Ad Hoc Analysis am 1. März 2021 zu beenden. Weiterführende Informationen finden Sie unter [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### AppMeasurement {#appm}

Die neuesten Aktualisierungen zu AppMeasurement-Versionen finden Sie in den [Versionshinweisen zu AppMeasurement für JavaScript](https://docs.adobe.com/content/help/de-DE/analytics/implementation/appmeasurement-updates.html).

### Report Builder {#arb}

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| ----------- | ---------- | ----- |
| Anmelde-Update für Analytics [!UICONTROL Report Builder] | 14. Januar 2021 | Die Verbesserungen am Anmeldeprozess [!UICONTROL Report Builder] entfernen Abhängigkeiten von älteren Technologien und richten den Anmeldeprozess an Adobe Experience Cloud aus. Mit dem Experience Cloud-Anmelden können Sie sich mit Ihrem Adobe ID oder Ihrer Enterprise ID (Single Sign-On) beim Adobe Experience Cloud anmelden. Bis zum 30. April 2021 müssen alle [!UICONTROL Report Builder]-Benutzer das [!UICONTROL Report Builder]-Add-In auf Version 5.6.47 oder höher aktualisieren. [!UICONTROL Report ] Builder Version 5.6.47 und höher unterstützt nur die Experience Cloud-Anmeldung und unterstützt keine alten Anmeldungen, wie z. B. SiteCatalyst Single Sign-On oder die standardmäßige Anmeldung. Weitere Informationen finden Sie unter [Report Builder-Anmeldung](https://experienceleague.adobe.com/docs/analytics/analyze/report-builder/report-builder-setup/login.html?lang=en#section_6D54B8ADAE7F416BB83F5082B3771CFA). |

### Analytics-Hilferessourcen

* [Adobe Analytics-Produktdokumentation und Tutorials](https://experienceleague.corp.adobe.com/docs/analytics.html)

## ![Symbol](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Neue Funktionen, Fehlerbehebungen, Dokumentationen und Tutorials in Audience Manager.

<!-- ### Fixes and Improvements {#aam-fixes-and-improvements}

* Fixed an issue in the Predictive Audience feature where some users were unable to delete any of their models, even if no segments were mapped to the models. (AAM-55881)
* Fixed an issue where some users were unable to delete traits or segments which had been used as baseline for deleted predictive audience models. (AAM-56476)
* We continued making accessibility improvements across the interface. (AAM-53215) -->

### Audience Manager-Kurse und -Tutorials {#tutorials-aam}

Neue Videos, Tutorials oder Kurse, die für Audience Manager veröffentlicht wurden.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| 15. Dezember 2020 | [Berechtigungen mit rollenbasierter Zugriffskontrolle festlegen](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/setup-and-admin/user-management/setting-permissions-with-role-based-access-control.html?lang=en#setup-and-admin) | Video | Erfahren Sie, wie Sie Berechtigungen auf Gruppenebene verwalten und steuern, wer Assets anzeigen und mit ihnen arbeiten kann, einschließlich Eigenschaften, Segmente, Ziele und Modellen. Richten Sie die Berechtigungsgruppen ein und fügen Sie ihnen Benutzer hinzu. |

## ![Symbol](/assets/aem.png) Adobe Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

>[!NOTE]
>
>Adobe empfiehlt, [Experience Manager-Versions-Updates und -Roadmaps](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) regelmäßig zu besuchen, um auf dem Laufenden zu bleiben.

### Produktaktualisierungen

* **AEM 6.5.7.0**
AEM 6.5, Service Pack 7 (6.5.7.0, veröffentlicht am 26. November 2020) ist ein wichtiges Update, das neue Funktionen, wichtige Kundenverbesserungen, verbesserte Leistung, Stabilität und Sicherheit umfasst. Das Update wurde seit der allgemeinen Verfügbarkeit von AEM 6.5, April 2019 veröffentlicht.
   * [Versionshinweise](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en#service-pack)
   * [Versionsfreigaben von AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **AEM 6.4.8.3**
AEM 6.4, Service Pack 8, Cumulative Fix Pack 3 (6.4.8.3 veröffentlicht am 26. November 2020) ist ein wichtiges Update, das einige interne und kundenspezifische Fehlerbehebungen seit der allgemeinen Verfügbarkeit von AEM 6.4, Service Pack 8 (6.4.8.0), März 2020 enthält.
   * [Versionshinweise](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
   * [Versionsfreigaben von AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

### Produktversionen

* **AEM as a Cloud Service**

   Neuerungen bei AEM as a Cloud Service

   * **Adobe Experience Manager Sites as a Cloud Service**
      * [Content Fragment HTTP-API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html): hinzufügen die Möglichkeit,   Inhaltsfragmentvarianten mithilfe der HTTP-API hinzuzufügen/zu aktualisieren und zu löschen.
   * **Adobe Experience Manager Assets as a Cloud Service**

      * Die Integration mit Adobe InDesign Server steht jetzt als [!UICONTROL Cloud Service] zum Experience Manager zur Verfügung. Es bietet Automatisierung zur Verarbeitung von Adobe InDesign-Dateien mithilfe von Adobe InDesign Server-Skripten und ermöglicht Benutzern die Verwendung von Asset-Vorlagen-Benutzeroberfläche zum Erstellen von Prospekten oder Anzeigen. Für den Experience Manager als [!UICONTROL Cloud Service] wird nur die von Adobe Managed Services gehostete InDesign Server unterstützt.
      * Experience Manager wurde erweitert, um Asset-Verweise zu verfolgen und anzuzeigen, wenn ein Asset in einer Site-Bereitstellung von Remote-Experience Managern mit der Funktion [!UICONTROL Connected Assets] verwendet wird. Die neue Registerkarte [!UICONTROL Referenzen] auf der Seite [!UICONTROL Eigenschaften] des Assets Liste jetzt lokale und Remote-Referenzen des Assets. Anhand der Referenzen können DAM-Benutzer die Asset-Nutzung auf den Seiten [!UICONTROL Sites] und in zusammengesetzten Assets in [!UICONTROL Assets] verfolgen.
Siehe [Connected Assets](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/use-assets-across-connected-assets-instances.html) konfigurieren und verwenden.
      * [!UICONTROL Dynamische ] Funktionen sind jetzt über   Sitemage-basierte Kernkomponenten verfügbar. Autoren können Komponenten schnell so konfigurieren, dass beim Erstellen von Webseiten [!UICONTROL Bildvorgaben], [!UICONTROL Smart-Zuschneiden] und [!UICONTROL Bildmodifikatoren] verwendet werden.
Siehe [Kernkomponenten 2.13.0 Release](https://github.com/adobe/aem-core-wcm-components/releases/tag/core.wcm.components.reactor-2.13.0).
      * Mit der Desktop-App von Experience Manager können Benutzer Dateien und Ordner hochladen, indem sie die Dateien aus dem Windows Explorer oder dem Mac Finder in die Benutzeroberfläche der Desktop-App ziehen.
Siehe [Hinzufügen von Assets mit der Desktop-App](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/using.html?lang=en#upload-and-add-new-assets-to-aem).
   * **Adobe Experience Manager Commerce as a Cloud Service**

      * CIF-Referenzseite Venia - 2020.12.01, die die neueste CIF-Kernkomponenten Version v1.6.0 enthält.
Siehe [CIF Venia Reference Site](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2020.12.01).
      * Version 1.6.0 der CIF-Kernkomponenten
Siehe [CIF-Kernkomponenten](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.6.0).
   * **Cloud Manager**

      * Selbstbedienungs-Management von [SSL-Zertifikate](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/manage-ssl-certificates/introduction.html) und [Benutzerspezifische Domänennamen](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/custom-domain-names/introduction.html).
      * Selbstbedienungs-Management von [IP-Zulassungslisten](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/onboarding/getting-access/ip-allow-lists/introduction.html).
      * Die Seite mit den Details zur Umgebung wurde aktualisiert und ermöglicht Benutzern nun, [!UICONTROL Benutzerspezifische Domänennamen] und [!UICONTROL IP-Zulassungslisten] auf ihren Umgebung zu verwalten.
   * **Code-Refaktorierungs-Tools**

      * Neue Version des AIO-CLI Plug-Ins veröffentlicht. Die neueste Version dieses Plug-ins enthält Fehlerbehebungen für den AEM Dispatcher Converter und den Repository Modernizer und unterstützt auch ein neues Dienstprogramm - den Index Converter.
Weitere Informationen zu diesem Plug-in finden Sie unter [Einheitliches Erlebnis](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/refactoring-tools/unified-experience.html#benefits).
      * Index Converter ist ein Dienstprogramm, das verwendet werden kann, um die benutzerdefinierten OAK-Indexdefinitionen eines Kunden in AEM als Cloud Service kompatible OAK-Indexdefinitionen umzuwandeln.
Siehe [Indexkonverter](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/index-converter).
      * Neue Funktion zu [Repository Modernizer](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/repository-modernizer) hinzugefügt, die ein separates Paket `ui.config` erstellt, das alle OSGi-Konfigurationen enthält.





Siehe [Versionshinweise für AEM as a Cloud Service](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html).

### Selbsthilfe

**[!DNL Experience Manager as a Cloud Service]**

Aktualisierungen der Dokumentation zu neuen Funktionen finden Sie unter den obigen Links. Zu den weiteren Aktualisierungen der Dokumentation gehören die folgenden:

* **Best Practices-Analyzer**

   * [!UICONTROL Cloud Readiness ] Analyzeris  [!UICONTROL Best Practices Analyzer] (BPA). BPA bietet eine Best Practices-Bewertung Ihrer aktuellen AEM-Implementierung und hilft bei der Beurteilung der Bereitschaft, von einer vorhandenen AEM-Instanz zu AEM als [!UICONTROL Cloud Service] zu wechseln.

* **Foundation**

   * Workflows - Unterstützung für die Suche nach Workflow-Instanzen auf Basis von [!UICONTROL Workflow-Titel], [!UICONTROL Workflow-Modell], [!UICONTROL Status], [!UICONTROL Initiator], [!UICONTROL Payload-Pfad] und [!UICONTROL Beginn-Datum].
Siehe [Instanzen des Sucharbeitsablaufs](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/administering/workflows-administering.html#administering).
   * Synchronisierung der Benutzerdaten auf Veröffentlichungsebene - Benutzerdaten, einschließlich Profil- und Gruppenattributen, können auf der Veröffentlichungsebene beibehalten werden.
Siehe [Profil zur Registrierung, Anmeldung und Benutzerdokumentation](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/personalization/user-and-group-sync-for-publish-tier.html#authoring).

### [!DNL Experience Manager] Formulare

Dokumentation zu den folgenden Funktionen in Version 6.5.7.0 ist verfügbar:

* Nach der Installation des Service Packs werden serverseitige Überprüfungen und die Konvertierung von PDF in adaptive Formulare schneller durchgeführt.

* Sie können jetzt alle Änderungen an der Größe rückgängig machen und für jede Komponente im Layoutmodus eines adaptiven Formulars das Standardlayout anwenden. Siehe [Verwenden Sie den Layoutmodus, um die Größe von Komponenten](https://experienceleague.adobe.com/docs/experience-manager-65/forms/adaptive-forms-basic-authoring/resize-using-layout-mode.html?lang=en) zu ändern.

* [!DNL Experience Manager Forms] Formulardatenmodell bei der Integration mit RESTful-Webdiensten, da die Datenquelle jetzt HTTP-Client-Konfigurationen für das Verbindungsmanagement enthält. Siehe [Datenquellen konfigurieren](https://experienceleague.adobe.com/docs/experience-manager-65/forms/form-data-model/configure-data-sources.html?lang=en#configure-relational-database).

### Community

**Neueste Adobe Experience Manager-Inhalte auf Experience League für Januar 2021**  - Eine  [umfassende Liste mit Funktionsvideos, Artikeln, Tutorials und Kursen finden Sie hier](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/td-p/392549).

### Neue Experience Manager-Kurse und -Tutorials

Aktualisiert: **10. Januar 2021**

Nachfolgend sind die im vergangenen Monat neu veröffentlichten Videos, Tutorials und Kurse aufgeführt.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| 7. Dezember 2020 | [Erweiterte Datenmodellierung mit Fragmentverweisen](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/fragment-references.html) | Artikel | Beginnen Sie mit Adobe Experience Manager (AEM) und GraphQL. Erfahren Sie, wie Sie mit der Funktion [!UICONTROL Fragmentverweis] eine erweiterte Datenmodellierung durchführen und eine Beziehung zwischen zwei verschiedenen [!UICONTROL Inhaltsfragmenten] erstellen können. Erfahren Sie, wie Sie eine GraphQL-Abfrage ändern, um Felder aus einem referenzierten Modell einzuschließen. |
| 7. Dezember 2020 | [Abfrage AEM mit GraphQL einer externen App](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/explore-graphql-api.html) | Artikel | Beginnen Sie mit Adobe Experience Manager (AEM) und GraphQL. Entdecken Sie AEM GraphQL APIs eine WKND GraphQL React App. Erfahren Sie, wie diese externe App GraphQL-Aufrufe an AEM ausführt, um das Erlebnis zu optimieren. Erfahren Sie, wie Sie eine grundlegende Fehlerbearbeitung durchführen. |
| 7. Dezember 2020 | [GraphQL APIs](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/explore-graphql-api.html) | Artikel | Beginnen Sie mit Adobe Experience Manager (AEM) und GraphQL. Entdecken Sie AEM GraphQL APIs mit der integrierten GrapiQL IDE. Erfahren Sie, wie AEM basierend auf einem Inhaltsfragmentmodell automatisch ein GraphQL-Schema generiert. Experimentieren Sie mit der Erstellung grundlegender Abfragen mit der GraphQL-Syntax. |
| Dezember 2020 | [Authoring von Inhaltsfragmenten](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/author-content-fragments.html) | Artikel | Beginnen Sie mit Adobe Experience Manager (AEM) und GraphQL. Erstellen und bearbeiten Sie ein neues Inhaltsfragment, das auf einem [!UICONTROL Inhaltsfragmentmodell] basiert. Erfahren Sie, wie Sie Varianten von [!UICONTROL Inhaltsfragmenten] erstellen. |
| 7. Dezember 2020 | [Definieren von Inhaltsfragmentmodellen](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/content-fragment-models.html) | Artikel | Beginnen Sie mit Adobe Experience Manager (AEM) und GraphQL. Erfahren Sie, wie Sie Inhalte modellieren und ein Schema mit Inhaltsfragmentmodellen in AEM erstellen. Überprüfen Sie vorhandene Modelle und erstellen Sie ein neues Modell. Erfahren Sie mehr über die verschiedenen Datentypen, mit denen ein Schema definiert werden kann. |
| 9. Dezember 2020 | [API-Kompatibilität](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/admin/developer-reference-material-apis.html) | Artikel | Erstellen Sie einen einfachen Artikel, der klar angibt, welche AEM APIs (npm, Java, HTTP) für verschiedene [!UICONTROL Assets]-Vorgänge verwendet werden können. |
| 2. Dezember 2020 | [Herunterladen von Inhaltsfragmenten](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-feature-video-use.html?lang=de-DE) | Video | Eine Übersicht über die Download-Funktionen von Inhaltsfragmenten. |
| 7. Dezember 2020 | [Inhaltsfragment-Editorfunktionen](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-feature-video-use.html) | Video | Eine Videoübersicht über die erweiterten Funktionen des Editors [!UICONTROL Inhaltsfragment]. Erfahren Sie, wie Sie Anmerkungen und Versionsvergleiche mit [!UICONTROL Inhaltsfragmenten] verwenden. |
| 4. Dezember 2020 | [OCR-Extraktion von Daten mit oder ohne Barcode von vom Staat ausgegebenen Dokumenten](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/ocr-data-extraction.html?lang=en#some-useful-integrations) | Artikel | Füllen Sie das adaptive Formular aus, indem Sie Daten aus staatlich ausgestellten Dokumenten wie Führerschein oder Reisepass extrahieren. |
| 14. Dezember 2020 | [AEM ohne Kopf mit GraphQL-Übersicht](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/overview.html) | Video | Eine Übersicht über die in Adobe Experience Manager oder AEM implementierte GraphQL API. Die GraphQL-API in AEM ist in erster Linie dafür ausgelegt, [!UICONTROL Inhaltsfragment]-Daten im Rahmen einer kostenlosen Bereitstellung an nachgeschaltete Anwendungen zu senden. |
| 16. Dezember 2020 | [Dynamic Media Core-Komponente](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/dynamic-media-core-components.html) | Video | Die Image-Komponente, die Teil der Experience Manager-Core-Komponenten ist, unterstützt Dynamic Media. Erfahren Sie, wie die Image-Komponente einem Inhaltsautor die Verwendung von Funktionen von Dynamic Media wie Bildvorgaben, Smart-Zuschneiden und Bildmodifikatoren auf einer AEM Sites-Seite ermöglicht. |

### Versionsinformationen zu Experience Manager

Die nachfolgend aufgeführten Seiten umfassen alle Versionshinweise zu Experience Manager:

* [Versions-Updates und Roadmap für Experience Manager](https://docs.adobe.com/content/help/de-DE/experience-manager-release-information/aem-release-updates/home.html)
* [Versionsinformationen zu AEM as a Cloud Service](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/release-notes/home.html)
* [Versionshinweise zu AEM Cloud Manager](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Versionshinweise zum Dienst für die automatische Formularkonvertierung](https://docs.adobe.com/content/help/de-DE/aem-forms-automated-conversion-service/using/release-notes.html)
* [Versionshinweise zum AEM 6.5 Cumulative Fix Pack](https://docs.adobe.com/content/help/de-DE/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Versionshinweise zum AEM 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/de-DE/experience-manager-64/release-notes/cfp-release-notes.html)
* [Versionshinweise zu AEM Assets Dynamic Media](https://docs.adobe.com/content/help/de-DE/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Versionshinweise zu AEM Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=en)
* [Versionshinweise zum AEM-Desktop-Programm](https://docs.adobe.com/content/help/de-DE/experience-manager-desktop-app/using/release-notes.html)
* [Versionshinweise zu AEM Dispatcher](https://docs.adobe.com/content/help/de-DE/experience-manager-dispatcher/using/getting-started/release-notes.html)
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

[Bulletin](https://helpx.adobe.com/security/products/campaign/apsb21-04.html)  zur Reaktion auf Vorfälle (aktualisiert:  **12. Januar 2021**)

* Version 20.3.3 – [Mehr lesen](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html#release-notes)
* Version 20.3.1 – [Mehr lesen](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html#release-notes)
* Version 20.2.4 – [Mehr lesen](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--20-2.html#release-20-2-4-build-9187)
* Version 20.1.4 – [Mehr lesen](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--20-1.html#release-20-1-4-build-9126)
* Version 19.2.4 – [Mehr lesen](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--19-2.html#release-19-2-4-build-9082)
* Version 19.1.8 – [Mehr lesen](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-8-build-9039)

#### Campaign Classic Gold Standard

* Gold Standard 11 Release - [Mehr lesen](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/gs-release/gold-standard.html?lang=en#gs-11)

### Hilfe-Ressourcen

* Adobe Campaign Standard: [Hilfe-Center](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/campaign-standard-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-notes.html) – [Anleitungsvideos](https://docs.adobe.com/content/help/de-DE/campaign-standard-learn/tutorials/overview.html) – [Versionsplanung](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-planning.html) – [Neueste Aktualisierungen der Dokumentation](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Hilfe-Center](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/campaign-classic-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/release-notes/latest-release.html) – [Anleitungsvideos](https://docs.adobe.com/content/help/de-DE/campaign-classic-learn/tutorials/overview.html) – [Neueste Aktualisierungen der Dokumentation](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/documentation-updates.html)
* Control Panel von Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/de-DE/control-panel/using/control-panel-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/control-panel/using/release-notes.html) – Anleitungsvideos für [Campaign Standard](https://docs.adobe.com/content/help/de-DE/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/de-DE/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

#### Neue Campaign-Kurse und -Tutorials

Nachfolgend sind die im vergangenen Monat neu veröffentlichten Videos, Tutorials und Kurse aufgeführt.

| Veröffentlicht | Name | Lösung | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| 23. Dezember 2020 | [Dynamische Inhalte konfigurieren](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/email-channel/configuring-dynamic-content.html#sending-messages) | Campaign Classic | (Video) Verstehen Sie die verschiedenen Arten von dynamischen Inhalten und erfahren Sie, wie Sie Gestaltungsbaustein und bedingte Anweisungen erstellen und auf einen Versand anwenden. |
| 9. Dezember 2020 | [Control Panel – Verwaltung von Google TXT-Einträgen](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/subdomains-and-certificates/google-txt-record-management.html#subdomains-and-certificates) | Campaign Standard | (Video) Erfahren Sie, wie Sie Google TXT-Site-Überprüfungsdatensätze zu allen Subdomänen hinzufügen können, die zum Senden von E-Mails an GMAIL-Adressen verwendet werden, mit dem [!UICONTROL Kampagne-Systemsteuerung]. |

## ![Symbol](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Versionshinweise für Adobe Advertising Cloud.

* [Neue Funktionen in Advertising Cloud DSP](#adcloud-dsp)
* [Neue Funktionen in Advertising Cloud Search](#adcloud-search)

### Neue Funktionen in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Zuletzt aktualisiert: **28. Oktober 2020**

| Funktion | Beschreibung |
| -----------| ---------- |
| Neu Hilfe | (Version vom 28. Oktober) Die alte Hilfe wurde durch aktualisierte Seiten ersetzt, die über den Hilfe-Link im DSP Hauptmenü abrufbar und jederzeit unter [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=de-DE](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=de-DE) verfügbar sind. |
| Kampagnen | (Version vom 28. Oktober) Die früheren Beta-Ansichten von Campaign sind jetzt die standardmäßigen Ansichten von Campaign und bieten schnellere Einblicke, vereinfachte Workflows und benutzerspezifische Ansichten. |
| Privates Inventar | (Version vom 15. Oktober) Alle Benutzer können jetzt mit einem neuen Deal-ID-Formular Details zu Deal-IDs einrichten und bearbeiten. Hierbei handelt es sich um eine vereinfachte Version des alten [!UICONTROL Smart Ad Serving]-Formulars. Um neue Details für Deal-IDs einzurichten, gehen Sie zu **[!UICONTROL Inventar > Deals]**, klicken Sie auf **[!UICONTROL Erstellen]** und dann auf **[!UICONTROL Deal ID Beta]**. |
| Platzierungsvorhersage | (Version vom 15. Oktober) Für Platzierungen mit Platzierungsebenen-Geschwindigkeit enthält der Abschnitt [!UICONTROL Prognose] der Platzierungseinstellungen einen neuen Abschnitt mit [!UICONTROL geschätzten Höchstwerten], der angibt, wie viel mehr Kapazität mit der aktuellen Targeting-Konfiguration verfügbar ist. |

### Neue Funktionen in [!DNL Advertising Cloud Search] {#adcloud-search}

Zuletzt aktualisiert: **17. Oktober 2020**

| Funktion | Beschreibung |
| -----------| ---------- |
| [!UICONTROL Search-Kampagnen] | In der Ansicht [!UICONTROL Konten] zeigt die Spalte [!UICONTROL Zugriff] jetzt an, wann sich [!DNL Advertising Cloud Search] nicht bei einem aktivierten Suchmaschinenkonto anmelden kann. Um die Fehlerursache anzuzeigen, halten Sie den Cursor über das Warnsymbol. |
| [!UICONTROL Benutzerspezifische Warnhinweise] | Die früheren Beta-[!UICONTROL Warnhinweise] heißen jetzt [!UICONTROL benutzerdefinierte Warnhinweise]. |
| [!UICONTROL Benutzerspezifische Warnhinweise] | Bei benutzerdefinierten Warnhinweisen wurde der Arbeitsablauf vereinfacht, der identifiziert, wann die Metriken für den angegebenen Datumsbereich gegenüber den Metriken für den vorherigen Zeitraum zu- oder abgenommen haben. Außerdem wurde er auf die Registerkarte [!UICONTROL Filter] verschoben. |

### Ad Cloud-Tutorials und -Kurse

Aktualisiert: **2. Dezember 2020**

| Veröffentlicht | Name | Lösung | Beschreibung |
| ----------- | ----------- | ---------- | ---------- |
| 14. November 2020 | [Erstellen von Advertising Cloud Dashboards mit Adobe Analytics](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-dashboards-a4adc.html?lang=de-DE) | Video | Verfahren zum Erstellen eines Advertising Cloud Dashboards zur Live-Überwachung von Kampagnen. |
| 14. November 2020 | [Erstellen von Site-Einstiegsberichten für Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-site-entry-a4adc.html?lang=de-DE#analytics) | Video | Erstellen eines Site-Einstiegsberichts für Advertising Cloud zur Überwachung von Wochentag, Tageszeit, Browser und geografischem Einfluss. |
| 14. November 2020 | [Erstellen von Analytics Custom-Metriken mit Advertising Cloud-Daten](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-custom-metrics-a4adc.html?lang=de-DE#analytics) | Video | Nützliche benutzerspezifische Metriken, die bei der Verwendung von Advertising Cloud-Daten in Adobe Analytics erstellt werden. |
| 14. November 2020 | [Erstellen von Analytics-Segmenten für Aktivierung und Reporting](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-segments-a4adc.html?lang=de-DE#analytics) | Video | Zur Verwendung von Abmessungen der Advertising Cloud zur Erstellung von Segmenten für saubereres Reporting und Analyse. |
| 14. November 2020 | [Grundlegendes zu Predictive Audiences](https://experienceleague.corp.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html?lang=de-DE#build-and-manage-audiences) | Video | In diesem Video besprechen wir, was Predictive Audiences in Audience Manager sind, erläutern Einzelheiten zu ihrer Funktionsweise und zeigen Anwendungsfälle auf. |
| 14. November 2020 | [Erstellen von Analytics-Profilen für Advertising Cloud-Aktivierung und -Reporting](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-profiles-a4adc.html?lang=de-DE#analytics) | Video | So erstellen Sie mit Adobe Analytics robuste Site-Retargeting-Pools für das Advertising Cloud-Remarketing. |
| 14. November 2020 | [Reporting mit Advertising Cloud-Marketing-Kanälen](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-reporting-a4adc.html?lang=de-DE#analytics) | Video | Hier erfahren Sie, wie die Viewthrough- und Clickthrough-Eingabedaten von Advertising Cloud mit Adobe Analytics Marketing-Kanälen funktionieren. |
| 14. November 2020 | [Erstellen einer Kampagnenanalyse vor dem Start mit Adobe Analytics](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-pre-launch-a4adc.html?lang=de-DE) | Video | Wie Sie mit Adobe Analytics die Grundlage für den Start einer Paid-Media-Kampagne in der Advertising Cloud schaffen. |

## ![Symbol](/assets/magento.png) [!DNL Magento] {#magento}

Magento-Versionshinweise finden Sie unter:

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![Symbol](/assets/target.png)[!DNL Target] {#target}

Die aktuellen Versionsinformationen finden Sie in den [[!DNL Target] Versionshinweisen](https://docs.adobe.com/content/help/de-DE/target/using/release-notes/target-release-notes.html).

## ![Symbol](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] ist eine Komplettanwendung für das Lead-Management. B2B-Marketer können damit Kundenerlebnisse transformieren, indem sie in allen Phasen komplexer Customer Journeys Interaktionen ermöglichen.

### Aktualisierungen von Core Marketo Engage

Die aktuellen Versionsinformationen finden Sie in den [!DNL Marketo] [Versionshinweisen](https://docs.marketo.com/display/public/DOCS/Jan+%2721).

### Bevorstehende Funktionen

Die folgenden Funktionen werden im Laufe dieses Quartals veröffentlicht:

| Funktion | Beschreibung |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>Neue kontobasierte Segmentierung</li><li>Speichern von Dashboard-spezifischen Filtern</li><li>Export von Bizible Dashboards als PDF</li></ul> |
| Sales Connect | Aktualisierungen/Verbesserungen für Compose Window und Command Center |

### Veraltete und entfernte Funktionen

* **Asset-API-Parameter „_method“:** Ab September 2020 wird `_method` nicht mehr vom Asset-API-Endpunkten akzeptiert, um Abfrageparameter zu einem POST-Textkörper weiterzuleiten und URI-Längenbeschränkungen zu umgehen.
* **Einstellung der Unterstützung für Internet Explorer:** Ab der Juli-Version vom 31. Juli 2020 wird die Benutzeroberfläche von Marketo Engage in Internet Explorer nicht mehr unterstützt.

Eine Sammlung historischer Versionshinweisen finden Sie unter [Marketo-Versionshinweise](https://docs.marketo.com/display/public/DOCS/Release+Notes).

## ![Symbol](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Versionshinweise und Hilferessourcen für Adobe Document Cloud.

### Acrobat-Lernprogramme

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| 29. Dezember 2020 | [Seiten organisieren](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/organize.html) | Artikel | Verwenden Sie im Acrobat-Document Cloud [!UICONTROL Seiten organisieren], um Seiten in Ihrer PDF-Datei hinzuzufügen, zu ersetzen, zu extrahieren, zu drehen, zu löschen und zu verschieben. |
| 29. Dezember 2020 | [Ausfüllbare Formulare erstellen](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/create-fillable-forms.html) | Artikel | Verwandeln Sie gescannte Papierformulare oder Dokumente, die in InDesign, Microsoft Word oder Excel oder einer anderen Anwendung erstellt wurden, in ein ausfüllbares PDF-Formular. |
| 29. Dezember 2020 | [Scan &amp; OCR](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/scan-and-ocr.html) | Artikel | Konvertieren Sie Scans oder Bilder von Dokumenten in durchsuchbare, editierbare PDF-Dateien und passen Sie die Qualität der Datei an. |
| 28. Dezember 2020 | [Barrierefreie PDF-Dateien vorbereiten](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/accessibility.html) | Artikel | Erstellen Sie PDF-Dateien mit universeller Barrierefreiheit. |
| 28. Dezember 2020 | [Arbeiten mit Formulardaten](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/formdata.html) | Artikel | Wenn Sie über einen Satz ausgefüllter Formulare verfügen und die Daten kompilieren müssen, können Sie die Antworten mit Acrobat DC in einer einzigen Tabelle zusammenführen. |
| 28. Dezember 2020 | [Reduzierung der Dateigröße und Optimierung](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/reduce.html) | Artikel | Reduzieren Sie große Dateien und optimieren Sie PDFs, ohne die Qualität von Freigabe, Veröffentlichung oder Archivierung zu beeinträchtigen. |
| 21. Dezember 2020 | [Barrierefreies Gestalten von PDF-Ballots](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/by-industry/gov/pdfs/making-pdf-ballots-accessible.html) | Webinar | Erfahren Sie mehr über die wichtigsten Bereiche der PDF-Barrierefreiheit, die erforderlich sind, damit Benutzer von Hilfstechnologien wie Bildschirmlesehilfen ihre Stimme lesen und abschließen können. |
| 21. Dezember 2020 | [Schwärzen und Bereinigen](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/redact.html) | Artikel | Verwenden Sie das Schwärzen-Werkzeug, um private oder vertrauliche Informationen dauerhaft aus Ihrem PDF- und Sanitize-Dokument zu entfernen. |
| 18. Dezember 2020 | [Action Wizard](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/action.html) | Artikel | Erstellen Sie eine Aktion, um automatisch eine Reihe von Befehlen auf eine oder mehrere Dateien anzuwenden. |
| 15. Dezember 2020 | [Konfigurieren des Ablaufs der Eigenschaft mit der Einstellung &quot;Time to Live (TTL)&quot;](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/configuring-trait-expiration-with-the-time-to-live-ttl-setting.html?lang=en#build-and-manage-audiences) | Video | Erfahren Sie, wie Sie mit [!UICONTROL Zeit bis zum Live] arbeiten. Dies ist ein Ablauf der Mitgliedschaft in der Eigenschaft, wenn Sie sich nicht innerhalb des angegebenen Zeitraums erneut qualifizieren. |
| 4. Dezember 2020 | [Verwenden der Adobe PDF Tools API für OCR-PDF-Dateien](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/ocr.html) | Artikel | Erfahren Sie, wie Sie mit [!UICONTROL Optische Zeichenerkennung] gescannte PDFs entsperren können, um Text zu extrahieren und durchsuchbare Dateien zu erstellen. |
| 4. Dezember 2020 | [Erste Schritte mit Adobe PDF Tools API und Java](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/gettingstartedjava.html) | Artikel | Entwickler können in wenigen Minuten mit den Beispieldateien beginnen, die für den Zugriff auf alle verfügbaren Webdienste bereitgestellt werden. Dieses Lernprogramm führt Sie durch alle Schritte, um die Beispieldateien mit dem Java-SDK für PDF Tools Beginn. |
| 4. Dezember 2020 | [Erste Schritte mit Adobe PDF Tools API und .NET](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/gettingstartednet.html) | Artikel | Entwickler können in wenigen Minuten mit den Beispieldateien beginnen, die für den Zugriff auf alle verfügbaren Webdienste bereitgestellt werden. Dieses Lernprogramm führt Sie durch alle Schritte zum Beginn der Beispielausführung mit dem PDF Tools .Net SDK. |
| 4. Dezember 2020 | [Verwenden der API für PDF-Werkzeuge zum Export PDF zu Word, PowerPoint und mehr](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/exportpdf.html) | Artikel | Konvertieren Sie PDF-Dateien zur Bearbeitung von Inhalten, Genehmigungen und später zum Senden von Unterschriften in MS Word, um benutzerdefinierte Workflows zu erstellen. Oder exportieren Sie PDF-Inhalte zur Analyse von Rechnungen und Finanzberechnungen oder Daten in das MS Excel-Format. |
| 4. Dezember 2020 | [PDF-Dateien aus HTML oder MS Office in wenigen Minuten mit der PDF Tools API und Node.js erstellen](https://experienceleague.adobe.com/docs/document-services/document-services/tutorials/createpdffromhtml.html) | Artikel | Erfahren Sie mehr über die Digitalisierung von Dokument Workflows mit der neuen Adobe PDF Tools API. Diese API bietet Entwicklern eine freie Auswahl zwischen mehreren leistungsstarken PDF-Manipulationsdiensten, um die Anforderungen komplexer Workflows zu erfüllen. |

### Neue Adobe Sign-Kurse und -Tutorials

Neue Videos, Tutorials oder Kurse, die für Adobe Document Cloud veröffentlicht wurden.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| 22. Dezember 2020 | [Paycheck-Schutz](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/expand/recipes/gov/usecasegovpaycheck.html) | Demo | Erfahren Sie, wie Sie mit Adobe Sign das Zahlungsschutz-Programm-Formular in ein interaktives Online-Formular konvertieren können. |

Hilfe zu Document Cloud erhalten Sie über:

* [Adobe Acrobat Learning Hub](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=de-DE)
* [Adobe Sign Learning Hub](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=de-DE)
* [Document Cloud-Schulungen und -Support](https://helpx.adobe.com/de/support/document-cloud.html)
