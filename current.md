---
title: Neueste Versionshinweise
description: Hier finden Sie Informationen über die aktuellen Versionshinweise, neue Funktionen und neue Dokumentation für Experience Cloud-Produkte und -Services. Hier finden Sie neues Material rund um Hilfen und Tutorials zu Experience Cloud, Creative Cloud für Unternehmen und Document Cloud.
doc-type: release notes
last-update: June 2021
author: mfrei
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 22f12b5bc45f0ed2c191c395c55314e646a330f2
workflow-type: tm+mt
source-wordcount: '5062'
ht-degree: 51%

---

# Adobe Experience Cloud – Versionshinweise, Juni 2021

![Banner](assets/experience-cloud-banner-3.png)

Experience Cloud-Programme und -Services werden monatlich aktualisiert. Auf dieser Seite finden Sie die neuesten Versions-Updates, Dokumentationen und Tutorials zu [!DNL Experience Cloud] und [!DNL Experience Platform]. Sie finden hier außerdem eine neue Dokumentation für [!DNL Creative Cloud for Enterprise] und [!DNL Document Cloud].

>[!NOTE]
>
>Abonnieren Sie das monatliche [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html), um E-Mail-Benachrichtigungen über Aktualisierungen dieser Seite zu erhalten. Diese Seite wird den ganzen Monat über gepflegt. Informieren Sie sich daher regelmäßig über die neuesten Updates zu Adobe Unternehmensprodukten und der Experience League-Dokumentation.

Letzte Aktualisierung: **11. Juni 2021**

