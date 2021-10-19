---
title: Neueste Versionshinweise
description: Erfahren Sie mehr über die neuesten Versionshinweise, neue Funktionen und neue Dokumentation für [!DNL Experience Cloud] Produkte und Dienstleistungen. Neue Hilfe und Tutorials zu finden [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud].
doc-type: release notes
last-update: October 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: ccdd4f3514cc11f9e0f373de29d0b21464bee923
workflow-type: tm+mt
source-wordcount: '5702'
ht-degree: 38%

---

# Adobe Experience Cloud – Versionshinweise, Oktober 2021

![Banner](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud]-Anwendungen und -Dienste werden monatlich aktualisiert. Auf dieser Seite finden Sie die neuesten Versions-Updates, Dokumentationen und Tutorials zu [!DNL Experience Cloud] und [!DNL Experience Platform]. Sie finden hier außerdem eine neue Dokumentation für [!DNL Creative Cloud for enterprise] und [!DNL Document Cloud].

>[!NOTE]
>
>Abonnieren Sie das monatliche [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html), um E-Mail-Benachrichtigungen über Aktualisierungen dieser Seite zu erhalten. Diese Seite wird den ganzen Monat über gepflegt. Informieren Sie sich daher regelmäßig über die neuesten Updates zu Adobe Unternehmensprodukten und der Experience League-Dokumentation.

Letzte Aktualisierung: **13. Oktober 2021**

