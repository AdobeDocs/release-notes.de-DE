---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 9ed727b23cbc90965f44c4bb914728bbc2394d6b

---


# Versionshinweise zu Adobe Experience Cloud - März 2020

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

>[!NOTE]
>Abonnieren Sie [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bald verfügbare Versionen benachrichtigt zu werden. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Veröffentlichungsdatum: März 2020**

(Die spezifischen Produktveröffentlichungstermine können variieren.)

* [Systemstatus von Adobe](#status)
* [Benutzeroberfläche und Core Services von Experience Cloud](#ecloud)  (Aktualisierung: **26. Februar 2020**)
* [Experience Platform](#platform)
* [Mobile Services und Mobile SDKs](#mobile)
* [!DNL Analytics](#analytics) (Aktualisierung: 21. Februar 2020)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (Links zur Lösungshilfe)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (Links zur Lösungshilfe)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)

Suchen Sie nach der Hilfeseite? Siehe die [Adobe Experience Cloud-Dokumentation](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Systemstatus von Adobe {#status}

[!UICONTROL Der Adobe-Systemstatus] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe Cloud-Produkten und -Diensten. Weiter Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/).

**Neuigkeiten**

* Mit Ihrer Adobe ID können Sie Benachrichtigungen zu Ereignissen basierend auf Ihren Voreinstellungen zu Produkten, Regionen, Ereignissen und Sprachen abonnieren. Benutzer, die ihre Abonnementvoreinstellungen konfigurieren, werden über relevante Produkt- und Wartungsereignisse benachrichtigt, wenn sie geöffnet, aktualisiert oder geschlossen werden. Weitere Informationen erhalten Sie unter [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Ab heute verfügbare neue Funktionen und Verbesserungen**

| Funktion | Beschreibung |
| -----------| ---------- |
| Schnellere Kenntnis von Produktereignissen | <ul><li>Informieren Sie sich 30 Tage im Voraus über bevorstehende Wartungsarbeiten. Diese Funktion bietet mehr Vorlaufzeit, um die potenziellen Auswirkungen auf Ihren Geschäftsbetrieb abzuschätzen, und ermöglicht Ihnen bei Bedarf die Implementierung eines Ausgleichsplans.</li><li>Erweiterte Benachrichtigungen sind auf Web-/Mobil-/Tablet-Oberflächen und über E-Mail-Benachrichtigungen verfügbar.</li></ul> |
| Personalisieren Sie Ihr Erlebnis auf Grundlage der bevorzugten Sprache. | <ul><li>Wählen Sie eine bevorzugte Sprache für E-Mail-Benachrichtigungen aus. Die Funktion für die Abonnement-Selbstregistrierung ist jetzt in neunzehn Sprachen verfügbar.</li></ul> |
| Verbesserte Benutzererfahrung bei Abonnements und Benachrichtigungen | <ul><li>Geben Sie für alle Produkte, für die Sie ein Abonnement abschließen möchten, die Voreinstellungen für Region und Ereignis mit nur einem Klick an.</li><li>Lassen Sie sich benachrichtigen, wenn _potenzielle_ Probleme in _Kleiner_ oder _Größer_ eingestuft werden.</li><li>Die Browserseite wird automatisch aktualisiert, wenn ein Produkt- oder Ereignisstatus aktualisiert wird.</li></ul> |

## Benutzeroberfläche und Core Services von Experience Cloud {#ecloud}

Aktualisierung der Version: **26. Februar 2016**

Neue Funktionen und Fehlerkorrekturen in der Benutzeroberfläche von Experience Cloud, einschließlich Verwaltung und Core Services (Kundenattribute, Zielgruppen, Auslöser, Cookies usw.).

| Funktion | Beschreibung |
| -----------| ---------- |
| Admin-Tool – Benutzerdetails anzeigen | Administratoren können im neuen Admin-Tool eine sortierbare und filterbare Liste aller Experience Cloud-Benutzer und deren Details anzeigen. Zu den Benutzerdetails zählen der Produktzugriff, die Rollen und die zuletzt aufgerufenen Informationen. Weitere Informationen finden Sie in der Hilfe zum [Experience Cloud-Admin-Tool](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html). |

### Einheitliche Produktdomäne

Adobe aktualisiert die Domäne und die Kopfzeile der Benutzeroberfläche, um Ihre Nutzererfahrung in allen Experience Cloud-Anwendungen zu vereinheitlichen und zu verbessern. Diese simplen Aktualisierungen sollen die Benutzerfreundlichkeit vereinfachen und verbessern. Ihre aktuellen Workflows werden dadurch nicht geändert.

Zu den Aktualisierungen gehören:

* Neue URLs für Lösungen: `experience.adobe.com/<application name>`:
   * Dieses URL-Muster wird schließlich von allen Produkten übernommen. Im Laufe des Monats werden neue URLs hinzugefügt werden.
   * Browserunterstützung: Unterstützte Browser sind [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] und [!DNL Opera] (neueste Versionen). **Hinweis:** Obwohl die Experience Cloud-Oberfläche diese Browser unterstützt, unterstützen einzelne Lösungen möglicherweise nicht alle Browser. ([Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) unterstützt beispielsweise nicht [!DNL Opera] und [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) unterstützt nicht [!DNL Safari].)
   * (Nur [!DNL Safari]) Die Domänenänderung kann bei [!DNL Safari] zu Cookie-Problemen führen. Wenn Sie in den Datenschutzvoreinstellungen von [!DNL Safari] die Option _Prevent cross-site tracking_ (Website-übergreifendes Tracking verhindern) deaktivieren, werden domänenübergreifende Cookies (und alle Site-übergreifenden Ereignisse) aktiviert, sodass Experience Cloud in dieser neuen Domäne funktionieren kann.
* Einfacherer Wechsel zwischen Ihren Organisationen oder zu einer anderen Anwendung.
* Verbesserte Produkthilfe: [!UICONTROL Experience League] ist in das Produkt integriert, sodass bei einer Hilfesuche auch Ergebnisse aus Community-Foren und Videos berücksichtigt werden. Diese Änderung vereinfacht den Zugriff auf weitere Inhalte und hilft Ihnen, Experience Cloud optimal zu nutzen. Zusätzlich können Sie unter **[!UICONTROL Hilfe]** > **[!UICONTROL Feedback]** Probleme melden oder Ihre Ideen mit Adobe teilen.
* Verbesserte Benachrichtigungen: Das Dropdown-Menü [!UICONTROL Benachrichtigungen] enthält jetzt zwei Registerkarten: eine für Ihre eigenen Produktbenachrichtigungen und eine für globale Produktankündigungen.

**Hinweis:** Die [!UICONTROL Feed]-Seite wird im Januar 2020 eingestellt. Innerhalb des Produkts finden Sie eine Benachrichtigung zur Einstellung.

Die Produktdokumentation finden Sie auf der [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)-Seite.

## Experience Platform {#platform}

Versionshinweise für Experience Platform, Experience Platform Launch, Identity Service und Sicherheitsbulletins.

* [Experience Platform – Versionshinweise](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/security.html)  (Alle Adobe-Produkte)

### Experience Platform Launch {#launch}

Versionshinweise und die Produktdokumentation finden Sie unter [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## Mobile Services und Mobile SDKs {#mobile}

Mobile Inhalte

## [!DNL Analytics] {#analytics}

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics](#aa-features)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [AppMeasurement](#appm) (aktualisiert am 21. Februar 2020)

Die Produktdokumentation finden Sie auf der [Startseite der Adobe Analytics-Hilfe](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics {#aa-features}

* **Mehrere Report Suites im Analysis Workspace**: Sie können jetzt Daten aus mehreren Report Suites in ein einzelnes Analysis Workspace-Projekt einbeziehen, um sie nebeneinander anzuzeigen. Ab dem 12. März 2020 wird die Funktion im Laufe einiger Wochen für alle Kunden eingeführt. [Mehr Info...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Zielgruppenoptimierung** in Experience Cloud: Mit dieser Funktion können Sie Segmente innerhalb von 8 Stunden in der Experience Cloud veröffentlichen (anstelle der vorherigen 48-Stunden-Verarbeitungszeit). [Mehr Info...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)

#### Fehlerbehebungen

* Es wurde ein Fehler in Reports &amp; Analysen behoben, der verhinderte, dass Kunden .xls-Berichte herunterladen konnten.(AN-206541, AN-204008)
* Mit der Einführung einer neuen Shell wurden mehrere Kundenprobleme beim Wechsel von Experience Cloud-Organisationen behoben.(AN-200844, AN-186920)

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt  oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Einstellung &quot;EOL of Conversion Level&quot; | 3. März 2020 | Die nicht funktionierende [Konvertierungsstufe](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) unter Admin Tools > Report Suites > Allgemeine Kontoeinstellungen wird am 12. März 2020 aus der Benutzeroberfläche entfernt. |
| EOL of Dashboard Archive | 3. März 2020 | Die Einstellung &quot;Archiv anzeigen&quot;unter &quot;Dashboards verwalten&quot;in Reports &amp; Analysen ist ab dem 12. März 2020 nicht mehr verfügbar. |
| Neue Adobe Analytics-Domäne | 18. Dezember 2019 | Am 16. Januar 2020 begann Adobe Analytics mit der Umstellung auf eine neue Domäne – `https://experience.adobe.com/analytics.`<br>**Hinweis:** Diese Änderung gilt für alle Benutzer, die mit ihrer Adobe ID oder Enterprise ID auf Analytics zugreifen.<ul><li>Diese Änderung kann zu Problemen mit Cookies führen, wenn Analytics in Safari geladen wird. Wenn Sie in den Datenschutzvoreinstellungen von Safari die Option _Prevent cross-site tracking_ (Website-übergreifendes Tracking verhindern) deaktivieren, werden domänenübergreifende Cookies (und alle Site-übergreifenden Ereignisse) aktiviert, sodass Analytics in dieser neuen Adobe Experience Cloud-Domäne funktionieren kann. Sie können problemlos andere Browser verwenden, da dies nur Safari-Benutzer betrifft.</li><li>Die Domänenänderung kann dazu führen, dass [!UICONTROL Activity Map] bei einigen Kunden [in bestimmten Fällen](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html) nicht mehr funktioniert.</li></ul> |
| End of Life - veraltete Analytics-APIs | 9. Januar 2020 | Im November 2020 werden die folgenden Legacy-API-Dienste von Analytics eingestellt. Aktuelle Integrationen, die mit diesen Diensten erstellt wurden, funktionieren dann nicht mehr. <ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Wir haben [FAQ zu Legacy API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) bereitgestellt, die Ihnen bei der Beantwortung Ihrer Fragen helfen und Anleitungen zum weiteren Vorgehen geben sollen. API-Integrationen, die diese Dienste nutzen, können zu den [Analytics-REST-APIs 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) oder den [Analytics-APIs 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) migrieren. Ältere OAuth-Konten können zu einem [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-Integrationskonto migrieren, das für den Zugriff auf sowohl Analytics-APIs 1.4 als auch Analytics-APIs 2.0 verwendet werden kann. |
| Option **[!UICONTROL Archiv anzeigen]** wird eingestellt | 30. Oktober 2019 | Die Option **[!UICONTROL Archiv anzeigen]** im Dashboard-Manager (**[!UICONTROL Komponenten > Dashboards]**) wird im Januar 2020 eingestellt. |
| Option **[!UICONTROL IP-Anmeldebeschränkungen erzwingen]** wird eingestellt | 30. Oktober 2019 | Die IP-Whitelist-Funktionalität (**[!UICONTROL IP-Anmeldebeschränkungen erzwingen]**) unter **[!UICONTROL Admin > Unternehmenseinstellungen > Sicherheit]** wird im Januar 2020 eingestellt. |
| Ende der Unterstützung für TLS 1.1 | 3. Oktober 2019 | Ab dem 31. März 2020 unterstützt Adobe Analytics TLS 1.1 nicht mehr. Diese Änderung ist Teil unserer laufenden Bemühungen, höchstmögliche Sicherheit von Kundendaten zu gewährleisten. |
| FTP-Broker in San Jose endet für London und Singapur | Juli 2020 | Für Kunden in London und Singapur wird die Datenvermittlung zwischen den beiden Städten und dem Rechenzentrum in San Jose ([ftp.omniture.com](ftp://ftp.omniture.com/)) nicht mehr unterstützt.<br/><ul><li>Für London verwenden Sie [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Für Singapur verwenden Sie [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Bevorstehende Änderung bezüglich des Felds `createDate` für Analytics-Benutzer | 30. August 2019 | Im Oktober oder November 2019 wurde das Feld `createDate` für Analytics-Benutzer von der US Pacific Time auf einen korrekt formatierten Datums-/Uhrzeitwert mit Zeitzoneninformationen aktualisiert.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Siehe [Versionshinweise zu AppMeasurement für JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Version 2.19.0 wurde am 21. Februar 2020 veröffentlicht.

## Audience Manager {#aam}

Korrekturen und Funktionen, die Audience Manager hinzugefügt wurden.

### Neue in Audience Manager verfügbare Funktionen, Verbesserungen und Fehlerbehebungen {#aam-features}

| Funktion | Beschreibung |
|----|----|
|  |  |
|  |  |

### Fehlerbehebungen und Verbesserungen {#aam-fixes-and-improvements}

Fehlerbehebungen für AAM.

## Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Zusätzliche Ressourcen

* [AEM als Cloud-Dienst](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager-Benutzerhandbuch](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Ältere Versionen der AEM-Dokumentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Startseite der Hilfe zu Dynamic Media Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Versionshinweise zu Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre-Versionshinweise](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Zusätzliche Ressourcen

* Adobe Campaign Standard: [Dokumentation](https://helpx.adobe.com/support/campaign/standard.html) – [Versionshinweise](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)     – [Versionsplanung](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Dokumentation](https://helpx.adobe.com/support/campaign/classic.html) – [Versionshinweise](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Control Panel von Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Aktualisiert: 10. Februar 2020, für die Version vom 8. Februar

## [!DNL Magento] {#magento}

Magento-Versionshinweise finden Sie unter:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] ist eine Komplettlösung für das Lead-Management. B2B-Marketer können damit Kundenerlebnisse transformieren, indem sie in allen Phasen komplexer Customer Journeys Interaktionen ermöglichen.

### Aktualisierungen von Core Marketo Engage

Versionsdatum: 21. Februar 2020

* **Microsoft Dynamics _Inhaber in Microsoft ändern_ Flow-Aktion**: Lead- oder Kontaktinhaber direkt in Marketo Engage ändern.
* **Verbesserungen bei API-Aufrufen:**
   * APIs für die Benutzerverwaltung
   * APIs für benutzerdefiniertes Objektschema
   * APIs für Umleitungsregeln auf der Landingpage
* **Caching des Formular-Deskriptors:** Verbesserungen für Landingpages und Formulare.

Weitere Informationen finden Sie in den [!DNL Marketo]-Versionshinweisen für [Februar 2020](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720).

### Bevorstehende Funktionen

Die folgenden Funktionen werden im Laufe dieses Quartals veröffentlicht:

| Funktion | Beschreibung |
|------|---------|
| [!DNL Bizible] | <ul><li>Neue kontobasierte Segmentierung</li><li>Speichern von Dashboard-spezifischen Filtern</li><li>Export von Bizible Dashboards als PDF</li></ul> |
| Sales Connect | Aktualisierungen/Verbesserungen für Compose Window und Command Center |

### Ankündigungen

**** Marketing Engage Success Center: Start im Februar 2020. Das Success Center ist ein produktinternes Hilfesystem, mit dem Sie u. a. Produktdokumente und die Community durchsuchen, Anleitungen aufrufen und auf Adoptionsinhalte zugreifen können. Hinweis: Diese Funktion wird als Betaversion in ANZ gestartet und später in diesem Quartal in Nordamerika eingeführt.

### Veraltete und entfernte Funktionen

* **Asset-API-Parameter „_method“:** Ab September 2020 wird „_method“ nicht mehr vom Asset-API-Endpunkte akzeptiert, um Abfrageparameter zu einem POST-Textkörper weiterzuleiten und URI-Längenbeschränkungen zu umgehen.
* **Einstellung der Unterstützung für Internet Explorer:** Ab der Juli-Version vom 31. Juli 2020 wird die Benutzeroberfläche von Marketo Engage in Internet Explorer nicht mehr unterstützt.

Eine Sammlung historischer Versionshinweisen finden Sie unter [Marketo-Versionshinweise](https://docs.marketo.com/x/CgA6Ag).