---
title: Adobe Experience Cloud – Versionshinweise
description: Adobe Experience Cloud – Versionshinweise
doc-type: release notes
last-update: July 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 19591a3d807cd772df0eb20e457d94cc9f7d5cfb
workflow-type: tm+mt
source-wordcount: '4203'
ht-degree: 60%

---


# Vorzeitiger Zugriff - Versionshinweise zu Adobe Experience Cloud - Juli 2020

![Banner](/assets/experience-cloud-banner-3.png)

Auf dieser Seite sind neue Funktionen, Fehlerbehebungen und wichtige Hinweise in [!DNL Adobe Experience Cloud] beschrieben. Außerdem werden neue Dokumentationen, Schulungen und Videoschulungen vorgestellt, die Ihnen helfen, Experience Cloud optimal zu nutzen.

>[!IMPORTANT]
>
>Diese Seite enthält Inhalte einer Vorabversion und kann vor der geplanten Veröffentlichung der Version geändert werden.

>[!NOTE]
>
>Abonnieren Sie das [Prioritätsprodukt-Update von Adobe](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bevorstehende Versionen benachrichtigt zu werden.

**Releasedatum: 16. Juli 2020**

Die Veröffentlichungsdaten einzelner Produkte können variieren. Suchen Sie regelmäßig nach Updates.

Neueste Aktualisierung: **10. Juli 2020**

* [Systemstatus von Adobe](#status)
* [Experience Cloud-Benutzeroberfläche](#ecloud)
* [Experience Platform](#platform)
* [Journey-Orchestrierung](#journey-orch)
* [Analytics](#analytics) und [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Kampagne](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/de-DE/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/de/primetime/user-guide.html) (Link zur Primetime-Hilfeseite)

Benötigen Sie Hilfe? Besuchen Sie [Adobe Experience League](https://experienceleague.adobe.com/#home), um Produkt- und technische Dokumentation, von Adobe kuratierte Kurse, Videoschulungen, schnelle Antworten, Community-Einblicke und von Schulungsleitern geführte Kurse zu erhalten.

## ![Symbol](/assets/adobe.png) Systemstatus von Adobe {#status}

[!UICONTROL Der Adobe-Systemstatus] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe Cloud-Produkten und -Diensten. Weitere Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/).

Veröffentlicht: **21. Mai 2020**

**Neuigkeiten**

* Mit Ihrer Adobe ID können Sie Ereignisbenachrichtigungen mit größerer Granularität bis hinunter zur Produktangebot- und Add-on-Ebene abonnieren. Um die Konfiguration Ihres Abonnements zu beschleunigen, wird bei der Abonnement-Selbstregistrierung jetzt eine Auswahl von Produkten und Dienstleistungen empfohlen, die auf Ihren Produktberechtigungen basieren. Dies sollte die Anzahl der E-Mails, die Sie erhalten, reduzieren und relevantere Benachrichtigungen in Ihrem Posteingang liefern. Weitere Informationen erhalten Sie unter [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Ab heute verfügbare neue Funktionen und Verbesserungen**

| Funktion | Beschreibung |
| -----------| ---------- |
| Verbessertes Kundenerlebnis bei Abonnements und Benachrichtigungen | <ul><li>Regionale [!DNL Marketo Engage]-Standorte werden nun anhand der Liste der ausgewählten Produktangebote gefiltert.</li><li>E-Mail-Benachrichtigungen von [!DNL Marketo Engage] sind für die Region, den Standort und die Umgebungsvoreinstellungen eines Benutzers relevant.</li></ul> |
| Bestätigungen von Ereignis-Abonnements | <ul><li>Sie können jetzt eine E-Mail-Bestätigung erhalten, wenn Sie laufende Aktualisierungen für einzelne Ereignisse abonnieren.</li></ul> |
| Verbesserungen der Benutzerfreundlichkeit der globalen Navigation | <ul><li>Konsistentes Kundenerlebnis im obersten Navigationsmenü auf `Adobe.com`.</li></ul> |

## ![Symbol](/assets/ec_appicon_24.png) Experience Cloud-Benutzeroberfläche {#ecloud}

Allgemeine Aktualisierungen der Experience Cloud-Benutzeroberfläche.

**Aktualisiertes Menü der Benutzeroberfläche**

In Experience Cloud wird mit der Version vom 16. **Juli 2020** das Dropdownmenü &quot;Anwendungsschalter&quot;aktualisiert. Es wurde optimiert, sodass Lösungs-Logos entfernt werden, und das Menü zeigt nur die Anwendungen und Dienste an, auf die Sie Zugriff haben.

Ein Beispiel finden Sie in der [Produktdokumentation](https://docs.adobe.com/content/help/de-DE/core-services/interface/experience-cloud.html) zur Experience Cloud-Oberfläche.

**Einheitliche Produktdomäne**

Adobe hat die Domäne und die Kopfzeile der Benutzeroberfläche aktualisiert, um Ihr Benutzererlebnis in allen Experience Cloud-Anwendungen zu vereinheitlichen und zu verbessern. Diese Verbesserungen sollen das Benutzererlebnis auf kleine, aber wichtige Weise vereinfachen. Ihre aktuellen Workflows werden dadurch nicht geändert.

Zu den Aktualisierungen gehören:

* Neue Anwendungs-URLs: `experience.adobe.com/<application name>`:
   * Dieses URL-Muster wird schließlich von allen Produkten übernommen. Im Laufe des Monats werden neue URLs hinzugefügt werden.
   * Browserunterstützung: Unterstützte Browser sind [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] und [!DNL Opera] (neueste Versionen). **Hinweis:** Obwohl die Experience Cloud-Oberfläche diese Browser unterstützt, unterstützen einzelne Anwendungen möglicherweise nicht alle Browser. ([Analytics](https://docs.adobe.com/content/help/de-DE/analytics/admin/sys-reqs.html) unterstützt beispielsweise nicht [!DNL Opera] und [Target](https://docs.adobe.com/help/de-DE/target/using/implement-target/before-implement/supported-browsers.html) unterstützt nicht [!DNL Safari].)
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

Versionshinweise für [!DNL Experience Platform] und Anwendungsdienste, einschließlich [!DNL Experience Platform Launch,] [!UICONTROL Angeboten], [!UICONTROL Personen], [!UICONTROL Places], [!UICONTROL Mobile Services] und Sicherheitsbulletins.

Latest release date: **June 10, 2020**

Aktuelle Informationen zur Experience Platform finden Sie in den Versionshinweisen zur [Experience Platform](https://docs.adobe.com/content/help/de-DE/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) .

## ![Symbol](/assets/experience_platform_appicon_24.png) Customer Journey Orchestration {#journey-orch}

Mithilfe der Adobe Experience Platform können Sie individuelle Customer Journeys maßstabsgetreu über verschiedene Erlebniskanäle orchestrieren, indem Sie die Bedürfnisse jedes einzelnen Kunden in Echtzeit und unabhängig vom Zielort intelligent antizipieren.

### Zusätzliche Ressourcen für Journey Orchestration

[Dokumentation](https://docs.adobe.com/content/help/de-DE/journeys/using/journey-orchestration-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/journeys/using/release-notes/release-notes.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Symbol](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Releasedatum: **16. Juli 2020**

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
| Arbeitsbereich: Neue Vorgaben für Datumsbereiche | Es wurden vier neue Datumsbereiche hinzugefügt (_Diese Woche/Monat/Quartal/Jahr_ (außer heute)), sodass Benutzer aus Datumsbereichen wählen können, die keine Daten aus Teiltagen von heute enthalten. |
| Datenreparatur-API - öffentliche Beta-Version | Die Datenreparatur-API bietet eine Selbstbedienungsoption zum Löschen von Spalten mit Adobe Analytics-Daten. Nach Veröffentlichung der öffentlichen Beta-Version unterstützt die API das Löschen von Activity Map-Daten. Weitere Funktionen werden später bereitgestellt. Wenden Sie sich an den Kundendienst, um Zugriff auf diese API zu erhalten. |

### Neue Funktionen in Customer Journey Analytics {#cust-journey}

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/de-DE/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| -----------| ---------- |-----|
| Keine neuen Funktionen in diesem Monat |  |  |

### Neue Funktionen in [!UICONTROL Media Analytics] {#media-aa}

Datum aktualisiert: **16. Juli 2020**

| Funktion | [Allgemeine Verfügbarkeit](https://docs.adobe.com/content/help/de-DE/analytics/landing/an-releases.html) – geplantes Datum | Beschreibung |
| -----------| ---------- | ---------- |
| [Unterstützte Geräte und Plattformen](https://docs.adobe.com/content/help/de-DE/media-analytics/using/supported-devices.html) | 18. Juni 2020 | Die Media Launch-Erweiterung mit dem AEP-SDK unterstützt jetzt die folgenden OTT-Geräte:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |  | [Unterstützte Geräte und Plattformen](https://docs.adobe.com/content/help/de-DE/media-analytics/using/supported-devices.html) | 18. Juni 2020 | Die Media Launch-Erweiterung mit dem AEP-SDK unterstützt jetzt die folgenden OTT-Geräte:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android TV</li></ul> |
| [Player-Status-Tracking](https://docs.adobe.com/content/help/de-DE/media-analytics/using/player-state-tracking/player-state-overview.html) | 29. Mai 2020 | [!UICONTROL Media Analytics]-Kunden können die Interaktion mit dem Besucher während der Wiedergabe mit einem Standardsatz von Lösungsvariablen für Vollbild, verdeckte Untertitel, Stummschaltung, Bild-in-Bild und im Fokus erfassen. Sie haben auch die Möglichkeit, benutzerdefinierte Player-Status zu erstellen. Player-Status-Tracking-Variablen sind jetzt für Berichte in [!UICONTROL Analysis Workspace] verfügbar. Diese Funktion erfordert eine der folgenden Voraussetzungen: <ul><li>Media [!DNL JavaScript] SDK 3.0 oder höher</li><li>Zur Verwendung mit dem [!DNL Adobe Experience Platform] (AEP)-SDK:</li><li>[!UICONTROL Media Analytics-Erweiterung] (für Web): [!UICONTROL Adobe Media Analytics] (3.x SDK) für Audio und Video v1.0 oder höher</li><li>[!UICONTROL Media Analytics-Erweiterung] (für Smartphone und Tablet): [!UICONTROL Adobe Media Analytics für Audio] und Video v2.0 oder höher</li><li>[!UICONTROL Mediensammlung]</li></ul> |

### Fehlerbehebungen in Adobe Analytics {#aa-fixes}

* Es wurde ein Problem behoben, das nach dem Wechsel zu einer Report Suite mit einer anderen Währung auftrat. Das Liniendiagramm [!UICONTROL Workspace] spiegelte nicht die richtige Währung wider. (AN-216655)
* Es wurden Probleme mit Visualisierungen behoben, die in heruntergeladenen PDFs nicht lesbar waren. (AN-217949)
* Es wurde ein Fehler behoben, der beim Hinzufügen einer Hierarchievariablen zu einer Report Suite zu einem Fehler führte. (AN-211974)
* Es wurde ein Fehler behoben, der beim Bearbeiten eines Datenfeeds auftrat, der einer Report Suite zugeordnet war, die eine andere Zeitzone als die aktuell ausgewählte Report Suite [!UICONTROL Reports &amp; Analytics] hatte. (AN-222474)
* Es wurde ein Problem behoben, durch das der [!UICONTROL Classification Rule Builder] nicht funktionierte. (AN-219662)
* Mehrere Probleme mit Classifications- und Classification-Regeln wurden behoben. (AN-223492, AN-220654, AN-219662, AN-223260)
* Es wurde ein Problem behoben, bei dem dasselbe Segment verschiedene Daten in einer Virtual Report Suite im Vergleich zur übergeordneten Report Suite zurückgab. (AN-201074)
* Es wurde ein Problem behoben, das den Download der Report Suite-Einstellungen verhinderte. (AN-223690)
* Es wurde ein Fehler in [!UICONTROL Intelligente Warnhinweise] behoben, der verhinderte, dass die _Opt-out dieses E-Mail-Links_ funktionierte. (AN-223875)
* Es wurde ein Problem mit einer falschen Währung behoben, die für eine Virtual Report Suite angezeigt wurde. (AN-224781)
* Es wurde ein Problem mit _Fehlern bei Komponenten_ in Virtual Report Suites behoben. (AN-224782)

#### Weitere Fehlerbehebungen in Adobe Analytics

AN-222672, AN-222813; AN-222892; AN-223272, AN-223432; AN-224062; AN-224108; AN-224163; AN-224339; AN-224456; AN-224449; AN-224552; AN-224553; AN-224786

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Report Suite-Zuordnung zu IMS-Org | Juli 2020 | Das Zuordnungstool für Report Suites wird im November 2020 eingestellt. Diese Funktion unterstützt Integrationen wie das Anzeigen von Analytics und das Veröffentlichen von Experience Clouden in Adobe Analytics. Eine Report Suite muss einem IMS-Org zugeordnet sein, um diese und andere Dienste zu aktivieren. Neuere Report Suites werden bei der Erstellung automatisch zugeordnet. Ältere Report Suites müssen jedoch manuell einem IMS-Org zugeordnet werden. Siehe [Ordnen Sie Report Suites einer Organisation](https://docs.adobe.com/content/help/de-DE/core-services/interface/about-core-services/report-suite-mapping.html) im Core Services-Benutzerhandbuch zu, um sicherzustellen, dass alle Report Suites zu einem IMS-Tag gehören. |
| Migration zu einer einheitlichen Produkt-Domain | Datum des Inkrafttretens: 28. Mai 2020 | Die Migration zu einer einheitlichen Produkt-Domain für Adobe Analytics, die im Januar 2020 begann, wurde am 28. Mai 2020 abgeschlossen. Adobe Analytics entfernt alle `omniture.com` Domain-Verweise aus seiner Architektur. Gleichzeitig muss `omniture.com` als Drittanbieter-Cookie auf die Zulassungsliste gesetzt werden. Wenn die Migration der vollständigen Architektur (bald) abgeschlossen ist, werden wir Sie in den Versionshinweisen darüber benachrichtigen. Dann ist dieser Schritt mit der Zulassungsliste nicht mehr erforderlich. [Hier](https://helpx.adobe.com/de/analytics/kb/adobe-ip-addresses.html) finden Sie eine vollständige Liste der empfohlenen IP-Adressen und Domänen, die Sie auf die Zulassungsliste setzen sollten.<br>Wenn Ihr Unternehmen Drittanbieter-Cookies blockiert, wenden Sie sich an die Kundenunterstützung, um wieder Zugriff auf Adobe Analytics zu erhalten. |
| Neue Standard-Landingpage von Adobe Analytics | Datum des Inkrafttretens: 18. Juni 2020 | Am 18. Juni 2020 ändert sich die standardmäßige Landingpage für Adobe Analytics von [!UICONTROL Reports] in [!UICONTROL Arbeitsbereich]. Diese Änderung wird für alle Benutzer sichtbar sein, die zuvor keine benutzerdefinierte Landingpage festgelegt haben. |
| Zulassungsliste für Drittanbietertechnologie | 12. März 2020 (Datum des Inkrafttretens) | Adobe Analytics hat begonnen, Technologien von Drittanbietern für die Verwaltung des Funktions-Rollouts und die Unterstützung innerhalb von Produkten zu nutzen. Die folgenden URLs sollten zu allen erforderlichen Netzwerk-Firewall-Zulassungslisten hinzugefügt werden, um den Zugriff auf alle Funktionen sicherzustellen:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Die Redundanz für die [!UICONTROL Analysis Workspace]-Verfügbarkeit wurde verbessert | 21. Mai 2020 | Um die Verfügbarkeit von [!UICONTROL Analysis Workspace] sicherzustellen, fügen wir ein sekundäres CDN (Content Delivery Network) hinzu, das die Redundanz verbessert. Die folgenden URLs sollten allen erforderlichen Netzwerk-Firewall-Zulassungslisten hinzugefügt werden:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Änderung der Berechnung von [!UICONTROL Einstiegen/Ausstiegen] in [!UICONTROL Workspace] | 7. April 2020 | In [!UICONTROL Analysis Workspace] wurde im März 2020 die Weise geändert, wie der Wert _Keine_ in Bezug auf [!UICONTROL Einstiege/Ausstiege] verwendet wird. Da Sie jetzt _Keine_ in [!UICONTROL Analysis Workspace] aktivieren und deaktivieren können, wird _Keine_ jetzt erst nach einem Ein- oder Ausstieg angewendet, während dieser Wert früher (bei eVars) vor einem Ein- oder Ausstieg angewendet wurde. Angenommen, der erste Treffer eines Besuchs liefert keinen Wert für eVars, der zweite aber schon. In [!UICONTROL Reports &amp; Analytics] wird der erste Treffer als _Nicht angegeben_ für den Einstieg angezeigt, aber in [!UICONTROL Analysis Workspace] wird dieser Wert beim zweiten Treffer angezeigt. |
| Entfernung des **[!UICONTROL Dashboard-Archivs]** | 27. März 2020 | Ab Oktober 2020 ist die Einstellung **[!UICONTROL Archiv anzeigen]** unter **[!UICONTROL Dashboards verwalten]** in [!UICONTROL Reports &amp; Analytics] nicht mehr verfügbar. |
| End of Life – veraltete Analytics-APIs | 9. Januar 2020 | Im November 2020 werden die folgenden Legacy-API-Dienste von Analytics eingestellt. Aktuelle Integrationen, die mit diesen Diensten erstellt wurden, funktionieren dann nicht mehr. <ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Wir haben [FAQ zu Legacy API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) bereitgestellt, die Ihnen bei der Beantwortung Ihrer Fragen helfen und Anleitungen zum weiteren Vorgehen geben sollen. API-Integrationen, die diese Dienste nutzen, können zu den [Analytics-REST-APIs 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) oder den [Analytics-APIs 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) migrieren. Ältere OAuth-Konten können zu einem [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-Integrationskonto migrieren, das für den Zugriff auf sowohl Analytics-APIs 1.4 als auch Analytics-APIs 2.0 verwendet werden kann. |
| FTP-Broker in San Jose endet für London und Singapur | Juli 2020 | Für Kunden in London und Singapur wird die Datenvermittlung zwischen den beiden Städten und dem Rechenzentrum in San Jose ([ftp.omniture.com](ftp://ftp.omniture.com/)) nicht mehr unterstützt.<br/><ul><li>Für London verwenden Sie [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Für Singapur verwenden Sie [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ende von Ad Hoc Analysis | 6. August 2018 | Adobe kündigte die Absicht an, Ad Hoc Analysis einzustellen. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist. Weiterführende Informationen finden Sie unter [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### AppMeasurement

Die neuesten Aktualisierungen zu AppMeasurement-Versionen finden Sie in den Versionshinweisen zu [AppMeasurement für JavaScript](https://docs.adobe.com/content/help/de-DE/analytics/implementation/appmeasurement-updates.html).

#### Analytics-Hilferessourcen

* [Adobe Analytics-Tutorials](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics-Produktdokumentation](https://docs.adobe.com/content/help/de-DE/analytics/landing/home.html)

## ![Symbol](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Neue Funktionen, Fehlerbehebungen, Dokumentationen und Tutorials in Audience Manager.

Releasedatum: **16. Juli 2020**

### Neue Funktionen und Fehlerbehebungen in Adobe Audience Manager

* Es wurde ein Problem behoben, bei dem Kunden einige Segmente nicht Amazon-Zielen zuordnen konnten. (AAM-54373)
* Es wurde ein Problem behoben, bei dem der Browserbildschirm eingefroren wurde, wenn Kunden ein Segment in einer neuen Registerkarte geöffnet hatten. (AAM-55213)
* Es wurde ein Problem im Bericht [zum](https://docs.adobe.com/help/en/audience-manager/user-guide/reporting/onboarding-status-report.html)Onboarding-Status behoben, bei dem Kunden eine Datumsabweichung zwischen dem Datum sehen konnten, das beim Klicken auf eine Leiste im Diagramm und dem Datum in der Tabelle auftrat. (AAM-55235)
* Es wurde ein Fehler im Abschnitt Administration behoben, durch den in der Benutzeroberfläche anstelle einer Bestätigungsmeldung ein Fehlersymbol angezeigt wurde, wenn Kunden versuchten, Benutzer zu löschen. (AAM-55186)
* Es wurde ein Problem mit der Swagger-API behoben, bei dem der `x-api-key` Header nicht zur Anfrage &quot;curl&quot;hinzugefügt wurde. (AAM-55392)
* Die standardmäßige Sortierreihenfolge für Segmente, die Zielen in der Ansicht &quot;Ziele&quot;zugeordnet sind, wurde verbessert. Die zugeordneten Segmente werden nun nach dem Beginn der Segmentzuordnung und dann nach Segment-ID sortiert. (AAM-38494)
* Mehrere Verbesserungen hinsichtlich der Barrierefreiheit auf der gesamten Benutzeroberfläche. (AAM-48956, AAM-49012, AAM-49364, AAM-49363, AAM-49374, AAM-49579, AAM-55037).

## ![Symbol](/assets/aem.png) Adobe Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktaktualisierungen

* **Dynamic Media Classic**

   Dynamic Media Classic-Benutzer haben jetzt Zugriff auf eine neue Desktop-App-Erfahrung, die im Browser nicht mehr auf Adobe Flash-Technologie zurückgreift. Die neue App ist jetzt für Windows und macOS verfügbar.

   Siehe [Adobe Dynamic Media Classic Desktop-App - jetzt verfügbar.](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/new-ui-2020.html)

* **3D-Asset-Unterstützung zu Dynamic Media hinzugefügt**

   Mit Dynamic Media in AEM 6.5 und AEM als Cloud Service können Sie jetzt 3D-Assets hochladen, verwalten, Ansicht und als umfassende Erlebnisse bereitstellen.

   * In AEM als Cloud Service finden Sie weitere Informationen unter [Arbeiten mit 3D-Assets in Dynamic Media.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/assets-3d.html)
   * In AEM 6.5, see [Working with 3D assets in Dynamic Media.](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/assets-3d.html)

### Selbsthilfe

* **Aktualisierungen der Dokumentation zu AEM 6.5.5 Forms**

   * Neue Funktionen und Verbesserungen in Version 6.5.5:

      * [Passen Sie die Inbox-Spalten](https://docs.adobe.com/content/help/en/experience-manager-65/authoring/essentials/inbox.html#inbox-admin-control)des Adobe Experience Managers an.
      * [Interaktive Kommunikation als Entwurf speichern](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/prepare-send-interactive-communication.html#save-as-draft)
      * Oracle WebLogic-Anwendungsserver-Unterstützung für [Installationen auf einem Server](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-single-server.pdf) und einem [Cluster](https://helpx.adobe.com/content/dam/help/en/experience-manager/6-5/forms/pdf/prepare-install-cluster.pdf) .
      * [Verbesserungen bei der Barrierefreiheit.](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#accessibility-improvements)
      * [X-509-Zertifikatbasierte Authentifizierung für SOAP-basierte Webdienste im Formulardatenmodell.](https://docs.adobe.com/content/help/en/experience-manager-65/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [Oracle RAC-Unterstützung.](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html#other-improvements)
      * [Verbesserte Fehlerprotokollierung im Transaktions-Berichte.](https://docs.adobe.com/content/help/en/experience-manager-65/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)
   * Neue Funktionen und Verbesserungen in Version 6.4.8.1:
      * [X-509-Zertifikatbasierte Authentifizierung für SOAP-basierte Webdienste im Formulardatenmodell.](https://docs.adobe.com/content/help/en/experience-manager-64/forms/form-data-model/configure-data-sources.html#configure-soap-web-services)
      * [Verbesserte Fehlerprotokollierung im Transaktions-Berichte.](https://docs.adobe.com/content/help/en/experience-manager-64/forms/transaction-reports/viewing-and-understanding-transaction-reports.html#view-transaction-reporting-logs)

### **Community**

* **AEM-Community-Diskussion**

   Jetzt können Sie sich alle Ankündigungen und interessanten Verweise von AEM auf interne und externe Blogger an einem Ort ansehen. Informationen finden Sie im [Diskussionsabschnitt](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions) der AEM-Community.

### Neue Experience Manager-Kurse und -Tutorials

Neue Videos, Tutorials oder Kurse, die im letzten Monat veröffentlicht wurden.

| Veröffentlicht | Name | Typ | Beschreibung |
| -----------| ---------- | ---------- | ---------- |
| 25. Juni 2020 | [Erste Schritte mit adaptiven Formularen](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/creating-your-first-adaptive-form/adaptive-forms-getting-started-tutorial-use.html) | Video | Diese Lernprogramme erläutern Ihnen, wie Sie adaptive Formulare mit mehreren Registerkarten erstellen können. Erfahren Sie, wie Sie mit Tabellen, Akkordeon-Layout und Regeleditor Geschäftsregeln erstellen können. |
| 25. Juni 2020 | [Erstellen eines Review-Arbeitsablaufs in AEM Forms](https://video.tv.adobe.com/v/35821/quality=9?captions=ger) | Video | Hier erfahren Sie, wie Sie einen Arbeitsablauf für die Überprüfung gesendeter Daten aus einer aktiven Formularübermittlung erstellen. |
| 23. Juni 2020 | [Verarbeitungsprofile](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/processing-profiles.html) | Video | Verarbeitungsvariablen definieren die Darstellungen, die für Assets in AEM als Cloud Service erstellt werden sollen. |
| 23. Juni 2020 | [Best Practices für Dynamic Media Classic](https://docs.adobe.com/content/help/en/experience-manager-learn/dynamic-media-classic-tutorial/overview.html) | Artikel | Aktuelle und neue Benutzer können sich über Dynamic Media Classic, seine Kernfunktionen sowie den _Arbeitsablauf für Erstellen_, _Autoren_ und _Bereitstellung_ informieren. |
| 23. Juni 2020 | [Debugging von AEM als Cloud Service-Build und Bereitstellungen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/build-and-deployment.html) | Artikel | Erfahren Sie, wie Sie Build- und Bereitstellungen für AEM als Cloud Service debuggen. |
| 16. Juni 2020 | [Debugging von AEM als Cloud Service mithilfe von Protokollen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/logs.html) | Artikel | Erfahren Sie, wie Sie mithilfe von Protokollen AEM als Cloud Service debuggen. Protokolle dienen als Frontline zum Debuggen von AEM-Anwendungen, sind jedoch von einer angemessenen Anmeldung bei der bereitgestellten AEM-Anwendung abhängig. |
| 10. Juni 2020 | [Verwenden von Dynamic Media 3D mit AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/dynamic-media/dynamic-media-3d-feature-video.html) | Video | Dynamic Media 3D-Unterstützung für Adobe Experience Manager ermöglicht Ihnen die einfache Anpassung und Bereitstellung interaktiver 3D-basierter Erlebnisse im Maßstab. |
| 5. Juni 2020 | [SPA-Editor-Projekt](https://docs.adobe.com/content/help/en/experience-manager-learn/spa-react-tutorial/create-project.html) | Artikel | Erfahren Sie, wie Sie mit dem Projektarchetyp Adobe Experience Manager (AEM) ein Maven-Mehrmodulprojekt als Ausgangspunkt für eine React-Anwendung erstellen können, die mit dem AEM SPA Editor integriert ist. |
| 3. Juni 2020 | [Handhabung der Übermittlung von HTML5-Formularen - Übung](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/html5-forms/handle-mobile-form-submission.html) | Artikel | Erfahren Sie, wie Sie im benutzerdefinierten Sende-Handler auf gesendete Daten zugreifen können. |

### Versionsinformationen zu Experience Managern

Alle Versionshinweise zum Experience Manager werden auf den folgenden Seiten beibehalten:

* [Versionsinformationen zu AEM als Cloud Service](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/release-notes/home.html)
* [Versionshinweise für AEM Cloud Manager](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Versionshinweise zum Automatisierten Forms-Konvertierungsdienst](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/using/release-notes.html)
* [Versionshinweise für AEM 6.5 Service Pack](https://docs.adobe.com/content/help/de-DE/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Versionshinweise zu AEM 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/de-DE/experience-manager-64/release-notes/cfp-release-notes.html)
* [Versionshinweise zu AEM Assets Dynamic Media](https://docs.adobe.com/content/help/de-DE/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Versionshinweise zu AEM Brand Portal](https://docs.adobe.com/content/help/de-DE/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Versionshinweise zum AEM-Desktop-Programm](https://docs.adobe.com/content/help/de-DE/experience-manager-desktop-app/using/release-notes.html)
* [Versionshinweise zu AEM Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Versionshinweise zu Adobe Primetime](https://docs.adobe.com/content/help/de-DE/primetime/release-notes/home.translate.html)
* [Livefyre-Versionshinweise](https://docs.adobe.com/content/help/de-DE/livefyre/using/release-notes/c-rn.html)

### Zusätzliche Hilferessourcen für AEM

* [Benutzerhandbücher für AEM als Cloud Service](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/landing/home.html)
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

Versionsinformationen für Campaign Classic, Campaign Standard und Systemsteuerung.

#### Campaign Classic

* Neuer Gold Standard Stable Build. [Weitere Infos](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

#### Control Panel von Campaign

* Prüfung der Subdomänenbereitstellung - [Weitere Informationen](https://docs.adobe.com/content/help/de-DE/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)

* Verwaltung von GPG-Schlüsseln - [Weitere Informationen](https://docs.adobe.com/content/help/en/control-panel/using/instances-settings/gpg-keys-management.html)

### Neue Campaign-Kurse und -Tutorials

Neue Videos, Tutorials oder Kurse, die im letzten Monat veröffentlicht wurden.

| Veröffentlicht | Name | Lösung | Beschreibung |
| ----------- | ----------- | ---------- | ---------- |  
| 26. Juni 2020 | [Die Benutzeroberfläche von Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/exploring-the-adobe-campaign-classic-user-interface.html) | Campaign Classic | In diesem Video wird die Hauptbenutzeroberfläche von Adobe Campaign Classic erläutert und die Navigation in der Hauptfunktion erläutert. |
| 8. Juli 2020 | [Installieren und Einrichten des Adobe Campaign-Clients](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/install-and-setup-the-adobe-campaign-client.html) | Campaign Classic | Erfahren Sie, wie Sie die Adobe Campaign-Client-Konsole herunterladen und installieren, Verbindungen mit mehreren Umgebung erstellen und verwalten und den Zugriff auf die Adobe Campaign-Client-Konsole überprüfen. |
| 19. Juni 2020 | [Einführung in Adobe Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/introduction-to-adobe-campaign-classic.html) | Campaign Classic | Erfahren Sie, wie Adobe Campaign Classic in das Adobe Digital Experience-Portfolio passt und welche Hauptfunktionen und -Funktionen es bietet. |
| 12. Juni 2020 | [Bereitstellen einer Ad-hoc-E-Mail-Versandvorlage](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/deploying-ad-hoc-email-delivery-template.html) | Campaign Classic | Informationen zum Bereitstellen einer Ad-hoc-E-Mail-Vorlage |
| 12. Juni 2020 | [Konfigurieren einer Versandvorlage](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/configuring-a-delivery-template.html) | Campaign Classic | Erfahren Sie, wie Sie eine E-Mail-Vorlage konfigurieren |
| 12. Juni 2020 | [Festlegen der Eigenschaften von Versandvorlagen](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/using-delivery-templates/setting-delivery-template-properties.html) | Campaign Classic | Erfahren Sie, wie Sie die Eigenschaften von E-Mail-Vorlagen festlegen |
| 12. Juni 2020 | [GPG-Schlüsselverwaltung](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management-overview.html) | Campaign Classic-/Systemsteuerung | Erfahren Sie, wie Sie ein öffentliches/privates GPG-Schlüsselpaar für die Datenverschlüsselung erstellen und installieren und wie Sie einen öffentlichen Schlüssel für die Datenverschlüsselung importieren und installieren. |
| 26. Juni 2020 | [Erste Schritte mit der Benutzeroberfläche in Adobe Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/getting-started/getting-started-with-the-ui.html) | Campaign Standard | In diesem Video erhalten Sie einen Überblick über die Benutzeroberfläche des Adobe Campaign Standards und erfahren, wie Sie zu wichtigen Funktionen und Kernfunktionen navigieren. |
| 26. Juni 2020 | [GPG-Schlüsselverwaltung](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/gpg-key-management-overview.html) | Campaign Standard/Systemsteuerung | Erfahren Sie, wie Sie ein öffentliches/privates GPG-Schlüsselpaar für die Datenverschlüsselung erstellen und installieren und wie Sie einen öffentlichen Schlüssel für die Datenverschlüsselung importieren und installieren. |

### Hilfe-Ressourcen

* Adobe Campaign Standard: [Hilfe-Center](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/campaign-standard-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-notes.html) – [Anleitungsvideos](https://docs.adobe.com/content/help/de-DE/campaign-standard-learn/tutorials/overview.html) – [Versionsplanung](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-planning.html) – [Neueste Aktualisierungen der Dokumentation](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Hilfe-Center](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/campaign-classic-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/release-notes/latest-release.html) – [Anleitungsvideos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) – [Neueste Aktualisierungen der Dokumentation](https://docs.adobe.com/content/help/de-DE/campaign-classic/using/documentation-updates.html)
* Control Panel von Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/de-DE/control-panel/using/control-panel-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/control-panel/using/release-notes.html) – Anleitungsvideos für [Campaign Standard](https://docs.adobe.com/content/help/de-DE/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html)/[Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Symbol](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Versionshinweise für Adobe Advertising Cloud.

### Neue Funktionen in [!UICONTROL Advertising Cloud Search] {#adcloud-search}

Aktualisiert am 8. **Juli 2020** für die Version vom 11. Juli.

| Funktion | Beschreibung |
| -----------| ---------- |
| [!UICONTROL Warnungen (Beta)] | Sie können jetzt eine schreibgeschützte, gefilterte Ansicht öffnen, die die Daten für jede Warnung enthält, und dann eine gefilterte Ansicht der Entitäten in der entsprechenden Ansicht der Kampagnenverwaltung öffnen, aus der Sie die Entitätsdatensätze bearbeiten können. |
| [!UICONTROL Portfolios] | Die Streichung von positionsbasierten Metriken in Beschränkungen und Portfolioeinstellungen wurde auf den 8. August verschoben. |

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
