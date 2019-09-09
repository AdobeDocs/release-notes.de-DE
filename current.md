---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: Versionshinweise
last-update: September 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 3b26af48364509946706cd183c1261ea8c15eab2

---


# Frühzeitiger Zugriff - September 2019 - Experience Cloud - Versionshinweise

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

>[!IMPORTANT]
>
>Diese Seite enthält Inhalte vor der Veröffentlichung und kann vor der Version vom 12. September 2019 geändert werden.

>[!NOTE]
>
>Subscribe to the [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases. Sie erhalten drei bis fünf Werktage vor der Veröffentlichung der Version eine Benachrichtigung. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

## Releasedatum: 12. September 2019

* [Experience Cloud-Benutzeroberfläche](#ecloud)
* [Experience-Plattform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (Links zur Lösungshilfe)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (Links zur Lösungshilfe)

## Experience Cloud-Benutzeroberfläche {#ecloud}

Versionshinweise für die Experience Cloud-Schnittstelle und die Produktverwaltung.

* Es wurde eine Sicherheitslücke behoben, die empfohlen wurde, empfohlene HTTP-Header einzuschließen. (MCUI-9942)
* Es wurde ein Problem beim Umschalten zwischen Analytics-Anmeldeunternehmen behoben. (MCUI-10049)

For product documentation, see [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html).

## Experience-Plattform {#platform}

Versionshinweise für die Experience Platform, Experience Platform Launch, Identitätsdienst und Sicherheitsbulletins.

* [Experience Platform Launch](#launch)
* [Mobile Services und Mobile SDK](#mobile)
* [Sicherheitsbulletins und -hinweise](https://helpx.adobe.com/security.html) (alle Adobe-Produkte)

### Experience Platform Launch {#launch}

See [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) for release notes and product documentation.

### Mobile Services und Mobile SDK {#mobile}

Release Date: **September 26th**

**Ios (4.18.8)**

* Es wurde ein Fehler behoben, durch den SDK-Daten mit der paketbezogenen watchos-App bei jedem Analytics-Aufruf synchronisiert werden.
* Es wurde ein Fehler behoben, durch den Push-Clickthrough-Nutzlast nicht als Eigenschaften für In-App-Nachrichten verwendet werden konnte.
* Aktualisierung auf Benutzerbenachrichtigungs-apis anstelle der uilocalnotification-API, die ab ios 10 nicht mehr unterstützt wurde.
* Aktualisierung auf wkwebview anstelle von uiwebview, die ab ios 12 nicht mehr unterstützt wurde.

**Android 4.17.10**

* Unterstützung für BCP 47-Sprachtags hinzugefügt.

**Unity**

* Zusatzmodul wurde auf 4.18.7 für ios und 4.17.9 für Android aktualisiert

## [!DNL Analytics] {#analytics}

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics](#aa-features)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)
* [AppMeasurement](#appm) 

For product documentation, see [Adobe Analytics Help Home](https://docs.adobe.com/content/help/en/analytics/landing/home.html).

### Neue Funktionen, Verbesserungen und Fehlerbehebungen in Adobe Analytics {#aa-features}

| Funktion | Beschreibung |
| -----------| ---------- |  
| **Journey IQ: Geräteübergreifende Analyse** | Im September 2019 stellt Adobe Analytics frühzeitigen Zugriff für Analytics Ultimate-Kunden zu einer leistungsstarken neuen Funktion namens "Journey IQ" ein: Geräteübergreifende Analyse. Geräteübergreifende Analytics (CDA) wandelt Adobe Analytics von einem Gerät in ein persönliches Analysetool um. Mithilfe von CDA können Sie Fragen wie z. B. folgende beantworten: <ul><li>Wie viele Menschen interagieren mit meiner Marke? Wie viele und welche Gerätetypen verwenden sie? Wie überschneiden sich diese?</li><li>Wie oft beginnen Personen mit einer Aufgabe auf einem Mobilgerät und wechseln dann zu einem Desktop-PC, um die Aufgabe abzuschließen? Führen Kampagnen-Clickthroughs, die auf einem Gerät landen, zur Umrechnung anderswo?</li><li>Wie ändert sich mein Verständnis der Kampagneneffektivität, wenn ich geräteübergreifende Routen berücksichtige? Wie ändert sich meine Trichteranalyse?</li><li>Welches sind die häufigsten Pfade, die Benutzer von einem Gerät zum nächsten verwenden? Wo steigen sie aus? Wo sind sie erfolgreich?</li><li>Wie unterscheidet sich das Verhalten von Benutzern mit mehreren Geräten von den Benutzern mit einem einzelnen Gerät?</li></ul><br/>Weitere Informationen finden Sie unter [adobe.ly/aacda](https://spark.adobe.com/page/8ZpjsX6Lp5XTM/). |
| **Aktualisierte Klassifizierungsarchitektur** | Ab September wird ein Update der Klassifizierungsarchitektur über einen Zeitraum von mehreren Monaten an Kunden migriert. Die September-Version beinhaltet die Migration für eine kleine Anzahl frühzeitiger Adopter.<br/>Die Aktualisierung verringert die Zeit für Uploads (einschließlich der Regellogik) erheblich, die importiert/abgerufen und zur Berichterstellung bereitgestellt werden kann. |

#### Fehlerbehebungen

* Es wurde ein Problem mit den Hauptdiensten [!UICONTROL "Personen] «und [!UICONTROL " Angebote"] behoben, auf die im Haupt-Experience Cloud-Menü nicht zugegriffen werden kann. (AN-184294)
* Es wurde ein Problem mit der linken Leiste im [!UICONTROL Arbeitsbereich für Analysen] behoben, durch das eine Bildlaufleiste zwischen über eine Bildlaufleiste und keine Bildlaufleiste erstellt wurde. Dies führte zu einem Flackerungseffekt. (AN-183904)
* Es wurden Probleme mit Fehlerberichten behoben. Sie beginnen mit der Anzeige spezifischer Fehlermeldungen anstelle des roten Fehlerindikators. Genauer gesagt sollten Sie erkennen, wann das Problem durch hohe Auslastung, einen Fehler oder eine zu komplexe Berichtanforderung verursacht wird. (AN -184135) [Mehr…](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/optimizing-performance.html)
* Ein Problem wurde behoben, das den erfolgreichen Download von Fallout-Berichten in `.pdf/.xls/.rtf` Formaten verhinderte. (AN-183165)
* Es wurden Probleme behoben, die beim Anmelden über die Experience Cloud und beim Wechseln zu verschiedenen Experience Cloud-Lösungen oder Wechsel zu einem anderen angemeldeten Unternehmen auftraten. (AN-183376)
* Es wurde ein Problem behoben, durch das Assets mit geplanten Projekten nicht ordnungsgemäß übertragen wurden. Gruppen werden jetzt in der [!UICONTROL Admin-Konsole] verwaltet, sodass sie nicht mehr zwischen den Benutzern kopiert werden, wenn Sie Assets weiterleiten. (AN-183751)
* Es wurde ein Problem beim Löschen terminierter Berichte behoben, deren Inhaber gelöscht wurden. Ab sofort wird eine Benachrichtigung an den Administrator gesendet (der den Löschvorgang durchgeführt hat), wenn der Zeitplan-Eigentümer nicht mehr vorhanden ist. (AN-181000)

### Wichtige Hinweise für [!DNL Analytics]-Administratoren {#aa-notices}

| Hinweis | Hinzugefügt  oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Aktualisierung der Freiform-Tabellensummen in Analysis Workspace | 12. September 2019 | Im Oktober 2019 beginnen die Freiform-Tabellenzeilen mit der Berechnung der [angewendeten Berichtsfilter](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/pagination-filtering-sorting.html) . Bisher wurden die Summen nur für die Segmentierung berücksichtigt. Mit dieser Änderung werden abhängige Visualisierungen aktualisiert (z. B. verknüpfte [!UICONTROL Zusammenfassungsvisualisierungen] ) sowie exportierte CSV- und PDF-Daten. |
| Bevorstehende Änderung bezüglich `createDate` des Feldes für Analytics-Benutzer | 30. August 2019 | Im Oktober oder November 2019 wird das `createDate` Feld für Analytics-Benutzer in der US Pacific Time auf einen korrekt formatierten Datums-/Uhrzeitwert mit Zeitzoneninformationen aktualisiert. (AN-183468) |
| Unterstützung für frühere Unterschiede bei Zeitzonen | 8. August 2019 | Analytics handhabt jetzt automatisch Unterschiede bei Zeitzonen für Treffer mit Zeitstempel. Nach dieser Änderung am 8. August müssen die unterschiedlichen Zeitzonen von Daten, die nachträglich verarbeitet werden sollen, nicht mehr vor dem Laden angepasst werden. |
| Einschränkungen für Classification Rule Builder | Hinzugefügt am 5. Juni 2019 | Diese Beschränkungen sind nicht neu, wurden aber zur Dokumentation [hier hinzugefügt](https://docs.adobe.com/content/help/en/analytics/components/classifications/classifications-rulebuilder/classification-rule-builder.html). |
| Einschränkungen des neuen Segmentoperators | Hinzugefügt am 31. Mai 2019 | Ab dem 18. Juli 2019 sind die Segmentoperatoren _enthält beliebig viele_, _enthält keinerlei_, _enthält alle von_ und _enthält nicht alle_ auf 100 Wörter pro Eingabefeld beschränkt. Die Beschränkung wird nach diesem Datum auf alle neuen und geänderten Segmente angewendet. Vorhandene Segmente, die die Beschränkung überschreiten, werden weiterhin unterstützt, können jedoch erst geändert oder gespeichert werden, wenn das Eingabefeld reduziert wurde. Diese Grenzwerte werden im Rahmen kontinuierlicher Bemühungen zur Verbesserung der Abfrageleistung angewendet. |
| Support changes for **[!UICONTROL Date-Enabled]** and **[!UICONTROL Numeric 2 Classifications]** | Aktualisiert am 28. Mai 2019 | Die Möglichkeit, die Klassifizierungen „Numerisch 2“ und „Datumsaktiviert“ zu importieren, wurde aus der Codebasis entfernt. Diese Änderung trat in der Maintenance-Version vom Juli 2019 auf. Wenn die Importdatei die Spalte „Numerisch“ oder „Datumsaktiviert“ enthält, werden diese Zellen still ignoriert und alle anderen Daten in dieser Datei werden normal importiert. <br/>Vorhandene Classifications können weiterhin über den Standard-Classification-Arbeitsablauf exportiert werden und sind weiterhin in Berichten verfügbar. |
| Change to _Report Total_ calculations | Aktualisiert am 9. Juli 2019 | On **June 18, 2019**, Adobe Analytics made _Report Total_ calculations consistent across all dimensions and metrics. Dies führte zu einer Änderung der Summen für einige Berichte (in der Regel "Prop" oder" Kundenattribute" ). Vor dieser Änderung kam es vor, dass in manchen Berichtssummen der Zeileneintrag _Unspecified_ uneinheitlich ein- oder ausgeschlossen wurde, und zwar unabhängig davon, ob _Unspecified_ im Bericht vorkam oder nicht. <br/>Ab 18. Juni 2019 wird _Nicht angegeben_ immer in Berichtssummen angezeigt, auch wenn dieser Wert nicht als Zeileneintrag im Bericht zu sehen ist. Darüber hinaus können Segmente, die die Logik _existiert_ oder _existiert nicht_ verwenden, für einige Dimensionen nach dieser Änderung andere Ergebnisse anzeigen, insbesondere Dimensionen, bei denen _Nicht angegeben_ einen speziellen Namen wie den Zeileneintrag „Eingegeben/Mit Lesezeichen versehen“ für die Dimension „Typ der verweisenden Stelle“ oder den Zeileneintrag „Sonstige“ für die Dimension „Gerätetyp“ verwendet werden. Diese Änderung betrifft Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder und die Reporting-API. |
| Aktualisierung von CSV-Downloads aus Analysis Workspace | 10. April 2019 | Starting on April 11, 2019, several changes were made to **[!UICONTROL CSV downloads]** (and **[!UICONTORL Copy to Clipboard]**) from Analysis Workspace to remove formatting from exported data.  <ul><li>Das Tausendertrennzeichen ist nicht mehr enthalten. Das Dezimaltrennzeichen wird weiterhin enthalten sein und dem unter **[!UICONTROL Komponenten &gt; Berichtseinstellungen &gt; Tausendertrennzeichen]** definierten Format entsprechen. Hinweis: Numerische Werte, die ein Komma als Dezimaltrennzeichen verwenden, werden weiterhin in der exportierten CSV angegeben.</li><li>Es werden keine Währungssymbole angezeigt.</li><li>Es werden keine Prozentsymbole angezeigt. Prozentangaben werden in Dezimalform angezeigt. Zum Beispiel werden 75 % als 0,75 dargestellt.</li><li>Die Zeit wird in Sekunden angezeigt.</li><li>Kohortentabellen zeigen nur Rohwerte an. Prozentsätze werden entfernt.</li><li>Wenn eine Nummer ungültig ist, wird eine leere Zelle angezeigt.</li></ul> |
| Anstehende Änderung am Befehl „Analysis Workspace Debugger“ | 4. April 2019 | Der Befehl „Console“ zum Aktivieren des Analysis Workspace-Debuggers ändert sich am **13. Juni 2019** in adobeTools.debug.includeOberonXml. adobe.tools.debug.includeOberonXml wird nach diesem Datum nicht mehr funktionieren. |
| Mobile Browser – Versionsnummern | 7. Februar 2019 | Am 8. Januar 2019 haben wir die Abschnittsebene bei den Versionsnummern mobiler Browser von 2 zu 1 geändert. Seit diesem Datum zeigen die Versionen nur die ersten beiden Ebenen an (Beispiel: _Firefox 64.0.2_ wird jetzt als _Firefox 64.0_ angegeben). |
| Wird eingestellt [!DNL Ad Hoc Analysis] | 29. Januar 2019 | Am 6. August 2018 kündigte Adobe die Absicht an, [!DNL Ad Hoc Analysis] einzustellen. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist.<br/>Weitere Informationen dazu, welche Versionen von Java während dieses Zeitraums kompatibel sein werden, finden [Sie unter [! DNL Discover Workspace]](https://adobe.ly/discoverworkspace). |
| Kurz-Links [!DNL Analytics] für Berichte | 14. Januar 2019 | Kurz-Links [!DNL Analytics] für Berichte, die innerhalb eines Jahres nicht aufgerufen wurden, werden entfernt und ab Donnerstag, den 17. Januar 2019 fortlaufend gelöscht. |
| Daten-Feed: Spalte „post_product_list“ – Änderung der Größe | 9. Januar 2019 | Adobe hat die Größe der Spalte „post_product_list“ am dem 7. Februar 2019 von 64 KB auf 16 MB erweitert. Diese Änderung stellt sicher, dass bei der Verarbeitung zu „post_product_list“ hinzugefügte Merchandising-eVar-Werte nicht zu abgeschnittenen Produkt- und Umsatzwerten führen. Wenn Sie über Prozesse verfügen, bei denen post_product_list-Werte erfasst werden, stellen Sie sicher, dass diese Prozesse Werte mit einer Länge von bis zu 16 MB verarbeiten können (ansonsten werden Werte bei 16 KB abgeschnitten), um Datenerfassungsfehler zu vermeiden. |
| Verwaltungsänderungen mit Auswirkung auf inaktive [!DNL Analytics Live Stream]-Endpunkte | 20. Dezember 2018 | Ab dem 1. Februar 2019 können [!DNL Live Stream]-Endpunkte, die 90 Tage lang keine aktive Verbraucherverbindung aufweisen, deaktiviert werden. Sie können sich an die Kundenunterstützung wenden, um sich über Ihre [!DNL Live Stream]-Endpunkte zu informieren und diese bei Bedarf wieder zu aktivieren. Stellen Sie außerdem sicher, dass für Ihre Verbraucherprozesse eine dauerhafte Verbindung besteht, wie es das Konzept des Dienstes vorsieht, und dass sie so implementiert sind, dass sie sich wieder verbinden, wenn die Verbindung getrennt oder unterbrochen wird. |
| Aktualisieren von Adobe [!DNL Report Builder] aufgrund der Einstellung des Supports für TLS 1.0 | 7. Sept. 2018 |
| Ende der Unterstützung für TLS 1.0 | Aktualisiert am 10. Januar 2019 | TLS 1.0 wird nicht mehr unterstützt in |

### [!DNL AppMeasurement] {#appm}

Siehe [appmeasurement for Javascript-Versionshinweise](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-release-notes/c-release-notes-mjs.html).

## Audience Manager {#aam}

Neue Funktionen, Verbesserungen und Fehlerbehebungen in Audience Manager.

### Neue Funktionen und Verbesserungen {#aam-features}

| Funktion | Beschreibung |
| -----------| ---------- |  
| **[Benutzerbasierte Ziele](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html)** | [!DNLPeople-basierte Ziele] sind ein kostenpflichtiges Audience Manager-Add-on, mit dem Sie Zielgruppensegmente von Erstanbietern in verschiedenen Umgebungen, wie Facebook, mithilfe von Hash-Bezeichnern wie E-Email-Adressen aktivieren können. |
| **[Konfigurieren von Twitter-angepassten Zielgruppen als selbstbedienungsbasiertes Ziel](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/device-based/twitter-tailored-audiences.html)** | Wir migrieren Twitter-Ziele in ein Selbstbedienungskonfigurationsmodell. In diesem Artikel wird beschrieben, was Sie für vorhandene Twitter-Integrationen tun müssen, um nach der Migration weiterhin arbeiten zu können. |
| **[Audience Marketplace Rechnungsling](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/audience-marketplace/audience-marketplace-for-data-buyers/marketplace-buyer-billing.html#billing-examples)** | Wir haben ein neues Beispiel in Fall 3 hinzugefügt, in dem wir detailliert angeben, wie die Abrechnung für Segmente mit Aktivierungs- und Modellierungsanwendungsfällen funktioniert. |

**Fehlerbehebungen und Verbesserungen**

* Es wurde ein Fehler behoben, durch den Benutzer Adobe Analytics-Ziele nicht bearbeiten konnten, um Segmente manuell zuzuordnen. (AAM-49323)
* Es wurde ein Fehler behoben, durch den doppelte Audience Marketplace-Feeds aus einer einzigen Datenquellen-ID stammen. Zwischen Datenquellen und [!DNL Marketplace] Feeds muss eine 1:1-Zuordnung vorhanden sein. (AAM-48504)
* Wir haben die Arbeitsabläufe für Eigenschaften und Segmente verbessert. Jetzt können Sie die Datenquelle filtern, um Eigenschaften oder Segmente zu speichern, um Nicht-Audience Manager-Datenquellen auszuschließen (z. B. Report Suite-Datenquellen aus Adobe Analytics). (AAM-35899)
* Es wurde ein Problem in der Data Sources-API behoben, bei dem die Einstellung des Abfrageparameters `ExcludeReportSuites=true` keine Report Suite-Datenquellen aus Adobe Analytics ausschließte. (AAM-48545)
* Im Zusammenhang mit der Barrierefreiheit der Audience Manager-Benutzeroberfläche wurden verschiedene Verbesserungen vorgenommen. (AAM -49024) und (AAM -49031)

## Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktveröffentlichung

**Cloud Manager 2019.8.0**

Cloud Manager Release 2019.8.0 beinhaltet eine Vielzahl von kleineren Bugs, verbessert die Leistung und fügt Unterstützung für selektive erstellte Inhaltspakete hinzu.

* [Versionshinweise für Cloud Manager 2019.8.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Produktwartung

**Roadmap für AEM Maintenance Release**

Weitere Informationen finden Sie im AEM Maintenance Release Plan, wie er hier veröffentlicht [](https://helpx.adobe.com/experience-manager/maintenance-releases-roadmap.html)wird.

### Selbsthilfe

**Vorabversion von Asset Link 1.1**

* [Informationen zur Vorabversion von Adobe Asset Link](https://helpx.adobe.com/enterprise/using/adobe-asset-link-prerelease.html)
* [Konfigurieren von AEM für den Adobe Asset Link für Vorabversion](https://helpx.adobe.com/enterprise/using/configure-aem-for-aal-prerelease.html)

**AEM Desktop App 2.0**

AEM Desktop App 2.0 für MAC wurde 30. August 2019 veröffentlicht. AEM Desktop App 2.0 für Windows wird Anfang September veröffentlicht.

Hier finden Sie Dokumentation und Downloads [](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/introduction.html).

**Smart-Tags für Assets**

Hier erfahren Sie, wie Sie ein Zertifikat aktualisieren, nachdem es abgelaufen [](https://helpx.adobe.com/experience-manager/6-5/assets/using/config-smart-tagging.html#Obtainpubliccertificate)ist.

**AEM 6.5 Bildschirme Benutzerhandbuch**

Neue Dokumentation zu _Richtlinien_ zur Netzwerkbereitstellung ist jetzt verfügbar. See the [User Guide](https://helpx.adobe.com/experience-manager/6-5/screens/user-guide.html).

**Automatisierte Forms-Konversionsdienst**

Die Dokumentation für den automatisierten Konvertierungsdienst für AEM Forms ist jetzt verfügbar. Siehe [Einführung in den Konversionsdienst für automatisierte Formulare](https://helpx.adobe.com/experience-manager/Automated-Forms-Conversion-Service/introduction-to-automated-form-conversion-service.html).

### Community

**Weem Intelligence Builder-Webinare**

* [Adobe Experience Manager-Sites](https://forums.adobe.com/thread/2647742)

   | Webinar | Datum |
   | -----------| ---------- |  
   | _Authoring von Web-Erlebnissen_ | 27. August 2019 |
   | _Inhalt suchen und navigieren_ | 03. September 2019 |
   | _Immer wechselnde Inhalte verwalten_ | 10. September 2019 |
   | _Fließende Erlebnisse_ | 17. September 2019 |
   | _Multilingual, Multi-National, um eine globale Website-Struktur zu erstellen und zu verwalten_ | 24. September 2019 |

* [Adobe Experience Manager Assets](https://forums.adobe.com/thread/2647743)

   | Webinar | Datum |
   | -----------| ---------- |  
   | _Ordnerstruktur und Suche_ | 29. August 2019 |
   | _Metadaten_ | 05. September 2019 |
   | _Brand Portal _ | 12. September 2019 |
   | _Dynamische Medien_ | 19. September 2019 |
   | _Asset-Link_ | 26. September 2019 |

* [Adobe Experience Manager Forms](https://forums.adobe.com/thread/2647744)

   | Webinar | Datum |
   | -----------| ---------- |  
   | Forms 101_ | 04. September 2019 |
   | _Verbinden von Formularen mit Datenbanken, Erstellen von Workflows und Integrieren von Formularen mit E-Signaturen_ | 11. September 2019 |
   | _Mobile-Responsive Web und druckfertige interaktive Kommunikation erstellen_ | 25. September 2019 |

* [Adobe Experience Manager Cloud Manager](https://forums.adobe.com/thread/2647745)

   | Webinar | Datum |
   | -----------| ---------- |  
   | _Testen von Best Practices - Erstellen, Überwachen, Prüfen und Einblicke mit Cloud Manager_ | 18. September 2019 |
   | _Dispatcher-Konfigurationen mit Cloud Manager_ | 16. Oktober 2019 |
   | _Erstellen von Workflows mit Cloud Manager und Drittanbieter-Tools_ | 13. November 2019 |

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

[!DNL Digital Publishing Suite Classic] (DPSC) endet am 31. August 2019. Weitere Informationen finden Sie unter [[! DNL Digital Publishing Suite Classic] FAQ](https://helpx.adobe.com/digital-publishing-suite/help/eol-statement-for-dpsc.html)zum Lebenszyklusende.

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

### Adobe Campaign [!UICONTROL Control Panel]

Wir haben neue Funktionen für Administratoren hinzugefügt, die Benachrichtigungen erhalten, bevor SSL-Zertifikate für ihre Domänen ablaufen. Weitere Informationen finden Sie in der [ausführlichen Dokumentation](https://helpx.adobe.com/campaign/kb/control-panel-subdomains-certificates.html).

Außerdem können Administratoren nun SSH-Schlüssel löschen, die zum Zugriff auf SFTP-Server hinzugefügt wurden.

Beachten Sie, dass das [!UICONTROL Control Panel] sowohl für auf AWS gehostete Kunden von Adobe Campaign Classic als auch von Adobe Campaign Standard verfügbar ist. No upgrades are required to access [!UICONTROL Control Panel].

### Zusätzliche Ressourcen

* Adobe Campaign Standard: [Documentation](https://helpx.adobe.com/support/campaign/standard.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html)
* Adobe Campaign Classic: [Documentation](https://helpx.adobe.com/support/campaign/classic.html) - [Release Notes](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [How-to videos](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
