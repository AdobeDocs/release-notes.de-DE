---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: Versionshinweise
last-update: . November 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 2c6076aa0af7b9a273e31b1f8919e006ff48e6b4

---


# Vorzeitiger Zugriff - Versionshinweise zu Adobe Experience Cloud - November 2019

> [!IMPORTANT] Diese Seite enthält Inhalte einer Vorabversion und kann vor der geplanten Veröffentlichung der Version geändert werden.

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

> [!NOTE] Abonnieren Sie [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bald verfügbare Versionen benachrichtigt zu werden. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Releasedatum: 30. Oktober 2019**

* [Experience Cloud-Benutzeroberfläche](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (Links zur Lösungshilfe)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (Links zur Lösungshilfe)
* [!DNL Advertising Cloud](#adcloud)

## Experience Cloud-Benutzeroberfläche {#ecloud}

Versionshinweise für die Experience Cloud-Benutzeroberfläche und die Produktverwaltung.

* Die Feed-Seite wird im Dezember 2019 nicht mehr unterstützt. Suchen Sie nach einem Hinweis zur Produktvernichtung. (MCUI-10039)
* Der Link [Mehr](https://www.adobe.com/marketing/campaign.html) erfahren für Adobe Campaign wurde über die App-Auswahl aktualisiert. (MCUI-10034)
* Verbesserte Stabilität und Reaktionsgeschwindigkeit der Hauptplattform für die Experience Cloud-Schnittstelle. (MCUI-6822)
* Sicherheitslücken in der Benutzeroberfläche der Experience Cloud wurden behoben. (MCUI-9942)
* Es wurde ein kritischer Fehler in Kundenattributen behoben, der die Schemabeüberprüfung für einige Kunden blockierte. (MCUI-10024, MCUI-6479)
* Die Zielgruppenbibliothek wurde verbessert, um Dimensionen zu entfernen, die für die Erstellung von Zielgruppen in Echtzeit nicht unterstützt werden. (MCUI-10046)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Versionshinweise für Experience Platform, Experience Platform Launch, Identity Service und Sicherheitsbulletins.

* [Experience Platform Launch](#launch)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/security.html) (Alle Adobe-Produkte)

### Experience Platform Launch {#launch}

Versionshinweise und die Produktdokumentation finden Sie unter [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html).

## [!DNL Analytics] {#analytics}

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics](#aa-features)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [AppMeasurement](#appm)

Eine Produktdokumentation finden Sie auf der [Startseite der Adobe Analytics-Hilfe](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics {#aa-features}

| Funktion | Beschreibung |
| -----------| ---------- | 
| Customer Journey Analytics | Am 21. November 2019 stellt Adobe [Customer Journey Analytics](https://www.adobe.com/analytics/customer-journey-analytics.html) als Add-On zu Adobe Analytics zur Verfügung.<br><br/>Customer Journey Analytics ermöglicht Ihnen, alle Kundendaten von jedem beliebigen Kanal zu bringen — sowohl online als auch offline — in die Adobe Experience Platform ein und analysieren Sie diese Daten dann genau so, wie Sie Ihre vorhandenen digitalen Daten heute mithilfe des Analysis Workspace nutzen würden. Customer Journey Analytics bietet Ihnen die Möglichkeit, zu steuern, wie Sie Ihre Online- und Offline-Daten im Analysis Workspace mit einer beliebigen Kunden-ID verbinden, wodurch Sie letztendlich Zuordnungen, Segmentierung, Fluss, Trichteranalyse usw. vornehmen können. über Ihren gesamten Kundendatensatz in Adobe Analytics.<br><br/>Kunden von Analytics Select, Prime und Ultimate sind zum Kauf dieses Zusatzprodukts berechtigt. Weitere Informationen erhalten Sie von Ihrem Adobe-Kundenbetreuungsteam. |
| Privacy Service API: CCPA | Der California Consumer Privacy Act (CCPA) erweitert die Datenschutzrechte und den Verbraucherschutz für Einwohner von Kalifornien, USA. Die neue Regelung tritt am 1. Januar 2020 in Kraft.<br><br/>Der CCPA bietet neue Datenschutzrechte, mit denen Verbraucher beispielsweise ihre personenbezogenen Daten einsehen und löschen oder herausfinden können, ob (und an wen) ihre Daten verkauft oder weitergegeben wurden, und mit denen sie dem Verkauf ihrer personenbezogenen Daten widersprechen können.<br><br/>Zur Vorbereitung auf den CCPA unterstützt der Datenschutzdienst Anfragen zur Abmeldung vom Verkauf personenbezogener Daten.<br><br/>„Privacy Service“ ist der neue Name des DSGVO-Dienstes; der Service behält alle vorherigen Funktionen und unterstützt jetzt auch den CCPA.<br/><br/>[CCPA in Analytics](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/an-ccpa-overview.html)<br><br/>[Übersicht über den Datenschutzdienst](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Datenschutz-Reporting: Analytics Admin Console | Wenn Sie das Datenschutz-Reporting für Analytics aktivieren, werden Report Suites verschiedene reservierte Variablen hinzugefügt.  Die Variablen unterstützen die Erfassung von Verbraucher-Einwilligungsdaten auf Trefferebene.<br><br/>Neue Dimensionen:<br/><ul><li>Einwilligungsmanagement Opt-out</li><li>Einwilligungsmanagement Opt-in</li><li>[Variablen des Einwilligungsmanagements](https://docs.adobe.com/content/help/en/analytics/admin/data-governance/consent-variables.html)</li></ul> |
| Audio- und Videoanalyse: Datenschutzunterstützung | Der Media Collection API wurden zwei neue Variablen hinzugefügt:<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul><br/><br/>Mit diesen optionalen Variablen kann der Status der Benutzereinwilligung zum Zeitpunkt des Treffers erfasst werden.<br/><br/>[Dokumentation zur Medienerfassungs-API](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/><br/>Die neuen Kontextdatenvariablen für Analytics-Einwilligungsmanagement wurden dem Federated Analytics-Formular hinzugefügt. Diese Variablen können Sie jetzt verwenden, um Abmeldungen von der Weitergabe oder vom Verkauf von Daten für Federated Analytics zu kennzeichnen.<br/><br/>[Federated-Formular herunterladen](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |

#### Fehlerbehebungen

* Es wurde ein Fehler behoben, der beim Löschen von Datumsbereichen, die "Unbekannter Benutzer"gehörten, zu einem Fehler führte. (AN-185540)

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| EOL of **[!UICONTROL View Archive]** Option | 30. Oktober 2019 | Bei der Ankündigung des Enddatums Januar 2020 für die Option Archiv **** anzeigen im Dashboard-Manager ("**[!UICONTROL Komponenten"&gt; "Dashboards]**"). |
| EOL der Option **[!UICONTROL IP-Anmeldebeschränkungen]** erzwingen | 30. Oktober 2019 | Bei der Ankündigung des Enddatums für die IP-Anmeldung in der Whitelist-Funktion (IP-Anmeldebeschränkungen **[!UICONTROL erzwingen]**) unter " **[!UICONTROL Admin"&gt; "Unternehmenseinstellungen"&gt; "Sicherheit]** ". |
| Verarbeitung zu SameSite-Attribut für Cookies aktualisiert | 15. Oktober 2019 | Im August 2019 gab Adobe bekannt, dass die Einstellung "SameSite-Cookie"allen von Analytics eingerichteten Cookies hinzugefügt wurde. Eine Aktualisierung der Logik wird angewendet, wenn:<ul><li>Bei allen Drittanbieter-Cookies, die nicht auf Webkit basieren, ist das Attribut SameSite auf `none`eingestellt.</li><li>Für alle anderen Cookies ist nicht das Attribut SameSite festgelegt.</li></ul> |
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

Neue in Audience Manager verfügbare Funktionen, Verbesserungen und Fehlerbehebungen.

| Funktion | Beschreibung |
|--- |----|
| [Erweiterungen der Profile Merge Rules](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rules-overview.html) | Wir haben eine Reihe von Verbesserungen für [!UICONTROL Regeln]zur Profilzusammenführung veröffentlicht: <ul><li>Die Segmentbewertung wird jetzt für bis zu 100 Geräte im Batch unterstützt.</li><li>Wir haben die Berichtsgenauigkeit für Eigenschaften- und Segmentpopulationen verbessert.</li><li>Die Genauigkeit von Batch-Dateien, die mit geräteübergreifenden IDs generiert wurden, wurde verbessert.</li><li>Die Dokumentation wurde mit detaillierteren Anwendungsfällen für jede Regel aktualisiert. Siehe [Allgemeine Anwendungsfälle für Regeln](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/merge-rule-targeting-options.html)zur Profilzusammenführung, Anwendungsfälle[für ](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/external-graph-use-cases.html)externe Gerätediagramme und Anwendungsfälle für [Profillinkdiagramme](https://docs.adobe.com/help/en/audience-manager/user-guide/features/profile-merge-rules/profile-link-use-case.html).</li></ul> |
| [Massenverwaltungswerkzeuge](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) | Wir haben eine neue Version des Bulk Management-Arbeitsblatts herausgegeben, das auf MacOS- und Microsoft Windows-Betriebssystemen funktioniert und die Experience Cloud-Anmeldung unterstützt. |
| [HTTP Strict-Transport-Security](https://docs.adobe.com/help/en/audience-manager/user-guide/overview/data-security-and-privacy/data-security.html#hsts) | Wir haben Unterstützung für [!DNL HTTP Strict-Transport-Security]eine Web-Sicherheitsrichtlinie hinzugefügt, die vor Cookie-Hijacking und Protokoll-Downgrade-Angriffen schützt. |

**Fehlerbehebungen und Verbesserungen**

* Es wurde ein Fehler in Audience Marketplace behoben, durch den die Benutzeroberfläche den Fehler 409 zurückgab, als Kunden die monatliche Segmentnutzung einreichten. (AAM-50825)
* Es wurde ein Fehler in Abgeleiteten Signalen behoben, durch den Kunden kurzfristig keine neuen abgeleiteten Signale erstellen konnten. (AAM-50968)
* Es wurde ein Fehler in People-Based Destination behoben, durch den Kunden den Namen eines Ziels nicht ändern konnten. (AAM-51025)
* Es wurde ein Fehler behoben, durch den einige Benutzer doppelte Konten hatten, um sich bei der Benutzeroberfläche von Audience Manager anzumelden. Aufgrund der Berechtigungen, die mit den duplizierten Konten verknüpft sind, konnten diese Benutzer nicht auf einige Teile der Benutzeroberfläche zugreifen und Vorgänge durchführen. (AAM-50818)
* Die Zugänglichkeit der Benutzeroberfläche von Audience Manager wurde weiter verbessert. (AAM-48932, AAM-49043, AAM-49054, AAM-49371, AAM-49375)

## Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktversionen

* **Brand Portal 6.4.5**

   Adobe Experience Manager Assets Brand Portal 6.4.5 ist eine Version mit Funktionen, die Benutzern von Markenportalen (externe Agenturen/Teams) die Möglichkeit geben soll, Inhalte in das Markenportal hochzuladen und auf AEM Assets zu veröffentlichen, ohne auf die Autorenumgebung zugreifen zu müssen. Diese Funktion wird als [Asset-Sourcing im Markenportal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/using-asset-sourcing/brand-portal-overiew-using-asset-sourcing.html)bezeichnet und verbessert die Kundenerfahrung, indem eine bidirektionale Methode zur Verfügung gestellt wird, mit der Benutzer Assets mit anderen global verteilten Markenportalen-Benutzern teilen und hinzufügen können.

   Siehe [Neue Funktionen im AEM Assets-Markenportal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/whats-new.html).

   See [Release notes](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html).

* **Automatisierter Konvertierungsdienst für AEM Forms**

   Der Dienst "Automatisierte Formularkonvertierung"beschleunigt die Digitalisierung und Modernisierung der Datenerfassungserfahrung durch die automatische Konvertierung von PDF-Formularen in adaptive Formulare. Der Dienst mit Adobe Sensei konvertiert Ihre PDF-Formulare automatisch in gerätefreundliche, reaktionsfähige und HTML5-basierte adaptive Formulare. Bei der Nutzung der vorhandenen Investitionen in PDF-Formulare und XFA wendet der Dienst während der Konvertierung auch geeignete Überprüfungen, Stile und Layouts auf adaptive Formularfelder an.

   Siehe Automatischer Konvertierungsdienst für [Adobe Experience Manager Forms](https://docs.adobe.com/content/help/en/aem-forms-automated-conversion-service/table-of-contents/introduction.html).

* **Cloud Manager 2019.10.0**

   Die allgemeinen Versionshinweise für Cloud Manager 2019.10.0 sind jetzt verfügbar. In den Hinweisen werden auch Aktualisierungen der Implementierungsschritte und die Handhabung der Projektversion aufgeführt.

   Siehe [Cloud Manager 2019.10.0 - Versionshinweise](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html).

### Selbsthilfe

* **Activity Map**

   Aufgrund von Sicherheitsänderungen in der Adobe Analytics-API ist es nicht mehr möglich, die in AEM enthaltene Version von Activity Map zu verwenden. Siehe [Verbindung zu Adobe Analytics](https://helpx.adobe.com/experience-manager/6-5/sites/administering/using/adobeanalytics-connect.html#ConfiguringtheConnectiontoAdobeAnalytics)konfigurieren.

   Sie sollten jetzt das [Activity Map-Browser-Plugin](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/getting-started/get-started-users/activitymap-install.html) für Chrome, Firefox oder Internet Explorer verwenden, wie von Adobe Analytics bereitgestellt.

* **Anleitung zu Best Practices für AEM Screens-Projekte**

   Der neue Leitfaden für _Best Practices für AEM Screens_ bietet umfassende Einblicke und praktische Ratschläge zur Vorstellung, Entwicklung und Einbindung vorsätzlicher Kundenerlebnisse in Ihre digitale Signaturimplementierung. Darüber hinaus wird erläutert, wie Sie mithilfe bewährter Verfahren positive Auswirkungen auf Ihr Unternehmen erzielen können, während Sie gleichzeitig ein Projekt zur digitalen Signatur in AEM Screens bereitstellen.

   Siehe [Best Practices-Handbuch für AEM Screens-Projekte](https://docs.adobe.com/content/help/en/experience-manager-screens/using/about-guide.html).

* **Headless Experience Management**

   Funktionen des [Remote Content Renderer](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#main-pars_header_450130848) , der für die serverseitige Wiedergabe von Einzelseitenanwendungen verwendet wird, sind jetzt dokumentiert.

* **SPA und serverseitiges Rendering**

   Sie können den Renderdienst für Remote-Inhalte, den Ihre AEM-basierten SPAs für das serverseitige Rendering verwenden, erweitern und anpassen, um Ihren Anforderungen zu entsprechen.

   Siehe [SPA- und serverseitiges Rendering](https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/spa-ssr.html#RemoteContentRenderer).

* **AEM Project Archetyp**

   Der AEM Project Archetype erstellt ein Adobe Experience Manager-Projekt mit minimalen Best Practices als Ausgangspunkt für Ihre eigenen AEM-Projekte. Mit den Eigenschaften, die bei Verwendung dieses Archetyps angegeben werden müssen, können Sie die Namen für alle Teile dieses Projekts angeben sowie bestimmte optionale Funktionen steuern.

   Siehe [AEM-Projektarchiv](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/archetype/overview.html).

* **Aktualisierungen der AEM-Dokumentation**

   Lesen Sie mehr über wichtige Dokumentationsänderungen und Aktualisierungen für Adobe Experience Manager in den letzten drei Monaten.

   Siehe [AEM-Dokumentation: Jüngste Aktualisierungen der Dokumentation](https://helpx.adobe.com/experience-manager/documentation-updates.html).

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

Aktualisiert für die Version vom 12. Oktober 2019

| Ansicht | Funktion |
|------|---------|
| Search-Kampagnen | Advertising Cloud kann jetzt Tracking auf Anzeigenebene synchronisieren und für Konten im Yahoo! Japan Display Network bereitstellen. Wenn Sie für ein Konto Anmeldeinformationen angeben, stehen alle vorhandenen Kampagnen, Anzeigengruppen und Anzeigen in diesem Konto in den Kampagnen-Management-Ansichten schreibgeschützt zur Verfügung. In den Kampagnen-Management-Ansichten sowie in einfachen und erweiterten Berichten werden Klicks, Kosten, Konversionen und andere Leistungsdaten bereitgestellt. |
|  | (Werbetreibende mit Google Analytics) Advertising Cloud Search kann Konversionsmetriken für ein bestimmtes Google Analytics-Konto, eine bestimmte Eigenschaft und eine bestimmte Kombination von Ansichten zur Optimierung und zum Reporting synchronisieren. Seitenansichten, Sitzungen, Absprungraten (berechnet als Absprünge/Sitzungen) und Sitzungsdauer werden automatisch einbezogen. Sie können bis zu 16 zusätzliche Metriken pro Datenquelle einbeziehen. |
|  | (Vorhandene Google Ads-Konten für Werbetreibende mit einer Integration von Advertising Cloud und Adobe Analytics) Für den s_kwcid-Trackingcode ist ein neues Format verfügbar, durch das Advertising Cloud Kontodaten unter Verwendung der Adobe Analytics-Reporting- und Analysefunktion teilen kann. Das aktuelle Format enthält Parameter für die Kampagnen-ID und Anzeigengruppen-ID, die erforderlich sind, um in Analytics auf Kampagnen- und Anzeigengruppenebene präzise Berichte für Google-Kampagnenentwürfe und -tests zu erstellen. Wenn Ihre bestehenden Google-Konten Google-Kampagnenentwürfe und -tests enthalten, bearbeiten Sie die Konto-Tracking-Einstellungen für jedes einzelne Konto, um zum neuen s_kwcid zu migrieren. Wenn Sie keine Google-Kampagnenentwürfe und -tests haben, ist die Migration zum neuen Format optional. Hinweis: Alle neuen Google-Konten verwenden automatisch das neue Format. |
| Advanced Campaign Management (ACM) von Search | (Google Ads-Kampagnen) Sie können jetzt die Suffixe der finalen URL auf Kampagnenebene für Google-Textanzeigen und Shopping-Anzeigenvorlagen konfigurieren. |
|  | (Google Ads-Kampagnen) Die optionalen Felder „Überschrift 3“ und „Beschreibung 2“ stehen für erweiterte Google-Textanzeigen zur Verfügung. |
| Berichte | Die folgenden „Impression Share“-Metriken von Bing Ads, die mit der neuesten Bing Ads API beendet wurden, werden nach dem 11. Oktober nicht mehr erfasst: Search IS% Lost to Rank, Search IS% Lost to Bid (Bing), Search IS% Lost to Page Relevance (Bing) und Search IS% Lost to Keyword Relevance (Bing). Zuvor erfasste Metriken stehen weiterhin für das Reporting zur Verfügung. |
| Adobe Analytics-Integration | (Nur für Werbetreibende mit Adobe Analytics) In Analysis Workspace ist die Dimension „Gerät (AMO-ID)“, die nie Daten erfasst hat, nicht mehr verfügbar. Verwenden Sie zum Reporting von Online-Analytics-Daten die Dimension „Mobile Device Type“ (Mobilgerätetyp). Verwenden Sie zum Reporting von Suchmaschinen-Traffic-Metriken (z. B. Klicks, Kosten und Impressionen) nach Gerätetyp weiterhin das Reporting in Advertising Cloud Search. |
