---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: d92cffebc2db7e6a6d7d7b531390b6e307b2943e

---


# Vorzeitiger Zugriff - Versionshinweise zu Adobe Experience Cloud - Januar 2020

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

>[!IMPORTANT]
>Diese Seite enthält Inhalte vor der Veröffentlichung und kann vor der geplanten Version des jeweiligen Produkts geändert werden.

>[!NOTE]
>Abonnieren Sie [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bald verfügbare Versionen benachrichtigt zu werden. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Releasedatum: 16. Januar 2020**

* [Adobe-Systemstatus](#status)
* [Benutzeroberfläche und Hauptdienste von Experience Cloud](#ecloud)
* [Experience Platform](#platform)
* [Mobile Services und Mobile SDKs](#mobile)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (Links zur Lösungshilfe)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (Links zur Lösungshilfe)
* [!DNL Advertising Cloud](#adcloud)

Suchen Sie nach der Hilfeseite? Siehe die [Adobe Experience Cloud-Dokumentation](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Adobe System Status {#status}

[!UICONTROL Der Adobe-Systemstatus] enthält detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Adobe Cloud-Produkten und -Services-Ausfällen, Störungen und Wartungsereignissen. Sehen Sie sich das unter [status.adobe.com](https://status.adobe.com/)an.

**Neuigkeiten**

* Mit Ihrer Adobe-ID können Sie Ereignisbenachrichtigungen abonnieren, die auf Ihren Produkt-, Regions- und Ereignisvoreinstellungen basieren. Benutzer, die ihre Abonnementeinstellungen konfigurieren, werden nur über relevante Produktereignisse und Wartungsereignisse benachrichtigt, sobald sie geöffnet, aktualisiert oder geschlossen werden. Beginnen Sie mit [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Neue Funktionen und Verbesserungen heute verfügbar**

| Funktion | Beschreibung |
| -----------| ---------- |
| Proaktive E-Mail-Benachrichtigungen abonnieren | <ul><li>Unterstützung für Experience Cloud, Creative Cloud, Document Cloud, Adobe Experience Platform und Adobe Services</li><li>Unterstützung für Voreinstellungen für Regionen und Ereignistypen</li></ul> |
| Benachrichtigungseinstellungen verwalten | <ul><li>Bearbeiten und Speichern von Voreinstellungen für Benachrichtigungen jederzeit möglich</li><li>Abmelden von Benachrichtigungen jederzeit möglich</li></ul> |
| Personalisierte und schnellere E-Mail-Zustellung | <ul><li>Ereignisbenachrichtigungen werden gesendet, sobald Ereignisse geöffnet, aktualisiert oder geschlossen werden</li><li>Empfang ausschließlich der relevanten Ereignisbenachrichtigungen, die Ihren konfigurierten Voreinstellungen entsprechen</li><li>Empfangen lokalisierter Benachrichtigungen je nach der in Ihren Kontovoreinstellungen konfigurierten Sprache</li></ul> |
| Personalisierte In-Produkt-Benachrichtigungen | <ul><li>Ereignisse, die Ihren Benachrichtigungseinstellungen und Produktberechtigungen entsprechen, werden im Bereich &quot;Mitteilungen&quot;angezeigt</li></ul> |

## Experience Cloud interface and core services {#ecloud}

Neue Funktionen und Fehlerbehebungen in der Benutzeroberfläche der Experience Cloud, einschließlich Verwaltung und Hauptdienste (Kundenattribute, Zielgruppen, Auslöser, Cookies usw.).

### Einheitliche Produktdomäne

Adobe aktualisiert die Domäne und die Kopfzeile der Benutzeroberfläche, um Ihre Erfahrung in allen Experience Cloud-Anwendungen zu vereinheitlichen und zu verbessern. Diese Erweiterungen sollen Ihnen das Erlebnis auf kleine, aber wichtige Weise vereinfachen. Diese Verbesserungen ändern Ihre aktuellen Arbeitsabläufe nicht.

Zu den Updates gehören:

* Neue Lösungs-URLs: `experience.adobe.com/<application name>`:
   * Alle Produkte übernehmen dieses URL-Muster. Suchen Sie nach neuen URLs, die im Laufe des Monats wirksam werden.
   * Unterstützte Browser: [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari]und [!DNL Opera] (neueste Versionen).
   * ([!DNL Safari] Nur) Die Domänenänderung kann zu Cookie-Problemen führen [!DNL Safari]. Wenn Sie die _Option &quot;Site-übergreifendes Tracking_ verhindern&quot;in den [!DNL Safari] Datenschutzeinstellungen deaktivieren, werden domänenübergreifende Cookies (und alle Site-übergreifenden Erlebnisse) aktiviert und die Funktion der Experience Cloud in dieser neuen Domäne ermöglicht.
* Einfacherer Wechsel zwischen Ihren Organisationen oder zu einer anderen Anwendung.
* Verbesserte Produkthilfe: Die [!UICONTROL Experience League] ist in das Produkt integriert, sodass bei einer Hilfesuche auch Ergebnisse aus Community-Foren und Videoinhalten berücksichtigt werden. Diese Änderung vereinfacht den Zugriff auf weitere Inhalte und hilft Ihnen, das Beste aus Experience Cloud zu machen. Klicken Sie außerdem auf **[!UICONTROL Hilfe]**>**[!UICONTROL  Feedback]** , um Probleme zu melden oder Ihre Ideen mit Adobe zu teilen.
* Verbesserte Benachrichtigungen: Das Dropdownmenü [!UICONTROL Benachrichtigungen] enthält jetzt zwei Registerkarten: eine für Ihre eigenen Produktbenachrichtigungen und eine für globale Produktankündigungen.

**** Hinweis: Die [!UICONTROL Feed] -Seite wird im Januar 2020 eingestellt. Innerhalb des Produkts finden Sie eine Benachrichtigung zur Einstellung.

Die Produktdokumentation finden Sie auf der [Seite zu Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Cookies in Experience Cloud

Adobe passt die `same-site` Einstellung für Cookies an, um sich auf Änderungen vorzubereiten, die Chrome in Chrome 80 vornehmen wird (Veröffentlichung im Februar 2020).

Sie müssen keine Änderungen vornehmen, es sei denn, Sie verwenden einen CNAME für die Datenerfassung durch Erstanbieter, sondern verwenden diesen CNAME für mehrere Domänen (freundliche Drittanbieter-Domänen) und Sie verwenden nicht den Experience Cloud(Besucher)-ID-Dienst. Mit der Chrome 80-Version gibt Chrome den Analytics-Besucher-ID-Cookies automatisch den Wert &quot;GleichSite&quot; `Lax,` , der deren Verwendung auf Ihren anderen Domänen verhindert. Wenn Sie Ihren CNAME auch weiterhin domänenübergreifend verwenden möchten, wenden Sie sich an den Adobe-Kundendienst und fordern Sie an, dass der gleiche Site-Wert für Ihren CNAME in `None.`

Beachten Sie, dass Adobe empfiehlt, für jede Ihrer Domänen einen separaten CNAME zu verwenden, unabhängig davon, ob Sie den Experience Cloud ID-Dienst verwenden oder nicht.

[Mehr…](https://medium.com/adobetech/adobe-experience-cloud-cookie-updates-for-google-chrome-19ad67cf1598)

## Experience Platform {#platform}

Versionshinweise für Experience Platform, Experience Platform Launch, Identity Service und Sicherheitsbulletins.

* [Experience Platform – Versionshinweise](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/security.html) (Alle Adobe-Produkte)

### Experience Platform Launch {#launch}

Versionshinweise und die Produktdokumentation finden Sie unter [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## Mobile Services and Mobile SDKs {#mobile}

16\. Januar 2020: Version 4.18.0

* Akquise - Es wurde eine neue API zur Unterstützung `Analytics.processGooglePlayInstallReferrerUrl(final String url)`der [!DNL Google Play] Installieren von Referrer-APIs hinzugefügt.

Weitere Informationen zu den APIs für die Installation der verweisenden Stelle finden Sie unter Verwenden von InstallBroadcast [noch? Wechseln Sie bis zum 1. März 2020](https://android-developers.googleblog.com/2019/11/still-using-installbroadcast-switch-to.html)zur Play Referrer-API.

## [!DNL Analytics] {#analytics}

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics](#aa-features)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [AppMeasurement](#appm)

Eine Produktdokumentation finden Sie auf der [Startseite der Adobe Analytics-Hilfe](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics {#aa-features}

| Funktion | Beschreibung |
| -----------| ---------- | 
| Analysis Workspace - Freiform Table Builder | Wenn Sie den Tabellenaufbau aktiviert haben, können Sie Tabellen mit vielen Dimensionen, Unterteilungen, Metriken und Segmenten per Drag &amp; Drop erstellen, um komplexere Geschäftsfragen zu beantworten. Daten werden nicht sofort aktualisiert. Stattdessen werden nach dem Klicken auf **[!UICONTROL Erstellen]**Updates angezeigt, sodass Sie Zeit sparen, sobald Sie wissen, welche Tabelle erstellt werden soll. Zusätzlich bietet diese Funktion:<ul><li>**Vorschau**: Sie können eine Vorschau des Tabellenformats anzeigen, bevor Sie Zeit zum Rendern echter Daten verbringen.</li><li>**Flexible Zeilen- und Aufschlüsselungseinstellungen**: Sie können Ihre Zeilen- und Unterteilungsebenen für jede Dimensionzeile festlegen. Zuvor wurden in Workspace Standardwerte festgelegt, die erst nach Rückgabe der Daten geändert werden konnten.</li><li>**Aufschlüsselung nach Position**: Sie können Dimensionszeilen so einstellen, dass sie immer nach Position _und nicht_ nach einem bestimmten Element _(Standard)_ aufgeschlüsselt werden.</li><li>**Manuelle statische Zeilenreihenfolge**: Sie können statische Zeilen manuell sortieren, damit die Tabellenzeilen genau nach Bedarf angezeigt werden. Zuvor konnten statische Zeilen nur nach einer Metrikspalte oder alphabetisch sortiert werden.</li></ul>Die zugehörige Dokumentation wird veröffentlicht, wenn diese Funktion später im Januar veröffentlicht wird. |
| Neue [!UICONTROL Dimension &quot;Identifizierter Status] &quot;für geräteübergreifende Analysen (CDA) | Wir fügen eine neue Dimension namens &quot; [!UICONTROL Identifizierter Staat] &quot;zu Virtual Report Suites von CDA hinzu. Die Dimension verfügt über zwei mögliche Werte: _Identifiziert_ und _Nicht identifiziert_. _Identifiziert_ bedeutet, dass die Person durch das Gerätediagramm identifiziert wurde. _Nicht identifiziert_ bedeutet, dass die Person nicht durch das Gerätediagramm identifiziert wurde.<br>Das bedeutet, dass CDA-Benutzer jetzt berechnete Metriken erstellen können, z. B. die [!UICONTROL Gerätediagrammabdeckung], in der beschrieben wird, wie viele Personen in der Virtual Report Suite vom Gerätediagramm bekannt sind. Diese Metrik ist hilfreich, um CDA-Komprimierungsraten zu beheben. Wenn nur wenige Personen identifiziert werden, ist der Grad der Nähung gering. |
| VRS-Unterstützung in Data Warehouse API | Virtual Report Suites stehen jetzt über die Data Warehouse-API zur Verfügung. Zuvor waren sie nur über die Data Warehouse-Benutzeroberfläche verfügbar. Bei Verwendung der Data Warehouse-API können Sie jetzt Virtual Report Suites anzeigen und abfragen, allerdings nur, wenn die auf eine Virtual Report Suite angewendeten Segmente mit Data Warehouse kompatibel sind. |
| Privacy Service API: CCPA | Der California Consumer Privacy Act (CCPA) erweitert die Datenschutzrechte und den Verbraucherschutz für Einwohner von Kalifornien, USA. Dieses Gesetz trat am 1. Januar 2020 in Kraft.<br><br/>Der CCPA bietet neue Datenschutzrechte, mit denen Verbraucher beispielsweise ihre personenbezogenen Daten einsehen und löschen oder herausfinden können, ob (und an wen) ihre Daten verkauft oder weitergegeben wurden, und mit denen sie dem Verkauf ihrer personenbezogenen Daten widersprechen können.<br><br/>Der Datenschutzdienst unterstützt Anfragen, sich vom Verkauf personenbezogener Daten abzumelden.<br><br/>Der Datenschutzdienst war früher der GDPR-Dienst und behält alle vorherigen Funktionen, jetzt erweitert, um CCPA zu unterstützen.<br/><br/>[CCPA in Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Übersicht über den Datenschutzdienst](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |

#### Fehlerbehebungen

* Es wurde ein Problem behoben, bei dem Warnmeldungen nicht an Telefonnummern in Ägypten gesendet wurden. (AN-197079)
* Es wurden mehrere Probleme mit der [!DNL DFA Data Connector]Variablen behoben. (AN-193281, AN-193075, AN-193484, AN-193737)
* [!UICONTROL Reports &amp; Analysen]: Es wurde ein Problem behoben, bei dem der Produktumrechnungstrichterbericht abgeschnitten und unklare Zahlen angezeigt wurden. (AN-186901)
* Es wurde ein Fehler behoben, der verhinderte, dass Benutzer Report Suites in Workspace-Projekten wechseln konnten, die auf Report Suites mit der neuen Classifications-Architektur basieren. (AN-199076)
* Es wurde ein Fehler behoben, der dazu führte, dass die Funktion [!UICONTROL Kumulative] in [!UICONTROL berechneten Metriken] nicht ordnungsgemäß funktionierte. (AN-184257)

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Neue Adobe Analytics-Domäne | 18. Dezember 2019 | Am 16. Januar 2020 beginnt Adobe Analytics mit der Umstellung auf eine neue Domäne - `https://experience.adobe.com/analytics.`<br>**Hinweis **: Diese Änderung gilt für alle Benutzer, die mit ihrer Adobe ID oder Enterprise ID auf Analytics zugreifen.<ul><li>Die Domänenänderung kann beim Laden von Analytics in Safari zu Cookie-Problemen führen. Unchecking _Prevent cross-site tracking_ in the Safari Privacy Preferences enables cookies across domains (and all cross-site experiences), and allows Analytics to function on this new Adobe Experience Cloud domain. Sie können andere Browser ohne Probleme verwenden, da dies nur Safari-Benutzer betrifft.</li><li>Die Domänenänderung kann dazu führen, dass [!UICONTROL Activity Map] bei einigen Kunden [in bestimmten Fällen](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html)nicht mehr funktioniert.</li></ul> |
| Ende der Laufzeit - Analytics-APIs mit veralteter Version | 9. Januar 2020 | Im November 2020 werden die folgenden Analytics Legacy-API-Dienste bis zum Ende ihrer Laufzeit beendet und beendet. Aktuelle Integrationen, die mit diesen Diensten erstellt wurden, funktionieren nicht mehr. <ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Wir haben eine FAQ[ zu ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email)Legacy API EOL zur Verfügung gestellt, die Ihnen bei der Beantwortung Ihrer Fragen helfen und Anleitungen zum weiteren Vorgehen geben soll. API-Integrationen, die diese Dienste verwenden, können zu den Analytics-REST-APIs[ von ](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email)1.4 oder den Analytics-APIs[von ](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email)2.0 migrieren. Ältere OAuth-Konten können zu einem [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-Integrationskonto migrieren, das für den Zugriff auf die Analytics-APIs 1.4 und 2.0 und Analytics-APIs verwendet werden kann. |
| Option **[!UICONTROL Archiv anzeigen]** wird eingestellt | 30. Oktober 2019 | Die Option **[!UICONTROL Archiv anzeigen]** im Dashboard-Manager (**[!UICONTROL  Komponenten > Dashboards]**) wird im Januar 2020 eingestellt. |
| Option **[!UICONTROL IP-Anmeldebeschränkungen erzwingen]** wird eingestellt | 30. Oktober 2019 | Die IP-Whitelist-Funktionalität (**[!UICONTROL IP-Anmeldebeschränkungen erzwingen]**) unter **[!UICONTROL  Admin > Unternehmenseinstellungen > Sicherheit]** wird im Januar 2020 eingestellt. |
| Ende der Unterstützung für TLS 1.1 | 3. Oktober 2019 | Ab dem 31. März 2020 unterstützt Adobe Analytics TLS 1.1 nicht mehr. Diese Änderung ist Teil unserer laufenden Bemühungen, höchstmögliche Sicherheit von Kundendaten zu gewährleisten. |
| FTP-Broker in San Jose endet für London und Singapur | Juli 2020 | Für Kunden in London und Singapur wird die Datenvermittlung zwischen den beiden Städten und dem Rechenzentrum in San Jose ([ftp.omniture.com](ftp://ftp.omniture.com/)) nicht mehr unterstützt.<br/><ul><li>Für London verwenden Sie [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Für Singapur verwenden Sie [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Bevorstehende Änderung bezüglich des Felds `createDate` für Analytics-Benutzer | 30. August 2019 | In October or November 2019, the `createDate` field for Analytics users was updated from US Pacific Time to a correctly formatted date and time value with time zone information.(AN-183468) |

### [!DNL AppMeasurement] {#appm}

Siehe [Versionshinweise zu AppMeasurement für JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Korrekturen und Funktionen, die Audience Manager hinzugefügt wurden.

### Neue in Audience Manager verfügbare Funktionen, Verbesserungen und Fehlerbehebungen {#aam-features}

| Funktion | Beschreibung |
| -----------| ---------- |
| [California Consumer Privacy Act (CCPA) - Überarbeitung der Support- und Datenschutzdokumentation](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html) | Das [California Consumer Privacy Act (CCPA)](https://www.caprivacy.org/about), das am 1. Januar 2020 in Kraft getreten ist, verleiht kalifornischen Bürgern neue Rechte in Bezug auf ihre persönlichen Daten und erlegt bestimmten Einrichtungen, die in Kalifornien Geschäfte tätigen, Datenschutzpflichten auf. <br><br> Audience Manager unterstützt Sie bei der Erfüllung Ihrer Verpflichtungen aus Datenschutzbestimmungen durch Datenschutzwerkzeuge wie den [Adobe Experience Platform Privacy Service](https://www.adobe.io/apis/experienceplatform/home/services/privacy-service.html) für den Datenzugriff und das Löschen von Anforderungen. <br><br> Wir haben den aktuellen [Opt-out-Verwaltungsprozess](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#opt-out-requests) aktualisiert, um die Abmeldung einer beliebigen deklarierten ID (z.B. CRM-ID) einzuschließen. Bei Ausschluss durch deklarierte ID werden die deklarierte ID und das zuletzt verknüpfte Gerät aus der Datenerfassung von Audience Manager ausgeschlossen. Ausschluss-Anfragen senden jetzt auch Nicht-Segment-Anfragen an [Zielpartner](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy-requests.html#aam-partners-with-unsegmentation) , die diese Funktion unterstützen, sowohl in Batch- als auch in Echtzeit. <br><br> Darüber hinaus haben wir unsere Dokumentation zur [Datensicherheit](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-security.html), zum [Datenschutz](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/data-privacy.html)und zur [Datenverwaltung](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-governance.html) überarbeitet, um Ihnen die Informationen zu erleichtern, die zur Einhaltung der oben genannten Vorschriften erforderlich sind. |

### Fehlerbehebungen und Verbesserungen {#aam-fixes-and-improvements}

* Es wurde ein Problem im Arbeitsablauf zum [!UICONTROL Erstellen eines Ziels] behoben, bei dem bei Auswahl von **[!UICONTROL integrierten Plattformen]**als[!UICONTROL Kategorie]der Abschnitt[!UICONTROL Grundlegende Informationen]ausgeblendet wurde und der Workflow nicht abgeschlossen werden konnte. (AAM-52397, AAM-52414)
* We fixed a bug where the [!UICONTROL Create/edit] destinations page would not load in the Apple Safari and Mozilla Firefox browsers. (AAM-51784)

## Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktwartung

* **AEM 6.5.3.0** AEM 6.5 Service Pack 3.0 (6.5.3.0, 12. Dezember 2019) ist ein wichtiges Update, das wichtige Fehlerbehebungen von Kunden enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.5, April 2019, veröffentlicht wurden.
   * [Versionshinweise](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.7.0**

   AEM 6.4, Service Pack 7.0 (6.4.7.0, 12. Dezember 2019 veröffentlicht) ist ein wichtiges Update, das wichtige Fehlerbehebungen von Kunden enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.4, April 2018 veröffentlicht wurden.
   * [Versionshinweise](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.7**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 7 (6.3.3.7 veröffentlicht am 12. Dezember 2019) ist ein wichtiges Update, das wichtige Fehlerbehebungen von Kunden enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.3 im April 2017 veröffentlicht wurden.
   * [Versionshinweise](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Desktop App 2.0.1.1**

   AEM Desktop App 2.0.1.1 bietet ein Update für Single Sign-On mit Okta und die Möglichkeit, den Speicherort temporärer Dateien in den Voreinstellungen anzugeben. Die Unterstützung für AEM 6.3.x wird für die Desktop-App 2.x mit dieser Version nicht mehr unterstützt.
   * [Versionshinweise](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Adobe Asset Link 1.1 beendet Unterstützung für AEM 6.3.x**

   Die Unterstützung für AEM 6.3.x wird in Adobe Asset Link seit April 2019 nicht mehr unterstützt. Adobe Asset Link 1.1 entfernt ab dem 13. Januar 2020 die Unterstützung für AEM 6.3.x.
   * [Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link.html)

### Produktversionen

* **NEU:AEM als Cloud-Dienst**

   [Adobe Experience Manager](https://www.adobe.com/marketing/experience-manager.html) (AEM) ist jetzt als Cloud-Dienst verfügbar.

   * [Einführung](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/overview/introduction.html)
   * [Versionsinformationen](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/home.html)
   * [Dokumentation](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)

* **Dienst zur automatisierten Formularumwandlung**

   Der automatisierte Forms-Konvertierungsdienst, der Dienst zum automatischen Konvertieren von PDF-Formularen in schöne, für Mobilgeräte geeignete HTML-Formulare, steht seit dem 12. Dezember 2019 für den allgemeinen Gebrauch zur Verfügung.

   * [Einführung](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html)
   * [Konfigurieren des Dienstes](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/configure-service.html)
   * [Konvertieren von PDF-Formularen in adaptive Formulare](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/convert-existing-forms-to-adaptive-forms.html)

### Selbsthilfe

* **Vorschau von 3D-Assets**

   AEM 6.5 unterstützt das Hochladen, Bereitstellen und interaktive Anzeigen einer Vorschau von 3D-Assets als Teil des Authoring-Prozesses. Der interaktive 3D-Viewer ist auf der Seite mit den Asset-Details in AEM verfügbar. Der Viewer enthält u. a. eine Sammlung interaktiver Kamerasysteme, mit denen Sie das 3D-Asset drehen, zoomen und schwenken können.
Siehe [Anzeigen einer Vorschau für 3D-Assets](https://docs.adobe.com/content/help/en/experience-manager-65/assets/using/previewing-3d-assets.html).

* **Kernkomponenten**

   Core Components 2.8.0, with numerous fixes, is now available along with [authoring documentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) and [developer details and project download available on GitHub](https://github.com/adobe/aem-core-wcm-components).

* **AEM Projektarchetyp**

   Das [ui.frontend-Modul](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/uifrontend.html) des [AEM-Projektarchetyps](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html) ist ein nützliches und flexibles Tool, um die Front-End-Entwicklung für Ihr AEM-Projekt zu vereinfachen.

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

### Campaign Classic 19.2

| Funktionalität | Beschreibung |
| ------------- | ----------- |
| California Consumer Privacy Act (CCPA) | CCPA ist das neue Datenschutzgesetz des Bundesstaates Kalifornien, mit dem die Datenschutzanforderungen harmonisiert und modernisiert werden, die am 01. Januar 2020 in Kraft treten. CCPA gilt für Adobe Campaign-Kunden, die Daten für in Kalifornien ansässige Datensubjekte speichern. <br> Zusätzlich zu den bereits verfügbaren Datenschutzfunktionen (einschließlich Zustimmungsverwaltung, Einstellungen zur Datenspeicherung und Benutzerrollen) hilft Adobe Campaign Ihnen bei der Vorbereitung auf CCPA: <ul><li>__ Recht auf Zugriff _und_ Recht auf Löschen: nutzen wir die für GDPR hinzugefügten Funktionen. [Mehr Info](https://helpx.adobe.com/campaign/kb/acc-privacy.html#righttoaccess) </li><li>Sie können nachverfolgen, ob ein Verbraucher sich für den Verkauf von persönlichen Informationen entschieden hat. Dazu müssen Sie die Tabelle &quot; [!UICONTROL Profile] &quot;erweitern und ein Feld &quot; **[!UICONTROL Ausschluss für CCPA]**&quot;hinzufügen.[Mehr Info](https://helpx.adobe.com/campaign/kb/acc-privacy.html#ccpa)</li></ul> Siehe [Anleitung](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html). |
| Live-Überwachung des Arbeitsablaufs | Sie können jetzt den Ausführungsstatus aller Workflows in Ihrer Instanz mithilfe vordefinierter Ansichten überwachen. <br> Weitere Informationen finden Sie unter [Filtern von Workflows nach ihrem Status](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/monitoring-workflows/monitoring-workflow-execution.html#filtering-workflows-status). |
| Interaktive Inhalte mit AMP | Mit Adobe Campaign können Sie das neue interaktive [AMP für E-Mail](https://amp.dev/about/email/) -Format ausprobieren, das es Marketingexperten ermöglicht, AMP-Komponenten in Nachrichten einzuschließen, um das E-Mail-Erlebnis mit komplexen, dynamischen und interaktiven Inhalten zu verbessern, die direkt in der Nachricht selbst verarbeitet werden können. <br> Diese Funktion wird als öffentliche Betaversion veröffentlicht. <br> Weitere Informationen finden Sie in der [ausführlichen Dokumentation](https://docs.adobe.com/content/help/en/campaign-classic/using/sending-messages/sending-emails/defining-interactive-content.html) und im [Lernvideo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/sending-messages/email-channel/defining-interactive-email-content-with-amp.html). |
| Sicheres SMS-Messaging (TLS) | Gesicherte SMS werden jetzt über den Extended Generic SMPP Connector unterstützt. Dies ermöglicht eine verschlüsselte Verbindung zum Provider. <br> **Warnung**: Diese Funktion erfordert ein aktuelles Zertifikat auf allen Servern. Ungültige, gesperrte oder abgelaufene Zertifikate führen zu Fehlern, die sich auf die gesamten SMS-Sendefunktionen auswirken. <br>Weitere Informationen finden Sie in der [ausführlichen Dokumentation](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html). |

Fehlerbehebungen und Verbesserungen finden Sie unter [Adobe Campaign Classic – Versionshinweise](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html).

### Campaign Standard 19.4

| Funktionalität | Beschreibung |
| ------------- | ----------- |
| California Consumer Privacy Act (CCPA) | CCPA ist das neue Datenschutzgesetz des Bundesstaates Kalifornien, mit dem die Datenschutzanforderungen harmonisiert und modernisiert werden, die am 01. Januar 2020 in Kraft treten. CCPA gilt für Adobe Campaign-Kunden, die Daten für in Kalifornien ansässige Datensubjekte speichern. <br> Zusätzlich zu den Datenschutzfunktionen, die bereits in Adobe Campaign verfügbar sind (einschließlich Zustimmungsverwaltung, Einstellungen zur Datenspeicherung und Benutzerrollen), nutzen wir diese Gelegenheit, um zusätzliche Funktionen einzubinden, um Ihre Bereitschaft zur Erstellung von CCPA zu erleichtern: <ul><li> Recht auf Zugriff und Recht auf Löschen: nutzen wir die für GDPR hinzugefügten Funktionen. [Mehr Info](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#righttoaccess) </li><li> Bei der Erstellung einer Datenschutzanforderung wurde der Regelungstyp (GDPR oder CCPA) in den Datenschutz-Core-Service aufgenommen. Diese Methode sollten Sie für alle Zugriff- und Löschanforderungen verwenden. Die Verwendung der Kampagnen-API und -Schnittstelle für den Zugriff und das Löschen von Anforderungen wird nicht mehr unterstützt. Siehe Artikel [Veraltete und entfernte Funktionen](https://helpx.adobe.com/campaign/kb/acs-deprecated-and-removed-features.html). </li><li> Der Profiles-Ressource wurde ein **CCPA-Ausschluss** -Feld hinzugefügt, mit dem Adobe Campaign-Benutzer nachverfolgen können, ob ein Kunde sich für den Verkauf persönlicher Informationen entschieden hat. [Mehr Info](https://helpx.adobe.com/content/help/en/campaign/kb/acs-privacy.html#ccpa) </li></ul> Siehe [Anleitung](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/privacy/privacy-overview.html). |
| Integration von Microsoft Dynamics 365 (GA) | Die Integration zwischen Adobe Campaign Standard und Microsoft Dynamics 365 ist jetzt verfügbar. Sie können Ihre Kontakt- und benutzerdefinierten Entitätsdatensätze von Dynamics 365 auf Campaign übertragen und E-Mail-Ereignisdaten von Campaign auf Dynamics 365 zurückerhalten, um eine bessere Ausrichtung von Vertrieb und Marketing zu erzielen. <br> Lesen Sie die [ausführliche Dokumentation](https://helpx.adobe.com/campaign/kb/acs-ms-dynamics.html) , um diese Integration einzurichten und das [Anleitungsvideo](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/integrating/microsoft-dynamics365-connector/introduction.html)anzuzeigen. |

See [Adobe Campaign Standard Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) for fixes and improvements.

### Control Panel von Adobe Campaign

Es wurden neue Funktionen hinzugefügt, mit denen Administratoren Subdomänen delegieren und SSL-Zertifikate über die Systemsteuerung erneuern können.

Weitere Informationen finden Sie auf folgenden Seiten:

* Einrichten einer neuen Subdomäne - [Weitere Informationen](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/setting-up-new-subdomain.html)
* Verlängerung des SSL-Zertifikats einer Subdomäne - [Weitere Informationen](https://docs.adobe.com/content/help/en/control-panel/using/subdomains-and-certificates/renewing-subdomain-certificate.html)

>[!CAUTION]
>
>Diese Funktionen werden bis Ende Januar in der Beta-Version verfügbar sein, vorbehaltlich häufiger Updates und Änderungen ohne Vorankündigung.

### Zusätzliche Ressourcen

* Adobe Campaign Standard: [Dokumentation](https://helpx.adobe.com/support/campaign/standard.html) – [Versionshinweise](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)  – [Versionsplanung](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Dokumentation](https://helpx.adobe.com/support/campaign/classic.html) – [Versionshinweise](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign-Systemsteuerung: [Dokumentation](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Versionshinweise](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## Advertising Cloud {#adcloud}

Aktualisiert für Version vom 11. Januar 2020

| Ansicht | Funktion |
|------|---------|
| Konversions-Tracking | Alle Advertising Cloud-Cookies wurden aktualisiert, um die neuen Cookie-Kontrollanforderungen für Google Chrome 80 zu erfüllen, die am 4. Februar veröffentlicht werden. Die Änderungen wurden von Adobe-Servern mithilfe der vorhandenen Cookies implementiert, ohne dass sich dies auf die Besuchermetriken auswirkt. Es sind keine Advertiser-Aktualisierungen erforderlich. |
| Einblicke > Warnhinweise Beta, Suche > Kampagnen | (Nur Beta-Funktion für Suchkonten) Mit einer neuen Warnhinweis-Beta-Funktion können Sie Warnvorlagen erstellen, um zu erkennen, wann Suchkampagnen, Anzeigengruppen, Suchbegriffe oder Anzeigen bestimmte Bedingungen erfüllen — wie Leistungsmetriken — während eines bestimmten Zeitraums und dann eine Warnung generieren. Warnungen sind für einen einzigen Anbieter verfügbar. |
| Berichte | Daten für Produktlistungsanzeigen sind jetzt in den Berichten Label-Classification, Label-Wert, Angebotsregel und Beschränkung enthalten. |