* [[!DNL Experience League]-Live-Ereignisse](#events)
* [[!DNL Experience Cloud Central Interface Components] und Administration](#ecloud)
* [[!UICONTROL Adobe-Systemstatus]](#status)
* [[!DNL Adobe Analytics]](#analytics) und [Customer Journey Analytics](#cust-journey) **Aktualisiert am 7. Oktober 2021**
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Experience Manager]](#aem) (aktualisiert **13. Oktober 2021**)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Advertising Cloud]](#adcloud) (aktualisiert **7. Oktober 2021**)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

Benötigen Sie Hilfe? Besuchen Sie [Adobe Experience League](https://experienceleague.adobe.com/?lang=de#home), um Produkt- und technische Dokumentation, von Adobe kuratierte Kurse, Video-Tutorials, schnelle Antworten, Community-Einblicke und von Schulungsleitern geführte Kurse zu erhalten.

## ![Icon](/assets/experience-league.png) [!DNL Experience League] Live-Ereignisse {#events}

[!DNL Experience League]-Live-Ereignisse sind Diskussionen mit Adobe-Experten und wichtigen Gästen, die maßgeblich dazu beitragen, Ihnen die Adobe-Technik zu bringen. Sehen Sie sich folgenden Zeitplan an und nehmen Sie an der Live-Schaltung teil oder rufen Sie die zuvor aufgezeichneten Ereignisse ab.

| Ereignisdatum | Zeit | Ereignisname | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |---------- |
| 4. Oktober 2021 | Bei Bedarf | [Adobe Developers Live](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | Video | Adobe-Produktteams in Adobe Experience Cloud, Document Cloud und Creative Cloud präsentierten die neuesten technologischen Fortschritte und Entwicklungstools, mit denen Design, Content-Erstellung, Workflows, Dokument-Services und Customer Experience Management branchenübergreifend unterstützt werden. Ansicht der Keynote-Adresse, Erfahren Sie mehr über Analytics-APIs, Client-Datenschicht, Adobe I/O Open-Source-Projekte und vieles mehr. |
| 21. Oktober 2021 | 23.00 Uhr (EST) | [Wer hat das angeklickt? Erweiterter Berichte bei Link-Klicks mit Adobe Analytics](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) | Live Video-Ereignis | Berichte bei der Benutzerinteraktion mit Ihrem Web oder Ihrer mobilen Eigenschaft ist ein wichtiger Aspekt des Verständnisses der Journey. Mit Adobe Analytics können Sie wissen, wer, was, warum und wo von jedem Klick in Ihre Anwendung. Erfahren Sie von Adobe Analytics-Experten, wie Sie mithilfe von Activity Map-Classifications und benutzerspezifischen Zuweisungen die Benutzerinteraktion besser verstehen. |
| 23. September 2021 | Bei Bedarf | [Expertentipps für eine erfolgreiche Kampagne zum Jahresende](https://www.youtube.com/watch?v=bsU1lAv0xes) | Live-Videoereignis | So wie es nie zu früh ist, um mit einem Urlaubseinkauf zu beginnen, ist es nie zu früh, um mit der Planung einer sehr erfolgreichen Marketing-Kampagne für die Feiertage zum Jahresende zu beginnen. Mit Adobe Campaign können Sie Kampagnen entwerfen, planen und ausführen, die alle Urlaubswünsche Ihres Unternehmens erfüllen.<br>Aber kennen Sie alle Tipps, um Kampagnen zu starten, die das Jahr mit einem Knall beenden? Treten Sie Sandra bei und diskutieren Sie live mit drei Experten aus der Adobe, die über genug kollektives Know-how verfügen. |
| 26. August 2021 | Bei Bedarf | [Machen Sie Ihr nächstes Zielgruppensegment intelligenter als je zuvor](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=de) | Ereignisaufzeichnung | Der Erfolg jeder guten Marketing-Kampagne hängt von einer präzisen Bestimmung Ihrer Zielgruppe ab. Mit dem neuen [!UICONTROL Segment Builder] von Adobe Experience Platform können Sie Ihr nächstes Zielgruppensegment anhand von Profildaten und zeitbasiertem Benutzerverhalten kanalübergreifend erstellen. Es gibt keine bessere Möglichkeit, um mit Ihren Nachrichten die Menschen zu erreichen, die sie am dringendsten hören müssen. |
| 29. Juli 2021 | Bei Bedarf | [Meine drei beliebtesten Implementierungstipps für Adobe Analytics](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=de) | Ereignisaufzeichnung | Sie haben ihn beim Summit auf der Bühne gesehen. Sie haben ihn bei Adobe Insider Tours erlebt, wo er Expertentipps vortrug. Möglicherweise haben Sie sogar mit ihm zusammen an Ihrer eigenen Adobe Analytics-Implementierung gearbeitet. Nun bringt Eric Matisoff seine drei beliebtesten Implementierungstipps für Adobe Analytics in diese exklusive Experience League Live-Diskussion ein. |

{style=&quot;table-layout:auto&quot;}

Weitere Videos finden Sie im [Adobe Experience League-Kanal](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) auf YouTube.

## ![Symbol](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] und Administration {#ecloud}

| Funktion | Beschreibung |
| ------- | ------- |
| Einheitliche Suche | Unified Search fügt dem Suchindex weiterhin Objekttypen hinzu. In diesem Update durchsucht die globale Suche nun den Inhalt der Experience League und die folgenden Journey Optimizer-Objektarten: <ul><li>Datensätze</li><li>Ziele</li><li>Abfragen</li><li>Schemas</li><li>Segmente</li><li>Quellen</li><li>Angebote</li><li>Komponenten</li><li>Nachrichten</li><li>Journeys</li></ul> |
| Zustimmung zu Produktverwendungsdaten | Bei einer erstmaligen Anmeldung werden Sie aufgefordert, Voreinstellungen einzureichen, damit Ihnen Adobe hilfreiche, personalisierte Inhalte wie Tutorials, Leitfäden, QuickInfos, Empfehlungen, Lernvideos und vieles mehr auf Basis Ihrer Experience Cloud-Produktgebrauchsdaten bereitstellen kann. Diese Anforderung enthält auch eine Aktualisierung Ihrer Voreinstellungen für die Erfassung und Verwendung dieser Daten unter <https://experience.adobe.com/preferences>. |
| Experience Cloud [!UICONTROL Trigger] Navigation | [Experience Cloud Trigger](https://experienceleague.adobe.com/docs/core-services/interface/services/activation/triggers.html?lang=en) ist für die direkte Navigation vom Anwendungsschalter im Header für bereitgestellte Benutzer verfügbar. |
| **Hinweis:** Geplante Aktualisierung der Benutzeroberfläche | Im November 2021 _[!UICONTROL Zu Launch/Datenerfassung wechseln]_ Navigationsfunktion wird entfernt von <https://experience.adobe.com/implement>. |

{style=&quot;table-layout:auto&quot;}

**Weitere Hilferessourcen zu [!DNL Experience Cloud Central UI Components] und Administration**

* Hilfe für Administratoren zum Thema [zentrale UI-Komponenten](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=de) und Benutzerverwaltung
* Hilfe und Versionshinweise für [Places-/Location-Service](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=de)
* Hilfe zu [Personen - Kundenattribute und Zielgruppenbibliothek](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![Symbol](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe-Produkten und -Diensten. Weitere Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/de).

(Die neuesten Versionsinformationen zu [!DNL Adobe System Status] finden Sie in den Versionshinweisen vom [21. Mai 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=de).)

## ![Symbol](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Release-Datum: **7. Oktober 2021**

* [Neue Funktionen in Adobe Analytics](#aa-features)
* [Neue Funktionen in Customer Journey Analytics](#cust-journey)   **Aktualisiert am 7. Oktober 2021**
* [Fehlerbehebungen in Adobe Analytics](#aa-fixes)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [Analytics-Kurse und -Tutorials](#tutorials-analytics)
* [AppMeasurement](#appm)

### Neue Funktionen in Adobe Analytics {#aa-features}

| Funktion | Beschreibung | [Allgemeine Verfügbarkeit](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=de) – geplantes Datum |
| ----------- | ---------- | ------- |
| Visualisierungen für Analytics-Dashboard | Analytics [!UICONTROL Dashboards] stellt drei neue Visualisierungen vor, um Führungskräften und Entscheidungsträgern ein besseres Verständnis ihrer Daten auf einen Blick zu vermitteln. Die neue [!UICONTROL Doughanisch], [!UICONTROL Linie]und [!UICONTROL Horizontal] Balkendiagramme erleichtern die Anzeige von Daten für einzelne Dimensionselemente, ohne dass eine Ansicht mit Details geöffnet werden muss. [Weitere Informationen](https://experienceleague.adobe.com/docs/analytics/analyze/mobapp/create-scorecard.html?lang=en#apply-visualizations) | 7. Oktober 2021 |
| [!UICONTROL Bei Medienwiedergabe verbrachte Zeit] | Adobe Streaming Media Play-back [!UICONTROL Besuchszeit] bietet wertvolle Einblicke in die Betrachter-Interaktion und ermöglicht es Medienunternehmen, tiefere, detailliertere Einblicke durch eine Minute-für-Minute-Interaktion durch erweiterte Analyse mit Tagesaufteilung zu gewinnen. Sie können die Zeit, die Sie mit der Anzeige Ihrer Medienströme verbracht haben, zu einem bestimmten Zeitpunkt beobachten. Sie können die Wiedergabedauer nach verschiedenen Granularitäten aufteilen, einschließlich neuer Granularitäten von 5 Minuten, 15 Minuten und 30 Minuten. [Weitere Informationen](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 18. Oktober 2021 |
| Schnell [!UICONTROL Segmentaufbau] | Ermöglicht es Geschäftsbenutzern, einfache Segmente schnell in einem vereinfachten, integrierten Projektablauf anzuwenden. Es ist nicht erforderlich, zum [!UICONTROL Segmentaufbau]. [Weitere Informationen](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 21. Oktober 2021 |
| Verbesserungen bei der Suche nach links in Analysis Workspace | Bei der Suche im linken Bereich werden exakte Übereinstimmungen über breitgefächerten Übereinstimmungen nach 1) gepriorisiert, zusätzlich zur weiteren Berücksichtigung der Neuigkeit und Relevanz der Komponenten. 2) Es werden übereinstimmende Zeichen hervorgehoben, um die Suchergebnisse verständlicher zu machen. 3) Es ist einfacher, Classifications für eine Dimension zu finden. 4) Schließlich unterstützt es Platzhalter (`*`) zu suchen, um spezifische Komponenten, die Sie benötigen, leichter zu finden. Hinweis: Die Platzhaltersuche funktioniert noch nicht auf der Ebene der Dimensionselemente. | 21. Oktober 2021 |
| Analysis Workspace Dark Theme | Dunkles Thema ist als Anzeigeoption verfügbar. | 21. Oktober 2021 |

{style=&quot;table-layout:auto&quot;}

### Neue Funktionen in Customer Journey Analytics {#cust-journey}

| Funktion | Beschreibung | [Allgemeine Verfügbarkeit](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) – geplantes Datum |
| ----------- | ---------- | ----- |
| Rollierendes Fenster für [!UICONTROL Verbindung] Datenspeicherung | **Hinweis: Wenden Sie sich an die Kundenunterstützung oder Ihren Kundenbetreuer für die Adobe, um diese Einstellung implementieren zu lassen. Es ist noch nicht über die CJA-Benutzeroberfläche verfügbar.**<p>Ermöglicht die Definition einer CJA-Einstellung zur Vorratsdatenspeicherung als rollierendes Fenster in Monaten (3 Monate, 6 Monate usw.) in einem [!UICONTROL Verbindung] Ebene (nicht auf [!UICONTROL Datenbestand] Ebene). Die Datenspeicherung basiert auf Zeitstempeln für Ereignis-Datasets und gilt nur für Ereignis-Datensätze. Für Profil- oder Nachschlagedatasets gibt es keine Datenspeicherungseinstellung, da keine gültigen Zeitstempel vorhanden sind. Der Hauptvorteil besteht darin, dass Sie Daten, die anwendbar und nützlich sind, nur speichern oder Bericht erstatten und ältere Daten löschen, die nicht mehr nützlich sind. Es hilft Ihnen, die vertraglichen Beschränkungen einzuhalten und das Risiko von Übernachtungskosten zu verringern. | 7. Oktober 2021 |
| Report Builder-Support | Report Builder ist ein Microsoft® [!DNL Excel] hinzufügen, mit dem Sie benutzerspezifische Berichte mithilfe von Customer Journey Analytics-Daten leicht erstellen, bearbeiten und aktualisieren können. Mit Report Builder und Excel können Sie die einfache, aber flexible Drag-and-Drop-Oberfläche verwenden, um komplexe Datenanforderungen einfach zu erstellen. Mit Report Builder für Customer Journey Analytics können Sie:<ul><li>Bestehende Arbeitsblattzellen referenzieren, um die perfekte Zeilenreihenfolge, den perfekten Datumsbereich oder den perfekten Filter zu erhalten.</li><li>Benutzerdefinierte Datumswerte mit Kalender, Zellverweisen oder Datums-Mathematik erstellen</li><li>Entwerfen Sie Tabellen und Visualisierungen mit vertrauten Excel-Formatierungswerkzeugen.</li><li>Verfügbar für Excel unter macOS, Microsoft 365 für das Web und Microsoft Windows</li></ul>[Weitere Informationen](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-reportbuilder/report-buider-overview.html#) | 7. Oktober 2021 |
| Visualisierungen für Analytics-Dashboard | Analytics [!UICONTROL Dashboards] stellt drei neue Visualisierungen vor, um Führungskräften und Entscheidungsträgern ein noch besseres Verständnis ihrer Daten auf einen Blick zu vermitteln. Die neuen Doppel-, Linien- und horizontalen Balkendiagramme erleichtern die Anzeige von Daten für einzelne Dimensionselemente, ohne dass eine Ansicht geöffnet werden muss. [Weitere Informationen](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/create-scorecard.html?lang=en#apply-visualizations) | 7. Oktober 2021 |
| API für Customer Journey Analytics-Prüfprotokolle | Die [Auditprotokoll](https://adobe.io/cja-apis/docs/endpoints/auditlogs/) API-Endpunkt ermöglicht es Ihnen, Auditprotokolldaten von der Adobe anzufordern. Es ist ein wichtiger Bestandteil der Einhaltung der Sicherheitsvorschriften und der Prüfung von Daten oder Benutzeraktionen. | 7. Oktober 2021 |
| Schnell [!UICONTROL Filteraufbau] | Ermöglicht es Geschäftsbenutzern, einfache Segmente schnell in einem vereinfachten, integrierten Projektablauf anzuwenden. Es ist nicht erforderlich, zum [!UICONTROL Filteraufbau]. [Weitere Informationen](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=en) | 21. Oktober 2021 |
| Verbesserungen bei der Suche nach links in Analysis Workspace | Bei der Suche im linken Bereich werden exakte Übereinstimmungen über breitgefächerten Übereinstimmungen nach 1) gepriorisiert, zusätzlich zur weiteren Berücksichtigung der Neuigkeit und Relevanz der Komponenten. 2) Es werden übereinstimmende Zeichen hervorgehoben, um die Suchergebnisse verständlicher zu machen. 3) Es ist einfacher, Classifications für eine Dimension zu finden. 4) Schließlich unterstützt es Platzhalter (`*`) zu suchen, um spezifische Komponenten, die Sie benötigen, leichter zu finden. Hinweis: Die Platzhaltersuche funktioniert noch nicht auf der Ebene der Dimensionselemente. | 21. Oktober 2021 |
| Analysis Workspace Dark Theme | Dunkles Thema ist als Anzeigeoption verfügbar. | 21. Oktober 2021 |

{style=&quot;table-layout:auto&quot;}

### Fehlerbehebungen in Adobe Analytics und CJA {#aa-fixes}

* Ein terminierter Berichtsfehler im Customer Journey Analytics wurde behoben. (AN-271721)
* Gelöste Probleme mit [!UICONTROL Komponenten durchsuchen] in [!UICONTROL Arbeitsbereich] keine genauen Übereinstimmungen ergeben. (AN-253937; AN-271707)

#### Weitere Fehlerbehebungen in Adobe Analytics

AN-256136; AN-265420; AN-268455 AN-269768; AN-270276; AN-270287; AN-271601; AN-271969; AN-272056; AN-272111; AN-272457

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| ----------- | ---------- | ---------- |
| Ende der Nutzungsdauer von drei Analytics-API-Services | 16. September 2021 | Ein **20. Oktober 2021**, erreichen die folgenden Analytics Legacy-API-Dienste das Enddatum und werden heruntergefahren. Alle aktuellen Integrationen, die mit diesen Services erstellt wurden, funktionieren seit diesem Tag nicht mehr.<ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Adobe hat ein Dokument [Häufig gestellte Fragen (FAQ) zum Ende der Nutzungsdauer (EOL) der Legacy-API](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) bereitgestellt, das Ihre Fragen beantworten und Anleitungen zum weiteren Vorgehen geben soll. API-Integrationen, die diese Dienste nutzen, können zu den [Analytics-REST-APIs 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) oder den [Analytics-APIs 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) migrieren. Ältere OAuth-Konten können zu einem [Adobe I/O](https://developer.adobe.com/console) Analytics-Integrationskonto migriert werden, das für den Zugriff auf sowohl Analytics-APIs 1.4 als auch Analytics-APIs 2.0 verwendet werden kann. |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Die neuesten Aktualisierungen zu AppMeasurement-Versionen finden Sie in den Versionshinweisen (Version 2.22.2) zu [AppMeasurement für JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=de).

### Analytics-Kurse und -Tutorials {#tutorials-analytics}

Neueste Kurse, Tutorials und Artikel in [!DNL Analytics] und [!UICONTROL Customer Journey Analytics].

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Oktober 2021 | [Verwenden von Visualisierungen zum Teilen von Datenmeldungen](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | Kurs | Wer will nach Tabelle scour, nur um zu versuchen, Einblicke aus den Daten zu ziehen? Nicht du! In diesem Kurs lernen Sie die Grundlagen über Visualisierungen, wie Sie sie zu einem Projekt hinzufügen, Daten darin sammeln und was jede Visualisierung Ihnen zeigen kann. Erfahren Sie, wie Sie die Einstellungen konfigurieren, um die gewünschten Daten zu erhalten. Außerdem gibt es einige Tipps und Anwendungsbeispiele, die Ihnen helfen, Visualisierungen für Ihre reguläre Analyse praktisch zu gestalten. |

{style=&quot;table-layout:auto&quot;}

### Analytics-Hilferessourcen

* [Adobe Analytics-Produktdokumentation und Tutorials](https://experienceleague.adobe.com/docs/analytics.html?lang=de)

## ![Symbol](/assets/audience-manager.png) Audience Manager {#aam}

Neue Funktionen in Audience Manager, aktualisiert am **14. September 2021**:

| Funktion | Beschreibung |
| ------- | ------- |
| Einverständnis zur Datenerfassung bei mobilen IDs | Das Einverständnis zur Datenerfassung bei mobilen IDs wird jetzt unterstützt. Um von dieser Aktualisierung profitieren zu können, müssen Kunden ihre Produktversion auf [AEP Mobile SDK iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) oder höher aktualisieren. |

## ![Symbol](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Enthält Versionsupdates und neue Dokumentationen für Experience Platform und [!UICONTROL Mobile SDK].

**29. September 2021**

| Funktion | Beschreibung |
| ------- | ------- |
| [[!UICONTROL Daten-Einstiegszone]](https://experienceleague.adobe.com/docs/experience-platform/sources/connectors/cloud-storage/data-landing-zone.html) | [!UICONTROL Daten-Einstiegszone] ist ein [!DNL Platform]-bereitgestellt [!UICONTROL Azure Blob Store] die es einer sicheren und temporären Datenspeicherung pro Sandbox ermöglicht, Dateien in Experience Platform zu bringen. |
| Unterstützung von Streaming-Quellen für [Datenaufbereitung](https://www.adobe.com/go/monitor-streaming-dataflows-en) | Streaming-Quellen unterstützen nun die Datenvorbereitung und ermöglichen es Ihnen, ein JSON-Quell-Schema bereitzustellen, mit dem nicht-XDM-kompatible Quelldaten einem XDM-Schema der Zielgruppe zugeordnet werden können. |
| [Nicht ablaufende Anmeldedaten](https://experienceleague.adobe.com/docs/experience-platform/query/ui/credentials.html) | Nicht abgelaufene Anmeldedaten für [!UICONTROL Abfrage] Benutzer erlauben eine permanentere Verbindung zu externen Clients, anstatt die Anmeldedaten alle 24 Stunden zu erneuern. |
| [[!UICONTROL Ziel-SDK]](https://www.adobe.com/go/destination-sdk-overview-en) | Verwenden [!UICONTROL Ziel-SDK] Integration in [!DNL Platform] und tragen Sie zum ständig wachsenden Reisezielkatalog bei. Der Zugriff auf diese Funktion ist nur für Kunden von Experience Platform Aktivierung verfügbar. |

Weitere Informationen finden Sie in den [Versionshinweisen zu Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=de).

### Experience Platform-Tutorials und -Kurse {#tutorials-platform}

Neueste Videos, Tutorials oder Kurse, die für Experience Platform und Dienstleistungen veröffentlicht wurden.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Oktober 2021 | [[!DNL Platform] Administration](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | Kurs | Erfahren Sie mehr über administrative Aktivitäten für die Experience Platform, einschließlich Berechtigung und Sandbox-Verwaltung. |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

Siehe [Versionshinweise und Änderungsprotokolle](https://aep-sdks.gitbook.io/docs/release-notes) für die Mobile SDKs von Adobe Experience Platform.

## ![Symbol](/assets/experience_platform_appicon_24.png) Journey Optimizer {#journey-opt}

Erfahren Sie mehr über die neuesten Funktionen, Verbesserungen und Fehlerbehebungen in den [Versionshinweisen zu Journey Orchestration](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=de).

### Journey Optimizer-Tutorials und -Kurse {#tutorials-ajo}

Neueste Journey Optimizer-Tutorials:

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Oktober 2021 | [Daten konfigurieren und verwalten in [!DNL Journey Optimizer] für Dateningenieure](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | Kurs | Erfahren Sie, wie Sie die für die Journey-Verwaltung in Journey Optimizer erforderlichen Daten konfigurieren und verwalten. |
| Oktober 2021 | [Erste Schritte mit [!DNL Journey Optimizer] für Journey-Administratoren und -Manager](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | Kurs | Erfahren Sie alles, was Sie wissen müssen, um Ihre erste Journey zu erstellen. |
| Oktober 2021 | [Konfigurieren [!DNL Journey Optimizer] für Journey-Administratoren](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | Kurs | die [!DNL Journey Optimizer] Architektur und Integrationspunkte. Informationen zur Konfiguration [!DNL Journey Optimizer]. |

{style=&quot;table-layout:auto&quot;}

### Weitere Ressourcen für [!DNL Journey Optimizer]

[Hilfe-Center](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) – [Anleitungsvideos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=de)

## ![Symbol](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Verwenden Sie Experience Platform, um die Customer Journey in großem Umfang über alle Erlebniskanäle hinweg zu orchestrieren, indem Sie die Bedürfnisse jedes Einzelnen in Echtzeit intelligent antizipieren.

### Letzte [!DNL Journey Orchestration] Produktversionen

Erfahren Sie mehr über die neuesten Funktionen, Verbesserungen und Fehlerbehebungen in den [[!DNL Journey Orchestration] Versionshinweisen zu ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=de).

#### Weitere Ressourcen für [!DNL Journey Orchestration]

[Hilfe-Center](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) – [Anleitungsvideos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=de) – [Neueste Aktualisierungen der Dokumentation](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=de)

## ![Symbol für](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL offer decisioning] ist ein in Adobe Experience Platform integrierter Dienst. Verwenden Sie [!UICONTROL Offer Decisioning], um Ihren Kunden über alle Berührungspunkte hinweg zur richtigen Zeit das beste Angebot und Erlebnis zu bieten.

### Neueste Offer decisioning-Produktversionen

Erfahren Sie mehr über die neuesten Funktionen, Verbesserungen und Korrekturen im [offer decisioning Versionshinweise](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html).

#### Weitere Ressourcen zu [!UICONTROL Offer Decisioning]

[Hilfe-Center](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) – [Anleitungsvideos](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=de) – [Neueste Aktualisierungen der Dokumentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![Symbol](/assets/aem.png) Experience Manager {#aem}

Adobe empfiehlt, die Seite [Experience Manager-Versions-Updates und -Roadmaps](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=de) zu besuchen, um auf dem Laufenden zu bleiben.

**Aktualisierung 13.10.2021:** Prüfen Sie die [Versionshinweise September 2021 - Überblick](https://video.tv.adobe.com/v/337381) Video mit einem Überblick über die neuen Funktionen.

### Community

* [Adobe Developers Live](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk) | 4./5. Oktober 2021, 7:00 PDT

   Adobe Developers Live vereint Entwickler und Erlebnisbauer von Adoben mit unterschiedlichem Hintergrund und einem besonderen Zweck - um unfassbare End-to-End-Erlebnisse zu schaffen. Diese zweitägige Konferenz bietet wichtige Entwickler-Updates, technische Sitzungen und Community-Netzwerkmöglichkeiten.

   Produktteams in der Adobe in Adobe Experience Cloud, Document Cloud und Creative Cloud präsentieren die neuesten technologischen Fortschritte und Entwicklungstools, mit denen Design, Content-Erstellung, Workflows, Dokument-Services und Customer Experience Management branchenübergreifend unterstützt werden.

   In der Adobe sind 20 Experience Manager geplant. Verrate das Wort!

   * [Liste der Sitzung beenden](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [Kostenlose Registrierung - Bei RSVP anmelden](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Adobe Developers Live Community](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-october-4-5/td-p/422127)

### Neue Experience Manager-Kurse und -Tutorials {#tutorials-aem}

Nachfolgend sind die im vergangenen Monat neu veröffentlichten Videos, Tutorials und Kurse aufgeführt.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Oktober 2021 | [Erste Schritte mit der XML-Dokumentation](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.xmldocs) | Kurs | Erfahren Sie, wie Sie mit der XML-Dokumentation für Adobe Experience Manager Inhalte erstellen, organisieren, erstellen und veröffentlichen. |
| Oktober 2021 | [Kreative Workflows verwalten mit [!DNL Workfront] und Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.2.assets.essentials) | Kurs | Adobe [!DNL Workfront] und Experience Manager. |
| Oktober 2021 | [Erste Schritte mit AEM Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.assets.essentials) | Kurs | Erfahren Sie, wie AEM Assets Essentials das Asset-Management für Ihr Unternehmen optimieren kann. |
| Oktober 2021 | [[!UICONTROL Content Transfer Tool]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/content-transfer-tool.html?lang=en) | Video | Erfahren Sie mehr darüber [!UICONTROL Inhaltsübertragungswerkzeug] hilft Ihnen, Inhalte von AEM 6.3+ auf AEM as a Cloud Service zu migrieren. |
| Oktober 2021 | [[!UICONTROL Massenimport-Dienst]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/bulk-import-service.html?lang=en) | Video | Erfahren Sie, wie AEM Cloud Services [!UICONTROL Massenimport-Dienst] kann verwendet werden, um Assets aus nicht AEM Quellen zu importieren. |
| Oktober 2021 | [Kommunikation (Output Service)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/communications.html?lang=en) | Video | Erfahren Sie, wie AEM Forms as a Cloud Service den Kommunikationsverwendungsfall unterstützt. |
| Oktober 2021 | [Digitale Registrierung](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/digital-enrollment.html?lang=en) | Video | Erfahren Sie mehr darüber, wie AEM Forms as a Cloud Service den Verwendungsfall für die Digitale Registrierung unterstützt. |
| Oktober 2021 | [Verwenden [!UICONTROL Cloud-Beschleunigungs-Manager] Werkzeuge](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/using.html) | Video | Ein erklärter Durchgang von [!UICONTROL Cloud-Beschleunigungs-Manager] Tools. |
| Oktober 2021 | [Navigation [!UICONTROL Cloud-Beschleunigungs-Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/navigating.html) | Video | Navigationserlebnis entdecken von [!UICONTROL Cloud-Beschleunigungs-Manager] für Experience Manager as a Cloud Service. |
| Oktober 2021 | [Asset-Workflow-Migrations-Tool](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/asset-workflow-migration-tool.html) | Video | Erfahren Sie mehr über [!UICONTROL Asset-Workflow-Migration] migrieren Sie Ihre bestehende AEM Assets-Workflows as a Cloud Service. |
| Oktober 2021 | [[!UICONTROL Index Converter]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/index-converter.html) | Video | Erfahren Sie mehr über [!UICONTROL Indexkonverter] wandelt vorhandene AEM Indexdefinitionen automatisch in AEM as a Cloud Service kompatible um. |
| Oktober 2021 | [[!UICONTROL Dispatcher Converter]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/dispatcher-converter.html) | Video | Erfahren Sie mehr über [!UICONTROL Dispatcher Converter] aktualisiert automatisch bestehende AEM Dispatcher-Konfigurationen, um as a Cloud Service kompatibel zu sein. |
| Oktober 2021 | [[!UICONTROL Code-Repository-Moderator]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-repository-modernizer.html) | Video | Erfahren Sie mehr über [!UICONTROL Zentrale Repository-Modernizer] aktualisiert automatisch bestehende AEM Maven-Projekte auf AEM as a Cloud Service kompatible. |
| Oktober 2021 | [[!UICONTROL Code-Refaktorierungs-Tools]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-refactoring-tools.html) | Video | Erfahren Sie mehr über die AEM [!UICONTROL Code-Umgestaltungswerkzeuge] Automatisieren Sie die Konvertierung bestehender AEM Projekte, damit diese as a Cloud Service kompatibel sind. |
| Oktober 2021 | [[!UICONTROL Inhaltsübertragungswerkzeug]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/content-transfer-tool.html) | Video | Erfahren Sie mehr über [!UICONTROL Inhaltsübertragungswerkzeug] ermöglicht das effiziente Verschieben von Inhalten von AEM 6.5 auf AEM as a Cloud Service. |
| Oktober 2021 | [Die Implementierungsphasen von [!UICONTROL Cloud-Beschleunigungs-Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/implementation-phase.html) | Video | die wichtigsten Implementierungsphasen zu überprüfen und zu verstehen oder as a Cloud Service zu AEM, indem [!UICONTROL Cloud-Beschleunigungs-Manager]. |
| Oktober 2021 | [Bereitschaft und [!UICONTROL Best Practice Analyzer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/readiness-and-best-practice-analyzer.html) | Video | Erfahren Sie mehr über [!UICONTROL Best Practice Analyzer] können Sie dabei unterstützen, den Wechsel von AEM Onprem oder Adobe Managed Services zu Experience Manager as a Cloud Service vorzubereiten. |
| Oktober 2021 | [Einführung in Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/introduction.html) | Video | Erfahren Sie mehr darüber [!UICONTROL Cloud-Beschleunigungs-Manager] kann Ihnen dabei helfen, schnell und einfach zu Experience Manager as a Cloud Service zu bewegen. |
| Oktober 2021 | [AEM Forms as a Cloud Service - Umstieg auf AEM CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/introduction.html?lang=en) | Video | Erfahren Sie mehr über Anwendungsfälle und Funktionen, die von AEM Forms as a Cloud Service unterstützt werden. |
| Oktober 2021 | [Fehlerbehebung AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/troubleshooting.html?lang=en) | Video | Erfahren Sie, wie Sie das AEM SDK, AEM as a Cloud Service und, den Build- und Bereitstellungsvorgang beheben und debuggen. |
| Oktober 2021 | [AEM [!UICONTROL Assets-Mikrodienste] - as a Cloud Service AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/asset-compute-microservices.html?lang=en) | Video | Erfahren Sie, wie Sie mit den asset compute-Mikrodiensten von AEM Assets as a Cloud Service automatisch und effizient jede Ausgabe für Ihre Assets generieren können. Dadurch wird diese Funktion des herkömmlichen AEM-Workflows ersetzt. |
| Oktober 2021 | [Suchen und indizieren](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/search-and-indexing.html?lang=en) | Video | Erfahren Sie mehr über die AEM as a Cloud Service-Suchindizes, wie Sie AEM 6-Indexdefinitionen so konvertieren, dass sie as a Cloud Service kompatibel sind, und wie Sie Indizes für AEM as a Cloud Service bereitstellen. |
| Oktober 2021 | [[!UICONTROL  Dispatcher  ]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/dispatcher.html?lang=en) | Video | Weitere Informationen zu AEM [!UICONTROL Dispatcher] für AEM as a Cloud Service, mit Schwerpunkt auf wichtigen Änderungen von [!UICONTROL Dispatcher] für AEM 6 [!UICONTROL Dispatcher] Konvertierungs-Tool und wie Sie das Dispatcher Tools SDK verwenden. |
| Oktober 2021 | [[!UICONTROL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/cloud-manager.html?lang=en) | Video | Erfahren Sie mehr über Cloud Manager für AEM as a Cloud Service und seine Unterschiede zu Cloud Manager für AEM in Adobe-Verwaltungsdiensten (AMS). |
| Oktober 2021 | [Umsteigen auf AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/onboarding.html?lang=en) | Video | Informieren Sie sich über das Einsteigen in AEM as a Cloud Service von der Vertragsphase bis zur Einrichtung der Umgebung unter Verwendung von [!UICONTROL Cloud Manager]. |
| Oktober 2021 | [Repository-Modernisierung](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/repository-modernization.html?lang=en) | Video | Erfahren Sie mehr über die Modernisierung von Repositorys, anpassbare und unveränderbare Inhalte, Paketstruktur und das Repository-Modernisierer-CLI-Tool. |
| Oktober 2021 | [[!UICONTROL AEM-Modernisierungs-Tools]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-modernization-tools.html?lang=en) | Video | AEM [!UICONTROL Modernisierungstools] werden verwendet, um ein vorhandenes AEM zu aktualisieren und um AEM as a Cloud Service kompatibel zu sein. |
| Oktober 2021 | [AEM-Modernisierungs-Tools](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/introduction.html?lang=en) | Video | Erfahren Sie, wie Sie anders über AEM as a Cloud Service-Implementierungen denken. |
| Oktober 2021 | [Best Practice Analyzer und Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/bpa-and-cam.html?lang=en) | Video | Erfahren Sie, wie Best Practice Analyzer (BPA) und Cloud Acceleration Manager (CAM) ein benutzerdefiniertes Handbuch für die Migration auf AEM as a Cloud Service bereitstellen. |
| Oktober 2021 | [Versionsverlauf wird beibehalten](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/versions.html) | Video | Erfahren Sie, wie Adobe Workfront und Experience Manager [!UICONTROL Assets Essentials] hilft Ihnen, Versionen von [!DNL Workfront] Dokumente und Assets Essentials-Vermögenswerte. |
| Oktober 2021 | [Senden von Dokumenten und Verknüpfen von Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/link-send.html?lang=en) | Video | Erfahren Sie, wie Sie Workfront-Dokumente an Assets Essentials senden und Assets Essentials-Assets an Workfront verknüpfen. |
| Oktober 2021 | [Integration konfigurieren](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html?lang=en) | Video | Erfahren Sie, wie Sie die Integration von Adobe Workfront und Assets Essentials konfigurieren. |
| Oktober 2021 | [Was ist eine digitale Signatur?](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | Video | Erfahren Sie mehr über zertifikatbasierte digitale Signaturen, die den weltweit strengsten gesetzlichen Vorschriften entsprechen und die höchste Sicherheit für die Identität eines Unterzeichners bieten. |
| Oktober 2021 | [Segment Builder in Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-builder-overview.html?lang=en#) | Video | Stellen Sie Ihre Daten mit der Segmentierung in Adobe Analytics individuell zusammen. Dieses Video führt Sie durch die [!UICONTROL Segmentaufbau] und gibt einen Überblick. |
| Oktober 2021 | [Metadaten zuordnen](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=en) | Video | Erfahren Sie, wie Sie die Metadatenzuordnung zwischen Workfront-Feldern und Assets Essentials-Eigenschaften konfigurieren und Assets Essentials so konfigurieren, dass die zugeordneten Werte angezeigt werden. |

{style=&quot;table-layout:auto&quot;}

### Versionsinformationen zu Experience Manager {#aem-links}

Versionshinweise und andere Links zu Versionsinformationen für Experience Manager finden Sie hier:

* [[!DNL Experience Manager as a Cloud Service]  Versionshinweise](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=de)
* [[!DNL Experience Manager as a Cloud Service] Versionsinformationen](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=de)
* [[!DNL Experience Manager Cloud Manager]  Versionshinweise](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=de)
* [Versionshinweise zum Service für die automatische Formularkonversion](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=de)
* [Versionshinweise für Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=de)
* [Versionshinweise für Experience Manager 6.4 Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=de)
* [[!DNL Experience Manager Assets Dynamic Media]  Versionshinweise](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=de)
* [[!DNL Experience Manager Brand Portal]  Versionshinweise](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=de)
* [Versionshinweise zum Experience Manager-Desktop-Programm ](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=de)
* [[!DNL Experience Manager Dispatcher]  Versionshinweise](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=de)
* [Versionshinweise zu Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=de)
* [Versionshinweise zu Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=de)

### Weitere Hilferessourcen für Experience Manager

* [[!DNL Experience Manager as a Cloud Service] Handbücher](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=de)
* [Experience Manager 6.5 – Training und Support, Startseite](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=de)
* [Experience Manager 6.4 – Training und Support, Startseite](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=de)
* [Experience Manager 6.3 – Training und Support, Startseite](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=de)
* [Experience Manager 6.2 – Training und Support, Startseite](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=de#previous-updates)
* [Ältere Versionen der Dokumentation zu Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [[!DNL Cloud Manager]  Benutzerhandbuch](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=de)
* [[!DNL Dynamic Media Classic] Hilfe-Startseite](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=de)
* [Experience Manager-Dokumentation: Neueste Aktualisierungen](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=de#aem-as-a-cloud-service)

## ![Symbol](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Aktuelle Campaign-Produktversionen

Erfahren Sie mehr über die aktuellsten veröffentlichten Funktionen, Verbesserungen und Fehlerbehebungen:

* [Versionshinweise zu Campaign Version 8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=de)
* [Versionshinweise zu Campaign Classic 7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=de)
* [Versionshinweise zu Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=de)

### Neue [!UICONTROL Campaign]-Kurse und -Tutorials {#tutorials-campaign}

Neueste Tutorials und Kurse zum Adobe Campaign.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Oktober 2021 | [Erstellen erweiterter Kampagnen mit Adobe Campaign V8 für Geschäftsbenutzer](https://experienceleague.adobe.com/?recommended=Campaign-U-1.2021.1.v8) | Kurs | Erfahren Sie, wie Sie erweiterte Marketing-Kampagnen mit Adobe Campaign V8 konfigurieren und ausführen. Erfahren Sie mehr über die Voraussetzungen, erstellen und konfigurieren Sie erweiterte Kampagnen, Versand und verwalten Sie Abonnement. |
| Oktober 2021 | [Verwenden von SOAP-APIs in Workflows - Einführung](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=de) | Tutorial | Erfahren Sie, wie Sie Adobe Campaign Soap-APIs verwenden und einen erweiterten Versand-Workflow auf Basis der über die API erhaltenen Daten erstellen. |
| Oktober 2021 | [Ereignisse erstellen](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/create-events.html?lang=en) | Übung | Erfahren Sie, wie Sie ein Ereignis konfigurieren, den Streaming-Endpunkt und die Nutzlast für ein Ereignis angeben. |
| Oktober 2021 | [Konfigurieren von Datenquellen](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/configure-data-sources.html?lang=en) | Übung | Erfahren Sie, was eine Datenquelle ist, und lernen Sie, wie Sie Experience Platform- und externe Datenquellen konfigurieren. |
| Oktober 2021 | [Verwendungsfall - Burst-Meldungen](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/use-case-burst-message.html?lang=en) | Übung | Machen Sie sich mit den Anwendungsfällen für Bust-Messaging vertraut. Erfahren Sie, wie Sie eine Journey für Burst-Nachrichten konfigurieren und welche Best Practices zur Anwendung kommen. |

{style=&quot;table-layout:auto&quot;}

### Hilferessourcen für Campaign

* Adobe Campaign Version 8: [Hilfe-Center](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=de) – [Implementierungshandbücher](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=de)
* Adobe Campaign Standard: [Campaign Standard – Dokumentation](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) – [Anleitungsvideos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=de) – [Versionsplanung](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=de) – [Neueste Aktualisierungen der Dokumentation](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=de)
* Adobe Campaign Classic: [Campaign Classic v7 – Dokumentation](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) – [Anleitungsvideos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=de) – [Neueste Aktualisierungen der Dokumentation](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=de)
* Control Panel von Adobe Campaign: [Dokumentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=de) – Anleitungsvideos für [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=de)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=de)

## ![Symbol](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Versionshinweise für [!DNL Adobe Advertising Cloud].

* [Neue Funktionen in Version  [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Neue Funktionen in Version  [!DNL Advertising Cloud Search]](#adcloud-search)

### Neue Funktionen in Version [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Zuletzt aktualisiert: **7. Oktober 2021**

| Funktion | Beschreibung |
| ------- | ----------- |
| Dokumentation | Alle [DSP und andere Advertising Cloud-Dokumentation](https://experienceleague.adobe.com/docs/advertising-cloud.html) on [!DNL Experience League] ist nun maschinell in alle verfügbaren Sprachen übersetzt. Um die angezeigte Sprache zu ändern, verwenden Sie das Menü &quot;Sprache ändern&quot; links unten auf jeder Seite. |

{style=&quot;table-layout:auto&quot;}

### Neue Funktionen in Version [!DNL Advertising Cloud Search] {#adcloud-search}

Zuletzt aktualisiert: **7. Oktober 2021**

| Funktion | Beschreibung |
| ------- | ----------- |
| [!UICONTROL Berichte], [!UICONTROL Benachrichtigungszentrum] | (Version 9. Oktober) Alle E-Mail-Benachrichtigungen für Berichte, die Advertising Cloud Search sendet, wenn ein benutzerspezifischer oder terminierter Bericht abgeschlossen wurde oder fehlgeschlagen ist, werden nun verarbeitet von [!UICONTROL Benachrichtigungszentrum]. E-Mail-Benachrichtigungen und Webbenachrichtigungen sind standardmäßig für Berichte aktiviert, Sie können jedoch optional die Benachrichtigungseinstellungen ändern. Mit dieser Änderung:<ul><li>E-Mail-Empfänger sind auf Benutzer beschränkt, die registrierte, authentifizierte Benutzer von Advertising Cloud Search sind und Zugriff auf das Advertiserkonto haben. Dadurch wird sichergestellt, dass keine vertraulichen Daten an nicht autorisierte Benutzer gesendet werden.</li><li>Format und Inhalt der E-Mail verwenden die [!UICONTROL Benachrichtigungszentrum] Vorlage, die weitere Details zum Bericht enthält und direkte Download-Links für alle Berichtsformate enthält.</li><li>Berichtsbenachrichtigungen sind ein neuer Benachrichtigungstyp mit eigenen Benachrichtigungseinstellungen in [!UICONTROL Benachrichtigungszentrum].</li></ul>Wenn Sie Berichte mithilfe von Automatisierung aus E-Mail-Benachrichtigungen abrufen, müssen Sie die Filterlogik möglicherweise aktualisieren, um die Prozesskontinuität sicherzustellen. |
| Werbeeinblicke | Weitere Informationen sind im Beta-Modus verfügbar. |

{style=&quot;table-layout:auto&quot;}

## ![Symbol](/assets/magento.png) [!DNL Commerce] (Magento) {#magento}

Versionshinweise zu Adobe Commerce finden Sie unter den folgenden Links:

* [Adobe Commerce und Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite für Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![Symbol](/assets/target.png) [!DNL Target] {#target}

Letzte Aktualisierung: **3. August 2021**

Die aktuellen Versionsinformationen finden Sie in den [[!DNL Target] Versionshinweisen](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=de).

## ![Symbol](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] ist eine Komplettanwendung für das Lead-Management. B2B-Marketer können damit Kundenerlebnisse transformieren, indem sie in allen Phasen komplexer Customer Journeys Interaktionen ermöglichen.

### Aktualisierungen von Core Marketo Engage

Aktuelle Informationen zum Veröffentlichungszeitplan sowie Versionshinweise finden Sie in der [!DNL Marketo Engage] [Versionsplanung](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=de).

## ![Symbol](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] ist eine umfassende Software für das Ideenmanagement, die Content-Erstellung und die Verwaltung komplexer Prozesse, die optimales Arbeiten im Team ermöglicht.

Auf der Seite zu [[!DNL Workfront] Versionen](https://one.workfront.com/s/product-releases) finden Sie eine Zusammenfassung der aktuellsten Informationen zu allen Produkten.

## ![Symbol](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Neue Videos, Tutorials oder Kurse, die für Adobe Document Cloud veröffentlicht wurden.

### Document Cloud-Kurse und -Tutorials {#tutorials-doc-cloud}

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Oktober 2021 | [Was ist eine digitale Signatur?](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | Video | Erfahren Sie, wie Sie mit Adobe Sign digitale IDs aus aller Welt verwenden. |
| Oktober 2021 | [Erste Schritte mit Adobe Sign für neue Absender](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/new-sender.html) | Video | Wenn Sie neu bei Adobe Sign sind, ist dieses Tutorial ein großartiger Ort zum Beginn. Dieses umfassende Tutorial konzentriert sich auf alle Grundlagen, damit Sie schnell mit Adobe Sign arbeiten können. |
| Oktober 2021 | [PDF-Kommentare in InDesign laden](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/indesign.html) | Video | In diesem 60-Sekunden-Video-Tutorial erfahren Sie, wie Sie PDF-Kommentare nach einer gemeinsamen Überprüfung durch Acrobat wieder in InDesign laden. Dieser digitale Workflow hilft Ihnen, Revisionen in Rekordzeit abzuschließen. |
| Oktober 2021 | [Digitale ID abrufen von [!DNL Intesi Group] (Qualifiziert)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-qualified.html) | Video | Erfahren Sie, wie Sie ein qualifiziertes digitales Signaturzertifikat abrufen von [!DNL Intesi] Gruppe. Nach der Registrierung und Überprüfung Ihrer Identität, [!DNL Intesi] Gruppiert Probleme mit einer digitalen ID, die zum Anwenden einer Adobe Sign Cloud-Signatur verwendet wird. |
| Oktober 2021 | [Signieren mit [!DNL Intesi Group]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-sign.html) | Video | Erfahren Sie, wie Sie Ihre Intesi Group-digitale ID verwenden, um Ihre Identität zu authentifizieren und eine digitale Fernsignatur (Cloud-Signatur) für ein Dokument zu autorisieren. |
| Oktober 2021 | [Digitale ID abrufen von [!DNL Intesi Group] (Erweitert)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-advanced.html) | Video | Erfahren Sie, wie Sie ein erweitertes digitales Signaturzertifikat von Intesi Group erhalten. Nach der Registrierung und der Bestätigung Ihrer Identität gibt die Intesi Group Ihnen eine digitale ID aus, mit der Sie eine Adobe Sign Cloud-Signatur anwenden können. |
| Oktober 2021 | [Signieren mit [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-sign.html) | Video | Erfahren Sie, wie Sie Ihre [!DNL Digidentity] Digitale ID zur Identitätsauthentifizierung und Autorisierung einer digitalen Fernsignatur (Cloud-Signatur) auf einem Dokument. |
| Oktober 2021 | [Digitale ID abrufen von [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-reg.html) | Video | Erfahren Sie, wie Sie ein digitales Signaturzertifikat abrufen von [!DNL Digidentity]. Nach der Registrierung und Überprüfung Ihrer Identität, [!DNL Digidentity] gibt Ihnen eine digitale ID aus, die zur Anwendung einer Adobe Sign Cloud-Signatur verwendet wird. |
| Oktober 2021 | [Unterschiede zwischen zwei PDF erkennen](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/compare.html) | Video | Machen Sie nie den Fehler, mit der falschen Version einer Datei zu arbeiten. Erkennen Sie schnell und präzise die Unterschiede zwischen zwei PDF-Dateien, um die Workflows zu verbessern. |
| Oktober 2021 | [Erstellen von PDF-Inhalten beim Browsen mit Microsoft® Edge](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/edge.html) | Video | Erfahren Sie, wie Sie mit der Adobe Acrobat-Erweiterung für Microsoft® Edge Web-Seiten mit sofortiger PDF archivieren. Dieses nur Windows-Tool ist unschätzbar für Forschungsprojekte und die Offline-Anzeige von webbasierten Informationen. |
| Oktober 2021 | [E-Mail-Nachrichten und Anhänge in PDF in Outlook konvertieren](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/outlook.html) | Video | Erfahren Sie, wie Sie E-Mail-Nachrichten und Anhänge für Ihre Projekte in Outlook auf PDF archivieren. Lernen Sie, Informationen professioneller und sicherer zu liefern, indem Sie Anlagen automatisch in PDF konvertieren. Dieses Tool ist nur für Windows verfügbar. |

{style=&quot;table-layout:auto&quot;}

Hilfe zu Document Cloud erhalten Sie über:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=de)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=de)
* [Document Cloud: Lernen und Support](https://helpx.adobe.com/de/support/document-cloud.html)

## ![Symbol](/assets/creative-cloud-24.png) Creative Cloud für Unternehmen {#creative-cloud}

Siehe [Creative Cloud für Enterprise-Tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=de) für die neuesten Tutorials.
