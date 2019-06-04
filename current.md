---
title: Adobe Experience Cloud – Versionshinweise
description: Vorlage für Experience Cloud-Versionshinweise
doc-type: Versionshinweise
last-update: Mai 2019
author: mfrei
translation-type: tm+mt
source-git-commit: c8db350233cea9b83993e4723601b01a8e301f87

---


# Adobe Experience Cloud – Versionshinweise

Neue Funktionen und Fehlerbehebungen in Adobe Experience Cloud.

>[!NOTE]
>Abonnieren Sie das [Prioritätsprodukt-Update von Adobe](https://www.adobe.com/subscription/priority-product-update.html), um per E-Mail über bevorstehende Versionen benachrichtigt zu werden. Sie erhalten drei bis fünf Werktage vor der Veröffentlichung der Version eine Benachrichtigung. Nach dem Release veröffentlichte neue Informationen werden mit dem Veröffentlichungsdatum gekennzeichnet.

**Veröffentlichungsdatum: Mai 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Kampagne](#ac)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.5.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Versionshinweise zu Adobe Experience Platform

Version 1.0, 15. Mai 2019

* Aktuelle Aktualisierungen zur Experience Platform finden Sie unter [Experience Platform Versionshinweise](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) zu Adobe. io.

### Experience Platform Launch

* Aktuelle Informationen finden Sie unter [Experience Platform Start](https://docs.adobelaunch.com/) .

### Experience Cloud ID-Dienst

Veröffentlichung am **13. Mai 2019**

* Unterstützung für Besucher-API 4.3.0
* Unterstützung für ITP 2.1.
* Ein Problem mit der Konfiguration von secureCookie wurde behoben.

## Analytics {#analytics}

Neue Funktionen und Fehlerbehebungen in Adobe Analytics:

* [Neue Funktionen und Fehlerbehebungen in Adobe Analytics](#aa-features)
* [Wichtige Hinweise für Analytics-Administratoren](#aa-notices)

Eine Produktdokumentation finden Sie auf der [Startseite der Hilfe zu Analytics](https://marketing.adobe.com/resources/help/en_US/reference/).

### Neue Funktionen und Fehlerbehebungen in Adobe Analytics {#aa-features}

| Funktion | Beschreibung |
| -----------| ---------- |  
| [!DNL AppMeasurement Version 2.14.0] <ul><li>Es wurden Probleme mit der Verwaltung des Status von Trackerparametern behoben, wenn mehrere Treffer ausstehend sind. (AN -176931, AN -176629, DTM -12758)</li><li>Appmeasurement aktualisiert auf Visitor. js 4.3.0 (AN -180049)</li></ul> |
| [!DNL Analysis Workspace]: Neue Einstellung für die Flussvisualisierung: _Wiederholungsinstanzen einschließen_ | Mit der Option _Wiederholungsinstanzen einschließen_ können Sie Wiederholungsinstanzen, wie z. B. das Neuladen von Seiten, ein- oder ausschließen. Außerdem basieren alle Flussvisualisierungen jetzt nur noch auf Instanzen. |
| [!DNL Ad Hoc Analysis]: Kompatibilität mit Java 11 | Ad Hoc Analysis ist jetzt kompatibel mit Java 11. Erfahren Sie, wie [Sie Ad-hoc-Analysen auf Java 11 ausführen](https://marketing.adobe.com/resources/help/en_US/dsc/adhoc-java.html). |
| **Datenerfassung:** Neues s_ ecid-Cookie | Der neue Erstanbieter-Cookie s_ecid wurde hinzugefügt, in dem die ECID des Besuchers gespeichert wird. |

**Korrekturen am Analysis Workspace**

* Korrektur eines Problems, das sich auf die **[!UICONTROL Besuchszeit pro Seite ausgewirkt hat]**. [!DNL Analysis Workspace] Berichte verwenden keinen **[!UICONTROL Seitennamen]** mehr, wenn die Behälter **[!UICONTROL &quot;Besuchszeit]** &quot; berechnet werden. Dadurch können granulare und gestapelte Treffer gezählt werden. (AN-140479)
* Es wurden Leistungsprobleme bei der Linienvisualisierung behoben, die im Rahmen größerer Bemühungen zur Leistungsverbesserung [!DNL Analysis Workspace] auftraten. (AN-174878)
* Korrektur eines Problems aufgrund fehlender UTF-8-Kodierungen in heruntergeladenen .csv-Dateien. (AN-178393)
* Es wurden Probleme mit langsamen [!DNL Analysis Workspace] Projektleistung behoben. (AN-177710)
* Anzeigeprobleme bei der Linienvisualisierung, die bei kleinen Bereichen in der Granularität der Y-Achse auftraten, wurden korrigiert. (AN-176467)

**Andere Fehlerbehebungen in Analytics**

* [!DNL Audience Analytics]: Es wurde ein Problem behoben, das auftrat, nachdem ein Zielgruppenname geändert wurde. [!DNL Audience Manager (AAM)] Der aktualisierte Name wurde nicht in Audience Analytics angezeigt. (AN-176237)
* Es wurde ein Problem behoben, durch das Benutzer [! DNL Analytics-Segmente [!DNL Audience Manager]in. Dies wurde durch vorhandene AAM-Ordner mit uneinheitlicher Groß- und Kleinschreibung verursacht. Bei allen Ordnern wird jetzt die Groß- und Kleinschreibung ignoriert, sodass sie in jedem Fall synchronisiert werden. (AN-177934)
* Es wurde ein Problem behoben, das auftrat, wenn Benutzer sich [!DNL Analytics] über das und [!DNL Experience Cloud] dann über die Sitzung angemeldet hatten. Beim Fortsetzen der Sitzung wurde der Benutzer zu einer fehlerhaften URL umgeleitet. (AN-176812)
* Es wurde ein Problem mit Zeitzonenabständen in [!DNL Data Warehouse] Anforderungen behoben. (AN-177585)

### Wichtige Hinweise für Analytics-Administratoren {#aa-notices}

| Hinweis | Datum hinzugefügt  oder aktualisiert am | Beschreibung |
| -----------| ---------- | ---------- |
| Bevorstehende Supportänderungen für **[!UICONTROL Datumsaktivierte]** und **[!UICONTROL nummerische 2 Classifications]** | Aktualisiert am 28. Mai 2019 | Die Möglichkeit, Nummerisch -2- und datumsaktivierte Classifications zu importieren, wird aus der Codebase entfernt. Diese Änderung wird ab dem Maintenance Release vom Juli 2019 wirksam. Wenn die Importdatei die Spalte „Numerisch“ oder „Datumsaktiviert“ enthält, werden diese Zellen still ignoriert und alle anderen Daten in dieser Datei werden normal importiert. <br/>Vorhandene Classifications können weiterhin über den Standard-Classification-Arbeitsablauf exportiert werden und sind weiterhin in Berichten verfügbar. |
| Bevorstehende Änderung bei Berechnungen der _Berichtssumme_ | Aktualisiert am 2. Mai 2019 | Ab **13. Juni 2019** werden in Adobe Analytics Berechnungen von _Berichtssummen_ für alle Dimensionen und Metriken vereinheitlicht. Dadurch werden sich die Gesamtsummen bei manchen Berichten ändern (vor allem bei Berichten zu Eigenschaften oder Kundenattributen). Vor dieser Änderung kam es vor, dass in manchen Berichtssummen der Zeileneintrag _Unspecified_ uneinheitlich ein- oder ausgeschlossen wurde, und zwar unabhängig davon, ob _Unspecified_ im Bericht vorkam oder nicht. <br/>Ab 13. Juni 2019 wird _Nicht angegeben_ immer in Berichtssummen angezeigt, auch wenn dieser Wert nicht als Zeileneintrag im Bericht zu sehen ist. Außerdem kann es vorkommen, dass Segmente, die die _ist vorhanden_- oder _ist nicht vorhanden_-Logik nutzen, nach dieser Änderung andere Ergebnisse für einige Dimensionen aufweisen. Diese Änderung betrifft Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder und die Reporting-API. |
| Aktualisierung auf CSV-Downloads von [!DNL Analysis Workspace] | 10. April 2019 | Ab dem 11. April 2019 wurden verschiedene Änderungen an **[!UICONTROL CSV-Downloads]** vorgenommen (und **[!UICONTORL in die Zwischenablage kopieren]**), [!DNL Analysis Workspace] um Formatierungen aus exportierten Daten zu entfernen.  <ul><li>Der Tausender-Trennzeichen ist nicht mehr enthalten. Das Dezimaltrennzeichen wird weiterhin enthalten sein und dem unter **[!UICONTROL Komponenten &gt; Berichtseinstellungen &gt; Tausendertrennzeichen]** definierten Format entsprechen. Hinweis: Numerische Werte, die ein Komma als Dezimaltrennzeichen verwenden, werden weiterhin in der exportierten CSV angegeben.</li><li>Es werden keine Währungssymbole angezeigt.</li><li>Es werden keine Prozentsymbole angezeigt. Prozentangaben werden in Dezimalform angezeigt. Zum Beispiel werden 75 % als 0,75 dargestellt.</li><li>Die Zeit wird in Sekunden angezeigt.</li><li>Kohortentabellen zeigen nur Rohwerte an. Prozentsätze werden entfernt.</li><li>Wenn eine Nummer ungültig ist, wird eine leere Zelle angezeigt.</li></ul> |
| Bevorstehende Änderung des [!DNL Analysis Workspace] Debuggers | 4. April 2019 | Der Befehl &quot;Console&quot; zum Aktivieren des [!DNL Analysis Workspace] Debuggers wechselt am **13. Juni 2019 zu adobetools. debug. includeoberonxml**. adobe.tools.debug.includeOberonXml wird nach diesem Datum nicht mehr funktionieren. |
| Mobile Browser – Versionsnummern | 7. Februar 2019 | Am 8. Januar 2019 haben wir die Abschnittsebene bei den Versionsnummern mobiler Browser von 2 zu 1 geändert. Seit diesem Datum zeigen die Versionen nur die ersten beiden Ebenen an (Beispiel: _Firefox 64.0.2_ wird jetzt als _Firefox 64.0_ angegeben). |
| Lebenszyklusende für [!DNL Ad Hoc Analysis] | 29. Januar 2019 | Am 6. August 2018 kündigte Adobe das Ende des Lebenszyklus [!DNL Ad Hoc Analysis]an. Das Datum für das Ende des Produktlebenszyklus wird bekannt gegeben, sobald es verfügbar ist.<br/>Weitere Informationen dazu, welche Versionen von Java während dieses Zeitraums kompatibel sind, finden Sie unter [Arbeitsbereich entdecken](https://adobe.ly/discoverworkspace). |
| Kurz-Links für Analytics-Berichte | 14. Januar 2019 | Kurz-Links für Analytics-Berichte, die innerhalb eines Jahres nicht aufgerufen wurden, werden entfernt und ab Donnerstag, den 17. Januar 2019 fortlaufend gelöscht. |
| Ende der Unterstützung für TLS 1.0 | Aktualisiert am 10. Januar 2019 | Ab dem 11. Februar 2019 unterstützt die Adobe Analytics-Berichterstellung die Verschlüsselung mit TLS (Transport Layer Security) 1.0 nicht mehr. Diese Änderung ist Teil unserer ständigen Bemühungen, die höchsten Sicherheitsstandards einzuhalten und die Daten unserer Kunden zu schützen. Wenn Sie nach dem 11. Februar 2019 keine Verbindung zu Adobe Analytics-Berichten herstellen können, sollten Sie den Browser auf die [neueste Version aktualisieren](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> Ab dem 20. Februar 2019 bietet die Adobe Analytics-Datenerfassung keine Unterstützung für TLS 1.0 mehr. Aufgrund dieser Änderung werden von Adobe keine Analytics-Daten von Endbenutzern mit älteren Geräten oder Webbrowsern ohne Unterstützung für TLS 1.1 oder höher erfasst. Wir gehen davon aus, dass dies keine wesentlichen Auswirkungen auf Kundendaten oder die Berichterstattung haben wird. (Wenn Ihre Website TLS 1.0 bereits nicht mehr unterstützt, sind Sie nicht betroffen.) <br/>Ab dem 11. April 2019 bietet die Reporting-API von Adobe Analytics keine Unterstützung mehr für die TLS 1.0-Verschlüsselung. Kunden, die auf die API zugreifen, sollten sicherstellen, dass sie nicht von den Auswirkungen betroffen sind. <ul><li>Für API-Clients, die Java 7 mit den Standardeinstellungen verwenden, müssen einige [Änderungen zur Unterstützung von TLS 1.2](https://www.java.com/en/configure_crypto.html) vorgenommen werden (siehe _„Changing default TLS protocol version for client end points: TLS 1.0 to TLS 1.2“_).  </li><li>API-Clients mit Java 8 sollten nicht betroffen sein, da die Standardeinstellung TLS 1.2 ist.</li><li> Bei API-Clients, die andere Frameworks verwenden, müssen Sie die Details zur Unterstützung von TLS 1.2 beim jeweiligen Anbieter erfragen.</li></ul> |
| Daten-Feed: Spalte „post_product_list“ – Änderung der Größe | 9. Januar 2019 | Adobe hat die Größe der Spalte „post_product_list“ am dem 7. Februar 2019 von 64 KB auf 16 MB erweitert. Diese Änderung stellt sicher, dass Merchandising-evar-Werte, die während der Verarbeitung zu post_ product_ list hinzugefügt wurden, keine Kürzung der Produkt- und Umsatzwerte verursachen. Wenn Sie über Prozesse verfügen, bei denen post_product_list-Werte erfasst werden, stellen Sie bitte sicher, dass diese Prozesse Werte mit einer Länge von bis zu 16 MB verarbeiten können (ansonsten werden Werte bei 16 KB abgeschnitten), um Datenerfassungsfehler zu vermeiden. |
| Managementänderungen wirken sich auf inaktive [!DNL Analytics Live Stream] Endpunkte aus | 20. Dezember 2018 | Ab dem 1. Februar 2019 können [!DNL Live Stream] Endpunkte ohne aktive Kundenverbindungen für 90 Tage deaktiviert werden. Sie können sich an den Kundendienst wenden, um Ihre [!DNL Live Stream] Endpunkte zu erhalten und bei Bedarf erneut zu aktivieren. Stellen Sie außerdem sicher, dass für Ihre Verbraucherprozesse eine dauerhafte Verbindung besteht, wie es das Konzept des Dienstes vorsieht, und dass sie so implementiert sind, dass sie sich wieder verbinden, wenn die Verbindung getrennt oder unterbrochen wird. |
| Aktualisieren von Adobe [!DNL Report Builder] aufgrund der Einstellung des Supports für TLS 1.0 | 7. Sept. 2018 | Aufgrund der Unterstützung für TLS 1.0 sollten [!DNL Report Builder] Benutzer Version 5.6.21 vor Februar 2019 herunterladen. Nach diesem Datum funktionieren frühere Versionen von [!DNL Report Builder] nicht mehr. |

## Audience Manager {#aam}

| Funktion | Beschreibung |
| -----------| ---------- |  
| [Verschleierung von IP-Adressen](https://marketing.adobe.com/resources/help/en_US/aam/ip-obfuscation.html) | Aufgrund globaler Datenschutzregeln muss Ihr Unternehmen in einigen Ländern möglicherweise IP-Adressen verschleiern. Mit Audience Manager können Sie die IP-Adressen der Besucher auf globaler oder Länderebene verschleiern. |
| [Benutzerdefinierte Partnerintegrationen – Oracle Data Cloud](https://marketing.adobe.com/resources/help/en_US/aam/custom-partner-integrations.html) | Diese Seite enthält benutzerdefinierte Integrationen zwischen Audience Manager und Datenpartnern. Audience Manager übernimmt mithilfe von eingehenden Datendateien Cookie-Daten und mobile IDs aus der Oracle Data Cloud für Audience Marketplace. Die auf dieser Seite beschriebenen benutzerdefinierten Integrationen beziehen sich nur auf eingehende Datendateien, die mobile IDs (IDFA und Android-Geräte-IDs) enthalten. |

**Fehlerbehebungen, Verbesserungen und veraltete Elemente**

* Den allgemeinen Berichten für Ziele wurden zwei neue Spalten hinzugefügt. Sie können jetzt das Startdatum und das Enddatum für die Zuordnung eines Segments zu einem Ziel sehen. (AAM-44781)

## Experience Manager {#aem}

Neue Funktionen, Fehlerbehebungen und Aktualisierungen in Adobe Experience Manager (AEM). Adobe empfiehlt Kunden mit lokalen Implementierungen, die aktuellen Patches zu implementieren, um mehr Stabilität, Sicherheit und Leistung zu erzielen.

### Produktversionen

**AEM 6.5**

AEM 6.5 ist ein Upgrade-Release zur Codebasis von AEM 6.4, das ab dem 8. April 2019 verfügbar ist. Durch die neuesten Updates in AEM 6.5 erhalten Sie sofortigen Zugriff auf großartige Verbesserungen, mit denen Sie Ihr Unternehmen noch schneller voranbringen können.

* [Neue Funktionen in Adobe Experience Manager 6.5](https://www.adobe.com/marketing/experience-manager/new.html)
* [Versionshinweise für Adobe Experience Manager 6.5](https://helpx.adobe.com/experience-manager/6-5/release-notes.html)

**Cloud Manager 2019.4.0**

Die neueste Version von Cloud Manager (2019.4.0, veröffentlicht am 18. April 2019) hat jetzt auch eine lokalisierte Benutzeroberfläche in Französisch, Deutsch und Japanisch. Außerdem wurden die Implementierungsschritte verbessert.

* [Versionshinweise für Cloud Manager 2019.4.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

### Produktwartung

**AEM 6.4.4.0**

AEM 6.4 Service Pack 4 (6.4.4.0, veröffentlicht am 4. April 2019) ist ein wichtiges Update, das für Kunden wichtige Fehlerbehebungen enthält, die seit der allgemeinen Verfügbarkeit von AEM 6.4 im April 2018 veröffentlicht wurden.

[Versionshinweise für AEM 6.4 Service Pack](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
[AEM Forms-Versionen](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

**AEM S3 Connector**

AEM-Instanzen mit alten Versionen des S3 Datastore Connector sind aufgrund von S3-Zugriffsfehlern nach dem Supportende von Signature Version 2 am 24. Juni 2019 nicht mehr verfügbar. Adobe empfiehlt AEM-Kunden zu prüfen, welche Version des S3 Datastore Connector sie verwenden. Gegebenenfalls sollte auf eine neuere Version aktualisiert werden.

Siehe [The Impact of AWS Signature Version 2 Deprecation for Amazon S3](https://helpx.adobe.com/experience-manager/kb/the-impact-of-aws-signature-version-2-deprecation-for-amazon-s3.html)

### Selbsthilfe

**Modernisieren der AEM Sites-Codebasis**

Erfahren Sie, wie Sie die neueste AEM-Technologie nutzen, um Ihre AEM Sites-Codebase zu modernisieren. [Modernisierung Ihrer vorhandenen Adobe Experience Manager-Sites-Codebase](https://expleague.azureedge.net/labs/L761/index.html)

**AEM Rich Text Editor – Ausführliche Erklärung**

Erfahren Sie mehr über die vielfältigen Konfigurations- und Nutzungsmöglichkeiten des Rich Text Editor in AEM.

Siehe [AEM Rich Text Editor (RTE) Deep Dive](https://helpx.adobe.com/experience-manager/kt/eseminars/gems/AEM-Rich-Text-Editor-RTE-Deep-Dive1.html)

### Zusätzliche Ressourcen 

* [AEM 6.5 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 Schulung und Support – Startseite](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Cloud Manager-Benutzerhandbuch](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Ältere Versionen der AEM-Dokumentation](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Scene7 Publishing System – Versionshinweise](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Livefyre-Versionshinweise](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## Kampagne {#ac}

Adobe Campaign bietet die Möglichkeit, direkte Nachrichten über Online- und Offline-Marketing-Kanäle intuitiv und automatisiert zu übermitteln. Sie können nun vorhersagen, was Ihre Kunden wünschen, und ihnen Erlebnisse bieten, die Sie anhand ihrer Gewohnheiten und Vorlieben ermittelt haben.

* Kampagne Classic 18.10.4 - Build 8983
* Kampagne Classic 18.10.5 - Build 8984

Fehlerbehebungen und Verbesserungen finden Sie unter [Adobe Campaign Classic – Versionshinweise](http://docs.campaign.adobe.com/doc/AC/en/RN.html).

Eine Produktdokumentation finden Sie hier:

* Adobe Campaign Standard: [Dokumentation](https://helpx.adobe.com/support/campaign/standard.html) – [ Versionshinweise](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) – [Videos zu Funktionen](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Dokumentation](https://helpx.adobe.com/support/campaign/classic.html) – [Versionshinweise](https://docs.campaign.adobe.com/doc/AC/en/RN.html) – [Videos zu Funktionen](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Advertising Cloud {#adcloud}

| Funktion | Beschreibung |
| -----------| ---------- |  
| Durchsuchen Werkzeuge | (Werbekunden mit Google Ads-Konten) Aus Advertising Cloud können optional alle Konversionsdaten in Google Ads hochgeladen werden, die für Google Ads-Kampagnen getrackt werden, die den Konversions-Trackingdienst der Advertising Cloud nutzen. Zu den täglichen Uploads gehört der Konversionswert, der über das Attributionsmodell auf Ebene der Werbekunden definiert wird. Alle hochgeladenen Konversionen haben das Präfix „Adobe_ACS_“ (z. B. „Adobe_ACS_Abonnements“ für die Konversion „Abonnements“). <br/> **Hinweis**: Die Uploads enthalten keine in Advertising Cloud hochgeladenen Konversionsdaten aus Feeddateien. |
| Suchkampagnen | Das Menü &quot; **Suchen** &quot; &gt; **&quot; Kampagnen** «&gt; **&quot;Kampagnen&quot;** ist jetzt hierarchisch, mit Kampagnen unter Konten. Anzeigengruppen unter Kampagnen; und Suchbegriffe (mit Untermenü), Anzeigen, Produktgruppen (nur Live-Ansichten), Platzierungen (mit Untermenü) und automatisches Targeting unter Anzeigengruppen.<br/>In den Live-Ansichten befinden sich Zielgruppen und Erweiterungen auf derselben Ebene wie Konten mit eigenen Untermenüs. |

## Target Standard/Premium 19.5.1 {#target}

Diese Version enthält die folgenden Funktionen, Änderungen und Verbesserungen:

(Die Problemnummern in Klammern sind für den internen Gebrauch von Adobe.)

### Funktionsaktualisierungen

| Funktion/Verbesserung | Beschreibung |
| --- | --- |
| Single Page App Visual Experience Composer (SPA VEC) | Der SPA VEC enthält die folgenden Verbesserungen, mit denen Sie Ihre Arbeit schneller und effizienter erledigen können:<ul><li>Sie können jetzt das Laden einer Website in VEC abbrechen, um die Bearbeitung einer Aktivität zu entsperren. Diese Verbesserung ist nützlich, wenn Sie z. B. eine kleine Änderung an einer Aktivität vornehmen, die Einstellungen in der Vorschau ansehen oder benutzerdefinierten Code hinzufügen möchten, Sie aber nicht warten möchten, bis die Website geladen ist. (TGT-33872)</li><li>Sie können viele Aktionen ausführen, bevor die Seite im VEC geladen wird, oder selbst dann, wenn die Seite nicht vollständig geladen werden kann (wenn beispielsweise benutzerdefinierter Code nicht mehr funktioniert). Aktionen, die nicht bearbeitet werden können, bevor die Website geladen ist, sind in der Benutzeroberfläche von Target deaktiviert. (TGT-33851 und TGT-34149)</li></ul> |
| Aktivitäten vom Typ „Automatisierte Personalisierung“ (AP) und „Automatisches Targeting“ | Sie können beim Erstellen eines AP oder eines automatischen Targetings ein Control-Erlebnis auswählen. Mit dieser Funktion können Sie den gesamten Control-Traffic zu einem bestimmten Erlebnis leiten, basierend auf dem in der Aktivität konfigurierten Traffic-Zuordnungsprozentwert. Anschließend können Sie die Leistung der personalisierten Bereitstellungen anhand des Control-Erlebnisses bewerten. (TGT-26572) |
| Empfehlungen | Sie können den Schalter „Zuvor gekaufte Artikel empfehlen“ beim Erstellen der Logik „Kürzlich angezeigte Elemente“ nutzen. (TGT-34030) |

### Verbesserungen, Fehlerbehebungen und Änderungen

* Die Symbole der Symbolleiste werden entsprechend angezeigt, nachdem Sie das Laden einer Seite innerhalb des VEC abgebrochen haben. Wenn bestimmte Aktionen erst nach dem vollständigen Laden der Seite ausgeführt werden können, werden die zugehörigen Symbolleistensymbole deaktiviert. (TGT-33811)
* Sie können jetzt einfacher durch Angebotsordner im Asset-Wähler blättern und navigieren, anstatt durch eine flache Ordnerhierarchie zu navigieren. (TGT-33725)

In den [Adobe Target-Versionshinweisen](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) finden Sie die aktuellen Versionsinformationen zu den folgenden Produkten:

* Target Standard und Target Premium
* Recommendations Classic

## Magento {#magento}

Magento ist eine E-Commerce-Plattform, die Online-Händlern ein flexibles Warenkorbsystem und Kontrolle über den Look, den Inhalt und die Funktionalität des Online-Geschäfts bietet. Magento ist in einer Open-Source-Version und in einer umfassenderen Commerce-Version verfügbar.

Magento Commerce ist Teil der Adobe Commerce Cloud und bietet eine E-Commerce-Lösung mit Enterprise-Power, unbegrenzter Skalierbarkeit und Open-Source-Flexibilität für B2C- und B2B-Anwendungen.

Versionshinweise für unsere Open Source- und Commerce-Editionen finden Sie auf der Seite [&quot;Versionsinformationen](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) &quot; .

## Primetime {#primetime}

Adobe Primetime ist eine Multiscreen-TV-Plattform, mit der Medienunternehmen ein ansprechendes, personalisiertes Fernseherlebnis schaffen und profitabel einsetzen können.

[Primetime – Versionshinweise](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Startseite der Primetime-Hilfe](http://help.adobe.com/en_US/primetime/)