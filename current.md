---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: release notes
last-update: February 2020
author: mfrei
translation-type: tm+mt
source-git-commit: d2b03da33ea1c49d683fc9486ae8b7d7bc59c87f

---


# Vorzeitiger Zugriff - Versionshinweise zu Adobe Experience Cloud - Februar 2020

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

>[!IMPORTANT]
>Diese Seite enthält Inhalte einer Vorabversion und kann vor der geplanten Veröffentlichung der Version geändert werden.

>[!NOTE]
>Abonnieren Sie [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bald verfügbare Versionen benachrichtigt zu werden. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Versionsdatum: 20. Februar 2020**

(Die spezifischen Produktveröffentlichungsdaten können variieren)

Neueste Aktualisierung: 10. Februar 2020

* [Systemstatus von Adobe](#status)
* [Benutzeroberfläche und Core Services von Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services und Mobile SDKs](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (Links zur Lösungshilfe)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (Links zur Lösungshilfe)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)

Suchen Sie nach der Hilfeseite? Siehe die [Adobe Experience Cloud-Dokumentation](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Systemstatus von Adobe {#status}

[!UICONTROL Der Adobe-Systemstatus] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe Cloud-Produkten und -Diensten. Weiter Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/).

**Neuigkeiten**

* Mit Ihrer Adobe-ID können Sie Ereignisbenachrichtigungen abonnieren, die auf Ihren Produkt-, Regions-, Ereignis- und Spracheinstellungen basieren. Benutzer, die ihre Abonnementeinstellungen konfigurieren, werden über relevante Produktereignisse und Wartungsereignisse benachrichtigt, sobald sie geöffnet, aktualisiert oder geschlossen werden. Weitere Informationen erhalten Sie unter [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Ab heute verfügbare neue Funktionen und Verbesserungen**

| Funktion | Beschreibung |
| -----------| ---------- |
| Schnelleres Bewusstsein für Produktereignisse | <ul><li>Informieren Sie sich 30 Tage im Voraus über die bevorstehende Wartungsarbeiten. Diese Funktion bietet mehr Vorlaufzeit, um die potenziellen Auswirkungen auf Ihren Geschäftsbetrieb abzuschätzen, und ermöglicht Ihnen bei Bedarf die Implementierung eines Abmilderungsplans.</li><li>Erweiterte Benachrichtigungen sind auf Web-/Mobil-/Tablet-Oberflächen und über E-Mail-Benachrichtigungen verfügbar.</li></ul> |
| Personalisieren Sie Ihr Erlebnis auf Grundlage der bevorzugten Sprache. | <ul><li>Wählen Sie eine bevorzugte Sprache für E-Mail-Benachrichtigungen. Die Funktion für die Selbstabonnement ist jetzt in neunzehn Sprachen verfügbar.</li></ul> |
| Verbesserte Benutzererfahrung bei Abonnements und Benachrichtigungen | <ul><li>Geben Sie für alle Produkte, für die Sie ein Abonnement abschließen möchten, die Voreinstellungen für Region und Ereignis in nur einem Klick an.</li><li>Werde benachrichtigt wenn _potenzielle_ Probleme zu _kleineren_ oder _größeren_ aufgeworfen werden.</li><li>Die Browserseite wird automatisch aktualisiert, wenn ein Produkt- oder Ereignisstatus aktualisiert wird.</li></ul> |

## Benutzeroberfläche und Core Services von Experience Cloud {#ecloud}

Neue Funktionen und Fehlerkorrekturen in der Benutzeroberfläche von Experience Cloud, einschließlich Verwaltung und Core Services (Kundenattribute, Zielgruppen, Auslöser, Cookies usw.).

**Fehlerbehebungen**

* **** Kundenattribute: Die Benutzeroberfläche &quot;Kundenattribute&quot;zeigt jetzt zusätzliche Status der in Target synchronisierten Profile an. (MCUI-10231)
* **** Auslöser Hauptdienst: Aufgrund der mangelnden Verwendung wurde der Tendenzwert &quot;Wahrscheinlichkeit einer Rückkehr in 30 Tagen&quot;beim Erstellen eines Auslösers vom Typ Abbruch entfernt. (MCUI-10056)

### Einheitliche Produktdomäne

Adobe aktualisiert die Domäne und die Kopfzeile der Benutzeroberfläche, um Ihre Nutzererfahrung in allen Experience Cloud-Anwendungen zu vereinheitlichen und zu verbessern. Diese simplen Aktualisierungen sollen die Benutzerfreundlichkeit vereinfachen und verbessern. Ihre aktuellen Workflows werden dadurch nicht geändert.

Zu den Aktualisierungen gehören:

* Neue URLs für Lösungen: `experience.adobe.com/<application name>`:
   * Dieses URL-Muster wird schließlich von allen Produkten übernommen. Im Laufe des Monats werden neue URLs hinzugefügt werden.
   * Browser support: Supported browsers include [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari], and [!DNL Opera] (latest versions). **Hinweis:** Obwohl die Experience Cloud-Oberfläche diese Browser unterstützt, unterstützen einzelne Lösungen möglicherweise nicht alle Browser. ([Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) unterstützt beispielsweise nicht [!DNL Opera] und [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) unterstützt nicht [!DNL Safari].)
   * (Nur [!DNL Safari]) Die Domänenänderung kann bei [!DNL Safari] zu Cookie-Problemen führen. Deselecting _Prevent cross-site tracking_ in the [!DNL Safari] Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Experience Cloud to function on this new domain.
* Einfacherer Wechsel zwischen Ihren Organisationen oder zu einer anderen Anwendung.
* Verbesserte Produkthilfe: [!UICONTROL Experience League] ist in das Produkt integriert, sodass bei einer Hilfesuche auch Ergebnisse aus Community-Foren und Videos berücksichtigt werden. Diese Änderung vereinfacht den Zugriff auf weitere Inhalte und hilft Ihnen, Experience Cloud optimal zu nutzen. Zusätzlich können Sie unter **[!UICONTROL Hilfe]** > **[!UICONTROL Feedback]** Probleme melden oder Ihre Ideen mit Adobe teilen.
* Verbesserte Benachrichtigungen: Das Dropdown-Menü [!UICONTROL Benachrichtigungen] enthält jetzt zwei Registerkarten: eine für Ihre eigenen Produktbenachrichtigungen und eine für globale Produktankündigungen.

**Hinweis:** Die [!UICONTROL Feed]-Seite wird im Januar 2020 eingestellt. Innerhalb des Produkts finden Sie eine Benachrichtigung zur Einstellung.

Die Produktdokumentation finden Sie auf der [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html)-Seite.

## Experience Platform {#platform}

Versionshinweise für Experience Platform, Experience Platform Launch, Identity Service und Sicherheitsbulletins.

* [Experience Platform – Versionshinweise](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/security.html) (Alle Adobe-Produkte)

### Experience Platform Launch {#launch}

Versionshinweise und die Produktdokumentation finden Sie unter [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## Mobile Services und Mobile SDKs {#mobile}

**4. Februar 2020: Version 4.19.0**

In dieser Version wurde folgende Aktualisierung vorgenommen:

**** Lebenszyklus: Es wurde eine neue API hinzugefügt, `pauseCollectingLifecycleData`um die Daten zur anormalen Sitzungslänge zu verringern, die von einigen alten iOS-Geräten gemeldet wurden.

## [!DNL Analytics] {#analytics}

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics](#aa-features) (Aktualisiert am 21. Januar 2020)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [AppMeasurement](#appm)

Eine Produktdokumentation finden Sie auf der [Startseite der Adobe Analytics-Hilfe](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics {#aa-features}

<!--* **Support for multiple report suites in Workspace:** You can now bring in data from multiple report suites into a single project to view side by side. Beginning on Feb 20, 2020, the feature will roll out to all customers over the course of several weeks. [Learn more...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)-->
* **Neue** Workspace-Vorlage für Organisationen, die geräteübergreifende Analysen verwenden:Diese Vorlage zeigt, wie effektiv CDA beim Zusammenfügen von Besuchen ist, und informiert Sie über CDA-exklusive Dimensionen und Metriken. Eine Report Suite, die CDA verwendet, ist erforderlich. Weitere Informationen finden Sie unter [Einrichten von geräteübergreifenden Analysen](https://docs.adobe.com/content/help/en/analytics/components/cda/cda-setup.html) .
* **** Die Latenz der CDA-Stiftung für Organisationen, die das private Diagramm verwenden, wird auf einen Tag reduziert: Die Funktion &quot;Private Graph&quot;wurde verbessert, um die Wartezeit bei der Diagrammerstellung von einem wöchentlichen Batch-Prozess auf ein täglich aktualisiertes Diagramm zu reduzieren, sodass CDA-Kunden auf aktuellere Identitätsdiagramme und Links zugreifen können.
* **** Labs (Technologievorschau): Mit dieser neuen Analytics-Funktion können Sie neue Funktionsprototypen in der Produktion testen und Adobe wertvolles Feedback geben. [Mehr Info...](https://docs.adobe.com/content/help/en/analytics/analyze/tech-previews/overview.html)
* **Neue Hotkeys in Workspace:**<ul><li>Alle Bereiche reduzieren/erweitern: `alt + m`</li><li>Bereich &quot;Aktiv reduzieren/erweitern&quot;: `alt + ctrl + m`</li><li>Links suchen: `ctrl + /`</li><li>Zum nächsten Bereich wechseln: `alt + Right Key`</li><li>Zum vorherigen Bereich wechseln: `alt + Left Key`</li></ul>[Mehr Info...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/fa-shortcut-keys.html)
* **Weitere Verbesserungen am Arbeitsbereich:**<ul><li>Wenn ein Bedienfeld oder eine Visualisierung in [!UICONTROL Workspace]abgelegt wird, wechselt die linke Leiste automatisch zu Komponenten, um einen nahtlosen Arbeitsablauf zu gewährleisten.</li><li>Vorlagenkomponenten können nun aktiviert werden (z. B. markiert, als Favorit markiert, genehmigt).</li><li>Gefilterte Metrik- und Segmentlisten bieten die `+` Schaltfläche, um eine neue Komponente hinzuzufügen, wenn Sie nicht genau wissen, was Sie benötigen.</li></ul>
* Der **Workspace-Debugger** wurde dem Menü &quot;Hilfe&quot;hinzugefügt, sodass Sie ihn nahtloser zum Debuggen von Workspace-Anforderungen aktivieren können. [Mehr Info...](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/reporting-tricks.md)
* **** Chrominbasierter Microsoft Edge-Browser: Diese Version enthält Änderungen zur Erkennung des Chrome-basierten Microsoft Edge-Browsers (Version 79 und höher) zu Berichtszwecken.

#### Fehlerkorrekturen

* Es wurde ein Problem mit der Segment-Benutzeroberfläche behoben, bei dem festgestellt wurde, dass [!UICONTROL Marketingkanal] -Dimensionen mit [!UICONTROL Data Warehouse]kompatibel waren, obwohl sie in Wirklichkeit nicht verfügbar waren. In Zukunft werden diese Dimensionen im [!UICONTROL Segmentaufbau] nicht mehr als [!UICONTROL Data Warehouse] -kompatibel angezeigt. (AN-202297)
* Es wurde ein Problem mit dem Namen eines veröffentlichten Segments behoben, das in Analytics aktualisiert wurde und nicht innerhalb von 24 Stunden in Audience Manager aktualisiert wurde. (AN-199974)

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Neue Adobe Analytics-Domäne | 18. Dezember 2019 | `https://experience.adobe.com/analytics.`<br>** Am 16. Januar 2020 begann Adobe Analytics mit der Umstellung auf eine neue Domäne - **Hinweis: Diese Änderung gilt für alle Benutzer, die mit ihrer Adobe ID oder Enterprise ID auf Analytics zugreifen.<ul><li>Diese Änderung kann zu Problemen mit Cookies führen, wenn Analytics in Safari geladen wird. Deselecting _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. Sie können problemlos andere Browser verwenden, da dies nur Safari-Benutzer betrifft.</li><li>Die Domänenänderung kann dazu führen, dass [!UICONTROL Activity Map] bei einigen Kunden [in bestimmten Fällen](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html) nicht mehr funktioniert.</li></ul> |
| End of Life - veraltete Analytics-APIs | 9. Januar 2020 | Im November 2020 werden die folgenden Legacy-API-Dienste von Analytics eingestellt. Aktuelle Integrationen, die mit diesen Diensten erstellt wurden, funktionieren dann nicht mehr. <ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Wir haben [FAQ zu Legacy API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) bereitgestellt, die Ihnen bei der Beantwortung Ihrer Fragen helfen und Anleitungen zum weiteren Vorgehen geben sollen. API-Integrationen, die diese Dienste nutzen, können zu den [Analytics-REST-APIs 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) oder den [Analytics-APIs 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) migrieren. Ältere OAuth-Konten können zu einem [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-Integrationskonto migrieren, das für den Zugriff auf sowohl Analytics-APIs 1.4 als auch Analytics-APIs 2.0 verwendet werden kann. |
| Option **[!UICONTROL Archiv anzeigen]** wird eingestellt | 30. Oktober 2019 | Die Option **[!UICONTROL Archiv anzeigen]** im Dashboard-Manager (**[!UICONTROL Komponenten > Dashboards]**) wird im Januar 2020 eingestellt. |
| Option **[!UICONTROL IP-Anmeldebeschränkungen erzwingen]** wird eingestellt | 30. Oktober 2019 | Die IP-Whitelist-Funktionalität (**[!UICONTROL IP-Anmeldebeschränkungen erzwingen]**) unter **[!UICONTROL Admin > Unternehmenseinstellungen > Sicherheit]** wird im Januar 2020 eingestellt. |
| Ende der Unterstützung für TLS 1.1 | 3. Oktober 2019 | Ab dem 31. März 2020 unterstützt Adobe Analytics TLS 1.1 nicht mehr. Diese Änderung ist Teil unserer laufenden Bemühungen, höchstmögliche Sicherheit von Kundendaten zu gewährleisten. |
| FTP-Broker in San Jose endet für London und Singapur | Juli 2020 | Für Kunden in London und Singapur wird die Datenvermittlung zwischen den beiden Städten und dem Rechenzentrum in San Jose ([ftp.omniture.com](ftp://ftp.omniture.com/)) nicht mehr unterstützt.<br/><ul><li>Für London verwenden Sie [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Für Singapur verwenden Sie [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Bevorstehende Änderung bezüglich des Felds `createDate` für Analytics-Benutzer | 30. August 2019 | Im Oktober oder November 2019 wurde das Feld `createDate` für Analytics-Benutzer von der US Pacific Time auf einen korrekt formatierten Datums-/Uhrzeitwert mit Zeitzoneninformationen aktualisiert.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Siehe [Versionshinweise zu AppMeasurement für JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Version 2.18.0 wurde am 13. Februar 2020 veröffentlicht.

## Audience Manager {#aam}

Korrekturen und Funktionen, die Audience Manager hinzugefügt wurden.

### Neue in Audience Manager verfügbare Funktionen, Verbesserungen und Fehlerbehebungen {#aam-features}

| Funktion | Beschreibung |
|----|----|
| [Berichte zur Aktivitätsnutzung](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/administration/activity-usage-reporting.html) | Der Bericht[!UICONTROL  zur ]Aktivitätsauslastung hilft Ihnen, die Aktivitätsnutzung Ihrer Audience Manager-Instanz anzuzeigen und zu verfolgen, und gibt Ihnen eine klare Vorstellung davon, wie Ihre Aktivitätsnutzung mit Ihrer vertraglichen Verpflichtung verglichen wird. |

### Fehlerbehebungen und Verbesserungen {#aam-fixes-and-improvements}

* Es wurde ein Fehler behoben, der dazu führte, dass die Benutzeroberfläche für die Auswahl integrierter Konten durch die Zielerstellung beschädigt wurde (AAM-52414).
* Es wurde ein Fehler behoben, der dazu führte, dass die Benutzeroberfläche beim Navigieren durch den Erstellungsfluss Algorithmischer Modelle (AAM-37942) beschädigt wurde.
* Es wurde ein Fehler behoben, der dazu führte, dass beim Speichern von Datenexportsteuerelementen für neue oder vorhandene Ziele die Auswahl &quot;Datenexport&quot;für Kunden, die die Adobe Experience Platform-Integration (AAM-52814) verwenden, nicht gespeichert wurde.
* Es wurde ein Fehler behoben, der dazu führte, dass Empfehlungen zu Eigenschaften von Drittanbietern für Eigenschaften mit Pipe-Zeichen (`|`) im Namen (AAM-51635) nicht korrekt funktionierten.
* Verbesserungen an der Zugänglichkeit in der gesamten Benutzeroberfläche.

## Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktversionen

* **Cloud Manager 2020.2.0**

   Cloud Manager 2020.2.0 vereinfacht die Verwaltung von Sandboxen für den Self-Service für Adobe Experience Manager als Cloud-Dienst.

   Siehe [Versionshinweise](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html).

### Selbsthilfe

* **Übungen zu AEM als Cloud-Dienst**

   Erste Schritte mit den [Tutorials für AEM als Cloud-Dienst](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/overview.html).

* **AEM Forms-API für interaktive Kommunikationsstapel**

   Mit der Stapel-API der interaktiven Kommunikation mit AEM Forms können Kunden mehrere interaktive Kommunikationen erstellen, entweder automatisch oder auf Abruf. Kunden können Druck- und Webausgabe gleichzeitig generieren.
Siehe [Generieren mehrerer interaktiver Kommunikation mit der Stapel-API](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/generate-multiple-interactive-communication-using-batch-api.html).

* **Unterstützte Plattformen für AEM Forms on JEE**

   Unterstützung für Oracle 19c für AEM Forms on JEE-Kunden hinzugefügt.
Siehe [Unterstützte Plattformen für AEM Forms on JEE](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/jee-installation/aem-forms-jee-supported-platforms.html).

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

### Campaign Classic 19.2.3

Fehlerbehebungen und Verbesserungen finden Sie unter [Adobe Campaign Classic – Versionshinweise](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html).

### Campaign Standard 20.1

Fehlerbehebungen und Verbesserungen finden Sie unter [Adobe Campaign Standard – Versionshinweise](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html).

### Zusätzliche Ressourcen

* Adobe Campaign Standard: [Dokumentation](https://helpx.adobe.com/support/campaign/standard.html) – [Versionshinweise](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) – [Versionsplanung](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Dokumentation](https://helpx.adobe.com/support/campaign/classic.html) – [Versionshinweise](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Control Panel von Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Aktualisiert: 10. Februar 2020, für die Version vom 8. Februar

| Ansicht | Funktion |
|------|---------|
| Portfolios | Sie können jetzt Yahoo! Japan Display Network (YDN)-Kampagnen zu Portfolios hinzufügen, um die Kampagnenbudgets und Gebote auf Anzeigengruppenebene zu optimieren. Das gleiche Gebot wird auf alle Anzeigen einer Anzeigengruppe angewendet. Daten für YDN-Kampagnen sind in den Simulationen für das Portfolio enthalten. |
| Suche > Bulksheets | Sie können jetzt mithilfe von Bulksheets responsive Suchanzeigen (RSAs) von Google erstellen, bearbeiten und löschen. Previously, support was available only through the standard campaign management interface at **[!UICONTROL Search]** > **[!UICONTROL Campaigns]** |
| Suche > Kampagnen, Berichte | The Google Ads prominence metrics `Impr. (Abs. Top) %` and `Impr. (Top) %` are now available in all basic reports and entity-level campaign management views except for those for shopping product groups, in the [!UICONTROL Campaign Daily Impression Share] and [!UICONTROL Keyword Daily Impression Share] reports, and in the labels and constraints views. |

## [!DNL Magento] {#magento}

Versionshinweise zu Magento finden Sie unter:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)
