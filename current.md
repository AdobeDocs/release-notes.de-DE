---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: release notes
last-update: January 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 8a895d104abd20910aa37ec2ec3b6eeaccd8c461

---


# INTERNE ÜBERPRÜFUNG - Versionshinweise zu Adobe Experience Cloud - Januar 2020

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

> [!NOTE] Abonnieren Sie [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bald verfügbare Versionen benachrichtigt zu werden. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Releasedatum: Januar 2020**

* [Experience Cloud-Benutzeroberfläche](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (Links zur Lösungshilfe)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (Links zur Lösungshilfe)
* [!DNL Advertising Cloud](#adcloud) (Aktualisiert am 8.11.2019)

Suchen Sie nach der Hilfeseite? Siehe die [Adobe Experience Cloud-Dokumentation](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## Status.adobe.com

Mit Ihrer Adobe-ID können Sie Statusbenachrichtigungen abonnieren, die auf Ihren Produkt-, Regions- und Ereignisvoreinstellungen basieren.

| Funktion | Beschreibung |
| -----------| ---------- |
| E-Mail-Benachrichtigungen in Echtzeit abonnieren | <ul><li>Unterstützung für Experience Cloud, Creative Cloud, Document Cloud, AEP und Adobe Services</li><li>Unterstützung für Voreinstellungen für Region und Ereignistyp</li><li>UX-Unterstützung für Web-, Mobil- und Tablets</li></ul> |
| Verwaltung der Benachrichtigungseinstellungen | <ul><li>Voreinstellungen für Benachrichtigungen jederzeit bearbeiten und speichern</li><li>Abmelden von Benachrichtigungen jederzeit</li><li>Element</li></ul> |
| Personalisierte und schnellere E-Mail-Zustellung | <ul><li>Ereignisbenachrichtigungen werden gesendet, sobald CSO und CMR geöffnet, aktualisiert oder geschlossen werden</li><li>Erhalten Sie nur die relevanten Ereignisbenachrichtigungen, die Ihren konfigurierten Voreinstellungen entsprechen</li><li>Empfangene lokalisierte Benachrichtigungen basierend auf der in Ihren Kontovoreinstellungen konfigurierten Sprache</li></ul> |
| Personalisierte In-Produkt-Benachrichtigungen | Ereignisse, die Ihren Benachrichtigungseinstellungen und Produktberechtigungen entsprechen, werden im Fenster &quot;Mitteilung&quot;angezeigt. |

## Experience Cloud-Benutzeroberfläche {#ecloud}

Versionshinweise für die Experience Cloud-Benutzeroberfläche und die Produktverwaltung.

* Element
* Element

Die Produktdokumentation finden Sie auf der [Seite zu Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Versionshinweise für Experience Platform, Experience Platform Launch, Identity Service und Sicherheitsbulletins.

* [Experience Platform – Versionshinweise](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Experience Platform Launch](#launch)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/security.html) (Alle Adobe-Produkte)

### Experience Platform Launch {#launch}

Versionshinweise und die Produktdokumentation finden Sie unter [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## [!DNL Analytics] {#analytics}

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics](#aa-features)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices) (18.**Dezember 2019** aktualisiert)
* [AppMeasurement](#appm)

Eine Produktdokumentation finden Sie auf der [Startseite der Adobe Analytics-Hilfe](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics {#aa-features}

| Funktion | Beschreibung |
| -----------| ---------- | 
|  |  |

#### Fehlerbehebungen

* Fehlerbehebung
* Fehlerbehebung

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Neue Adobe Analytics-Domäne | 18. Dezember 2019 | Am 16. Januar 2020 wechselt Adobe Analytics in die neue Domäne https://experience.adobe.com/analytics. Diese Änderung kann zu Cookie-Problemen führen, wenn Analytics in Safari geladen wird. Wenn Sie in den Datenschutzeinstellungen von Safari die Option &quot;Site-übergreifendes Tracking verhindern&quot;deaktivieren, werden domänenübergreifende Cookies (und alle Site-übergreifenden Erlebnisse) aktiviert, sodass Analytics in dieser neuen Adobe Experience Cloud-Domäne funktionieren kann. Benutzer können andere Browser ohne Ausgabe verwenden, da dies nur Safari-Benutzer betrifft. |
| Option **[!UICONTROL Archiv anzeigen]**wird eingestellt | 30. Oktober 2019 | Die Option **[!UICONTROL Archiv anzeigen]**im Dashboard-Manager (**[!UICONTROL  Komponenten > Dashboards]**) wird im Januar 2020 eingestellt. |
| Option **[!UICONTROL IP-Anmeldebeschränkungen erzwingen]**wird eingestellt | 30. Oktober 2019 | Die IP-Whitelist-Funktionalität (**[!UICONTROL IP-Anmeldebeschränkungen erzwingen]**) unter**[!UICONTROL  Admin > Unternehmenseinstellungen > Sicherheit]**. |
| SameSite-Attribut für Cookies wird neu geregelt | 15. Oktober 2019 | Im August 2019 gab Adobe bekannt, dass für alle von Analytics festgelegten Cookies das SameSite-Attribut festgelegt wird. Die neue Logik wird angewendet, wenn:<ul><li>bei allen nicht auf WebKit basierenden Drittanbieter-Cookies das SameSite-Attribut festgelegt ist auf `none`.</li><li>für alle anderen Cookies nicht das SameSite-Attribut festgelegt ist.</li></ul> |
| Ende der Unterstützung für TLS 1.1 | 3. Oktober 2019 | Ab dem 31. März 2020 unterstützt Adobe Analytics TLS 1.1 nicht mehr. Diese Änderung ist Teil unserer laufenden Bemühungen, höchstmögliche Sicherheit von Kundendaten zu gewährleisten. |
| FTP-Broker in San Jose endet für London und Singapur | Juli 2020 | Für Kunden in London und Singapur wird die Datenvermittlung zwischen den beiden Städten und dem Rechenzentrum in San Jose ([ftp.omniture.com](ftp://ftp.omniture.com/)) nicht mehr unterstützt.<br/><ul><li>Für London verwenden Sie [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Für Singapur verwenden Sie [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Aktualisierung der Summen der Freiformtabellen in Analysis Workspace | 12. September 2019 | Ab Oktober 2019 werden in den Freiformtabellenzeilen „Gesamt“ die angewendeten [Berichtsfilter](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) berücksichtigt. Bisher wurde bei den Summen nur die Segmentierung berücksichtigt. Mit dieser Änderung werden auch die entsprechenden Visualisierungen aktualisiert (z. B. verknüpfte Darstellungen von [!UICONTROL Zusammenfassungen]) sowie exportierte CSV- und PDF-Daten. |
| Bevorstehende Änderung bezüglich des Felds `createDate` für Analytics-Benutzer | 30. August 2019 | Im Oktober oder November 2019 wird das Feld `createDate` für Analytics-Benutzer von der US Pacific Time auf einen korrekt formatierten Datums-/Uhrzeitwert mit Zeitzoneninformationen aktualisiert. (AN-183468) |
| Unterstützung für frühere Unterschiede bei Zeitzonen | 8. August 2019 | Analytics handhabt jetzt automatisch Unterschiede bei Zeitzonen für Treffer mit Zeitstempel. Nach dieser Änderung am 8. August müssen die unterschiedlichen Zeitzonen von Daten, die nachträglich verarbeitet werden sollen, nicht mehr vor dem Laden angepasst werden. |
| Einschränkungen für Classification Rule Builder | Hinzugefügt am 5. Juni 2019 | Diese Beschränkungen sind nicht neu, sondern wurden der Dokumentation [hier](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html) hinzugefügt. |
| Einschränkungen des neuen Segmentoperators | Hinzugefügt am 31. Mai 2019 | Ab dem 18. Juli 2019 sind die Segmentoperatoren _enthält beliebig viele_, _enthält keinerlei_, _enthält alle von_ und _enthält nicht alle_ auf 100 Wörter pro Eingabefeld beschränkt. Die Beschränkung wird nach diesem Datum auf alle neuen und geänderten Segmente angewendet. Vorhandene Segmente, die die Beschränkung überschreiten, werden weiterhin unterstützt, können jedoch erst geändert oder gespeichert werden, wenn das Eingabefeld reduziert wurde. Diese Grenzwerte werden im Rahmen kontinuierlicher Bemühungen zur Verbesserung der Abfrageleistung angewendet. |
| Änderungen der Unterstützung für die Classifications **[!UICONTROL Datumsaktiviert]**und**[!UICONTROL  Numerisch 2]** | Aktualisiert am 28. Mai 2019 | Die Möglichkeit, die Klassifizierungen „Numerisch 2“ und „Datumsaktiviert“ zu importieren, wurde aus der Codebasis entfernt. Diese Änderung wurde mit der Wartungsversion vom Juli 2019 wirksam. Wenn die Importdatei die Spalte „Numerisch“ oder „Datumsaktiviert“ enthält, werden diese Zellen still ignoriert und alle anderen Daten in dieser Datei werden normal importiert. <br/>Vorhandene Classifications können weiterhin über den Standard-Classification-Arbeitsablauf exportiert werden und sind weiterhin in Berichten verfügbar. |
| Änderung bei Berechnungen der _Berichtssumme_ | Aktualisiert am 9. Juli 2019 | Am **18. Juni 2019** wurden in Adobe Analytics die Berechnungen von _Berichtssummen_ für alle Dimensionen und Metriken vereinheitlicht. Dadurch änderten sich die Gesamtsummen bei manchen Berichten (vor allem bei Berichten zu Eigenschaften oder Kundenattributen). Vor dieser Änderung kam es vor, dass in manchen Berichtssummen der Zeileneintrag _Unspecified_ uneinheitlich ein- oder ausgeschlossen wurde, und zwar unabhängig davon, ob _Unspecified_ im Bericht vorkam oder nicht. <br/>Ab 18. Juni 2019 wird _Nicht angegeben_ immer in Berichtssummen angezeigt, auch wenn dieser Wert nicht als Zeileneintrag im Bericht zu sehen ist. Darüber hinaus können Segmente, die die Logik _existiert_ oder _existiert nicht_ verwenden, für einige Dimensionen nach dieser Änderung andere Ergebnisse anzeigen, insbesondere Dimensionen, bei denen _Nicht angegeben_ einen speziellen Namen wie den Zeileneintrag „Eingegeben/Mit Lesezeichen versehen“ für die Dimension „Typ der verweisenden Stelle“ oder den Zeileneintrag „Sonstige“ für die Dimension „Gerätetyp“ verwendet werden. Diese Änderung betrifft Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder und die Reporting-API.<br>**Hinweis **: Diese _Gesamtberechnung_des Berichts heißt jetzt _Gesamtsumme_. Siehe &quot;Analysis Workspace: Auf Freiform-Tabellensummen aktualisieren&quot;oben. |
| Aktualisierung von CSV-Downloads aus Analysis Workspace | 10. April 2019 | Ab dem 11. April 2019 wurden mehrere Änderungen an **[!UICONTROL CSV-Downloads]**(und**[!UICONTORL  In Zwischenablage kopieren]**) in Analysis Workspace vorgenommen, um die Formatierung aus den exportierten Daten zu entfernen.  <ul><li>Das Tausendertrennzeichen ist nicht mehr enthalten. Das Dezimaltrennzeichen wird weiterhin enthalten sein und dem unter **[!UICONTROL Komponenten > Berichtseinstellungen > Tausendertrennzeichen]**definierten Format entsprechen. Hinweis: Numerische Werte, die ein Komma als Dezimaltrennzeichen verwenden, werden weiterhin in der exportierten CSV angegeben.</li><li>Es werden keine Währungssymbole angezeigt.</li><li>Es werden keine Prozentsymbole angezeigt. Prozentangaben werden in Dezimalform angezeigt. Zum Beispiel werden 75 % als 0,75 dargestellt.</li><li>Die Zeit wird in Sekunden angezeigt.</li><li>Kohortentabellen zeigen nur Rohwerte an. Prozentsätze werden entfernt.</li><li>Wenn eine Nummer ungültig ist, wird eine leere Zelle angezeigt.</li></ul> |
| Anstehende Änderung am Befehl „Analysis Workspace Debugger“ | 4. April 2019 | Der Befehl „Console“ zum Aktivieren des Analysis Workspace-Debuggers ändert sich am **13. Juni 2019** in adobeTools.debug.includeOberonXml. adobe.tools.debug.includeOberonXml wird nach diesem Datum nicht mehr funktionieren. |
| Mobile Browser – Versionsnummern | 7. Februar 2019 | Am 8. Januar 2019 haben wir die Abschnittsebene bei den Versionsnummern mobiler Browser von 2 zu 1 geändert. Seit diesem Datum zeigen die Versionen nur die ersten beiden Ebenen an (Beispiel: _Firefox 64.0.2_ wird jetzt als _Firefox 64.0_ angegeben). |
| Wird eingestellt [!DNL Ad Hoc Analysis] | 29. Januar 2019 | Am 6. August 2018 kündigte Adobe die Absicht an, [!DNL Ad Hoc Analysis] einzustellen. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist.<br/>Weitere Informationen dazu, welche Versionen von Java während dieses Zeitraums kompatibel sind, finden Sie unter [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Kurz-Links [!DNL Analytics] für Berichte | 14. Januar 2019 | Kurz-Links [!DNL Analytics] für Berichte, die innerhalb eines Jahres nicht aufgerufen wurden, werden entfernt und ab Donnerstag, den 17. Januar 2019 fortlaufend gelöscht. |
| Daten-Feed: Spalte „post_product_list“ – Änderung der Größe | 9. Januar 2019 | Adobe hat die Größe der Spalte „post_product_list“ am dem 7. Februar 2019 von 64 KB auf 16 MB erweitert. Diese Änderung stellt sicher, dass bei der Verarbeitung zu „post_product_list“ hinzugefügte Merchandising-eVar-Werte nicht zu abgeschnittenen Produkt- und Umsatzwerten führen. Wenn Sie über Prozesse verfügen, bei denen post_product_list-Werte erfasst werden, stellen Sie sicher, dass diese Prozesse Werte mit einer Länge von bis zu 16 MB verarbeiten können (ansonsten werden Werte bei 16 KB abgeschnitten), um Datenerfassungsfehler zu vermeiden. |
| Verwaltungsänderungen mit Auswirkung auf inaktive [!DNL Analytics Live Stream]-Endpunkte | 20. Dezember 2018 | Ab dem 1. Februar 2019 können [!DNL Live Stream]-Endpunkte, die 90 Tage lang keine aktive Verbraucherverbindung aufweisen, deaktiviert werden. Sie können sich an die Kundenunterstützung wenden, um sich über Ihre [!DNL Live Stream]-Endpunkte zu informieren und diese bei Bedarf wieder zu aktivieren. Stellen Sie außerdem sicher, dass für Ihre Verbraucherprozesse eine dauerhafte Verbindung besteht, wie es das Konzept des Dienstes vorsieht, und dass sie so implementiert sind, dass sie sich wieder verbinden, wenn die Verbindung getrennt oder unterbrochen wird. |
| Aktualisieren von Adobe [!DNL Report Builder] aufgrund der Einstellung des Supports für TLS 1.0 | 7. Sept. 2018 | Aufgrund der Unterstützung für TLS 1.0 sollten Benutzer von [!DNL Report Builder] die Version 5.6.21 vor Februar 2019 herunterladen. Nach diesem Datum sind frühere Versionen von [!DNL Report Builder] nicht mehr funktionstüchtig. |

### [!DNL AppMeasurement] {#appm}

Siehe [Versionshinweise zu AppMeasurement für JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

### Neue in Audience Manager verfügbare Funktionen, Verbesserungen und Fehlerbehebungen {#aam-new-features}

| Funktion | Beschreibung |
|--- |----|
|  |  |

### Verbesserungen {#aam-enhancements}

Weitere Informationen erhalten Sie von Ihrem Audience Manager-Berater oder der Kundenunterstützung.

### Fehlerbehebungen und Verbesserungen {#aam-fixes-and-improvements}

* Fehlerbehebung
* Fehlerbehebung

## Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktversionen

### Selbsthilfe

* **Aktualisierungen der Dokumentation zu AEM**

   Machen Sie sich mit wichtigen in den letzten drei Monaten vorgenommenen Dokumentationsänderungen und Aktualisierungen für Adobe Experience Manager vertraut.

   Siehe [AEM-Dokumentation: Aktuelle Aktualisierungen der Dokumentation](https://helpx.adobe.com/experience-manager/documentation-updates.html).

### Zusätzliche Ressourcen

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

### Dokumentationsressourcen

* Adobe Campaign Standard: [Dokumentation](https://helpx.adobe.com/support/campaign/standard.html) – [Versionshinweise](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) – [Versionsplanung](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Dokumentation](https://helpx.adobe.com/support/campaign/classic.html) – [Versionshinweise](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)

## Advertising Cloud {#adcloud}

| Ansicht | Funktion |
|------|---------|
|  |  |
