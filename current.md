---
title: Neueste Versionshinweise
description: Hier finden Sie Informationen über die aktuellen Versionshinweise, neue Funktionen und neue Dokumentation für Experience Cloud-Produkte und -Services. Hier finden Sie neues Material rund um Hilfen und Tutorials zu Experience Cloud, Creative Cloud für Unternehmen und Document Cloud.
doc-type: release notes
last-update: March 2021
author: mfrei
translation-type: tm+mt
source-git-commit: 99f32ddc69aa869be32186b9b0746aae27a79113
workflow-type: tm+mt
source-wordcount: '7556'
ht-degree: 31%

---


# Adobe Experience Cloud – Versionshinweise, März 2021

![Banner](/assets/experience-cloud-banner-3.png)

Experience Cloud-Lösungen und -Services werden monatlich aktualisiert. Diese Seite ist Ihr zentraler Speicherort für die neuesten Versionsupdates, Dokumentation und Übungen für [!DNL Experience Cloud]-Produkte und -Dienste. Sie finden hier außerdem eine neue Dokumentation für [!DNL Creative Cloud for Enterprise] und [!DNL Document Cloud].

>[!NOTE]
>
>Abonnieren Sie das monatliche [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html), um E-Mail-Benachrichtigungen über Aktualisierungen dieser Seite zu erhalten. Diese Seite wird den ganzen Monat lang gepflegt und enthält möglicherweise Inhalte, die vor dem Veröffentlichungsdatum geändert werden können. Aktuelle Informationen zu Adobe Enterprise-Produkten und Experience League-Dokumentation finden Sie regelmäßig.

Letzte Aktualisierung: **24. März 2021**

