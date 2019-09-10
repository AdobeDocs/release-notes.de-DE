---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: Versionshinweise
last-update: September 2019
author: mfrei
translation-type: tm+mt
source-git-commit: b680e3b7c761ca2b6ba28150fb3102d0778d0d3a

---


# Frühzeitiger Zugriff – September 2019 – Versionshinweise zur Adobe Experience Cloud

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

>[!IMPORTANT]
>
>Diese Seite enthält Inhalte einer Vorabversion und kann vor der Veröffentlichung am 12. September 2019 geändert werden.

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. Sie erhalten drei bis fünf Werktage vor der Veröffentlichung der Version eine Benachrichtigung. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

## Releasedatum: 12. September 2019

* [Experience Cloud-Benutzeroberfläche](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (Links zur Lösungshilfe)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (Links zur Lösungshilfe)

## Experience Cloud-Benutzeroberfläche {#ecloud}

Versionshinweise für die Experience Cloud-Benutzeroberfläche und die Produktverwaltung.

* Eine Sicherheitslücke wurde behoben, sodass empfohlene HTTP-Header jetzt eingeschlossen werden. (MCUI-9942)
* Ein Problem beim Wechseln zwischen bei Analytics angemeldeten Unternehmen wurde behoben. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience Platform {#platform}

Versionshinweise für Experience Platform, Experience Platform Launch, Identity Service und Sicherheitsbulletins.

* [Experience Platform Launch](#launch)
* [Mobile Services und Mobile SDK](#mobile)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/security.html) (alle Adobe-Produkte)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

### Mobile Services und Mobile SDK {#mobile}

Releasedatum: **26. September**

**iOS (4.18.8)**

* Ein Fehler wurde behoben, bei dem SDK-Daten bei jedem Analytics-Aufruf mit der gekoppelten watchOS-App synchronisiert wurden.
* Ein Fehler wurde behoben, durch den die Push-Clickthrough-Payload nicht als Eigenschaft für In-App-Nachrichten verwendet werden konnte.
* Aktualisierung auf Benutzerbenachrichtigungs-Framework-APIs anstelle der UILocalNotification API, die seit iOS 10 nicht mehr unterstützt wird.
* Aktualisierung auf WKWebView anstelle von UIWebView, das ab iOS 12 nicht mehr unterstützt wird.

**Android 4.17.10**

* Unterstützung für BCP-47-Sprachtags hinzugefügt.

**Unity**

* Plug-in wurde auf 4.18.7 für iOS und auf 4.17.9 für Android aktualisiert.

## [!DNL Analytics] {#analytics}

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics](#aa-features)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [AppMeasurement](#appm) 

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics {#aa-features}

| Funktion | Beschreibung |
| -----------| ---------- |  
| **Journey IQ: Cross-Device Analytics** | Im September 2019 stellt Adobe Analytics eine leistungsstarke neue Funktion namens "Journey IQ" ein: Geräteübergreifende Analyse. (Bitte beachten Sie, dass diese Funktion nur für Analytics-Bestandskunden verfügbar ist.) Cross-Device Analytics (CDA) verwandelt Adobe Analytics von einem gerätespezifischen in ein personenspezifisches Analysetool. Mithilfe von CDA können Sie Fragen beantworten wie z. B.: <ul><li>Wie viele Menschen interagieren mit meinem Unternehmen? Wie viele und welche Gerätetypen verwenden sie? Wie überschneiden sich diese?</li><li>Wie oft beginnen Personen mit einer Aufgabe auf einem Mobilgerät und wechseln dann zu einem Desktop-PC, um die Aufgabe abzuschließen? Führen Kampagnen-Clickthroughs auf einem Gerät zur Konversion auf einem anderen Gerät?</li><li>Wie ändern sich meine Daten zur Wirksamkeit einer Kampagne, wenn ich geräteübergreifende Journeys berücksichtige? Wie ändert sich meine Trichteranalyse?</li><li>Welche sind die häufigsten Pfade, die Benutzer beim Wechsel von einem Gerät zum anderen verwenden? Wo steigen sie aus? Wo schließen sie ihre Aktion erfolgreich ab?</li><li>Wie unterscheidet sich das Verhalten von Benutzern mit mehreren Geräten von Benutzern mit nur einem Gerät?</li></ul><br/>Weitere Informationen finden Sie unter [adobe.ly/aacda](https://spark.adobe.com/page/8ZpjsX6Lp5XTM/). |
| **Aktualisierte Klassifizierungsarchitektur** | Ab September wird ein Update der Klassifizierungsarchitektur über einen Zeitraum von mehreren Monaten an Kunden übermittelt. Die September-Version beinhaltet die Migration für eine geringe Anzahl frühzeitiger Anwender.<br/>Die Aktualisierung verringert die Zeit für Uploads erheblich (einschließlich der Regellogik), die importiert/aufgenommen und zur Berichterstellung verwendet werden. |

#### Fehlerbehebungen

* Ein Problem mit den Core Services [!UICONTROL People] und [!UICONTROL Offers] wurde behoben, auf die im Experience Cloud-Hauptmenü kein Zugriff bestand. (AN-184294)
* Ein Problem mit der linken Leiste in [!UICONTROL Analysis Workspace] wurde behoben, bei der die Bildlaufleiste ständig zwischen sichtbar und nicht sichtbar wechselte, sodass ein Flimmern vorhanden war. (AN-183904)
* Ein Problem mit Fehlerberichten wurde behoben. In Zukunft werden mehr spezifische Fehlermeldungen anstelle der roten Fehleranzeige zu sehen sein. Genauer gesagt, wird jetzt angezeigt, ob das Problem durch zu hohe Auslastung, einen Fehler oder eine zu komplexe Berichtsanfrage verursacht wird. (AN -184135) [Mehr…](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/optimizing-performance.html)
* Ein Problem wurde behoben, das den erfolgreichen Download von Fallout-Berichten in `.pdf/.xls/.rtf`-Formaten verhinderte. (AN-183165)
* Ein Probleme wurde behoben, das auftrat, wenn die Anmeldung über Experience Cloud erfolgte und zu verschiedenen Experience Cloud-Lösungen oder zu einem anderen angemeldeten Unternehmen gewechselt wurde. (AN-183376)
* Ein Problem wurde behoben, durch das Assets bei terminierten Projekten nicht ordnungsgemäß übermittelt wurden. Gruppen werden jetzt in der [!UICONTROL Admin Console] verwaltet, sodass Assets beim Transfer nicht mehr zwischen den Benutzern kopiert werden. (AN-183751)
* Ein Problem wurde beim Löschen terminierter Berichte behoben, deren Inhaber bereits gelöscht worden waren. Ab sofort wird eine Benachrichtigung an den Administrator gesendet (der den Löschvorgang durchgeführt hat), wenn der Inhaber eines geplanten Berichts nicht mehr vorhanden ist. (AN-181000)

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Aktualisierung der Summen der Freiformtabellen in Analysis Workspace | 12. September 2019 | Im Oktober 2019 beginnen die Freiform-Tabellenzeilen mit der Berechnung der [angewendeten Berichtsfilter](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) . Bisher wurde bei den Summen nur die Segmentierung berücksichtigt. Mit dieser Änderung werden auch die entsprechenden Visualisierungen aktualisiert (z. B. verknüpfte Darstellungen von [!UICONTROL Zusammenfassungen]) sowie exportierte CSV- und PDF-Daten. |
| Bevorstehende Änderung bezüglich des Felds `createDate` für Analytics-Benutzer | 30. August 2019 | Im Oktober oder November 2019 wird das Feld `createDate` für Analytics-Benutzer von der US Pacific Time auf einen korrekt formatierten Datums-/Uhrzeitwert mit Zeitzoneninformationen aktualisiert. (AN-183468) |
| Unterstützung für frühere Unterschiede bei Zeitzonen | 8. August 2019 | Analytics handhabt jetzt automatisch Unterschiede bei Zeitzonen für Treffer mit Zeitstempel. Nach dieser Änderung am 8. August müssen die unterschiedlichen Zeitzonen von Daten, die nachträglich verarbeitet werden sollen, nicht mehr vor dem Laden angepasst werden. |
| Einschränkungen für Classification Rule Builder | Hinzugefügt am 5. Juni 2019 | Diese Beschränkungen sind nicht neu, wurden aber zur Dokumentation [hier hinzugefügt](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Einschränkungen des neuen Segmentoperators | Hinzugefügt am 31. Mai 2019 | Ab dem 18. Juli 2019 sind die Segmentoperatoren _enthält beliebig viele_, _enthält keinerlei_, _enthält alle von_ und _enthält nicht alle_ auf 100 Wörter pro Eingabefeld beschränkt. Die Beschränkung wird nach diesem Datum auf alle neuen und geänderten Segmente angewendet. Vorhandene Segmente, die die Beschränkung überschreiten, werden weiterhin unterstützt, können jedoch erst geändert oder gespeichert werden, wenn das Eingabefeld reduziert wurde. Diese Grenzwerte werden im Rahmen kontinuierlicher Bemühungen zur Verbesserung der Abfrageleistung angewendet. |
| Änderungen der Unterstützung für die Classifications **[!UICONTROL Datumsaktiviert]** und **[!UICONTROL Numerisch 2]** | Aktualisiert am 28. Mai 2019 | Die Möglichkeit, die Klassifizierungen „Numerisch 2“ und „Datumsaktiviert“ zu importieren, wurde aus der Codebasis entfernt. Diese Änderung wurde mit der Wartungsversion vom Juli 2019 wirksam. Wenn die Importdatei die Spalte „Numerisch“ oder „Datumsaktiviert“ enthält, werden diese Zellen still ignoriert und alle anderen Daten in dieser Datei werden normal importiert. <br/>Vorhandene Classifications können weiterhin über den Standard-Classification-Arbeitsablauf exportiert werden und sind weiterhin in Berichten verfügbar. |
| Änderung bei Berechnungen der _Berichtssumme_ | Aktualisiert am 9. Juli 2019 | Am **18. Juni 2019** wurden in Adobe Analytics die Berechnungen von _Berichtssummen_ für alle Dimensionen und Metriken vereinheitlicht. Dadurch änderten sich die Gesamtsummen bei manchen Berichten (vor allem bei Berichten zu Eigenschaften oder Kundenattributen). Vor dieser Änderung kam es vor, dass in manchen Berichtssummen der Zeileneintrag _Unspecified_ uneinheitlich ein- oder ausgeschlossen wurde, und zwar unabhängig davon, ob _Unspecified_ im Bericht vorkam oder nicht. <br/>Ab 18. Juni 2019 wird _Nicht angegeben_ immer in Berichtssummen angezeigt, auch wenn dieser Wert nicht als Zeileneintrag im Bericht zu sehen ist. Darüber hinaus können Segmente, die die Logik _existiert_ oder _existiert nicht_ verwenden, für einige Dimensionen nach dieser Änderung andere Ergebnisse anzeigen, insbesondere Dimensionen, bei denen _Nicht angegeben_ einen speziellen Namen wie den Zeileneintrag „Eingegeben/Mit Lesezeichen versehen“ für die Dimension „Typ der verweisenden Stelle“ oder den Zeileneintrag „Sonstige“ für die Dimension „Gerätetyp“ verwendet werden. Diese Änderung betrifft Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder und die Reporting-API. |
| Aktualisierung von CSV-Downloads aus Analysis Workspace | 10. April 2019 | Ab dem 11. April 2019 wurden mehrere Änderungen an **[!UICONTROL CSV-Downloads]** (und **[!UICONTORL In Zwischenablage kopieren]**) in Analysis Workspace vorgenommen, um die Formatierung aus den exportierten Daten zu entfernen.  <ul><li>Das Tausendertrennzeichen ist nicht mehr enthalten. Das Dezimaltrennzeichen wird weiterhin enthalten sein und dem unter **[!UICONTROL Komponenten &gt; Berichtseinstellungen &gt; Tausendertrennzeichen]** definierten Format entsprechen. Hinweis: Numerische Werte, die ein Komma als Dezimaltrennzeichen verwenden, werden weiterhin in der exportierten CSV angegeben.</li><li>Es werden keine Währungssymbole angezeigt.</li><li>Es werden keine Prozentsymbole angezeigt. Prozentangaben werden in Dezimalform angezeigt. Zum Beispiel werden 75 % als 0,75 dargestellt.</li><li>Die Zeit wird in Sekunden angezeigt.</li><li>Kohortentabellen zeigen nur Rohwerte an. Prozentsätze werden entfernt.</li><li>Wenn eine Nummer ungültig ist, wird eine leere Zelle angezeigt.</li></ul> |
| Anstehende Änderung am Befehl „Analysis Workspace Debugger“ | 4. April 2019 | Der Befehl „Console“ zum Aktivieren des Analysis Workspace-Debuggers ändert sich am **13. Juni 2019** in adobeTools.debug.includeOberonXml. adobe.tools.debug.includeOberonXml wird nach diesem Datum nicht mehr funktionieren. |
| Mobile Browser – Versionsnummern | 7. Februar 2019 | Am 8. Januar 2019 haben wir die Abschnittsebene bei den Versionsnummern mobiler Browser von 2 zu 1 geändert. Seit diesem Datum zeigen die Versionen nur die ersten beiden Ebenen an (Beispiel: _Firefox 64.0.2_ wird jetzt als _Firefox 64.0_ angegeben). |
| Wird eingestellt [!DNL Ad Hoc Analysis] | 29. Januar 2019 | Am 6. August 2018 kündigte Adobe die Absicht an, [!DNL Ad Hoc Analysis] einzustellen. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist.<br/>Weitere Informationen dazu, welche Versionen von Java während dieses Zeitraums kompatibel sind, finden Sie unter [[!DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Kurz-Links [!DNL Analytics] für Berichte | 14. Januar 2019 | Kurz-Links [!DNL Analytics] für Berichte, die innerhalb eines Jahres nicht aufgerufen wurden, werden entfernt und ab Donnerstag, den 17. Januar 2019 fortlaufend gelöscht. |
| Ende der Unterstützung für TLS 1.0 | Aktualisiert am 10. Januar 2019 | Ab dem 11. Februar 2019 unterstützt die Adobe Analytics-Berichterstellung die Verschlüsselung mit TLS (Transport Layer Security) 1.0 nicht mehr. Diese Änderung ist Teil unserer ständigen Bemühungen, die höchsten Sicherheitsstandards einzuhalten und die Daten unserer Kunden zu schützen. If you are unable to connect to Adobe Analytics reporting after February 11, 2019, you should upgrade your browser to the [latest version](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html).<br/> Ab dem 20. Februar 2019 bietet die Adobe Analytics-Datenerfassung keine Unterstützung für TLS 1.0 mehr. Aufgrund dieser Änderung werden von Adobe keine [!DNL Analytics]-Daten von Endbenutzern mit älteren Geräten oder Webbrowsern ohne Unterstützung für TLS 1.1 oder höher erfasst. Wir gehen davon aus, dass dies keine wesentlichen Auswirkungen auf Kundendaten oder die Berichterstattung haben wird. (Wenn Ihre Website TLS 1.0 bereits nicht mehr unterstützt, sind Sie nicht betroffen.) <br/>Ab dem 11. April 2019 bietet die Reporting-API von Adobe Analytics keine Unterstützung mehr für die TLS 1.0-Verschlüsselung. Kunden, die auf die API zugreifen, sollten sicherstellen, dass sie nicht von den Auswirkungen betroffen sind. <ul><li>Für API-Clients, die Java 7 mit den Standardeinstellungen verwenden, müssen einige [Änderungen zur Unterstützung von TLS 1.2](https://www.java.com/en/configure_crypto.html) vorgenommen werden (siehe _„Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2“_.) </li><li>API-Clients, die Java 8 verwenden, sollten nicht beeinträchtigt sein, da die Standardeinstellung TLS 1.2 ist.</li><li> Bei API-Clients, die andere Frameworks verwenden, müssen Sie die Details zur Unterstützung von TLS 1.2 beim jeweiligen Anbieter erfragen.</li></ul> |
| Daten-Feed: Spalte „post_product_list“ – Änderung der Größe | 9. Januar 2019 | Adobe hat die Größe der Spalte „post_product_list“ am dem 7. Februar 2019 von 64 KB auf 16 MB erweitert. Diese Änderung stellt sicher, dass bei der Verarbeitung zu „post_product_list“ hinzugefügte Merchandising-eVar-Werte nicht zu abgeschnittenen Produkt- und Umsatzwerten führen. Wenn Sie über Prozesse verfügen, bei denen post_product_list-Werte erfasst werden, stellen Sie sicher, dass diese Prozesse Werte mit einer Länge von bis zu 16 MB verarbeiten können (ansonsten werden Werte bei 16 KB abgeschnitten), um Datenerfassungsfehler zu vermeiden. |
| Verwaltungsänderungen mit Auswirkung auf inaktive [!DNL Analytics Live Stream]-Endpunkte | 20. Dezember 2018 | Ab dem 1. Februar 2019 können [!DNL Live Stream]-Endpunkte, die 90 Tage lang keine aktive Verbraucherverbindung aufweisen, deaktiviert werden. Sie können sich an die Kundenunterstützung wenden, um sich über Ihre [!DNL Live Stream]-Endpunkte zu informieren und diese bei Bedarf wieder zu aktivieren. Stellen Sie außerdem sicher, dass für Ihre Verbraucherprozesse eine dauerhafte Verbindung besteht, wie es das Konzept des Dienstes vorsieht, und dass sie so implementiert sind, dass sie sich wieder verbinden, wenn die Verbindung getrennt oder unterbrochen wird. |
| Aktualisieren von Adobe [!DNL Report Builder] aufgrund der Einstellung des Supports für TLS 1.0 | 7. Sept. 2018 | Aufgrund der Unterstützung für TLS 1.0 sollten Benutzer von [!DNL Report Builder] die Version 5.6.21 vor Februar 2019 herunterladen. Nach diesem Datum sind frühere Versionen von [!DNL Report Builder] nicht mehr funktionstüchtig. |

### [!DNL AppMeasurement] {#appm}

Siehe [appmeasurement for Javascript-Versionshinweise](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Neue in Audience Manager verfügbare Funktionen, Verbesserungen und Fehlerbehebungen.

### Neue Funktionen und Verbesserungen {#aam-features}

| Funktion | Beschreibung |
| -----------| ---------- |  
| **[[! DNL benutzerbasierte Ziele]](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)** | [!DNL People-Based Destinations] ist ein kostenpflichtiges Audience Manager-Add-on, mit dem Sie Erstanbieter-Zielgruppensegmente in verschiedenen personenbasierten Umgebungen, wie Facebook, mithilfe von Hash-Kennungen aktivieren können, etwa anhand von E-Mail-Adressen. |
| **[Konfigurieren von Twitter-angepassten Zielgruppen als selbstbedienungsbasiertes Ziel](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/device-based/twitter-tailored-audiences.html)** | Wir migrieren Twitter-Ziele in ein Modell, dessen Konfiguration Sie selbst durchführen können. In diesem Artikel wird beschrieben, welche Änderungen Sie bei vorhandenen Twitter-Integrationen vornehmen müssen, damit sie nach der Migration weiterhin funktionieren. |
| **[Audience Marketplace Rechnungsling](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/audience-marketplace/audience-marketplace-for-data-buyers/marketplace-buyer-billing.html#billing-examples)** | Wir haben ein neues Beispiel (Fall 3) hinzugefügt, in dem wir detailliert beschreiben, wie die Abrechnung für Segmente mit Aktivierungs- und Modellierungsanwendungsfällen funktioniert. |

**Fehlerbehebungen und Verbesserungen**

* Ein Fehler wurde behoben, bei dem Benutzer Adobe Analytics-Ziele nicht bearbeiten konnten, um Segmente manuell zuzuordnen. (AAM-49323)
* Ein Fehler wurde behoben, bei dem doppelte Audience Marketplace-Feeds aus einer einzigen Datenquellen-ID stammten. Zwischen Datenquellen und [!DNL Marketplace]-Feeds muss eine 1:1-Zuordnung bestehen. (AAM-48504)
* Die Workflows für die Eigenschaften- und Segmenterstellung wurden verbessert. Jetzt können Sie die Datenquelle filtern, um Eigenschaften oder Segmente zu speichern und andere Datenquellen als Audience Manager auszuschließen (z. B. Report Suite-Datenquellen aus Adobe Analytics). (AAM-35899)
* Ein Problem in der Data Sources-API wurde behoben, bei dem bei der Definition des Abfrageparameters `ExcludeReportSuites=true` keine Report Suite-Datenquellen aus Adobe Analytics ausgeschlossen wurden. (AAM-48545)
* Im Zusammenhang mit der Barrierefreiheit der Audience Manager-Benutzeroberfläche wurden verschiedene Verbesserungen vorgenommen. (AAM-49024) und (AAM-49031)

## Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktversion

**Cloud Manager 2019.8.0**

Die Cloud Manager-Version 2019.8.0 enthält kleinere Fehlerkorrekturen, eine Leistungsverbesserung und Unterstützung für bestimmte Content-Packages.

* [Versionshinweise für Cloud Manager 2019.8.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Produktwartung

**Roadmap für AEM-Wartungsversion**

Weitere Informationen finden Sie im AEM Maintenance Release Plan, wie er hier veröffentlicht [](https://helpx.adobe.com/experience-manager/maintenance-releases-roadmap.html)wird.

### Selbsthilfe

**Vorabversion von Asset Link 1.1**

* [Informationen zur Vorabversion von Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link-prerelease.html)
* [Konfigurieren von AEM für den Adobe Asset Link für Vorabversion](https://helpx.adobe.com/enterprise/using/configure-aem-for-aal-prerelease.html)

**AEM Desktop App 2.0**

AEM Desktop App 2.0 für MAC wurde am 30. August 2019 veröffentlicht. AEM Desktop App 2.0 für Windows wird Anfang September veröffentlicht.

Hier finden Sie Dokumentation und Downloads [](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/introduction.html).

**Intelligente Tags für Assets**

Hier erfahren Sie, wie Sie ein Zertifikat aktualisieren, nachdem es abgelaufen [](https://helpx.adobe.com/experience-manager/6-5/assets/using/config-smart-tagging.html#Obtainpubliccertificate)ist.

**Benutzerhandbuch für die Fenster von AEM 6.5**

Die neue Dokumentation zu _Richtlinien zur Netzwerkimplementierung_ ist jetzt verfügbar. See the [User Guide](https://helpx.adobe.com/experience-manager/6-5/screens/user-guide.html).

**Dienst zur automatisierten Formularumwandlung**

Die Dokumentation für den Dienst zur automatisierten Formularumwandlung für AEM Forms ist jetzt verfügbar. Siehe [Einführung in den Konversionsdienst für automatisierte Formulare](https://helpx.adobe.com/experience-manager/Automated-Forms-Conversion-Service/introduction-to-automated-form-conversion-service.html).

### Community

**AEM Skill Builder-Webinare**

* [Adobe Experience Manager-Sites](https://forums.adobe.com/thread/2647742)

   | Webinar | Datum |
   | -----------| ---------- |  
   | _Authoring Web Experiences (Erstellen von Web-Erlebnissen)_ | 27. August 2019 |
   | _Search and Navigate Content (Suchen und Navigieren in Inhalten)_ | 03. September 2019 |
   | _Manage Every-Evolving Content Easily (Verwalten von sich laufend verändernden Inhalten)_ | 10. September 2019 |
   | _Fluid Experiences (Reibungslose Erlebnisse)_ | 17. September 2019 |
   | _Create and Manage Multi-Lingual, Multi-National to Design a Global Website Structure (Erstellen und Verwalten mehrsprachiger, länderübergreifender Inhalte zur Gestaltung einer globalen Website-Struktur)_ | 24. September 2019 |

* [Adobe Experience Manager Assets](https://forums.adobe.com/thread/2647743)

   | Webinar | Datum |
   | -----------| ---------- |  
   | _Folder Structure and Search (Ordnerstruktur und Suche)_ | 29. August 2019 |
   | _Metadaten_ | 05. September 2019 |
   | _Brand Portal_ | 12. September 2019 |
   | _Dynamische Medien_ | 19. September 2019 |
   | _Asset-Link_ | 26. September 2019 |

* [Adobe Experience Manager Forms](https://forums.adobe.com/thread/2647744)

   | Webinar | Datum |
   | -----------| ---------- |  
   | _Forms 101_ | 04. September 2019 |
   | _Connect Forms to Databases, Build Workflows, and Integrate Forms with E-Signatures (Verbinden von Formularen mit Datenbanken, Erstellen von Workflows und Integrieren von Formularen mit E-Signaturen)_ | 11. September 2019 |
   | _Create Mobile-Responsive Web and Print-Ready Interactive Communications (Erstellen von Mobile-responsiven Websites und druckfertigen interaktiven Mitteilungen)_ | 25. September 2019 |

* [Adobe Experience Manager Cloud Manager](https://forums.adobe.com/thread/2647745)

   | Webinar | Datum |
   | -----------| ---------- |  
   | _Testing Best Practices – Build execution, monitoring, audit, and insights with Cloud Manager (Testen von Best Practices – Ausführen, Überwachen, Prüfen und Einblicke mit Cloud Manager)_ | 18. September 2019 |
   | _Dispatcher Configurations with Cloud Manager (Dispatcher-Konfigurationen mit Cloud Manager)_ | 16. Oktober 2019 |
   | _Creating Workflows with Cloud Manager and Third-Party Tools (Erstellen von Workflows mit Cloud Manager und Drittanbieter-Tools)_ | 13. November 2019 |

### Zusätzliche Ressourcen

* [AEM 6.5 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager-Benutzerhandbuch](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Ältere Versionen der AEM-Dokumentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Hilfe zu Dynamic Media Classic - Startseite](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Versionshinweise zu Dynamic Media ](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre-Versionshinweise](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

### Ende der Produktlebensdauer

[!DNL Digital Publishing Suite Classic] (DPSC) wird am 31. August 2019 eingestellt. Weitere Informationen finden Sie unter [[! DNL Digital Publishing Suite Classic] FAQ](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html)zum Lebenszyklusende.

### Zusätzliche Ressourcen

* [AEM 6.5 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager-Benutzerhandbuch](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Ältere Versionen der AEM-Dokumentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System – Versionshinweise](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre-Versionshinweise](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

### Adobe Campaign Classic

* [Kampagne Classic 19.1.4 -](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9032) Build 9032
* [Kampagne Classic 19.1.5 -](https://docs.campaign.adobe.com/doc/AC/en/RN.html#9033) Build 9033

### [!UICONTROL Control Panel] von Adobe Campaign

Wir haben neue Funktionen für Administratoren hinzugefügt, sodass sie Benachrichtigungen erhalten, bevor SSL-Zertifikate für ihre Domänen ablaufen. Weitere Informationen finden Sie in der [ausführlichen Dokumentation](https://helpx.adobe.com/campaign/kb/control-panel-subdomains-certificates.html).

Außerdem können Administratoren nun SSH-Schlüssel löschen, die zum Zugriff auf SFTP-Server hinzugefügt wurden.

Beachten Sie, dass das [!UICONTROL Control Panel] sowohl für auf AWS gehostete Kunden von Adobe Campaign Classic als auch von Adobe Campaign Standard verfügbar ist. Für den Zugriff auf das [!UICONTROL Control Panel] sind keine Upgrades erforderlich.

### Zusätzliche Ressourcen

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
