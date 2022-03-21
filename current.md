---
title: Neueste Versionshinweise
description: Hier finden Sie Informationen über die aktuellen Versionshinweise, neue Funktionen und neue Dokumentation für  [!DNL Experience Cloud] -Produkte und -Services. Neue Hilfen und Tutorials zu [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise] und [!DNL Document Cloud].
doc-type: release notes
last-update: March 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: eb5f320b029eb30f548c2016ac51e52c14de8199
workflow-type: tm+mt
source-wordcount: '5696'
ht-degree: 49%

---

# Adobe Experience Cloud – Versionshinweise, März 2022

![Banner](assets/experience-cloud-banner-3.png)

Als Erlebnisgestalter beginnt Ihr Weg zum Erfolg mit [Adobe Experience League](https://experienceleague.adobe.com/?lang=de#home). Hier finden Sie eine umfangreiche Bibliothek mit Anleitungsdokumenten, Tutorials zum Selbststudium, Anleitungsvideos und Kursen für alle Ebenen und Rollen, eine Online-Community mit Gleichgesinnten und Unterstützung von Experten, wenn Sie sie benötigen.

Bereit zum Einstieg? [Machen Sie ein 5-minütiges Quiz und gewinnen Sie](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp)!

>[!NOTE]
>
>Um monatliche E-Mail-Benachrichtigungen über Aktualisierungen auf dieser Seite zu erhalten, abonnieren Sie das [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html). Schauen Sie regelmäßig wieder vorbei, um über die Entwicklung bei Experience League auf dem Laufenden zu bleiben.

Letzte Aktualisierung: **21. März 2022**

* [[!DNL Experience League]Ereignisse](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - zentrale Schnittstellenkomponenten und Administration](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Blueprints für digitale Erlebnisse – Tutorials](#blueprints)

Benötigen Sie Hilfe? Besuchen Sie [Adobe Experience League](https://experienceleague.adobe.com/?lang=de#home), um Produkt- und technische Dokumentation, von Adobe kuratierte Kurse, Video-Tutorials, schnelle Antworten, Community-Einblicke und von Schulungsleitern geführte Kurse zu erhalten.

## ![Symbol](/assets/experience-league.png) [!DNL Experience League] events {#events}

Experience League-Events sind ein idealer Ort, um bei der Adobe zu lernen, zu interagieren und Antworten von Produktexperten zu erhalten!

| Event | Typ | Beschreibung |
| -----------|---------- | ----|
| [Experience League LIVE ](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=de) | Live- und On-Demand-Video | Eine Live-Streaming-Show des Experience League-Teams. Dort haben Sie Gelegenheit, sich mit Produktexperten von Adobe auszutauschen und praktische Tipps, Tricks und Strategien für die Arbeit mit den Programmen rund um Adobe Experience Cloud kennenzulernen.<br> [Details und vergangene Ereignisse](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) |
| [AEM Gems](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/aem-gems-build-sites-faster-with-aem-headless-and-app-builder/m-p/440205#M31629) | Adobe Live-Webinar | Schnelles Bootstrap und Bereitstellen von Einzelseiten-Apps (SPA) mithilfe von Adobe [!UICONTROL App Builder] Workflows und Tools ohne herkömmliche Experience Manager-Fähigkeiten wie Java™ und Sling erforderlich sind. Mit Experience Manager Headless können Marketing-Experten und Entwickler jeweils über das Know-how in ihrer eigenen Domäne verfügen - Entwickler steuern das gesamte Anwendungsframework, die Formatierung und das Routing, während Marketingexperten den Inhalt und die Darstellung bestimmen.<br>**Datum:** Mittwoch, 23. März - [Details und Registrierung](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/aem-gems-build-sites-faster-with-aem-headless-and-app-builder/m-p/440205#M31629) |
| [Adobe Analytics: Aussagekräftige Geschichten mit Daten erzählen](https://engage.adobe.com/adobe-analytics-telling-impactful-stories.html?s_rtid=7015Y0%5b%E2%80%A6%5d15Y000003A5SbQAK&amp;sfid=&amp;acctid=&amp;ecp=&amp;sdid=JCNCWJFP&amp;mv=display) | Adobe Live-Webinar | Das Erzählen von Daten ist gut, wenn es um ein Gleichgewicht von Kunst und Wissenschaft geht. Warum also übertechnisch? Adobe Analytics-Meister Amy Ard diskutiert drei Teile, die darauf abzielen, Ihr Datengeschichten zu erzählen, ohne die Kreativität zu beeinträchtigen:<ul><li>Ermitteln der Gelegenheit oder des Problems</li><li>Durch Daten erklären</li><li>Lösung anbieten</li></ul>**Datum:** Donnerstag, 31. März - [Details und Registrierung](https://engage.adobe.com/adobe-analytics-telling-impactful-stories.html?s_rtid=7015Y0%5b...%5d15Y000003A5SbQAK&amp;sfid=&amp;acctid=&amp;ecp=&amp;sdid=JCNCWJFP&amp;mv=display) |
| [Experience Maker - Der Qualifikationsaustausch für Adobe Workfront](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) | Adobe Live-Webinar | Wir freuen uns, die erste Ausgabe von Experience Makers ankündigen zu können - Der Skill Exchange für Adobe Workfront findet am 13. April statt. Diese kostenlose, dreistündige digitale Lernveranstaltung konzentriert sich ausschließlich auf Workfront und bietet Kunden die Möglichkeit, Fragen live von Experten und Kollegen zu stellen, die das Arbeitsmanagement am besten kennen. Egal ob Sie neuere Workfront sind oder ein erfahrener Experte sind, wir haben für jeden etwas dabei. <br>**Datum:** Mittwoch, 13. April - [Details und Registrierung](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=de) | Video | [!DNL Developers Live] präsentiert die neuesten technischen Fortschritte und Entwickler-Tools, die das Design, Workflows zur Inhaltserstellung, Dokumenten-Services und das Customer Experience Management in verschiedenen Branchen ermöglichen. Sehen Sie sich die Keynote an, erfahren Sie mehr über Analytics-APIs, Client Data Layer, Adobe I/O-Open-Source-Projekte und vieles mehr. |

{style=&quot;table-layout:auto&quot;}

## ![Symbol](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe-Produkten und -Diensten. Weitere Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/de).

Die neuesten Versionsinformationen finden Sie unter Systemstatus der Adobe [Versionshinweise](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=en#status).

## ![Symbol](/assets/ec_appicon_24.png) Experience Cloud - zentrale Schnittstellenkomponenten und Administration {#ecloud}

Experience Cloud [Komponenten der zentralen Benutzeroberfläche](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=de) enthält Funktionen, die auf der Startseite und der beständigen Produktheader verfügbar sind. Zu diesen Funktionen gehören Benutzerprofileinstellungen, Voreinstellungen und Suchen. Hilfe finden Sie auch in den Bereichen Benutzer- und Produktverwaltung, Kundenattribute und Experience Cloud-Zielgruppen.

| Funktion | Beschreibung |
| ------- |-------|
| Zugriff _[!UICONTROL Letzte]_ in Experience Platform und Journey Optimizer mit [!UICONTROL Einheitliche Suche] | Sie können auf zuletzt aufgerufene Objekte von jeder Seite der Experience Platform und von Journey Optimizer aus über die [!UICONTROL Einheitliche Suche] -Feld.<br>Siehe [Einheitliche Suche für Objekte und Entitäten](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en) für weitere Informationen. |

{style=&quot;table-layout:auto&quot;}

**Weitere Hilferessourcen zu [!DNL Experience Cloud Central UI Components] und Administration**

* [Versionshinweise](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=en) für zentrale Komponenten der Benutzeroberfläche von Experience Cloud
* [Benutzer- und Produktverwaltung](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) für Experience Cloud (Administration)
* Places Service – [Versionshinweise](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=de)
* Produktdokumentation für [People – Kundenattribute und Zielgruppenbibliothek](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)
* [Einheitliche Suche nach Objekten und Entitäten](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en)

## ![Symbol](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Aktuelle Versionsinformationen und neue Dokumentation für Experience Platform und [!UICONTROL Mobile SDK]:

Veröffentlichungsdatum: **7. März 2022**

* [Versionshinweise zu Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=de)

### Neue Experience Platform-Tutorials und -Kurse {#tutorials-platform}

Neue Videos, Tutorials oder Kurse, die für Experience Platform veröffentlicht wurden.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| März 2022 | [Tutorial zur Implementierung von Adobe Experience Cloud in Apps](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/overview.html) | Kurs | Erfahren Sie, wie Sie mit dem Adobe Experience Platform Mobile SDK Adobe Experience Cloud-Anwendungen in Ihre Mobile App implementieren. |
| März 2022 | [Erstanbieter-Geräte-IDs generieren](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/generate-first-party-device-ids.html) | Video | Erfahren Sie mehr über das Generieren von Erstanbieter-Geräte-IDs und deren Funktionsweise. |
| März 2022 | [Konfigurieren von Datenspeichern](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/configure-datastreams.html) | Video | Erfahren Sie, wie Sie Datenspeicher für Web- und Mobile SDK-Implementierungen erstellen und konfigurieren. |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

Siehe [Versionshinweise und Änderungsprotokolle](https://aep-sdks.gitbook.io/docs/release-notes) für die Mobile SDKs von Adobe Experience Platform.

## ![Symbol](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Veröffentlichungsdatum: **23. März 2022**

* [Versionshinweise](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=de) zu Adobe Analytics (**neuer Speicherort**)
* [Produktdokumentation und Tutorials](https://experienceleague.adobe.com/docs/analytics.html?lang=de) zu Adobe Analytics

### AppMeasurement {#appm}

Release-Version: **2.22.4**

* [Versionshinweise für AppMeasurement für JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=de)

### Neue Analytics-Tutorials und -Kurse {#tutorials-analytics}

Neue Videos, Tutorials oder Kurse, die für Adobe Analytics veröffentlicht wurden.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| März 2022 | [Tipps und Tricks zur Vereinfachung und Verringerung der Schulungszeit von Benutzern](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/simplify-training-users.html?lang=en) | Video und Artikel | Erfahren Sie, wie wichtig für den Erfolg einer gut ausgebildeten Adobe Analytics-Organisation in Ihrem Unternehmen sein kann. |
| März 2022 | [Aufbau einer gestärkten Community](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/empowered-community.html) | Video und Artikel | Erfahren Sie mehr über den Wert einer leistungsstarken Analytics-Community und wie Sie eine Community erstellen und unterstützen. |
| März 2022 | [Einrichten von Marketingkanal-Verarbeitungsregeln](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/create-marketing-channel-processing-rules.html?lang=en) | Video | Erfahren Sie, wie Sie [!UICONTROL Verarbeitungsregeln] für [!UICONTROL Marketingkanäle]. |
| März 2022 | [Einrichten von Marketingkanälen in Ihrer Report Suite](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/set-up-marketing-channels.html) | Video | In diesem Video erfahren Sie, wie Sie die Berichterstellung für Marketing-Kanäle in Ihrer Analytics Report Suite konfigurieren. |
| März 2022 | [Übergang von Google Analytics zu Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/transitioning-from-other-platforms/transition-from-google-analytics.html?lang=en) | Video | Ein umfassender Leitfaden für die Umstellung auf [!DNL Adobe Analytics] von [!DNL Google Analytics]. |
| März 2022 | [Konfigurieren von Hierarchievariablen](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-hierarchy-variables.html?lang=en) | Video | Erfahren Sie, wie und wann Sie Hierarchievariablen für Ihre Site einrichten und konfigurieren. Diese Funktion kann verwendet werden, um eine hierarchische Ansicht der Seiten auf Ihrer Site anzuzeigen und zu sehen, wie viel Traffic an die einzelnen Knoten geleitet wird. |
| März 2022 | [Kuratieren und Freigeben in Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/curation-and-sharing-in-analysis-workspace.html?lang=en) | Video | Erfahren Sie, wie Sie mit Kuratierungs- und Freigabeprojekten in Analysis Workspace arbeiten. |
| März 2022 | [Direkter Link zu einem Projekt in Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/direct-link-to-a-project.html?lang=en) | Video | Erfahren Sie, wie Sie die Analyse besser demokratisieren können, indem Sie gekürzte Links erstellen, über die Ihre Kollegen direkt zu Ihren Analysis Workspace-Projekten gelangen. |

{style=&quot;table-layout:auto&quot;}

## ![Symbol](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Veröffentlichungsdatum: **23. März 2022**

* [Versionshinweise](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=de) zu Customer Journey Analytics (**neuer Speicherort**)
* [Produktdokumentation und Tutorials](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=de) zu Customer Journey Analytics

## ![Symbol](/assets/audience-manager.png) Audience Manager {#aam}

Fehlerbehebungen und Verbesserungen bei Audience Manager:

| Verbesserung | Beschreibung |
| -----------| ---------- |  
| Validator für Zieldatenquellen anderer Unternehmen | Audience Manager hat eine Verbesserung der [Batch-Datenintegrationsprozess](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=en). Um das versehentliche Einsteigen von Dateien und Daten in Zieldatenquellen anderer Partner zu verhindern, hat der Audience Manager eine Zuordnungsanforderung zwischen Partner-ID (PID) und Datenquellen (DPID) anderer Partner hinzugefügt. <ul><li>Siehe auch __DPID_TARGET_DATA_OWNER_ -Feld in [Anforderungen an Namen und Dateigrößen der über Amazon S3 eingehenden Datendateien](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=en#name-elements).</li><li>Adobe-interne Berater und Kundenunterstützung sollten lesen [Onboarding-Zugriff für Daten von Zweitanbietern verwalten](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=en) für Informationen zum neuen Mapping, die verbessert werden müssen, und wie Sie ein neues Mapping anfordern können</li><li>Es ist _not_ erforderlich, um eine Zuordnung für bestehende Datenfreigabe-Beziehungen anzufordern. Die Zuordnung ist auch _not_ erforderlich, wenn Daten in Zieldatenquellen integriert werden, die zu Ihrer PID gehören.</li></ul> |

{style=&quot;table-layout:auto&quot;}

Ressourcen zur Selbsthilfe finden Sie unter [Dokumentation und Tutorials zu Audience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=de) in Experience League.

## ![Symbol](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe empfiehlt, die Seite [Experience Manager-Versions-Updates und -Roadmaps](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=de) zu besuchen, um auf dem Laufenden zu bleiben.

### Produktaktualisierungen für Experience Manager

* **Experience Manager 6.5, Service Pack 12 (6.5.12.0)**

   Adobe Experience Manager 6.5.12.0 enthält neue Funktionen, wichtige von Kunden angeforderte Verbesserungen sowie Leistungs-, Stabilitäts- und Sicherheitsverbesserungen, die seit der Veröffentlichung der Version 6.5 im April 2019 veröffentlicht wurden. Das Service Pack wird auf Adobe Experience Manager 6.5 installiert.

   Siehe [Versionshinweise](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=de).

### Produktversionen von Experience Manager

* **Experience Manager as a Cloud Service**

   * [Video Versionsübersicht Januar 2022](https://video.tv.adobe.com/v/340120) von neuen Funktionen.
   * [Video mit der Übersicht über die Version Dezember 2021](https://video.tv.adobe.com/v/339278) im Hinblick auf neue Funktionen.
   * [Video mit einer Übersicht über die Version Oktober 2021](https://video.tv.adobe.com/v/338253) im Hinblick auf neue Funktionen.
   * [Video mit einer Übersicht über die Version September 2021](https://video.tv.adobe.com/v/337381) im Hinblick auf neue Funktionen.

   * **Experience Manager Assets as a Cloud Service**

      _Neue Funktionen in Experience Manager Assets_

      * Dynamic Media: Sie können jetzt die Dynamic Media-Benutzeroberfläche von Experience Manager verwenden, um [Allgemeine Einstellungen](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-general-settings.html?lang=de) und [Veröffentlichungseinstellungen](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-publish-settings.html?lang=de) zu konfigurieren, und müssen hierfür nicht auf das Desktop-Programm Dynamic Media Classic zurückgreifen.
      * Dynamic Media unterstützt jetzt die Aufnahme, Vorschau, Wiedergabe und Veröffentlichung von MXF-Videos. Anmerkungen und Videos mit Shopping-Funktion werden bei MXF-Videos noch nicht unterstützt.
      * Nach dem Konfigurieren einer Verbindung zwischen Remote-DAM- und Sites-Implementierungen werden die Assets auf Remote-DAM in der Sites-Implementierung verfügbar gemacht. Sie können jetzt über Remote-DAM-Assets oder -Ordner die [aktualisieren, löschen, umbenennen und verschieben](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=de). Die Aktualisierungen stehen mit etwas Verzögerung automatisch in der Sites-Implementierung zur Verfügung.

      _Neue Funktionen im Vorabversionskanal von Experience Manager Assets_

      * Dynamic Media bietet jetzt die Möglichkeit, in der Benutzeroberfläche [ein (1) Alias-Konto für ein Unternehmen](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=de) zu konfigurieren, sodass die nativen URLs von Dynamic Media und der Viewer-Einbettungs-Code aktualisiert werden. Diese Aktion wirkt sich positiv auf SEO aus, um Aktualisierungen an Ihrem Geschäftskontext widerzuspiegeln, z. B. Rebranding.
      * Sie können jetzt die Experience Manager Assets-Benutzeroberfläche für folgende Aufgaben verwenden:

         * Konfigurieren Sie die Erkennung doppelter Assets in einem Repository.
         * Konfigurieren Sie das Hinzufügen digitaler Wasserzeichen zu Bildern.
      * Administratoren können jetzt den E-Mail-Service für große Downloads konfigurieren. Dadurch können Benutzer über die Experience Manager Assets-Benutzeroberfläche [E-Mail-Benachrichtigungen für große Downloads aktivieren](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=de#enable-email-notifications-for-large-downloads). Nach Abschluss des Download-Prozesses erhält der Benutzer eine E-Mail-Benachrichtigung mit dem Download-Link des archivierten ZIP-Ordners.
      * Die Funktion [Veröffentlichung verwalten](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=de) erhielt eine verbesserte Benutzeroberfläche. Benutzer können Inhalte im ausgewählten Ziel veröffentlichen oder die Veröffentlichung aufheben. Zusätzlich ist das [Hinzufügen von Inhalten](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=de#add-content) zur Veröffentlichungsliste aus dem gesamten DAM-Repository möglich. Sie können beim Veröffentlichen des Inhalts aus den ausgewählten Ordnern auch [Ordnereinstellungen einschließen](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=de#include-folder-settings) und Filter anwenden sowie für einen späteren Zeitpunkt eine [Veröffentlichung planen](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=de#publish-assets-later).

      _Fehlerbehebung_

      * Nicht verarbeitete Assets ohne ursprüngliche Ausgabedarstellung werden zur Verarbeitung an Asset Compute gesendet, während Assets von Experience Manager On-Premise zu Cloud-Services migriert werden.
   * **Experience Manager Forms as a Cloud Service**

      _Neu in Forms_

      * **Experience Manager Forms as a Cloud Service – Kommunikationen** – [Kommunikations-APIs](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=de) helfen Ihnen, eine Vorlage und XML-Daten zu vereinen, um Print-Dokumente in verschiedenen Formaten zu erstellen. Mit dem Service können Sie Dokumente im synchronen Modus und im Batch-Modus generieren. Mit den APIs können Sie Anwendungen erstellen, die Ihnen bei folgenden Aufgaben helfen:

         * Erstellen von Dokumenten durch Füllen von Vorlagendateien mit XML-Daten.
         * Generieren von Formularen in verschiedenen Formaten, einschließlich nicht interaktiver PDF-Printstreams.
         * Generieren von druckbaren PDFs aus XFA-Formular-PDFs.
         * Generieren von PDF-, PostScript-, PCL- und ZPL-Dokumenten in großen Mengen durch Zusammenführen mehrerer Datensätze mit den Quellvorlagen.
      * **Benutzerdefinierte Schriftarten für Datensatz- und PDF-Dokumente, die mit Kommunikations-APIs erstellt wurden** – Sie können jetzt entsprechend Ihren Unternehmensanforderungen markengenehmigte Schriftarten in PDF-Dokumenten verwenden, die mithilfe von Kommunikations-APIs generiert wurden.

      _Neu im Forms-Vorabversionskanal_

      * [Assembler-API](https://developer.adobe.com/experience-manager-forms-cloud-service-developer-reference/references/assembler-sync/) – Assembler-APIs zum Kombinieren, Neuanordnen, Erweitern und Abrufen von Informationen zu PDF-Dokumenten.
   * **Cloud Manager**

      _Versionsdatum_

      Die Version 2022.01.0 von Cloud Manager in Experience Manager as a Cloud Service wurde am 20. Januar 2022 veröffentlicht.
Die nächste Version soll am 31. März 2022 veröffentlicht werden.

      _Neue Funktionen_

      * Cloud Manager [vermeidet den Neuaufbau der Code-Basis, wenn festgestellt wird, dass ein und derselbe Git-Commit](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/create-application-project/setting-up-project.html?lang=de#build-artifact-reuse) in mehreren Pipeline-Ausführungen mit vollem Stapel verwendet wird.
      * Für den Zugriff auf das Experience Manager-Umgebungsprotokoll ist jetzt das Produktprofil **[!UICONTROL Deployment Manager]** erforderlich. Benutzern ohne dieses Profil wird in der Benutzeroberfläche eine deaktivierte Schaltfläche angezeigt.
      * Die Benutzeroberfläche lässt keine Konfiguration der Front-End-Pipeline für ein Programm zu, bei dem Sites nicht als Lösung aktiviert ist.
      * Beim Generieren eines Git-Passworts wird das Ablaufdatum angezeigt.








### Community

* **Experience Manager-GEMS-Webinar: _Schnellere Erstellung von Sites mit Experience Manager Headless und App Builder_**

   * Haben Sie die Eröffnungsschlüsselnote zum Adobe Summit 2022 verpasst? Watch [Digitale Wirtschaft als persönlich erachten](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2022-opening-keynote-make-the-digital-economy/td-p/444612).
   * Adobe Summit 2022 | [Vollständige Experience Manager-Sitzungsliste](https://adobe.ly/3rti6gF).
   * Experience Manager-GEMs | Webinar | Mittwoch, 23. März 2022
      * Thema: *Schnellere Erstellung von Sites mit Experience Manager Headless und App Builder*
      * [Hier registrieren](https://adobe.ly/3oCkEsh)
      * [Für Fragen und Antworten](https://adobe.ly/3LkSWdm)

### Neue Experience Manager-Kurse und -Tutorials {#tutorials-aem}

Nachfolgend sind die im vergangenen Monat neu veröffentlichten Videos, Tutorials und Kurse aufgeführt.

| Veröffentlicht | Name | Typ | Beschreibung | Programme |
| -----------| ---------- | ---------- | ---------- | ------|
| März 2022 | [Entwicklung mit AEM Headless beginnen](https://experienceleague.adobe.com/landing/experience-manager/headless/developer.html?lang=de) | Kurs | Erstellen Sie AEM Headless-Landingpage, die den gesamten Inhalt auf AEM Headless auf ExL abruft. | AEM Headless |
| März 2022 | [Erstellen Ihrer ersten Website in Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.1.aemcs.website) | Kurs | Schnelles Generieren einer neuen Website in Experience Manager mithilfe einer vordefinierten Site-Vorlage. | AEM Sites |
| März 2022 | [Knoten aus gesendeter Daten-XML extrahieren](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/custom-workflow-steps/extract-xml-node.html?lang=en) | Video | Lernen Sie diesen benutzerdefinierten Prozessschritt kennen, um ein XML-Dokument zu erstellen, indem Sie Knoten aus einem anderen XML-Dokument extrahieren. Verwenden Sie diesen Vorgang, wenn Sie die gesendeten Daten mit der XDP-Vorlage zusammenführen möchten, um PDF zu generieren. | AEM Forms |
| März 2022 | [Schreiben Sie das Dokument in das Dateisystem](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/custom-workflow-steps/write-payload-document.html?lang=en) | Video | Erfahren Sie, wie Sie die generierten Dokumente im Workflow in das Dateisystem schreiben. | AEM Forms |
| März 2022 | [Benutzerdefinierte Funktionen](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/custom-functions-aem-forms.html?lang=en) | Video | AEM Forms 6.5 bietet nun die Möglichkeit, JavaScript-Funktionen zu definieren, mit denen komplexe Geschäftsregeln mithilfe des Regeleditors definiert werden können. | AEM Forms |
| März 2022 | [Workfront für Experience Manager - Expertenserie für Connectoren](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/overview.html?lang=en) | Video | Nehmen Sie an dieser vierteiligen Videoserie teil, in der die Experten von Adobe Workfront und Experience Manager Assets die Ins und Outs der Workfront für den erweiterten Connector für Experience Manager demonstrieren und diskutieren. | AEM Assets, Workfront |
| März 2022 | [Kaskadierende Dropdown-Listen](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/geonames-org.html?lang=en) | Video | Ein Tutorial mit Beispiel-Assets zum Erstellen eines Formulars mit einer Dropdown-Liste für Kaskadierende Elemente. | AEM Forms |
| März 2022 | [Ersteinrichtung und -konfiguration](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/setup.html?lang=en) | Video | Erfahren Sie, wie Sie den Workfront für Experience Manager Enhanced Connector einrichten und konfigurieren, um die kombinierte Leistung von AEM Assets und Workfront zu erschließen. | AEM Assets, Workfront |
| März 2022 | [Benutzerdefinierte Formulare und Metadatenzuordnung in Workfront](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/custom-forms.html?lang=en) | Video | Erfahren Sie, wie Sie Workfront und AEM Assets konfigurieren, um Asset-Metadaten mithilfe von benutzerdefinierten Workfront-Formularen zu verwalten und zu synchronisieren und Metadatenschemata AEM. | AEM Assets, Workfront |
| März 2022 | [AEM Tags, projektverknüpfte Ordner und Ordnermetadaten](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/aem-tags-project-linked-folders-and-folder-metadata.html?lang=en) | Video | Erfahren Sie, wie Sie die Verwendung von AEM-Tags für Assets über Workfront-Daten fördern, projektverknüpfte Ordner einrichten und verwenden sowie Workfront-Daten, um Metadatenschemata für Asset-Ordner AEM. | AEM Assets, Workfront |
| März 2022 | [Erweiterte Einstellungen und Workflows](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/advanced-settings-and-workflows.html?lang=en) | Video | Erfahren Sie mehr über die erweiterten Einstellungen für Workfront für AEM erweiterten Connector und wie Sie erweiterte Workflows und Starter in AEM konfigurieren, um die Datensynchronisation zwischen AEM und Workfront zu verwalten. | AEM Assets, Workfront |
| März 2022 | [Dynamics-Konto erstellen und konfigurieren](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/formscs-dynamics-crm/create-dynamics-account.html?lang=en) | Video | Erfahren Sie mehr über die Schritte zur Registrierung von Microsoft® Dynamics mit Azure Active Directory. | AEM CS |
| März 2022 | [Öffentliche Linkfreigabe](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/link-sharing.html) | Video | Erfahren Sie, wie Sie mit Share Link von Assets Essentials Assets für interne und externe Stakeholder freigeben können, während Sie gleichzeitig das Risiko minimieren, falsche Assets oder Informationen freizugeben. | AEM Assets |

{style=&quot;table-layout:auto&quot;}

### Versionsinformationen zu Experience Manager

Die nachfolgend aufgeführten Seiten umfassen alle Versionshinweise zu Experience Manager:

* [Versionshinweise für Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=de)
* [Versionshinweise für Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=de)
* [Versionshinweise zum Service für die automatische Formularkonversion](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=de)
* [Versionshinweise für Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=en)
* [Versionshinweise für Experience Manager 6.4 Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=de)
* [Experience Manager Assets Dynamic Media – Versionshinweise](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=de)
* [Versionshinweise für Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=de)
* [Versionshinweise zum Experience Manager-Desktop-Programm ](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=de)
* [Versionshinweise für Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=de)
* [Versionshinweise zu Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=de)
* [Versionshinweise zu Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=de)

### Weitere Hilferessourcen für Experience Manager

* [Handbücher für Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=de)
* [Cloud Manager-Benutzerhandbuch](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=de)
* [Experience Manager 6.5 – Training und Support, Startseite](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=de)
* [Experience Manager 6.4 – Training und Support, Startseite](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=de)
* [Experience Manager 6.3 – Training und Support, Startseite](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=de)
* [Experience Manager 6.2 – Training und Support, Startseite](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=de#previous-updates)
* [Ältere Versionen der Dokumentation zu Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Startseite der Hilfe zu Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=de)
* [Experience Manager-Dokumentation: Neueste Aktualisierungen](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=de#aem-as-a-cloud-service)

## ![Symbol](/assets/ec_appicon_24.png) XML-Dokumentation für Adobe Experience Manager {#xml-doc}

Die XML-Dokumentation für Adobe Experience Manager ist ein Programm, das in AEM bereitgestellt wird. Es handelt sich dabei um eine leistungsstarke, für Unternehmen geeignete Komponenten-Content-Management-Lösung (CCMS), die die native DITA-Unterstützung in Adobe Experience Manager unterstützt und es AEM ermöglicht, die DITA-basierte Inhaltserstellung und -bereitstellung zu handhaben.

Weitere Informationen zu [XML-Dokumentation für AEM](https://www.adobe.com/de/products/xml-documentation-for-experience-manager/features.html).

### Neue Tutorials für [!DNL XML Documentation for Adobe Experience Manager] {#tutorials-xml-doc}

Neue Videos, Tutorials oder Kurse, die für veröffentlicht wurden [!DNL XML Documentation for Adobe Experience Manager].

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| März 2022 | [Ausgabenerstellung mit XML-Dokumentation](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2022.2.xmldocs&amp;lang=de) | Kurs | Erfahren Sie, wie Sie eine Ausgabe generieren mit [!DNL XML Documentation for Adobe Experience Manager]. Erfahren Sie mehr über verschiedene Funktionen, die für die Ausgabegenerierung verfügbar sind, einschließlich Berichten, Grundlinien, Bedingungen, Fehlerbehebung, Massenveröffentlichung und Aktivierung. |

{style=&quot;table-layout:auto&quot;}

### Weitere Ressourcen

* [XML-Dokumentation für Adobe Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=de) – Tutorials zu Experience League
* [XML-Dokumentation für Adobe Experience Manager – Schulung und Support](https://helpx.adobe.com/de/support/xml-documentation-for-experience-manager.html) – Produktdokumentation

## ![Symbol](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Versionshinweise zu Adobe Commerce finden Sie unter den folgenden Links:

* [Adobe Commerce und Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite für Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### Neue Adobe Commerce-Ressourcen {#new-commerce}

Neue Dokumentationen und Tutorials zu Adobe Commerce on Experience League.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| März 2022 | [Handbuch für Zahlungsdienste](https://experienceleague.adobe.com/docs/commerce-merchant-services/payment-services/guide-overview.html) | Handbuch | Ein Handbuch für Administratoren von Adobe Commerce und Magento Open Source. Es enthält detaillierte Informationen über die Installation und das Onboarding von Zahlungsdiensten sowie die Konfiguration und Verwaltung der Dienste. Es wird von einem grundlegenden Verständnis der Commerce-Konfiguration und -Funktionalität ausgegangen. |

{style=&quot;table-layout:auto&quot;}

## ![Symbol](/assets/target.png) [!DNL Adobe Target] {#target}

Zuletzt aktualisiert: **21. März 2022**

* Informationen zur Vorabversion finden Sie unter [Vorabversion von Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=de)
* Aktuelle Informationen finden Sie unter [Versionshinweise zu Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=de)

## ![Symbol](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Aktuelle Campaign-Produktversionen

Erfahren Sie mehr über die aktuellsten veröffentlichten Funktionen, Verbesserungen und Fehlerbehebungen:

* [Campaign Classic v7.2.2](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=de)

### Neue Tutorials und Kurse zu [!DNL Campaign] {#tutorials-campaign}

Neue für Adobe Campaign veröffentlichte Tutorials und Kurse.

| Veröffentlicht | Name | Typ | Beschreibung | Programme |
| ------| ----- | -----| ------ | --- |
| März 2022 | [Integration in Experience Manager – Übersicht](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/overview.html?lang=de) | Video | Verbinden Sie Adobe Campaign mit Adobe Experience Manager, um E-Mail-Versandvorlagen, Assets und Formulare in Experience Manager zu verwalten. | AEM, Campaign v8 |
| März 2022 | [Konfigurieren von Campaign für die Experience Manager-Integration](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/configure-campaign-for-aem-integration.html?lang=en) | Video | Erfahren Sie, wie Sie die Integration zwischen Experience Manager und Campaign einrichten, einschließlich wichtiger Einstellungen für die Suche und möglicher &quot;Fallstricke&quot;, die vermieden werden können. | AEM, Campaign v8 |
| März 2022 | [Genehmigen und Veröffentlichen einer Experience Manager-Seite in Campaign](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/create-a-campaign-delivery-with-content-from-experience-manager/approve-and-publish-aem-content-to-campaign.html?lang=en) | Video | Erfahren Sie, wie Sie in Experience Manager einen Newsletter erstellen und genehmigen und ihn dann in Campaign veröffentlichen. | AEM, Campaign v8 |
| März 2022 | [Experience Manager-E-Mail-Versand in Campaign synchronisieren und senden](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/create-a-campaign-delivery-with-content-from-experience-manager/synchronize-and-send-an-aem-delivery-in-campaign.html?lang=en) | Video | Erfahren Sie, wie Sie eine E-Mail von Adobe Campaign mit einem in Experience Manager erstellten Newsletter testen und versenden können. | AEM, Campaign v8 |
| März 2022 | [Integration mit Adobe Target](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/connect/target-integration.html) | Video | Hier erfahren Sie, wie Sie einen Versand mit dynamischen Inhalten personalisieren, die von Adobe Target bereitgestellt werden. | Adobe Target, Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### Hilferessourcen für Campaign

* Adobe Campaign Version 8: [Dokumentation](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) – [Implementierungshandbücher](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=de)
* Adobe Campaign Standard: [Campaign Standard – Dokumentation](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=de) – [Anleitungsvideos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=de) – [Versionsplanung](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=de) – [Neueste Aktualisierungen der Dokumentation](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=de)
* Adobe Campaign Classic: [Campaign Classic v7 – Dokumentation](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) – [Anleitungsvideos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=de) – [Neueste Aktualisierungen der Dokumentation](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=de)
* Control Panel von Adobe Campaign: [Dokumentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=de)  – Anleitungsvideos für [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=de)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=de)

## ![Symbol](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Mit Journey Optimizer können Sie geplante Omni-Channel-Kampagnen und individuelle Erlebnisse für Millionen von Kunden in einem zentralen Programm verwalten – und die gesamte Journey wird mit intelligenten Entscheidungen und Erkenntnissen optimiert.

### Neueste Journey Optimizer-Produktversionen

Erfahren Sie mehr über die neuesten Funktionen, Verbesserungen und Fehlerbehebungen in den [Versionshinweisen zu Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=de).

### Neue Tutorials und Kurse zu Journey Optimizer {#tutorials-ajo}

Neueste Journey Optimizer-Tutorials:

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| März 2022 | [Verwenden und Verwalten gespeicherter Ausdrücke in der Personalisierungsbibliothek](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/personalize-content/use-and-manage-saved-expressions-in-personalization-library.html?lang=en) | Video | Erfahren Sie, wie Sie gespeicherte Elemente der Personalisierungsbibliothek in einer Nachricht verwenden und wie Sie Elemente der Personalisierungsbibliothek erstellen und verwalten. |

### Weitere Ressourcen zu [!DNL Journey Optimizer]

* [Dokumentation zu Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) – [Anleitungsvideos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=de)
* [Dokumentation zum Entscheidungs-Management](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) – [Anleitungsvideos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=de) – [Neueste Aktualisierungen der Dokumentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=de)

## ![Symbol](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Verwenden Sie Experience Platform, um die Customer Journey in großem Umfang über alle Erlebniskanäle hinweg zu orchestrieren, indem Sie die Bedürfnisse jedes Einzelnen in Echtzeit intelligent antizipieren.

### Aktuelle [!DNL Journey Orchestration]-Produktversionen

Erfahren Sie mehr über die neuesten Funktionen, Verbesserungen und Fehlerbehebungen in den Versionshinweisen zu [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=de).

#### Weitere Ressourcen zu [!DNL Journey Orchestration]

* [Dokumentation zu Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) – [Anleitungsvideos](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=de) – [Neueste Aktualisierungen der Dokumentation](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=de)

## ![Symbol](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] ist eine Komplettanwendung für das Lead-Management. B2B-Marketer können damit Kundenerlebnisse transformieren, indem sie in allen Phasen komplexer Customer Journeys Interaktionen ermöglichen.

### Aktualisierungen von Core Marketo Engage

Aktuelle Informationen zum Veröffentlichungszeitplan sowie Versionshinweise finden Sie in der [!DNL Marketo Engage] [Versionsplanung](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=de).

### Neue Marketo-Tutorials und -Kurse {#tutorials-marketo}

Neue Tutorials und Kurse veröffentlicht für Adobe Marketo.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| März 2022 | [Personalisierte Dialogfelder erstellen und verwalten](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/dialogue-management.html?lang=en) | Video | Erfahren Sie, wie Sie eine _[!UICONTROL Dialogfeld]_. Die Erstellung zielgerichteter und personalisierter Konversationen ist der Schlüssel zu einem großartigen Gesprächserlebnis für jeden Webbesucher. |
| März 2022 | [Einrichten und Installieren des Chat-Bots](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/setup.html?lang=en) | Video | Eine Anleitung zur Installation von Chatbot-JavaScript auf Ihrer Website oder Landingpage und zur Anpassung des Erscheinungsbilds an Ihre Marke. |
| März 2022 | [Personen die Möglichkeit geben, mit Ihrem Verkaufsteam Meetings zu buchen](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/meeting-booking.html?lang=en) | Video | Verwendung [!UICONTROL Dynamischer Chat] um die Verbindung mit dem Umsatz für Target-Konto-Leads zu beschleunigen. |
| März 2022 | [Aktivieren Sie Ihre Marketo-Integration mit [!UICONTROL Dynamischer Chat]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/marketo-integration.html?lang=en) | Video | [!UICONTROL Dynamischer Chat] ist nativ in Marketo Engage integriert, was es Ihnen ermöglicht, Kontext aus Chatbot-Konversationen zu nutzen, um Ihre potenziellen Kunden neu zu bestimmen oder zu bewerten. |
| März 2022 | [Benutzer verwalten von [!UICONTROL Dynamischer Chat]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/user-management.html?lang=en) | Video | Verwalten Sie Ihre [!UICONTROL Dynamischer Chat] Benutzer über Adobe Admin Console. |
| März 2022 | [Produktübersicht [!UICONTROL Dynamischer Chat]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/product-tour.html?lang=en) | Video | [!UICONTROL Dynamischer Chat] ist eine neue Chatbot-Lösung, die für Marketing und Vertrieb entwickelt wurde. Es ist nativ in Marketo Engage integriert, sodass Sie den dynamischen Chat als neuen Kanal in Ihrem kanalübergreifenden Marketing verwenden können. Es ist einfach zu verwenden und leicht einzurichten. |

## ![Symbol](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] ist eine umfassende Software für das Ideenmanagement, die Content-Erstellung und die Verwaltung komplexer Prozesse, die optimales Arbeiten im Team ermöglicht.

Auf der Seite zu [[!DNL Workfront] Versionen](https://one.workfront.com/s/product-releases) finden Sie eine Zusammenfassung der aktuellsten Informationen zu allen Produkten.

## ![Symbol](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Versionshinweise für [!DNL Adobe Advertising Cloud].

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
* [Neue Funktionen in Version  [!DNL Advertising Cloud Search]](#adcloud-search)
* [Neue  [!DNL Advertising Cloud] -Tutorials](#tutorials-ad-cloud)

<!-- 
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

{style="table-layout:auto"}
-->

<!-- 
### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Custom Reports | You can now create and manage [!DNL Amazon S3] and different types of FTP delivery locations, called *[!DNL report destinations]*, for your custom reports. Once you configure report destinations, you can set up each of your new custom reports to be delivered to one or more locations of a single destination type, or to email recipients. Updates to your [!DNL Amazon S3] and FTP credentials won't interrupt report delivery.<br><br>Your existing reports are still sent to the specified email recipients. To configure delivery to a different report destination, create a report with the new destination. |
| [!UICONTROL Packages], [!UICONTROL Placements], and [!UICONTROL Ads] views| When you view data for a single day, the trend charts now include hourly data. Hold the cursor over any point to see the data for that hour. |
| [!UICONTROL Placements] | The placement [!UICONTROL Inspector] now includes an [!UICONTROL Inventory] tab, which shows all deals and their associated metrics for the placement. Use the information to make quick adjustments or troubleshoot issues without generating a custom report. |
| [!UICONTROL Ads] | (Users with permission to include Clearcastclock numbers in their ads) DSP no longer shows an error if you use a clock number that's attached to another ad. **Note:**  The best practice is to use a unique clock number for each video ad. Otherwise, the publisher does not approve all the ads. |
| [!UICONTROL Deal IDs] | The [!UICONTROL Deal ID] settings and other places in the user interface reflect new branding for [!DNL Magnite] SSP:<br><ul><li>The SSP [!DNL Tremor] ([!DNL Telaria]) is now [!DNL Magnite CTV].</li><li>In the coming weeks, [!DNL Rubicon] will change to [!DNL Magnite DV+], where [!DNL DV+] stands for display, video, and other formats such as audio.</li></ul> |
| [!DNL Freewheel] programmatically guaranteed deals | You can now find the status of ads for [!DNL Freewheel] programmatically guaranteed deals from the [!UICONTROL Ads] view. Previously, you could check the status only from the [!UICONTROL Deals] view. |
-->

<!--
{style="table-layout:auto"}
-->

### Neue Funktionen in Version [!DNL Advertising Cloud Search] {#adcloud-search}

Zuletzt aktualisiert: **14. März 2022** für Version vom 12. März

| Funktion | Beschreibung |
| ------- | ----------- |
| [!UICONTROL Portfolios] | Standardmäßig ist die Hybridoptimierung auf Kampagnenebene verfügbar. Sie können jetzt optional die Hybridoptimierung auf Anzeigengruppenebene aktivieren, für die die Optimierungsfunktion [!DNL Google] CPA- oder ROAS-Ziele auf Anzeigengruppenebene für eine präzisere Leistungssteuerung.<br>Bei jedem Portfolio müssen Sie einen Lernzeitraum einräumen, bevor Sie das Portfolio starten, um sicherzustellen, dass es über eine ausreichende Modellabdeckung verfügt. Wenn Sie ein hybrides Portfolio von der Optimierung auf Kampagnenebene in die Optimierung auf Anzeigengruppenebene ändern, legen Sie das Portfolio für etwa zwei Wochen auf den aktiven Status fest. Dadurch wird sichergestellt, dass die Optimierungsfunktion Zeit hat, über die enthaltenen Anzeigengruppen zu erfahren und Ziele zu generieren.<br>Um die Optimierung auf Anzeigengruppenebene zu unterstützen, können benutzerdefinierte Simulationen jetzt Ergebnisse nach Anzeigengruppe enthalten. Führen Sie eine benutzerdefinierte Simulation mit Ergebnissen auf Anzeigengruppenebene durch, bevor Sie ein hybrides Portfolio mit Optimierung auf Anzeigengruppenebene starten. |
| [!UICONTROL Portfolios] <br> [!UICONTROL Kampagnen] | (Beta-Funktion, [!DNL Microsoft® Advertising] campaigns) - Sie können jetzt Suchkampagnen konfigurieren, um die [!UICONTROL Maximieren von Konversionen] Angebotsstrategie und optional Festlegung von maximalen Kosten pro Klick.<br>Wenn Sie bereits an der Hybrid-Optimierungs-Beta für andere Strategien der automatischen Angebotsabgabe teilnehmen, haben Sie automatisch Zugriff auf die [!UICONTROL Maximieren von Konversionen] und Sie können Kampagnen in die [!UICONTROL Maximieren von Konversionen] Strategie in hybriden Portfolios. Um diese Strategie in einem Hybridportfolio zu verwenden, müssen Sie das Hochladen von Advertising Cloud Search-Zielen in [!DNL Microsoft® Ads]. Wenn Sie noch nicht an der Beta-Phase teilnehmen und Mitglied werden möchten, wenden Sie sich an Ihren [!DNL Adobe] Kundenbetreuer. |
| Kampagne [!UICONTROL Zielgruppen]<br><br>Kampagne [!UICONTROL Bulksheets] | ([!DNL Microsoft® Advertising] Kampagnen) - Sie können jetzt eine Ihrer [!DNL Microsoft® Advertising] Zielgruppen außer marktinternen Zielgruppen als Zielgruppen auf Kampagnenebene oder [!UICONTROL adgroup]-Ziele. Zuvor konnten Sie sie nur als [!UICONTROL adgroup]-Ziele. |
| Kampagne [!UICONTROL Zielgruppen] | (Beta-Funktion, [!DNL Microsoft® Advertising] Konten, die [!UICONTROL Kundenabgleich]) Sie können jetzt Zielgruppen für die Kundenabstimmung erstellen und verwalten, indem Sie CSV-Dateien mit E-Mail-Adressen hochladen. Die Daten müssen mit dem SHA-256-Algorithmus gehasht werden. |

{style=&quot;table-layout:auto&quot;}

### Neue Advertising Cloud-Tutorials {#tutorials-ad-cloud}

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| März 2022 | [Erstellen einer standardmäßigen Anzeigeplatzierung](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/placement-create.html) | Video | Erfahren Sie, wie Sie eine standardmäßige Anzeigeplatzierung für eine Advertising Cloud DSP-Kampagne erstellen. |

{style=&quot;table-layout:auto&quot;}

## ![Symbol](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Neue für Adobe Document Cloud veröffentlichte Tutorials und Kurse.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| März 2022 | [Benutzerdefinierte Befehle und Tools](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/custom.html?lang=en) | Video | Erfahren Sie, wie Sie mithilfe von benutzerdefinierten Befehlen und Tools die Produktivität des Dokument-Workflows verbessern können. Geben Sie dann Ihre neuen Befehle und Tools für Kollegen frei, um die Effizienz Ihrer Organisation zu verbessern. |
| März 2022 | [Lesezeichen und Hyperlinks hinzufügen](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/bookmarks.html?lang=en) | Video | Erfahren Sie, wie Sie Lesezeichen und Hyperlinks hinzufügen, um die Navigation und Interaktion mit Ihren PDF-Dateien zu verbessern. |
| März 2022 | [Gescannte Dokumente optimieren](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/optimizescan.html) | Video | Egal ob Ihr Dokument von einer Kamera oder einem Scanner stammt, lernen Sie, wie Sie das Ergebnis in Acrobat verbessern können, um eine bessere PDF-Anzeige und Sucherfahrung zu erzielen. |
| März 2022 | [Konvertieren von Word in PDF einschließlich Formularfeldern](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/wordform.html?lang=en) | Video | In diesem 60-Sekunden-Video-Tutorial erfahren Sie, wie Sie Word-Dateien und Formulare in PDF konvertieren und Formularfelder automatisch erstellen. |
| März 2022 | [Erweiterte Formularfelder](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/advancedforms.html?lang=en) | Video | In diesem praxisorientierten Tutorial erfahren Sie, wie Sie Berechnungen einrichten, eine E-Mail-Senden-Schaltfläche erstellen und Formularseiten schnell aktualisieren, ohne alle vorhandenen Formularfelder neu erstellen zu müssen. |
| März 2022 | [Effizientere PDF-Dateien per Schnappschuss erstellen](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/optimize.html?lang=en) | Video | In diesem 60-Sekunden-Video-Tutorial erfahren Sie, wie Sie mit dem Optimize PDF-Tool die Dateigröße Ihrer PDF erheblich reduzieren können. |
| März 2022 | [Text in einer gescannten PDF-Datei erkennen](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/textrecognition.html?lang=en) | Video | In diesem 60-Sekunden-Video-Tutorial erfahren Sie, wie Sie eine gescannte PDF konvertieren, damit Sie in der PDF nach Text suchen können. |
| März 2022 | [Mit Acrobat können Sie barrierefreie PDF bereitstellen](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/accessible.html?lang=en) | Video | In diesem 60-Sekunden-Video-Tutorial erfahren Sie, wie Sie überprüfen können, ob auf eine PDF zugegriffen werden kann. |
| März 2022 | [Export PDF zu Word von Ihrem Telefon aus](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/exportwordphone.html?lang=en) | Video | In diesem 60-Sekunden-Video-Tutorial erfahren Sie, wie Sie mit der mobilen Acrobat-App eine PDF-Datei in ein vollständig bearbeitbares Microsoft® Word-Dokument konvertieren. |
| März 2022 | [Protect Ihrer PDF-Dateien mit einem Kennwort](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/protect.html?lang=en) | Video | In diesem 60-Sekunden-Video-Tutorial erfahren Sie, wie Sie eine PDF schützen können, sodass ein Kennwort erforderlich ist, um die PDF zu öffnen oder zu bearbeiten. |

{style=&quot;table-layout:auto&quot;}

Hilfe zu Document Cloud erhalten Sie über:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=de)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=de)
* [Document Cloud: Lernen und Support](https://helpx.adobe.com/de/support/document-cloud.html)

## ![Symbol](/assets/creative-cloud-24.png) Adobe Creative Cloud für Unternehmen {#creative-cloud}

Unter [Creative Cloud für Unternehmen – Tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=de) finden Sie die neuesten Tutorials.

## ![Symbol](/assets/experience-league.png) Customer Data Management - Stimmen {#voices}

[Stimmen im Customer Data Management](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) ist Ihr Ziel als technischer und Marketing-Praxisführer und -Spezialist für das Kundendatenmanagement. Diese Sammlung von Tutorials ist Ihr One-Stopp-Shop, um von Ihren Kollegen zu hören, sich inspirieren zu lassen und über die Entwicklungen in MarTech zu erfahren. Keine Registrierung erforderlich, klicken und beobachten.

## ![Symbol](/assets/experience-league.png) Digital Experience Blueprints {#blueprints}

[Digital Experience Blueprints](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=de) sind wiederholbare Implementierungen, die Ihnen helfen, Strategien zu entwickeln und bestehende geschäftliche Herausforderungen zu meistern. Jeder Blueprint bietet eine Reihe von Artefakten, die jeweils die anspruchsvolle geschäftliche Herausforderung, die Architekturen, die Implementierungsschritte und die technischen Überlegungen erläutern, sowie die Links zur entsprechenden Dokumentation.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Februar 2022 | [Customer Journeys](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=de) | Video | Customer Journeys ermöglichen es Marken, aktiv mit ihren Kunden über Kanäle wie E-Mail, SMS und Benachrichtigungen auf Smartphone und Tablet zu interagieren und mit ihnen zu kommunizieren. |
| Februar 2022 | [Campaign v7-Blueprint](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/campaign-v7/campaign-v7.html?lang=de) | Video | Adobe Campaign v7 ist ein Tool für Kampagnen, das für herkömmliche Marketing-Kanäle wie E-Mail und Direkt-Mail entwickelt wurde. Es bietet zuverlässige ETL- und Daten-Management-Funktionen, mit denen Sie die perfekte Kampagne erstellen und kuratieren können. |

{style=&quot;table-layout:auto&quot;}
