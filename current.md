---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: a9f229b5766e90c4fef37d5c35f055856aa42f5a

---


# Adobe Experience Cloud – Versionshinweise, April 2020

![Banner](/assets/experience-cloud-banner-3.png)

Neue Funktionen und Fehlerbehebungen in [!DNL Adobe Experience Cloud].

>[!NOTE]
>
>Abonnieren Sie [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bald verfügbare Versionen benachrichtigt zu werden. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Veröffentlichungsdatum: 2020. April**

Neueste Aktualisierung: 29. **April 2020**

(Die einzelnen Veröffentlichungsdaten können variieren.)

* [Systemstatus von Adobe](#status)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) **(Aktualisiert am 29. April)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/de-DE/target/using/release-notes/target-release-notes.html) (Link zur Target-Hilfeseite)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (Link zur Primetime-Hilfeseite)

Suchen Sie nach der Hilfeseite? Siehe die [Adobe Experience Cloud-Dokumentation](https://docs.adobe.com/content/help/de-DE/experience-cloud/user-guides/home.html).

## ![Symbol](/assets/adobe.png) Systemstatus von Adobe {#status}

[!UICONTROL Der Adobe-Systemstatus] liefert detaillierte Informationen, Statusaktualisierungen und E-Mail-Benachrichtigungen zu Ausfällen, Störungen und Wartungsarbeiten von Adobe Cloud-Produkten und -Diensten. Weitere Informationen dazu erhalten Sie unter [status.adobe.com](https://status.adobe.com/).

**Neuigkeiten**

* Mit Ihrer Adobe ID können Sie Ereignisbenachrichtigungen mit größerer Granularität bis hinunter zur Produktangebot- und Add-on-Ebene abonnieren. Darüber hinaus wird bei der Abonnement-Selbstregistrierung in unserer aktuellen Version eine Auswahl von Produkten und Dienstleistungen empfohlen, die auf Ihren Produktberechtigungen basieren. Dies verkürzt den Prozess der Selbstregistrierung, da die Anzahl der Entscheidungen bzw. Klicks verringert wird, die zum Erstellen Ihrer Abonnements erforderlich sind. Zusätzlich werden Ihnen relevantere Benachrichtigungen gesendet. Weitere Informationen erhalten Sie unter [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Ab heute verfügbare neue Funktionen und Verbesserungen**

| Funktion | Beschreibung |
| -----------| ---------- |
| Personalisierte Abonnements basierend auf Berechtigungen | <ul><li>Vorab ausgewählte Abonnement-Empfehlungen basierend auf den DX-Berechtigungen des Benutzers.</li><li>Empfohlene Abonnements werden oben in der Produktliste hervorgehoben, damit sie besser erkennbar sind.</li><li>Die erhaltenen E-Mail-Benachrichtigungen sind relevant für die Produktberechtigungen des Benutzers.</li></ul> |
| Einfachere Verwaltung von Abonnements | <ul><li>Die Option zum **[!UICONTROL Verwalten von Abonnements]** ist neu und ermöglicht die Verwaltung von sowohl Produkt- als auch Ereignis-Abonnements.</li><li>Neue Möglichkeit zur getrennten Ansicht und Bearbeitung von Produkt- und Ereignis-Abonnements.</li><li>Mit der Option **[!UICONTROL Löschen]** können Sie sich von einem Produkt- oder Ereignis-Abonnement abmelden.</li><li>Der Benutzer kann sich von den Abonnements mit der Option **[!UICONTROL Alle Abonnements löschen]** mit nur einem Klick abmelden.</li><li>Support für die Benutzeroberfläche ist für Web, Mobile und Tablet in 19 Sprachen verfügbar.</li></ul> |

## ![Symbol](/assets/ec_appicon_24.png) Experience Cloud-Benutzeroberfläche {#ecloud}

Für die Benutzeroberfläche der Experience Cloud gibt es folgende neue Funktionen und Fehlerbehebungen:

* Die Seite „Experience Cloud- [!UICONTROL Feed]“ wurde entfernt. (EXC-8505)
* Die Experience Cloud-Anmeldeseite wurde aktualisiert und enthält jetzt neue Branding-Elemente. (EXC-10747)

Die Produktdokumentation finden Sie in der [Hilfe zur Experience Cloud-Benutzeroberfläche](https://docs.adobe.com/content/help/de-DE/core-services/interface/experience-cloud.html).

### Einheitliche Produktdomäne

Adobe aktualisiert die Domäne und die Kopfzeile der Benutzeroberfläche, um Ihre Nutzererfahrung in allen Experience Cloud-Anwendungen zu vereinheitlichen und zu verbessern. Diese simplen Aktualisierungen sollen die Benutzerfreundlichkeit vereinfachen und verbessern. Ihre aktuellen Workflows werden dadurch nicht geändert.

Zu den Aktualisierungen gehören:

* Neue Anwendungs-URLs: `experience.adobe.com/<application name>`:
   * Dieses URL-Muster wird schließlich von allen Produkten übernommen. Im Laufe des Monats werden neue URLs hinzugefügt werden.
   * Browserunterstützung: Unterstützte Browser sind [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] und [!DNL Opera] (neueste Versionen). **Hinweis:** Obwohl die Experience Cloud-Oberfläche diese Browser unterstützt, unterstützen einzelne Anwendungen möglicherweise nicht alle Browser. ([Analytics](https://docs.adobe.com/content/help/de-DE/analytics/admin/sys-reqs.html) unterstützt beispielsweise nicht [!DNL Opera] und [Target](https://docs.adobe.com/help/de-DE/target/using/implement-target/before-implement/supported-browsers.html) unterstützt nicht [!DNL Safari].)
   * (Nur [!DNL Safari]) Die Domänenänderung kann bei [!DNL Safari] zu Cookie-Problemen führen. Wenn Sie in den Datenschutzvoreinstellungen von [!DNL Safari] die Option _Prevent cross-site tracking_ (Website-übergreifendes Tracking verhindern) deaktivieren, werden domänenübergreifende Cookies (und alle Site-übergreifenden Ereignisse) aktiviert, sodass Experience Cloud in dieser neuen Domäne funktionieren kann.
* Einfacherer Wechsel zwischen Ihren Organisationen oder zu einer anderen Anwendung.
* Verbesserte Produkthilfe: [!UICONTROL Experience League] ist in das Produkt integriert, sodass bei einer Hilfesuche auch Ergebnisse aus Community-Foren und Videos berücksichtigt werden. Diese Änderung vereinfacht den Zugriff auf weitere Inhalte und hilft Ihnen, Experience Cloud optimal zu nutzen. Zusätzlich können Sie unter **[!UICONTROL Hilfe]** > **[!UICONTROL Feedback]** Probleme melden oder Ihre Ideen mit Adobe teilen.

## ![Symbol](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Versionshinweise für [!DNL Experience Platform,] einschließlich [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL Angebote], [!UICONTROL Personen], [!UICONTROL Places], [!UICONTROL Mobile Services] und Sicherheitsbulletins.

### Journey-Orchestrierung {#journey}

Mithilfe der Adobe Experience Platform können Sie individuelle Customer Journeys maßstabsgetreu über verschiedene Erlebniskanäle orchestrieren, indem Sie die Bedürfnisse jedes einzelnen Kunden in Echtzeit und unabhängig vom Zielort intelligent antizipieren.

* [Dokumentation](https://docs.adobe.com/content/help/de-DE/journeys/using/journey-orchestration-home.html)
* [Versionshinweise](https://docs.adobe.com/content/help/de-DE/journeys/using/release-notes/release-notes.html)
* [Anleitungsvideos](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobile Services und Mobile SDKs {#mobile}

Android 4.18.2 (3. April 2020):

* In-App-Benachrichtigungen: Aus Sicherheitsgründen setzt [!UICONTROL WebViews], das vom SDK erstellt wurde, jetzt die Eigenschaft `setAllowFileAccess` auf _false_.

iOS 4.19.2 (24. März 2020):

* Allgemein: Es wurden einige Lecks im [!DNL Target]-Code behoben.

Unity 4.19.0 (10. März 2020):

* Das [!UICONTROL Unity-Plugin] wurde aktualisiert und verwendet nun die Versionen 4.19.0 von iOS und 4.18.0 von [!DNL Android].
* Eine neue Akquise-Methode für [!DNL Android] wurde vorgestellt, um die Verarbeitung einer URL zu ermöglichen, die von Referrer-APIs von [!DNL Google Play] bereitgestellt wird.

### Zusätzliche Versionsinformationen zu Experience Platform

* [Experience Platform Launch – Versionshinweise](https://docs.adobe.com/content/help/de-DE/launch/using/intro/release-notes/current.html)
* [Experience Platform – Versionshinweise](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/de/security.html)  (alle Adobe-Produkte)

## ![Symbol](/assets/analytics.png) [!DNL Analytics] {#analytics}

>[!IMPORTANT]
>
>Das Adobe Analytics-Update vom April wurde auf den 21. Mai 2020 verschoben. Die neuesten Versionshinweise zu Analytics finden Sie in den [Versionshinweisen vom März](c-legacy-releases/2020/03122020.md)

* [Customer Journey Analytics](#cust-journey)
<!--* [New features in Adobe Analytics](#aa-features)-->
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)  (Aktualisiert am 16. April 2020)
* [AppMeasurement](#appm)
* [Neue Analytics-Tutorials](#tutorials-analytics)

### Customer Journey Analytics {#cust-journey}

| Funktion | Beschreibung |
| -----------| ---------- |
| Data Workbench 6.74 (**Update 4/29/2020**) | Aktualisierung der IMS-Zertifikatanalyse für Identitätsverwaltungsdienste (Identity Management Service) bei der Serverimplementierung. Dieses Update erweitert die Analyse von der Zeichenfolgenübereinstimmung auf den regulären Ausdruck, einschließlich der Möglichkeit, Zertifikate mit alternativen Themennamen (SAN) zu verarbeiten. See [Data Workbench release notes](https://docs.adobe.com/content/help/en/data-workbench/using/release-notes/release-notes.html) for more information. |
| [!UICONTROL Customer Journey Analytics]: Automatische Aufstockung von Datensätzen | Mit dieser neuen Option können Sie alle historischen Daten importieren und eine Verbindung mit [!UICONTROL Customer Journey Analytics] herstellen. [Mehr Infos](https://docs.adobe.com/content/help/de-DE/analytics-platform/using/cja-connections/create-connection.translate.html) |

<!--### New features in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |
|Analytics support for [!UICONTROL Experience Edge] |You can now forward data that was sent to [!UICONTROL Experience Edge] to Analytics.|
 |[!UICONTROL Workspace]: Automatically build Freeform Tables from a blank state|Previously, you could not drop components directly into a blank project or blank panel; you had to add a freeform table first. You can now drop components directly into a blank project or panel, and a freeform table will automatically be built for you in a recommended format. Additionally, improvements were made to how mixed component types (e.g. dimensions & metrics) are handled when dropped into a blank freeform table together.|

#### Analytics fixes

* Fixed an issue that caused missing Analytics segment data in Audience Manager. (AN-206221)
* Fixed an issue with [!UICONTROL Data Sources] processing showing the wrong dates. (AN-213604)
* Fixed an issue with classification files not getting uploaded to FTP properly. (AN-214102)
* Fixed an issue with the API method `Segments.Get` not returning a full response. (AN-206210)
* Fixed an issue where table line items were converted to special characters in [!DNL Workspace] PDF download. (AN-196153)
* Fixed an issue with Adobe Analytics API 1.4 call `visattrcustomeridcustomerattributes` not working properly. (AN-186873)
* Fixed an issue with data appearing in reports but missing from the [!UICONTROL Data Feed]. (AN-211923)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to Report Builder. (AN-207750)
* Fixed an issue with [!UICONTROL AdWords] data not showing in [!UICONTROL Advertising Analytics]. (AN-213249)
* Fixed an issue where classification data did not display in the trended view. (AN-212761)
* Fixed an issue that caused an incorrect published segment count in the [!UICONTROL Segment Manager]. (AN-213374)

#### Additional Analytics fixes

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212 -->

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt  oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Die Prüfung „Segment in Data Warehouse angewendet“ wurde entfernt. | 16. April 2020 | Ab dem 16. April 2020 wird nicht mehr geprüft, ob ein Segment in einer Data Warehouse-Anfrage in Segment Builder angewendet wird. Zuvor wurden bei dieser Prüfung einzelne in Data Warehouse-Anfragen angewendete Segmente gesucht (dabei wurden mehrere angewendete Segmente ausgeschlossen), und eine Warnmeldung wurde zurückgegeben, wenn dies der Fall war („true“). Diese Änderung wirkt sich nicht auf die Produktkompatibilitätsprüfung für Segmente von Data Warehouse aus. |
| Änderung der Berechnung von [!UICONTROL Einstiegen/Ausstiegen] in [!UICONTROL Workspace] | 7. April 2020 | In [!UICONTROL Analysis Workspace] wurde im März 2020 die Weise geändert, wie der Wert _Keine_ in Bezug auf [!UICONTROL Einstiege/Ausstiege] verwendet wird. Da Sie jetzt _Keine_ in [!UICONTROL Analysis Workspace] aktivieren und deaktivieren können, wird _Keine_ jetzt erst nach einem Ein- oder Ausstieg angewendet, während dieser Wert früher davor (bei eVars) angewendet wurde. Angenommen, der erste Treffer eines Besuchs liefert keinen Wert für eVars, der zweite aber schon. In [!UICONTROL Reports &amp; Analytics] wird als Wert für den Einstieg _Nicht angegeben_ angezeigt, aber in [!UICONTROL Analysis Workspace] wird dieser Wert beim zweiten Treffer angezeigt. |
| Ende der **[!UICONTROL Konversionsebenen]**-Einstellung | 3. März 2020 | Die nicht funktionierende Einstellung der [Konversionsebene](https://docs.adobe.com/content/help/de-DE/analytics/admin/admin-tools/general-acct-settings-admin.html) unter **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL Allgemeine Kontoeinstellungen]** wird am 12. März 2020 aus der Benutzeroberfläche entfernt. |
| Entfernung des **[!UICONTROL Dashboard-Archivs]** | 27. März 2020 | Ab Oktober 2020 ist die Einstellung **[!UICONTROL Archiv anzeigen]** unter **[!UICONTROL Dashboards verwalten]** in [!UICONTROL Reports &amp; Analytics] nicht mehr verfügbar. |
| Ende der Unterstützung für TLS 1.1 | 3. Oktober 2019 | Ab dem 31. März 2020 unterstützt Adobe Analytics TLS 1.1 nicht mehr. Diese Änderung ist Teil unserer laufenden Bemühungen, höchstmögliche Sicherheit von Kundendaten zu gewährleisten. |
| Neue Adobe Analytics-Domäne | 18. Dezember 2019 | Am 16. Januar 2020 begann Adobe Analytics mit der Umstellung auf eine neue Domäne – `https://experience.adobe.com/analytics.`<br>**Hinweis:** Diese Änderung gilt für alle Benutzer, die mit ihrer Adobe ID oder Enterprise ID auf Analytics zugreifen.<ul><li>Diese Änderung kann zu Problemen mit Cookies führen, wenn Analytics in Safari geladen wird. Wenn Sie in den Datenschutzvoreinstellungen von [!DNL Safari] die Option _Prevent cross-site tracking_ (Website-übergreifendes Tracking verhindern) deaktivieren, werden domänenübergreifende Cookies (und alle Site-übergreifenden Ereignisse) aktiviert, sodass Analytics in dieser neuen Adobe Experience Cloud-Domäne funktionieren kann. Sie können problemlos andere Browser verwenden, da dies nur [!DNL Safari]-Anwender betrifft.</li><li>Die Domänenänderung kann dazu führen, dass [!UICONTROL Activity Map] bei einigen Kunden [in bestimmten Fällen](https://docs.adobe.com/content/help/de-DE/analytics/analyze/activity-map/activity-map.html) nicht mehr funktioniert.</li></ul> |
| End of Life – veraltete Analytics-APIs | 9. Januar 2020 | Im November 2020 werden die folgenden Legacy-API-Dienste von Analytics eingestellt. Aktuelle Integrationen, die mit diesen Diensten erstellt wurden, funktionieren dann nicht mehr. <ul><li>1.3 Analytics-APIs</li><li>1.4 SOAP Analytics-APIs</li><li>Legacy-OAuth-Authentifizierung (OAuth und JWT)</li></ul>Wir haben [FAQ zu Legacy API EOL](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) bereitgestellt, die Ihnen bei der Beantwortung Ihrer Fragen helfen und Anleitungen zum weiteren Vorgehen geben sollen. API-Integrationen, die diese Dienste nutzen, können zu den [Analytics-REST-APIs 1.4](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) oder den [Analytics-APIs 2.0](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email) migrieren. Ältere OAuth-Konten können zu einem [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-Integrationskonto migrieren, das für den Zugriff auf sowohl Analytics-APIs 1.4 als auch Analytics-APIs 2.0 verwendet werden kann. |
| FTP-Broker in San Jose endet für London und Singapur | Juli 2020 | Für Kunden in London und Singapur wird die Datenvermittlung zwischen den beiden Städten und dem Rechenzentrum in San Jose ([ftp.omniture.com](ftp://ftp.omniture.com/)) nicht mehr unterstützt.<br/><ul><li>Für London verwenden Sie [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Für Singapur verwenden Sie [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| Ende von Ad Hoc Analysis | 6. August 2018 | Adobe kündigte die Absicht an, Ad Hoc Analysis einzustellen. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist. Weiterführende Informationen finden Sie unter [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Siehe [Versionshinweise zu AppMeasurement für JavaScript](https://docs.adobe.com/content/help/de-DE/analytics/implementation/appmeasurement-updates.html). Version 2.20.0 wurde am 5. März 2020 veröffentlicht.

### Neue Analytics-Tutorials {#tutorials-analytics}

| Inhalt | Beschreibung |
| -----------| ---------- |
| [Adobe Labs (Technology Previews) mit Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Mit Adobe Labs (Technology Previews) können Sie sich mit neuen Technologien beschäftigen, wertvolle Einblicke gewinnen und die Entwicklung und die Prioritäten künftiger [!DNL Analytics]-Funktionen beeinflussen. |
| [Verbesserung der Veröffentlichung von Experience Cloud-Audiences](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | Die Veröffentlichung von [!UICONTROL Experience Cloud-Audiences] wurde verbessert. Jetzt ist die Veröffentlichung und Bereitstellung von Audiences (Segmenten) sechsmal schneller. Auf diese Weise wird die aktuelle Latenzzeit von 48 auf ca. 8 Stunden reduziert und ist je nach Traffic- und Segmentgröße möglicherweise noch schneller. |
| [Mehrere Report Suites in Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | Mehrere Report Suites können in einem einzigen [!UICONTROL Workspace]-Projekt analysiert werden, indem Report Suites auf Bedienfeldebene ausgewählt werden. Auf diese Weise können Sie eine parallele Bedienfeldanalyse für verschiedene Datensätze durchführen. |

Die Produktdokumentation finden Sie auf der [Startseite der Hilfe zu Adobe Analytics](https://docs.adobe.com/content/help/de-DE/analytics/landing/home.html).

## ![Symbol](/assets/audience-manager.png) Audience Manager {#aam}

Neue Funktionen und Fehlerbehebungen in Adobe Audience Manager verfügbar:

| Funktion | Beschreibung |
| -----------| ---------- |  
| [Prognostizierende Audiencen](../features/algorithmic-models/predictive-audiences.md) | [!UICONTROL Prognostische Audiencen] helfen Ihnen, eine unbekannte Audience in Echtzeit mithilfe fortschrittlicher Datenwissenstechniken in verschiedene Personen zu klassifizieren. <br><br> In einem Marketingkontext ist eine Audience ein Segment, das von Besuchern, Benutzern oder potenziellen Käufern definiert wird, die eine bestimmte Reihe von Eigenschaften gemeinsam haben, wie demografische Merkmale, Browsing-Gewohnheiten, Shopping-Geschichte usw.<br><br>[!UICONTROL Prognostische Audiencen] gehen noch einen Schritt weiter, indem Sie die maschinellen Lernfunktionen von Audience Manager nutzen, um unbekannte Audiencen in verschiedene Personengruppen zu klassifizieren. <br><br>Audience Manager hilft Ihnen dabei, die Tendenz Ihrer unbekannten Erstanbieter-Audience für eine Reihe bekannter Erstanbieter-Audiencen zu berechnen. |
| Additional [!UICONTROL Profile Merge Rules] Enhancements | [!UICONTROL Profil Merge Rules] geben Audience Manager-Kunden die Möglichkeit, Audiencen anhand von Identitätssegmenten und nicht anhand von Geräten zu definieren, zu verwalten und zu aktivieren. <br><br> Ab dem 29. April können Audience Manager-Kunden die Aufschlüsselung der Geräte- und geräteübergreifenden ID-Populationen für Eigenschaften und Segmente sowohl innerhalb der Segmentierung als auch im Bulk-Berichte in der Audience Manager-Benutzeroberfläche besser verstehen. <br><br> Auf diese Weise erhalten Sie einen besseren Einblick in die Identität im Audience Manager und erhalten so eine ganzheitliche Ansicht der Segmentgesamtheit nach Gerät, Person und Haushalt. Auch die Export von Massenmerkmalen von geräteübergreifenden und Geräte-IDs wird aktualisiert, um diese Verbesserungen widerzuspiegeln.<br><br>  Spezifische Aktualisierungen umfassen die Möglichkeit, <ul><li>Bericht gegen [geräteübergreifende IDs](https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/reference/ids-in-aam.html) in den [allgemeinen](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reporting/general-reports.html) und [Trendberichten](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reporting/trend-reports.html) ;</li><li>Verbessern Sie die [!UICONTROL Eigenschaftsauswahl] im [Segmentaufbau](https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/features/segments/segment-builder.html) , um Eigenschaftspopulationen einzubeziehen, die aus [CRM-IDs](https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/reference/ids-in-aam.html)herausgegeben wurden.</li><li>Erstellen Sie exakte Eigenschaftsexporte, die mit [geräteübergreifenden IDs](https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/reference/ids-in-aam.html)ausgefüllt werden.</li><li>Erstellen Sie exakte Eigenschaftsexporte, die mit [Geräte-IDs](https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/reference/ids-in-aam.html) (nicht authentifizierte Eigenschaften ausschließen) ausgefüllt sind.</li><li>Geben Sie korrekte Zählungen für Eigenschaften zurück, die mit [CRM-IDs](https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/reference/ids-in-aam.html) verknüpft sind, wenn Sie mit dem [BAAAM](https://docs.adobe.com/help/de-DE/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) -Tool angefordert werden.</li></ul> |
| [Häufigste Probleme beim Support](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | Wir haben einen neuen Abschnitt zu unserem Dokumentationsportal hinzugefügt, der Antworten auf die häufigsten Fragen enthält, die unserem Support-Team gestellt werden. |

* Es wurde ein Fehler behoben, der zu ungenauen Berichten von [adressierbaren Audiences](https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/features/addressable-audiences.html) für Segmente mit Mobilgeräte-IDs führte. Nach diesem Update bemerken Sie möglicherweise einen Anstieg bei [adressierbaren Audiences](https://docs.adobe.com/content/help/de-DE/audience-manager/user-guide/features/addressable-audiences.html).
* Es wurde ein Fehler behoben, der dazu führte, dass die Schaltflächen [!UICONTROL Duplikat-Test] und [!UICONTROL Duplikat-Zuordnungsvorlage] im Register [!UICONTROL Audience Lab] nicht funktionierten. (AAM-53388)
* Es wurde ein Fehler behoben, der dazu führte, dass die [!UICONTROL Übereinstimmungsrate] und [!UICONTROL segmentadressierbare Audiences] als 0 angezeigt wurden, wenn ein Ziel für den Export von UUIDs konfiguriert wurde. Die [!UICONTROL Übereinstimmungsrate] und [!UICONTROL segmentadressierbare Audiences] werden jetzt als 100 % angezeigt. (AAM-51615)
* Es wurde ein Problem behoben, bei dem Namen von Merkmalen, die Sonderzeichen enthalten, zweimal HTML-kodiert wurden. (AAM-54001)
* Es wurde ein Fehler behoben, der manche Benutzer daran hinderte, über die [!DNL Audience Manager]-Benutzeroberfläche zu anderen Adobe Experience Cloud-Anwendungen zu wechseln. (AAM-52917)
* Es wurde ein Problem behoben, das manche Benutzer daran hinderte, eine SHA256-Datenquelle für People-basierte Ziele zu erstellen. (AAM-53525)
* Mehrere Verbesserungen hinsichtlich der Barrierefreiheit auf der gesamten Benutzeroberfläche. (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032, AAM-49360)

## ![Symbol](/assets/aem.png) Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Selbsthilfe

* **AEM-Newsletter**

   Siehe den neuesten [Adobe Experience Manager-Newsletter](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html).

* **AEM als Cloud-Dienst – Konfigurieren des dynamischen Media Cloud-Dienstes**

   Bei der Konfiguration des Dynamic Media Cloud-Diensts ist eine neue Option verfügbar:

   **Selektive Veröffentlichung**: Wenn Sie diese Option wählen, werden Assets nur in einer sicheren Vorschau automatisch angezeigt und können dann in AEM veröffentlicht werden, ohne dass eine Veröffentlichung in DMS7 stattfindet, wo öffentlich darauf zugegriffen werden könnte.

   Siehe [Konfigurieren von Dynamic Media Cloud Services](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services).

* **Dynamic Media – Smart Imaging**

   Das gesamte Hilfethema zu Smart Imaging wurde mit neuen Informationen ergänzt, einschließlich Beispielen für Bild-Assets, in denen die hinzugefügte Smart Imaging-Optimierung dargestellt wird.

   Siehe [Smart Imaging](https://docs.adobe.com/content/help/de-DE/experience-manager-65/assets/dynamic/imaging-faq.html).

* **Konfigurieren von Dynamic Media – Scene7-Modus**

   Die neue Option „Alle Inhalte synchronisieren“ ist jetzt auf der Seite „Konfiguration von Dynamic Media“ unter **[!UICONTROL Tools > Cloud-Dienste]** verfügbar.

   Siehe [Erstellen einer Dynamic Media-Konfiguration](https://docs.adobe.com/content/help/de-DE/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services).

* **AEM Assets Brand Portal unterstützt AEM Assets as a Cloud Service**

   Jetzt können Sie Assets aus AEM Assets as a Cloud Service in AEM Assets Brand Portal veröffentlichen.

   Siehe [AEM Assets mit Brand Portal konfigurieren](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) und [Assets in Brand Portal veröffentlichen](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html).

* **Adobe Asset Link 2.0 wurde veröffentlicht**

   Adobe Asset Link 2.0 unterstützt die Verwendung mehrerer AEM-Umgebung und AEM as a Cloud Service. AEM erfüllt die Anforderungen von Marketern bei der Konfiguration der automatischen Ausführung des Asset-Verarbeitungs-Workflows, wenn Assets mit Adobe Asset Link in einen Ordner hochgeladen werden.

   Siehe [Adobe Asset Link](https://helpx.adobe.com/de/enterprise/using/adobe-asset-link.html).

### Neue Experience Manager-Tutorials

| Inhalt | Beschreibung |
| -----------| ---------- |  
| [Einrichten von lokalen Dispatcher-Tools](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | Erfahren Sie, wie Sie die Konfiguration, Validierung und Simulation von [!UICONTROL Dispatcher] lokal vereinfachen können. |
| [Einrichten von Entwicklungs-Tools für AEM-Projekte](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | Für die Entwicklung von Adobe Experience Manager (AEM) ist eine minimale Auswahl an Entwicklungs-Tools erforderlich, die auf dem Computer des Entwicklers installiert und eingerichtet werden müssen. Diese Tools unterstützen die Entwicklung und den Aufbau von AEM-Projekten. |
| [Einrichten von Local AEM Runtime](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) kann lokal mithilfe von AEM als ein [!UICONTROL QuickStart Jar] des Cloud Service SDK ausgeführt werden. Auf diese Weise können Entwickler benutzerdefinierten Code, Konfigurationen und Inhalte bereitstellen und testen, bevor sie ihn an die Versionskontrolle senden, und ihn als Cloud-Dienst-Umgebung in AEM bereitstellen. |
| [Navigation](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | Lernen Sie die Grundlagen zur Navigation mit AEM Assets kennen. |
| [Versionen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | Erfahren Sie, wie AEM Asset-Versionen erstellt und verwaltet. |
| [AEM-[!DNL Magento]-Integration mithilfe des [!UICONTROL Commerce Integration Framework]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | Dieses Video führt Sie durch die Einrichtung der Integration zwischen AEM und [!DNL Magento]. |
| [Einführung in den AEM Architecture Stack](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | Der CIF Project-Archetyp erstellt mit Adobe Experience Manager (AEM) ein CIF-Projekt als Grundlage für Kundenprojekte mit CIF-Kernkomponenten. |
| [Einführung in OSGi](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | Eine Einführung in OSGi, eine dynamische, modulare Architektur für Java-Anwendungen, die die Grundlage für Adobe Experience Manager bildet. |
| [Einführung in das Java Content Repository (JCR)](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Eine Einführung in das von Adobe Experience Manager verwendete [Java Content Repository (JCR). |
| [Einführung in Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | Eine Einführung in [!DNL Sling], ein Open-Source-RESTful-Web-Framework, das zum zugrunde liegenden Technologie-Stack von Adobe Experience Manager gehört. |
| [Einführung in die Autoren- und Veröffentlichungsebene](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | Eine Einführung in die Ebenen [!UICONTROL Autor] und [!UICONTROL Veröffentlichen] als Teil der Architektur in Adobe Experience Manager. |
| [Einführung in Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | Eine Einführung in die Funktionen und Merkmale von Dispatcher als Teil der AEM-Architektur. |
| [Einführung in die Komponentenentwicklung](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | Eine Übersicht über Entwicklungskomponenten mit Adobe Experience Manager Sites. Enthält eine Einführung zu [!UICONTROL Dialogen], [!UICONTROL Sling-Modellen], [!UICONTROL HTL-Skripten] und [!UICONTROL Client-seitigen Bibliotheken]. |
| [AEM-Projektarchetyp](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | Das AEM-Projekt enthält sämtlichen Code und alle Konfigurationen für eine Implementierung. Der [!UICONTROL AEM-Projektarchetyp] erstellt ein Adobe Experience Manager-Projekt mit minimalen Best Practices als Ausgangspunkt für Ihre eigenen AEM-Projekte. |
| [Erklärung zu Core Components](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | AEM [!UICONTROL Core Components] sind Standardkomponenten, die mit Adobe Experience Manager verwendet werden. |
| [Verwenden von AEM Quickstart Jar](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | Erfahren Sie, wie Sie eine lokale Instanz von Adobe Experience Manager in nur wenigen Minuten mit [!UICONTROL AEM Quickstart Jar] installieren und ausführen. |

### Zusätzliche Hilferessourcen

* [AEM als Cloud-Dienst](https://docs.adobe.com/content/help/de-DE/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-5.html)
* [AEM 6.4 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-4.html)
* [AEM 6.3 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-3.html)
* [AEM 6.2 Schulung und Support – Startseite](https://helpx.adobe.com/de/support/experience-manager/6-2.html)
* [Cloud Manager-Benutzerhandbuch](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Ältere Versionen der AEM-Dokumentation](https://helpx.adobe.com/de/experience-manager/aem-previous-versions.html)
* [Startseite der Hilfe zu Dynamic Media Classic](https://docs.adobe.com/content/help/de-DE/dynamic-media-classic/using/home.html)
* [Versionshinweise zu Dynamic Media](https://docs.adobe.com/content/help/de-DE/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Livefyre-Versionshinweise](https://docs.adobe.com/content/help/de-DE/livefyre/using/release-notes/c-rn.html)

## ![Symbol](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-notes.html)

### Neue Tutorials für Campaign Standard {#tutorials-acs}

| Inhalt | Beschreibung |
| -----------| ---------- |  
| [Austausch von Profilen – Testen von E-Mail-Nachrichten mit ausgewählten Profilen](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | Testen Sie Ihre E-Mail-Nachrichten mit der Funktion zum Ersetzen von Profilen. |

### Zusätzliche Hilferessourcen für Campaign

* Adobe Campaign Standard: [Dokumentation](https://helpx.adobe.com/de/support/campaign/standard.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/campaign-standard/using/release-notes/release-notes.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)  – [Versionsplanung](https://helpx.adobe.com/de/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Dokumentation](https://helpx.adobe.com/de/support/campaign/classic.html) – [Versionshinweise](https://docs.campaign.adobe.com/doc/AC/de-DE/RN.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Control Panel von Adobe Campaign: [Dokumentation](https://docs.adobe.com/content/help/de-DE/control-panel/using/control-panel-home.html) – [Versionshinweise](https://docs.adobe.com/content/help/de-DE/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![Symbol](/assets/magento.png) [!DNL Magento] {#magento}

Magento-Versionshinweise finden Sie unter:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Symbol](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] ist eine Komplettanwendung für das Lead-Management. B2B-Marketer können damit Kundenerlebnisse transformieren, indem sie in allen Phasen komplexer Customer Journeys Interaktionen ermöglichen.

### Aktualisierungen von Core Marketo Engage

Weitere Informationen finden Sie unter den [!DNL Marketo] [Versionshinweisen](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720).

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
