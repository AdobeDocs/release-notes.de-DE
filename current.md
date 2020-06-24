---
title: Adobe Experience Cloud – Versionshinweise
description: Adobe Experience Cloud – Versionshinweise
doc-type: release notes
last-update: June 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 1fe0c0a5b892802837115df53c2f178e6e0ee81c
workflow-type: tm+mt
source-wordcount: '7082'
ht-degree: 34%

---


# Versionshinweise zu Adobe Experience Cloud - Juni 2020

![Banner](/assets/experience-cloud-banner-3.png)

This page describes new features, fixes, and important notices in [!DNL Adobe Experience Cloud]. Außerdem werden neue Dokumentationen, Schulungen und Videoschulungen vorgestellt, die Ihnen helfen, das Experience Cloud optimal zu nutzen.

>[!NOTE]
>
>Abonnieren Sie das [Prioritätsprodukt-Update von Adobe](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bevorstehende Versionen benachrichtigt zu werden.

**Releasedatum: 18. Juni 2020**

Das Datum der Produktveröffentlichung kann variieren. Suchen Sie regelmäßig nach Updates.

Letzte Aktualisierung: **18. Juni 2020**

* [Systemstatus von Adobe](#status)
* [Experience Cloud-Benutzeroberfläche](#ecloud)
* [Experience Platform](#platform)
* [Journey-Orchestrierung](#journey-orch)
* [Analytics](#analytics) (und [Customer Journey Analytics](#cust-journey))
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Kampagne](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/de-DE/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/de/primetime/user-guide.html) (Link zur Primetime-Hilfeseite)

Benötigen Sie Hilfe? Besuchen Sie [Adobe Experience League](https://experienceleague.adobe.com/#home) , um Produkt- und technische Dokumentation, von Adobe kuratierte Kurse, Videoschulungen, schnelle Antworten, Community-Einblicke und Schulungen unter Anleitung von Lehrern zu erhalten.

## ![Symbol](/assets/adobe.png) Systemstatus von Adobe {#status}

[!UICONTROL Der Adobe-Systemstatus] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe Cloud-Produkten und -Diensten. Weitere Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/).

Herausgegeben: **21. Mai 2020**

**Neuigkeiten**

* Mit Ihrer Adobe ID können Sie Ereignisbenachrichtigungen mit größerer Granularität bis hinunter zur Produktangebot- und Add-on-Ebene abonnieren. Um die Konfiguration Ihres Abonnements zu beschleunigen, wird bei der Abonnement-Selbstregistrierung jetzt eine Auswahl von Produkten und Dienstleistungen empfohlen, die auf Ihren Produktberechtigungen basieren. Dies sollte die Anzahl der E-Mails, die Sie erhalten, reduzieren und relevantere Benachrichtigungen in Ihrem Posteingang liefern. Weitere Informationen erhalten Sie unter [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Ab heute verfügbare neue Funktionen und Verbesserungen**

| Funktion | Beschreibung |
| -----------| ---------- |
| Verbessertes Kundenerlebnis bei Abonnements und Benachrichtigungen | <ul><li>Regionale [!DNL Marketo Engage]-Standorte werden nun anhand der Liste der ausgewählten Produktangebote gefiltert.</li><li>E-Mail-Benachrichtigungen von [!DNL Marketo Engage] sind für die Region, den Standort und die Umgebungsvoreinstellungen eines Benutzers relevant.</li></ul> |
| Bestätigungen von Ereignis-Abonnements | <ul><li>Sie können jetzt eine E-Mail-Bestätigung erhalten, wenn Sie laufende Aktualisierungen für einzelne Ereignisse abonnieren.</li></ul> |
| Verbesserungen der Benutzerfreundlichkeit der globalen Navigation | <ul><li>Konsistentes Kundenerlebnis im obersten Navigationsmenü auf `Adobe.com`.</li></ul> |

## ![Symbol](/assets/ec_appicon_24.png) Experience Cloud-Benutzeroberfläche {#ecloud}

Allgemeine Aktualisierungen der Experience Cloud-Oberfläche.

**Einheitliche Produktdomäne**

Adobe hat die Domäne und die Kopfzeile der Benutzeroberfläche aktualisiert, um Ihr Benutzererlebnis in allen Experience Cloud-Anwendungen zu vereinheitlichen und zu verbessern. Diese Verbesserungen sollen das Benutzererlebnis auf kleine, aber wichtige Weise vereinfachen. Ihre aktuellen Workflows werden dadurch nicht geändert.

Zu den Aktualisierungen gehören:

* Neue Anwendungs-URLs: `experience.adobe.com/<application name>`:
   * Dieses URL-Muster wird schließlich von allen Produkten übernommen. Im Laufe des Monats werden neue URLs hinzugefügt werden.
   * Browserunterstützung: Unterstützte Browser sind [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] und [!DNL Opera] (neueste Versionen). **Hinweis:** Obwohl die Experience Cloud-Oberfläche diese Browser unterstützt, werden nicht alle Browser von einzelnen Anwendungen unterstützt. ([Analytics](https://docs.adobe.com/content/help/de-DE/analytics/admin/sys-reqs.html) unterstützt beispielsweise nicht [!DNL Opera] und [Target](https://docs.adobe.com/help/de-DE/target/using/implement-target/before-implement/supported-browsers.html) unterstützt nicht [!DNL Safari].)
   * (Nur [!DNL Safari]) Die Domänenänderung kann bei [!DNL Safari] zu Cookie-Problemen führen. Wenn Sie in den Datenschutzvoreinstellungen von [!DNL Safari] die Option _Prevent cross-site tracking_ (Website-übergreifendes Tracking verhindern) deaktivieren, werden domänenübergreifende Cookies (und alle Site-übergreifenden Ereignisse) aktiviert, sodass Experience Cloud in dieser neuen Domäne funktionieren kann.
* Einfacherer Wechsel zwischen Ihren Organisationen oder zu einer anderen Anwendung.
* Verbesserte Produkthilfe: [!UICONTROL Experience League] ist in das Produkt integriert, sodass bei einer Hilfesuche auch Ergebnisse aus Community-Foren und Videos berücksichtigt werden. Diese Änderung vereinfacht den Zugriff auf weitere Inhalte und hilft Ihnen, Experience Cloud optimal zu nutzen. Zusätzlich können Sie unter **[!UICONTROL Hilfe]** > **[!UICONTROL Feedback]** Probleme melden oder Ihre Ideen mit Adobe teilen.

Die folgenden Anwendungen verwenden die neue Domäne „experience.adobe.com“:

| Anwendung oder Dienst | Domäne |
| -----------| ---------- |
| Experience Cloud-Startseite | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Journey Management | `experience.adobe.com/journeys` |
| Adobe Analytics | `experience.adobe.com/analytics` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Control Panel von Adobe Campaign | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Softwareverteilung | `experience.adobe.com/downloads` |
| Admin-Tool (Beta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Pinnwand und Kollektionen]**, ein veralteter Filter in der [!UICONTROL Experience Cloud-Assets]-Auswahl, werden derzeit entfernt.

## ![Symbol](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Release notes for the [!DNL Experience Platform] and application services, including [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], and security bulletins.

Releasedatum: **10. Juni 2020**

[!DNL Adobe Experience Platform] umfasst die folgenden neuen Funktionen:

* **Data Science Workspace** Das [!DNL JupyterLab Launcher] enthält jetzt einen [!DNL Python] Notebook-Starter für Echtzeit-Maschinelles Lernen (Alpha).
* **Segmentierung:** Es wurde ein Feld für das Ablaufdatum für Datumsfunktionen hinzugefügt, mit dem Benutzer Daten ohne Jahr auswerten können.
* **Quellen:** Neue Quellanschlüsse für [!DNL Apache HDFS] und [!DNL Couchbase].

Weitere Informationen zu diesen Funktionen finden Sie in den Versionshinweisen zur [Experience Platform](https://docs.adobe.com/content/help/de-DE/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md).

### Zusätzliche Versionsinformationen zu Experience Platform

* [Experience Platform Launch – Versionshinweise](https://docs.adobe.com/content/help/de-DE/launch/using/intro/release-notes/current.html)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/de/security.html) (alle Adobe-Produkte)

### Neue Experience Platformen - Kurse und Tutorials {#tutorials-plat}

| Inhalt | Content-Typ | Beschreibung |
| -----------| ---------- | ---------- |
| [Einführung in die Adobe Experience Platform](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1) | Kurs | Erfahren Sie, wie Adobe Experience Platform Ihnen dabei hilft, das richtige Erlebnis zu bieten, indem Sie Ihre Daten in robuste Echtzeit-Profil und AI-basierte Einblicke umwandeln, die Sie in jedem Kanal aktivieren können. Dieser Einführungskurs gibt Ihnen einen Überblick über die Funktionen, Anwendungsfälle, die Beziehung zu Adobe Experience Cloud, die Basisarchitektur, Benutzeroberfläche und Projektrollen der Experience Platform. |
| [Einführung in Web SDK und Edge Network](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html) | Videoschulung | Eine Übersicht über Adobe Experience Platform SDK und Edge Network. Experience Platform Web SDK ist eine clientseitige JavaScript-Bibliothek, mit der Kunden eine JavaScript-Bibliothek, einen Beacon-Typ, einen Datenstrom, ein und ein serverseitiges Ziel verwenden können, um Daten an alle Adobe-Anwendungen und an Drittanbieter-Ziele zu senden. |
| [Demo von Web SDK und Edge Network](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html) | Videoschulung | Sehen Sie sich das Web-SDK und das Edge-Netzwerk der Adobe Experience Platform in Aktion an, und senden Sie Daten an Adobe mit einem einzigen Aufruf an Experience Platform, Analytics, Audience Manager und Target. |
| [Demo zur Platform von Kundendaten in Echtzeit](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html) | Videoschulung | Erfahren Sie, wie Echtzeit-CDP zur Datenerfassung aus mehreren Quellen verwendet wird. Sie können diese Daten zu einem einzigen Echtzeit-Kundenerlebnis zusammenführen und diese Daten aktivieren, um personalisierte Kundenerlebnisse zu erstellen. |

## ![Symbol](/assets/experience_platform_appicon_24.png) Customer Journey Orchestration {#journey-orch}

Mithilfe der Adobe Experience Platform können Sie individuelle Customer Journeys maßstabsgetreu über verschiedene Erlebniskanäle orchestrieren, indem Sie die Bedürfnisse jedes einzelnen Kunden in Echtzeit und unabhängig vom Zielort intelligent antizipieren.

### Neueste Version

Die neuesten Versionshinweise finden Sie unter Versionshinweise zur [Journey Orchestration](https://docs.adobe.com/content/help/de-DE/journeys/using/release-notes/release-notes.html)

### Neue Journey Orchestrationen - Kurse und Tutorials {#jo-tutorials}

| Inhalt | Content-Typ | Beschreibung |
| -----------| ---------- | ---------- |
| [Erste Schritte mit Journey Orchestration für Administratoren](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2) | Kurs | Erfahren Sie, wie Sie Journey Orchestration konfigurieren und verwenden. In diesem Kurs werden die wichtigsten Konzepte und Konfigurationsschritte erläutert, die für die Orchestrierung einer Reise erforderlich sind. Erfahren Sie, wie Sie Orchesterreisen erstellen, veröffentlichen und wie Sie sie dokumentieren und analysieren können. |
| [Erste Schritte mit der Journey Orchestration für Geschäftsbenutzer](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1) | Kurs | Erfahren Sie, wie Sie Journey Orchestration konfigurieren und verwenden. Dieser Kurs behandelt die wichtigsten Konzepte. Sie lernen, wie Sie Ihre Orchesterreisen erstellen, veröffentlichen, berichten und analysieren können. |

### Zusätzliche Ressourcen für die Journey Orchestration

[Dokumentation](https://docs.adobe.com/content/help/de-DE/journeys/using/journey-orchestration-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/journeys/using/release-notes/release-notes.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Symbol](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Releasedatum: **18. Juni 2020**

* [Neue Funktionen in Adobe Analytics](#aa-features)
* [Neue Funktionen in Customer Journey Analytics](#cust-journey)
* [Neue Funktionen in Media Analytics](#media-aa)
* [Fehlerbehebungen in Adobe Analytics](#aa-fixes)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [Neue Adobe Analytics-Kurse und -Tutorials](#tutorials-analytics)
* [AppMeasurement](#appm)

### Neue Funktionen in Adobe Analytics {#aa-features}

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/de-DE/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| -----------| ---------- |-------|
| Zuordnung IQ: Algorithmische Zuordnung | 18. Juni 2020 | Das [!UICONTROL algorithmische Zuordnungsmodell] in Analysis Workspace verwendet statistische Verfahren, um die optimale Zuordnung der Gutschrift für die ausgewählte Metrik dynamisch zu bestimmen. Verfügbar für Kunden von Adobe Analytics Ultimate. [Mehr Infos...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| Zuordnung IQ: Benutzerdefinierte Lookback-Fenster | 18. Juni 2020 | Sie können jetzt jedes Zuordnungsmodell in [!UICONTROL Attribution IQ] so konfigurieren, dass Touchpoints von bis zu 90 Tagen vor dem Zeitraum des Berichte einbezogen werden. Dies erhöht in der Regel die Zuordnungsgenauigkeit für Ereignis, die frühzeitig im Berichte auftreten, indem Interaktionen berücksichtigt werden, die im/den Vormonat/en aufgetreten sind. Verfügbar für Kunden mit Adobe Analytics Foundation, Select, Prime, Premium, Premium Attribution, Premium Complete und Ultimate. [Mehr Infos...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Projektrollen für freigegebene Workspace-Projekte | 18. Juni 2020 | Beim Freigeben eines Workspace-Projekts können Sie nun Empfänger je nach Projekterfahrung in eine der drei Rollen setzen: Bearbeiten, Duplikat und Ansicht. [Mehr Infos...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Arbeitsbereich-Projekte, die nur für Ansichten gedacht sind | 18. Juni 2020 | Workspace-Projekte können nur als &quot;Kann Ansicht&quot;freigegeben werden. Wenn ein Empfänger der Ansicht das freigegebene Projekt öffnet, erhält er eine restriktivere Projekterfahrung ohne linke Leiste und eingeschränkte Interaktionen. [Mehr Infos...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Möglichkeit zur Kobearbeitung von Workspace-Projekten | 18. Juni 2020 | Empfänger, die der Rolle &quot;Kann bearbeiten&quot;hinzugefügt wurden, können über einem Projekt speichern, das für sie freigegeben wurde. Dies gilt sowohl für Administratoren als auch für Nicht-Administratoren. [Mehr Infos...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Aktualisiertes leeres Bedienfeld in Workspace | 18. Juni 2020 | Der leere Bereich in Workspace umfasst jetzt Bedienfelder und Visualisierungen, sodass Sie den Arbeitsablauf für die Analyse, der für Sie am besten geeignet ist, nahtloser wählen können. |
| In China RDC verfügbare Erstanbieter-Domänen | 18. Juni 2020 | Ermöglicht Kunden mit einer `.cn` Domäne, eine Erstanbieterdomäne zur Verwendung innerhalb von Mainland China anzufordern. (Dokumentation verfügbar mit dem Kauf der SKU &quot;China Performance Optimization&quot;.) |
| Bereich „Quick Insights“ in Arbeitsbereich | 25. Juni 2020 | Quick Insights bietet Nicht-Analytikern und neuen Benutzern von Analysis Workspace eine Möglichkeit, betriebliche Fragen schnell und einfach zu beantworten. [Mehr Infos...](https://docs.adobe.com/content/help/de-DE/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| Bereich Analytics for Target in Arbeitsbereich | 25. Juni 2020 | Mit dem Bedienfeld &quot;Analytics for Target&quot;(A4T) können Sie Ihre Adobe Target-Aktivitäten und -Erlebnisse mit Steigerung und Konfidenz im Analysis Workspace analysieren. [Mehr Infos...](https://docs.adobe.com/content/help/de-DE/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |
| [!UICONTROL Info zur Workspace] -Seite | Juni 18,2020 | Auf der Seite &quot; [!UICONTROL Info zu Workspace] &quot;finden Sie Informationen zu Ihrer Analysis Workspace-Umgebung, zu Ihren Adobe Analytics-Administratoren (falls Sie Support benötigen) und eine Möglichkeit, produktinterne Feedback zu geben. Sie finden sie unter **[!UICONTROL Workspace]** > **[!UICONTROL Hilfe]** > **[!UICONTROL Info zu Workspace]**. |

### Neue Funktionen in Customer Journey Analytics {#cust-journey}

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/de-DE/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| -----------| ---------- |-----|
| Unterstützung für Objektarrays | 18. Juni 2020 | CJA-Kunden können jetzt Berichte zu Dimensionen und Metriken erstellen, die in Objektarrays in ihren Adobe Experience Platform DataSet-Schemas angezeigt werden. [Mehr Infos...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-usecases/object-arrays.html) |
| Zuordnung IQ: [!UICONTROL Algorithmische Zuordnung] | 18. Juni 2020 | Das [!UICONTROL algorithmische Zuordnungsmodell] in [!UICONTROL Analysis Workspace] verwendet statistische Verfahren, um die optimale Zuordnung der Gutschrift für die ausgewählte Metrik dynamisch zu bestimmen. Verfügbar für Kunden von Adobe Analytics Ultimate. [Mehr Infos...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/attribution/algorithmic.html) |
| Zuordnung IQ: Benutzerdefinierte Lookback-Fenster | 18. Juni 2020 | Sie können jetzt jedes Zuordnungsmodell in [!UICONTROL Attribution IQ] so konfigurieren, dass Berührungspunkte von bis zu 90 Tagen vor dem Zeitraum des Berichte einbezogen werden. Dies erhöht in der Regel die Zuordnungsgenauigkeit für Ereignis, die frühzeitig im Berichte auftreten, indem Interaktionen berücksichtigt werden, die im/den Vormonat/en aufgetreten sind. [Mehr Infos...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/attribution/models.html) |
| Unterstützung der [!UICONTROL Anomalieerkennung] | 18. Juni 2020 | [!UICONTROL Die Anomalieerkennung] bietet eine statistische Methode, um zu bestimmen, wie sich eine bestimmte Metrik im Vergleich zu vorherigen Daten verändert hat. [Mehr Infos...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Projektrollen für freigegebene [!UICONTROL Workspace] -Projekte | 18. Juni 2020 | Beim Freigeben eines [!UICONTROL Workspace] -Projekts können Sie Empfänger nun je nach Projekterfahrung in eine der drei Rollen platzieren: Bearbeiten, Duplikat und Ansicht. [Mehr Infos...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| Ansicht-only- [!UICONTROL Workspace] -Projekte | 18. Juni 2020 | [!UICONTROL Workspace] -Projekte können für Benutzer freigegeben werden, da nur _[!UICONTROL Kann-Ansicht]_verwendet werden kann. Wenn ein Empfänger der Ansicht das freigegebene Projekt öffnet, erhält er eine restriktivere Projekterfahrung ohne linke Leiste und eingeschränkte Interaktionen.[Mehr Infos...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/view-only-projects.html) |
| Möglichkeit zur Kobearbeitung von [!UICONTROL Workspace] -Projekten | 18. Juni 2020 | Empfänger, die der Rolle &quot; _[!UICONTROL Kann bearbeiten]_&quot;hinzugefügt wurden, können über einem Projekt speichern, das für sie freigegeben wurde.[Mehr Infos...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| Bereich „Quick Insights“ in [!UICONTROL Arbeitsbereich] | 25. Juni 2020 | Quick Insights bietet Nicht-Analytikern und neuen Benutzern von [!UICONTROL Analysis Workspace] eine Möglichkeit, betriebliche Fragen schnell und einfach zu beantworten. [Mehr Infos...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/panels/quickinsight.html) |
| [!UICONTROL Info zur Workspace] -Seite | Juni 18,2020 | Auf der Seite &quot; [!UICONTROL Info zu Workspace] &quot;finden Sie Informationen zu Ihrer Analysis Workspace-Umgebung, zu Ihren Adobe Analytics-Administratoren (falls Sie Support benötigen) und eine Möglichkeit, produktinterne Feedback zu geben. Sie finden sie unter **[!UICONTROL Workspace]** > **[!UICONTROL Hilfe]** > **[!UICONTROL Info zu Workspace]**. |

### Neue Funktionen in [!UICONTROL Media Analytics] {#media-aa}

Datum aktualisiert: **18. Juni 2020**

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/de-DE/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| -----------| ---------- | ---------- |
| [Unterstützte Geräte und Plattformen](https://docs.adobe.com/content/help/en/media-analytics/using/supported-devices.html) | 18. Juni 2020 | Die Media Launch Extension mit dem AEP SDK unterstützt jetzt die folgenden OTT-Geräte:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |  | [Unterstützte Geräte und Plattformen](https://docs.adobe.com/content/help/en/media-analytics/using/supported-devices.html) | 18. Juni 2020 | Die Media Launch Extension mit dem AEP SDK unterstützt jetzt die folgenden OTT-Geräte:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Player-Statusverfolgung](https://docs.adobe.com/content/help/de-DE/media-analytics/using/player-state-tracking/player-state-overview.html) | 29. Mai 2020 | [!UICONTROL Media Analytics] -Kunden können die Interaktion mit dem Viewer während der Wiedergabe mit einem Standardsatz von Lösungsvariablen für Vollbild, Untertitel, Stummschaltung, Bild-in-Bild und Im-Fokus erfassen. Sie haben auch die Möglichkeit, benutzerdefinierte Player-Status zu erstellen. Player-Status-Tracking-Variablen sind jetzt für Berichte in [!UICONTROL Analysis Workspace] verfügbar. Diese Funktion erfordert eine der folgenden Voraussetzungen: <ul><li>Media [!DNL JavaScript] SDK 3.0 oder höher</li><li>Zur Verwendung mit dem [!DNL Adobe Experience Platform] (AEP)-SDK:</li><li>[!UICONTROL Media Analytics-Erweiterung] (für Web): [!UICONTROL Adobe Media Analytics] (3.x SDK) für Audio und Video v1.0 oder höher</li><li>[!UICONTROL Media Analytics-Erweiterung] (für Smartphone und Tablet): [!UICONTROL Adobe Media Analytics für Audio] und Video v2.0 oder höher</li><li>[!UICONTROL Mediensammlung]</li></ul> |

### Fehlerbehebungen in Adobe Analytics {#aa-fixes}

* Es wurde ein Fehler behoben, der dazu führte, dass Segmente mit Multibyte-Suchen nach bestimmten Report Suites nicht übereinstimmten. Sie stimmen nun mit den richtigen Zeichenfolgen überein. (AN-220043)
* Es wurde ein Problem behoben, bei dem der [!UICONTROL Elementfilter] in [!UICONTROL Reports &amp; Analytics] nicht funktionierte. (AN-206132)
* Langsame Reaktionszeit in der Benutzeroberfläche [!UICONTROL Geplante Projekte] wurde korrigiert. (AN-214837)
* Es wurde ein Problem behoben, bei dem die Analytics Berichte API 2.0 einen Datumsbereichsfehler ausgab. (AN-215087)
* Fixed a case in which the instance/visit/visitor wasn&#39;t being counted in the denominator for the [!UICONTROL Time Spent] metrics. Dies geschieht, wenn ein Treffer ohne Wert für die Dimension (z. B. &quot;Seitenname&quot;) in derselben Sekunde folgt. (AN-211074)
* Es wurde ein Problem behoben, durch das Benutzer nicht auf [!UICONTROL Workspace] -Projekte zugreifen konnten, die für sie freigegeben wurden. (AN-217561)
* Es wurde ein Problem behoben, bei dem Schlüssel nicht vom [!UICONTROL Classification Rule Builder klassifiziert wurden]. (AN-221538)
* Es wurde ein Problem behoben, bei dem die Verwendung [!UICONTROL von] Serveraufrufen keine Nutzungsdaten Berichten. (AN-210452)
* Es wurden Probleme mit veröffentlichten Adobe Analytics-Segmenten behoben, bei denen Daten in Audience Manager fehlten. (AN-220208, AN-220659)
* Es wurde ein Problem behoben, durch das Berichte mit Daten, aber [!UICONTROL Datenfeeds] -Protokollen mit der Meldung &quot;Keine Data warehouse-Daten&quot;angezeigt wurden. (AN-220784, AN-220858)
* Es wurden Probleme behoben, die den Start der [!UICONTROL Ad Hoc Analysis] aus der `experiencecloud.com` Domäne verhinderten. (AN-219680, AN-221629)
* Es wurden Probleme bei der Verwendung des Hotkeys &quot;Strg (oder Befehl) + C&quot;behoben. (AN-221101, AN-221537)
* Es wurde ein Problem mit der Seite zur [!UICONTROL Activity Map] -Aktivierung behoben. (AN-222029, AN-221242)
* Es wurde ein Problem behoben, bei dem ein Touchpoint nicht in der Mitte einer [!UICONTROL Trichteranalyse] -Visualisierung hinzugefügt werden konnte. (AN-221648)

#### Weitere Fehlerbehebungen in Adobe Analytics

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Migration zu einer einheitlichen Produkt-Domain | Datum des Inkrafttretens: 28. Mai 2020 | Die Migration zu einer einheitlichen Produkt-Domain für Adobe Analytics, die im Januar 2020 begann, wurde am 28. Mai 2020 abgeschlossen. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist `omniture.com` as a third-party cookie. Wenn die vollständige Architekturmigration (demnächst) abgeschlossen ist, werden wir Sie über die Versionshinweise benachrichtigen, und dieser zulassungsliste-Schritt des wird nicht mehr benötigt. [Hier](https://helpx.adobe.com/de/analytics/kb/adobe-ip-addresses.html) finden Sie eine vollständige Liste der empfohlenen IP-Adressen und Domänen, die Sie auf die Zulassungsliste gesetzt haben sollten.<br>Wenn Ihr Unternehmen Drittanbieter-Cookies blockiert, wenden Sie sich an die Kundenunterstützung, um wieder Zugriff auf Adobe Analytics zu erhalten. |
| Neue Standard-Landingpage von Adobe Analytics | Datum des Inkrafttretens: 18. Juni 2020 | Am 18. Juni 2020 ändert sich die standardmäßige Landingpage für Adobe Analytics von [!UICONTROL Reports] in [!UICONTROL Arbeitsbereich]. Diese Änderung wird für alle Benutzer sichtbar sein, die zuvor keine benutzerdefinierte Landingpage festgelegt haben. |
| zulassungsliste von Drittanbietertechnologie | 12. März 2020 (Datum des Inkrafttretens) | Adobe Analytics hat begonnen, Technologien von Drittanbietern für die Verwaltung des Funktions-Rollouts und die Unterstützung innerhalb von Produkten zu nutzen. Die folgenden URLs sollten zu allen erforderlichen Netzwerk-Firewall-zulassungsliste hinzugefügt werden, um den vollen Funktionenzugriff sicherzustellen:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Improved redundancy for [!UICONTROL Analysis Workspace] availability | 21. Mai 2020 | In order to ensure availability of [!UICONTROL Analysis Workspace], we are adding a secondary CDN (Content Delivery Network) for improved redundancy. Die folgenden URLs sollten zu allen erforderlichen Netzwerk-Firewall-zulassungsliste hinzugefügt werden:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Änderung der Berechnung von [!UICONTROL Einstiegen/Ausstiegen] in [!UICONTROL Arbeitsbereich] | 7. April 2020 | In [!UICONTROL Analysis Workspace] wurde im März 2020 die Weise geändert, wie der Wert _Keine_ in Bezug auf [!UICONTROL Einstiege/Ausstiege] verwendet wird. Da Sie jetzt _Keine_ in [!UICONTROL Analysis Workspace] aktivieren und deaktivieren können, wird _Keine_ jetzt erst nach einem Ein- oder Ausstieg angewendet, während dieser Wert früher (bei eVars) vor einem Ein- oder Ausstieg angewendet wurde. Angenommen, der erste Treffer eines Besuchs liefert keinen Wert für eVars, der zweite aber schon. In [!UICONTROL Reports &amp; Analytics] wird der erste Treffer als _Nicht angegeben_ für den Einstieg angezeigt, aber in [!UICONTROL Analysis Workspace] wird dieser Wert beim zweiten Treffer angezeigt. |
| Entfernung des **[!UICONTROL Dashboard-Archivs]** | 27. März 2020 | Ab Oktober 2020 ist die Einstellung **[!UICONTROL Archiv anzeigen]** unter **[!UICONTROL Dashboards verwalten]** in [!UICONTROL Reports &amp; Analytics] nicht mehr verfügbar. |
| End of Life – veraltete Analytics-APIs | 9. Januar 2020 | Im November 2020 werden die folgenden Legacy-API-Dienste von Analytics eingestellt. Aktuelle Integrationen, die mit diesen Diensten erstellt wurden, funktionieren dann nicht mehr. <ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Wir haben [FAQ zu Legacy API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) bereitgestellt, die Ihnen bei der Beantwortung Ihrer Fragen helfen und Anleitungen zum weiteren Vorgehen geben sollen. API-Integrationen, die diese Dienste nutzen, können zu den [Analytics-REST-APIs 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) oder den [Analytics-APIs 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) migrieren. Ältere OAuth-Konten können zu einem [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-Integrationskonto migrieren, das für den Zugriff auf sowohl Analytics-APIs 1.4 als auch Analytics-APIs 2.0 verwendet werden kann. |
| FTP-Broker in San Jose endet für London und Singapur | Juli 2020 | Für Kunden in London und Singapur wird die Datenvermittlung zwischen den beiden Städten und dem Rechenzentrum in San Jose ([ftp.omniture.com](ftp://ftp.omniture.com/)) nicht mehr unterstützt.<br/><ul><li>Für London verwenden Sie [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Für Singapur verwenden Sie [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ende von Ad Hoc Analysis | 6. August 2018 | Adobe kündigte die Absicht an, Ad Hoc Analysis einzustellen. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist. Weiterführende Informationen finden Sie unter [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### Neue Analytics-Kurse und -Tutorials {#tutorials-analytics}

Neue Kurse, Übungsvideos und Artikel in Analytics und Customer Journey Analytics.

| Inhalt | Content-Typ | Beschreibung |
| -----------| ---------- | ---------- |
| [Erste Schritte mit Customer Journey Analytics für Benutzer](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1) | Kurs | In diesem Kurs lernen Sie, wie Sie mit Customer Journey Analytics (CJA) Daten aus vielen verschiedenen Datenquellen analysieren können. Hier erfahren Sie mehr über die Unterschiede zwischen Adobe Analytics und Customer Journey Analytics und darüber, wie die Daten in CJA verarbeitet werden. Nach diesem Kurs sollten Sie in der Lage sein, benutzerübergreifende Visualisierungen zu erstellen und anzupassen, um ein besseres Verständnis Ihrer Kanal zu erhalten. |
| [Erste Schritte mit Customer Journey Analytics für Administratoren](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Kurs | Erfahren Sie, wie Sie [!UICONTROL Journey Orchestration]konfigurieren und verwenden. In diesem Kurs werden die wichtigsten Konzepte und Konfigurationsschritte beschrieben, die für die Orchestrierung einer Reise erforderlich sind. Sie lernen, wie Sie Orchesterreisen erstellen, veröffentlichen und wie Sie sie berichten und analysieren können. |
| [Erste Schritte mit Customer Journey Analytics für Dateningenieure](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1) | Kurs | In diesem Verlauf erfahren Sie, welche Daten in Customer Journey Analytics gelangen und wie sich dies auf die Berichte für den Analysten auswirkt. Dieser Kurs baut auf Ihren allgemeinen Kenntnissen der Adobe Experience Platform auf. |
| [Erste Schritte mit Customer Journey Analytics für Administratoren](https://video.tv.adobe.com/v/34349?captions=ger) | Videoschulung | Ein Einführungsvideo zu Customer Journey Analytics für Administratoren. |
| [Implementierungshandbuch für Analytics](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1) | Kurs | In diesem Kurs lernen Sie, wie Sie mit der Implementierung von Adobe Analytics beginnen, die Konzepte von Analytics verstehen, einen Plan erstellen und Adobe Analytics mithilfe von Experience Platform Launch implementieren. |
| [Adobe Analytics-Grundlagen für Führungskräfte](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1) | Kurs | Erfahren Sie hier mehr über die Analytics-Grundlagen und wie Analysis Workspace Ihr Geschäft verändern kann. Erfahren Sie, wie Sie mit Adobe Sensei Einblicke gewinnen, Kundenaussagen hören und Highlights von Branchenexperten auf dem Summit 2019 ansehen können. |
| [Erste Schritte mit Analysis Workspace](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace) | Kurs | Erfahren Sie, wie Sie mit Analysis Workspace beginnen. Erstellen Sie Ihr erstes Projekt, lernen Sie, wie Sie Datumsbereiche definieren, Segmente anwenden und an Projekten gemeinsam arbeiten können. |
| [Adobe Analytics Dashboards Scorecard Builder](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html) | Videoschulung | In diesem Video erfahren Sie, wie Sie [!UICONTROL Scorecards] in [!UICONTROL Analysis Workspace] erstellen und freigeben, die auf Adobe Analytics-Dashboards (mobile App) angezeigt werden. |
| [Adobe Analytics Dashboards In-App-Erlebnis](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html) | Videoschulung | In diesem Video erfahren Sie, wie Sie mit Adobe Analytics-Dashboards (mobile App) auf [!UICONTROL Barcodes] zugreifen und diese für Sie freigeben können. |

#### Analytics-Hilferessourcen

* [Adobe Analytics-Tutorials](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics-Produktdokumentation](https://docs.adobe.com/content/help/de-DE/analytics/landing/home.html)

## ![Symbol](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Neue Funktionen, Fehlerbehebungen, Dokumentationen und Tutorials in Audience Manager.

Updated **June 10, 2020**

### Aktualisierungen der Benutzeroberfläche

Audience Manager veröffentlicht Aktualisierungen für die Domäne und die Kopfleiste, um Ihr Erlebnis zu verbessern und mit anderen Experience Cloud-Anwendungen zu vereinheitlichen.

* Einfacherer Wechsel zwischen Ihren Organisationen oder zu einer anderen Anwendung.
* Verbessertes Handbuch, einschließlich spezieller Artikel und kontextbezogener Videos im Hilfemenü.
* Möglichkeit, Feedback zu Experience Platform- und Dateiunterstützungstickets zu geben.
* Ein neues einfacheres URL-Muster. Aktualisieren Sie Ihre Lesezeichen auf die neue URL: `experience.adobe.com/audience-manager`.

Diese Aktualisierungen stehen nur Benutzern zur Verfügung, die sich mit der Adobe ID anmelden. Informationen zum Wechsel zu einer Adobe ID finden Sie unter [Verwalten von Experience Cloud-Benutzern und -Produkten](https://docs.adobe.com/content/help/de-DE/core-services/interface/manage-users-and-products/admin-getting-started.html).

### Neue Funktionen und Fehlerbehebungen in Adobe Audience Manager

| Funktion | Beschreibung |
| -----------| ---------- |  
| [Audience Manager-Plug-in für IAB TCF v2.0 ](https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.html) | Um den Fokus von Adobe auf Privacy by Design zu erhalten, aktualisieren wir das Audience Manager-Plug-in für IAB TCF ab dem 10. Juni 2020 auf die IAB Transparency &amp; Consent Framework (TCF) Version 2.0. Kunden, die das Audience Manager-Plug-in für IAB TCF implementiert haben, müssen bis zum 15. August 2020 auf Version 2.0 aktualisieren, um die Funktion weiterhin nutzen zu können. Ab dem 15. August 2020 wird Version 1.1 nicht mehr unterstützt. |

**Fehlerbehebungen**

* Die Geschäftsbedingungen [!UICONTROL für das] Audience Marketplace wurden aktualisiert, um den gesetzlichen Anforderungen in bestimmten Ländern Rechnung zu tragen. (AAM-54518)
* Es wurde ein Problem behoben, bei dem der Zugriff auf die Seite &quot; [!UICONTROL Eigenschaften] &quot;über Lesezeichen zu einem 404-Fehler führte. (AAM-54768)
* Es wurde ein Problem behoben, bei dem die Ziel-Update-API beim Abrufen [!UICONTROL algorithmischer Modelle]eine Zeitüberschreitung verursachte. (AAM-54342)
* Benutzer können nun einen Modelleinstufungsgenauigkeitsindikator für [!UICONTROL Smart-Personen]anzeigen. (AAM-54847)
* Es wurde ein Problem behoben, bei dem durch Drücken der Eingabetaste nach dem Hinzufügen eines Eigenschafts-Ausdrucks der Ausdruck entfernt wurde, anstatt ihn zu speichern. (AAM-54210)
* Es wurde ein Problem behoben, bei dem Aufrufe der GET-Methode der [!UICONTROL Eigenschaften] -API für Benutzer ohne die Berechtigung &quot;ANSICHT_MODELS&quot;fehlschlugen. (AAM-53104)
* Es wurde ein Problem behoben, bei dem Benutzer [!UICONTROL Algorithmische Modelle] mit [!UICONTROL Ordnereigenschaften]nicht löschen konnten. (AAM-50192)
* Ausdruck mit langen Eigenschaften werden jetzt mehrzeilig umgebrochen. (AAM-54972)
* Es wurde ein Problem behoben, bei dem Benutzer mit schreibgeschützten Berechtigungen auf den Seiten mit algorithmischen Modellen die Schaltfläche Neu [!UICONTROL erstellen] sehen konnten. (AAM-54889)
* Es wurde ein Fehler behoben, der dazu führte, dass sich die Ladeanzeige für [!UICONTROL allgemeine] und [!UICONTROL Trend] Berichte nach Abschluss des CSV-Downloads weiter dreht. (AAM-54571)
* Es wurde ein Problem behoben, bei dem Benutzer keine Masseneigenschaften zu Segmenten im [!UICONTROL Segmentaufbau]hinzufügen konnten. (AAM-55033)
* Mehrere Verbesserungen hinsichtlich der Barrierefreiheit auf der gesamten Benutzeroberfläche. (AAM-47269, AAM-48966, AAM-48976, AAM-49369, AAM-49023, AAM-49042).

### Neue Audience Manager-Kurse und -Tutorials {#tutorials-aam}

| Inhalt | Content-Typ | Beschreibung |
| -----------| ---------- | ---------- |  
| [Einführung in den Audience Manager](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1) | Kurs | Dieser Kurs vermittelt Ihnen die Grundlagen des Audience Managers und die Probleme, die Sie damit lösen können. Erfahren Sie mehr über gängige Anwendungsfälle und wichtige Audience Manager-Begriffe und -Konzepte. |
| [Einführung in die Identität im Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html) | Videoschulung | Erfahren Sie, wie Adobe Audience Manager die Identitätsverwaltung verwaltet, einschließlich der internen Profile und der Zusammenführung von Profilen sowie der ID-Synchronisierung mit Partnern. |
| [Das benutzerbasierte Ziel von LinkedIn verstehen und konfigurieren](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html) | Kurs | In diesem Video werden die Konzepte und Schritte zum Erstellen eines benutzerbasierten Ziels für LinkedIn erläutert. Er baut auf den zusätzlichen Videos und der Dokumentation zu People-Based Destination auf. |
| [Regelbasierte Eigenschaften erstellen](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html) | Videoschulung | Erfahren Sie, wie Sie mit dem [!UICONTROL Eigenschaften-Builder] in der Benutzeroberfläche des Audience Managers eine regelbasierte Eigenschaft erstellen, mit der Sie Echtzeit-Aktivitäten in Audience Manager-Profil erfassen können. |
| [Aktivieren des Audience Manager-Plug-ins für IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf) | Videoschulung | Erfahren Sie, wie Sie das Audience Manager-Plug-in für IAB TCF aktivieren. Wenn Sie Adobe Experience Platform Launch verwenden, ist es einfach, dieses Plug-in zu aktivieren. |
| [Demo des Audience Manager-Plugins für IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo) | Videoschulung | In diesem Video sehen Sie, wie Cookies und Beacons vom Experience Cloud-ID-Dienst und von Lösungen durch die Auswahl der IAB-Benutzer beeinflusst werden. |

## ![Symbol](/assets/aem.png) Adobe Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktaktualisierungen

* **AEM 6.5.5.0**

   AEM 6.5, Service Pack 5 (Version 6.5.5.0 vom 04. Juni 2020) ist ein wichtiges Update, das neue Funktionen, wichtige kundenspezifische Verbesserungen sowie Leistung, Stabilität und Sicherheitsverbesserungen umfasst. Dieses Update wurde seit der allgemeinen Verfügbarkeit von AEM 6.5 im April 2019 veröffentlicht.

   * [Versionshinweise](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
   * [Versionsfreigaben von AEM Forms](https://helpx.adobe.com/de/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

   AEM 6.4, Service Pack 8, Cumulative Fix Pack (Version 6.4.8.1 vom 04. Juni 2020) ist ein wichtiges Update, das seit der allgemeinen Verfügbarkeit von AEM 6.4, Service Pack 8 (Version 6.4.8.0) im März 2020 mehrere interne und kundenspezifische Korrekturen enthält.

   * [Versionshinweise](https://docs.adobe.com/content/help/en/experience-manager-64/release-notes/cfp-release-notes.html)
   * [Versionsfreigaben von AEM Forms](https://helpx.adobe.com/de/aem-forms/kb/aem-forms-releases.html)

### Selbsthilfe

* **AEM as a Cloud Service**

   Neue Funktionen in AEM als Cloud Service

   Zu den Highlights gehören:

   * AEM Sites Commerce Integration Framework.
   * Erweiterte Smart-Tags und neue Funktionen in der Schulung mit Benutzeroberflächen.
   * Adobe Asset Link-Unterstützung für Adobe Xd.
   * AEM Assets Dynamic Media 3D-Unterstützung.
   * Neue Verbesserungen beim Selbstbedienungsservice reduzieren die Abhängigkeit von Adobe bei Sandbox-Vorgängen.
      * Dank der verbesserten Unterstützung für die Self-Service-Sandbox in Cloud Manager können berechtigte Benutzer alle Umgebung in einer Sandbox löschen und Gutschriften erhalten.
      * Sandbox-Umgebung mit automatischer Hibernation werden nach einer Inaktivität automatisch &quot;Hibernates&quot;-Sandboxen. Kunden können aktiv eine &quot;Entspannung&quot;auslösen.
   * Werkzeuge zur Transition zur Unterstützung der Cloud-Beschleunigung
   Mit dem Ziel, die Kosten für die Transition und die Zeit von Ort zu Cloud Service zu reduzieren, wurden in diesem Monat zwei Transitionen-Tools eingeführt. Diese Tools wurden entwickelt, um einige der wichtigsten Aufgaben während der Transition zu automatisieren und damit den Gesamtaufwand zu reduzieren. .

   1. [Mit dem Content Transfer Tool](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html) (auf SD verfügbar) wird die Aktivität der Inhaltsübertragung optimiert und skalierbar. Mit einer benutzerfreundlichen Benutzeroberfläche ist das Tool eine Selbstbedienung für Bestandskunden und -partner (on-prem/AMS), die als Cloud Service auf AEM umsteigen.
   1. [AMS Dispatcher Converter](https://github.com/adobe/aem-cloud-service-dispatcher-converter) (Open-Source) Tool zur Automatisierung der Konvertierung von AMS Dispatcher-Konfigurationen in Cloud Service Dispatcher-Konfigurationen.
   [Versionshinweise für AEM als Cloud Service 2020.6.0](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

   Werkzeuge für Transitionen:

   https://github.com/adobe/aem-cloud-service-dispatcher-converter

   https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **Kernkomponenten**

   Core Components 2.9.0 bietet eine Integration in die [Adobe Client Data Layer](https://github.com/adobe/adobe-client-data-layer) und eine neue Fortschrittsleistenkomponente. Die Komponente ist jetzt zusammen mit der [Authoring-Dokumentation](https://docs.adobe.com/content/help/de-DE/experience-manager-core-components/using/introduction.html) und den Details zum [Entwickler sowie dem Projektdownload auf GitHub](https://github.com/adobe/aem-core-wcm-components)verfügbar.

* **Wechseln zu AEM as a Cloud Service**

   [Der Wechsel zu AEM als Cloud Service](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/moving/home.html) beschreibt die empfohlene Transition für einen vorhandenen AEM-Kunden, der zu Cloud Service wechselt. Ziel dieser Dokumentation ist es, den Kunden Informationen, Anleitungen und Best Practices zur Verfügung zu stellen, um sie bei der Vorbereitung auf diese Transition zu unterstützen und eine strukturierte und berechenbare Reise zu ermöglichen.

   Eines der Cloud-Transitionen-Tools - Content Transfer Tool wurde veröffentlicht. [Das Content Transfer Tool](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html) wird von Adobe entwickelt und kann verwendet werden, um vorhandene Inhalte von einer AEM-Quellinstanz (lokal oder AMS) in die AEM Cloud Service-Instanz der Zielgruppe zu verschieben.

   Eines der Code Refactoring Tools - AEM Dispatcher Converter wurde veröffentlicht. [AEM Dispatcher Converter](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html) ist ein Tool zum Konvertieren vorhandener AEM Dispatcher-Konfigurationen in AEM als Cloud Service-Dispatcher-Konfigurationen und ist verfügbar.

* **Zugänglichkeit und WCAG 2.1-Leitlinien**

   Aktualisierungen in Bezug auf die WCAG 2.1-Leitlinien:

   * [Adobe Experience Manager as a Cloud Service und Richtlinien für barrierefreien Web-Zugang](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
   * [Kurzanleitung zu WCAG 2.1](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
   * [Erstellung barrierefrei zugänglicher Inhalte (in Übereinstimmung mit den WCAG 2.1-Richtlinien) ](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.translate.html)

* **AEM-Newsletter**

   Der AEM-Newsletter von Experience League soll Ihnen helfen, sich mit AEM vertraut zu machen, damit Sie sofort Nutzen ziehen können. Der aktuelle Newsletter:

   * [Ausgabe 31](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html): Experience Manager ist jetzt als Cloud-Dienst verfügbar.
   * [Abonnieren](https://adobeeventsonline.com/AEM/2017/NL/Optin/) Sie den Experience Insider-Newsletter.
   * Die Newsletter-Archive finden Sie im Bereich [AEM-Ressourcen](https://helpx.adobe.com/de/support/experience-manager/6-5.html) auf der Seite „Adobe Experience Manager 6.5 – Schulungsmaterialien und Support“.

### **Community**

* **AEM-Community-Diskussion**

   Jetzt können Sie sich alle AEM-Mitteilungen und interessanten Verweise auf interne und externe Blogger an einem Ort ansehen. Siehe AEM-Community- [Diskussionsabschnitt.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

### Neue Experience Manager-Kurse und -Tutorials

| Inhalt | Content-Typ | Beschreibung |
| -----------| ---------- | ---------- |
| [Erste Schritte mit Adobe Asset Link für Geschäftsbenutzer](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link) | Kurs | In diesem Kurs erfahren Sie, wie Sie die Funktionen und Funktionen von Adobe Asset Link nutzen, um Ihr kreatives Design mit in Adobe Experience Manager Assets gespeicherten Inhalten zu fördern. Der Kurs behandelt alles Mögliche, von der Einführung der Adobe Asset-Verknüpfung über grundlegende Asset-Vorgänge bis hin zu Such- und Durchsuchoptionen bis hin zur effizienten Zusammenarbeit mit anderen Benutzern. |
| [Erste Schritte mit AEM Assets für Geschäftsbenutzer](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets) | Kurs | Erfahren Sie, wie Sie mit AEM Assets für Geschäftsbenutzer beginnen können. Lernen Sie die Grundlagen von AEM Assets, Funktionen für die Zusammenarbeit, Suchen, Organisieren von Assets und Herunterladen von Assets und deren Darstellungen kennen. |
| [Erste Schritte mit AEM Sites für Geschäftsbenutzer](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites) | Kurs | Erfahren Sie, wie Sie die wichtigsten Funktionen und Funktionen der AEM Sites zur Verwaltung der Webseiten Ihres Unternehmens nutzen. Der Kurs umfasst alles, von einer Einführung in AEM Sites über grundlegende Konzepte des Authoring bis hin zu erweiterten Authoring-Funktionen und Seitenverwaltungsfunktionen. |
| [Struktur von AEM-Projekten](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | Artikel | Beschreibt die Änderungen, die für Adobe Experience Manager Maven-Projekte erforderlich sind, damit sie mit AEM Cloud Service kompatibel sind. |
| [Sling-Modelle](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models) | Videoschulung | Erfahren Sie mehr über das Debugging von AEM als lokaler Schnellstart eines Cloud Service-SDK mit der Webkonsole der Sling-Modelle. |
| [AEM Web Console-Komponenten](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components) | Videoschulung | Erfahren Sie mehr über das Debugging von AEM als lokaler Schnellstart des Cloud Service-SDK mit der Komponenten-Webkonsole. |
| [Lokalen Schnellstart des AEM SDK mit Protokollen debuggen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Videoschulung | Erfahren Sie mehr über das Debugging von AEM als lokaler Schnellstart des Cloud Service-SDK mit der Bundles-Webkonsole. |
| [Remote-Debugging von AEM als lokaler Schnellstart des Cloud Service-SDK](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html) | Videoschulung | Erfahren Sie mehr über das Java-Debugging von Ihrer IDE aus, sodass Sie die Live-Codeausführung in AEM schrittweise durchführen können, um den genauen Ausführungsfluss zu verstehen. |
| [Intelligente Tag-Einrichtung](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html) | Videoschulung | Schrittweise Anleitung zur Integration von Adobe Experience Manager (AEM) in den Smart Content Service mit Adobe I/O. |
| [Stapelgenerierung von Dokumenten](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html) | Artikel | Erfahren Sie, wie Sie mit der Stapel-API mehrere interaktive Kommunikation aus einer Vorlage erstellen. |
| [Erstellen des Print Kanal-Dokuments in AEM Forms](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html) | Artikel | Erfahren Sie, wie Sie eine interaktive Kommunikation für den Kanal &quot;Drucken&quot;erstellen können. |
| [Adobe Asset Link aufrufen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html) | Videoschulung | Erfahren Sie mehr über den Zugriff auf Adobe Experience Manager Assets (AEM Assets), ohne die Creative Cloud-Desktop-Apps zu verlassen, mit denen Sie am besten vertraut sind. |
| [Übersicht über das Asset-Verknüpfungsbedienfeld](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html) | Videoschulung | Adobe Asset Link bietet kreativen Benutzern die Möglichkeit, über das In-App-Bedienfeld in InDesign, Fotoshop und Illustrator in AEM Assets gespeicherte Assets zu durchsuchen, zu suchen, auszuchecken und einzuchecken. Lernen Sie die Benutzeroberfläche und Funktionen des Bedienfelds &quot;Asset-Link&quot;von Adobe kennen. |
| [Asset-Suche](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html) | Videoschulung | Kreative Benutzer können mithilfe von Suchbegriffen nach Assets suchen, die in AEM Assets gespeichert sind, oder eine Suche an einem bestimmten Ort durchführen. |
| [Dateiversionen und Kommentare](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html) | Videoschulung | Über das Adobe Asset Link-Bedienfeld können Sie auf Dateidetails für Assets in AEM Assets wie Miniaturansichten, Metadaten und Versionen aus dem Bedienfeld zugreifen. |
| [Checkin-Checkout](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html) | Videoschulung | Mit Adobe Asset können Sie AEM Assets direkt aus der Kreativ-App auschecken, an der Sie gerade arbeiten, und sofort mit der Bearbeitung beginnen. |
| [Nur Platzierung für AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html) | Videoschulung | Hier erfahren Sie, wie Sie eine Darstellung nur für Platzierung (For Placement Only, FPO) für AEM-Assets erstellen und verwenden. |
| [Kopieren platzieren](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html) | Videoschulung | Erfahren Sie, wie Sie mithilfe des Vorgangs &quot;Kopieren platzieren&quot;Assets aus AEM Assets verwenden. |
| [Herunterladen und Hochladen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html) | Videoschulung | Erfahren Sie, wie Sie Asset-Dateien über das Bedienfeld &quot;Asset-Link&quot;von und zu AEM Assets herunterladen und hochladen können. |
| [Dateien und Sammlungen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html) | Videoschulung | Erfahren Sie, wie Sie schnell und einfach über das Bedienfeld &quot;Asset-Link&quot;auf AEM Assets und Sammlungen zugreifen können. |
| [Download](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html) | Videoschulung | Erfahren Sie, wie Sie Assets und deren Darstellungen zur Verwendung und Freigabe auf Ihren lokalen Computer herunterladen können. |

### Zusätzliche Ressourcen

* [AEM als Cloud-Dienst](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-5.html)
* [AEM 6.4 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-4.html)
* [AEM 6.3 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-3.html)
* [AEM 6.2 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-2.html)
* [Cloud Manager-Benutzerhandbuch](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Ältere Versionen der AEM-Dokumentation](https://helpx.adobe.com/de/experience-manager/aem-previous-versions.html)
* [Startseite der Hilfe zu Dynamic Media Classic](https://docs.adobe.com/content/help/de-DE/dynamic-media-classic/using/home.html)
* [Versionshinweise zu Dynamic Media](https://docs.adobe.com/content/help/en/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Livefyre-Versionshinweise](https://docs.adobe.com/content/help/de-DE/livefyre/using/release-notes/c-rn.html)

## ![Symbol](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Neue Produktversionen

[Version](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/release-notes/latest-release.html) 20.2 von Adobe Campaign Classic umfasst:

* _Unterstützung von Emoticon_ - _Azurblase Synapse FDA Connector_ - _Neue Datenschutzbestimmungen_
* Kampagne-Systemsteuerung: [Aktive Profil-Überwachung](https://docs.adobe.com/content/help/en/control-panel/using/performance-monitoring/active-profiles-monitoring.html)

### Neue Kampagnenkurse und -übungen

| Inhalt | Content-Typ | Beschreibung |
| -----------| ---------- | ---------- |  
| [Erste Schritte mit Adobe Campaign Standard für Geschäftsbenutzer](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Kurs | Erfahren Sie, wie Sie in der Benutzeroberfläche navigieren, mit Versänden arbeiten und Empfänger-Daten erstellen und verwalten. |
| [Installieren und Einrichten des Adobe Campaign-Clients](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Video | Erfahren Sie, wie Sie die Adobe Campaign Client-Konsole herunterladen und installieren, Ihre Verbindungen zu mehreren Umgebung erstellen und verwalten und den Zugriff auf die Adobe Campaign Client-Konsole überprüfen. |

### Hilfe-Ressourcen

* Adobe Campaign Standard: [Hilfe-Center](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/campaign-standard-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-notes.html) – [Anleitungsvideos](https://docs.adobe.com/content/help/de-DE/campaign-standard-learn/tutorials/overview.html) – [Versionsplanung](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-planning.html) – [Neueste Aktualisierungen der Dokumentation](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Hilfe-Center](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/campaign-classic-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/release-notes/latest-release.html) – [Anleitungsvideos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) – [Neueste Aktualisierungen der Dokumentation](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/documentation-updates.html)
* Control Panel von Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/de-DE/control-panel/using/control-panel-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/control-panel/using/release-notes.html) - Anleitungen zu Videos für [Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Symbol](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Updated **June 3, 2020**

* [Neue Funktionen in Advertising Cloud DSP](#adcloud-dsp)
* [Neue Funktionen in Advertising Cloud Search](#adcloud-search)

### Neue Funktionen in Advertising Cloud DSP {#adcloud-dsp}

Updated **June 23, 2020**

| Funktion | Beschreibung |
| -----------| ---------- |
| Domänenmigration | (Version vom 22. Juni) Das Advertising Cloud-DSP wurde von https://www.tubemogul.com auf [https://advertising.adobe.com](https://advertising.adobe.com)migriert. |
| Adobe Analytics-Integration | (Version vom 18. Juni) DSP kann jetzt optional die AMO-Kostenmetrik aus den an Analytics gesendeten Daten unterdrücken. Wenden Sie sich zum Unterdrücken der Metrik an Ihren Adobe-Kundenbetreuer. |
| Mobilgerätediagramm | (Version vom 22. Juni) Self-Service-DSP-Kunden können jetzt ein Gerätediagramm (entweder Adobe Experience Cloud Device Co-op oder LiveRamp) für personalbasiertes Targeting und Frequenzmanagement in allen neuen Kampagnen nutzen. Dadurch wird sichergestellt, dass Sie Ihre Audiencen auf allen eigenen Geräten erreichen und die Anzeigenexposition einschränken können. |
| CCPA Opt-out-of-Sale | (Version vom 22. Juni) Sie können jetzt CCPA-Ausschluss-Kaufanfragen an Advertising Cloud mit einem neuen CCPA-Ausschluss-Verkaufssegment kommunizieren, das Sie aus [!UICONTROL Audiencen > Segmente]erstellen können. Sie können auch monatliche Berichte zu IDs abrufen, die Kunden für die Abmeldeanforderung für das Konto a) von [!UICONTROL Audiencen > Segmente] oder b) über die Advertising Cloud-Trafficking-API eingereicht haben. Weitere Informationen finden Sie unter [https://docs.adobe.com/content/help/en/advertising-cloud/all/privacy/ad-cloud-ccpa-opt-out-of-sale.html.](https://docs.adobe.com/content/help/en/advertising-cloud/all/privacy/ad-cloud-ccpa-opt-out-of-sale.html) |
| DoubleVerify Authentic Markensicherheit | (Release vom 22. Juni) Werbetreibende können nun eine DoubleVerify Segment-ID vor dem Angebot mit umfassenden Filtern zur Markensicherheit Zielgruppe haben, um ihre Blockierungsregeln nach dem Angebot mit DoubleVerify nachzuahmen. Sie können dies jetzt im Targeting-Bereich Medienqualität in den Advertiser-Einstellungen unter [!UICONTROL Einstellungen > Advertiser]tun. Weitere Informationen zum Dienst erhalten Sie unter programmaticsales@doubleverify.com. Für diese Funktion fallen zusätzliche Gebühren an. |
| CPA/ROAS-Optimierung | (Release 20. Mai) Kampagnen-Manager müssen keine neuen Platzierungen mehr in Paketen beschränken, um eine Überzuweisung des Budgets zu verhindern. Praktika erhalten nun eine dynamische Budgetzwischenzuweisung basierend auf ihrer CPM- oder CPA/ROAS-Leistung. |
| [!UICONTROL Kampagne] - Startseite | (Release 3. Juni) Es stehen neue Pacing-Metriken auf Kampagne-Ebene zur Verfügung, die auf dem bereitgestellten Budget und der bereitgestellten Kampagne basieren. |
| [!UICONTROL Platzierungen] | (Release vom 22. Juni) Die Filter &quot;Site-Vielfalt&quot;und &quot;Player-Größe&quot;wurden entfernt, um die Platzierung zu vereinfachen. |
| Platzierungsvorhersage | (Release 3. Juni) Bei CTV- und Videoplatzierungen mit Optimierung auf Platzierungsebene beinhalten die Platzierungseinstellungen jetzt Prognosen für mehrere Anzeigenlängen (15 Sek. und 30 Sek.). Sie umfassen auch Prognosen für VAST- und VPAID-Bestände. |
| CPA/ROAS-Optimierung | (Release 20. Mai) Kampagnen-Manager müssen keine neuen Platzierungen mehr in Paketen beschränken, um eine Überzuweisung des Budgets zu verhindern. Praktika erhalten nun eine dynamische Budgetzwischenzuweisung basierend auf ihrer CPM- oder CPA/ROAS-Leistung. |
| [!UICONTROL Bestand] | (Beta-Version vom 22. Juni) Ein neues Deal-ID-Formular ermöglicht es Ihnen, schnell einen privaten Deal einzurichten, den Sie bereits ausgehandelt haben. |
|  | (Beta-Version vom 22. Juni) Interaktive Pre-Roll ist jetzt für VAST-Bestände verfügbar. Sie können eine einzelne interaktive Pre-Roll-Anzeige und Platzierung einrichten, wodurch sich die Anzahl Ihrer Anzeigen und Platzierungen verringert. |
| ACTV Audience Lens | (18. Juni) Audience Lenses ermöglicht es Benutzern, sekundäre Audiencen zu erstellen und auf ihre Planung, Bestellung und Berichte Workflows. Dadurch können sie (1) schnelle Einblicke in sekundäre Audiencen gewinnen, (2) flexibel auf bevorzugte Audiencen transagieren und (3) die Ausführung einer Kampagne durch das &quot;Objektiv&quot;mehrerer Audiencen messen. |

### Neue Funktionen in [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Funktion | Beschreibung |
| -----------| ---------- |
| [!UICONTROL Kampagnen] | Microsoft Advertising (früher Bing Ads) veraltet die durchschnittlichen Positionsmetriken nach dem 30. September 2020. In Vorbereitung darauf werden ab dem 11. Juli Positionsbeschränkungen ignoriert und Positionsbedingungen in jeder Art von Einschränkung ignoriert. |
| [!UICONTROL Werbeeinblicke] | (Version vom 13. Juni) Die folgenden Erkenntnisse wurden entfernt:<br/><br/><ul><li>Audience Target Performance (die neuere Version)</li><li>Historische Leistung (die neuere Version)</li><li>Übereinstimmungstyp (die neuere Version)</li><li>Einstellungsprüfung (die neuere Version)</li><li>Portfolio-Pre-Post (veraltet)</li></ul><br/>Die verbleibenden Erkenntnisse sind ältere Versionen, und die _Legacy_ -Bezeichnung wurde aus den Namen entfernt. Außerdem wurden die Modi &quot;Live/Bearbeiten&quot;entfernt. |

## ![Symbol](/assets/magento.png) [!DNL Magento] {#magento}

Magento-Versionshinweise finden Sie unter:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Symbol](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] ist eine Komplettanwendung für das Lead-Management. B2B-Marketer können damit Kundenerlebnisse transformieren, indem sie in allen Phasen komplexer Customer Journeys Interaktionen ermöglichen.

### Aktualisierungen von Core Marketo Engage

Die aktuellen Versionsinformationen finden Sie in den [!DNL Marketo] [Versionshinweisen](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720).

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
