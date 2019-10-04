---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: Versionshinweise
last-update: . Oktober 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 59bbe7ddd5cbbcb653d6c44223b644257dd94cb4

---


# Vorzeitiger Zugriff - Experience Cloud-Versionshinweise - Oktober 2019

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

>[!IMPORTANT]
>
>Diese Seite enthält Inhalte einer Vorabversion und kann vor der geplanten Veröffentlichung der Version geändert werden.

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

## Releasedatum: 10. Oktober 2019

<!-- * [Experience Cloud interface](#ecloud) -->
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (Links zur Hilfe zur Lösung)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (Links zur Hilfe zur Lösung)

<!-- ## Experience Cloud interface {#ecloud}

Release notes for Experience Cloud interface and product administration.

* Fixed a security vulnerability to include recommended HTTP headers. (MCUI-9942)
* Fixed an issue in switching between Analytics login companies. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html). -->

## Experience Platform {#platform}

Versionshinweise für Experience Platform, Experience Platform Launch, Identity Service und Sicherheitsbulletins.

* [Experience Platform Launch](#launch)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/security.html) (Alle Adobe-Produkte)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

## [!DNL Analytics] {#analytics}

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics](#aa-features)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [AppMeasurement](#appm)

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics {#aa-features}

| Funktion | Beschreibung |
| -----------| ---------- |  
| Datenschutzdienst-API: CCPA | The California Consumer Privacy Act (CCPA) enhances privacy rights and consumer protection for residents of California, United States. This Act is set to become effective on January 1, 2020.<br><br/>The CCPA provides new data privacy rights to California residents, such as the right to access and delete their personal data, to know whether their personal data is sold or disclosed (and to whom), and to refuse the sale of their personal data.<br><br/>In Erwartung des CCPA wird der Datenschutzdienst Anfragen unterstützen, sich vom Verkauf personenbezogener Daten abzumelden.<br><br/>Der Datenschutzdienst wurde früher als GDPR-Dienst bezeichnet und behält alle vorherigen Funktionen bei, die jetzt zur Unterstützung von CCPA erweitert wurden.<br/>CCPA in Analytics: (Inhalt demnächst) Übersicht über den <br><br/>[Datenschutzdienst](https://www.adobe.io/apis/experiencecloud/gdpr/docs/alldocs.html#!api-specification/markdown/narrative/technical_overview/privacy_service_overview/privacy_service_overview.md) |
| Datenschutzberichte: Analytics Admin Console | Durch Aktivierung der Datenschutzberichterstellung für Analytics wird einer Report Suite ein Satz reservierter Variablen hinzugefügt.  Die Variablen sind so konzipiert, dass sie bei der Erfassung von Daten zur Zustimmung der Verbraucher auf Trefferebene helfen.<br/>Neue Dimensionen:<br/><ul><li>Abmeldeoption für Genehmigungsverwaltung</li><li>Anmelde für die Verwaltung</li><li>Verwaltungsvariablen für Zustimmung: <!-- `[Link to new Consent Variables page in Analytics]()` --></li></ul> |
| Audio and Video Analytics: Privacy Support | Zwei neue Variablen wurden der Media Collection-API hinzugefügt:<br/><ul><li>analytics.optOutServerSideForwarding</li><li>analytics.optOutShare</li></ul>These are optional variables that can be used to capture the status of a consumer’s consent at the time of the hit. [Dokumentation zur Medienerfassungs-API](https://docs.adobe.com/content/help/en/media-analytics/using/media-collection-api/mc-api-overview.html)<br/>Die neuen Kontextdatenvariablen für die Analytics-Verwaltung wurden dem Federated Analytics-Formular hinzugefügt. Diese Variablen stehen jetzt zur Verwendung bei der Kennzeichnung von Treffern für die Freigabe oder den Verkauf für eine Föderation zur Verfügung. [Download Federated Form](https://docs.adobe.com/content/help/en/media-analytics/using/federated-analytics.html#download-the-federated-analytics-form) |
| Analysis Workspace: Auf Freiform-Tabellen aktualisieren | Freeform tables now include two totals, a Table total and a Grand total. ******** Die Zeile "Tabelle insgesamt"berücksichtigt angewendete [Berichtsfilter](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) . Previously, only segmentation impacted totals. [Learn moreIn addition, Show Totals and Show Grand Total options have been added to Column Settings.](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/workspace-totals.html)<br/>************<br/>Mit dieser Änderung an den Freiformsummen werden abhängige Visualisierungen (z. B. Visualisierungen zu verknüpften **[!UICONTROL Zusammenfassungsnummern]** ) sowie exportierte CSV- und PDF-Daten aktualisiert. |
| Analysis Workspace: Option to remove Unspecified/None | The ability to easily remove ‘Unspecified (None)’ has been added as an option to report filters. |
| Analysis Workspace: Abbau der lila Granularitätskomponenten | Purple granularity time components (Minute, Hour, Day, Week, Month, Quarter, Year) have been deprecated. Die lila Zeitkomponenten haben sich immer genau wie ihre orangefarbenen Dimensionskomponenten verhalten, sodass diese Änderung das Erlebnis vereinfachen wird. **Wenn Sie zuvor eine der lila Zeitkomponenten verwendet haben, müssen Sie keine Maßnahmen** ergreifen.<br/>Mit dieser Änderung wurde auch der violette **[!UICONTROL Zeitraum]** in **[!UICONTROL Datumsbereiche]** umbenannt. |

#### Fehlerbehebungen

* Analysis Workspace: Es wurde ein Problem behoben, das bei der Suche nach Dimensionselementen in der linken Leiste zu falschen Suchergebnissen führte. (AN-185065)
* Es wurden Probleme behoben, die dazu führten, dass freigegebene Segmente in Adobe Audience Manager (AAM) nicht gelöscht oder die Veröffentlichung rückgängig gemacht werden konnten. Das Segment kann nicht gelöscht werden, wenn AAM nicht reagiert. (AN-185882, AN-185883, AN-184607)
* Es wurde ein Problem mit der Zeitüberschreitung behoben, durch das Segmente nicht in Ad-hoc-Analysen geladen werden konnten. (AN-184654)
* Es wurde ein Problem behoben, das auftrat, wenn die zuletzt verwendete Report Suite anschließend ausgeblendet wurde oder Sie nicht mehr berechtigt waren, auf diese Report Suite zuzugreifen. In diesem Fall konnten Sie sich nicht mehr über Experience Cloud anmelden. (AN-181777)
* Fixed a timeout issue in segments that made it difficult to create a VRS based on a segment. (AN-179684)

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Ende der Unterstützung für TLS 1.1 | October 3, 2019 | Bis zum 31. März 2020 wird die Unterstützung für TLS 1.1 von Adobe Analytics eingestellt. Diese Änderung ist Teil unserer kontinuierlichen Bemühungen, höchste Sicherheitsstandards zu gewährleisten und die Sicherheit von Kundendaten zu fördern. |
| San Jose FTP Broker Ending für London und Singapur | Juli 2020 | Für Kunden in London und Singapur werden wir das Vermitteln von Daten zwischen London oder Singapur und dem San Jose-Rechenzentrum [ftp.omniture.com](ftp://ftp.omniture.com/)nicht mehr unterstützen.<br/><ul><li>For London use [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Für Singapur verwenden Sie [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li> |
| Aktualisierung der Summen der Freiformtabellen in Analysis Workspace | 12. September 2019 | In October 2019, freeform table total rows will begin accounting for report filters applied. [](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) Bisher wurde bei den Summen nur die Segmentierung berücksichtigt. Mit dieser Änderung werden auch die entsprechenden Visualisierungen aktualisiert (z. B. verknüpfte Darstellungen von [!UICONTROL Zusammenfassungen]) sowie exportierte CSV- und PDF-Daten. |
| Bevorstehende Änderung bezüglich des Felds `createDate` für Analytics-Benutzer | 30. August 2019 | Im Oktober oder November 2019 wird das Feld `createDate` für Analytics-Benutzer von der US Pacific Time auf einen korrekt formatierten Datums-/Uhrzeitwert mit Zeitzoneninformationen aktualisiert. (AN-183468) |
| Unterstützung für frühere Unterschiede bei Zeitzonen | 8. August 2019 | Analytics handhabt jetzt automatisch Unterschiede bei Zeitzonen für Treffer mit Zeitstempel. Nach dieser Änderung am 8. August müssen die unterschiedlichen Zeitzonen von Daten, die nachträglich verarbeitet werden sollen, nicht mehr vor dem Laden angepasst werden. |
| Einschränkungen für Classification Rule Builder | Hinzugefügt am 5. Juni 2019 | Diese Beschränkungen sind nicht neu, sondern wurden der Dokumentation [hier](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html)hinzugefügt. |
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

Siehe Versionshinweise [zu AppMeasurement für JavaScript](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Neue in Audience Manager verfügbare Funktionen, Verbesserungen und Fehlerbehebungen.

**Fehlerbehebungen und Verbesserungen**

* All customer accounts created after July 1st, 2019, will automatically be assigned a  license, providing them access to their reports. [!DNL Tableau] Wenn Ihr Konto vor dem 1. Juli 2019 erstellt wurde und Sie immer noch keinen Zugriff auf Ihre [!DNL Tableau] Berichte haben, wenden Sie sich bitte an die Kundenunterstützung.
* Wir haben fälschlicherweise generierte Aktivitätsmerkmalen-Mitgliedschaften für Besucherprofile entfernt, die keine ID-Synchronisierung mit der Eigenschaftendatenquelle hatten (AAM-45371).
* Wir haben ungültige globale Geräte-IDs aus globalen Datenquellen entfernt. Siehe [Globale Datenquellen](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/data-sources/global-data-sources.html) , um zu erfahren, wie gültige Geräte-IDs aussehen sollten, um von Audience Manager akzeptiert zu werden (AAM-41259).
* Es wurde ein Fehler behoben, der dazu führte, dass die Seite "Segmente"nicht mehr reagierte, wenn Sie versuchten, ein geschütztes Segment zu löschen (AAM-49881).
* Beim Bearbeiten von Zielen für Twitter-Zielgruppen ist die [!UICONTROL Kontoauswahl] jetzt nur aktiv, wenn dem Ziel kein [!DNL Twitter Ads] Konto zugewiesen wurde (AAM-49975).
* Es wurde ein Fehler behoben, der Benutzer daran hinderte, [!UICONTROL Audience Marketplace] -Datenfeeds zu deaktivieren, wenn Abonnements deaktiviert sind (AAM-49640).
* Im Zusammenhang mit der Barrierefreiheit der Audience Manager-Benutzeroberfläche wurden verschiedene Verbesserungen vorgenommen.

## Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktwartung

* **AEM 6.3.3.6**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 6 (6.3.3.6 veröffentlicht am 25. September 2019) ist ein wichtiges Update, das wichtige Fehlerbehebungen von Kunden enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.3 im April 2017 veröffentlicht wurden.
   * [Versionshinweise](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.6.0**

   AEM 6.4, Service Pack 6.0 (6.4.6.0, 19. September 2019) ist ein wichtiges Update, das wichtige Fehlerbehebungen von Kunden enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.4, April 2018 veröffentlicht wurden.
   * [Versionshinweise](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.5.2.0**
AEM 6.5, Service Pack 2.0 (6.5.2.0 released September 19, 2019) is an important update that includes key customer fixes released since the general availability of AEM 6.5, April 2019.
   * [Versionshinweise](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [CFP-Versionen für AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Selbsthilfe

* **Scene7: Reprocess Assets workflow**

   You can now reprocess assets in a folder that already has an existing processing profile that you later changed.
Siehe [Neuverarbeitung von Assets in einem Ordner, nachdem Sie das Verarbeitungsprofil](https://helpx.adobe.com/experience-manager/6-5/assets/using/processing-profiles.html#Reprocessingassetsinafolderafteryouhaveediteditsprocessingprofile)bearbeitet haben.

* **Integration von Viewern für dynamische Medien mit Adobe Analytics und Adobe Launch**

   The Dynamic Media Viewers extension for Adobe Launch, along with the release of Dynamic Media Viewers 5.13, lets customers of Dynamic Media, Adobe Analytics, and Adobe Launch use events and data specific for the Dynamic Media Viewers in their Adobe Launch configuration.
Siehe [Integrieren von Viewern für dynamische Medien in Adobe Analytics und Adobe Launch](https://helpx.adobe.com/experience-manager/6-5/assets/using/launch.html).

* **AEM desktop app**

   AEM desktop app 2.0 is now available for creatives, marketers, and line-of-business users, to work with AEM Assets.
Siehe Versionshinweise zur [AEM-Desktop-App.](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/release-notes.html)

* **Kernkomponenten**
   * Learn about the localization features of Core Components and how they work with AEM templates.
      [Siehe Beispiel](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/get-started/localization.html).
   * Core Components 2.6.0 introduces an Experience Fragment Component. Die Komponente ist jetzt zusammen mit der [Authoring-Dokumentation](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) und den [Entwicklerdetails sowie dem Projektdownload auf GitHub](https://github.com/adobe/aem-core-wcm-components)verfügbar.

* **AEM Assets**
   * New documentation for visual/similarity search capability.
See Find similar images.[](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html#visualsearch)
   * Die Funktion "Connected Assets"verwendet jetzt Dokumente, die in der Remote-DAM-Bereitstellung verfügbar sind, zusätzlich zu den Dateiformaten für Bilder.
See Use Connected Assets to share DAM assets in AEM Sites.[](https://helpx.adobe.com/experience-manager/6-5/assets/using/use-assets-across-connected-assets-instances.html)
   * Fresh content on asset searching and discovery. The Search assets in AEM topic is your one-stop-shop for information on using, configuring, troubleshooting, limitations, and tips.
__
Siehe [Suchen von Assets in AEM](https://helpx.adobe.com/experience-manager/6-5/assets/using/search-assets.html).

### Zusätzliche Ressourcen

* [AEM 6.5 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager-Benutzerhandbuch](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Ältere Versionen der AEM-Dokumentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Startseite der Hilfe zu Dynamischen Medien Classic](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Versionshinweise zu Dynamic Media ](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre-Versionshinweise](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Adobe Campaign Classic

* [Campaign Classic 19.1.4 Update](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) - Build 9032
* [Campaign Classic 19.1.6 Update](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-19-1-6-build-9035) - Build 9035

### Zusätzliche Ressourcen

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