* [Zentrale Schnittstellenkomponenten von Experience Cloud](#ecloud)
* [Adobe-Systemstatus](#status)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Offer Decisioning](#offer-decisioning)
* [[!DNL Analytics]](#analytics) und [Customer Journey Analytics](#cust-journey) 
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Campaign]](#ac)
* [[!DNL Advertising]](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

Benötigen Sie Hilfe? Besuchen Sie [Adobe Experience League](https://experienceleague.adobe.com/?lang=de#home), um Produkt- und technische Dokumentation, von Adobe kuratierte Kurse, Video-Tutorials, schnelle Antworten, Community-Einblicke und von Schulungsleitern geführte Kurse zu erhalten.

## ![](/assets/ec_appicon_24.png) SymbolZentrale Experience Cloud-UI-Komponenten {#ecloud}

Experience Cloud Central Interface Components umfasst Aktualisierungen, auf die über die einheitliche Produktheader zugegriffen werden kann, z. B. Voreinstellungen für Selbsthilfe, Suche und Benutzerkonten. Updates für Personen, Orte (Ort) und Produktverwaltung finden Sie hier.

| Funktion | Datum | Beschreibung |
| ------- | ------- | ------- |
| Single-Sign-On-Unterstützung für Adobe Federated IDs | 17. Juni 2021 | Wenn Sie Federated IDs verwenden, können Sie sich bei Experience Cloud anmelden, ohne eine E-Mail-Adresse oder ein Passwort eingeben zu müssen. Um diese Funktion zu verwenden, fügen Sie **#/sso:@domain** zur Experience Cloud-URL hinzu. <br><br>Nehmen wir beispielsweise an, dass Sie der Domäne  **adobeccustomer.** com gehören und sich bei Adobe Analytics anmelden möchten. Die URL lautet: **https://experience.adobe.com/#/sso:@adobecustomer.com/analytics**. |
| Experience League-Suche | 1. Juni 2021 | Die Experience League-Dokumentationssuche wurde verbessert. Navigieren Sie zu [Experience League](https://experienceleague.adobe.com/docs/?lang=en) und verwenden Sie das Feld **[!UICONTROL Suchen]** , um Tutorials, Dokumentationen, Kurse und mehr zu finden. |

{style=&quot;table-layout:auto&quot;}

**Weitere Hilferessourcen**

* Administration-Hilfe für [Central Interface Components](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) und Benutzerverwaltung
* Hilfe und Versionshinweise für [Orte - Location Service](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)
* Hilfe zu [Personen - Kundenattribute und Zielgruppenbibliothek](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)
Eine Produktdokumentation zu diesen Funktionen finden Sie unter [Experience Cloud Central Interface Components](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en).

## ![Symbol](/assets/adobe.png) Adobe-Systemstatus {#status}

[!UICONTROL Der Adobe-Systemstatus] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe Cloud-Produkten und -Diensten. Weitere Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/).

Informationen zu den neuesten Aktualisierungen des Adobe-Systemstatus finden Sie unter [Adobe-Systemstatus – 21. Mai 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=de).

## ![Symbol](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Enthält Versionsupdates und neue Dokumentationen für Experience Platform und Experience Platform Launch.

* **26. Mai 2021:** [Versionshinweise zur Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=de)
* **17. Mai 2021:** [Versionshinweise zur Experience Platform-Datenerfassung](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html?lang=de)  (früher Experience Platform Launch)

### Experience Platform-Tutorials und -Kurse {#tutorials-platform}

Neue Videos, Tutorials oder Kurse, die für Experience Platform und Services veröffentlicht wurden.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Juni 2021 | [Daten vorbereiten](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/prepare-data.html) | Video | Erfahren Sie, wie Sie Daten aus mehreren Datensätzen bereinigen, vorbereiten und kombinieren können, um einen Datensatz mit den Funktionen &quot;Tabelle AS (CTAS) erstellen&quot;und &quot;Spark SQL&quot;für die Berichterstellung und das Dashboard zu erstellen. |
| Juni 2021 | [Kopieren von Schemata zwischen Sandboxes](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/copy-schemas-between-sandboxes.html) | Video | Erfahren Sie, wie Sie ein Schema in Adobe Experience Platform mithilfe der [!UICONTROL Export/Import-Schema-API] aus einer Sandbox in eine andere kopieren. Erstellen und testen Sie Ihre Schemas in Entwicklungs-Sandboxes und kopieren Sie sie dann in die Produktion. |
| Juni 2021 | [Schemata aktualisieren](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/update-schemas.html) | Video | Lernen Sie die wichtigsten Informationen zum Aktualisieren vorhandener Schemata in Adobe Experience Platform kennen. |
| Juni 2021 | [Schema-Bausteine](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schema-building-blocks.html) | Video | Erfahren Sie mehr über die wichtigsten Bausteinelemente von Experience-Datenmodell (XDM)-Schemas, einschließlich Feldern, Datentypen, Schemafeldgruppen, Klassen und Verhalten. |
| Juni 2021 | [Klassen erstellen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-classes.html) | Video | Erfahren Sie, wie Sie in Adobe Experience Platform Klassen zur Verwendung in Experience-Datenmodell (XDM)-Schemas erstellen. |
| Juni 2021 | [Beziehungen zwischen Schemata konfigurieren](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/configure-relationships-between-schemas.html) | Video | Erfahren Sie, wie Sie in Adobe Experience Platform eine Beziehung zwischen zwei Schemas konfigurieren. Beziehungen ermöglichen es Ihnen, einen Datensatz als Suchtabelle für einen anderen zu verwenden. |
| Juni 2021 | [Erstellen von Datentypen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-data-types.html) | Video | Erfahren Sie, wie Sie Ihre eigenen Datentypen in Adobe Experience Platform zur Verwendung in Experience-Datenmodell (XDM)-Schemata erstellen. |
| Juni 2021 | [Konvertieren Ihres Datenmodells in ein Erlebnisdatenmodell](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/convert-your-data-model-to-xdm.html) | Video | Erfahren Sie, wie Datenarchitekten ihr vorhandenes Transaktionsdatenmodell in ein Experience-Datenmodell konvertieren können. In diesem Video wird der Unterschied bei der Modellierung von Ansätzen anhand von Entitäts-Beziehungsdiagrammen veranschaulicht. |
| Juni 2021 | [Datenmodell planen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/plan-your-data-model.html) | Video | Erfahren Sie, was Sie tun müssen, bevor Sie mit der Erstellung Ihrer Schemas in Adobe Experience Platform beginnen. Dokumentieren Sie Ihre geschäftlichen Anwendungsfälle, verstehen Sie Ihre Platform-Lizenz, kennen Sie die Produktgarantien und ermitteln Sie, welche Daten aufgenommen werden sollen, bevor Sie Ihr Datenmodell abschließen. |
| Juni 2021 | [Tableau](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/psql-client-tableau.html) | Video | Erfahren Sie, wie Sie eine Verbindung zu [!UICONTROL Query Service] aus verschiedenen Desktop-Clientanwendungen herstellen, die das `PostgreSQL`-Protokoll unterstützen, und wie Sie `PostgreSQL`-Tools und -Treiber verwenden können, um Abfragen zu verbinden und zu schreiben. |
| Juni 2021 | [Von Adoben definierte Funktionen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/adobe-defined-functions.html) | Video | Erfahren Sie, wie Sie in Adobe Experience Platform mithilfe von Adobe-definierten Funktionen [!UICONTROL Query Service] häufige geschäftsbezogene Aufgaben für Erlebnisereignisdaten ausführen können. |
| Juni 2021 | [Datenforschung](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/explore-data.html) | Video | Erfahren Sie, wie Sie erfasste Daten validieren, Daten in der Vorschau anzeigen und mithilfe von SQL-Funktionen statistische und analytische Eigenschaften von Daten untersuchen können. |
| Juni 2021 | [Query Service – Übersicht](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/understanding-query-service.html) | Video | Erfahren Sie mehr über Query Service in Adobe Experience Platform und wie Sie damit das Kundenverhalten verstehen und effektive Einblicke generieren können. |
| Juni 2021 | [Übersicht über die Benutzeroberfläche von Query Service](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-ui.html) | Video | Erfahren Sie, wie Sie Abfragen schreiben und ausführen, zuvor ausgeführte Abfragen anzeigen und auf Abfragen zugreifen können, die von anderen Benutzern in Ihrer IMS-Organisation in Adobe Experience Platform Query Service gespeichert wurden. |
| Juni 2021 | [Abfrage-API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/query-service-api.html) | Video | Erfahren Sie, wie Sie Abfragen schreiben und ausführen, planen Sie Abfragen und erstellen Sie eine Abfragevorlage mit Adobe Experience Platform [!UICONTROL Query Service API]. |

{style=&quot;table-layout:auto&quot;}

## ![Symbol](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Verwenden Sie Experience Platform, um die Journey eines Kunden in großem Maßstab über Erlebniskanäle hinweg zu orchestrieren, indem Sie die Bedürfnisse jedes Einzelnen in Echtzeit intelligent antizipieren.

* Aktualisiert im Juni 2021 - [Journey Orchestration-Versionshinweise](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=de)

**Weitere Ressourcen für Journey Orchestration**

[Dokumentation](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=en) – [Videoanleitungen](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=de)

## ![Symbol für](/assets/experience_platform_appicon_24.png) Offer Decisioning {#offer-decisioning}

[!UICONTROL Offer Decisioning] ist ein in Adobe Experience Platform integrierter Anwendungsdienst. Verwenden Sie [!UICONTROL Offer Decisioning], um Ihren Kunden über alle Berührungspunkte hinweg zur richtigen Zeit das beste Angebot und Erlebnis zu bieten.

* Aktualisiert im April 2021 - [Offer decisioning-Versionshinweise](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=de#new)

**Weitere Ressourcen zu Offer Decisioning**

[Dokumentation](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new) – [Videoanleitungen](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=de)

## ![Symbol](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Releasedatum: **17. Juni 2021**

* [Neue Funktionen in Adobe Analytics](#aa-features)
* [Neue Funktionen in Customer Journey Analytics](#cust-journey)
* [Fehlerbehebungen in Adobe Analytics](#aa-fixes)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [Analytics-Kurse und -Tutorials](#tutorials-analytics)
* [AppMeasurement](#appm)

### Neue Funktionen in Adobe Analytics {#aa-features}

| Funktion | [Allgemeine Verfügbarkeit](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=de) – geplantes Datum | Beschreibung |
| ----------- | ---------- | ------- |
| K. A. | K. A. |

{style=&quot;table-layout:auto&quot;}

### Neue Funktionen in Customer Journey Analytics {#cust-journey}

| Funktion | [Allgemeine Verfügbarkeit](https://experienceleague.adobe.com/docs/analytics/landing/an-releases.html?lang=en) – geplantes Datum | Beschreibung |
| ----------- | ---------- | ----- |
| K. A. | K. A. |

{style=&quot;table-layout:auto&quot;}

### Fehlerbehebungen in Adobe Analytics {#aa-fixes}

* Es wurde ein Problem behoben, bei dem die falsche Währung im Echtzeitbericht zum Umsatz angezeigt wurde. (AN-254649)
* Die Dokumentation zu [Groß-/Kleinschreibung bei eVar in Berichten](https://experienceleague.adobe.com/docs/analytics/components/dimensions/evar.html) wurde aktualisiert. (AN-246438)
* Die Dokumentation wurde aktualisiert, um [Data Feed-Implementierung](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/create-feed.html) und [hier](https://experienceleague.adobe.com/docs/analytics/export/analytics-data-feed/df-faq.html#BucketOwnerFullControl) besser zu erklären. (AN-219485)
* Es wurden Probleme behoben, die dazu führten, dass einige Daten nicht im Bericht Data Warehouse gesendet wurden (AN-259951). AN-259712; AN-260107; AN-259953)

#### Zusätzliche Fehlerbehebungen in Adobe Analytics oder CJA

AN-246344 AN-250035; AN-250354; AN-252482; AN-254661; AN-254965; AN-255424; AN-256515; AN-257232; AN-257572; AN-257893; AN-258393 AN-259203 AN-259513; AN-259614; AN-259665; AN-259931; AN-260074; AN-260085; AN-260147; AN-260190; AN-260198 AN-260290 AN-260306 (CJA); AN-260508; AN-260625; AN-260793; AN-260861; AN-260938; AN-260945; AN-261149; AN-261317

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt    oder aktualisiert am | Beschreibung |
| ----------- | ---------- | ---------- |
| Browser-Benutzeragenten zeigen für macOS falsche Betriebssystemversionen an | 19. Mai 2021 | Alle gängigen Browser zeigen derzeit für Benutzer von macOS X 11 und höher fälschlicherweise macOS 10 an, wie in der Benutzeragenten-Zeichenfolge des Browsers hinterlegt. Dies wirkt sich auf das Reporting in Adobe Analytics aus, da es den Benutzeragenten verwendet, um Geräteinformationen wie etwa das Betriebssystem zu ermitteln. Diese Ungenauigkeit dient anscheinend dazu, Kompatibilitätsprobleme bei einigen Websites zu vermeiden. Hierfür dient dieses [Bugzilla-Ticket](https://bugs.webkit.org/show_bug.cgi?id=213622&amp;utm_source=convertkit&amp;utm_medium=email&amp;utm_campaign=User+Agent+strings%2C+new+BigQuery+features%2C+custom+Google+Tag+Manager+loader...+%E2%80%93+Simmer+Newsletter+%2311%20-%205873454) als Referenz. Es ist nicht klar, wann oder ob dieses Problem behoben wird.<br>Bei einigen Browsern war zunächst macOS 11 korrekt eingetragen, sodass es möglicherweise Traffic gibt, der diesem Wert entspricht. Aufgrund des unpräzisen Reportings ist das Filtern nach dem Betriebssystem macOS 11 jedoch nicht sinnvoll.<br>Dieses Problem ist von Bedeutung, da Apple ab Safari unter macOS 11 die Ablaufbeschränkungen für ITP-Cookies aktualisiert hat, sodass sie auch für CNAME-Implementierungen gelten (siehe [WebKit-Blogpost](https://webkit.org/blog/11338/cname-cloaking-and-bounce-tracking-defense/)).<br>Vor dieser Aktualisierung galten diese Einschränkungen nur für Client-seitige Cookies, die über JavaScript gesetzt wurden. Diese Ungenauigkeit erschwert die Beurteilung der Menge des Traffics, der unter macOS 11 erfolgt und daher von der ITP-Änderung betroffen ist. Weitere Informationen zu Cookies und Adobe Analytics finden Sie [hier](https://experienceleague.adobe.com/docs/analytics/technotes/cookies/cookies.html?lang=de#cookies). |
| Ende der Nutzungsdauer von drei Analytics-API-Services | 19. Mai 2021 | Am 18. August 2021 erreichten die folgenden Analytics Legacy-API-Services das Ende Ihrer Nutzungsdauer und werden eingestellt. Alle aktuellen Integrationen, die mit diesen Services erstellt wurden, funktionieren seit diesem Tag nicht mehr.<ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Adobe hat ein Dokument [Häufig gestellte Fragen (FAQ) zum Ende der Nutzungsdauer (EOL) der Legacy-API](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) bereitgestellt, das Ihre Fragen beantworten und Anleitungen zum weiteren Vorgehen geben soll. API-Integrationen, die diese Dienste nutzen, können zu den [Analytics-REST-APIs 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) oder den [Analytics-APIs 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) migrieren. Ältere OAuth-Konten können zu einem [Adobe I/O](https://console.adobe.io/home?mv=email#) Analytics-Integrationskonto migriert werden, das für den Zugriff auf sowohl Analytics-APIs 1.4 als auch Analytics-APIs 2.0 verwendet werden kann. |
| Aktualisierung der ISO-Region 2021 | 13. Mai 2021 | Am 21. Mai 2021 wird Adobe die Aktualisierung der ISO-Region 2021 durchführen. Nach dieser Version sollten Sie mit kleineren Aktualisierungen rechnen. |
| Ende der vollständigen Data Sources-Verarbeitung | 12. April 2021 | Adobe plant, die volle Verarbeitung von Datenquellen am 31. Juli 2021 einzustellen. Ab dem 25. März 2021 können keine neuen Importe dieser Art mehr erstellt werden. Verwenden Sie zum Importieren dieses Datentyps die [API zum Massendateneinfügen](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md). |
| Update des Anmeldevorgangs bei [!UICONTROL Report Builder] | 9. April 2021 | Am 14. Januar 2021 wurden durch die Updates des Anmeldevorgangs bei [!UICONTROL Report Builder] die Abhängigkeiten von veralteten Technologien beendet und der Anmeldevorgang mit dem von Experience Cloud abgestimmt. Experience Cloud verwendet Ihre Enterprise ID (E-Mail und Passwort). Um den unterbrechungsfreien Zugriff auf [!UICONTROL Report Builder] sicherzustellen, aktualisieren Sie das Add-in für [!UICONTROL Report Builder] bis zum 22. Juli 2021 auf Version 5.6.47 oder höher. Report Builder Version 5.6.47 und höher unterstützt nur die Experience Cloud-Anmeldung. Single Sign-on wird nicht unterstützt. |
| Änderungen am Daten-Feed und an der IP-Adresse von Data Warehouse | 6. April 2021 | Ab dem 17. Juni wird das System der Daten-Feeds und des Data Warehouse-Versands in Adobe-Rechenzentren neu positioniert, was zu einer Änderung der für Sie sichtbaren externen IP-Adressen führen kann. Adobe empfiehlt sicherzustellen, dass alle IP-CIDR-Blöcke für das Rechenzentrum, von dem Ihre Berichte und Feeds bezogen werden, in Firewalls für die von Ihnen verwalteten Zielsysteme vorhanden sind. [Hier finden Sie eine vollständige Liste der IP-Adressbereiche, die in die Zulassungslisten Ihrer Firewall gesetzt werden müssen](https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html?lang=de#data-collection-and-ftp-ip-address-blocks). |
| Hinweis auf bevorstehende Änderungen im Analytics-Menü | 24. März 2021 | Am 22. April 2021 aktualisierte Adobe die Dropdown-Menüs **[!UICONTROL Komponenten]**, **[!UICONTROL Tools]** und **[!UICONTROL Admin]**, um Leistungsgewinne zu erzielen. Alle diese Seiten stehen weiterhin unter den Links **[!UICONTROL Alle Komponenten]**, **[!UICONTROL Alle Tools]** und **[!UICONTROL Alle Admin]** zur Verfügung. Sie werden nur aus dem Dropdown-Menü entfernt. Hier die Menüelemente, die aus dem Dropdown-Menü entfernt und auf ihre jeweilige Link-Seite platziert werden:<br><br> [!UICONTROL Komponenten]<ul><li>[!UICONTROL Lesezeichen]</li><li>[!UICONTROL Dashboards]</li><li>[!UICONTROL Zielgruppen]</li><li>[!UICONTROL Kalenderereignisse]</li><li>[!UICONTROL Terminierte Berichte]</li><li>[!UICONTROL Berichtseinstellungen]</li></ul>[!UICONTROL -Tools]<ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search&amp;Promote]</li></ul>[!UICONTROL Admin]<ul><li>[!UICONTROL Benutzerverwaltung]</li><li>[!UICONTROL Classification Importer]</li><li>[!UICONTROL Classification Rule Builder]</li><li>[!UICONTROL Data Sources]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL Unternehmenseinstellungen]</li><li>[!UICONTROL Protokolle]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL Code-Manager]</li><li>[!UICONTROL Nach IP ausschließen]</li><li>[!UICONTROL Traffic-Management]</li></ul> |
| Same-as-SiteCatalyst VISTA Processing = ON | 17. März 2021 | Am 17. Juni 2021 werden alle Report Suites dahingehend aktualisiert, dass [!UICONTROL Same-as-SiteCatalyst VISTA Processing] auf „ON“ festgelegt ist. Diese Änderung wirkt sich auf Data Warehouse-Berichte aus, indem die Daten entsprechend den Verarbeitungsregeln verarbeitet werden. Wenden Sie sich bei Fragen oder Unklarheiten an die Adobe-Kundenunterstützung. |
| Optionen zur Landingpage von Reports &amp; Analytics | 19. Februar 2021 | Am 25. März 2021 wurden Optionen zum Festlegen neuer Reports &amp; Analytics-Dashboards sowie anderer Inhalte (wie Ihre Adobe Analytics-Landingpage) entfernt. Wenn Sie zuvor eine Reports &amp; Analytics-Seite als benutzerdefinierte Landingpage festgelegt hatten, funktioniert sie so lange weiter, bis Ihre Landingpage unter [!UICONTROL Benutzervoreinstellungen] geändert wird. |
| Ende von Adobe Data Connectors | 13. Juli 2020 | Adobe [!UICONTROL Data Connectors] basieren auf einer älteren Technologie, die nicht mehr funktionsfähig ist oder unterstützt wird. Ein neuer Standard ist im [Adobe Exchange-Partner-Programm](https://partners.adobe.com/exchangeprogram/experiencecloud) verfügbar. Sie können diesen Standard für jede Integration verwenden, sodass dies weiterhin angeboten und unterstützt werden kann. Das offizielle Enddatum ist der 1. August 2021. [Weitere Infos...](https://experienceleague.adobe.com/docs/analytics/import/dataconnectors/data-connectors-eol.html?lang=de) |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Die neuesten Aktualisierungen zu AppMeasurement-Versionen finden Sie in den Versionshinweisen zu [AppMeasurement für JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=de).

### Neue Analytics-Kurse und -Tutorials {#tutorials-analytics}

Neue Kurse, Tutorial- und Artikel in [!DNL Analytics] und [!UICONTROL Customer Journey Analytics].

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Juni 2021 | [Erste Schritte mit Customer Journey Analytics für Administratoren](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Kurs | Erfahren Sie, wie Sie Customer Journey Analytics einrichten, konfigurieren und verwalten. Lernen Sie einige grundlegende Konzepte kennen, die Ihnen eine Grundlage geben, und gehen Sie dann in weitere Konfigurationsschritte. Der Kurs wird dann mit einigen Empfehlungen zur Migration berechneter Metriken und Segmente von Adobe Analytics nach Customer Journey Analytics abgeschnitten. |
| Juni 2021 | [Konfigurieren von internen Site-Suchberichten](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/configure-internal-site-search-reports.html?lang=en) | Video | Erstellen und konfigurieren Sie Freiformtabellen in Analysis Workspace, um die interne Suchfunktion auf Ihrer Site zu analysieren. |
| Juni 2021 | [Zuordnen von Web SDK-Variablen in Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/map-web-sdk-variables-into-adobe-analytics.html?lang=en) | Video | Erfahren Sie, wie Sie mithilfe von Verarbeitungsregeln Analysevariablen vom Web SDK bis Adobe Analytics zuordnen. |
| Juni 2021 | [Implementieren interner Suchvariablen mit dem Web SDK](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-web-sdk.html?lang=en) | Video | Erfahren Sie, wie Sie mit dem Web SDK Adobe Analytics-Variablen für einen Anwendungsfall des internen Suchbegriff-Trackings implementieren. Anzeigen des Datenflusses von der Seite zum Experience Edge und dann zum Adobe Analytics. |
| Juni 2021 | [Implementieren von internen Suchvariablen mit AppMeasurement](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/implement-internal-search-variables-using-appmeasurement.html?lang=en) | Video | In diesem Video erfahren Sie, wie Sie interne Site-Suchvariablen für Adobe Analytics mithilfe von Experience Platform Data Collection/Launch implementieren, einschließlich Suchbegriff, Anzahl der Ergebnisse und anderer. |
| Juni 2021 | [Definieren Ihrer Geschäftsanforderungen für die interne Site-Suche](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-use-cases/internal-site-search/defining-your-internal-site-search-business-requirements.html?lang=en) | Video | Bei der Entscheidung, die interne Suche auf Ihrer Site zu verfolgen, ist es wichtig, zunächst zu entscheiden, welche Aspekte der Suche Sie verfolgen möchten und welche Maßnahmen aus der Analyse der Ergebnisse ergriffen werden können. Dieses Video führt Sie durch die Dokumentation von Geschäftsanforderungen. |

{style=&quot;table-layout:auto&quot;}

### Analytics-Hilferessourcen

* [Adobe Analytics-Produktdokumentation und Tutorials](https://experienceleague.adobe.com/docs/analytics.html?lang=de)

## ![Symbol](/assets/audience-manager.png) Audience Manager {#aam}

Fehlerbehebungen und Verbesserungen bei Audience Manager.

### Fehlerbehebungen und Verbesserungen {#aam-fixes-and-improvements}

* Es wurde eine Verbesserung für den [Aktivitätsverwendungsbericht](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/administration/activity-usage-reporting.html?lang=en) veröffentlicht, mit dem Sie jetzt Daten überprüfen können, die älter als ein Jahr sind. (AAM-58268)
* Adobe bietet Audience Manager Benutzerzugriffsschlüssel für die Audience Manager Amazon S3-Buckets. Aus Sicherheitsgründen werden die Schlüssel jetzt nach 100 Tagen Inaktivität automatisch deaktiviert. Weitere Informationen finden Sie in der Frage unten auf der Seite in den FAQ [Datenerfassung und Produktintegration](https://experienceleague.adobe.com/docs/audience-manager/user-guide/faqs/faq-data-collection.html?lang=en).

## ![Symbol](/assets/aem.png) Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Experience Manager (AEM). Adobe empfiehlt Kunden mit On-Premise-Implementierungen, die aktuellsten Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

>[!NOTE]
>
>Adobe empfiehlt, die Seite [Experience Manager-Versions-Updates und -Roadmaps](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=de) zu besuchen, um auf dem Laufenden zu bleiben.

### AEM Produktaktualisierungen

* **Experience Manager 6.5.9.0**

   AEM 6.5, Service Pack 9.0 (6.5.9.0 vom 27. Mai 2021) ist ein wichtiges Update, das neue Funktionen, wichtige von Kunden angeforderte Verbesserungen, verbesserte Leistung, Stabilität und Sicherheit umfasst. Dieses Update wurde seit der allgemeinen Verfügbarkeit von AEM 6.5 im April 2019 veröffentlicht.

   * [Versionshinweise](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=de)
   * [Versionsfreigaben von AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html?lang=en)

### AEM Produktversionen

* **Experience Manager as a Cloud Service**

   Neue Funktionen in Experience Manager as a Cloud Service:

   * **Adobe Experience Manager as a Cloud Service Foundation**

      * [Vorabversionskanal](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/prerelease.html?lang=en): Vorschau bevorstehender Funktionen einen Monat vor ihrer Live-Schaltung!
      * [API-Einstellung](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/deprecated-apis.html?lang=en): Eine Liste der neuesten veralteten APIs.
      * [Build Analyzer-Maven-Plug-in für Experience Manager as a Cloud Service SDK](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=en): Aktualisieren Sie Ihre Maven-Projekte auf die neueste Version, die eine veraltete Java™-API-Prüfung und weitere Verbesserungen enthält.
   * **Experience Manager Sites as a Cloud Service**

      * **GraphQL-Endpunkte:** Es ist jetzt möglich, die Experience Manager GraphQL-API für individuelle Experience Manager-Sites-Konfigurationen zu aktivieren und benutzerdefinierte GraphQL-Endpunkte für diese Konfigurationen zu erstellen, indem eine neue GraphQL-Konsolenbenutzeroberfläche verwendet wird. Die Benutzeroberfläche ermöglicht auch die Verwaltung von GraphQL-Endpunkten.
      * **Inhaltsmodelle, erweiterter Datums- und Uhrzeitdatentyp:** Es ist jetzt möglich, den Datums- und Uhrzeittyp so zu konfigurieren, dass nur die Authoring-Daten Datum, Uhrzeit oder Datum und Uhrzeit enthalten.
      * **Inhaltsmodelle, erweiterter Datentyp Tags:**  Der Datentyp Tags kann jetzt konfiguriert werden, um das Authoring von einzelnen oder mehreren Tags zu ermöglichen.
      * **Inhaltsmodelle, neuer Tabulator-Platzhalterdatentyp:** Mit dem neuen Tabulator-Platzhalterdatentyp können Sie Datentypen in Abschnitte gruppieren, die unter Registerkarten im Inhaltsfragment-Editor gerendert werden.
   * **Experience Manager Assets as a Cloud Service**

      Sie können jetzt Inhalte in einer neuen [Vorschaustufe](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/previewing-content.html?lang=en) überprüfen, um das endgültige Erscheinungsbild des Erlebnisses wie auf der Veröffentlichungsstufe zu simulieren. Diese neue Funktion wird vom Experience Manager Sites Managed Publishing-Assistenten aktiviert, mit dem Sie ein Veröffentlichungsziel zwischen [!UICONTROL Publish] oder [!UICONTROL Preview] wählen können. Erlebnisse für [!UICONTROL Vorschau] können dann über eine dedizierte URL aufgerufen werden. Nach der Validierung für [!UICONTROL Vorschau] können Inhalte wie gewohnt von [!UICONTROL Autor] in [!UICONTROL Veröffentlichen] veröffentlicht werden. Die Aktivierung des Diensts [!UICONTROL Vorschau] in der Experience Manager as a Cloud Service-Umgebung erfolgt in den nächsten Wochen schrittweise.

   * **Experience Manager Assets as a Cloud Service**

      Neue Funktionen im Kanal der Vorabversion:

      * Metadatenschemata können direkt auf die Ordnereigenschaften angewendet werden.
      * Mit dem Tool [!UICONTROL Asset-Massenaufnahme] können Sie Metadaten während einer Massenaufnahme hinzufügen.
      * Eine Erweiterung des Benutzererlebnisses zeigt die Anzahl der in einem Ordner vorhandenen Assets an. Für mehr als 1000 Assets in einem Ordner zeigt Experience Manager Assets 1000+ an.

      Neue Funktionen in [!UICONTROL Dynamic Media]:

      * Die intelligente Bildbearbeitungsgeräte-Pixel-Ratio (DPR) und Optimierung der Netzwerkbandbreite ermöglichen es Ihnen, effizient hochwertige Bilder auf Geräten mit hoher Auflösung und eingeschränkter Netzwerkbandbreite bereitzustellen. Siehe [Häufig gestellte Fragen zur intelligenten Bildbearbeitung](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/assets/dynamicmedia/imaging-faq.html?lang=en).




### **AEM Community**

* [One-Stopp-Shop für alle Experience Manager-Blogs](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

* [Leitlinien für die Vorlage einer neuen Experience Manager-Idee](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/guidelines-for-submitting-a-new-experience-manager-aem-idea/td-p/382376)

* [Gipfeltreffen der Adobe 2021 mit Dan Levy](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-sneaks-with-dan-levy/td-p/405865): Einmal jährlich haben alle Mitarbeiter der Adobe, von Ingenieuren und Datenwissenschaftlern bis hin zu UX-Designern und Produktmanagern, die Möglichkeit, innovative Ideen auszutauschen, um die Art und Weise zu entwickeln, wie Marken mit ihren Kunden interagieren. Treten Sie uns bei Adobe Sneaks bei, wo wir die sieben besten Projekte gemeinsam haben und die neuesten Technologien in Bereichen wie KI und Low-Code-Apps nutzen.

### Versionsinformationen zu Experience Manager

Die nachfolgend aufgeführten Seiten umfassen alle Versionshinweise zu Experience Manager:

* [Versionsinformationen für Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=en)
* [Versionshinweise für Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=de)
* [Versionshinweise zum Dienst für die automatische Formularkonversion](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Versionshinweise für Experience Manager 6.5 Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
* [Versionshinweise für Experience Manager 6.4 Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=de)
* [Experience Manager Assets Dynamic Media – Versionshinweise](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=de)
* [Versionshinweise für Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=de)
* [Versionshinweise zum Experience Manager-Desktop-Programm ](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* [Versionshinweise für Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=de)
* [Versionshinweise zu Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=de)

### Neue Experience Manager-Kurse und -Tutorials {#tutorials-aem}

Nachfolgend sind die im vergangenen Monat neu veröffentlichten Videos, Tutorials und Kurse aufgeführt.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Juni 2021 | [Implementieren der Methoden der Benutzeroberfläche](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/implement-interface.html?lang=en) | Artikel | Erfahren Sie, wie Sie die Methoden der Benutzeroberfläche implementieren, um PDFs mit der Document Cloud-REST-API zu erstellen. |
| Juni 2021 | [Benutzeroberfläche &quot;Dienst erstellen&quot;](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-interface.html) | Artikel | Definieren Sie die Methoden in der Benutzeroberfläche, die Sie verfügbar machen möchten. |
| Juni 2021 | [Erstellen einer benutzerdefinierten OSGi-Konfiguration](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/create-doc-cloud-configuration.html?lang=en) | Artikel | Erfahren Sie mehr über die benutzerdefinierte OSGi-Konfiguration, damit Sie Adobe I/O-Projektdetails erfassen können. |
| Juni 2021 | [Erstellen von Content Analyzer](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/get-content-analyzer.html?lang=en) | Artikel | Erfahren Sie, wie Sie den JSON-Teil erstellen, der Informationen zu den Eingabeparametern für den REST-Aufruf &quot;Create PDF&quot;enthält. |
| Juni 2021 | [Erstellen eines benutzerdefinierten Prozessschritts](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-cloud-sdk/custom-process-step.html?lang=en) | Artikel | Zeigen Sie den vollständigen Code des benutzerdefinierten Prozessschritts an, der die nativen Dateien konvertiert und durch die konvertierten PDFs ersetzt. Dieser benutzerdefinierte Schritt sucht nach allen Anlagen unter dem Ordnernamen, der als Prozessargument im Workflow bereitgestellt wird. In diesem benutzerdefinierten Prozessschritt werden die Methoden des benutzerdefinierten `DocumentCloudSDKService` zum Erstellen von PDFs verwendet. |
| Juni 2021 | [GraphQL - Beständige Abfragen](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/video-series/graphql-persisted-queries.html?lang=en) | Video | Erfahren Sie, wie Sie persistente Abfragen in Experience Manager aktivieren, erstellen, aktualisieren und ausführen. |
| Juni 2021 | [Erstellen Ihres ersten Servlets in AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-servlet.html?lang=en) | Artikel | Erstellen Sie Ihr erstes Sling-Servlet, damit Sie Daten mit einer Formularvorlage zusammenführen können. |
| Juni 2021 | [Erstellen Ihres ersten OSGi-Dienstes mit Experience Manager forms](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/creating-your-first-osgi-bundle/create-osgi-service.html?lang=en) | Artikel | Erstellen Sie Ihren ersten OSGi-Dienst mit AEM Forms, damit Sie PDF generieren können, indem Sie Daten mit einer Vorlage zusammenführen. |

{style=&quot;table-layout:auto&quot;}

### Andere Hilferessourcen für Experience Manager

* [Handbücher für Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=en)
* [Experience Manager 6.5 – Training und Support, Startseite](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=de)
* [Experience Manager 6.4 – Training und Support, Startseite](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=de)
* [Experience Manager 6.3 – Training und Support, Startseite](https://helpx.adobe.com/de/support/experience-manager/6-3.html)
* [Experience Manager 6.2 – Training und Support, Startseite](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=de#previous-updates)
* [Ältere Versionen der Dokumentation zu Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Cloud Manager-Benutzerhandbuch](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=de)
* [Startseite der Hilfe zu Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=de)
* [Experience Manager-Dokumentation: Neueste Aktualisierungen](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=de#aem-as-a-cloud-service)

## ![Symbol](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Aktuelle Produktversionen

Erfahren Sie mehr über die aktuellsten veröffentlichten Funktionen, Verbesserungen und Fehlerbehebungen:

* **Neue Adobe Campaign v8**  mit wesentlichen Verbesserungen in den Bereichen Infrastruktur, Sicherheit, Zustellbarkeit und Überwachung. Durch die Verwendung von [!DNL Snowflake], einer Cloud-Datenbanktechnologie, verbessert Adobe Campaign erheblich den Umfang und die Geschwindigkeit. So kann eine größere Anzahl von Kundenprofilen sowie deutlich höhere Bereitstellungsraten und Transaktionen pro Stunde verwaltet werden. Weitere Informationen finden Sie in der [Campaign v8-Dokumentation](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html).

* **Adobe Campaign Classic Version** 21.1.3: Weitere Informationen finden Sie in den  [Versionshinweisen zu Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html).

* **Adobe Campaign Standard-Version 21.2**: Weitere Informationen finden Sie in den  [Versionshinweisen zu Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html).

### Neue [!UICONTROL Campaign] Kurse und Tutorials {#tutorials-campaign}

| Veröffentlicht | Name | Lösung | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Juni 2021 | [Integration von Campaign Standard mit Analytics zur Optimierung des E-Mail-Marketings](https://experienceleague.adobe.com/?lang=de#dashboard/learning) | Campaign Standard | (Kurs) Erfahren Sie, wie Sie Campaign Standard mit Adobe Analytics integrieren und Ihre E-Mail-Marketing-Strategien mithilfe von Echtzeitdaten optimieren können. In diesem Kurs erfahren Sie, wie Sie einen Campaign Standard-Bericht in Adobe Analytics erstellen. Anschließend erfahren Sie, wie Sie mit Experience Cloud Triggers und Platform Launch Marketing- und Transaktionsnachrichten basierend auf der Kundenaktivität konfigurieren. |
| Juni 2021 | [Tutorials zu Adobe Campaign v8](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/overview.html) | Campaign v8 | Dieses Benutzerhandbuch enthält Videos und Tutorials zu den zahlreichen Funktionen von Adobe Campaign v8. |
| Juni 2021 | [Erstellen und Entwerfen eines E-Mail-Versands](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/content-creation/email/create-and-design-email-deliveries.html) | Campaign v8 | (Video) Verstehen Sie den Prozess der Erstellung eines E-Mail-Versands und erfahren Sie, wie Sie E-Mail-Inhalte erstellen und personalisieren. |
| Juni 2021 | [Entwerfen von E-Mails für die Zustellbarkeit](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/email/design-emails-for-deliverability.html) | Campaign v8 | (Video) Erfahren Sie, wie Sie Best Practices zur Zustellbarkeit auf Ihre E-Mail-Sendungen anwenden. |
| Juni 2021 | [Ermüdung mithilfe von Typologieregeln verwalten](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/typology-rules-for-fatigue-management.html) | Campaign v8 | (Video) Erfahren Sie, wie Sie die Ermüdungsverwaltung mithilfe von Typologieregeln implementieren. |
| Juni 2021 | [Einrichten der Ermüdungsverwaltung mithilfe von Filtern](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/fatigue-management/fatigue-management-using-filters.html) | Campaign Standard | (Video) Erfahren Sie, wie Sie die Ermüdungsverwaltung in Adobe Campaign mithilfe von Filtern implementieren. |

{style=&quot;table-layout:auto&quot;}

### Hilferessourcen für Campaign

* Adobe Campaign Standard: [Hilfe-Center](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=en) – [Anleitungsvideos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=de) – [Versionsplanung](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=de) – [Neueste Aktualisierungen der Dokumentation](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=de)
* Adobe Campaign Classic: [Hilfe-Center](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=de) – [Versionshinweise](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=en) – [Anleitungsvideos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=de) – [Neueste Aktualisierungen der Dokumentation](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=de)
* Control Panel von Adobe Campaign: [Dokumentation](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en) – [Versionshinweise](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en)    – Anleitungsvideos für [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=de)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=de)

## ![Symbol](/assets/advertising-cloud.png) Advertising {#adcloud}

Versionshinweise für [!DNL Adobe Advertising].

* [Neue Funktionen in Advertising DSP](#adcloud-dsp)
* [Neue Funktionen in Advertising Search](#adcloud-search)

### Neue Funktionen in [!DNL Advertising DSP] {#adcloud-dsp}

Zuletzt aktualisiert: **10. Juni 2021 für die Version vom 16. Juni**

| Funktion | Beschreibung |
| -----------| ---------- |
| Kampagnenverwaltung | (Version vom 16. Juni) Die Prognose ist für standardmäßige Platzierungen mit Platzierungsebenen-Geschwindigkeit und Budgets verfügbar. |

{style=&quot;table-layout:auto&quot;}

### Neue Funktionen in [!DNL Advertising Search] {#adcloud-search}

Zuletzt aktualisiert: **19. Mai 2021, für die Version vom 18. Mai**

| Funktion | Beschreibung |
| -----------| ---------- |
| [!UICONTROL Benachrichtigungszentrum – Beta-Version] | Die [!UICONTROL Beta-Version des Benachrichtigungszentrums] steht allen Benutzern zur Verfügung. Abonnieren Sie damit E-Mail- und Web-Benachrichtigungen zu Fehlern bei der Kontoauthentifizierung, ausgelösten benutzerdefinierten Warnungen und abgeschlossenen von Ihnen generierten [!UICONTROL Werbungseinblicke].<br>Sie können Ihre Benachrichtigungen in folgenden Bereichen anzeigen:<ul><li>Im Bedienfeld [!UICONTROL Benachrichtigungen], das über den Link „Benachrichtigungen“ oben rechts auf einer beliebigen Seite geöffnet wird.</li><li>Im [!UICONTROL Benachrichtigungszentrum] unter [!UICONTROL Einblicke und Berichte > Benachrichtigungszentrum – Beta].</li></ul><br><b>Hinweis:</b> Aufgrund von Verbesserungen bei der Speicherung von Benachrichtigungen wurden alle vorhandenen Benachrichtigungen gelöscht. |

{style=&quot;table-layout:auto&quot;}

## ![Symbol](/assets/magento.png) [!DNL Magento] {#magento}

Die neuesten Versionsinformationen finden Sie in den Magento Commerce- und Open Source-[Versionshinweisen](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html).

## ![Symbol](/assets/target.png)[!DNL Target] {#target}

Die aktuellen Versionsinformationen finden Sie in den [[!DNL Target] Versionshinweisen](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=de).

## ![Symbol](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] ist eine Komplettanwendung für das Lead-Management. B2B-Marketer können damit Kundenerlebnisse transformieren, indem sie in allen Phasen komplexer Customer Journeys Interaktionen ermöglichen.

### Aktualisierungen von Core Marketo Engage

Aktuelle Informationen zum Veröffentlichungsplan und die Versionshinweise finden Sie unter [!DNL Marketo Engage] [Veröffentlichungsplan](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) .

## ![Symbol](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe [!DNL Workfront] ist eine einheitliche Anwendung für die Verwaltung von Ideen, die Erstellung von Inhalten, die Verwaltung komplexer Prozesse und die bestmögliche Arbeit.

Auf der Seite [[!DNL Workfront] releases](https://one.workfront.com/s/product-releases) finden Sie eine Zusammenfassung der neuesten Informationen zu allen Produkten.

## ![Symbol](/assets/document-cloud-24.png) Document Cloud {#doc-cloud}

Neue Videos, Tutorials oder Kurse, die für Adobe Document Cloud veröffentlicht wurden.

### Document Cloud-Kurse und -Tutorials {#tutorials-doc-cloud}

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Juni 2021 | [Adobe Acrobat für Google Drive](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/acrobatandgoogle.html) | Video | Erhalten Sie Zugriff auf zeitsparende PDF-Tools und e-Signatur-Workflows direkt in der Google Drive-App. |

{style=&quot;table-layout:auto&quot;}

Hilfe zu Document Cloud erhalten Sie über:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=de)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=de)
* [Document Cloud: Lernen und Support](https://helpx.adobe.com/de/support/document-cloud.html)

## ![Symbol](/assets/creative-cloud-24.png) Creative Cloud Enterprise {#creative-cloud}

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| Juni 2021 | [Testen Sie Ihre Hand am Fresco auf dem iPad (und iPhone).](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/frescoworkshop.html) | Video | In diesem 15-minütigen Handwerksshop erleben Sie mit Adobe Fresco eine ganz neue Welt des digitalen Zeichens und Zeichens. Schnell lernen Sie, mit Ebenen und Schnittmasken zu arbeiten, um Farbe und Texturen an eine Grundform anzupassen. |
| Juni 2021 | [Dekodieren der Alphabet-Suppe von Grafikformaten](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/alphabetsoup.html) | Video | PG-, PNG-, SVG-, GIF- und EPS-Dateien werden häufig im Design verwendet, einige für Web-Seiten, andere für Präsentationen, Publikationen und kreative Projekte. Aber... was bedeuten sie, und was sollten Sie wählen? In diesem 15-minütigen Workshop erfahren Sie mehr. |

{style=&quot;table-layout:auto&quot;}

Unter [Creative Cloud für Unternehmen – Tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=de) finden Sie die neuesten Tutorials.
