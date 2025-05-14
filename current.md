---
title: Neueste Versionshinweise
description: Aktuelle Versionshinweise und Wissensdatenbank-Probleme für Produkte und Services von Adobe  [!DNL Experience Cloud] . Informationen über bevorstehende Ereignisse und neue Dokumentationen zu Experience League. Die neuesten Tutorials und Kurse für [!DNL Experience Cloud] -Programme entdecken.
doc-type: release notes
last-update: May 2025
author: mfrei
mini-toc-levels: 2
exl-id: 091f0168-21b0-4f48-a02b-d70e96b84e27
source-git-commit: aee116de593350a931323eecfea00c7410224907
workflow-type: tm+mt
source-wordcount: '5569'
ht-degree: 31%

---

# Experience Cloud-Versionshinweise – Mai 2025

<!-- badgeReview: label="Internal Review" type="Negative" -->

<!-- ![Banner](assets/release-notes-header.png) -->

Auf dieser Seite finden Sie anwendungsspezifische Versionshinweise, bevorstehende Veranstaltungen, neue Tutorials und die neuesten Support-Artikel zu Experience League.

<!-- * [Customize your learning](https://experienceleague.adobe.com/de/home/profile-settings): Help us customize your learning experience. Select your role, industry, and the products that interest you.
* [Browse and discover](https://experienceleague.adobe.com/de/browse): Find popular content, new tutorials, documentation, upcoming events, and more!
* [Get fresh perspectives](https://experienceleague.adobe.com/de/perspectives): We've gathered a variety of real-world use cases and best practices, written by your peers and Adobe product experts. 
* [Get certified](https://experienceleague.adobe.com/de/certification-home): The new Adobe Certification Portal makes honing your skills and getting certified a simple process.
* [Engage with a community of peers](https://experienceleaguecommunities.adobe.com/?profile.language=de): Join groups, meet our Experience League Community Advisors, and even learn how to become one. -->

Um eine monatliche E-Mail-Benachrichtigung über Aktualisierungen auf dieser Seite zu erhalten, abonnieren Sie das [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html).

**Aktualisiert am 14. Mai 2025**

+++Produktlinks anzeigen

* [[!DNL Adobe System Status]](#status)
* [[!DNL Adobe Experience Cloud] - Zentrale Schnittstelle und Administration](#ecloud) (aktualisiert: **12. Mai**)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Real-Time CDP]](#rtcdp)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Adobe Customer Journey Analytics]](#cja)
* [[!DNL Adobe Streaming Media Analytics]](#sma)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Journey Optimizer B2B Edition]](#ajo-b2b)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe GenStudio for Performance Marketing]](#genstudio-marketing)
* [[!DNL Adobe Mix Modeler]](#mix-modeler)
* [[!DNL Adobe Advertising]](#advertising)
* [[!DNL Adobe Pass]](#pass)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Customer Data Management – Voices](#voices)
* [Blueprints für digitale Erlebnisse](#blueprints)
* [Zertifizierung bei Adobe](https://experienceleague.adobe.com/de/certification-home)
* [Sicherheitslücken bei Adobe-Produkten](https://helpx.adobe.com/de/security.html)

+++

## Events auf [!DNL Experience League] {#events}

Suchen Sie [Events](https://experienceleague.adobe.com/de/events) und registrieren Sie sich für diejenigen, die Sie interessieren.

+++Kommende Events

* **Multisolution** | _Adobe Digital Insights: Webinar zur Einführung von Digital- und GenAI-Technologien_ | Basierend auf Daten von über einer Billion Besuchen US-amerikanischer Websites wird Adobe Digital Insights wichtige Trends im Einzelhandel und auf Reisen teilen, darunter die Zunahme von Mobilgeräten, die Einführung von GenAI und die Fragmentierung der Verbraucheraufmerksamkeit. | **Donnerstag, 15.** | [Registrieren](https://events.teams.microsoft.com/event/c63a6057-465d-486a-a447-f644cd3648e4@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **Multisolution** | _Mit Adobe auf eine Stufe stellen: Wie bewerbe ich mich und steche als Champion hervor_ | Nehmen Sie am Adoption Marketing-Team von Adobe und aktuellen Adobe Champions teil, um ein exklusives Webinar zu erhalten, in dem wir Sie durch das Programm führen und Tipps zum Senden einer herausragenden Anwendung teilen. | **Donnerstag, 15.** | [Registrieren](https://engage.adobe.com/Champion_applications.html)

* **[!DNL Workfront]** | _Dies ist die Workfront Collective Event - eine Crowdsourcing-Gelegenheit für alle Workfront-Benutzer!_ | Diese Veranstaltung hat keine formelle Präsentation oder Tagesordnung. Die Diskussionsthemen basieren ausschließlich auf der Interaktion der Teilnehmer. | **Montag, 19. Mai** | [Registrieren](https://events-ar.adobeconnect.com/content/adobeconnect/1/655548740/en/events/event/shared/1243343674/event_landing.html?sco-id=1273286511&amp;_charset_=utf-8)

* **[!DNL Workfront]** | _Creative-Methoden zum Verwalten von Ressourcen in Workfront_ | Möchten Sie lernen, wie Sie Ressourcen in Workfront verwalten, ohne sich auf herkömmliche Tools wie den Ressourcenplaner oder den Workload Balancer zu verlassen? Wenn ja, ist diese Sitzung für Sie! | **Dienstag, 20. Mai** | [Registrieren](https://events.teams.microsoft.com/event/126180b0-7153-414f-8ef3-a2bbc53176bb@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL Commerce]** | _Commerce &amp; Coffee: Wachstum mit SEO vorantreiben_ | In dieser Sitzung werden Sr. Commerce Strategy Consultant, Corey Gelato, und Commerce Strategy Consultant, Agbi Bajrushi, einen tiefen Einblick in SEO geben. | **Mittwoch, 21. Mai** | [Registrieren](https://events-emea5.adobeconnect.com/content/adobeconnect/43/5415868397/en/events/event/shared/5750600822/event_landing.html?sco-id=5750592916&amp;campaign-id=ExL&amp;_charset_=utf-8)

* **[!DNL Workfront]** | _Schneller Einstieg, intelligente Skalierung: Aktivierung des Erfolgs auf Team-Ebene mit Workfront Planning_ | Eine neue Planungslösung in einem Unternehmen einzuführen, kann sich anfühlen, als würde man den heißen Stein voll stopfen - kostspielig, langsam und losgelöst von den Anforderungen der Teams, die die Dinge jetzt einfach erledigen möchten. In dieser Sitzung stellen wir Ihnen das Implementierungsmodell von Bund und Ländern vor und zeigen Ihnen, wie frühe Anwender Workfront Planning nutzen, um schnell Mehrwert zu erschließen - ohne auf einen unternehmensweiten Konsens zu warten.  | **Mittwoch, 28. Mai** | [Registrieren](https://events.teams.microsoft.com/event/2fa2a2f4-ada5-4810-9014-aa7fe34d0354@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL Workfront]** | _Entfesseln Sie die Leistungsfähigkeit von Workfront Data Connect_ | Möchten Sie die Workfront-Berichterstellung auf die nächste Stufe heben? Dieses einstündige Webinar, das im Ultimate-Paket enthalten ist, aber als Add-on ($) für ausgewählte oder Prime-Kunden verfügbar ist, wird in Zusammenarbeit mit Adobe Workfront Product Management durchgeführt und Ihnen Data Connect und alles, was es tun kann, vorstellen.  | **Donnerstag, 29. Mai** | [Registrieren](https://events.teams.microsoft.com/event/5adb7454-e13d-408d-a430-eb3a69a08510@fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL Experience Manager Guides]** | _Adobe DITAWORLD 2025_ | Planen Sie, uns vom 3. bis 5. Juni 2025 beizutreten, für drei Tage voller Präsentationen von Branchenexperten und fantastischer Chats mit Fachleuten aus der Branche. | **3. bis 5. Juni** | [Registrieren](https://2025-adobe-dita-world.meetus.adobeevents.com/?utm_campaign=community_forum&amp;utm_source=experience_league)

* **[!DNL Workfront]** | _Mit Workfront wecken: Optimieren, um die Ansicht zu erhöhen. Prüfen und Ausrichten der Adobe Workfront-Instanz_ | Beschreibung | **Monat, Tag um 10:00 Uhr MT** | [Registrieren](https://events-emea5.adobeconnect.com/content/adobeconnect/43/5415868397/en/events/event/shared/5748588430/event_landing.html?sco-id=5748605291&amp;campaign-id=ExL&amp;_charset_=utf-8)

Sehen Sie sich die vollständige Liste der [kommenden Events](https://experienceleague.adobe.com/de/events) und der [On-Demand-Events](https://experienceleague.adobe.com/de/docs/events/experience-league-recorded-events/overview) in Experience League an.

+++

## [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] bietet detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Adobe-Produkten und -Diensten. Erhalten Sie Benachrichtigungen über Ausfälle, Störungen und Wartungsereignisse. Weitere Informationen dazu erhalten Sie unter [status.adobe.com/de](https://status.adobe.com/de/).

+++Versionshinweise

Frühere Versionshinweise für [!DNL Adobe System Status]:

* [April 2025](https://experienceleague.adobe.com/en/docs/release-notes/experience-cloud/previous/2025/04162025#status)
* [August 2024](https://experienceleague.adobe.com/de/docs/release-notes/experience-cloud/previous/2024/09142023#status)
* [Mai 2024](https://experienceleague.adobe.com/de/docs/release-notes/experience-cloud/previous/2024/05152024#status)
* [Januar 2024](https://experienceleague.adobe.com/de/docs/release-notes/experience-cloud/previous/2024/02142024#status)
* [Oktober 2023](https://experienceleague.adobe.com/de/docs/release-notes/experience-cloud/previous/2023/10042023#status)
* [August 2023](https://experienceleague.adobe.com/de/docs/release-notes/experience-cloud/previous/2023/08092023#status)
* [März 2023](https://experienceleague.adobe.com/de/docs/release-notes/experience-cloud/previous/2023/03082023#status)
* [Januar 2023](https://experienceleague.adobe.com/de/docs/release-notes/experience-cloud/previous/2023/02082023#status)

+++

## [!DNL Experience Cloud] - Zentrale Benutzeroberfläche und Verwaltung {#ecloud}

Erfahren Sie mehr über Aktualisierungen der [!DNL Experience Cloud]-Administrationsoberfläche und der zentralen Komponenten der Benutzeroberfläche.

+++Neue Funktionen

Keine Updates im Mai.

Hilfe zu folgenden Themen finden Sie im Handbuch für die [Oberfläche und Administration von Experience Cloud](https://experienceleague.adobe.com/de/docs/core-services/interface/experience-cloud):

* Benutzerverwaltung und Produktlizenzen (Admin Console)
* Generative KI in Experience Cloud-Programmen
* Kundenattribute und Zielgruppenbibliothek
* Assets in Experience Cloud
* Cookies in Experience Cloud

+++

## [!DNL Experience Platform] {#platform}

Aktuelle Versionshinweise und neue Dokumentation für [!DNL Experience Platform] und [!UICONTROL Mobile SDK]. Sehen Sie sich neue Tutorials und Wissensdatenbank-Support-Artikel an.

+++Versionshinweise, Tutorials und Support-Artikel

* [[!DNL Experience Platform] -Versionshinweise](https://experienceleague.adobe.com/de/docs/experience-platform/release-notes/latest)

* [[!DNL Experience Platform] -Versionshinweise zu Mobile SDK](https://developer.adobe.com/client-sdks/documentation/release-notes/)

<!-- ### New [!DNL Experience Platform] tutorials{#tutorials-aep}

New tutorials published for Adobe [!DNL Experience Platform] on Experience League.

| Published | Applications | Name | Type | Description |
| ----------| ---------- | ---------- | ---------- |---------- |
|April 2025| [!DNL Experience Platform] | [Evaluate batch audiences on demand](https://experienceleague.adobe.com/de/docs/platform-learn/tutorials/audiences/evaluate-audiences-on-demand)| New video | Evaluate batch audiences on demand with flexible audience evaluation. |
|April 2025| [!DNL Experience Platform] | [Migrate a mobile app from Target to Journey Optimizer](https://experienceleague.adobe.com/de/docs/platform-learn/migrate-target-to-mobile-sdk-decisioning/overview)| New video | Learn how to migrate your mobile app implementation from the Adobe Target to the Adobe Journey Optimizer - Decisioning extension|
|April 2025| [!DNL Experience Platform] | [Configure a dataset export destination in Experience Platform](https://experienceleague.adobe.com/de/docs/platform-learn/tutorials/destinations/configure-dataset-export-destination)| Updated video | Learn about the configuration, workflow, and use cases for exporting datasets from Adobe Experience Platform to a cloud storage location using a destination connection. |
 -->

### Neue [!DNL Experience Platform]-Support-Wissensdatenbank{#kb-aep}

Neue Artikel und Aktualisierungen vorhandener Artikel für [!DNL Experience Platform].

| Veröffentlicht | Name | Typ | Beschreibung |
|---------|----|----|-----------|
| April 2025 | [AEP: Niedrige Zielgruppen-Volumina am  [!DNL TikTok]  trotz hoher Aktivierungsrate](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26380) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn [!DNL TikTok] Ziel in Adobe [!DNL Experience Platform] (AEP) trotz einer hohen Aktivierungsrate (~99 %) niedrigere Zielgruppen-Volumina meldet. |
| April 2025 | [Beheben von Problemen beim Datensatzexport in Adobe [!DNL Experience Platform]](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26413) | Neuer Artikel | Erfahren Sie mehr über die Lösung, wenn Probleme beim Datensatzexport in Adobe aufgrund von Einschränkungen bei API-erstellten Datensätzen auftreten [!DNL Experience Platform]. |
| April 2025 | [Beheben des Batch-Erfassungsfehlers und der doppelten Erfassung in Adobe [!DNL Experience Platform]](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26349) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass die Batch-Aufnahme in Adobe [!DNL Experience Platform] beim Erstellen einer doppelten Aufnahme fehlschlägt. |
| April 2025 | [[!DNL Snowflake] Connector-Authentifizierungsfehler in Adobe [!DNL Experience Platform]](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26294) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn Authentifizierungsfehler in Adobe [!DNL Experience Platform] (AEP) und [!DNL Snowflake] auf Formatierungs- oder Konfigurationsprobleme für private Schlüssel zurückzuführen sind. |
| April 2025 | [*406-Fehler (Nicht akzeptabel* beim Hochstufen der Inhaltsvorlage](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26320) | Neuer Artikel | Erfahren Sie, wie Sie den Fehler *406 (Nicht akzeptabel)* in [!UICONTROL Journey Orchestration&rbrace; von Adobe [!DNL Experience Platform] beheben können] indem Sie API-Kopfzeilen anpassen. |
| April 2025 | [AEP - Was ist der Unterschied zwischen dem HTTP-API-Ziel und Destination SDK?](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26316) | Neuer Artikel | Erfahren Sie, wie sich die Funktionen und Ziele des HTTP-API-Ziels und von Destination SDK unterscheiden und wie sie sich unterscheiden. |

+++

## [!DNL Real-Time CDP] {#rtcdp}

Erhalten Sie die neusten Tutorials für [!DNL Real-Time CDP]. 

+++Neue Tutorials

| Veröffentlicht | Name | Typ | Beschreibung |
| ----------| ---------- | ---------- |---------- |
| Mai 2025 | [Konfigurieren des Azure Blob-Ziels](https://experienceleague.adobe.com/de/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination) | Aktualisiertes Video | Erfahren Sie, wie Sie in [!DNL Real-Time Customer Data Platform] eine Verbindung einrichten und Daten an das Azure Blob Storage-Ziel senden. Dieses Ziel unterstützt den Export von Datensätzen und Audiences und ermöglicht Ihnen das Anpassen der Dateikopfzeilen und Datenattribute. |

Weitere Informationen finden Sie unter:

* Video-Tutorials: [Grundlegendes zu Real-Time Customer Data Platform](https://experienceleague.adobe.com/de/docs/platform-learn/tutorials/rtcdp/understanding-the-real-time-customer-data-platform)

* Produktdokumentation: [Real-Time Customer Data Platform](https://experienceleague.adobe.com/de/docs/real-time-customer-data-platform)

+++

## [!DNL Analytics] {#analytics}

Erhalten Sie die neuesten Versionsinformationen für [!DNL Adobe Analytics] und [!DNL AppMeasurement]. Sehen Sie sich neue Tutorials und Support-Artikel an.

+++Versionshinweise und neue Tutorials

[!DNL Analytics] Veröffentlichungsdatum: **Donnerstag, 14. Mai 2025**

* [Versionshinweise](https://experienceleague.adobe.com/de/docs/analytics/release-notes/latest) zu [!DNL Analytics]

* [Produktdokumentation und Tutorials](https://experienceleague.adobe.com/de/docs/analytics) zu [!DNL Analytics]

### AppMeasurement {#appm}

* [Versionshinweise zu AppMeasurement für JavaScript](https://github.com/adobe/appmeasurement/releases)

<!-- ### New Analytics tutorials {#tutorials-analytics}

New or updated video tutorials published for Adobe Analytics.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|April 2025|[Configure variables in Report Suite Manager](https://experienceleague.adobe.com/de/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-variables-in-the-admin-console)| New video |Configure variables and events in [!UICONTROL Report Suite Manager], ensuring that the reports, dimensions, and metrics have the right names and behavior.| -->

+++

## [!DNL Customer Journey Analytics] {#cja}

Erhalten Sie die neusten Versionsinformationen für [!DNL Customer Journey Analytics]. Zeigen Sie neue Tutorials auf Experience League an.

+++Versionshinweise und neue Tutorials

* [Versionshinweise](https://experienceleague.adobe.com/de/docs/analytics-platform/using/releases/latest#releases)

  Versionen für [!DNL Customer Journey Analytics] werden ständig veröffentlicht. Daher werden die Versionshinweise mehrmals monatlich aktualisiert. Sie sollten daher regelmäßig nachschauen.

* [Produktdokumentation und Tutorials](https://experienceleague.adobe.com/de/docs/customer-journey-analytics)

### Neue [!DNL Customer Journey Analytics]-Tutorials {#tutorials-cja}

Neue Tutorials, die für [!DNL Customer Journey Analytics] veröffentlicht wurden.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Mai 2025 | [Verwenden des Bedienfelds [!UICONTROL Quick Insights]](https://experienceleague.adobe.com/de/docs/customer-journey-analytics-learn/tutorials/analysis-workspace/panels/use-the-quick-insights-panel) | Neues Video | Erfahren Sie, wie Sie geschäftliche Fragen mithilfe des Bedienfelds _[!UICONTROL Quick Insights]_ in [!DNL Customer Journey Analytics] schnell und einfach beantworten können. |

+++

## [!DNL Streaming Media Analytics] {#sma}

Erhalten Sie die neusten Versionsinformationen für [!DNL Streaming Media Analytics]. Zeigen Sie neue Tutorials auf Experience League an.

+++Versionshinweise

Nicht aktualisiert.

* [Versionshinweise](https://experienceleague.adobe.com/de/docs/media-analytics/using/release-notes/release-notes) zu [!DNL Streaming Media Analytics]

* [Produktdokumentation und Tutorials](https://experienceleague.adobe.com/de/docs/media-analytics/using/media-overview) zu [!DNL Streaming Media Analytics]

+++

## [!DNL Experience Manager] {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in [!DNL Experience Manager]. Adobe empfiehlt Kundinnen und Kunden mit On-Premise-Bereitstellungen, die aktuellsten Patches bereitzustellen, um mehr Stabilität, Sicherheit und Performance zu erzielen.

+++Versionshinweise, neue Tutorials und Support-Artikel

### Versionshinweise zu Experience Manager

[!DNL Experience Manager as a Cloud Service] Wartungsversion [2025.4.0](https://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current).

Die nächste geplante Version ist **5. Juni 2025**.

Die nachfolgend aufgeführten Seiten umfassen alle Versionshinweise zu [!DNL Experience Manager]:

* [Aktuelle Versionshinweise für [!DNL Experience Manager] as a Cloud Service](https://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current)
* [Aktuelles Video zur Versionsübersicht](https://experienceleague.adobe.com/de/docs/events/aemcs-release-update-recordings/overview)
* [[!DNL Experience Manager] Versionsaktualisierungen und Roadmaps](https://experienceleague.adobe.com/de/docs/experience-manager-release-information/aem-release-updates/home)
* [[!DNL Experience Manager] Versionshinweise zum 6.5 Service Pack](https://experienceleague.adobe.com/de/docs/experience-manager-65/content/release-notes/release-notes)
* [[!DNL Experience Manager] Versionshinweise zu Cloud Manager](https://experienceleague.adobe.com/de/docs/experience-manager-cloud-manager/content/release-notes/current)
* [Versionshinweise zum Service für die automatische Formularkonversion](https://experienceleague.adobe.com/de/docs/aem-forms-automated-conversion-service/using/release-notes)
* [[!DNL Experience Manager] Versionshinweise zu Assets Dynamic Media](https://experienceleague.adobe.com/de/docs/dynamic-media-developer-resources/release-notes/s7rn2017)
* [[!DNL Experience Manager] Versionshinweise zu Brand Portal](https://experienceleague.adobe.com/de/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes)
* [[!DNL Experience Manager] Versionshinweise zum Desktop-Programm](https://experienceleague.adobe.com/de/docs/experience-manager-desktop-app/using/release-notes)
* [[!DNL Experience Manager] Versionshinweise zu Dispatcher](https://experienceleague.adobe.com/de/docs/experience-manager-dispatcher/using/getting-started/release-notes)

### Neue [!DNL Experience Manager]-Tutorials {#tutorials-aem}

Neue Tutorials, die für [!DNL Experience Manager] auf [!DNL Experience Manager] veröffentlicht wurden.

| Veröffentlicht | Programme | Name | Typ | Beschreibung |
| ----------| ---------- | ---------- | ---------- |---------- |
| Mai 2025 | [!DNL Experience Manager Sites] | [Videos und Tutorials zu AEM Sites](https://experienceleague.adobe.com/de/docs/experience-manager-learn/sites/overview) | Aktualisierte Tutorial-Startseite | Durchsuchen Sie Videos und Tutorials zu den Funktionen und Leistungsmerkmalen von Adobe Experience Manager Sites. AEM Sites ist eine führende Experience-Management-Plattform. |
| Mai 2025 | [!DNL Experience Manager as a Cloud Service] | [Einrichten von OpenAPI-basierten AEM-APIs](https://experienceleague.adobe.com/de/docs/experience-manager-learn/cloud-service/aem-apis/openapis/setup) | Neues Video | Erfahren Sie, wie Sie Ihre AEM as a Cloud Service-Umgebung einrichten, um den Zugriff auf die OpenAPI-basierten AEM-APIs zu ermöglichen. |
| Mai 2025 | [!DNL Experience Manager Forms] | [Erstellen eines Formulars mit dem adaptiven Forms-Block](https://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/edge-delivery/build-forms/getting-started-edge-delivery-services-forms/create-forms) | Neues Video | Erste Schritte mit Edge Delivery Services für AEM Forms. Erstellen Sie perfekte Formen, schnell! AEM Forms Edge Delivery doc-basiertes Authoring = unglaubliche Geschwindigkeit und SEO-freundliche Formulare für zufriedene Anwender und Suchmaschinen. |
| Mai 2025 | [!DNL Experience Manager Sites] - Headless | [Erweiterte Konzepte von AEM Headless](https://experienceleague.adobe.com/de/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/advanced-tutorial/overview) | Neues Video | Ein durchgehendes Tutorial zur Illustration erweiterter Konzepte der GraphQL-APIs von Adobe Experience Manager (AEM). |

### Neue [!DNL Experience Manager]-Support-Wissensdatenbank{#kb-aem}

Neue Artikel und Aktualisierungen vorhandener Artikel für [!DNL Experience Manager].

| Veröffentlicht | Name | Typ | Beschreibung |
|---------|--------|---------|---------|
| April 2025 | [Workflow-Instanzen bleiben im Status „Wird ausgeführt“](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26078) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass Workflow-Instanzen (WF) über einen längeren Zeitraum im Status „Wird ausgeführt“ feststecken bleiben. |
| April 2025 | [Beheben der langsamen Leistung in AEM aufgrund veralteter Workflows](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26369) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn übermäßig veraltete Workflow-Instanzen in [!DNL Adobe Experience Manager (AEM) Sites] die Autorenumgebung verlangsamen. |
| April 2025 | [Nach der Erstellung eines VPN schlägt das Senden von Traffic mit *java.net.UnknownHostException fehl*](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26374) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass ein VPN erstellt wurde und sich im Status &quot;*&quot; befindet* das Senden von Traffic durch den Tunnel jedoch mit *java.net.UnknownHostException* fehlschlägt. |
| April 2025 | [Beheben von ACS AEM [!UICONTROL Commons Copy-Eigenschaften] Prozessschrittfehler](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26327) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn der ACS AEM [!UICONTROL Commons Copy Properties]-Prozessschritt aufgrund einer fehlenden Prozessressourcenkonfiguration fehlschlägt. |
| April 2025 | [Adobe Experience Manager as a Cloud Service: HTTP-zu-HTTPS-Traffic-Umleitung](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26336) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass AEM as a Cloud Service automatisch den gesamten Traffic von HTTP zu HTTPS umleitet. |
| April 2025 | [Adobe Experience Manager as a Cloud Service: *[!UICONTROL Schreibgeschützt]* Status für [!UICONTROL Ereignis]-Einstellungen in [!DNL Adobe I/O Projects]](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26337) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn Benutzende in [!DNL Adobe Developer Console] [!DNL (Adobe I/O Projects)] feststellen, dass die Auswahloption für AEM as a Cloud Service in den neuen **[!UICONTROL Event]**-Einstellungen nicht angezeigt wird oder dass vorhandene **[!UICONTROL Event]**-Einstellungen im *[!UICONTROL ReadOnly]*-Status gesperrt sind. |
| April 2025 | [Korrigieren Sie die Sortierung der Inhaltsstruktur in Adobe Experience Manager](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26241) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn ein Ordner in Adobe Experience Manager (AEM) 1.000 Ordner überschreitet und sich das Sortierverhalten unerwartet ändert. |
| April 2025 | [Beheben von Audioproblemen in Videodateien mit  [!DNL Dynamic Media]  in AEM](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26197) | Neuer Artikel | Erfahren Sie, wie Sie Audiosynchronisierungsprobleme in Videodateien bei Verwendung von [!DNL Dynamic Media] in Adobe Experience Manager as a Cloud Service (AEMaaCS) beheben. |
| April 2025 | [Beheben von Fehlern bei ungültigen Benutzeridentitätswechseln in AEM as a Cloud Service](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26118) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass der Identitätswechsel mit dem Fehler *Ungültiger Benutzer* in [!DNL Adobe Experience Manager as a Cloud Service - Sites] fehlschlägt. |
| April 2025 | [Einrichtung nicht möglich [!DNL Microsoft Translation Service]  in Adobe Experience Manager (AEM)](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26096) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems beim Konfigurieren der [!DNL Microsoft Translation Service] in Adobe Experience Manager (AEM) as a Cloud Service. Der Endpunkt und der Schlüssel, die von [!DNL Microsoft Azure] bereitgestellt werden, werden vom [!DNL AEM Translation]-Konfigurationsformular nicht erkannt. |
| April 2025 | [Überwachen des Zustands der AEM-Umgebung](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-25893) | Neuer Artikel | Erfahren Sie, wie Sie den Zustand einer AEM-Umgebung mithilfe integrierter Konsistenzprüfungs-Endpunkte programmgesteuert überwachen. |
| April 2025 | [Beheben von Problemen beim Export von Inhaltsfragmenten in Adobe Target](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26167) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Fehlers *Synchronisieren mit Adobe Target fehlgeschlagen* der beim Exportieren von Inhaltsfragmenten von Adobe Experience Manager nach Adobe Target auftritt. |
| April 2025 | [Beheben von Problemen mit hoher Auslastung in AEM-Veröffentlichungsservern aufgrund  [!DNL Time-to-Live]  (TTL)-Caching](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26393) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn Leistungsspitzen auf AEM-Veröffentlichungsservern durch eine 5-minütige TTL-Caching-Strategie in [!DNL AEMaaCS - Sites] verursacht werden. |
| April 2025 | [Produktauswahlbegrenzung in der Produktlistenkomponente von AEM Cloud Service](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26019) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass die Produktlistenkomponente in Adobe Experience Manager (AEM) Cloud Service Benutzenden nicht erlaubt, mehr als 20 Produkte (SKUs) über das Kontrollkästchen **[!UICONTROL Alle auswählen]** hinzuzufügen. |
| April 2025 | [Automatisches Tagging neu hochgeladener Assets in [!DNL AEMaaCS - Assets]](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-25925) | Neuer Artikel | Erfahren Sie, wie Sie das [!DNL AEMaaCS - Assets] beheben können, dass neu hochgeladene Assets automatisch mit Tags der Standardausrichtung versehen werden, was sich auf bestehende Metadaten-Management-Verfahren auswirkt. |
| April 2025 | [Beheben der Bereitstellung fehlerhafter Inhalte in Adobe Experience Manager (AEM) as a Cloud Service](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-25922) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn aufgrund von Konfigurationskonflikten in der as a Cloud Service-Bereitstellung von Adobe Experience Manager (AEM) falsche Inhalte bereitgestellt werden. |

+++

## [!DNL Commerce] {#commerce}

Erhalten Sie Zugriff auf Versionshinweise, neue Tutorials und Wissensdatenbank-Artikel für [!DNL Adobe Commerce] auf Experience League.

+++Versionshinweise, neue Tutorials und Support-Artikel

* Siehe die [Versionshinweise für  [!DNL Adobe Commerce]  und  [!DNL Magento Open Source]](https://experienceleague.adobe.com/de/docs/commerce-operations/release/notes/overview), um auf dem aktuellen Stand zu bleiben.
* Informationen zur Version der Commerce-Dienste und die Dokumentation finden Sie in den [Handbüchern für Adobe  [!DNL Commerce] -Dienste](https://experienceleague.adobe.com/de/docs/commerce/user-guides/home).
* Siehe [Produktverfügbarkeit](https://experienceleague.adobe.com/de/docs/commerce-operations/release/product-availability), um auf die Produktversionshinweise zuzugreifen und die Verfügbarkeit zu überprüfen.

### Neue Tutorials für [!DNL Adobe Commerce] {#tutorials-commerce}

Neue Tutorials für [!DNL Adobe Commerce] auf Experience League.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Mai 2025 | [Organisatorische Bereitschaft für Erfolgsbeschleuniger](https://experienceleague.adobe.com/de/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/success-accelerators-organizational-readiness) | Neues Video | Erfahren Sie mehr über die Erfolgsbeschleuniger von Adobe für die organisatorische Vorbereitung. |
| Mai 2025 | [Commerce Support-Add-ons](https://experienceleague.adobe.com/de/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/commerce-support-add-ons) | Neues Video | Erfahren Sie mehr über erweiterte Support-Pläne für Kunden, einschließlich Expert Success, Ultimate Success und verschiedenen Add-ons für strategische Unterstützung. |
| Mai 2025 | [Was ist Expert Success?](https://experienceleague.adobe.com/de/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/what-is-expert-success) | Neues Video | Erfahren Sie mehr über den Adobe Commerce-Experten success plan. Erfahren Sie mehr über die Details, einschließlich der drei Support-Kanäle und Service-Level-Ziele. |
| Mai 2025 | [Technische Bereitschaft für Erfolgsbeschleuniger](https://experienceleague.adobe.com/de/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/success-accelerators-technical-readiness) | Neues Video | Erfahren Sie mehr über die technische Bereitschaft von Commerce Success Accelerator, die Prüfung von Lösungen, die Ereignisplanung und das 24-Stunden-Monitoring, um eine optimale Leistung zu erzielen. |
| Mai 2025 | [Einführung und Aktivierung von Erfolgsbeschleunigern](https://experienceleague.adobe.com/de/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/success-accelerators-adoption-and-enablement) | Neues Video | Erfahren Sie mehr über die Verwendung von Adobe Commerce Success Accelerator und die Unterstützung für strategische Entwicklung, Kompetenzverbesserung und Governance. |
| Mai 2025 | [Was ist Ultimate Success?](https://experienceleague.adobe.com/de/docs/commerce-learn/tutorials/webinars-and-events/commerce-conversations/what-is-ultimate-success) | Neues Video | Erfahren Sie mehr über den proaktiven Support von Adobe Commerce Ultimate Success und die strategische Anleitung für hochleistungsfähige digitale Erlebnisse. |
| Mai 2025 | [Technisches Onboarding - SaaS-Angebote](https://experienceleague.adobe.com/de/docs/commerce-learn/tutorials/adobe-commerce-cloud/technical-onboarding-hardware-handoff/saas-offerings-support-communications-next-steps) | Neues Video | Erfahren Sie mehr über die SaaS-Angebote von Adobe Commerce Cloud, den Support und weitere Kommunikationen sowie über die nächsten Schritte. |

### Neue [!DNL Commerce]-Support-Wissensdatenbank{#kb-commerce}

Neue Artikel und Aktualisierungen vorhandener Artikel für Adobe Commerce.

| Veröffentlicht | Name | Typ | Beschreibung |
|---------|--------|---------|---------|
| April 2025 | [[!DNL Quality Patches Tool] (QPT)](https://experienceleague.adobe.com/de/docs/commerce-operations/tools/quality-patches-tool/patches-available-in-qpt/patches-available-in-qpt-tool-overview) | Neue Artikel | Neue Artikel zum Anwenden von Patches, die in QPT 1.1.60, QPT 1.1.61 und QPT 1.1.62 verfügbar sind, wurden veröffentlicht und sind in den jeweiligen Abschnitten zu finden. |
| April 2025 | [Erhöhte Ausführungszeit für alle asynchronen Massenwebendpunkte nach dem APSB25-08-Sicherheits-Patch](https://experienceleague.adobe.com/de/docs/commerce-knowledge-base/kb/troubleshooting/known-issues-patches-attached/increased-execution-time-for-bulk-asynchronous-web-endpoints-post-apsb25-08-security-patch) | Neue Artikel | Dieser Artikel enthält einen Hotfix für alle asynchronen Massenwebendpunkte, z. B. `POST rest/all/async/bulk/V1/products` mit über 1.000 Einträgen, die nach der Anwendung des Sicherheits-Patches APSB25-08 deutlich längere Ausführungszeiten aufweisen. |
| April 2025 | [Leistungsproblem beim Upgrade `Magento_Company` B2B-Moduls nach der Aktualisierung auf B2B 1.5.2](https://experienceleague.adobe.com/de/docs/commerce-knowledge-base/kb/troubleshooting/installation-and-upgrade/magento-company-module-upgrade-performance-issue) | Neue Artikel | Dieser Artikel bietet einen Hotfix für das Leistungsproblem beim Upgrade des `Magento_Company`-Moduls nach der Aktualisierung von B2B 1.5.2, wobei die übermäßig lange Verarbeitungszeit für große Datensätze (~100.000+ Datensätze) in der `company_structure` behandelt wird. |
| April 2025 | [Die Aktualisierung auf B2B 1.5.2 schlägt aufgrund einer fehlenden `REGEXP_LIKE` mit einem SQL-Syntaxfehler fehl](https://experienceleague.adobe.com/de/docs/commerce-knowledge-base/kb/troubleshooting/installation-and-upgrade/sql-syntax-error-due-to-missing-regexp-like-function) | Neue Artikel | Dieser Artikel enthält einen Hotfix für den SQL-Syntaxfehler, der aufgrund der fehlenden `REGEXP_LIKE` beim Versuch auftritt, die `company_structure` zu aktualisieren. |
| April 2025 | [*Maximale Anzahl von Cookies wird überschritten* Fehler in Adobe Commerce](https://experienceleague.adobe.com/de/docs/commerce-knowledge-base/kb/troubleshooting/known-issues-patches-attached/maximum-number-of-cookies-would-be-exceeded-error) | Neue Artikel | Dieser Artikel enthält Patches zur Behebung des Fehlers *Maximale Anzahl von Cookies würde überschritten* in Adobe Commerce. |
| April 2025 | [[!DNL Web Application Firewall] (WAF) zeigt den Status „Deaktiviert“ in Adobe Commerce auf der Cloud-Infrastruktur [!UICONTROL Admin]-Oberfläche an](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26387) | Neue Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn die [!DNL Web Application Firewall] (WAF) in Adobe Commerce in der Cloud-Infrastruktur auf der Seite [!UICONTROL Admin] deaktiviert erscheint, obwohl sie aktiviert ist und ordnungsgemäß funktioniert. |
| April 2025 | [Beheben eines Adobe Commerce-Sicherheits-Patch-Cloud-Bereitstellungsfehlers](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26408) | Neue Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn Bereitstellungsfehler durch nicht unterstützte Backend-Cache-Konfigurationen in Adobe Commerce auf der Cloud-Infrastruktur auftreten. |
| April 2025 | [Beheben von Protokollpufferfehlern in Adobe Commerce in der Cloud-Infrastruktur](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26382) | Neue Artikel | Erfahren Sie mehr über die Lösung des Problems, dass ein Protokollpuffer voll wird, was zu gekürzten Zugriffsprotokollanfragen bei Site-Ausfällen führt. |
| April 2025 | [Fehlerbehebung bei Datenbank-Dump-Fehlern in Adobe Commerce in der Cloud-Infrastruktur](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26385) | Neue Artikel | Erfahren Sie, wie Sie `magento-cloud db:dump` Fehler beheben, um einen erfolgreichen Datenbank-Dump sicherzustellen. |
| April 2025 | [Probleme beheben mit  [!DNL Security Scan Tool]  Zugriff auf Suchergebnisse](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26357) | Neue Artikel | Erfahren Sie, wie Sie mit Situationen umgehen können, in denen die Adobe Commerce-[!DNL Security Scan Tool] Malware oder kritische Probleme erkennt, die Suchergebnisse jedoch nicht verfügbar sind. |

+++

## [!DNL Target] {#target}

Erhalten Sie Hinweise zu Vorabversionen, Hinweise zur aktuellen Version und Tutorials zu [!DNL Adobe Target].

+++Versionshinweise

<!-- ### New [!DNL Target] support knowledge base{#kb-target}

|Published|Name|Type|Description|
|---------|----|----|-----------|
|July 2024|[[!DNL Adobe Target] bulk profile update [!DNL API] throws *[!DNL Unexpected Error]* when using [!DNL Postman]](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-24281)|New article| Learn about how to fix the issue when running the [!DNL Target Bulk Profile Update API] throws the *[!DNL Unexpected Error]* message in [!DNL Postman].|
-->

* Informationen zur Vorabversion finden Sie unter Vorabversion von [[!DNL Adobe Target] ](https://experienceleague.adobe.com/de/docs/target/using/release-notes/target-release-notes).
* Aktuelle Informationen finden Sie unter Versionshinweise zu [[!DNL Adobe Target] ](https://experienceleague.adobe.com/de/docs/target/using/release-notes/release-notes)

+++

## [!DNL Campaign] {#ac}

Erhalten Sie die neuesten Aktualisierungen für [!DNL Adobe Campaign]. Erfahren Sie mehr über neue Tutorials und Wissensdatenbank-Support-Artikel auf Experience League.

+++Versionshinweise und Support-Artikel

### Aktuelle Campaign-Produktversionen

* [!DNL Web User Interface]: Mai 2025 - [Versionshinweise](https://experienceleague.adobe.com/de/docs/campaign-web/v8/release-notes/release-notes) | [Produktdokumentation](https://experienceleague.adobe.com/de/docs/campaign-web/v8/campaign-web-home)

* [!DNL Campaign] v8: 25. April 2025 - [Versionshinweise](https://experienceleague.adobe.com/de/docs/campaign/campaign-v8/releases/release-notes#release-8-7-4) | [Produktdokumentation](https://experienceleague.adobe.com/de/docs/campaign/campaign-v8/campaign-home)

* [!DNL Campaign Standard]: 25.1 – [Versionshinweise](https://experienceleague.adobe.com/de/docs/campaign-standard/using/release-notes/release-notes) | [Produktdokumentation](https://experienceleague.adobe.com/de/docs/campaign-standard/using/campaign-standard-home)

* [!DNL Campaign Classic] 7.4.2: Dienstag, 12. Mai 2025 – [Versionshinweise](https://experienceleague.adobe.com/de/docs/campaign-classic/using/release-notes/latest-release#release-7-4-2) | [Produktdokumentation](https://experienceleague.adobe.com/de/docs/campaign-classic/using/campaign-classic-home)

<!-- ### New [!DNL Campaign] tutorials {#tutorials-campaign}

New or updated videos tutorials published for Adobe Campaign.

| Published | Application | Name | Type | Description |
| ----------| ---------- | ---------- | ---------- |---------- |
|January 2025| |[Create and manage test profiles](https://experienceleague.adobe.com/de/docs/campaign-web-learn/tutorials/profiles-and-audiences/create-and-manage-test-profiles)|New video |Learn how to create a test profile in the client console and how to manage, and edit profiles in the Adobe Campaign Web UI.|
|January 2025| |[Enhance a delivery with dynamic content](https://experienceleague.adobe.com/de/docs/campaign-web-learn/tutorials/content-management/enhance-a-delivery-with-dynamic-content)|New video |Learn how to make message content dynamic by using the expression editor to personalize your message or add conditional content.| -->

### Neue [!DNL Campaign]-Support-Wissensdatenbank{#kb-campaign}

Neue Artikel und Aktualisierungen vorhandener Artikel für [!DNL Campaign].

| Veröffentlicht | Name | Typ | Beschreibung |
|---------|----|----|-----------|
| April 2025 | [Tracking-URL-Markierung ersetzt die richtigen URLs in Adobe Campaign](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26309) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems des Trackings von URL-Markern in Adobe Campaign. |
| April 2025 | [Exportbezeichnung für Auflistungen, die während der Dateiextraktion nicht funktionieren](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26155) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass Auflistungsbeschriftungen in Adobe Campaign-Workflows nicht korrekt exportiert werden. |
| April 2025 | [Quarantäneregeln für interne E-Mail-Adressen in Adobe Campaign Standard verwalten](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26334) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn interne E-Mail-Adressen zur Quarantänetabelle hinzugefügt werden, wodurch wichtige Nachrichten blockiert werden. |
| April 2025 | [Beheben von  [!DNL Snowflake] [!UICONTROL Laden] Problemen nach Passwortänderung in Adobe Campaign Classic](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26368) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass beim Aktualisieren des Kennworts in **[!UICONTROL Externe]**) für eine [!DNL Snowflake] in Adobe Campaign Classic Probleme mit neuen Aktivitäten [!UICONTROL Laden] auftreten. |
| April 2025 | [Suchfilter können nicht in Adobe Campaign Classic-Ordnern angezeigt werden](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26160) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass Suchfilter in Adobe Campaign Classic Hosted (v7) nicht in bestimmten Ordnern angezeigt werden. |
| April 2025 | [Rückgang der Öffnungsraten bei E-Mail-Sendungen in Adobe Campaign Classic](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26266) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass die Öffnungsraten für E-Mail-Sendungen gesunken sind, obwohl keine Änderungen an Workflows oder Inhalten vorgenommen wurden. |
| April 2025 | [Anmeldung bei nicht möglich [!DNL Adobe Campaign Managed Cloud]](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26119) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass die Anmeldung bei [!DNL Adobe Campaign Managed Cloud] zu einer Fehlermeldung führt, die besagt: *Unbekannter Authentifizierungsmodus: Verhandeln.* |
| April 2025 | [E-Mail-Seed wird als gesendet, aber nicht im Posteingang empfangen angezeigt](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26162) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass über Adobe Campaign gesendete E-Mails in den Versandlogs als gesendet angezeigt werden, aber nicht sofort im Posteingang der Empfängerin oder des Empfängers empfangen werden. |
| April 2025 | [Beheben von Problemen mit der Ordnersichtbarkeit in Adobe Campaign](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26292) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn ein bestimmter Ordner in Ihrer Adobe Campaign Classic-Instanz nicht angezeigt wird. |
| April 2025 | [Lösen von Problemen mit Load-Balancer-URLs in [!DNL Adobe Campaign Classic Hosted]](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26264) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems in [!DNL Adobe Campaign Classic Hosted], wenn die Load-Balancer-URL bei der App-Integration fehlschlägt und dies zu einem 401-Fehler aufgrund einer fehlerhaften Konfiguration für HTTPS-Anfragen führt. |

+++

## [!DNL Journey Optimizer] {#journey-opt}

Erfahren Sie mehr über die neuesten Versions-Updates für [!DNL Journey Optimizer]. Sehen Sie sich die neuesten Tutorials und Wissensdatenbank-Support-Artikel auf Experience League an.

+++Versionshinweise und neue Tutorials

### Aktuelle Informationen zu [!DNL Journey Optimizer]-Produktversionen

Neueste Version: **Mai 2025**

* Updates und Hilfe finden Sie in den [Journey Optimizer-Versionshinweisen](https://experienceleague.adobe.com/de/docs/journey-optimizer/using/whats-new/release-notes).

### Neue [!DNL Journey Optimizer]-Tutorials {#tutorials-ajo}

Neue Tutorials, die für Adobe [!DNL Journey Optimizer] auf Experience League veröffentlicht wurden.

| Veröffentlicht | Programme | Name | Typ | Beschreibung |
| ----------| ---------- | ---------- | ---------- |---------- |
| Mai 2025 | [!DNL Journey Optimizer] | [Skalieren der Orchestrierung für die Omni-Channel-Interaktion in Journey Optimizer](https://experienceleague.adobe.com/de/docs/journey-optimizer-learn/scaling-orchestration-to-omnichannel-engagement/introduction) | Neue Videos | Erfahren Sie, wie Sie die Geschäftskommunikation von grundlegenden ausgehenden Nachrichten auf anspruchsvolle Omni-Channel-Erlebnisse umstellen können. Anhand von Praxisbeispielen erstellen Sie eine Kunden-Journey, die proaktive Öffentlichkeitsarbeit mit responsiver Interaktion kombiniert. Ursprünglich auf der Adobe Summit 2025 als Lab L535 präsentiert. |
| Mai 2025 | Journey Optimizer | [Das tägliche Trigger-Journey wird nach Abschluss der Batch-Segmentierung ausgeführt](https://experienceleague.adobe.com/de/docs/journey-optimizer-learn/tutorials/create-journeys/trigger-daily-journey-runs-after-batch-segmentation-completion) | Neues Video | Erfahren Sie, wie Sie die Journey der Aktivität „Zielgruppe lesen“ so konfigurieren, dass sie erst nach Abschluss der Segmentierungsvorgänge gestartet werden, um die Datengenauigkeit und -konformität sicherzustellen. |
| Mai 2025 | Journey Optimizer; Adobe Express | [Bearbeiten von Assets mit Adobe Express](https://experienceleague.adobe.com/de/docs/journey-optimizer-learn/tutorials/content-management/assets/edit-assets-with-adobe-express) | Neues Video | Erfahren Sie, wie Sie Ihre Assets in Adobe Journey Optimizer mit Adobe Express-Tools bearbeiten. |
| Mai 2025 | [!DNL Journey Optimizer] | [Personalization-Editor-Playground](https://experienceleague.adobe.com/de/docs/journey-optimizer-learn/tutorials/personalize-content/personalization-editor-playground) | Neues Video | Erfahren Sie, wie Sie vordefinierte Code-Beispiele nutzen, Platzhalterprofil-Payloads bearbeiten und eine Vorschau der Ausgabe des Personalisierungs-Codes in Echtzeit anzeigen. |
| Mai 2025 | [!DNL Journey Optimizer]; [!DNL Experience Platform] | [Verwenden von Decisioning zur Personalisierung von Web-Angeboten](https://experienceleague.adobe.com/de/docs/journey-optimizer-learn/use-decisioning-to-personalize-web-offers/introduction?lang=en) | Neue Artikel | Erfahren Sie, wie Sie mit Journey Optimizer (AJO) [!UICONTROL Decisioning] personalisierte Angebote auf einer Web-Seite unterbreiten können, indem Sie die in [!DNL Experience Platform] (AEP) integrierte Zielgruppensegmentierung nutzen. |
| Mai 2025 | [!DNL Journey Optimizer]; [!DNL Experience Platform] | [Erstellen von Zielgruppen mithilfe von Web SDK](https://experienceleague.adobe.com/de/docs/journey-optimizer-learn/create-audiences-using-web-sdk/introduction) | Neue Artikel | Erfahren Sie, wie Sie Benutzereinstellungen über ein Web-Formular erfassen, diese Daten in Echtzeit an Adobe [!DNL Experience Platform] (AEP) senden und Benutzer basierend auf ihrer Auswahl dynamisch für Audiences qualifizieren. |

### Neue [!DNL Journey Optimizer]-Support-Wissensdatenbank{#kb-ajo}

Neue Artikel und Aktualisierungen vorhandener Artikel für [!DNL Journey Optimizer].

| Veröffentlicht | Name | Typ | Beschreibung |
|---------|----|----|-----------|
| April 2025 | [Klickverhalten bei Push-Nachrichten, die nicht zur Web-URL in AJO umgeleitet werden](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26226) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass die Konfiguration von Push-Nachrichten, die Sie beim Klicken auf die konfigurierte Web-URL umleiten, nicht wie erwartet funktioniert. |
| April 2025 | [Journey Optimizer: Transaktions-SMS werden trotz `consents.marketing.sms.value=y`](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26258) nicht zugestellt | Neuer Artikel | `STOP` Erfahren Sie mehr über die Lösung des Problems, dass durch die Reaktion auf eine SMS-Nachricht alle nachfolgenden SMS von dieser kurzen Nummer blockiert werden, einschließlich Transaktionsnachrichten. |
| April 2025 | [Beheben von Problemen mit der Zielgruppenpopulation in Adobe Journey Optimizer](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26333) | Neuer Artikel | Erfahren Sie mehr über die Lösungen für Probleme mit der Zielgruppenpopulation: fehlende Komponenten und Ressourcen, Auswirkungen auf Berechtigungen und Bereitstellung. |
| April 2025 | [Berichte zum In-App[!UICONTROL Kanal können nicht in &#x200B;] werden [!DNL Customer Journey Analytics]](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26206) | Neuer Artikel | Erfahren Sie, wie Sie Probleme beim Reporting über den [!UICONTROL inApp]Kanal in [!DNL Adobe Customer Journey Analytics] (CJA) beheben können. |
| April 2025 | [Journey Optimizer: Veraltete Zielgruppenanzahl aufgrund einer manuellen Segmentauswertung](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26166) | Neuer Artikel | Erfahren Sie mehr über die Lösungen für das Problem, dass eine Journey nicht die neuesten qualifizierten Daten widerspiegelt. |
| April 2025 | [Die Profilanzahl beim Eingeben einer Journey im Vergleich zur zugehörigen Zielgruppe in AJO stimmt nicht überein](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26253) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass die Profilanzahl beim Eingeben in eine Journey nicht mit der Profilanzahl in der zugehörigen Zielgruppe übereinstimmt, insbesondere in Journeys, die Batch-Zielgruppen verwenden. |
| April 2025 | [Beheben von Profilaktualisierungsfehlern in Adobe Journey Optimizer](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26352) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn bestimmte Feldwerte nach dem Durchlaufen eines Knotens [!UICONTROL Profil aktualisieren] in einer Journey nicht ordnungsgemäß aktualisiert zu werden scheinen. |
| April 2025 | [Kampagnen erzeugen keine erwarteten Dateien in Adobe Journey Optimizer](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26235) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass beim Starten einer wiederkehrenden Briefpostkampagne nach der Zeit des täglichen Durchlaufs die Mailings für diesen Tag nicht verarbeitet werden. |
| April 2025 | [Beheben von Problemen bei der Erstellung von Angebotssammlungen in Adobe Journey Optimizer](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26265) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass beim Erstellen von Angebotssammlungen in Adobe Journey Optimizer (AJO) Probleme auftreten, weil Kataloge nicht bereitgestellt werden. |
| April 2025 | [Aktivieren von TLS v1.3 für benutzerdefinierte Aktionen in Adobe Journey Optimizer](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26223) | Neuer Artikel | Erfahren Sie, wie Sie die Datenintegrität und -sicherheit beim Herstellen einer Verbindung zu Drittanbietersystemen gewährleisten, indem Sie [!DNL Transport Layer Security] (TLS) v1.3 für benutzerdefinierte Aktionen in AJO aktivieren. |
| April 2025 | [Beheben von Problemen mit dem Journey-Trigger nach Zielgruppenänderungen in Adobe Journey Optimizer](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26224) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass ein Journey in Adobe Journey Optimizer (AJO) nicht mehr ausgelöst wird, wenn Änderungen an der zugehörigen Zielgruppe vorgenommen werden, z. B. durch Ändern der Zusammenführungsrichtlinie. |
| April 2025 | [Aus einer Abfrage in Adobe Journey Optimizer kann kein Dashboard erstellt werden](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26201) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass Benutzer Dashboards nicht direkt aus Abfragen erstellen können. |
| April 2025 | [Adobe Journey Optimizer: Die mehrsprachige Funktion erhält *Fehler bei der Nachrichtenvalidierung (CJMMAS - 1069-500)*](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26168) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn ein *Fehler bei der Nachrichtenvalidierung (CJMMAS - 1069-500), der mit der mehrsprachigen Funktion verknüpft*, verhindert, dass Journey in den Testmodus versetzt oder veröffentlicht werden. |
| April 2025 | [Profile, die aufgrund von Ereignisbegrenzungen in Adobe Journey Optimizer beendet werden](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26018) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass Profile aufgrund von Ereignisbegrenzungen unerwartet eine Journey verlassen, was zu Kommunikationsausfällen führen kann. |
| April 2025 | [Diskrepanz im Link-Verhalten bei der Verwendung der HTML-Komponente in AJO-E-Mail-Vorlagen](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26221) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems beim Hinzufügen einer HTML-Komponente zu einer E-Mail-Inhaltsvorlage. |
| April 2025 | [Ereignis löst das Journey in Adobe Journey Optimizer nicht aus](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26031) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn bei Ereignissen manchmal kein Trigger zum beabsichtigten Journey möglich ist, selbst wenn alle Kriterien erfüllt sind. |
| April 2025 | [Adobe Journey Optimizer: Zeitüberschreitung des externen Drittanbieter-Endpunkts in der benutzerdefinierten Aktion](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26156) | Neuer Artikel | Erfahren Sie, wie Sie bei der Konfiguration einer benutzerdefinierten Aktion in Adobe Journey Optimizer (AJO) zum Aufrufen eines externen Drittanbieter-Endpunkts das Problem beheben können und wie Zeitüberschreitungsfehler auftreten. |
| April 2025 | [Anstieg der [!UICONTROL Engageable Profiles] Anzahl in Adobe Journey Optimizer](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26161) | Neuer Artikel | Erfahren Sie, warum [!UICONTROL &#x200B; Anzahl der &#x200B;] in Adobe Journey Optimizer (AJO) in kurzer Zeit erheblich ansteigen kann. |
| April 2025 | [Fehlerbehebung **[!UICONTROL Begrenzungsregeln]** Dropdown-Probleme in Adobe Journey Optimizer](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26204) | Neuer Artikel | Erfahren Sie mehr über die Lösung von Problemen mit **[!UICONTROL Dropdown-Menü &quot;]**&quot; in Adobe Journey Optimizer (AJO). |
| April 2025 | [Profile beenden Journey vorzeitig in Adobe Journey Optimizer](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26127) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass Profile unerwartet eine Journey verlassen, ohne einen bestimmten Knoten zu passieren. |
| April 2025 | [Adobe Journey Optimizer-Kontrollkästchen fehlt in [!UICONTROL Datenstrom]-Konfiguration](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26131) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn das Kontrollkästchen &quot;Adobe Journey Optimizer&quot; in der Konfiguration [!UICONTROL Datenstrom] unter dem Adobe [!DNL Experience Platform] (AEP)-Service fehlt. |
| April 2025 | [[!UICONTROL Preheader]-Feld wird im Modus **[!UICONTROL Eigenen Code erstellen]** in Adobe Journey Optimizer nicht angezeigt](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26174) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn das [!UICONTROL Preheader]-Eingabefeld für den Modus **[!UICONTROL Eigenen Code erstellen]** unter der Funktion **[!UICONTROL E-Mail-Textkörper bearbeiten]** nicht angezeigt wird. |
| April 2025 | [Zugriff auf **[!UICONTROL Offer Decisioning]** in Adobe Journey Optimizer nicht möglich](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26175) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass beim Integrieren von Adobe Target in eine Anwendung mit Adobe Journey Optimizer (AJO) eine Warnung angezeigt wird, die darauf hinweist, dass auf die Option **[!UICONTROL Offer Decisioning]** in der Konfiguration [!UICONTROL Datenstrom] nicht zugegriffen werden kann. |
| April 2025 | [Beheben von Zugriffsproblemen mit [!DNL Adobe Journey Optimizer Query Service API]](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26196) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems Wenn Sie versuchen, über [!DNL Postman] oder ähnliche Tools auf die [!DNL Adobe Journey Optimizer Query Service API] zuzugreifen, treten Zugriffsfehler aufgrund unzureichender Berechtigungen auf. |
| April 2025 | [Mail-Exchange-Fehler beim Einrichten von API-ausgelösten Transaktions-E-Mail-Kampagnen in AJO](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26200) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass Sie beim Einrichten einer API-ausgelösten Transaktions-E-Mail-Kampagne in Adobe Journey Optimizer (AJO) aufgrund eines MX-Fehlers keine neue Kanalkonfiguration erstellen können. |
| April 2025 | [Journey Optimizer: Falsch konfigurierte `AFTER` sendet E-Mails an eine unbeabsichtigte Zielgruppe](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26173) | Neuer Artikel | Erfahren Sie mehr über die Lösung eines falsch konfigurierten Problems mit der `AFTER` in Adobe Journey Optimizer (AJO), das dazu führt, dass E-Mails an Mitglieder gesendet werden, die nicht als Teil der vorgesehenen Zielgruppe qualifiziert sind. |
| April 2025 | [In AJO kann kein Datei-Routing für  [!DNL Azure]  eingerichtet werden](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26323) | Neuer Artikel | Erfahren Sie, wie Sie das Problem lösen können, wenn Sie beim Einrichten des [!UICONTROL -Routings für Ausgabedateien des &#x200B;]Versandmanagements) von Adobe Journey Optimizer (AJO) nach [!DNL Azure] einen Fehler aufgrund einer falschen Konfiguration der [!DNL Azure]-Verbindungszeichenfolge und des -Containers auftritt. |
| April 2025 | [Das Journey wird für das Profil nicht ausgelöst, obwohl die Ereignisbedingungen erfüllt sind](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26305) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass es in der [!DNL Journey Orchestration] von Adobe [!DNL Experience Platform] (AEP) Fälle gibt, in denen eine Journey für ein bestimmtes Profil keinen Trigger erstellt, obwohl die Ereignisbedingungen erfüllt sind. |

### Zusätzliche Ressourcen zu [!DNL Journey Optimizer]

* [[!DNL Journey Optimizer] Dokumentation](https://experienceleague.adobe.com/de/docs/journey-optimizer/using/ajo-home) – [Versionshinweise](https://experienceleague.adobe.com/de/docs/journey-optimizer/using/whats-new/release-notes) – [Videoanleitungen](https://experienceleague.adobe.com/de/docs/journey-optimizer-learn/tutorials/overview)
* [Dokumentation zum Entscheidungs-Management](https://experienceleague.adobe.com/de/docs/journey-optimizer/using/decisioning/offer-decisioning/get-started-decision/starting-offer-decisioning) – [Versionshinweise](https://experienceleague.adobe.com/de/docs/journey-optimizer/using/whats-new/release-notes) – [Anleitungsvideos](https://experienceleague.adobe.com/de/docs/journey-optimizer-learn/tutorials/decision-capabilities/decision-management/introduction-to-decision-management) – [Neueste Aktualisierungen der Dokumentation](https://experienceleague.adobe.com/de/docs/journey-optimizer/using/whats-new/documentation-updates)

+++

## [!DNL Journey Optimizer B2B Edition] {#ajo-b2b}

Erfahren Sie mehr über die neuesten Versionsinformationen für [!DNL Journey Optimizer B2B Edition].

+++Versionshinweise und Dokumentation

Neueste Version: **10. April 2025**

* [Journey Optimizer B2B edition](https://experienceleague.adobe.com/de/docs/journey-optimizer-b2b) (alle Selbsthilfe)
* [Versionshinweise](https://experienceleague.adobe.com/de/docs/journey-optimizer-b2b/user/release-notes) für Journey Optimizer B2B edition
* [Produktdokumentation](https://experienceleague.adobe.com/de/docs/journey-optimizer-b2b/user/guide-overview) für Journey Optimizer B2B edition
* [Videoübersichten und Tutorials](https://experienceleague.adobe.com/de/docs/journey-optimizer-b2b-learn/tutorials/overview) für Journey Optimizer B2B edition
* [Produktbeschreibung und Lizenzierung](https://helpx.adobe.com/de/legal/product-descriptions/adobe-journey-optimizer-b2b.html#_blankl) für Journey Optimizer B2B edition

<!-- New videos, tutorials, or courses published for Journey Optimizer B2B Edition.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|February 2025|[Account Journeys](https://experienceleague.adobe.com/de/docs/journey-optimizer-b2b-learn/tutorials/account-journeys/introducing-account-journeys)|New videos |Visit the Account Journeys tutorial home. Learn about Account Journeys and how to use them to engage your target audience.|
|February 2025|[Use Case Playbook - Abandoned shopping cart](https://experienceleague.adobe.com/de/docs/journey-optimizer-learn/tutorials/use-cases/abandoned-cart)|New video |Learn how to implement the abandoned shopping cart use case, using the Playbook feature in Adobe Journey Optimizer.|
|February 2025|[Import and activate an audience by uploading a CSV file](https://experienceleague.adobe.com/de/docs/journey-optimizer-learn/tutorials/profiles-audiences-subscriptions/import-and-activate-an-audience-by-uploading-a-csv-file)|New video |Discover how to efficiently import and activate an audience by uploading a CSV file. Learn to personalize your content using enrichment attributes from the CSV file, ensuring a more tailored experience for your audience.| -->

Weitere Informationen finden Sie unter:

* Produktinformationen finden Sie unter [[!DNL Journey Optimizer B2B Edition]](https://business.adobe.com/de/products/journey-optimizer-b2b-edition.html).

+++

## [!DNL Marketo Engage] {#marketo}

Neueste Versionshinweise und Veröffentlichungszeitpläne für [!DNL Marketo Engage].

+++Versionshinweise, Tutorials und Support-Artikel

### Wesentliche Marketo Engage-Aktualisierungen

* Die neuesten Informationen finden Sie unter [Aktuelle Versionshinweise](https://experienceleague.adobe.com/de/docs/marketo/using/release-notes/current).
* Aktuelle Informationen zum Veröffentlichungszeitplan sowie Versionshinweise finden Sie in der [!DNL Marketo Engage]-[Versionsplanung](https://experienceleague.adobe.com/de/docs/marketo/using/release-notes/release-schedule).

<!-- ### New Marketo tutorials {#tutorials-marketo}

New tutorials published for Adobe Marketo.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|March 2025|[Best practices to implement live chat](https://experienceleague.adobe.com/de/docs/marketo-learn/tutorials/dynamic-chat/live-chat-best-practices)| New video |Learn about the best practices to follow when you're implementing the live chat feature in Dynamic Chat.| -->

Die neueste Produktdokumentation finden Sie auf der Startseite der [Marketo-Produktdokumentation](https://experienceleague.adobe.com/de/docs/marketo/using/home)

### Neue [!DNL Marketo]-Support-Wissensdatenbank

Neue Artikel und Aktualisierungen vorhandener Artikel für [!DNL Marketo].

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| April 2025 | [[!UICONTROL Everytouch-Attribution] -Einstellung ändert sich unerwartet in [!DNL Marketo Measure]](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26378) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, wenn die [!UICONTROL Everytouch-Attributionsmethode] in [!DNL Marketo Measure] unerwartet zwischen **[!UICONTROL Verwenden der Kontaktrolle]** und **[!UICONTROL Verwenden der Konto-ID]** wechselt. |

+++

## [!DNL Workfront] {#workfront}

Erfahren Sie mehr über die neuesten Versionshinweise für [!DNL Adobe Workfront]. Suchen Sie neue Tutorials auf Experience League.

+++Versionshinweise und neue Tutorials

### [!DNL Adobe Workfront]-Updates

* [Versionsübersicht für das zweite Quartal 2025](https://experienceleague.adobe.com/de/docs/workfront/using/product-announcements/product-releases/release-25-q2/25-q2-release-overview)

Für alle Versionsinformationen:

* Informationen zur Versionsplanung und die Versionshinweise für [!DNL Workfront]. finden Sie auf der Seite [Adobe [!DNL Workfront] -Produktversionen](https://experienceleague.adobe.com/de/docs/workfront/using/product-announcements/product-releases/product-releases)

* Die neuesten Informationen zu Fusion finden Sie in der [Übersicht zur Adobe [!DNL Workfront] Fusion-Versionsaktivität](https://experienceleague.adobe.com/de/docs/workfront-fusion/using/fusion-release-activity/fusion-release-activity).

### Neue Adobe [!DNL Workfront]-Tutorials {#tutorials-workfront}

Neue [!DNL Workfront]-Tutorials und -Ereignisse auf Experience League.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Mai 2025 | [Erstellen einer Zeitleisten-Ansicht](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/workfront-planning/create-and-manage-timeline-views) | Neues Video | Erfahren Sie, wie Sie Zeitleisten-Ansichten in Workfront Planning verwalten und anpassen. |
| Mai 2025 | [Verstehen Sie mehrere Abrechnungssätze](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/manage-work/project-finances-users/multiple-billing-rates) | Neues Video | Erfahren Sie, wie Sie Abrechnungssätze für Aufgabengebiete in einem Projekt verwalten und anpassen. |
| Mai 2025 | [Einrichten von Wechselkursen](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/set-up-exchange-rates) | Neues Video | Passen Sie Währungseinstellungen mit flexibler Wechselkursverwaltung, globaler Anpassung und manuellen Eingabemöglichkeiten für eine genaue Finanzverfolgung an. |
| Mai 2025 | [Finanzen aktualisieren](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/manage-work/project-finances-users/update-and-review-finances) | Neues Video | Optimieren Sie die Kostennachverfolgung und Abrechnung, indem Sie Sätze definieren, Aufgaben Kosten- und Umsatztypen zuweisen, Ausgaben verwalten und Rechnungsnachweise erstellen. Workfront übernimmt nicht die eigentliche Abrechnung. |
| Mai 2025 | [Grundlegendes zu Leistungsmetriken](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/understand-performance-metrics) | Neues Video | Entdecken Sie anpassbare Finanzleistungsmetriken mit flexiblen Berechnungsmethoden, globalen Standardwerten und Überschreibungen auf Projektebene. |
| Mai 2025 | [Richten Sie Standard-Aufgabenumsätze und -kosten ein](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/set-up-task-revenue-and-cost-defaults) | Neues Video | Erfahren Sie, wo die Umsatztypen und Kostentypen verwendet werden und wie Sie die Systemstandardwerte einrichten. |
| Mai 2025 | [Verstehen des finanziellen Zugriffs](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/understand-financial-access) | Neues Video | Erfahren Sie, wie Sie den Zugriff auf Finanzdaten durch anpassbare Berechtigungen steuern und so sicherstellen können, dass eine sichere Verwaltung, Aufsicht auf Projektebene und maßgeschneiderte Freigabeoptionen für finanzielle Sichtbarkeit gewährleistet sind. |
| Mai 2025 | [Ausgabentypen einrichten](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/administration-and-setup/project-finances/set-up-expense-types) | Neues Video | Erfahren Sie, wie Sie beim Eingeben von Ausgaben vorgefertigte Ausgabentypen verwenden und wie Sie neue Ausgabentypen erstellen. |
| Mai 2025 | [Erstellen eines Basisfilters](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-a-basic-filter) | Neues Video | Erfahren Sie, wie Sie in Workfront Filter erstellen und verwenden, um Listenberichte anhand bestimmter Kriterien anzupassen. |
| Mai 2025 | [Grundlegendes zu Berichtskomponenten](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/reporting-components) | Neues Video | Lernen Sie Reporting-Komponenten kennen, mit denen Sie die Datenvisualisierung mit objektbasierten Filtern, dynamischen Ansichten, strukturierten Gruppierungen und Platzhalterfunktionen für maßgeschneiderte Einblicke verfeinern können. |
| Mai 2025 | [Finanz-Informationen suchen](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/manage-work/project-finances-users/find-financial-information) | Neues Video | Erfahren Sie, wie Sie effizient auf Finanzdaten für Projekte und Aufgaben zugreifen, diese analysieren und verwalten können. Dabei werden Budgets, Einnahmen, Kosten und Leistungsmetriken sowohl auf Projekt- als auch auf Aufgabenebene abgedeckt. |
| Mai 2025 | [Erstellen von Berichten mit Diagrammen](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-reports-with-charts) | Neues Video | Erfahren Sie, wie Sie Diagramme verwenden können, um Daten effektiv zu visualisieren, insbesondere zur Verfolgung von Projektaufgaben. |
| Mai 2025 | [Installieren des Microsoft Outlook-Add-ins](https://experienceleague.adobe.com/de/docs/workfront-learn/tutorials-workfront/integrations/outlook/integrations-microsoft-outlook) | Neues Video | Erfahren Sie, wie Sie das Microsoft Outlook-Add-in installieren, um den Microsoft Outlook-Kalender in den Workfront-Startseiten-Kalender zu integrieren. |


### Neue [!DNL Workfront]-Support-Wissensdatenbank

Neue Artikel und Aktualisierungen vorhandener Artikel für [!DNL Workfront].

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| April 2025 | [Beheben von 500 Fehlern in  [!DNL Adobe Workfront Fusion] Szenarien](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26250) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass [!DNL Adobe Workfront Fusion] Szenarien mit der folgenden Meldung den Fehler 500 zurückgeben: *`[ 500] Cannot invoke "java.lang.Class.getName()" because "cls" is null.`* |
| April 2025 | [Unfähigkeit zum Löschen persönlicher Projekte in Adobe Workfront wird behoben](https://experienceleague.adobe.com/de/docs/experience-cloud-kcs/kbarticles/ka-26238) | Neuer Artikel | Erfahren Sie mehr über die Lösung des Problems, dass Admins fälschlicherweise erstellte persönliche Projekte nicht löschen oder abschließen können. |

Die neueste Produktdokumentation finden Sie auf der Startseite der [Adobe [!DNL Workfront] -Dokumentation](https://experienceleague.adobe.com/de/docs/workfront/using/home).

+++

## GenStudio for Performance Marketing {#genstudio-marketing}

Aktuelle Versionshinweise und neue Dokumentation für [!DNL GenStudio for Performance Marketing].

+++Versionshinweise und Dokumentation

* [2025.04.10 - ](https://experienceleague.adobe.com/de/docs/genstudio-for-performance-marketing/user-guide/release-notes#latest) für GenStudio for Performance Marketing
* [GenStudio for Performance Marketing](https://experienceleague.adobe.com/de/browse/genstudio-for-performance-marketing) (Nur Selbsthilfe)
* [Produktdokumentation](https://experienceleague.adobe.com/de/docs/genstudio-for-performance-marketing/user-guide/home) für GenStudio for Performance Marketing
* [GenStudio for Performance Marketing](https://business.adobe.com/de/products/genstudio-for-performance-marketing.html) – Produktinformationen

+++

## [!DNL Mix Modeler] {#mix-modeler}

+++Versionshinweise und Dokumentation

Aktuelle Informationen finden Sie auf den folgenden Seiten:

* Mix Modeler [März/April 2025 - Versionshinweise](https://experienceleague.adobe.com/de/docs/mix-modeler/using/releases/latest)
* [Produktdokumentation](https://experienceleague.adobe.com/de/docs/mix-modeler) zu Mix Modeler

+++

## Adobe [!DNL Advertising] {#advertising}

Aktuelle Versionshinweise und neue Dokumentation für [!DNL Adobe Advertising].

+++Versionshinweise

Um die Hilfe zu Adobe [!DNL Advertising] zu durchsuchen, sehen Sie sich die [Dokumentation zu Adobe Advertising](https://experienceleague.adobe.com/de/docs/advertising) an.

### Neue Funktionen in [!DNL Advertising DSP] {#advertising-dsp}

&#x200B;7. Mai 2025

Siehe [Neue Funktionen in [!DNL Advertising DSP]](https://experienceleague.adobe.com/de/docs/advertising/dsp/home)

### Neue Funktionen in [!DNL Advertising Search, Social, & Commerce] {#advertising-search}

&#x200B;26. März 2024

Siehe [Neue Funktionen in [!DNL Advertising Search, Social, & Commerce]](https://experienceleague.adobe.com/de/docs/advertising/search-social-commerce/home)

+++

## [!DNL Adobe Pass] {#pass}

[!DNL Adobe Pass] ist eine Multiscreen-TV-Plattform, mit der Rundfunkanbieter, Kabelnetzwerke und Dienstleister ansprechende, personalisierte Erlebnisse erstellen und monetarisieren können.

+++Dokumentation

Neue Tutorials für Adobe Pass veröffentlicht.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- |---------- |
| April 2025 | [Adobe Pass - neue REST-API v2](https://experienceleague.adobe.com/de/docs/events/experience-league-recorded-events/solution/hidden/adobe-pass-rest-api-v2) | Neues Video | Erfahren Sie mehr über die neue REST-API v2 von Adobe und den Migrationsprozess. |

In der [Dokumentation von Adobe Pass](https://experienceleague.adobe.com/de/docs/pass) finden Sie veröffentlichungsspezifische Informationen, Systemanforderungen, Einschränkungen, behobene und bekannte Probleme.

+++

## [!DNL Document Cloud] {#doc-cloud}

Neue Tutorials, die für [!DNL Document Cloud], einschließlich [!DNL Acrobat Services] und [!DNL Acrobat Sign], veröffentlicht wurden.

+++Neue Tutorials

Neue Tutorials, die für Adobe Document Cloud veröffentlicht wurden.

| Veröffentlicht | Anwendung | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |---------- |
| Mai 2025 | Programme | [Kommentar zu einer PDF](https://experienceleague.adobe.com/de/docs/document-cloud-learn/acrobat-learning/getting-started/comment-on-pdf-files) | Aktualisiertes Video | Erfahren Sie, wie Sie mithilfe eines Webbrowsers Kommentare zu einer freigegebenen PDF hinzufügen. Unabhängig davon, ob Sie mit einem Team zusammenarbeiten oder ein Dokument Korrektur lesen: Die Kommentierungs-Tools von Acrobat erleichtern die Bereitstellung von klarem und umsetzbarem Feedback. |

Zu [!DNL Document Cloud]-Tutorials siehe:

* [Adobe Acrobat](https://experienceleague.adobe.com/de/docs/document-cloud-learn/acrobat-learning/overview)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/de/docs/document-cloud-learn/sign-learning-hub/overview)
* [Adobe Acrobat Services API-Tutorials](https://experienceleague.adobe.com/de/docs/acrobat-services-learn/tutorials/overview)
* [Document Cloud: Schulungen und Support](https://helpx.adobe.com/de/support/document-cloud.html)

+++

## [!DNL Creative Cloud] für Unternehmen {#creative-cloud}

Neue Tutorials, die für Anwendungen in [!DNL Adobe Creative Cloud for enterprise] veröffentlicht wurden.

+++Neueste Tutorials

<!-- | Published | Application | Name | Type | Description |
| -----------| ---------- | ---------- | ---------- |---------- |
| February 2025 | Applications | [Effortless brand consistency with templates](https://experienceleague.adobe.com/de/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/use-templates) | New video | Learn how to create on-brand content quickly and efficiently across your entire organization. This tutorial walks through how to create fresh new on-brand content that can immediately be shared and localized.|
| February 2025 | Applications | [Maximize efficiency: Create reusable templates](https://experienceleague.adobe.com/de/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expresshowto/create-templates) | New video | Learn how to bring brand consistency, efficiency, professionalism, and cost savings to your organization with Adobe Express templates. | -->

Unter [Creative Cloud für Unternehmen – Tutorials](https://experienceleague.adobe.com/de/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview) finden Sie die neuesten Tutorials.

+++

## Customer Data Management – Voices {#voices}

[Customer Data Management - Voices](https://experienceleague.adobe.com/de/docs/events/customer-data-management-voices-recordings/overview) bietet eine Sammlung von Informationsmaterialien für technische Experten und Marketing-Spezialisten im Kundendaten-Management. Hier finden Sie Tutorials sowie die Möglichkeit, von Berufskollegen zu hören, sich inspirieren zu lassen und sich über Entwicklungen im Bereich MarTech zu informieren. Keine Registrierung erforderlich, einfach anklicken und ansehen.

## Blueprints für digitale Erlebnisse {#blueprints}

[Digital Experience Blueprints](https://experienceleague.adobe.com/de/docs/blueprints-learn/architecture/overview) sind wiederholbare Implementierungen, die Ihnen helfen, Strategien zu entwickeln und bestehende geschäftliche Herausforderungen zu meistern. Jeder Blueprint bietet eine Reihe von Artefakten, die jeweils die anspruchsvolle geschäftliche Herausforderung, die Architekturen, die Implementierungsschritte und die technischen Überlegungen erläutern, sowie die Links zur entsprechenden Dokumentation.

<!-- |Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|January 2025|[Guardrails](https://experienceleague.adobe.com/de/docs/blueprints-learn/architecture/architecture-overview/deployment/guardrails)|Updated article |Learn about guardrails, the performance expectations and impact for the components and services within Adobe Experience Platform and Applications.| -->

<!-- ## ![Icon](/assets/certification-badge.png) Certification{#certification}

Attention all Adobe certification candidates! Visit the Experience Cloud [Certification](https://experienceleague.adobe.com/de/docs/certification/program/overview) site on Experience League. 

+++Details

The [Experience Cloud Certification](https://experienceleague.adobe.com/de/docs/certification/program/overview) site is your one-stop shop for all [!DNL Experience Cloud] certification-related content and is updated regularly with:

* Available certifications
* Certification renewals for Adobe applications
* Certification program updates

And more! Head over to [Adobe Certification](https://experienceleague.adobe.com/de/docs/certification/program/overview) on Experience League and start your certification journey today!

+++ -->

