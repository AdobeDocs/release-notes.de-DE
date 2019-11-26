---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: release notes
last-update: November 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 836117dd47be9051044e0c07b960361a65c7b15f

---


# Adobe Experience Cloud – Versionshinweise, November 2019

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

> [!NOTE] Abonnieren Sie [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bald verfügbare Versionen benachrichtigt zu werden. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Releasedatum: 31. Oktober 2019**

* [Experience Cloud-Benutzeroberfläche](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**Aktualisiert am 26. November 2019**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (Links zur Lösungshilfe)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (Links zur Lösungshilfe)
* [!DNL Advertising Cloud](#adcloud) (Aktualisiert am 8.11.2019)

Suchen Sie nach der Hilfeseite? Siehe [Experience Cloud-Schulungen und -Support](https://helpx.adobe.com/support/experience-cloud.html).

## Experience Cloud-Benutzeroberfläche {#ecloud}

Versionshinweise für die Experience Cloud-Benutzeroberfläche und die Produktverwaltung.

* Die Feed-Seite wird im Dezember 2019 nicht mehr unterstützt. Innerhalb des Produkts finden Sie eine Benachrichtigung zur Einstellung. (MCUI-10039)
* Der Link [Weitere Informationen](https://www.adobe.com/marketing/campaign.html) für den App-Selektor in Adobe Campaign wurde aktualisiert. (MCUI-10034)
* Die Core-Plattform für die Experience Cloud-Schnittstelle läuft jetzt flüssiger. (MCUI-6822)
* Sicherheitslücken in der Benutzeroberfläche von Experience Cloud wurden behoben. (MCUI-9942)
* Es wurde ein kritischer Fehler in Kundenattributen behoben, der die Schemavalidierung für einige Kunden blockierte. (MCUI-10024, MCUI-6479)
* Aus der Zielgruppenbibliothek wurden Dimensionen entfernt, die für die Echtzeit-Erstellung von Zielgruppen nicht unterstützt werden. (MCUI-10046)

Die Produktdokumentation finden Sie auf der [Seite zu Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Versionshinweise für Experience Platform, Experience Platform Launch, Identity Service und Sicherheitsbulletins.

* [Experience Platform Launch](#launch)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/security.html) (Alle Adobe-Produkte)

### Experience Platform Launch {#launch}

Versionshinweise und die Produktdokumentation finden Sie unter [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## [!DNL Analytics] {#analytics}

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics](#aa-features)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices) (**Aktualisiert am 26. November 2019**)
* [AppMeasurement](#appm)

Eine Produktdokumentation finden Sie auf der [Startseite der Adobe Analytics-Hilfe](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics {#aa-features}

| Funktion | Beschreibung |
| -----------| ---------- | 
| Customer Journey Analytics | Am 21. November 2019 wird [Customer Journey Analytics](https://www.adobe.com/analytics/customer-journey-analytics.html) als Add-On für Adobe Analytics verfügbar.<br><br/>Customer Journey Analytics ermöglicht es Ihnen, Kundendaten von beliebigen Kanälen – sowohl online als auch offline – in Adobe Experience Platform zusammenzuführen und sie genauso zu analysieren wie Sie Ihre vorhandenen digitalen Daten aktuell anhand von Analysis Workspace analysieren. Mit Customer Journey Analytics können Sie steuern, wie Sie Ihre Online- und Offline-Daten in Analysis Workspace mit jeder beliebigen Kunden-ID verbinden. Dadurch können Sie Aufgaben wie Attribution, Segmentierung, Fluss- und Fallout-Steuerung etc. über Ihren gesamten Kundendatensatz hinweg in Adobe Analytics durchführen.<br><br/>Kunden von Analytics Select, Prime und Ultimate sind zum Erwerb dieses Zusatzprodukts qualifiziert. Weitere Informationen erhalten Ihren Ansprechpartnern beim Adobe Account Team. |
| Privacy Service API: CCPA | Der California Consumer Privacy Act (CCPA) erweitert die Datenschutzrechte und den Verbraucherschutz für Einwohner von Kalifornien, USA. Die neue Regelung tritt am 1. Januar 2020 in Kraft.<br><br/>Der CCPA bietet neue Datenschutzrechte, mit denen Verbraucher beispielsweise ihre personenbezogenen Daten einsehen und löschen oder herausfinden können, ob (und an wen) ihre Daten verkauft oder weitergegeben wurden, und mit denen sie dem Verkauf ihrer personenbezogenen Daten widersprechen können.<br><br/>Zur Vorbereitung auf den CCPA unterstützt der Datenschutzdienst Anfragen zur Abmeldung vom Verkauf personenbezogener Daten.<br><br/>„Privacy Service“ ist der neue Name des DSGVO-Dienstes; der Service behält alle vorherigen Funktionen und unterstützt jetzt auch den CCPA.<br/><br/>[CCPA in Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Übersicht über den Datenschutzdienst](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Datenschutz-Reporting: Analytics Admin Console | Wenn Sie das Datenschutz-Reporting für Analytics aktivieren, werden Report Suites verschiedene reservierte Variablen hinzugefügt.  Die Variablen unterstützen die Erfassung von Verbraucher-Einwilligungsdaten auf Trefferebene.<br><br/>Neue Dimensionen:<br/><ul><li>Einwilligungsmanagement Opt-out</li><li>Einwilligungsmanagement Opt-in</li><li>[Variablen des Einwilligungsmanagements](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| Audio- und Videoanalyse: Datenschutzunterstützung | Der Media Collection API wurden zwei neue Variablen hinzugefügt:<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>Mit diesen optionalen Variablen kann der Status der Benutzereinwilligung zum Zeitpunkt des Treffers erfasst werden.<br/><br/>[Dokumentation zur Medienerfassungs-API](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>Die neuen Kontextdatenvariablen für Analytics-Einwilligungsmanagement wurden dem Federated Analytics-Formular hinzugefügt. Diese Variablen können Sie jetzt verwenden, um Abmeldungen von der Weitergabe oder vom Verkauf von Daten für Federated Analytics zu kennzeichnen.<br/><br/>[Federated-Formular herunterladen](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### Fehlerbehebungen

* Fehlerkorrektur – Beim Löschen von Datumsbereichen eines unbekannten Nutzers tritt jetzt kein Fehler mehr auf. (AN-185540)

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Aktualisierung auf Dimensionsbezeichnungen "Monat"und "Quartal" | 26. November 2019 | Am 16. Januar 2020 werden die Dimensionsetiketten "Monat"und "Quartal"entsprechend dem Standardkalenderjahr aktualisiert. Benutzerdefinierte Kalendereinstellungen (definiert unter **[!UICONTROL Admin &gt; Report Suite &gt; Einstellungen bearbeiten &gt; Allgemein)** bestimmen weiterhin, welche Monate in einem Bericht zurückgegeben werden.<br>Wenn beispielsweise Ihr benutzerdefinierter Kalender für 2020 als Okt. 2019 bis September 2020 definiert ist, erscheinen Monate und Quartale in den Berichten wie folgt:<ul><li>Quartal - Oktober 2019-Dezember 2019, Januar 2020-März 2020, April 2020-Juni 2020, Juli 2020-September 2020</li><li>Monate - Oktober 2019, November 2019, Dezember 2019, Januar 2020, Februar 2020 usw.</li><li>Bisher hätten alle oben genannten Elemente das Jahr 2019 widergespiegelt, was zu Verwirrung für die Endnutzer geführt hätte.</li></ul>Wenn Sie Berichtsfilter oder Segmente haben, die nach diesen Werten suchen, müssen Sie keine Maßnahmen ergreifen. Sie werden entsprechend der neuen Benennungsregel aktualisiert. |
| Option **[!UICONTROL IP-Anmeldebeschränkungen erzwingen]** wird eingestellt | 21. November 2019 | Announcing the *October, 2020*, end-of-life date for the IP login whitelisting (**[!UICONTROL Enforce IP Login Restrictions]**) functionality under the **[!UICONTROL Admin &gt; Company Settings &gt; Security]** menu. (Dies wurde ursprünglich im Januar 2020 angekündigt.) |
| Option **[!UICONTROL Archiv anzeigen]** wird eingestellt | 30. Oktober 2019 | Die Option **[!UICONTROL Archiv anzeigen]** im Dashboard-Manager (**[!UICONTROL Komponenten &gt; Dashboards]**) wird im Januar 2020 eingestellt. |
| SameSite-Attribut für Cookies wird neu geregelt | 15. Oktober 2019 | Im August 2019 gab Adobe bekannt, dass für alle von Analytics festgelegten Cookies das SameSite-Attribut festgelegt wird. Die neue Logik wird angewendet, wenn:<ul><li>bei allen nicht auf WebKit basierenden Drittanbieter-Cookies das SameSite-Attribut festgelegt ist auf `none`.</li><li>für alle anderen Cookies nicht das SameSite-Attribut festgelegt ist.</li></ul> |
| Ende der Unterstützung für TLS 1.1 | 3. Oktober 2019 | Ab dem 31. März 2020 unterstützt Adobe Analytics TLS 1.1 nicht mehr. Diese Änderung ist Teil unserer laufenden Bemühungen, höchstmögliche Sicherheit von Kundendaten zu gewährleisten. |
| FTP-Broker in San Jose endet für London und Singapur | Juli 2020 | Für Kunden in London und Singapur wird die Datenvermittlung zwischen den beiden Städten und dem Rechenzentrum in San Jose ([ftp.omniture.com](ftp://ftp.omniture.com/)) nicht mehr unterstützt.<br/><ul><li>Für London verwenden Sie [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Für Singapur verwenden Sie [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Aktualisierung der Summen der Freiformtabellen in Analysis Workspace | 12. September 2019 | Ab Oktober 2019 werden in den Freiformtabellenzeilen „Gesamt“ die angewendeten [Berichtsfilter](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) berücksichtigt. Bisher wurde bei den Summen nur die Segmentierung berücksichtigt. Mit dieser Änderung werden auch die entsprechenden Visualisierungen aktualisiert (z. B. verknüpfte Darstellungen von [!UICONTROL Zusammenfassungen]) sowie exportierte CSV- und PDF-Daten. |
| Bevorstehende Änderung bezüglich des Felds `createDate` für Analytics-Benutzer | 30. August 2019 | Im Oktober oder November 2019 wird das Feld `createDate` für Analytics-Benutzer von der US Pacific Time auf einen korrekt formatierten Datums-/Uhrzeitwert mit Zeitzoneninformationen aktualisiert. (AN-183468) |
| Unterstützung für frühere Unterschiede bei Zeitzonen | 8. August 2019 | Analytics handhabt jetzt automatisch Unterschiede bei Zeitzonen für Treffer mit Zeitstempel. Nach dieser Änderung am 8. August müssen die unterschiedlichen Zeitzonen von Daten, die nachträglich verarbeitet werden sollen, nicht mehr vor dem Laden angepasst werden. |
| Einschränkungen für Classification Rule Builder | Hinzugefügt am 5. Juni 2019 | Diese Beschränkungen sind nicht neu, sondern wurden der Dokumentation [hier](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html) hinzugefügt. |
| Einschränkungen des neuen Segmentoperators | Hinzugefügt am 31. Mai 2019 | Ab dem 18. Juli 2019 sind die Segmentoperatoren _enthält beliebig viele_, _enthält keinerlei_, _enthält alle von_ und _enthält nicht alle_ auf 100 Wörter pro Eingabefeld beschränkt. Die Beschränkung wird nach diesem Datum auf alle neuen und geänderten Segmente angewendet. Vorhandene Segmente, die die Beschränkung überschreiten, werden weiterhin unterstützt, können jedoch erst geändert oder gespeichert werden, wenn das Eingabefeld reduziert wurde. Diese Grenzwerte werden im Rahmen kontinuierlicher Bemühungen zur Verbesserung der Abfrageleistung angewendet. |
| Änderungen der Unterstützung für die Classifications **[!UICONTROL Datumsaktiviert]** und **[!UICONTROL Numerisch 2]** | Aktualisiert am 28. Mai 2019 | Die Möglichkeit, die Klassifizierungen „Numerisch 2“ und „Datumsaktiviert“ zu importieren, wurde aus der Codebasis entfernt. Diese Änderung wurde mit der Wartungsversion vom Juli 2019 wirksam. Wenn die Importdatei die Spalte „Numerisch“ oder „Datumsaktiviert“ enthält, werden diese Zellen still ignoriert und alle anderen Daten in dieser Datei werden normal importiert. <br/>Vorhandene Classifications können weiterhin über den Standard-Classification-Arbeitsablauf exportiert werden und sind weiterhin in Berichten verfügbar. |
| Änderung bei Berechnungen der _Berichtssumme_ | Aktualisiert am 9. Juli 2019 | Am **18. Juni 2019** wurden in Adobe Analytics die Berechnungen von _Berichtssummen_ für alle Dimensionen und Metriken vereinheitlicht. Dadurch änderten sich die Gesamtsummen bei manchen Berichten (vor allem bei Berichten zu Eigenschaften oder Kundenattributen). Vor dieser Änderung kam es vor, dass in manchen Berichtssummen der Zeileneintrag _Unspecified_ uneinheitlich ein- oder ausgeschlossen wurde, und zwar unabhängig davon, ob _Unspecified_ im Bericht vorkam oder nicht. <br/>Ab 18. Juni 2019 wird _Nicht angegeben_ immer in Berichtssummen angezeigt, auch wenn dieser Wert nicht als Zeileneintrag im Bericht zu sehen ist. Darüber hinaus können Segmente, die die Logik _existiert_ oder _existiert nicht_ verwenden, für einige Dimensionen nach dieser Änderung andere Ergebnisse anzeigen, insbesondere Dimensionen, bei denen _Nicht angegeben_ einen speziellen Namen wie den Zeileneintrag „Eingegeben/Mit Lesezeichen versehen“ für die Dimension „Typ der verweisenden Stelle“ oder den Zeileneintrag „Sonstige“ für die Dimension „Gerätetyp“ verwendet werden. Diese Änderung betrifft Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder und die Reporting-API. |
| Aktualisierung von CSV-Downloads aus Analysis Workspace | 10. April 2019 | Ab dem 11. April 2019 wurden mehrere Änderungen an **[!UICONTROL CSV-Downloads]** (und **[!UICONTORL In Zwischenablage kopieren]**) in Analysis Workspace vorgenommen, um die Formatierung aus den exportierten Daten zu entfernen.  <ul><li>Das Tausendertrennzeichen ist nicht mehr enthalten. Das Dezimaltrennzeichen wird weiterhin enthalten sein und dem unter **[!UICONTROL Komponenten &gt; Berichtseinstellungen &gt; Tausendertrennzeichen]** definierten Format entsprechen. Hinweis: Numerische Werte, die ein Komma als Dezimaltrennzeichen verwenden, werden weiterhin in der exportierten CSV angegeben.</li><li>Es werden keine Währungssymbole angezeigt.</li><li>Es werden keine Prozentsymbole angezeigt. Prozentangaben werden in Dezimalform angezeigt. Zum Beispiel werden 75 % als 0,75 dargestellt.</li><li>Die Zeit wird in Sekunden angezeigt.</li><li>Kohortentabellen zeigen nur Rohwerte an. Prozentsätze werden entfernt.</li><li>Wenn eine Nummer ungültig ist, wird eine leere Zelle angezeigt.</li></ul> |
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
| [Verbesserungen bei den Regeln zur Profilzusammenführung](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | Adobe hat eine Reihe von Verbesserungen für die [!UICONTROL Regeln zur Profilzusammenführung] veröffentlicht: <ul><li>Die Bewertung von Segmenten wird nun für Batches mit bis zu 100 Geräten unterstützt.</li><li>Die Genauigkeit von Berichten zur Eigenschafts- und Segmentpopulationen wurde optimiert.</li><li>Die Genauigkeit von Batch-Dateien, die mit geräteübergreifenden IDs generiert wurden, wurde optimiert.</li><li>Die Dokumentation wurde mit detaillierteren Anwendungsfällen für die einzelnen Regeln aktualisiert. Siehe [Allgemeine Anwendungsfälle für Regeln zur Profilzusammenführung](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html), [Anwendungsbeispiele für Diagramme externer Geräte](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html) und [Anwendungsfälle des Profillink-Gerätediagramms](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html).</li></ul> |
| [Intelligente Recommendations für Audience Marketplace-Daten, powered by Adobe Sensei](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/trait-recommendations.html) | Bei Eigenschaftsempfehlungen erhalten Sie jetzt beim Erstellen oder Bearbeiten eines Segments in [Segment Builder](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/segment-builder.html) Empfehlungen zu zusätzlichen Eigenschaften, die Sie aus nicht abonnierten [!UICONTROL Audience Marketplace]-Daten-Feeds einbeziehen können. Fügen Sie die empfohlenen Eigenschaften zu Ihrem Segment hinzu, um Ihre Zielgruppe zu erweitern. <br>Darüber hinaus haben wir die [!UICONTROL Marketplace]-Seite neu gestaltet, um Ihnen das Finden ähnlicher Eigenschaften und das Filtern von Daten-Feeds zu erleichtern. |
| [Tools für die Massenverarbeitung](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | Ein neues Arbeitsblatt zur Massenverwaltung wurde veröffentlicht, das mit MacOS- und Windows-Betriebssystemen verwendet werden kann und die Experience Cloud-Anmeldung unterstützt. |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/en/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | Es wurde Unterstützung für [!DNL HTTP Strict-Transport-Security] ergänzt, eine Web-Sicherheitsrichtlinie, die Schutz vor Cookie-Hijacking und Protocol-Downgrade-Angriffen bietet. |

### Verbesserungen {#aam-enhancements}

Ab November 2019 unterstützt Audience Manager auch das Senden von Roku-IDs, Amazon Fire TV-IDs und Xbox-/Microsoft-IDs an Google Ad Manager- und DV360-Ziele zusätzlich zu den schon zuvor unterstützten Cookie-, IDFA- und GAID-Geräte-IDs. Sie müssen keine Änderungen an Ihren vorhandenen Google-Integrationen vornehmen.

In Audience Manager werden Roku-IDs, Amazon Fire TV-IDs und Xbox-/Microsoft-IDs als globale Geräte-IDs bezeichnet. Weitere Informationen zu diesen IDs und den Datenquellen, mit denen sie verknüpft sind, finden Sie in der Produktdokumentation zu Audience Manager:

* [Globale Geräte-IDs](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html#global-device-ids)
* [Globale Data Sources](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html)

Die Datenerfassung für die Datenquellen Roku, Amazon Fire TV und Xbox/Microsoft funktioniert genauso wie für IDFA und GAID: eine Audience Manager-ID wird automatisch generiert und mit der DAID verknüpft, wenn entsprechende Daten aufgenommen werden. Die neuen IDs werden automatisch an die vorhandenen und neuen Google-Ziele gesendet, die in Ihrem Konto konfiguriert sind.

Weitere Informationen erhalten Sie von Ihrem Audience Manager-Berater oder der Kundenunterstützung.

### Fehlerbehebungen und Verbesserungen {#aam-fixes-and-improvements}

* Es wurde ein Fehler in Audience Marketplace behoben, durch den die Benutzeroberfläche den Fehler 409 ausgab, wenn Kunden ihre Monatsabrechnung der genutzten Segmente einreichte. (AAM-50825)
* Es wurde ein Fehler bei abgeleiteten Signalen behoben, durch den Kunden kurzzeitig keine neuen abgeleiteten Signale erstellen konnten. (AAM-50968)
* Es wurde ein Fehler in People-Based Destinations behoben, durch den Kunden den Namen eines Ziels nicht ändern konnten. (AAM-51025)
* Es wurde ein Fehler behoben, durch den einige Benutzer für die Anmeldung bei der Benutzeroberfläche von Audience Manager ein dupliziertes Konto erhalten haben. Aufgrund der Berechtigungen, die für duplizierte Konten zugewiesen werden, konnten diese Benutzer auf einige Teile der Benutzeroberfläche nicht zugreifen und Aktionen durchführen. (AAM-50818)
* Im Zusammenhang mit der Barrierefreiheit der Audience Manager-Benutzeroberfläche wurden weitere Verbesserungen vorgenommen. (AAM-48932, AAM-48997, AAM-49043, AAM-49054, AAM-49371, AAM-49375, AAM-51313)

## Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktversionen

* **Brand Portal 6.4.5**

   Adobe Experience Manager Assets Brand Portal Version 6.4.5 ermöglicht es Brand Portal-Nutzern (externe Agenturen/Teams), Inhalte in Brandportal hochzuladen und in AEM Assets zu veröffentlichen, ohne dass sie auf die Autorenumgebung zugreifen müssen. Diese Funktion wird als [Asset-Beschaffung in Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html) bezeichnet und verbessert die Kundenerlebnisse, indem eine bidirektionale Methode zur Verfügung gestellt wird, mit der Benutzer Assets beitragen und für andere rund um den Globus verteilte Brand Portal-Benutzer freigeben können.

   Siehe [Neue Funktionen in AEM Assets Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/whats-new.html).

   Siehe [Versionshinweise](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html).

* **AEM Forms-Dienst zur automatischen Formularumwandlung**

   Der Dienst für die automatische Formularumwandlung beschleunigt die Digitalisierung und Modernisierung von Erlebnissen mit Datenerfassung, indem dieser PDF-Formulare in adaptive Formulare konvertiert. Gestützt durch Adobe Sensei konvertiert der Dienst Ihre PDF-Formulare automatisch in für verschiedene Geräte optimierte, responsive und HTML5-basierte adaptive Formulare. Unter Nutzung vorhandener Investitionen in PDF-Formulare und XFA-Formularvorlagen wendet der Dienst außerdem die passenden Validierungen, Layouts und adaptiven Formularfelder anwendet.

   Siehe [Automatische Formularumwandlung in Adobe Experience Manager Forms](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html).

* **Cloud Manager 2019.10.0**

   Die allgemeinen Versionshinweise für Cloud Manager 2019.10.0 sind jetzt verfügbar. Darin sind außerdem die Aktualisierungen bezüglich der Implementierungsschritte sowie der Handhabung von unterschiedlichen Versionen von Maven-Projekten aufgeführt.

   Siehe [Versionshinweise zu Cloud Manager 2019.10.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html).

### Selbsthilfe

* **Activity Map**

   Aufgrund von sicherheitsbezogenen Anpassungen in der Adobe Analytics-API kann die in AEM enthaltene Version von Activity Map nicht mehr verwendet werden. Siehe dazu die Dokumentation zum [Herstellen einer Verbindung zu Adobe Analytics](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics).

   Sie sollten fortan das [Activity Map-Browser-Plugin](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html) für Chrome, Firefox oder Internet Explorer verwenden, das von Adobe Analytics bereitgestellt wird.

* **Best-Practice-Handbuch für AEM Screens-Projekte**

   Das neue _Best-Practice-Handbuch für AEM Screens_ bietet umfassende Einblicke und praktische Ratschläge zur Konzeptionierung, Entwicklung und Einbindung vorsätzlicher Kundenerlebnisse in Ihre Digital-Signage-Implementierung. Darüber hinaus wird erläutert, wie Sie mithilfe von Best Practices Ihr Unternehmen voranbringen, während Sie gleichzeitig ein Digital-Signage-Projekt in AEM Screens bereitstellen.

   Siehe [Best-Practice-Handbuch für AEM Screens-Projekte](https://docs.adobe.com/content/help/en/experience-manager-screens/using/about-guide.html).

* **Headless-Erlebnis-Management**

   Die Funktionen des [Remote-Content-Renderers](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848), der für die serverseitige Wiedergabe von Single Page Applications verwendet wird, sind jetzt dokumentiert.

* **SPA und serverseitiges Rendering**

   Sie können den Dienst für das Remote-Content-Rendering, das Ihre AEM-basierten SPAs für das serverseitige Rendering verwenden, entsprechend Ihren Anforderungen erweitern und anpassen.

   Siehe [SPA und serverseitiges Rendering](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer).

* **AEM Projektarchetyp**

   Der AEM Projektarchetyp erstellt ein auf Best Practices basierendes Adobe Experience Manager-Minimalprojekt als Ausgangspunkt für Ihre eigenen AEM-Projekte. Über die Eigenschaften, die bei Verwendung dieses Archetyps angegeben werden müssen, können Sie die Namen für alle Teile dieses Projekts angeben sowie bestimmte optionale Funktionen steuern.

   Siehe [AEM Projektarchetyp](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html).

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

Aktualisiert für die Version vom 8. November 2019

| Ansicht | Funktion |
|------|---------|
| Konversions-Tracking | Das JavaScript-basierte Advertising Cloud-Zuordnungstag für Konversionen unterstützt jetzt das Tracking von Klicks aus Mozilla Firefox Version 69 und höher, in der Drittanbieter-Cookies standardmäßig blockiert werden. Das gleiche Tag unterstützt bereits Apple Safari.<br><br/>Wenn Sie das Advertising Cloud-Konversions-Tracking verwenden und das Advertising Cloud-Konversions-Zuordnungstag noch nicht implementiert haben, implementieren Sie den folgenden Code auf allen Landingpages:<br></br>`<script src="//www.everestjs.net/static/amo-conversion-mapper.js"></script>`<br></br>Hinweis: Dieses Tag unterstützt Konversions-Tracking-Tags der JavaScript-Version 2 und 3 der Advertising Cloud, nicht aber das Bild-Tracking-Tag. |
| Portfolios | Wenn die Portfoliooption „Enable campaign max spend % target“ aktiviert ist, wird das maximale Ausgabenziel jetzt nicht mehr überschritten. Bisher überschritt Advertising Cloud das maximale Ausgabenziel, wenn dies optimal war. |
| Zielgruppen suchen | Ihre Zielgruppenbibliothek unter „Suche“ &gt; „Zielgruppen“ &gt; „Bibliothek“ enthält jetzt automatisch die Spalte „Zielgruppengröße“, die täglich mit Daten von Bing Ads und Google Ads gefüllt wird. Optional können Sie die Spalte als Datenfilter verwenden. |
| Integration in Adobe Analytics | Analytics enthält jetzt für Advertising Cloud DSP-Kampagnen die Dimension „Landing Type (AMO ID)“.  Sie können diese Dimension zur Segmentierung von Analytics-Metriken verwenden. Sie gibt an, wie Besucher auf eine Site einstiegen. Zu den Werten gehören „Click Through“ und „View Through“.<br><br/>**Hinweis:** Daten für View-Throughs, die vor dem 31. Oktober 2019 erfasst wurden, werden als Daten für Click-Throughs angezeigt. Daher empfehlen wir nicht, diese Dimension mit Daten zu verwenden, die vor Mitte November 2019 erfasst wurden. |
