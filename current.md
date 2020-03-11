---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 6fa8ddb48734849f15490dce814b1fd8763051d3

---


# Vorzeitiger Zugriff - Versionshinweise zu Adobe Experience Cloud - März 2020

![Banner](/assets/experience-cloud-banner-3.png)

Neue Funktionen und Fehlerbehebungen in [!DNL Adobe Experience Cloud].

>[!IMPORTANT]
>Diese Seite enthält Inhalte einer Vorabversion und kann vor der geplanten Veröffentlichung der Version geändert werden.

>[!NOTE]
>Abonnieren Sie [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bald verfügbare Versionen benachrichtigt zu werden. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Veröffentlichungsdatum: März 2020**

Neueste Aktualisierung: 11. März 2020

* [Systemstatus von Adobe](#status)
* [Benutzeroberfläche und Core Services von Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (Links zur Lösungshilfe)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (Links zur Lösungshilfe)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [Neue Dokumentation und Tutorials](#selfhelp)

Suchen Sie nach der Hilfeseite? Siehe die [Adobe Experience Cloud-Dokumentation](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

(Das Datum der Produktversion kann unterschiedlich sein.)

## ![Symbol](/assets/adobe.png) Adobe-Systemstatus {#status}

[!UICONTROL Der Adobe-Systemstatus] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe Cloud-Produkten und -Diensten. Weiter Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/).

**Neuigkeiten**

* Mit Ihrer Adobe-ID können Sie Ereignis-Benachrichtigungen mit größerer Granularität bis hin zum Produktangebot und Add-On-Stufe abonnieren. Suchen Sie nach dieser neuen Funktion in Experience Cloud-Produkten, bei der im Self-Abonnement-Prozess Unterangebote für die Produkte und Dienste angezeigt werden, für die Sie ein Abonnement abschließen möchten. Diese Verbesserung sollte die Anzahl der Benachrichtigungen, die Sie erhalten, erheblich verringern und die Benachrichtigungen für die von Ihnen verwendeten Produkte und Funktionen relevanter machen.  Weitere Informationen erhalten Sie unter [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Ab heute verfügbare neue Funktionen und Verbesserungen**

| Funktion | Beschreibung |
| -----------| ---------- |
| Personalisiertes Self-Abonnement nach Produkt-Unterangeboten | <ul><li>Self-Abonnement nach Produktangebot oder Add-ons für Experience Cloud-Produkte.</li><li>Benachrichtigungen über Ereignis sind für Ihre Produkt- und Produktangebotseinstellungen relevant.</li></ul> |
| Personalisiertes Erlebnis basierend auf Benutzereinstellungen | <ul><li>Zeitzonenvoreinstellungen werden je nach Browsereinstellung in E-Mail-Benachrichtigungen verwendet.</li><li>E-Mail-Bestätigung beim Abonnieren/Abmelden mit allen ausgewählten Voreinstellungen gesendet.</li></ul> |
| Besserer Versand von Ereignis-Nachrichten | <ul><li>Der Ereignis-Verlauf wurde nach chronologischen Ereignis-Aktualisierungen sortiert.</li><li>Zeitstempel für die Auflösung des Ereignisses, die zu &quot;Größer/Kleiner&quot;hinzugefügt wurden, wurden geschlossen.</li></ul> |

## ![Icon](/assets/experience-cloud.png) Experience Cloud-Benutzeroberfläche und Hauptdienste {#ecloud}

Neue Funktionen und Fehlerkorrekturen in der Benutzeroberfläche von Experience Cloud, einschließlich Verwaltung und Core Services (Kundenattribute, Zielgruppen, Auslöser, Cookies usw.).

| Funktion | Releasedatum | Beschreibung |
| ----|----|---- |
| Admin-Tool – Benutzerdetails anzeigen | 26. Februar 2020 | Administratoren können im neuen Admin-Tool eine sortierbare und filterbare Liste aller Experience Cloud-Benutzer und deren Details anzeigen. Zu den Benutzerdetails zählen der Produktzugriff, die Rollen und die zuletzt aufgerufenen Informationen. Weitere Informationen finden Sie in der Hilfe zum [Experience Cloud-Admin-Tool](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html). |

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

**Hinweis:** Die [!UICONTROL Feed] -Seite wurde im Januar 2020 eingestellt. Innerhalb des Produkts finden Sie eine Benachrichtigung zur Einstellung.

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) help.

## ![Symbol](/assets/platform.png) -Erlebnisplattform {#platform}

Release notes for the [!UICONTROL Experience Platform,] [!UICONTROL Experience Platform Launch,] [!UICONTROL Identity Service,] and security bulletins.

* [Experience Platform – Versionshinweise](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Reisebegleitung](#journey)
* [Mobile Services und Mobile SDKs](#mobile)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/security.html)   (Alle Adobe-Produkte)

### Experience Platform Launch {#launch}

Versionshinweise und die Produktdokumentation finden Sie unter [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

### Reisebegleitung {#journey}

Mit der Adobe Experience Platform können Sie maßgeschneiderte Kundenreisen für erfahrene Kanal organisieren, indem Sie die Bedürfnisse jedes Einzelnen in Echtzeit vorhersehen, egal, wohin die Reise führt.

Version Q1 wurde veröffentlicht. [Mehr dazu](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

**Zusätzliche Ressourcen**

[Dokumentation](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [Versionshinweise](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [Anleitungen](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services und Mobile SDKs {#mobile}

**iOS v4.19.1**

* Allgemein - Es wurde ein möglicher Absturz behoben, wenn [!UICONTROL Swift] -enums in Kontextdaten für Verfolgungsaufrufe enthalten sind.
* [!DNL Target] - [!DNL Target] Die Sitzungs-ID wird nun als Kontextdatenparameter `a.target.sessionId` im internen Treffer von [!UICONTROL Analytics für die Zielgruppe] hinzugefügt, der an Adobe Analytics gesendet wird.

**Android v4.18.1**

* [!DNL Target] - [!DNL Target] Die Sitzungs-ID wird jetzt als Kontextdatenparameter &quot;a.Zielgruppe.sessionId&quot;im internen Treffer [!UICONTROL von Analytics für Zielgruppen] hinzugefügt, der an Adobe Analytics gesendet wird.

## ![Symbol](/assets/analytics.png) [!DNL Analytics] {#analytics}

Releasedatum: **12. März 2020**

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics](#aa-features)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [AppMeasurement](#appm)

Die Produktdokumentation finden Sie auf der [Startseite der Adobe Analytics-Hilfe](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics {#aa-features}

* **Mehrere Report Suites im Arbeitsbereich[!UICONTROL für ]**Analysen: Sie können jetzt Daten aus mehreren Report Suites in ein einzelnes[!UICONTROL Analyse Workspace]-Projekt zur Ansicht in nebeneinander liegenden Bereichen einführen.[Mehr Info...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Optimierung** der Experience Cloud-Audience: Mit dieser Funktion können Sie Segmente innerhalb von 8 Stunden in der Experience Cloud veröffentlichen (anstelle der vorherigen 48-Stunden-Verarbeitungszeit). [Mehr Info...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analyse Workspace - Schulungslehrvorlage**: Diese neue Standardvorlage führt Sie durch die gängige Terminologie und Schritte zum Aufbau Ihrer ersten Analyse in Workspace. Es ist als Standardvorlage im Modal &quot; [!UICONTROL Neues Projekt] &quot;verfügbar und ersetzt das Beispielprojekt, das heute für neue Benutzer besteht, die keine anderen Projekte in ihrer Liste haben.

#### Fehlerbehebungen

* Es wurde ein Problem in [!UICONTROL Reports &amp; Analysen] behoben, das das Herunterladen von `.xls` Berichten verhinderte. Dieses Problem betraf Kunden, die andere Währungen als US-Dollar und Euro verwenden. (AN-206541, AN-204008)
* Mit der Einführung einer neuen Shell wurden mehrere Kundenprobleme beim Wechsel von Experience Cloud-Organisationen behoben.(AN-200844, AN-186920)
* Es wurde ein Fehler behoben, der dazu führte, dass eine Aufschlüsselung des Zeileneintrags _Nicht angegeben_ (oder einiger anderer Zeileneinträge in Berichten) ohne _Nicht angegeben (Keine)_ in den Filtern der Aufschlüsselung keine Ergebnisse in der Aufschlüsselung ergab.
* Es wurde ein Fehler behoben, der bei Verwendung einer klassifizierten Dimension auftrat, wenn die Summen der Einstiegs- oder Ausstiegsmetriken nicht mit der Summe des Einzelelements bei einer Aufschlüsselung übereinstimmten.
* Es wurde ein Problem behoben, bei dem First Touch- und Last Touch-Modelle in Attribution IQ die Gutschrift für einige Zeilenelemente in einigen Out-of-the-Box-Dimensionen nicht korrekt berechnen.
* Es wurde ein Problem behoben, bei dem das Aufschlüsseln einer Datumsdimension durch eine andere Datumsdimension falsche Ergebnisse zurückgab.
* Es wurde ein Problem behoben, bei dem Einstiegs- oder Ausstiegsmetriken manchmal falsch gezählt wurden, wenn sie auf &quot;Nicht angegeben&quot;in einem klassifizierten Dimensionsbericht angewendet wurden.

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt   oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Einstellung &quot;EOL of **[!UICONTROL Conversion Level]** &quot; | 3. März 2020 | Die nicht funktionierende [Konvertierungsstufe](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) unter **[!UICONTROL Admin Tools]>[!UICONTROL Report Suites]>[!UICONTROL Allgemeine Kontoeinstellungen]** wird am 12. März 2020 aus der Benutzeroberfläche entfernt. |
| EOL of **[!UICONTROL Dashboard Archive]** | 3. März 2020 | Ab dem 12. März 2020 ist die Einstellung **[!UICONTROL Ansichten-Archiv]** unter Dashboard **** verwalten in [!UICONTROL Reports &amp; Analysen] nicht mehr verfügbar. |
| Ende der Unterstützung für TLS 1.1 | 3. Oktober 2019 | Ab dem 31. März 2020 unterstützt Adobe Analytics TLS 1.1 nicht mehr. Diese Änderung ist Teil unserer laufenden Bemühungen, höchstmögliche Sicherheit von Kundendaten zu gewährleisten. |
| Neue Adobe Analytics-Domäne | 18. Dezember 2019 | Am 16. Januar 2020 begann Adobe Analytics mit der Umstellung auf eine neue Domäne – `https://experience.adobe.com/analytics.`<br>**Hinweis:** Diese Änderung gilt für alle Benutzer, die mit ihrer Adobe ID oder Enterprise ID auf Analytics zugreifen.<ul><li>Diese Änderung kann zu Problemen mit Cookies führen, wenn Analytics in Safari geladen wird. Wenn Sie in den Datenschutzvoreinstellungen von die Option _Prevent cross-site tracking_ (Website-übergreifendes Tracking verhindern) deaktivieren, werden domänenübergreifende Cookies (und alle Site-übergreifenden Ereignisse) aktiviert, sodass Analytics in dieser neuen Adobe Experience Cloud-Domäne funktionieren kann. [!DNL Safari] You can use other browsers without issue because this affects only [!DNL Safari] users.</li><li>Die Domänenänderung kann dazu führen, dass [!UICONTROL Activity Map] bei einigen Kunden [in bestimmten Fällen](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html) nicht mehr funktioniert.</li></ul> |
| End of Life - veraltete Analytics-APIs | 9. Januar 2020 | Im November 2020 werden die folgenden Legacy-API-Dienste von Analytics eingestellt. Aktuelle Integrationen, die mit diesen Diensten erstellt wurden, funktionieren dann nicht mehr. <ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Wir haben [FAQ zu Legacy API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) bereitgestellt, die Ihnen bei der Beantwortung Ihrer Fragen helfen und Anleitungen zum weiteren Vorgehen geben sollen. API-Integrationen, die diese Dienste nutzen, können zu den [Analytics-REST-APIs 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) oder den [Analytics-APIs 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) migrieren. Ältere OAuth-Konten können zu einem [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-Integrationskonto migrieren, das für den Zugriff auf sowohl Analytics-APIs 1.4 als auch Analytics-APIs 2.0 verwendet werden kann. |
| FTP-Broker in San Jose endet für London und Singapur | Juli 2020 | For customers in London and Singapore, we will no longer support brokering of data between London or Singapore and the San Jose data center [ftp.omniture.com](ftp://ftp.omniture.com/).<br/><ul><li>For London, use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>For Singapore, use [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |

### [!DNL AppMeasurement] {#appm}

Siehe [Versionshinweise zu AppMeasurement für JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Version 2.20.0 wurde am 5. März 2020 veröffentlicht.

## ![Symbol](/assets/audience-manager.png) -Audience-Manager {#aam}

Neue Funktionen und Updates für Audience Manager:

### Fixes and improvements {#aam-fixes-and-improvements}

* Es wurde ein Fehler behoben, durch den Kunden den Segmentnamen aufgrund einer fehlenden RBAC-Berechtigung [!UICONTROL ANSICHT_ALL_DESTINATIONS]nicht aktualisieren konnten. Die Berechtigung [!UICONTROL ANSICHT_ALL_DESTINATIONS] sollte nicht erforderlich sein, um ein Segment zu aktualisieren. Weitere Informationen zu RBAC-Berechtigungen finden Sie unter [Administration (RBAC-Steuerelemente)](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions). (AAM-52760)
* Es wurde ein Fehler in [Data Explorer](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) behoben, durch den einige Kunden keine Inhalte im Abschnitt &quot;Grundlegende Informationen&quot;und Operatoren im Ausdruck-Builder sehen konnten, wenn Eigenschaften anhand von [!UICONTROL Data Explorer] -Signalen erstellt wurden. (AAM-53130)
* Es wurde ein Fehler behoben, durch den einige Kunden die [!UICONTROL Audience Marketplace] -Oberfläche nicht laden konnten. (AAM-52070)
* Es wurde ein Fehler in der [!UICONTROL Segments-API] behoben, durch den die Oberfläche aufgrund einiger Segmente ohne Beschreibung gesperrt wurde, wenn Benutzer versuchten, auf diese Segmente zuzugreifen, und die Benutzer mussten von dieser Seite weg navigieren. (AAM-53071)
* Mehrere Verbesserungen der Barrierefreiheit auf der Benutzeroberfläche. (AAM-48952, AAM-48969, AAM-48979, AAM-48993, AAM-49048, AAM-49057, AAM-49058,AAM-493 (92)

## ![Symbol](/assets/aem.png) Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktaktualisierungen

* **AEM 6.5.4.0** AEM 6.5, Service Pack 4.0 (6.5.4.0, veröffentlicht am 5. März 2020) ist ein wichtiges Update, das neue Funktionen, wichtige Kundenverbesserungen, verbesserte Leistung, Stabilität und Sicherheit umfasst. Dieses Update wurde seit der allgemeinen Verfügbarkeit von AEM 6.5 im April 2019 veröffentlicht.
   * [Neue Funktionen in Adobe Experience Manager 6.5, Service Pack 4](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [Versionshinweise](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Versionen von AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4, Service Pack 8.0 (6.4.8.0, veröffentlicht am 5. März 2020) ist ein wichtiges Update, das wichtige Fehlerbehebungen von Kunden enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.4, April 2018 veröffentlicht wurden.
   * [Versionshinweise](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 8 (6.3.3.8, veröffentlicht am 5. März 2019) ist ein wichtiges Update, das wichtige Fehlerbehebungen von Kunden enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.3, April 2017 veröffentlicht wurden.
   * [Versionshinweise](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal **

   AEM Assets Brand Portal 6.4, Service Pack 6 (6.4.6 veröffentlicht am 5. März 2020) ändert die Konfiguration von AEM Assets mit [!UICONTROL Brand Portal.] Darüber hinaus umfasst die Version weitere Verbesserungen und Fehlerkorrekturen.
   * [Versionshinweise](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### Selbsthilfe

* **AEM als Cloud-Dienst - Rollenbasierte Berechtigungen**

   Cloud Manager verfügt über vorkonfigurierte Rollen mit entsprechenden Berechtigungen. Jede der Rollen verfügt über spezifische Berechtigungen, vorkonfigurierte Aufgaben oder Berechtigungen, die jeder Rolle zugeordnet sind. Im Hilfethema [Rollenbasierte Berechtigungen](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) werden die verfügbaren Funktionen und die Rollen, die diese ausführen können, aufgeführt.

* **AEM als Cloud-Dienst - Dispatcher**

   Die [Abschnitte Dispatcher und CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) und [Explizite Dispatcher-Cache-Ungültigmachung](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) wurden aktualisiert, um die verfügbaren Optionen und ihre Funktionsweise zu klären.

* **AEM Assets mit Markenportal konfigurieren**

   AEM Assets wird jetzt über Adobe I/O mit [!UICONTROL Markenportal] konfiguriert, das ein IMS-Token zur Autorisierung des Markenportal-Mandanten erhält. Früher wurde es über das [!UICONTROL Legacy OAuth Gateway in der Classic-Oberfläche konfiguriert.]
Siehe AEM Assets mit Markenportal [konfigurieren](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html).

* **AEM als Cloud-Dienst - Smart-Zuschneiden in dynamischen Medien**

   Eine neue Option ist in AEM als Cloud-Dienst verfügbar, wenn Sie mit Smart-Zuschneiden in der Komponente &quot;Dynamische Medien&quot;arbeiten:

   **Seitenverhältnis aktivieren Übereinstimmung** : Wählen Sie diese Option, damit dynamische Medien eine intelligente Schnittdarstellung auswählen können, die dem Seitenverhältnis des Originalbilds am besten entspricht.
Siehe [Arbeiten mit intelligentem Beschneiden](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop).

### Community

* **AEM Skill Builder-Webinare**

   * AEM-Sites - Ab dem 17. März 2020 lernen Sie die Bausteine des Inhaltserstellens und die grundlegenden Konzepte und Vorgänge von AEM-Sites kennen. [Registrieren Sie sich jetzt](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register).
   * AEM Assets - Ab dem 19. März 2020 verfügen Sie über Ihr Expertenwissen im Bereich des digitalen Asset-Managements. Lernen Sie die Grundlagen von Markenportal, [!UICONTROL dynamischen Medien,] [!UICONTROL Asset-Link und mehr kennen] . [Registrieren Sie sich jetzt](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register).

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

## ![Symbol](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Campaign Classic

* [Update zu Campaign Classic 19.1.4](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Zusätzliche Ressourcen

* Adobe Campaign Standard: [Dokumentation](https://helpx.adobe.com/support/campaign/standard.html) – [Versionshinweise](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)      – [Versionsplanung](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Dokumentation](https://helpx.adobe.com/support/campaign/classic.html) – [Versionshinweise](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Control Panel von Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## ![Symbol](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Aktualisiert: 10. Februar 2020, für die Version vom 8. Februar:

| Ansicht | Funktion |
|------|---------|
| [!UICONTROL Portfolios] | You can now add [!DNL Yahoo!] Japan Display Network (YDN) campaigns to portfolios to optimize the campaign budgets and ad group-level bids. Das gleiche Gebot wird auf alle Anzeigen einer Anzeigengruppe angewendet. Daten für japanische Display Network-Campaign sind in den Simulationen für das Portfolio enthalten. |
| [!UICONTROL Suche] > [!UICONTROL Bulksheets] | Sie können jetzt mithilfe von Bulksheets responsive Suchanzeigen (RSAs) von Google erstellen, bearbeiten und löschen. Zuvor war die Unterstützung nur über die Standard-Kampagnenverwaltungsoberfläche unter **[!UICONTROL Suche]** > **[!UICONTROL Kampagnen]** verfügbar. |
| [!UICONTROL Suchen] > [!UICONTROL Campaign, Berichte] | Die Google Ads-Bekanntheitsmetriken `Impr. (Abs. Top) %` und `Impr. (Top) %` stehen nun in allen allgemeinen Berichten und Kampagnenverwaltungsansichten auf Entitätsebene zur Verfügung, mit Ausnahme der Ansichten für Einkaufsproduktgruppen, in den Berichten [!UICONTROL Campaign Daily Impression Share] und [!UICONTROL Keyword Daily Impression Share] sowie in den Kennzeichnungs- und Beschränkungsansichten. |

## ![Symbol](/assets/magento.png) [!DNL Magento] {#magento}

Magento-Versionshinweise finden Sie unter:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Symbol](/assets/marketo.png) [!DNL Marketo] {#marketo}

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

**Marketo Engage Success Center:** Start im Februar 2020. Das Success Center ist ein produktinternes Hilfesystem, mit dem Sie u. a. Produktdokumente und die Community durchsuchen, Anleitungen aufrufen und auf Adoptionsinhalte zugreifen können. Hinweis: Diese Funktion wird als Betaversion in ANZ gestartet und später in diesem Quartal in Nordamerika eingeführt.

### Veraltete und entfernte Funktionen

* **Asset-API-Parameter „_method“:** Ab September 2020 wird „_method“ nicht mehr vom Asset-API-Endpunkte akzeptiert, um Abfrageparameter zu einem POST-Textkörper weiterzuleiten und URI-Längenbeschränkungen zu umgehen.
* **Einstellung der Unterstützung für Internet Explorer:** Ab der Juli-Version vom 31. Juli 2020 wird die Benutzeroberfläche von Marketo Engage in Internet Explorer nicht mehr unterstützt.

Eine Sammlung historischer Versionshinweisen finden Sie unter [Marketo-Versionshinweise](https://docs.marketo.com/x/CgA6Ag).

## ![Symbol](/assets/experience-cloud.png) Neue Dokumentation und Lernprogramme {#selfhelp}

Neue und aktuelle Artikel und Videos zur Selbsthilfe. <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| Lösung | Inhalt | Beschreibung |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | Video - [Erstellen mehrerer Kategorien- und Produktseiten](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | Hier erfahren Sie, wie Sie ein CIF-Projekt mit Adobe Experience Manager (AEM) als Grundlage für Kundenprojekte mit CIF-Kernkomponenten erstellen. Wenden Sie Design- und CSS-Stile auf Komponenten an und prüfen Sie ein neues AEM CIF-Projekt, das vom Archetyp generiert wurde. Erfahren Sie außerdem, wie CSS und JavaScript, die von CIF-Kernkomponenten verwendet werden, organisiert werden. |
| [!UICONTROL AEM Forms] | Artikel - [Authentifizierung bei AEM Author mithilfe von OKTA](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | Erfahren Sie, wie Sie Ihre App im OKTA-Portal konfigurieren und welche Einstellungen Sie normalerweise bei der Registrierung neuer Anwendungen verwenden. |
| [!UICONTROL AEM Commerce] | Übung - CIF-Kernkomponenten [anpassen](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | Überprüfen Sie mehrere verschiedene Erweiterungspunkte, die von CIF-Kernkomponenten und AEM im Allgemeinen bereitgestellt werden. CIF-Kernkomponenten bieten einen Standardsatz von Commerce-Komponenten, die zur Beschleunigung eines Projekts verwendet werden können, das Adobe Experience Manager (AEM)- und Magento-Lösungen integriert. |
| [!DNL Adobe Campaign] - Audience Ziele | Video - [Create an audience...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Erstellen Sie eine Audience in Campaign Standard mithilfe des Segmentaufbaus für die Adobe [!UICONTROL Experience Platform]. Sie können über die [!UICONTROL Audiencen] -Module direkt in Adobe Campaign Standard auf diese Funktion zugreifen. |
| [!DNL Adobe Campaign] - Audience Ziele | Video - [Aktivieren von Adobe Experience Platform-Audiencen in einem Marketing-Workflow](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | Erfahren Sie, wie Sie die Audience [!UICONTROL der] Data Services-Abfrage in einem Workflow aktivieren, indem Sie die Aktivität [!UICONTROL Audience] lesen verwenden. |
| [!DNL Adobe Campaign] | Übung - [Push-Benachrichtigung mit Android](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | Senden Sie personalisierte und segmentierte Push-Benachrichtigungen an mobile iOS- und Android-Geräte. In diesem Lernprogramm werden Sie durch die Schritte geführt, die beim Senden von Push-Benachrichtigungen von Adobe Campaign und beim Empfang dieser Benachrichtigungen in Ihrer Android-App erforderlich sind. |
| [!DNL Adobe Campaign] | Video - Push-Benachrichtigung [erstellen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Erstellen Sie eine Push-Benachrichtigung in Adobe Campaign Standard. Sie können personalisierte und segmentierte Push-Benachrichtigungen an mobile iOS- und Android-Geräte senden. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Überprüfen des Status eines Datenerfassungsauftrags](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | Erfahren Sie, wie Sie den Status eines Datenerfassungsauftrags überprüfen und ob die Daten aus Adobe Campaign Standard in Adobe Experience Platform aufgenommen wurden. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Ändern der Datenzuordnung](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | Erfahren Sie, wie Sie den Status überprüfen und die Datenzuordnung ändern können. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Landkartenerlebnis-Ereignisse](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Erfahren Sie, wie Sie Experience Ereignisses in Adobe Experience Platform zuordnen. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - Benutzerdefinierte Ressourcen [zuordnen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Erfahren Sie, wie Sie verschiedene Datentypen zwischen Adobe Campaign Standard und Adobe Experience Platform zuordnen. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Erläuterung des Adobe Experience Platform Data Connector](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | Erfahren Sie, wie Sie Ihre Daten auf der Adobe Experience Platform bereitstellen können, indem Sie XTK-Daten (in Campaign erfasste Daten) zu Experience Data Model-(XDM-)Daten auf der Adobe Experience Platform zuordnen. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - Seed- [Map-Tabellendaten](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Erfahren Sie, wie Sie Seed-Daten/Test-Profil mit der Adobe Experience Platform zuordnen. |
| [!DNL Adobe Campaign]- Audience Ziele | Video - Zielgruppendimension eines Versands für eine Plattform-Audience [ändern](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Erfahren Sie, wie Sie die Zielgruppendimension eines Versands für eine Plattform-Audience außerhalb der Tabelle für das primäre Profil in Adobe Campaign Standard ändern. |
| [!DNL Adobe Campaign] | Video - [Großes Data Management auf Schneeflocke](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Nutzen Sie den Snowflake-Connector in Adobe Campaign Classic. |
| [!DNL Adobe Campaign] - Audience Ziele | Artikel - [Audiencen-Zielorte (BETA) - Übersicht](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Erfahren Sie, wie Sie zentralisierte und konsolidierte Profil-Daten aus der Adobe Experience Platform für Marketing-Campaign in Adobe Campaign Standard nutzen können. |
| [!DNL Adobe Target] - Mobile SDK | Tutorial - [Personalisieren von App-Erlebnissen mit Adobe Zielgruppe](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Implementieren Sie die Adobe-Zielgruppe in Ihre eigene Android-App. Validieren Sie das Mobile Services SDK-Setup und implementieren Sie [!DNL Target] Anforderungen wie das Vorab-Abrufen von Inhalten, Sperren von Anforderungen und mehr. |
| Adobe Analytics | Video - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | Sehen Sie sich ausgewählte Clips aus der High-Tech-Supersitzung des Gipfels 2019 an. |
| Adobe Analytics | Video - [Einführung in berechnete Metriken in Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | Gehen Sie durch die Grundlagen der Erstellung [!UICONTROL berechneter Metriken] in der [!UICONTROL Customer Journey Analytics]. |
| Adobe Analytics | Video - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | Ansicht kuratierte Clips aus der Reise- und Gastfreundschaftssitzung des Gipfels 2019. |
| Adobe Analytics | Video - [Adobe Summit 2019 Super Session](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | Siehe ausgewählte Clips aus der Einzelhandelssitzung auf Summit 2019. |
| Adobe Analytics | Video - [Verwendungsfall für Kunden: Akzentgruppe investiert in Kundenerfahrung, um den Verkauf voranzutreiben](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | Sehen Sie sich an, wie die Accent-Gruppe mit der Adobe Experience Cloud nahtlose digitale Erlebnisse erstellt. |
| Adobe Analytics | Video - [Verwendungsfall für Kunden: ServiceNow erhält die richtigen Einblicke zur Verbindung mit Potenzieller Kunden](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | Finden Sie heraus, wie Sie mit Adobe Advertising Cloud und Adobe Analytics umsetzbare Daten von Ihren Marketing-Kanälen [!DNL ServiceNow] abrufen und den ROI bei gebührenpflichtiger Suchwerbung steigern können. |
| Adobe Analytics | Video - [Adobe Analytics - Mehr als nur Daten - Customer Intelligence](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | Erfahren Sie mehr über datengesteuertes Marketing und wie Sie Ihre Analysenreife von Daten über Einblicke bis hin zu Aktionen optimieren können. |
| Adobe Analytics | Video - [Adobe Sensei und Adobe Analytics - Erweiterte Version](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | Ansicht der wichtigsten Funktionen in Adobe Analytics auf Basis von Adobe [!DNL Sensei,] einschließlich [!UICONTROL Anomalieerkennung,] [!UICONTROL Beitragsanalyse,] Intelligente Warnhinweise,  Clustering, [!UICONTROL Segment-IQ,Analyse und]  [!UICONTROL Propensity-Modellierung.] |
| Adobe Analytics | Video - [Wie Adobe Analyse Workspace Ihr Unternehmen verändern kann](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | Erfahren Sie, wie Sie Ad-hoc-Analysen, flexible Analysen, Kohorten-Analysen und Fallout-Analysen mithilfe von [!UICONTROL Analyse Workspace]durchführen können. Sie können die funktionierende Analyse auch für alle in Ihrer Firma freigeben. Die Drag &amp; Drop-Funktion ermöglicht es jedem, die Daten einfach zu analysieren und schnell Einblicke zu erhalten. |
| Adobe Analytics | Video - [Verwendungsfall für Kunden: Das Home Depot wird durch Customer Experience Management innovativ](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | Erfahren Sie, wie [!DNL Home Depot] Sie mit Adobe-Lösungen mit einem personalisierten, benutzerspezifischen Einkaufserlebnis Markenloyalität und Kundenzufriedenheit schaffen. |
| Adobe Analytics | Präsentation - [Informationen zur Customer Journey-Analyse](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | Erfahren Sie, wie Adobe mit [!UICONTROL Customer Journey Analytics], einem auf [!DNL Adobe Experience Platform]der [!UICONTROL Analyse Workspace] aufbauenden Anwendungsdienst, in die Experience Platform integriert wird. Diese Funktion ermöglicht die Analyse von mehreren Kanälen in allen [!DNL Adobe Experience Platform] Datensätzen. |
| Adobe Analytics | Video - Zuordnung [zu anderen Kanälen in CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | Erfahren Sie, wie Sie mithilfe von Visualisierungen die Zuordnung (Gutschrift) zu Kanälen in [!UICONTROL Customer Journey Analytics]anzeigen können. |
| Adobe Analytics | Artikel - [Kundentipps zur Fortführung Ihrer Adobe Analytics-Lernreise](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Treffen Sie drei Adobe-Kunden, die Tipps und Tricks dazu haben, wie Sie Adobe Analytics optimal nutzen können. |
| Adobe Analytics | Video - [Erstellen von Visualisierungen für mehrere Kanal in CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | Erfahren Sie, wie Sie mit [!UICONTROL Customer Journey Analytics] Visualisierungen erstellen können, die Daten aus mehreren Datensätzen über mehrere Kanal hinweg enthalten, einschließlich der Zusammenführung der Daten pro Besucher. |
| Adobe Analytics | Video - [Verschieben Sie Ihre berechneten Metriken von Adobe Analytics in Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | Hier finden Sie Tipps zur Neuerstellung Ihrer Analytics- [!UICONTROLCberechneten Metriken] in der [!UICONTROL Customer Journey-Analyse]. |
