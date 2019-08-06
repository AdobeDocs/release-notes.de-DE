---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: Versionshinweise
last-update: August 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 2229815ac75b0a7bd60571b39bd0f2780f20195e

---


# Frühzeitiger Zugriff – Versionshinweise zur Adobe Experience Cloud

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

>[!IMPORTANT]
>
>Diese Seite enthält Inhalte einer Vorabversion und kann vor der geplanten Veröffentlichung der Version geändert werden.

>[!NOTE]
>
>Abonnieren Sie das [Prioritätsprodukt-Update von Adobe](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bevorstehende Versionen benachrichtigt zu werden. Sie erhalten drei bis fünf Werktage vor der Veröffentlichung der Version eine Benachrichtigung. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Veröffentlichungsdatum: August 2019**

* [Erlebnisplattform und -verwaltung](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (Links zur Lösungshilfe)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (Links zur Lösungshilfe)

## [!UICONTROL Erlebnisplattform] und -verwaltung {#platform}

Versionshinweise für die [!UICONTROL Experience Platform], Experience Cloud-Schnittstelle, Produktverwaltung, Experience Platform Launch, Identitätsdienst und Sicherheitsbulletins.

* [Experience Cloud-Benutzeroberfläche](#core-services)
* [Experience Platform Launch](#launch)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/security.html) (Alle Adobe-Produkte)

### Experience Cloud-Benutzeroberfläche {#core-services}

* Ein kritisches Problem in der Experience Cloud-Anmeldung wurde behoben, das zu einer Sitzung für einige Benutzer führte. (MCUI-6908)
* Aktualisierung der Experience Cloud-Anmeldung, um die Leistung zu verbessern und die Latenz zu reduzieren. (MCUI -6854, MCUI -6869, MCUI -6883)
* Die Benutzeroberfläche wurde aktualisiert. (MCUI -6861, MCUI -6911, MCUI -6862)
* Es wurde ein Problem mit Experience Cloud [!UICONTROL -Auslösern] behoben, die zur falschen Interpretation _der "Gefällt mir"_ -Klausel in der [!UICONTROL Auslöserdefinition] geführt haben. (MCUI-6611)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics](#aa-features)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### New features, enhancements, and fixes in Adobe Analytics {#aa-features}

| Funktion | Beschreibung |
| -----------| ---------- |  
| Unterstützung für Cookie-Cookie-Einstellungen von samesite | Die Einstellung ["cooksite-Cookie"](https://web.dev/samesite-cookies-explained) wird allen Cookies von Analytics hinzugefügt. Diese Änderung ermöglicht es Ihnen, den Chrome-Änderungen zu entsprechen, die das Cookie-Feld von samesite erfordern. Analytics-Cookies werden standardmäßig `none`verwendet. Wenn Sie nur eine Erstanbieterdomäne verwendet haben (z. B. stats.domain.com), können Sie Adobe clientcare für `lax` Erstanbieter-Sammlungsdomänen festlegen lassen. |
| Arbeitsbereich: Elementbeschränkung für Dropdown-Filter von 50 auf 200 erhöhen | Wir haben die Anzahl der Elemente erhöht, die in einem Dropdown-Filter von 50 auf 200 platziert werden können. Diese Verbesserung bietet eine Vielzahl von Anwendungsfällen, z. B. das Hinzufügen aller Länder (195) zu einem Filter oder alle US-Bundesstaaten und Provinzen (52). |
| Zuordnungs-IQ für A 4 T-Metriken aktiviert | Wir haben zwei Analytics for Target (A 4 T)-Metriken für Zuordnungs-IQ aktiviert: Aktivitätsimpressionen und Aktivitätskonversionen. In Analysis Workspace sind diese Metriken im Vergleich zu Reports &amp; Analysen zu hoch. Mit dieser Änderung können Benutzer jetzt ein Zuordnungsmodell für die gleiche Berührung anwenden, das den Analysis Workspace in die Zeile Reports &amp; Analysen einbringt. |

#### Fehlerbehebungen

* Es wurde ein Problem behoben, durch das der Text in Echtzeitberichten im Vollbildmodus angezeigt wurde. (AN-183168)

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Einschränkungen für Classification Rule Builder | Hinzugefügt am 5. Juni 2019 | Diese Beschränkungen sind nicht neu, wurden aber zur Dokumentation [hier hinzugefügt](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Einschränkungen des neuen Segmentoperators | Hinzugefügt am 31. Mai 2019 | Starting July 18, 2019, the segment operators _contains any of_, _does not contain any of_, _contains all of_ and _does not contain all_ of will be limited to 100 words per input field. Die Beschränkung wird nach diesem Datum auf alle neuen und geänderten Segmente angewendet. Vorhandene Segmente, die die Beschränkung überschreiten, werden weiterhin unterstützt, können jedoch erst geändert oder gespeichert werden, wenn das Eingabefeld reduziert wurde. Diese Grenzwerte werden im Rahmen kontinuierlicher Bemühungen zur Verbesserung der Abfrageleistung angewendet. |
| Bevorstehende Änderungen der Unterstützung für die Klassifizierungen **[!UICONTROL Datumsaktiviert]** und **[!UICONTROL Numerisch 2]** | Aktualisiert am 28. Mai 2019 | Die Möglichkeit, die Klassifizierungen „Numerisch 2“ und „Datumsaktiviert“ zu importieren, wurde aus der Codebasis entfernt. Diese Änderung wird mit der Wartungsversion vom Juli 2019 wirksam. Wenn die Importdatei die Spalte „Numerisch“ oder „Datumsaktiviert“ enthält, werden diese Zellen still ignoriert und alle anderen Daten in dieser Datei werden normal importiert. <br/>Vorhandene Classifications können weiterhin über den Standard-Classification-Arbeitsablauf exportiert werden und sind weiterhin in Berichten verfügbar. |
| Bevorstehende Änderung bei Berechnungen der _Berichtssumme_ | Aktualisiert am 9. Juli 2019 | Ab **18. Juni 2019** werden in Adobe Analytics Berechnungen von _Berichtssummen_ für alle Dimensionen und Metriken vereinheitlicht. Dadurch werden sich die Gesamtsummen bei manchen Berichten ändern (vor allem bei Berichten zu Eigenschaften oder Kundenattributen). Vor dieser Änderung kam es vor, dass in manchen Berichtssummen der Zeileneintrag _Unspecified_ uneinheitlich ein- oder ausgeschlossen wurde, und zwar unabhängig davon, ob _Unspecified_ im Bericht vorkam oder nicht. <br/>Ab 18. Juni 2019 wird _Nicht angegeben_ immer in Berichtssummen angezeigt, auch wenn dieser Wert nicht als Zeileneintrag im Bericht zu sehen ist. Darüber hinaus können Segmente, die die Logik _existiert_ oder _existiert nicht_ verwenden, für einige Dimensionen nach dieser Änderung andere Ergebnisse anzeigen, insbesondere Dimensionen, bei denen _Nicht angegeben_ einen speziellen Namen wie den Zeileneintrag „Eingegeben/Mit Lesezeichen versehen“ für die Dimension „Typ der verweisenden Stelle“ oder den Zeileneintrag „Sonstige“ für die Dimension „Gerätetyp“ verwendet werden. Diese Änderung betrifft Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder und die Reporting-API. |
| Aktualisierung von CSV-Downloads aus [!DNL Analysis Workspace] | 10. April 2019 | Ab dem 11. April 2019 wurden mehrere Änderungen an **[!UICONTROL CSV-Downloads]** (und **[!UICONTORL In Zwischenablage kopieren]**) in [!DNL Analysis Workspace] vorgenommen, um die Formatierung aus den exportierten Daten zu entfernen.  <ul><li>Das Tausendertrennzeichen ist nicht mehr enthalten. Das Dezimaltrennzeichen wird weiterhin enthalten sein und dem unter **[!UICONTROL Komponenten &gt; Berichtseinstellungen &gt; Tausendertrennzeichen]** definierten Format entsprechen. Hinweis: Numerische Werte, die ein Komma als Dezimaltrennzeichen verwenden, werden weiterhin in der exportierten CSV angegeben.</li><li>Es werden keine Währungssymbole angezeigt.</li><li>Es werden keine Prozentsymbole angezeigt. Prozentangaben werden in Dezimalform angezeigt. Zum Beispiel werden 75 % als 0,75 dargestellt.</li><li>Die Zeit wird in Sekunden angezeigt.</li><li>Kohortentabellen zeigen nur Rohwerte an. Prozentsätze werden entfernt.</li><li>Wenn eine Nummer ungültig ist, wird eine leere Zelle angezeigt.</li></ul> |
| Anstehende Änderung am Befehl „[!DNL Analysis Workspace] Debugger“ | 4. April 2019 | Der Konsolenbefehl zum Aktivieren des [!DNL Analysis Workspace] Debuggers wird am **13. Juni 2019** in adobeTools.debug.includeOberonXml geändert. adobe.tools.debug.includeOberonXml wird nach diesem Datum nicht mehr funktionieren. |
| Mobile Browser – Versionsnummern | 7. Februar 2019 | Am 8. Januar 2019 haben wir die Abschnittsebene bei den Versionsnummern mobiler Browser von 2 zu 1 geändert. Seit diesem Datum zeigen die Versionen nur die ersten beiden Ebenen an (Beispiel: _Firefox 64.0.2_ wird jetzt als _Firefox 64.0_ angegeben). |
| wird eingestellt [!DNL Ad Hoc Analysis] | 29. Januar 2019 | Am 6. August 2018 kündigte Adobe die Absicht an, [!DNL Ad Hoc Analysis] einzustellen. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist.<br/>Weitere Informationen dazu, welche Versionen von Java während dieses Zeitraums kompatibel sind, finden Sie unter [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Kurz-Links[!DNL Analytics] für Berichte | 14. Januar 2019 | Kurz-Links [!DNL Analytics]für Berichte, die innerhalb eines Jahres nicht aufgerufen wurden, werden entfernt und ab Donnerstag, den 17. Januar 2019 fortlaufend gelöscht. |
| Ende der Unterstützung für TLS 1.0 | Aktualisiert am 10. Januar 2019 | Ab dem 11. Februar 2019 unterstützt die Adobe Analytics-Berichterstellung die Verschlüsselung mit TLS (Transport Layer Security) 1.0 nicht mehr. Diese Änderung ist Teil unserer ständigen Bemühungen, die höchsten Sicherheitsstandards einzuhalten und die Daten unserer Kunden zu schützen. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/> Ab dem 20. Februar 2019 bietet die Adobe Analytics-Datenerfassung keine Unterstützung für TLS 1.0 mehr. Aufgrund dieser Änderung werden von Adobe keine [!DNL Analytics]Analytics-Daten von Endbenutzern mit älteren Geräten oder Webbrowsern ohne Unterstützung für TLS 1.1 oder höher erfasst. Wir gehen davon aus, dass dies keine wesentlichen Auswirkungen auf Kundendaten oder die Berichterstattung haben wird. (Wenn Ihre Website TLS 1.0 bereits nicht mehr unterstützt, sind Sie nicht betroffen.) <br/>Ab dem 11. April 2019 bietet die Reporting-API von Adobe Analytics keine Unterstützung mehr für die TLS 1.0-Verschlüsselung. Kunden, die auf die API zugreifen, sollten sicherstellen, dass sie nicht von den Auswirkungen betroffen sind. <ul><li>Für API-Clients, die Java 7 mit den Standardeinstellungen verwenden, müssen einige [Änderungen zur Unterstützung von TLS 1.2](https://www.java.com/en/configure_crypto.html) vorgenommen werden (siehe _„Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2“_.) </li><li>API-Clients, die Java 8 verwenden, sollten nicht beeinträchtigt sein, da die Standardeinstellung TLS 1.2 ist.</li><li> Bei API-Clients, die andere Frameworks verwenden, müssen Sie die Details zur Unterstützung von TLS 1.2 beim jeweiligen Anbieter erfragen.</li></ul> |
| Daten-Feed: Spalte „post_product_list“ – Änderung der Größe | 9. Januar 2019 | Adobe hat die Größe der Spalte „post_product_list“ am dem 7. Februar 2019 von 64 KB auf 16 MB erweitert. Diese Änderung stellt sicher, dass bei der Verarbeitung zu „post_product_list“ hinzugefügte Merchandising-eVar-Werte nicht zu abgeschnittenen Produkt- und Umsatzwerten führen. Wenn Sie über Prozesse verfügen, bei denen post_product_list-Werte erfasst werden, stellen Sie sicher, dass diese Prozesse Werte mit einer Länge von bis zu 16 MB verarbeiten können (ansonsten werden Werte bei 16 KB abgeschnitten), um Datenerfassungsfehler zu vermeiden. |
| Verwaltungsänderungen mit Auswirkung auf inaktive [!DNL Analytics Live Stream]-Endpunkte | 20. Dezember 2018 | Ab dem 1. Februar 2019 können [!DNL Live Stream]-Endpunkte, die 90 Tage lang keine aktive Verbraucherverbindung aufweisen, deaktiviert werden. Sie können sich an die Kundenunterstützung wenden, um sich über Ihre [!DNL Live Stream]-Endpunkte zu informieren und diese bei Bedarf wieder zu aktivieren. Stellen Sie außerdem sicher, dass für Ihre Verbraucherprozesse eine dauerhafte Verbindung besteht, wie es das Konzept des Dienstes vorsieht, und dass sie so implementiert sind, dass sie sich wieder verbinden, wenn die Verbindung getrennt oder unterbrochen wird. |
| Aktualisieren von Adobe [!DNL Report Builder] aufgrund der Einstellung des Supports für TLS 1.0 | 7. Sept. 2018 | Aufgrund der Unterstützung für TLS 1.0 sollten Benutzer von [!DNL Report Builder] die Version 5.6.21 vor Februar 2019 herunterladen. Nach diesem Datum sind frühere Versionen von [!DNL Report Builder] nicht mehr funktionstüchtig. |

### AppMeasurement {#appm}

[!UICONTROL Appmeasurement] 2.16.0 veröffentlicht am 8. August 2019.

| Funktion | Beschreibung |
| -----------| ---------- |
| `sendBeacon` Unterstützung für Exitlinks | Implementierung in `sendBeacon`[!UICONTROL appmeasurement] für Exitlinks wurde implementiert. Dies verbessert die Verfolgung von Ausstiegslinks und führt wahrscheinlich zu erhöhtem Traffic. |
| ECID/fid-Werte | ECID/fid-Werte werden jetzt beim ersten Treffer zwischengespeichert, auch wenn sich die optin-Einstellungen ändern. |
| DIL 9.3 | Aktualisiertes Zielgruppen-Management-Modul auf DIL 9.3 |
| Bildlaufverfolgung | Offengelegter Wechsel in s. activitymap. trackscrollreach, um Scroll-Reichweite ein- oder auszuwählen. |
| Besucher-ID-Service 4.4.0 | Aktualisierte appmeasurement für die Verwendung des Besucher-ID-Service 4.4.0. |

#### Fehlerbehebungen

* Es wurde ein Fehler in der appmeasurement-Warteschlange behoben, der auftrat, bevor isreadytotrack wahr war.

In der [Versionshistorie zu AppMeasurement](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html) finden Sie Informationen zu den verschiedenen Versionen von AppMeasurement auf den folgenden Plattformen:

* JavaScript
* iOS
* Android
* Flash-Flex
* OSX
* Windows Phone, XBOX, Silverlight und .NET
* [!DNL BlackBerry]
* Java
* PHP
* Symbian

## Audience Manager {#aam}

**Fehlerbehebungen und Verbesserungen**

* Die Registerkarte "Administration" wird nun nur Benutzern mit Administratorrechten angezeigt (AAM -48557).
* Die Listenbenutzer-API gibt jetzt vollständige Benutzerdetails zurück (AAM -48662).
* Sie können jetzt die Größe der Ordnerordnerliste ändern (AAM -48800).
* Mehrere Optimierungen für die Benutzeroberfläche der Benutzeroberfläche (AAM -48865, AAM -48933).
* Laden von Optimierungen für die Seiten Administration und Data Sources (AAM -48514).

## [!DNL Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Adobe Campaign Standard

[Campaign Standard 19.3 Release](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

| Funktion | Beschreibung |
| -----------| ---------- |  
| Externe API-Aktivität (öffentliche Beta-Version) | Zur tieferen Personalisierung ermöglicht die externe API-Aktivität Ihnen, Daten aus externen Systemen über einen REST-API-Aufruf in einen Workflow zu übertragen. Die REST-Endpunkte können ein Kundenverwaltungssystem, Adobe I/O Runtime oder Adobe Experience Cloud REST Endpunkt (z. B. Datenplattform, Target, Analytics, Kampagne) sein. Diese Funktion befindet sich derzeit in öffentlicher Hand. Weitere Informationen finden Sie in der [detaillierten Dokumentation](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) und in der [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html). |
| Bericht über das Workflow-Segment | Mit dieser Funktion können Marketingexperten ihre Bereitstellungsleistung nach Segmentcode aufschlüsseln. Wenn Sie einen Workflow erstellen und eine Segmentierungsaktivität verwenden, um der Auslieferungspopulation Segmente zuzuweisen, können diese Segmente nun dieselbe Auslieferung durchführen. Auf diese Weise können Sie die Statistiken zum Öffnen/Klicken auf Grundlage mehrerer Segmente innerhalb einer einzelnen Auslieferung anzeigen. Weitere Informationen finden Sie in der [detaillierten Dokumentation](https://docs.adobe.com/content/help/en/campaign-standard/using/reporting/customizing-reports/creating-a-report-workflow-segment.html) und in der [Videoanleitungen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/reporting/report-on-workflow-segments.html). |

### Adobe Campaign Classic

[Kampagne Classic 19.1.3 -](https://docs.campaign.adobe.com/doc/AC/en/RN.html) Build 9031

### Adobe Campaign-Systemsteuerung

[Neue Funktionen des Steuerungsbedienfelds](https://helpx.adobe.com/campaign/kb/control-panel-instance-settings.html) umfassen die Möglichkeit, urls hinzuzufügen, mit denen Kampagnen-Classic-Verbindungen für Daten-/Dateiübertragungen hergestellt werden können.

Beachten Sie, [!UICONTROL dass die Systemsteuerung] für die auf AWS gehosteten Adobe Campaign Classic- und Adobe Campaign Standard-Kunden verfügbar ist. Für die Zugriffssteuerung sind keine Upgrades erforderlich.

### Zusätzliche Ressourcen

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)