* [Digital Experience Blueprints](#blueprints)  (neue Implementierungsdokumentation)
* [Systemstatus von Adobe](#status)
* [Komponenten, Dienste und Administration der Benutzeroberfläche von Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [Analytics](#analytics) und [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

Benötigen Sie Hilfe? Besuchen Sie [Adobe Experience League](https://experienceleague.adobe.com/?lang=de#home), um Produkt und technische Dokumentation, von Adobe kuratierte Kurse, Videoschulungen, schnelle Antworten, Community-Einblicke und von Schulungsleitern geführte Kurse zu erhalten.

## ![](/assets/adobe.png) IconDigital Experience Blueprints  {#blueprints}

Digital Experience Blueprints sind wiederholbare Implementierungen, um Strategien zu entwickeln und bestehende Geschäftsprobleme zu lösen. Blueprints beschleunigen die Time-to-Value und bieten einen schnellen Weg zum Erfolg.

| Veröffentlicht | Beschreibung |
| -----------| ---------- |
| [Digital Experience Blueprints](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html) | Übersicht über [!UICONTROL Digitale Blueprints]. Jedes Blueprint-Angebot enthält eine Reihe von Artefakten, die das hochwertige Geschäftsproblem, Architekturen, Implementierungsschritte, technische Überlegungen und Links zur entsprechenden Dokumentation erklären. |
| [Audience Activation-Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/audience-activation/overview.html) | Diese Audience-first-Aktivierung ermöglicht es Marken, Kundeninteraktionen über mehrere Kanal hinweg zu verbinden, um eine zentralisierte Audience bereitzustellen, die für alle Kanal aktiviert werden kann. |
| [Hub-Blueprint zur Aktivität von Kunden](https://experienceleague.adobe.com/docs/blueprints-learn/architecture//customer-activity-hub/overview.html) | Erfahren Sie, wie externe Anwendungen auf das Adobe Experience Platform [!UICONTROL Echtzeit-Profil des Kunden] zugreifen können. |
| [Customer Journey Analytics-Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journey-analytics/overview.html) | Erfahren Sie, wie Marken Kundendaten und Kundenverhalten aus verschiedenen Interaktionsquellen und Kanälen vereinheitlichen können, um eine Journey-basierte Ansicht aller Kundeninteraktionen zu erstellen. |
| [Custom Data Science for Profil Anreicherung Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-science/overview.html) | Erfahren Sie, wie die Daten in Adobe Experience Platform von [!UICONTROL Data Science Workspace] verwendet werden, um Modelle für maschinelles Lernen zu schulen, bereitzustellen und zu bewerten. |
| [Datenaufbereitung und Ingestion - Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-ingestion/overview.html) | Erfahren Sie, wie Sie Quelldaten dem Schema [!UICONTROL Erlebnisdatenmodell] (XDM) zuordnen. Dieser Entwurf umfasst auch die Durchführung von Datentransformationen, einschließlich Datumsformatierung, Feldteilungs-, Verkettungs- und Konvertierungen, sowie das Verbinden, Zusammenführen und erneute Keying von Datensätzen. |
| [Enterprise Data Exploration &amp; Berichte-Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-exploration/overview.html) | Der [!UICONTROL Abfrage-Dienst] der Experience Platform ermöglicht die Ausführung von SQL-Abfragen an den Daten. Erfahren Sie, wie mithilfe von [!UICONTROL Data Science Workspace] Datenerforschung, Datenwissenschaft und maschinelles Lernen mit den Daten ausgeführt werden kann. |
| [Blueprint für Nachrichtenorchestrierung für mehrere Kanal](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/multi-channel-message-orchestration/overview.html) | Erfahren Sie, wie Marken proaktiv mit ihren Kunden kommunizieren können, z. B. per E-Mail, SMS oder Mobil-Warnhinweise. |
| [Blueprint zur serverseitigen Datenerfassung](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/server-side-enterprise-data-collection/overview.html) | Erfahren Sie, wie mit Adobe Experience Platform Web- und Mobile-SDKs erfasste Daten von der Experience Platform [!UICONTROL Edge Network] an das gewünschte Ziel weitergeleitet werden können. |
| [Web- und Mobile-Personalisierungskonzept](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/web-personalization/overview.html) | Erfahren Sie, wie Sie die Segmentierung von Audiencen in mehreren Anwendungen verwenden, um Kundenerlebnisse zu personalisieren und zu optimieren. Sie können Kundenverhalten, Demografie, Treuestufe und vorherige Transaktionen verwenden, um Layouts, Aktionsaufrufe und Inhalte zu personalisieren. |

## ![Symbol](/assets/adobe.png) Systemstatus von Adobe {#status}

[!UICONTROL Der Adobe-Systemstatus] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe Cloud-Produkten und -Diensten. Weitere Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/).

Die neuesten Updates für den Systemstatus der Adobe finden Sie unter [Systemstatus der Adobe - 21. Mai 2020](https://docs.adobe.com/content/help/de-DE/release-notes/experience-cloud/previous/2020/05212020.html#status).

## ![](/assets/ec_appicon_24.png) IconExperience Cloud - Komponenten, Dienste und Administration  {#ecloud}

| Funktion | Beschreibung |
| -----------| ---------- |
| Einheitliche Suche | Die einheitliche Suche, die derzeit für die Experience Platform verfügbar ist, unterstützt jetzt die Suche nach Quellen und Zielen für Benutzer der Experience Platform. Mit dieser Funktion können Sie Segmente, Datensätze, Schema, Quellen und Ziele suchen. |

## ![Symbol](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Enthält Versions-Updates für Experience Platform und Experience Platform Launch.

* [Experience Platform – Versionshinweise](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html). (Aktualisiert am 24. Februar 2021)
* [Experience Platform Launch – Versionshinweise](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=de). (Aktualisiert am 18. Februar 2021)

### Experience Platform-Tutorials und -Kurse

Neue Videos, Tutorials oder Kurse, die für Experience Platform und Services veröffentlicht wurden.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| März 2021 | [Dashboard überwachen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/monitoring-dashboard.html) | Video | Erfahren Sie, wie Sie Daten überwachen und verfolgen, die mithilfe von Monitoring Dashboard in Adobe Experience Platform aufgenommen werden. Dieses Monitoring-Dashboard bietet eine Top-down-Ansicht der Quelldatenverarbeitung durch Data Lake to Profil und Identity Services auf der Quell-, Datenaflow- und Datenaflow-Laufzeitebene, mit umsetzbaren Ratschlägen in zeitnaher Weise. |
| März 2021 | [Streamen von Daten mit Source Connectors](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-source-connector.html) | Video | In diesem Video wird gezeigt, wie Daten in Echtzeit von einer Cloud-Datenspeicherung zur Plattform gestreamt werden können und wie die Daten in Echtzeit für die Kundenbindung verwendet werden können. |
| 5. März 2021 | [Datenauffüllung für Dateningenieure](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1.dataingestion) | Kurs | Wie Sie Daten aus mehreren Quellen in Adobe Experience Platform importieren können und vieles mehr. |
| März 2021 | [Konfigurieren des Azure Blob-Ziels](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=de#destinations) | Video | Erfahren Sie, wie Sie die Schritte durchlaufen, die für die Einrichtung und Konfiguration des Zielorts für die Datenspeicherung von Blase unter [!UICONTROL Echtzeit-Kundendatenplattform] (Echtzeit-CDP) erforderlich sind. |
| 5. März 2021 | [Erste Schritte mit Offer decisioning für Marketingexperten](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1.offerdecisioning) | Kurs | Erfahren Sie mehr über den auf Adobe Experience Platform aufbauenden Anwendungsdienst [!UICONTROL Offer decisioning]. Dieser Kurs richtet sich an Marketingexperten, die Umsatz, Kundenerlebnis und Kundenbindung steigern möchten, indem sie ihren Kunden die besten Angebot liefern. |
| 5. März 2021 | [Streaming-Datenerfassung über API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-http-api.html) | Video | In diesem Video wird gezeigt, wie Daten mit dem HTTP API-Endpunkt in Echtzeit an Adobe Experience Platform gestreamt werden. |
| 5. März 2021 | [Überwachen der Dateneinbindung mithilfe der API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/data-monitoring.html?lang=de#data-ingestion) | Video | Erfahren Sie, wie Sie mithilfe der Benutzeroberfläche und API von Platform Daten überwachen und verfolgen, die in Adobe Experience Platform eingespeist werden. |
| 5. März 2021 | [Daten aus Datenbanken erfassen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-databases.html?lang=en#sources) | Video | In diesem Video wird erläutert, wie Sie einen Batch-Erfassungsvorgang von Daten aus einer Datenbankquelle in Adobe Experience Platform&#39;s Echtzeit-Profil Customer und Experience Data Lake auf nahtlose und skalierbare Weise durchführen können. |
| 5. März 2021 | [Daten von Amazon S3 erfassen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-amazon-s3.html) | Video | In diesem Video wird gezeigt, wie Sie die Erfassung von Daten aus Cloud-Datenspeicherung-Services in Adobe Experience Platforms Echtzeit-Profil und Datensee nahtlos und skalierbar gestalten können. |
| 5. März 2021 | [Daten aus Salesforce CRM erfassen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-salesforce-crm.html) | Video | In diesem Video wird gezeigt, wie sich die Erfassung von Daten aus CRM-Quellen in Adobe Experience Platform&#39;s Echtzeit-Profil und Data Lake nahtlos und skalierbar gestalten lässt. |
| 5. März 2021 | [Daten aus Adobe Analytics erfassen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html) | Video | Mit dem Adobe Analytics Source Connector können Sie Daten von Adobe Analytics mühelos in Adobe Experience Platform&#39;s Echtzeit-Customer Profil und Experience Data Lake streamen, und zwar nahtlos und skalierbar. |
| 5. März 2021 | [Grundlegendes zu Source Connectors](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/overview.html?lang=en#sources) | Video | In diesem Video erhalten Sie einen Überblick über die Experience Platform von Sources oder Source Connectors. |
| 5. März 2021 | [Adobe IO Console Export Postman Details](https://experienceleague.adobe.com/docs/platform-learn/tutorials/apis/postman.html) | Video | Erfahren Sie, wie Sie Experience Platform-APIs authentifizieren und darauf zugreifen. |
| 5. März 2021 | [Erläuterungen zur Dateneinbindung](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/understanding-data-ingestion.html#data-ingestion) | Video | Erfahren Sie mehr über die Datenerfassungsfunktionen von Experience Platform, mit denen Sie Ihre Daten zu einer offenen und skalierbaren Plattform für die Verwaltung von Echtzeit-Profilen zusammenführen können. |

## ![Symbol](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Verwenden Sie Adobe Experience Platform, um die Customer Journey in großem Maßstab über Erlebniskanäle hinweg zu orchestrieren, indem Sie die Bedürfnisse jedes Einzelnen in Echtzeit vorhersehen.

### Aktuelle Produktversionen

Version vom Februar 2021 - Erfahren Sie mehr über die neuesten Funktionen, Verbesserungen und Fehlerbehebungen in den [Versionshinweisen zur Journey Orchestration](https://docs.adobe.com/content/help/de-DE/journeys/using/release-notes/release-notes.html).

### Neue Journey Orchestration-Kurse und -Tutorials

Nachfolgend sind die im vergangenen Monat neu veröffentlichten Videos, Tutorials und Kurse aufgeführt.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| 16. März 2021 | [Profil-Aktion aktualisieren](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/update-profile-action.html?lang=en#building-a-journey) | Video | Erfahren Sie, wie Sie ein vorhandenes Experience Platform-Profil mit Informationen aktualisieren, die von einem Ereignis, einer Datenquelle oder einem bestimmten Wert stammen. |

### Weitere Ressourcen für Journey Orchestration

[Dokumentation](https://docs.adobe.com/content/help/de-DE/journeys/using/journey-orchestration-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) – [Videoanleitungen](https://docs.adobe.com/content/help/de-DE/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![](/assets/experience_platform_appicon_24.png) IconOffer-Entscheidungsfindung  {#offer-decisioning}

[!UICONTROL Offer Decisioning ist ein in Adobe Experience Platform integrierter Anwendungsdienst.] Verwenden Sie [!UICONTROL Offer decisioning], um Ihren Kunden das beste Angebot und Erlebnis für alle Berührungspunkte zur richtigen Zeit bereitzustellen.

### Aktuelle Produktversionen

Version vom Februar 2021 - Erfahren Sie mehr über die neuesten Funktionen in den [Offer decisioning Versionshinweisen](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new).

### Weitere Ressourcen für das Offer decisioning

[Dokumentation](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=de)  -  [Anleitungen zu Videos](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=en)

## ![Symbol](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Veröffentlichungsdatum: **25. März 2021**

* [Neue Funktionen in Adobe Analytics](#aa-features)
* [Neue Funktionen in Customer Journey Analytics](#cust-journey)
* [Fehlerbehebungen in Adobe Analytics](#aa-fixes)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [AppMeasurement](#appm)

### Neue Funktionen in Adobe Analytics {#aa-features}

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/de-DE/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| ----------- | ---------- | ------- |
| Aktualisierung der Datenreparatur-API | 25. März 2021 | Die Datenreparatur-API unterstützt jetzt Standardvariablen wie [!UICONTROL Seite] und [!UICONTROL IP-Adresse], Mobil- und Videovariablen sowie benutzerdefinierte [!UICONTROL props] und [!UICONTROL eVars].  Werte innerhalb von Variablen können gelöscht oder neue Werte festgelegt werden. Die API filtert jetzt auch Angebote nach URLs, Abfragen-Zeichenfolgen, at-Signaturen und mehr. |
| Analysis Workspace: [!UICONTROL Komponenten] > [!UICONTROL Benutzereinstellungen] | 25. März 2021 | Auf der Seite [!UICONTROL Komponenten] > [!UICONTROL Benutzervoreinstellungen] können Sie [!UICONTROL Analysis Workspace]-Einstellungen und zugehörige Komponenten für Ihren Benutzer verwalten. [!UICONTROL Die Benutzereinstellungen ] gelten für alle neuen Projekte und Bereiche. <br>**Hinweis:** Die folgenden Einstellungen wurden auf die Seite  [!UICONTROL Benutzereinstellungen ] verschoben:<ul><li>Berichtseinstellungen: Tausender-Trennzeichen (jetzt als _Zahlenformat_ bezeichnet)</li><li>Berichtseinstellungen: CSV-Trennzeichen</li><li>Workspace-Projekte: Hilfe > Tipps aktivieren</li><li>Workspace-Projekte: Leeres Bedienfeld _Beginn neuer Projekte mit dieser Option_</li></ul> |
| Analysis Workspace: [!UICONTROL Histogramm-Smart-Bucket-Prognose] | 25. März 2021 | [!UICONTROL Histogramm Smart Bucket ] Predictionhilft bei Histogrammen mit hoher Kardinalität, indem automatisch die richtige Breite und Anzahl der Behälter für Ihren Datenbogen identifiziert wird. Bei Metriken mit niedriger Kardinalität verhält sich die Visualisierung genauso wie zuvor. |
| [!UICONTROL Nutzungs-] LogAPI | 25. März 2021 | Dies ist eine neue Analytics-API der Version 2.0, die den programmatischen Zugriff auf dieselben Protokolldaten ermöglicht, die unter **[!UICONTROL Admin]** > **[!UICONTROL Protokoll]** > **[!UICONTROL Nutzungs- und Zugriffsprotokoll]** verfügbar sind. Weitere Details zu Authentifizierung, Schema und Beispielantwort sind [hier](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/usage-logs.md) verfügbar. |
| Unterstützung von Analytics-Dashboards für benutzerdefinierte Datumsbereiche | 22. April 2021 | Scorecard-Ersteller können benutzerdefinierte Datumsbereiche erstellen und auf mobile Scorecard-Projekte anwenden. Ersteller können aus vertrauten Arbeitsbereichen und Datumsbereich-Vorgaben für Mobilgeräte wählen oder einen benutzerdefinierten Datumsbereich erstellen. [Weitere Infos](https://experienceleague.adobe.com/docs/analytics/analyze/mobapp/curator.html#mobapp). |

### Neue Funktionen in Customer Journey Analytics {#cust-journey}

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| ----------- | ---------- | ----- |
| Unterstützung für [!UICONTROL Adobe Analytics-Dashboard] | 25. März 2021 | [!UICONTROL Customer Journey Analytics] (CJA) unterstützt jetzt den  [!UICONTROL Adobe Analytics Dashboards Scorecard ] Builder und die Mobile App. Auf diese Weise können Führungskräfte und Geschäftsbenutzer ihre Kanal-KPIs auf Basis von CJA-Daten anzeigen, indem sie dieselbe App verwenden, die sie möglicherweise bereits für Adobe Analytics verwenden. |
| Analysis Workspace: **[!UICONTROL Komponenten]** > **[!UICONTROL Benutzereinstellungen]** | 25. März 2021 | Auf der Seite [!UICONTROL Komponenten] > [!UICONTROL Benutzervoreinstellungen] können Sie [!UICONTROL Analysis Workspace]-Einstellungen und zugehörige Komponenten für Ihren Benutzer verwalten. [!UICONTROL Die Benutzereinstellungen ] gelten für alle neuen Projekte und Bereiche. <br>**Hinweis:** Die folgenden Einstellungen wurden auf die Seite  [!UICONTROL Benutzereinstellungen ] verschoben:<ul><li>Workspace-Projekte: Hilfe > Tipps aktivieren</li><li>Workspace-Projekte: Leeres Bedienfeld _Beginn neuer Projekte mit dieser Option_</li></ul> |
| Analysis Workspace: [!UICONTROL Histogramm-Smart-Bucket-Prognose] | 25. März 2021 | [!UICONTROL Histogramm Smart Bucket ] Predictionhilft bei Histogrammen mit hoher Kardinalität, indem automatisch die richtige Breite und Anzahl der Behälter für Ihren Datenbogen identifiziert wird. Bei Metriken mit niedriger Kardinalität verhält sich die Visualisierung genauso wie zuvor. |
| Unterstützung von Analytics-Dashboards für Customer Journey Analytics | 25. März 2021 | Die Analytics-Dashboard-App unterstützt jetzt Customer Journey Analytics. Benutzer mit Customer Journey Analytics können KPIs aus allen Daten, die in der Analytics-Dashboard-App in Adobe Experience Platform erfasst werden, überlagern. Mit Customer Journey Analytics können Sie mehrere Datenquellen für eine echte Ansicht des Kundenerlebnisses mit mehreren Kanälen kombinieren. Mit der Analytics-Dashboard-App erhalten Sie jederzeit und überall eine aktuelle, ganzheitliche Ansicht Ihres Unternehmens. [Weitere Infos](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/curator.html?lang=en#cja-dashboards). |

### Fehlerbehebungen in Adobe Analytics {#aa-fixes}

* Es wurde ein Problem behoben, bei dem dieser neue Inhaber nach dem Bearbeiten und Speichern des neuen Segments nicht in der Segment-Benutzeroberfläche angezeigt wurde. (AN-234502) AN-250970; AN-250286)
* Es wurde ein Fehler behoben, der dazu führte, dass eine App-Report Suite sowohl primäre Server-Aufrufe als auch primäre mobile Server-Aufrufe nutzte. (AN-244029)
* Es wurde ein Problem mit der langsamen Reaktionszeit der Benutzeroberfläche beim Öffnen von Projekten behoben.  (AN-242553)
* Es wurde ein Fehler behoben, der dazu führte, dass sich nach einem Upgrade auf die neueste Version nicht mehr bei [!UICONTROL Report Builder] anmelden konnte. (AN-248825)
* Problem mit Benutzerberechtigungen für Benutzer ohne Administratorrechte behoben: Ein Benutzer sollte über eine Berechtigung verfügen, solange diese mindestens einem seiner Profil in [!UICONTROL Admin Console] hinzugefügt wird. Beim Hinzufügen von Benutzern zu Profilen sollten nur die Berechtigungen, über die sie verfügen, erhöht werden, und es sollten keine bereits über andere Profil erworbenen Berechtigungen entfernt werden. (AN-242723)
* Es wurde ein Sprachenkodierungsfehler mit [!UICONTROL Datenfeeds] behoben. (AN-249862)
* Es wurde ein Problem behoben, durch das Benutzer nicht auf freigegebene [!UICONTROL Workspace]-Projekte zugreifen können. (AN-247814)
* Es wurde ein Problem behoben, bei dem [!UICONTROL Warnungsmeldungen] nicht mit der Anzahl der ausgelösten [!UICONTROL Vorschauen] übereinstimmten. (AN-249392) AN-250804)

#### Weitere Fehlerbehebungen in Adobe Analytics

AN-206099; AN-237460; AN-241803; AN-243735; AN-244081; AN-244615; AN-244687; AN-246832; AN-247227; AN-248237; AN-248478; AN-248852; AN-249115; AN-249140; AN-249216; AN-249275; AN-249538; AN-249963; AN-250034; AN-250270; AN-250320; AN-250338; AN-250377; AN-250378; AN-250557; AN-250609; AN-250614; AN-250615; AN-250885; AN-251088; AN-251137; AN-251190; AN-251192; AN-251193; AN-251301; AN-251496; AN-251545; AN-251734; AN-251735; AN-251744; AN-251816; AN-251982; AN-251972; AN-252051; AN-252073; AN-252105; AN-252409; AN-252640

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| ----------- | ---------- | ---------- |
| Hinweis auf bevorstehende Änderungen im Analytics-Menü | 24. März 2021 | Am 22. April 2021 werden wir die Dropdown-Menüs **[!UICONTROL Komponenten]**, **[!UICONTROL Tools]** und **[!UICONTROL Admin]** aktualisieren, um Leistungsgewinne zu erzielen. Alle diese Seiten stehen weiterhin unter den Links **[!UICONTROL Alle Komponenten]**, **[!UICONTROL Alle Tools]** und **[!UICONTROL Alle Admin]** zur Verfügung. Sie werden einfach aus dem Dropdown-Menü entfernt. Hier sind die Menüelemente, die aus dem Dropdown-Menü entfernt und auf ihre jeweilige Link-Seite platziert werden:<br><br> [!UICONTROL Komponenten]<ul><li>[!UICONTROL Lesezeichen]</li><li>[!UICONTROL Dashboards]</li><li>[!UICONTROL Zielgruppen]</li><li>[!UICONTROL Ereignisse des Kalenders]</li><li>[!UICONTROL Geplante Berichte]</li><li>[!UICONTROL Berichtseinstellungen]</li></ul>[!UICONTROL -Tools]<ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search&amp;Promote]</li></ul>[!UICONTROL Admin]<ul><li>[!UICONTROL Benutzerverwaltung]</li><li>[!UICONTROL Classification Importer]</li><li>[!UICONTROL Classification Rule Builder]</li><li>[!UICONTROL Data Sources]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL Unternehmenseinstellungen]</li><li>[!UICONTROL Protokolle]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL Code-Manager]</li><li>[!UICONTROL Nach IP ausschließen]</li><li>[!UICONTROL Traffic-Management]</li></ul> |
| [!UICONTROL Gleich wie SiteCatalyst VISTA Processing] = ON | 17. März 2021 | Am 17. Juni 2021 werden alle Report Suites aktualisiert, sodass [!UICONTROL Wie-SiteCatalyst VISTA-Verarbeitung] auf &quot;ON&quot;eingestellt ist. Diese Änderung wirkt sich auf den Berichte [!UICONTROL Data Warehouse] aus, indem die Daten entsprechend den Verarbeitungsregeln verarbeitet werden. Wenden Sie sich bei Fragen oder Klarstellungen an die Adobe Kundenunterstützung. |
| EOL of [!UICONTROL Full Processing] [!UICONTROL Data Sources] | 10. März 2021 | Die Adobe plant, [!UICONTROL Volle Verarbeitung] [!UICONTROL Data Sources] in Zukunft zu deaktivieren. Ab dem 25. März 2021 können keine neuen Importe dieser Art mehr erstellt werden. Verwenden Sie [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md), um diesen Datentyp zu importieren. [Weitere Infos](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html) |
| Optionen zur Landingpage von Reports &amp; Analytics | 19. Februar 2021 | Am 25. März 2021 werden Optionen zum Festlegen neuer Reports &amp; Analytics-Dashboards sowie anderer Inhalte, wie Ihrer Adobe Analytics-Landingpage, entfernt. Wenn Sie zuvor eine Reports &amp; Analytics-Seite als benutzerdefinierte Landingpage festgelegt haben, funktioniert sie so lange weiter, bis Ihre Landingpage unter [!UICONTROL Benutzereinstellungen] geändert wird. |
| Ende von Ad Hoc Analysis | 2021. Januar | [!UICONTROL Ad Hoc Analysis] wurde am 1. März 2021 eingestellt. Weiterführende Informationen finden Sie unter [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |
| Ende der Nutzungsdauer von drei Analytics-API-Services | 6. Januar 2021 | Am 30. April 2021 haben die folgenden Analytics Legacy-API-Services das Ende ihrer Nutzungsdauer erreicht und werden eingestellt. Alle aktuellen Integrationen, die mit diesen Services erstellt wurden, funktionieren ab diesem Tag nicht mehr.<ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Wir haben ein Dokument mit [Häufig gestellten Fragen (FAQ) zum Ende der Nutzungsdauer (EOL) der Legacy-API](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) bereitgestellt, das Ihre Fragen beantworten und Anleitungen zum weiteren Vorgehen geben soll. API-Integrationen, die diese Dienste nutzen, können zu den [Analytics-REST-APIs 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) oder den [Analytics-APIs 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) migrieren. Ältere OAuth-Konten können zu einem [Adobe IO](https://console.adobe.io/home?mv=email#) Analytics-Integrationskonto migrieren, das für den Zugriff auf sowohl Analytics-APIs 1.4 als auch Analytics-APIs 2.0 verwendet werden kann. |
| Ende von Adobe Data Connectors | 13. Juli 2020 | Adobe [!UICONTROL Data Connectors] basieren auf einer älteren Technologie, die nicht mehr funktionsfähig ist oder unterstützt wird. Ein neuer Standard ist im [Adobe Exchange-Partner-Programm](https://partners.adobe.com/exchangeprogram/experiencecloud) verfügbar. Sie können diesen Standard für jede Integration verwenden, sodass dies weiterhin angeboten und unterstützt werden kann. Das offizielle Enddatum ist der 1. August 2021. [Weitere Infos...](https://docs.adobe.com/content/help/de-DE/analytics/import/dataconnectors/data-connectors-eol.html) |

### AppMeasurement {#appm}

Die neuesten Aktualisierungen zu AppMeasurement-Versionen finden Sie in den Versionshinweisen zu [AppMeasurement für JavaScript](https://docs.adobe.com/content/help/de-DE/analytics/implementation/appmeasurement-updates.html).

### Analytics-Hilferessourcen

* [Adobe Analytics-Produktdokumentation und Tutorials](https://experienceleague.adobe.com/docs/analytics.html?lang=de-DE)

## ![Symbol](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Fehlerbehebungen und Verbesserungen beim Audience Manager.

### Fehlerbehebungen und Verbesserungen {#aam-fixes-and-improvements}

* Es wurde ein Problem im [Bericht zum Onboarding-Status](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html?lang=de) behoben. Bei diesem Problem bestand eine Diskrepanz zwischen den Daten im Bericht und denen in der Datei, die von einem Onboardingpartner hochgeladen wurden. (AAM-57415)
* Es wurde ein Fehler behoben, der dazu führte, dass die Segmentzuordnung für **[!UICONTROL Benutzerbasierte Ziele]** nicht korrekt überprüft wurde. (AAM-56631)
* Es wurde ein Problem behoben, durch das einige Benutzer nicht auf **[!UICONTROL Audiencen-Berichte]** zugreifen konnten. (AAM-57412)
* Es wurde eine [!UICONTROL Verwundbarkeit der Ausführung von Remote-Code] gepatcht, die von Angreifern für den Zugriff auf sensible Daten verwendet werden könnte. (AAM-57495)

### Audience Manager-Kurse und -Tutorials {#tutorials-aam}

Neue Videos, Tutorials oder Kurse, die für Audience Manager veröffentlicht wurden.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| 19. März 2021 | [Verstehen der Datenverwaltung in Echtzeit-CDP für Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-data-gov-for-aam-users.html) | Video | Erfahren Sie mehr über die Funktionen zur Datenverwaltung in [!UICONTROL Echtzeit-Kundendatenplattform]. |
| 19. März 2021 | [Eine Geschichte von zwei Wahrnehmungen - Marken vs Verbraucher](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/brands-vs-consumers.html) | Video | In diesem Webinar bringt Adobe das Verständnis und die Bereitschaft von Werbetreibenden und Herausgebern für eine Zukunft ohne Cookies, die Auswirkungen auf ihre Anwendungsfälle und ihre Wahrnehmung des Ökosystems im weiteren Sinne zum Ausdruck. |
| 5. März 2021 | [10 Überlegungen zum verantwortungsvollen Data Management](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/ten-considerations-for-responsible-customer-data-management.html) | Ereignis | Hear from Adobe and Scotiabank Digital über wichtige Überlegungen für verantwortungsvolles Data Management. |
| 19. März 2021 | [Die Zukunft des Data Managements und die sich verändernde Umgebung](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/the-future-of-data-management-and-the-changing-environment.html) | Ereignis | In diesem Webinar sehen Sie, wie Adobe und 451 Research über die Zukunft der Technologie und Daten denken, um die neue Marketing-Umgebung und beginnen Sie, Ihr Geschäft auf die Zukunft des Data Managements vorzubereiten. |
| 21. März 2021 | [Grundlegendes zu Schemas und XDM in Echtzeit-CDP für Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html?lang=en#other-integrations) | Video | Wenn Sie von der Audience Manager- zur Echtzeit-Kundendatenplattform (Echtzeit-CDP) wechseln, werden Sie auf einige neue Konzepte und Verfahren stoßen. Schemas und XDM fallen in diese Kategorie. In diesem Video werden diese Konzepte erläutert. |
| 17. März 2021 | [Signale in Echtzeit-CDP für Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-signals-for-aam-users.html) | Video | Dieses Video ist für Audience Manager gedacht, die auf die Echtzeit-Kundendatenplattform (Echtzeit-CDP) umstellen, und beschreibt, wie Signale (Schlüssel-Wert-Paare), die Sie in Audience Manager zum Erstellen von Eigenschaften verwenden, in Platform verwendet werden. |
| 12. März 2021 | [Grundlegendes zu Schemas und XDM in Echtzeit-CDP für Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html) | Video | Wenn Sie von der Audience Manager- zur Echtzeit-Kundendatenplattform (Echtzeit-CDP) wechseln, werden Sie auf einige neue Konzepte und Verfahren stoßen. Schemas und XDM fallen in diese Kategorie. In diesem Video werden diese Konzepte erläutert. |
| 12. März 2021 | [Erläuterungen zur Webdateningestion in Echtzeit-CDP für Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-web-ingestion-for-aam-users.html) | Video | Lernen Sie die Konzepte für die Einbindung von Website-Daten in die Echtzeit-Kundendatenplattform (Echtzeit-CDP) kennen und erfahren Sie, wo der Audience Manager Data Connector passt und wie die Daten direkt über das Web-SDK in Echtzeit-CDP übertragen werden können. |
| 3. März 2021 | [Segmente in Echtzeit-CDP für Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-segments-for-aam-users.html?lang=en#other-integrations) | Video | Erfahren Sie, welche Unterschiede es bei der Segmenterstellung und Segmenterstellung zwischen Audience Manager- und Echtzeit-CDP gibt. |
| 3. März 2021 | [Eigenschaften in Echtzeit-CDP für Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-traits-for-aam-users.html?lang=en#other-integrations) | Video | Erfahren Sie, welche Eigenschaften in Audience Manager vorhanden sind und wie die Entsprechung in Echtzeit-CDP lautet. |
| 3. März 2021 | [Einführung in die CDP für Audience Manager in Echtzeit](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-1pd-ingestion-for-aam-users.html?lang=en#other-integrations) | Video | Erfahren Sie mehr zur Offline-Datenerfassung von Erstanbietern in Echtzeit-Kundendatenplattform (Echtzeit-CDP). Erfahren Sie mehr über die wichtigsten Unterschiede zwischen den beiden Produkten in Bezug auf die Datenerfassung und zeigen Sie, wie der Data Connector-Audience Manager als Stopp-Lücke verwendet werden kann, bis die Prozesse auf eine Echtzeit-CDP umgestellt wurden. |
| 1. März 2021 | [Geschäftliche Vermarktung Ihrer eigenen Audiencen durch Angebot auf Audience Marketplace](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/audience-marketplace/selling-data/commercialize-owned-audiences-on-marketplace.html?lang=en#audience-marketplace) | Video | Erfahren Sie, wie Sie Ihre Daten als privaten oder öffentlichen Datenfeed im Audience Marketplace einrichten, sodass Sie zu einem Datenanbieter mit Daten von Zweitanbietern oder Drittanbietern werden. |
| März 2021 | [Aktivierung von Daten in Audience Manager erstellen und verwalten](https://experienceleague.adobe.com/?lang=de&amp;recommended=AudienceManager-U-1-2020.4) | Kurs | Erfahren Sie in diesem Kurs alles über die Aktivierung Ihrer Audiencen, z. B. das Senden von Audiencen an Zielpartner, um das Erlebnis für Ihre Endbenutzer anzupassen. Lernen Sie die Grundlagen von Zielen, wie Sie das richtige Ziel auswählen und wie Sie Daten zur Audience an Social-Netzwerkziele vorbereiten und senden können, basierend auf Menschen, nicht auf Cookies. |
| März 2021 | [Audience Manager Advanced Skills](https://experienceleague.adobe.com/?lang=de&amp;recommended=AudienceManager-U-1-2020.5) | Kurs | Sobald Sie die Grundlagen des Audience Managers beherrscht haben, nehmen Sie diesen Kurs in Anspruch, um zu erfahren, wie Sie Ihr Audience Management auf die nächste Stufe bringen. Erfahren Sie, wie Sie AI mit algorithmischen Modellen einsetzen, wie Sie mit den Profil Merge Rules Ihre Kunden als Mitarbeiter anstatt als Geräte verstehen und wie Sie die Verwendung des DMP erweitern können. |

## ![Symbol](/assets/aem.png) Adobe Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Experience Manager. Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

>[!NOTE]
>
>Adobe empfiehlt, die Seite [Experience Manager-Versions-Updates und -Roadmaps](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=de) zu besuchen, um auf dem Laufenden zu bleiben.

### Produktversionen

* **AEM 6.5.8.0**
AEM 6.5, Service Pack 8 (6.5.8.0, veröffentlicht am 11. März 2021) ist das wichtigste Update seit der allgemeinen Verfügbarkeit von AEM 6.5 im April 2019 und beinhaltet neue Funktionen, wichtige Kundenverbesserungen und Steigerungen bei der Leistung, Stabilität und Sicherheit.
   * [Versionshinweise](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=de#service-pack)
   * [Versionsfreigaben von AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=de#forms-updates)

* **AEM 6.4.8.4**
AEM 6.4, Service Pack 8, Cumulative Fix Pack 4 (6.4.8.4 veröffentlicht am 25. Februar 2021) ist ein wichtiges Update, das einige interne und kundenspezifische Fehlerbehebungen seit der allgemeinen Verfügbarkeit von AEM 6.4, Service Pack 8 (6.4.8.0), März 2020 enthält.
   * [Versionshinweise](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=de)
   * [Versionsfreigaben von AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **Adobe Experience Manager as a Cloud Service**

   Was ist neu an Experience Manager als Cloud Service?

   * **Experience Manager-Sites als Cloud Service**

      * [Die RemotePage-Komponente](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html?lang=en): Zusätzliche Unterstützung für das Anzeigen und Bearbeiten externer SPA in Experience Manager.
      * [Bearbeiten eines externen SPA in Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html?lang=en): Es wurde die Möglichkeit hinzugefügt, eine eigenständige Einzelseitenanwendung in eine Experience Manager-Instanz hochzuladen, bearbeitbare Inhaltsabschnitte hinzuzufügen und das Authoring zu aktivieren.
   * **Experience Manager Assets as a Cloud Service**

      * Experience Manager Assets als Cloud Service ist berechtigt, über eine vorkonfigurierte Brand Portal-Instanz zu verfügen. Der Cloud Manager-Benutzer kann das Markenportal auf Experience Manager-Assets als Cloud Service aktivieren. Siehe [Aktivieren des Markenportals mithilfe von Markenportal](https://experienceleague.corp.adobe.com/docs/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html).
      * Unternehmen können jetzt Assets über das Markenportal beziehen. Die Asset-Sourcing-Funktion nutzt Brand Portal, um Kunden bei der Interaktion mit Agenturbenutzern zu unterstützen, um Assets für neue Marketing-Kampagnen, Fotoaufnahmen und Projekte zu beziehen. Siehe [Übersicht über die Asset-Beschaffung](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/brand-portal-asset-sourcing.html?lang=en) im Markenportal-Handbuch.
      * Der Bericht &quot;Nutzung des Markenportals&quot;zeigt jetzt nur die aktiven Benutzer an. Die inaktiven Benutzer werden jetzt nicht angezeigt. Aktive Benutzer sind Benutzer, deren Konto einem Profil in der Admin Console zugewiesen ist. Siehe [Arbeiten mit Berichten](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/admin-tools/brand-portal-reports.html?lang=en) im Markenportal-Handbuch.
      * Im Markenportal wird eine neue Downloadeinstellung eingeführt, mit der Sie separate Ordner für jedes Asset erstellen können, wenn Sie Ordner, Sammlungen usw. herunterladen. Siehe [Asset-Download](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/download/brand-portal-download-assets.html?lang=en) in **Herunterladen von Assets aus dem Markenportal** im Markenportal-Handbuch.
   * **Experience Manager Forms als Cloud Service**

      AEM Forms hat im Laufe der Jahre vielen Unternehmen dabei geholfen, großartige Einstiegs- und Registrierungserfahrungen zu machen. Diese Erlebnisse haben Unternehmen dabei unterstützt, Interessenten in Verkäufe umzuwandeln, erfasste Kundendaten zu verarbeiten, reaktionsfähige Erlebnisse basierend auf dem Profil der Audience bereitzustellen und vieles mehr. AEM Forms ist jetzt als Cloud-Dienst verfügbar.

      Sie können AEM Forms als Cloud Service verwenden, um digitale Formulare zu erstellen, Formulare mit vorhandenen Datenquellen zu verbinden, Formulare mit Adobe Sign zu integrieren, um Formulare e-Signaturen hinzuzufügen, Dokument aus Datensatz (DoR) zu generieren, um gesendete Formulare als PDF-Dateien zu archivieren. Der Dienst kann auch Ihre vorhandenen PDF forms in digitale Formulare konvertieren. Zusätzlich zu den standardmäßigen AEM Forms-Funktionen bietet der Dienst mehrere Cloud-native Funktionen wie automatische Skalierung, kostenlose Ausfallzeiten für Upgrades und Cloud-native Umgebung für die Entwicklung. Lesen Sie [diesen Blog-Beitrag](https://blog.adobe.com/en/publish/2021/03/11/experience-manager-forms-as-a-cloud-service.html), um mehr über die Funktionen und Funktionen von AEM Forms als Cloud Service zu erfahren.

      Sie können sich an Ihren Kundenbetreuer wenden, um eine Demo zu erhalten oder sich für den Service zu registrieren.


   * **Experience Manager Commerce als Cloud Service**

      * Produkt-Experience-Management: Richten Sie Produktkatalogseiten einzeln mit Erlebnisfragmenten ein.
      * Die Eigenschaften der Produktkonsole wurden erweitert, um verknüpfte Assets und Erlebnisfragmente anzuzeigen, einschließlich Aktionen zum schnellen Navigieren zum zugehörigen Inhalt.
      * CIF Venia-Referenzseite - 2021.02.24, die die neuesten CIF-Kernkomponenten Version 1.8.0 enthält. Weitere Informationen finden Sie unter [CIF Venia Reference Site 2021.02.24](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.24).
      * Version 1.8.0 der CIF-Kernkomponenten Weitere Informationen finden Sie unter [CIF-Kernkomponenten 1.8.0](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.8.0).
   * **Cloud Manager**

      * Kunden mit Umgebung, die über bereits vorhandene Konfigurationen für benutzerdefinierte Domänennamen für [IP-Zulassungslisten](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/ip-allow-lists/check-ip-allow-list-status.html?lang=en#pre-existing-cdn), [SSL-Zertifikate](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/manage-ssl-certificates/check-status-ssl-certificate.html?lang=en#pre-existing-cdn) und [Benutzerspezifische Domänennamen](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/custom-domain-names/check-domain-name-status.html?lang=en#pre-existing-cdn) verfügen, erhalten jetzt eine Meldung über ihre zuvor vorhandenen Konfigurationen. Sie können sich auch über die Benutzeroberfläche selbst bedienen.
      * Benutzer mit erforderlichen Berechtigungen können jetzt ein Programm bearbeiten, sodass sie Folgendes selbstständig ausführen können:
         * hinzufügen Sites-Lösung auf ein vorhandenes Programm mit Assets oder umgekehrt.
         * Entfernen Sie Sites oder Assets aus einem vorhandenen Programm mit sowohl Sites als auch Assets.
         * hinzufügen zweite, nicht verwendete Lösungsberechtigung entweder für ein vorhandenes Programm oder als neues Programm.
      * **AEM Push-** Aktualisierungsbildschirm wird jetzt sowohl für  *Pipeline-* Ausführung als auch für  ** Aktivitäten angezeigt.
      * Wenn eine Umgebung ausgeblendet wird, aber auch ein Experience Manager-Update verfügbar ist, hat der Status **Hibernated** Vorrang vor **Update available**.
      * Die Benutzer können nun ihre Cloud Manager-Rollen anzeigen, indem sie **Ansicht Cloud Manager-Rollen** auswählen, nachdem sie zum Symbol &quot;User Profil&quot;(oben rechts) von Unified Shell navigiert sind.
      * Die Beschriftung **Antrag auf Genehmigung** wurde zur besseren Klarheit in **Produktionsgenehmigung** umbenannt.
      * Die Beschriftung **Version** wurde im Bildschirm &quot;Produktions-Pipeline-Ausführung&quot;in **Git-Tag** umbenannt.
      * Die Beschriftungen, die das Verhalten definieren, wenn wichtige Metriken den definierten Schwellenwert nicht erreichen, wurden umbenannt, um ihr wahres Verhalten widerzuspiegeln: **Sofort abbrechen** und **Sofort genehmigen**.
      * Die Listen zum Entfernen von Klassen und Methoden wurden auf der Grundlage der Version `2021.3.4997.20210303T022849Z-210225` des Experience Manager Cloud Service-SDK aktualisiert.
      * Die Cloud Manager-Produktionsleitung bietet jetzt die Funktion [Benutzerdefinierte UI-Tests](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/functional-testing.html?lang=en#custom-ui-testing).




### **Community**

* **Adobe Developers Live 2021 | Komplette Session-Liste**

   [Hier ](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-2021-complete-session-list/m-p/394595#M27875) finden Sie eine zusammengefasste Liste aller Experience Manager-Sitzungen in  **Adobe Developers Live**.

* **Gipfeltreffen der Adobe 2021 | Liste zur vollständigen Experience Manager-Sitzung**

   [Es ](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-complete-aem-session-list/td-p/398344) handelt sich um eine zusammengefasste Liste aller Tagungen des Experience Managers, die auf dem Gipfeltreffen  **Adobe 2021** stattfinden.

### Versionsinformationen zu Experience Manager

Die nachfolgend aufgeführten Seiten umfassen alle Versionshinweise zu Experience Manager:

* [Versions-Updates und Roadmap für Experience Manager](https://docs.adobe.com/content/help/de-DE/experience-manager-release-information/aem-release-updates/home.html)
* [Versionsinformationen für Experience Manager as a Cloud Service](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/release-notes/home.html)
* [Versionshinweise für Experience Manager Cloud Manager](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Versionshinweise zum Dienst für die automatische Formularkonvertierung](https://docs.adobe.com/content/help/de-DE/aem-forms-automated-conversion-service/using/release-notes.html)
* [Versionshinweise für Experience Manager 6.5 Service Pack](https://docs.adobe.com/content/help/de-DE/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Versionshinweise für Experience Manager 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/de-DE/experience-manager-64/release-notes/cfp-release-notes.html)
* [Versionshinweise für Experience ManagerAssets Dynamic Media](https://docs.adobe.com/content/help/de-DE/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Versionshinweise für Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Versionshinweise zum Experience Manager-Desktop-Programm ](https://docs.adobe.com/content/help/de-DE/experience-manager-desktop-app/using/release-notes.html)
* [Versionshinweise für Experience Manager Dispatcher](https://docs.adobe.com/content/help/de-DE/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Versionshinweise zu Livefyre](https://docs.adobe.com/content/help/de-DE/livefyre/using/release-notes/c-rn.html)

### Experience Manager-Kurse und -Tutorials

Nachfolgend sind die im vergangenen Monat neu veröffentlichten Videos, Tutorials und Kurse aufgeführt.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| März 2021 | [Content Versand auf Experience Manager Cloud Service](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/content/feb2021/content-delivery.html#content) | Ereignis | Adobe Experience Manager als Cloud Service verfügt über eine leistungsstarke vorkonfigurierte Content Versand-Architektur. Optimierte Content Versand-Konfigurationen |
| März 2021 | [Migrieren von Helpxartikeln zu Typen von Forms und Dokumenten zu ExL](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/pdf-forms-and-documents.html?lang=en#document-services) | Artikel | Ein Artikel, der die verschiedenen Typen von PDF forms und Dokumenten erläutert. |
| März 2021 | [Bereitstellung der Produktion mit einer AEM Publishing Umgebung](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/production-deployment.html#graphql) | Tutorial | Richten Sie eine lokale Umgebung ein, um zu simulieren, wie Inhalte von einer Autoreninstanz an eine Veröffentlichungsinstanz verteilt werden. Erstellen Sie einen Produktionsaufbau einer React-App, die so konfiguriert ist, dass Inhalte aus der AEM Publish-Umgebung mit den GraphQL-APIs verwendet werden. Auf diesem Weg lernen Sie, wie Sie die Umgebung effektiv nutzen und die AEM CORS-Konfigurationen aktualisieren können. |
| März 2021 | [Headless-Content-Management mit GraphQL-APIs](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.headless) | Kurs | Erfahren Sie, wie AEM GraphQL-APIs und kopflosen Funktionen genutzt werden können, um Erlebnisse in einer externen App zu aktivieren. |
| März 2021 | [Starts - Video zu Funktionen](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/launches.html) | Video | Die Starts in AEM Sites bieten eine Möglichkeit, Website-Inhalte für zukünftige Versionen zu erstellen, zu erstellen und zu überprüfen. Während der Gründung der Produktion kann sich die Produktions-Website weiter entwickeln und sich täglich ändern, wie es normalerweise der Fall ist. |
| März 2021 | [Verknüpfen und Trennen von Assets - VideoText](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html?lang=de) | Video | Erfahren Sie, wie Sie in AEM Beziehungen zwischen Assets herstellen und verwalten. |
| März 2021 | [Authentifizierung für AEM as a Cloud Service aus einer externen Anwendung](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) | Kurs | Erfahren Sie, wie eine externe Anwendung mithilfe von Zugriffstoken für lokale Entwicklung und Dienstberechtigungen programmgesteuert authentifiziert AEM als Cloud Service über HTTP authentifizieren kann. |
| März 2021 | [Ausfüllen und Signieren mehrerer Formulare in einem Hypothekenantrag](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.7.forms&amp;lang=de-DE) | Kurs | Signieren Sie ein Paket von Dokumenten nahtlos mit der AEM Forms- und Sign-Integration. Die im Formular eingegebenen Daten können zum Vorausfüllen nachfolgender Formulare im Paket verwendet werden. |
| März 2021 | [Version/Zeitverkrümmung in AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/timewarp-feature-video-use.html) | Video | &quot;TimeWarp&quot;ist eine Funktion von Adobe Experience Manager Sites, mit der Autoren den Status einer Seite zu einem bestimmten Zeitpunkt in der Vergangenheit schnell überprüfen können. |
| März 2021 | [Stiftung - Workflow-Management](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-workflow-management.html?lang=en#workflow) | Video | In diesem Video werden Arbeitsablaufmodelle verwendet, um diesen Satz von Funktionen zu demonstrieren. Sie gelten jedoch auch für AEM Launchers. |
| März 2021 | [Erlebnisfragmentblöcke](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/building-blocks.html) | Video | Bausteine sind eine Unterfunktion von Erlebnisfragmenten. Mithilfe von Bausteinen können Inhaltsersteller Komponenten in verschiedenen Varianten von Erlebnisfragmenten wiederverwenden. |
| März 2021 | [Workflow-Editor](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-the-workflow-editor.html?lang=en#workflow) | Video | Der Workflow ermöglicht die Verwaltung von Geschäftsprozessen im Experience Manager und wird für die automatische Verarbeitung von Inhalten sowie zur Erleichterung von Governance- und Prozessabläufen verwendet, die eine persönliche Entscheidungsfindung erfordern. |
| März 2021 | [Geschlossene Benutzergruppen in AEM Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/closed-user-groups.html) | Video | Closed User Groups (CUGs) ist eine Funktion, mit der der Zugriff auf Inhalte auf eine bestimmte Benutzergruppe auf einer veröffentlichten Site eingeschränkt wird. In diesem Video wird gezeigt, wie mit Adobe Experience Manager Assets geschlossene Benutzergruppen verwendet werden können, um den Zugriff auf einen bestimmten Asset-Ordner zu beschränken. |
| März 2021 | [Berichte ](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/asset-reports.html) | Video | Erfahren Sie, wie AEM Assets ein Berichte-Framework auf Unternehmensebene bereitstellt, das durch eine intuitive Benutzererfahrung für große Repositorys skaliert wird. |
| März 2021 | [Smart-Tags für Bilder mit AEM Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/image-smart-tags.html) | Video | Smart-Tags für Bilder erweitern AEM Suchfunktionen, indem sie automatisch und intelligent Metadaten-Tags zu Bild-Assets hinzufügen, die auf dem Bildinhalt basieren. |
| März 2021 | [Metadaten-Kaskadierung, Sichtbarkeit](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/cascade-metadata-feature-video-use.html) | Video | Erfahren Sie mehr über die neuen dynamischen Regeln für Feldanforderungen, Sichtbarkeit und Kontextoptionen. Im Video werden auch die Schritte erläutert, die ein Administrator ausführen muss, um diese Regeln auf ein benutzerdefiniertes Metadaten-Schema anzuwenden. |
| März 2021 | [Projektmanager](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/projects/use-project-masters.html?lang=en#delete-project-masters) | Video | Das Löschen eines Übergeordnet erstellten Projekts führt zu unbrauchbaren abgeleiteten Projekten. |
| März 2021 | [Anpassen der Seiteneigenschaften](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/developing/page-properties-technical-video-develop.html) | Video | Erstellen Sie ein technisches Video zur optimalen Erweiterung und Anpassung der Seiteneigenschaften. |
| März 2021 | [Übersetzen von Inhaltsfragmenten](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-translation-feature-video-use.html) | Video | Erfahren Sie, wie Inhaltsfragmente mit Adobe Experience Manager lokalisiert und übersetzt werden können. Assets mit gemischten Medien, die mit einem Inhaltsfragment verknüpft sind, können ebenfalls extrahiert und übersetzt werden. |
| März 2021 | [Experience Fragments](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/experience-fragments-feature-video-use.html) | Video | Erfahren Sie, wie Erlebnisfragmente Autoren von Inhalten die Wiederverwendung von Inhalten über Kanal hinweg ermöglichen, einschließlich Siteseiten und Drittanbietersystemen. |
| März 2021 | [Verbesserte Suchverstärkung](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/search-and-discovery/search-boost.html?lang=de) | Video | Erfahren Sie mehr über Suchverstärkung. |

### Andere Hilferessourcen für Experience Manager

* [Handbücher für Experience Manager as a Cloud Service](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/landing/home.html)
* [Experience Manager 6.5 – Training und Support, Startseite](https://helpx.adobe.com/de/support/experience-manager/6-5.html)
* [Experience Manager 6.4 – Training und Support, Startseite](https://helpx.adobe.com/de/support/experience-manager/6-4.html)
* [Experience Manager 6.3 – Training und Support, Startseite](https://helpx.adobe.com/de/support/experience-manager/6-3.html)
* [Experience Manager 6.2 – Training und Support, Startseite](https://helpx.adobe.com/de/support/experience-manager/6-2.html)
* [Cloud Manager-Benutzerhandbuch](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Ältere Versionen der Dokumentation zu Experience Manager](https://helpx.adobe.com/de/experience-manager/aem-previous-versions.html)
* [Startseite der Hilfe zu Dynamic Media Classic](https://docs.adobe.com/content/help/de-DE/dynamic-media-classic/using/home.html)

## ![Symbol](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Aktuelle Produktversionen

Erfahren Sie mehr über die neuesten Funktionen, Verbesserungen und Fehlerbehebungen, die veröffentlicht wurden:

* [Versionshinweise zu Campaign Standard](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-notes.html)
* [Versionshinweise zu Campaign Classic](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/release-notes/latest-release.html).

>[!IMPORTANT]
>
>Erfahren Sie mehr über [erforderliche Konfigurationsaktualisierungen](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/acc-config-updates.html?lang=en) für Adobe Campaign Classic.

### Neue Campaign-Kurse und -Tutorials

Nachfolgend sind die im vergangenen Monat neu veröffentlichten Videos, Tutorials und Kurse aufgeführt.

| Veröffentlicht | Name | Lösung | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| 23. Februar 2021 | [Lieferbarkeit - Metriken für die Lieferbarkeit](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/metrics-overview.html) | Campaign Classic/Standard | Erfahren Sie mehr über die wichtigsten zu überwachenden Bereitstellungsmetriken und wie sie zur Identifizierung eines Reputationsproblems verwendet werden. |
| 23. Februar 2021 | [Lieferbarkeit - Absprünge](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bounces.html) | Campaign Classic/Standard | Erfahren Sie mehr über die verschiedenen Arten von Absprüngen. |
| 23. Februar 2021 | [Lieferbarkeit - Beschwerden](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/complaints.html) | Campaign Classic/Standard | Erfahren Sie mehr über Beschwerden, die registriert werden, wenn ein Benutzer angibt, dass eine E-Mail unerwünscht ist oder unerwartet gesendet wurde. |
| 23. Februar 2021 | [Lieferbarkeit - Spam-Fallen](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/spam-traps.html) | Campaign Classic/Standard | Erfahren Sie mehr über die verschiedenen Arten von Absprüngen. |
| 23. Februar 2021 | [Auslieferbarkeit - Blockierung](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bulking-and-blocking.html) | Campaign Classic/Standard | Erfahren Sie, warum ISPs E-Mail-Nachrichten in Bulk-Ordnern platzieren oder blockieren. |
| 23. Februar 2021 | [Lieferbarkeit - Transition - Infrastruktur](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/infrastructure.html) | Campaign Classic/Standard | Erfahren Sie, was zum ordnungsgemäßen Aufbau einer E-Mail-Infrastruktur erforderlich ist. |
| 23. Februar 2021 | [Lieferbarkeit - Interaktion](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/engagement.html) | Campaign Classic/Standard | Erfahren Sie mehr über die verschiedenen Einsatzformen und warum Interaktion für die Lieferbarkeit von Bedeutung ist. |
| 23. Februar 2021 | [Lieferbarkeit - Transition: Targeting-Kriterien](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/targeting-criteria.html) | Campaign Classic/Standard | Erfahren Sie, wie Sie einen guten Ruf von get-go aus aufbauen können, um effektiv Vertrauen zu schaffen, bevor Sie Ihre weniger engagierten Audiencen einführen. |
| 23. Februar 2021 | [Lieferbarkeit - Transition - ISP-spezifische Überlegungen bei der IP-Erwärmung](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/isp-specific-considerations-during-ip-warming.html) | Campaign Classic/Standard | Erfahren Sie mehr über die verschiedenen Regeln und Methoden, die ISP-Anbieter haben, um sich ihren Traffic anzusehen. |
| 24. Februar 2021 | [Lieferbarkeit - erste Impressionen - Einführung](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/introduction.html) | Campaign Classic/Standard | Erfahren Sie, wie Sie sich für ein erfolgreiches E-Mail-Programm einrichten können, indem Sie einen guten ersten Eindruck machen. |
| 24. Februar 2021 | [Lieferbarkeit - Transition: Volumen](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/volume.html) | Campaign Classic/Standard | Verstehen Sie, wie das Senden von Volumen die Zustellbarkeit Ihrer E-Mail-Kampagnen beeinflusst. |
| 24. Februar 2021 | [Auslieferbarkeit - Erste Impressionen - Ausbau der Adresserfassung und Liste](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/address-collection-and-list-growth.html) | Campaign Classic/Standard | Erfahren Sie, welche Quellen für neue E-Mail-Adressen am besten geeignet sind, wie Sie eine hohe Datenqualität sicherstellen und wie Sie sich an die rechtlichen Richtlinien anpassen können. |
| 25. Februar 2021 | [Auslieferbarkeit - Erste Impressionen - Begrüßungs-E-Mail](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/welcome-emails.html) | Campaign Classic/Standard | Erfahren Sie, was die Schlüsselelemente Ihrer Begrüßungsstrategie sein sollten. |
| 25. Februar 2021 | [Lieferbarkeit - Transition: Wechseln zwischen E-Mail-Plattformen](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/switching-email-platforms.html) | Campaign Classic/Standard | Erfahren Sie, wie Sie beim Wechseln von E-Mail-Plattformen reibungslos Transitionen durchführen können. |
| 26. Februar 2021 | [Lieferbarkeit - Best Practices für die optimale Lieferbarkeit](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/content-best-practices-for-optimal-delivery.html) | Campaign Classic/Standard | Tipps zur Optimierung des Inhalts Ihrer E-Mail für die Zustellbarkeit. |
| 26. Februar 2021 | [Lieferbarkeit - Absenderbeständigkeit](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/sender-permanence.html) | Campaign Classic/Standard | Erfahren Sie, warum es wichtig ist, ein konsistentes Senden-Volumen zu erstellen. |
| 26. Februar 2021 | [Lieferbarkeit - Laufende Überwachung](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/ongoing-monitoring.html) | Campaign Classic/Standard | Erkennen Sie, auf welche Probleme Sie achten müssen, wenn Sie Ihre Versand überwachen. |
| 26. Februar 2021 | [Umsetzbarkeit - praktische Umsetzung](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/putting-it-in-practice.html) | Campaign Classic/Standard | Vier Eckpfeiler für den Erfolg. |
| 10. März 2021 | [Best Practices für Führungskräfte, Geschäftsbenutzer und Administratoren](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.deliverability) | Campaign Classic | Erfahren Sie mehr über die wichtigsten Begriffe, Konzepte und Ansätze zur Zustellbarkeit, damit Sie den Erfolg Ihres Marketing-Programms sicherstellen können. |

### Hilfe-Ressourcen

* Adobe Campaign Standard: [Hilfe-Center](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/campaign-standard-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) – [Anleitungsvideos](https://docs.adobe.com/content/help/de-DE/campaign-standard-learn/tutorials/overview.html) – [Versionsplanung](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-planning.html) – [Neueste Aktualisierungen der Dokumentation](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Hilfe-Center](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/campaign-classic-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) – [Anleitungsvideos](https://docs.adobe.com/content/help/de-DE/campaign-classic-learn/tutorials/overview.html) – [Neueste Aktualisierungen der Dokumentation](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/documentation-updates.html)
* Control Panel von Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/de-DE/control-panel/using/control-panel-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/control-panel/using/release-notes.html) – Anleitungsvideos für [Campaign Standard](https://docs.adobe.com/content/help/de-DE/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/de-DE/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Symbol](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Versionshinweise für Adobe Advertising Cloud.

* [Neue Funktionen in Advertising Cloud DSP](#adcloud-dsp)
* [Neue Funktionen in Advertising Cloud Search](#adcloud-search)

### Neue Funktionen in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Zuletzt aktualisiert: **28. Oktober 2020**

| Funktion | Beschreibung |
| -----------| ---------- |
| Neu Hilfe | (Version vom 28. Oktober) Die alten Hilfeseiten wurden durch aktualisierte Seiten ersetzt, die über den Hilfe-Link im DSP-Hauptmenü abrufbar und auch jederzeit unter [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=de](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html?lang=de) verfügbar sind. |
| Kampagnen | (Version vom 28. Oktober) Die früheren Beta-Ansichten von Campaign sind jetzt die standardmäßigen Ansichten von Campaign und bieten schnellere Einblicke, vereinfachte Workflows und benutzerspezifische Ansichten. |
| Privates Inventar | (Version vom 15. Oktober) Alle Benutzer können jetzt mit einem neuen Deal-ID-Formular Details zu Deal-IDs einrichten und bearbeiten. Hierbei handelt es sich um eine vereinfachte Version des alten [!UICONTROL Smart Ad Serving]-Formulars. Um neue Details für Deal-IDs einzurichten, gehen Sie zu **[!UICONTROL Inventar > Deals]**, klicken Sie auf **[!UICONTROL Erstellen]** und dann auf **[!UICONTROL Deal ID Beta]**. |
| Platzierungsvorhersage | (Version vom 15. Oktober) Für Platzierungen mit Platzierungsebenen-Geschwindigkeit enthält der Abschnitt [!UICONTROL Prognose] der Platzierungseinstellungen einen neuen Abschnitt mit [!UICONTROL geschätzten Höchstwerten], der angibt, wie viel mehr Kapazität mit der aktuellen Targeting-Konfiguration verfügbar ist. |

### Neue Funktionen in [!DNL Advertising Cloud Search] {#adcloud-search}

Zuletzt aktualisiert: **22. Januar 2021 für die Version 23. Januar**

| Funktion | Beschreibung |
| -----------| ---------- |
| [!UICONTROL Search-Kampagnen]<br> Berichte | Advertising Cloud Search meldet keine neuen durchschnittlichen Positionsdaten mehr für Microsoft® Advertising-Kampagnen. Die Spalte „Durchschnittliche Position“ zeigt Werte von null (0) für Datumsangaben ab dem 23. Januar an. Dies gilt in Vorbereitung auf die Ausmusterung der durchschnittlichen Positionsdaten durch Microsoft im Januar 2021.<br>Durchschnittliche Positionsdaten, die bis zum 22. Januar gesammelt wurden, stehen in Berichten weiterhin zur Verfügung. |

### Ad Cloud-Tutorials und -Kurse

Aktualisiert: **2. Dezember 2020**

## ![Symbol](/assets/magento.png) [!DNL Magento] {#magento}

Die neuesten Versionsinformationen finden Sie in den Magento Commerce- und Open Source-[Versionshinweisen](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html).

## ![Symbol](/assets/target.png)[!DNL Target] {#target}

Die aktuellen Versionsinformationen finden Sie in den [[!DNL Target] Versionshinweisen](https://docs.adobe.com/content/help/de-DE/target/using/release-notes/target-release-notes.html).

## ![Symbol](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] ist eine Komplettanwendung für das Lead-Management. B2B-Marketer können damit Kundenerlebnisse transformieren, indem sie in allen Phasen komplexer Customer Journeys Interaktionen ermöglichen.

### Aktualisierungen von Core Marketo Engage

Die aktuellen Versionsinformationen finden Sie in den [!DNL Marketo Engage] [Versionshinweisen](https://docs.marketo.com/display/public/DOCS/Release+Notes).

### Bevorstehende Funktionen

Die folgenden Funktionen werden im Laufe dieses Quartals veröffentlicht:

| Funktion | Beschreibung |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>Neue kontobasierte Segmentierung</li><li>Speichern von Dashboard-spezifischen Filtern</li><li>Export von Bizible Dashboards als PDF</li></ul> |
| Sales Connect | Aktualisierungen/Verbesserungen für Compose Window und Command Center |

### Veraltete und entfernte Funktionen

* **Asset-API-Parameter „_method“:** Ab September 2020 wird `_method` nicht mehr vom Asset-API-Endpunkten akzeptiert, um Abfrageparameter zu einem POST-Textkörper weiterzuleiten und URI-Längenbeschränkungen zu umgehen.
* **Einstellung der Unterstützung für Internet Explorer:** Ab der Juli-Version vom 31. Juli 2020 wird die Benutzeroberfläche von Marketo Engage in Internet Explorer nicht mehr unterstützt.

## ![Symbol](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Hilfe zu Document Cloud erhalten Sie über:

* [Adobe Acrobat Learning Hub](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Sign Learning Hub](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud-Schulungen und -Support](https://helpx.adobe.com/de/support/document-cloud.html)

## ![Symbol](/assets/creative-cloud-24.png) Creative Cloud Enterprise {#creative-cloud}

Neue Tutorials für Creative Cloud Enterprise.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| März 2021 | [Grundlegendes zur Anwenderlizenzierung](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/nameduserlicensing.html) | Artikel | Erfahren Sie mehr über die Bedeutung der Benannten Benutzerlizenzierung. |
| 5. März 2021 | [Ablauf der Seriennummer](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/cceserial.html) | Video | Erfahren Sie, wie Sie sicherstellen können, dass Ihre Endbenutzer weiterhin Zugriff auf ihre Adobe-Apps und -Dienste haben. |
| März 2021 | [Landing bereitstellen und verwalten - Unterstützende Elemente](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/overview-deploy.html) | Video | Erfahren Sie, wie Creative Cloud for Enterprise benutzerdefinierte Implementierungen und flexible Lizenzaktualisierungen unterstützt und wie es mit anderen Adobe-Enterprise-Angeboten funktioniert. |
| 5. März 2021 | [Anpassen der Farben in einer Adobe Stock Vector-Abbildung](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/customizecolors.html) | Video | hinzufügen polieren Sie mit einer großartigen Illustration zu jedem Projekt. Finden Sie den perfekten Vektor in Adobe Stock und passen Sie dann die Farben mit Adobe Illustrator an die Palette Ihres Projekts an. |
| 5. März 2021 | [Passen Sie eine Adobe Stock-Präsentationsvorlage so an, dass sie professionell und dennoch auffällig aussieht.](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/presentationtemplate.html) | Video | Erstellen Sie in wenigen Minuten eine wunderschöne stilisierte Präsentation mit Bildern und Vorlagen aus Adobe Stock und einigen einfach zu handhabenden Spezialeffekten. |
| 5. März 2021 | [Anpassen einer Animation des Ladebildschirms mit Adobe Stock und XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/loadingscreen.html) | Video | Passen Sie Vektorgrafiken aus Adobe Stock an, um eine illernde Animation für den Ladebildschirm einer mobilen App zu erstellen. |
| 5. März 2021 | [Erstellen realistischer Fotokombinationen mit Adobe Stock-Bildern](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/realisticcomposite.html) | Video | Bringen Sie zwei großartige Adobe Stock-Fotos zusammen, um Menschen in Ihre Social Posts zu ziehen. |
| 5. März 2021 | [Erstellen Sie mit Adobe Stock in kürzester Zeit inspirierende Moodboards.](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/moodboard.html) | Video | Erstellen Sie ein Projekt-Stimmung-Forum, um Informationen, Ideen, Visualisierungen und Farbpaletten an Teams/Kunden weiterzuleiten. |
| 5. März 2021 | [Erstellen Sie einheitliche Markenbilder mit schönen Verläufen und Adobe Stock-Assets](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/brandgradients.html) | Video | Bringen Sie Animationen mit editierbaren Vektoren für Adobe Stock in Ihre Newsletter-Grafiken. |
| 5. März 2021 | [Animationen für E-Mail mit Adobe Stock und Photoshop erstellen](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/animationemail.html) | Video | Mit Stopp-Action Animation können Sie Ihre E-Mails mit Adobe Stock und Photoshop versenden. |
| 5. März 2021 | [Erstellen Sie ein interaktives Tourismusfoto mit Adobe Stock und XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/interactivetourismphoto.html) | Video | Erstellen Sie mit Adobe Stock &amp; XD schnell ein interaktives Foto in Ihrem Website-Prototyp. |
