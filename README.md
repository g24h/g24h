<img align="right" height="50" src="https://github.com/g24h/g24h/raw/main/img/G24-Logo.svg"/><br/></br>

# Gründen in 24 Stunden

## Grundlegende Zielsetzung und relevante Initiativen

Der [Koalitionsvertrag](https://www.koalitionsvertrag2025.de/sites/www.koalitionsvertrag2025.de/files/koav_2025.pdf) 
der Bundesregierung, der am **09.04.2025** veröffentlicht wurde, erwähnt mehrmals das politische Ziel die **Unternehmensgründung 
innerhalb von 24 Stunden** zu ermöglichen. Seit **Oktober 2025** arbeitet die [DigitalService GmbH des Bundes](https://digitalservice.bund.de/projekte/schneller-gruenden) 
in enger Abstimmung mit dem [Bundesministerium für Digitalisierung und Staatsmodernisierung](https://bmds.bund.de/themen/staatsmodernisierung/digitale-verwaltung/schneller-gruenden) 
an entsprechenden Lösungsansätzen zur Unternehmensgründung innerhalb von 24 Stunden. 

Obwohl die große Bedeutsamkeit und Dringlichkeit des Vorhabens bereits Ende letzten Jahr von führenden Wirtschaftsverbänden wie dem [Bitkom e.V.](https://www.bitkom.org/Bitkom/Publikationen/24-Stunden-Gruendung-Gruendungsbeschleunigungsgesetz)
und dem [Deutschen Industrie und Handelskammertag (DIHK)](https://www.dihk.de/de/newsroom/unternehmensgruendungen-reformen-dringend-noetig-156348)
angemahnt wurde, dauerte es bis zum **25.03.2026** bis von den Bundesländern [Bayern](https://www.stmwi.bayern.de/presse/pressemeldungen/116-2026/),
[Berlin](https://www.berlin.de/sen/web/presse/pressemitteilungen/2026/pressemitteilung.1656389.php)
und [Nordrhein-Westfalen](https://www.land.nrw/pressemitteilung/gruenden-24-stunden-laender-legen-konzept-fuer-vollautomatisierte) 
die Ergebnisse eines vom [IT-Planungsrat](https://www.it-planungsrat.de/) mandadierten Projektes mit einem Konzept zum [**Gründen in 24 Stunden**](https://www.g24h.de/) vorgestellt wurde. Neben den [Eckpunkten](https://publuu.com/flip-book/1078574/2403751)
eines Gründungsbeschleunigungsgesetzes samt eines Fahrplans von **2026-2029**, wurde auch ein entsprechendes 
[Detailkonzept](https://publuu.com/flip-book/1078574/2404413) für das Gründungsbeschleunigungsgesetz, 
eine [High-Level-IT-Architektur](https://publuu.com/flip-book/1078574/2403754) und schließlich eine
verfassungsrechtliche [Kurz-Analyse](https://publuu.com/flip-book/1078574/2403760) vorgelegt. 
Parallel dazu hat die Europäische Kommission am **19.11.2025** einen Regulierungsvorschlag für die 
Einführung der [European Business Wallets](https://digital-strategy.ec.europa.eu/en/library/proposal-regulation-establishment-european-business-wallets) 
vorgelegt und schließlich am **18.03.2026** einen weiteren Regulierungsvorschlag für ein neues harmonisiertes
Unternehmensrecht veröffentlicht, mit dem im so genannten 28. Regime die Gründung einer [EU Inc.](https://commission.europa.eu/topics/business-and-industry/doing-business-eu/company-law-and-corporate-governance/eu-inc-new-harmonised-corporate-legal-regime_en) 
in einem vollständig digitalen Prozess innerhalb von 48 Stunden möglich werden soll. 

Inzwischen hat die [DigitalService GmbH des Bundes](https://digitalservice.bund.de/projekte/schneller-gruenden) ein entsprechendes Pilotprojekt in Aussicht gestellt, 
das ab **Mai 2026** starten soll und für das sich interessierte [Pilot-Standorte bewerben](https://digitalservice.bund.de/media/pages/projekte/schneller-gruenden/3c137679c7-1775576914/schneller-gruenden_aufruf-pilotierung.pdf) bis zum **22.04.2026**
bewerben konnten. 

## Gründen in <code style="color: red">24 Minuten</code> mit der EUDI-Wallet

>
> Um die effiziente Unternehmensgründung rasch voran zu bringen, sucht der [IT-Umsetzungsrat](https://it-umsetzungsrat.de) 
> ab sofort <code style="color: red">**Turbo-Gewerbeämter**</code>, die unter Einsatz 
> der [<code style="color: red">EUDI-Wallet</code>](https://eudi-wallet.gov.de/) das <code style="color: red">**Gründen in 24 Minuten**</code>
> ermöglichen wollen.
>

Potenziell interessierte Kommunen und sonstige Institutionen mit einem Herz für Gründerinnen und Gründer werden um 
Kontaktaufnahme per E-Mail an [g24h@eID.AS](mailto:g24h@eID.AS) gebeten.


![24-Minuten-Gruendung](https://github.com/g24h/g24h/raw/main/img/Turbo-GA.svg)



## Umsetzung der Systemarchitektur für das Gründen in 24 Stunden

Mit der Bereitstellung des Konzeptes [**Gründen in 24 Stunden**](https://www.g24h.de/) am **25.03.2026** ist das Vorhaben von der 
Planungsphase in die Umsetzungsphase übergegangen, um eine möglichst rasche Umsetzung der nachfolgen skizzierten Systemarchitektur  
und dadurch schließlich die angestrebte Unternehmensgründung innerhalb von 24 Stunden zu ermöglichen.  

![Systemarchitektur](https://github.com/g24h/g24h/raw/main/img/G24.svg) 

Bei der anvisierten Systemarchitektur handelt es sich um Serice-orientierte Architektur (SOA) im 
Sinne von [ISO/IEC 18384-2](https://www.iso.org/standard/63105.html), die im Einklang mit der
anvisierten Architektur des [Deutschland-Stack](https://www.it-planungsrat.de/beschluss/b-2026-03-it) 
aus verschiedenen Schichten besteht, die nachfolgend kurz beschrieben werden.

### Zugangsdienste

Die Gründerinnen und Gründer nutzen das System über geeignete "Gründungsportale" (so genannte "One-Stop-Shops") 
oder entsprechende "Gründerapps", um nach einer sicheren Identifizierung und Authentifizierung 
mit einem geeigneten Identifizierungsmittel, wie z.B. dem [Personalausweis](https://www.personalausweisportal.de/), einem anderen gemäß
[Artikel 9 der eIDAS-Verordnung (EU) No. 910/2014](https://www.eid.as/de/#article9) notifizierten
Identifizierungsmittel oder zukünftig der [EUDI-Wallet](https://bmds.bund.de/themen/digitaler-staat/digitale-identitaeten/eudi-wallet), auf die Dienste der Gründungsplattform zugreifen zu können.

### Gründungsplattform

Die Gründungsplattform besteht aus einer Sammlung von Microservices, auf die über die verschiedenen registrierten 
Gründerportale oder Gründungsapps nach einer geeigneten Authentifizierung und Autorisierung zugegriffen
werden kann. Im Einklang mit den Vorgaben des [Deutschland-Stack](https://www.it-planungsrat.de/beschluss/b-2026-03-it)
erfolgt die sichere Identifizierung und Authentifizierung der Gründerinnen und Gründer über [OpenID Connect](https://openid.net/specs/openid-connect-core-1_0.html)
und die Registrierung, Authentifizierung und Autorisierung von zugreifenden Diensten erfolgt über [OAuth](https://datatracker.ietf.org/wg/oauth/documents/).
Die Microservices der Gründungsplattform nutzen bei Bedarf ausgewählte Basisdienste und nutzen insbesondere 
die verschiedenen Gründungsrelevanten Diensten, um den bisweilen komplexen Geschäftsprozess der 
Unternehmensgründung vollständig digital abwickeln zu können.    

### Gründungsrelevante Dienste

In dieser Schicht finden sich die verschiedenen für die Unternehmensgründung 
relevanten Dienste, die abhängig von der gewählten Rechtsform des zu gründenden Unternehmens 
und den spezifischen Umständen in den Prozess eingebunden werden müssen
oder können.  

#### Industrie- und Handelskammern (IHKs)

Die IHKs sind in potenziell in zweierlei Hinsicht in den Gründungsprozess eingebunden. 
Einerseits bieten zahlreiche IHKs, vermittelt über die [Unternehmenswerkstatt Deutschland](https://www.uwd.de/) 
kompetente und persönliche Beratung sowie nützliche Werkzeuge für Gründerinnen und Gründer an. Andererseits sind 
die IHKs bei verschiedenen gewerblichen Tätigkeiten, wie im Abschnitt zur Gewerbeordnung unten näher erläutert,
bei genehmigungspflichtigen Gewerben und im Zusammenhang mit [Sach- und Fachkundeprüfungen](https://www.dihk.de/de/serviceportal/qualifizierung/sach-und-fachkundepruefungen) 
und in den Gründungsprozess eingebunden. 

Eine ähnliche Rolle spielen bei handwerklichen Gewerben die [Handwerkskammern](https://www.handwerkskammer.de/)
und bei [verkammerten Freien Berufe](https://www.freie-berufe.de/) die entsprechenden Berufskammern für z.B.
Ärzte, Zahnärzte, Tierärzte, Apotheker, Architekten, Rechtsanwälte, Notare, Steuerberater und -bevollmächtigte, Wirtschaftsprüfer und vereidigte Buchprüfer, 
Ingenieure und Psychotherapeuten.

#### Notar

##### Beurkundung von Gründungsdokumenten

Bei der Gründung einer Kapitalgesellschaft, wie z.B. GmbH, UG oder AG, und auch bei bestimmten Personengesellschaften, wie
z.B. OHG, KG oder e.K., sind zwingend Notarinnen oder Notare im Gründungsprozess beteiligt, um die Gründungsdokumente zu beurkunden und letztlich die Anmeldung 
zur Eintragung ins Handelsregister vorzunehmen. Beispielsweise muss bei der Gründung einer GmbH gemäß 
[§ 2 (1) GmbHG](https://www.gesetze-im-internet.de/gmbhg/__2.html) der Gesellschaftsvertrag von allen Gesellschafterinnen und Gesellschaftern 
unterzeichnet und notariell beurkundet werden. Eine fehlende Beurkundung des Gesellschaftsvertrags durch eine Notarin oder 
einen Notar würde auf Grund von [§ 125 BGB](https://www.gesetze-im-internet.de/bgb/__125.html) zur Nichtigkeit des Gesellschaftsvertrags führen.
Gemäß [§ 53 (1) GmbHG](https://www.gesetze-im-internet.de/gmbhg/__53.html) müsste auch eine, etwa bei einer späteren 
Kapitalerhöhung notwendige, Änderung des Gesellschaftsvertrags durch einen Beschluss der Gesellschafter erfolgen, 
der  gemäß [§ 53 (3) GmbHG](https://www.gesetze-im-internet.de/gmbhg/__53.html) ebenso notariell beurkundet werden muss.

Die Details einer Beurkundung sind im Beurkundungsgesetz ([BeurkG](https://www.gesetze-im-internet.de/beurkg))
geregelt. Bei der Beurkundung des unterzeichneten Gesellschaftsvertrags muss gemäß [§ 8 BeurkG](https://www.gesetze-im-internet.de/beurkg/__8.html)
eine schriftliche oder elektronische Niederschrift angefertigt werden. Der Inhalt der Niederschrift 
muss den Beteiligten gemäß [§ 13 (1) BeurkG](https://www.gesetze-im-internet.de/beurkg/__13.html) 
in Gegenwart des Notars vorgelesen werden und die Niederschrift muss von den Beteiligten genehmigt
und eigenhändig unterschrieben, oder gemäß [§ 13a (1) BeurkG](https://www.gesetze-im-internet.de/beurkg/__13a.html) 
elektronisch signiert werden. Hierbei muss entweder eine qualifizierte elektronische Signatur gemäß [Artikel 3 (12)](https://www.eid.as/de/#article3) 
der [eIDAS-Verordnung](https://www.eid.as/) erstellt, oder eine auf einem zur elektronischen 
Erfassung der Unterschrift geeigneten Hilfsmittel, wie einem [Unterschriften-Pad](https://www.bnotk.de/fileadmin/user_upload_bnotk/Rundschreiben/2025/BNotK_RS_2025_04_Anlage_1.pdf), 
eigenhändig unterschrieben werden. 

Seit dem 1. August 2022 gestattet das Beurkundungsgesetz in 
bestimmten Fällen des Gesellschafts- und des Registerrechts die Durchführung notarieller Beurkundungen und 
Beglaubigungen in einem Online-Verfahren, was durch die Umsetzung der so genannten Digitalisierungsrichtlinie 
[(EU) 2019/1151](https://eur-lex.europa.eu/legal-content/DE/TXT/HTML/?uri=CELEX:32019L1151) zum Einsatz digitaler Werkzeuge und 
Verfahren im Gesellschaftsrecht durch das Gesetz zur Umsetzung der Digitalisierungsrichtlinie ([DiRUG](https://www.bmjv.de/SharedDocs/Downloads/DE/Gesetzgebung/BGBl/Bgbl_DiRUG.pdf?__blob=publicationFile&v=3)) vom 5. Juli 2021
ermöglicht wurde. Dadurch kann gemäß [§ 16a (1) BeurkG](https://www.gesetze-im-internet.de/beurkg/__16a.html) 
die Beurkundung von Willenserklärungen mittels des von der Bundesnotarkammer 
nach [§ 78p BNotO](https://www.gesetze-im-internet.de/bnoto/__78p.html) betriebenen Videokommunikationssystems 
erfolgen. Hierbei muss gemäß [§ 16b (1) BeurkG](https://www.gesetze-im-internet.de/beurkg/__16a.html) eine elektronische 
Niederschrift aufgenommen und gemäß [§ 16b (3) BeurkG](https://www.gesetze-im-internet.de/beurkg/__16a.html) mit einer 
qualifizierten elektronischen Signatur versehen werden. 

Gemäß  [§ 16c BeurkG](https://www.gesetze-im-internet.de/beurkg/__16c.html)
"**soll** sich der Notar Gewissheit über die Person der Beteiligten anhand eines ihm elektronisch übermittelten 
Lichtbildes" verschaffen und die Identität der Person mit einem geeigneten elektronischen Identifizierungsmittel bestimmen. 
Hierbei muss das elektronische Identifizierungsmittel auf dem Sicherheitsniveau **"hoch"** im Sinne von [Artikel 8 (2) lit. c)](https://www.eid.as/de/#article8) 
gemäß [Artikel 9 notifiziert](https://www.eid.as/de/#article9) und gemäß [Artikel 6 anerkannt](https://www.eid.as/de/#article6) sein.
"Das dem Notar zu übermittelnde Lichtbild ist mit Zustimmung des betreffenden 
Beteiligten nebst Vornamen, Familienname, Tag der Geburt, ausstellendem Staat, 
Dokumentenart, Gültigkeitsdauer sowie derjenigen Daten, die zur Überprüfung der 
Echtheit des Dokuments erforderlich sind, aus dem elektronischen Speicher- und 
Verarbeitungsmedium eines von der Bundesrepublik Deutschland ausgegebenen Personalausweises, 
Passes oder elektronischen Aufenthaltstitels oder eines amtlichen Ausweises oder Passes 
eines anderen Staates, mit dem die Pass- und Ausweispflicht im Inland erfüllt wird, 
**auszulesen**". Dies ist jedoch praktisch nur bei Personalausweisen, oder technisch 
identisch aufgebauten Unionsbürgerkarten und elektronischen Aufenthaltstiteln,
möglich, die ab dem [2. August 2021 ausgestellt](https://online.notar.de/hilfe-faq/auslesen-des-digitalen-lichtbildes/auslesevorgang-aus-dem-personalausweis) wurden.
Darüber hinaus existieren weitere Herausforderungen bei [Beglaubigungen und Beurkundungen in ausländischen Online Verfahren](https://www.bnotk.de/aufgaben-und-taetigkeiten/rundschreiben/details/beglaubigungen-und-beurkundungen-in-auslaendischen-online-verfahren),
die eine grenzüberschreitende Unternehmensgründung im Europäischen Binnenmarkt erschweren.
  
##### Anmeldung zur Eintragung ins Handelsregister

Gemäß [§ 7 (2) GmbHG](https://www.gesetze-im-internet.de/gmbhg/__7.html) darf die Anmeldung der Gesellschaft beim zuständigen Handelsregister erst erfolgen, nachdem zumindest die Hälfte des 
Mindeststammkapitals auf das Geschäftskonto der Gesellschaft eingezahlt, oder als Sacheinlage bereitgestellt wurde. 
Gemäß [§ 12 (2) HGB](https://www.gesetze-im-internet.de/hgb/__12.html) sind Dokumente zum Handelsregister in 
elektronischer Form einzureichen, was unter Verwendung von XML-basierten `nachricht.reg.0400003` Nachrichten gemäß 
[XJustiz](https://xjustiz.justiz.de/system/pdf/Spezifikation_XJustiz_351_06_03_2025.pdf) (Abschnitt 7, Fachmodul Register (REG)) 
erfolgt, die letztlich im Regelfall über eine notarielle Softwareanwendung, wie z.B. [XNotar](https://onlinehilfe.bnotk.de/einrichtungen/notarnet/xnotar.html) und 
das [besondere elektronische Notarpostfach (beN)](https://onlinehilfe.bnotk.de/einrichtungen/bundesnotarkammer/besonderes-elektronisches-notarpostfach.html), an das zuständige Registergericht übermittelt werden. 
Erwähnenswert erscheint, dass das XML-basierte `nachricht.reg.0400003` Datenformat nach der erfolgten Eintragung einer Gesellschaft ins Handelsregister auch für die Bereitstellung von strukturierten 
Registerinhalten (SI) im [gemeinsamen Registerportal der Länder](https://www.handelsregister.de/) verwendet wird.  

#### Bank

Da die Anmeldung einer Kapitalgesellschaft beim zuständigen Handelsregister erst nach der Einzahlung eines bestimmten 
Teils des Stammkapitals (vgl. [§ 7 (2) GmbHG](https://www.gesetze-im-internet.de/gmbhg/__7.html)) bzw. Grundkapitals
(vgl. [§ 36 (2) AktG](https://www.gesetze-im-internet.de/aktg/__36.html)) erfolgen darf, muss bei der Gründung einer
Kapitalgesellschaft regelmäßig auch ein Geschäftskonto eröffnet werden. Hierfür sind insbesondere die rechtlichen Anforderungen 
aus [§ 11 (4) GWG](https://www.gesetze-im-internet.de/gwg_2017/__11.html) und [§ 12 (2)](https://www.gesetze-im-internet.de/gwg_2017/__12.html)
zu beachten und es müssen gemäß [§ 12 (2) Nr. 2](https://www.gesetze-im-internet.de/gwg_2017/__12.html) regelmäßig 
Gründungsdokumente oder gleichwertig beweiskräftige Dokumente vorgelegt werden, da ja bei der Eröffnung des Geschäftskontos 
die Eintragung ins Handelsregister noch nicht erfolgt sein kann.  

#### Gewerbeordnung (GewO)

##### Gewerbeanzeige gemäß § 14 (1) GewO

Gemäß [§ 14 (1) GewO](https://www.gesetze-im-internet.de/gewo/__14.html) muss der selbständige 
"Betrieb eines stehenden Gewerbes, einer Zweigniederlassung oder einer unselbständigen Zweigstelle" 
bei der zuständigen Behörde angezeigt werden. Die Bestimmung der jeweils zuständigen Behörde ist durch [§ 155 (2) GewO](https://www.gesetze-im-internet.de/gewo/__155.html)
auf die Landesregierungen oder die von ihnen bestimmten Stellen übertragen.
Eine Gewerbeanzeige ist auch notwendig, wenn der Betrieb verlegt wird,
der Gegenstand des Gewerbes gewechselt oder auf Waren oder Leistungen ausgedehnt wird,
die bei Gewerbebetrieben der angemeldeten Art nicht geschäftsüblich sind, der Name des
Gewerbetreibenden geändert wird oder der Betrieb aufgegeben wird. 

##### Gewerbeanzeigeverordnung (GewAnzV) gemäß § 14 (14) GewO

Die auf der Grundlage von [§ 14 (14) GewO](https://www.gesetze-im-internet.de/gewo/__14.html) geschaffene
[Gewerbeanzeigeverordnung (GewAnzV)](https://www.gesetze-im-internet.de/gewanzv_2014/)
regelt weitere Details der Gewerbeanzeige gemäß [§ 14 (1) GewO](https://www.gesetze-im-internet.de/gewo/__14.html) und
der Datenübermittlung an die weiteren zuständigen Stellen gemäß [§ 14 (8) GewO](https://www.gesetze-im-internet.de/gewo/__14.html).
Beispielsweise finden sich in den Anlagen 1-3 der [GewAnzV](https://www.gesetze-im-internet.de/gewanzv_2014/)
bildlich definierte Musterformulare zur Gewerbe-Anmeldung, -Ummeldung und -Abmeldung und
[§ 3 (4) GewAnzV](https://www.gesetze-im-internet.de/gewanzv_2014/__3.html) legt fest, dass
für die Datenübermittlung an die weiteren zuständigen Stellen gemäß [§ 14 (8) GewO](https://www.gesetze-im-internet.de/gewo/__14.html)
der vom Bundesministerium für Wirtschaft im Bundesanzeiger bekannt gemachte Standard samt der vom IT-Planungsrat
beschlossenen IT-Interoperabilitäts- und IT-Sicherheitsstandards zu verwenden ist. Mit der formalen Bekanntmachung
[BAnz AT 25.08.2025 B1](https://www.bundesanzeiger.de/pub/publication/4HXS0iZfbIDPSh9VYMM/content/4HXS0iZfbIDPSh9VYMM/BAnz%20AT%2025.08.2025%20B1.pdf?inline)
des Standards [XGewerbeordnung](https://xgewerbeordnung.de/) durch das Bundesministerium für Wirtschaft und Energie im [Bundesanzeiger](https://www.bundesanzeiger.de/)
wurde klargestellt, dass ab dem 01.05.2026 die [Version 1.6](https://www.xrepository.de/details/urn:xoev-de:kosit:standard:xgewerbeordnung_1.6#version)
des Standards XGewerbeordnung anzuwenden ist. Organisatorische Details und rechtliche Auslegungsfragen zur Umsetzung der [GewAnzVwV](https://www.gesetze-im-internet.de/gewanzv_2014/) sind auch im zuletzt am 18. Juli 2025 geänderten Musterentwurf der
[12. Allgemeine Verwaltungsvorschrift zur Durchführung der §§ 14, 15 und 55c der Gewerbeordnung (GewAnzVwV)](https://xgewerbeordnung.de/wp-content/uploads/2025/07/250730_GewAnzVwV.final_.pdf)
beschrieben. Der Standard [XGewerbeordnung (Version 1.6)](https://www.xrepository.de/details/urn:xoev-de:kosit:standard:xgewerbeordnung_1.6#version) baut auf dem
[Kerndatenmodell](https://www.xrepository.de/api/xrepository/urn:xoev-de:xunternehmen:standard:basismodul_1.1:dokument:XUnternehmen.Kerndatenmodell__semantisches_Datenmodell_) und dem
[Basismodul](https://www.xrepository.de/api/xrepository/urn:xoev-de:xunternehmen:standard:basismodul_1.1:dokument:XUnternehmen.Basismodul__X_V-Standard_) des Standards
[XUnternehmen](https://xunternehmen.de/) auf, der jedoch unabhängig von [XJustiz](https://xjustiz.justiz.de/system/pdf/Spezifikation_XJustiz_351_06_03_2025.pdf) ist.   
Erwähnenswert erscheint, dass im "Regelungsbedarf 30" (siehe Seite 41) des [G24h-Detailkonzeptes](https://publuu.com/flip-book/1078574/2404413) 
empfohlen wird, [§ 14 (8) GewO](https://www.gesetze-im-internet.de/gewo/__14.html) zu streichen und die dort bislang genannten Stellen
in die Liste der empfangsberechtigten Stellen des [Basisregisters für Unternehmen](https://www.destatis.de/Verwaltungsregister/DE/Basisregister/_inhalt.html) gemäß
[§ 5 UBRegG](https://www.gesetze-im-internet.de/ubregg/__5.html) aufzunehmen.

##### Datenübermittlung an weitere Stellen gemäß § 14 (8) GewO

Gemäß [§ 14 (8) GewO](https://www.gesetze-im-internet.de/gewo/__14.html) übermittelt die zuständige Behörde 
regelmäßig die Daten aus der Gewerbeanzeige an 
1. die Industrie- und Handelskammer,
2. die Handwerkskammer, 
3. die für den Immissionsschutz zuständige Landesbehörden (d.h. in Bayern 
das entsprechende Landratsamt), 
4. die nach Landesrecht zuständige Behörde zur Wahrnehmung der Aufgaben bzgl. des Mess- und Eichgesetzes, 
5. die Bundesagentur für Arbeit, 
6. die Deutsche Gesetzliche Unfallversicherung e. V., 
7. die Behörden der Zollverwaltung zur Wahrnehmung der ihnen nach dem Schwarzarbeitsbekämpfungsgesetz sowie nach dem Arbeitnehmerüberlassungsgesetz 
obliegenden Aufgaben, 
8. das Registergericht, soweit es sich um die Abmeldung einer im Handels- und Genossenschaftsregister eingetragenen Haupt- oder Zweigniederlassung handelt,
9. die statistischen Ämter der Länder zur Führung des Statistikregisters, 
10. die nach Landesrecht zuständigen Behörden zur Wahrnehmung ihrer Aufgaben nach dem 
Lebensmittel-, Bedarfsgegenstände-, Futtermittel-, Tabak-, Tiergesundheits- und Tierschutzrecht, 
11. die Deutsche Rentenversicherung Knappschaft-Bahn-See zum Einzug und zur Vollstreckung 
der einheitlichen Pauschsteuer nach [§ 40a (2) EStG](https://www.gesetze-im-internet.de/estg/__40.html),
12. die Ausländerbehörden zur Wahrnehmung ihrer Aufgaben nach dem Aufenthaltsgesetz, 
13. die nach [§ 22 AO](https://www.gesetze-im-internet.de/ao_1977/__22.html) und 
[§ 138 AO](https://www.gesetze-im-internet.de/ao_1977/__138.html) zuständigen Finanzämter und schließlich 
14. die für die Erlaubnisverfahren gemäß [§ 29 ff GewO](https://www.gesetze-im-internet.de/gewo/__29.html) zuständigen Behörden.

##### Genehmigungspflichtige Gewerbe gemäß § 29 ff GewO 

Die vollständige Erfassung aller [genehmigungspflichtigen Gewerbe](https://www.ihk-nuernberg.de/ihr-unternehmen/rechtsinformationen-fuer-unternehmen/gewerberecht-/-handwerksrecht/genehmigungspflichtige-gewerbe-von-a-z)
ist keine triviale Aufgabe. Zu den in der Praxis möglicherweise wichtigsten 
[erlaubnispflichtigen Gewerben](https://www.ihk.de/bodensee-oberschwaben/recht/gesetzliche-vorgaben-fuers-gewerb-/gewerbeanzeige-und-erlaubnis/erlaubnispflichtige-gewerbe-uebersicht-1942554) 
zählen in alphabetischer Reihenfolge

* Apothekenbetrieb gemäß [ApoG](https://www.gesetze-im-internet.de/apog/)
* Arbeitnehmerüberlassung gemäß [AÜG](https://www.gesetze-im-internet.de/a_g/)
* Bank- und Finanzdienstleistungsgeschäfte gemäß [KWG](https://www.gesetze-im-internet.de/kredwg)
* Bauträger/Baubetreuer gemäß [§ 34c GewO](https://www.gesetze-im-internet.de/gewo/__34c.html)
* Bewachungsgewerbe gemäß [§ 34a GewO](https://dejure.org/gesetze/GewO/34a.html)
* Einzelhandel, sofern z.B. mit Hackfleisch, Arzneimitteln, Wirbeltieren, Schusswaffen und Munition gehandelt wird.
* Finanzanlagenvermittler gemäß [§ 34f (1) GewO](https://www.gesetze-im-internet.de/gewo/__34f.html)
* Gaststättengewerbe/Hotelgewerbe gemäß [GastG](https://www.gesetze-im-internet.de/gastg/) 
* Großhandel, sofern z.B. mit Chemikalien, Arzneimitteln oder Sprengstoff gehandelt wird.
* Güterbeförderung gemäß [GüKG](https://www.gesetze-im-internet.de/g_kg_1998)
* Handwerk gemäß [HwO](https://www.gesetze-im-internet.de/hwo/)
* Honorar-Finanzanlageberater gemäß [§ 34h GewO](https://www.gesetze-im-internet.de/gewo/__34h.html) 
* Immobiliardarlehensvermittler gemäß [§ 34i (1) GewO](https://www.gesetze-im-internet.de/gewo/__34i.html).
* Inkasso-Unternehmen gemäß [RDG](https://www.gesetze-im-internet.de/rdg/)
* Krankenanstalten gemäß [§ 30 GewO](https://www.gesetze-im-internet.de/gewo/__30.html)
* Maklergewerbe gemäß [§ 34c GewO](https://www.gesetze-im-internet.de/gewo/__34c.html)
* Personenbeförderung gemäß [PBefG](https://www.gesetze-im-internet.de/pbefg)
* Reisegewerbe gemäß [§ 55a GewO](https://www.gesetze-im-internet.de/gewo/__55a.html) 
* Sachverständigentätigkeit gemäß [§ 36 GewO](https://www.gesetze-im-internet.de/gewo/__36.html)
* Schaustellung von Personen gemäß [§ 33a GewO](https://www.gesetze-im-internet.de/gewo/__33a.html)
* Spielgeräte und Spielhallen gemäß [§ 33c GewO](https://www.gesetze-im-internet.de/gewo/__33c.html)
* Versteigerergewerbe gemäß [§ 34b GewO](https://www.gesetze-im-internet.de/gewo/__34b.html)
* Versicherungsberater gemäß [§ 34e GewO](https://www.gesetze-im-internet.de/gewo/__34e.html)
* Versicherungsvermittler gemäß [§ 34d (1) GewO](https://www.gesetze-im-internet.de/gewo/__34d.html)
* Wohnimmobilienverwalter gemäß [§ 34c GewO](https://www.gesetze-im-internet.de/gewo/__34c.html)

#### ELSTER

Die Daten der Gewerbeanzeige werden gemäß [§ 14 (8) Nr. 13 GewO](https://www.gesetze-im-internet.de/gewo/__14.html) 
an das gemäß [§ 22 AO](https://www.gesetze-im-internet.de/ao_1977/__22.html) zuständige Finanzamt übermittelt. Diese 
Datenübermittlung ersetzt jedoch nicht die gemäß [§ 138 (1b) AO](https://www.gesetze-im-internet.de/ao_1977/__138.html) 
notwendige Erteilung von Auskünften "über die für die Besteuerung erheblichen rechtlichen und tatsächlichen Verhältnisse", 
die "nach amtlich vorgeschriebenem Datensatz über die amtlich bestimmte Schnittstelle zu übermitteln" sind. Diese 
Erteilung von Auskünften erfolgt über den im [ELSTER](https://www.elster.de/)-Portal zugreifbaren 
[Fragebogen zur steuerlichen Erfassung](https://www.elster.de/eportal/formulare-leistungen/alleformulare), der in 
verschiedenen Varianten für gegründete Einzelunternehmen, Kapitalgesellschaften oder Genossenschaften, 
Personengesellschaften / -gemeinschaften, Vereine oder einer anderen Körperschaften des privaten Rechts und 
Körperschaften nach ausländischem Recht existiert. Die hierbei manuell im Portal oder programmatisch über die 
[ELSTER Rich Client (ERiC)](https://www.elster.de/elsterweb/infoseite/entwickler)-Programmierschnittstelle 
erfassten Daten für Kapitalgesellschaften sind in weiten Teilen mit den bei der Eintragung ins 
Handelsregister anfallenden Stammdaten gemäß [XJustiz](https://xjustiz.justiz.de/system/pdf/Spezifikation_XJustiz_351_06_03_2025.pdf) und der Gewerbeanzeige gemäß [XGewerbeordnung](https://www.xrepository.de/details/urn:xoev-de:kosit:standard:xgewerbeordnung_1.6#version) 
auf Basis von [XUnternehmen](https://xunternehmen.de/) identisch.

Nach der Bearbeitung des Fragebogens im zuständigen Finanzamt wird beim [Bundeszentralamt für Steuern (BZSt)](https://www.bzst.de/)
die Erteilung der [Wirtschafts-Identifikationsnummer (W-IdNr.)](https://www.bzst.de/DE/Unternehmen/Identifikationsnummern/Wirtschafts-Identifikationsnummer/wirtschaftsidentifikationsnummer_node.html) 
gemäß [§ 139c AO](https://www.gesetze-im-internet.de/ao_1977/__139c.html) und, sofern dies im Fragebogen angefragt wurde, 
auch die für den umsatzsteuerfreien innergemeinschaftlichen Erwerb von Gütern oder Leistungen notwendige [Umsatzsteuer-Identifikationsnummer (USt-IdNr.)](https://www.bzst.de/DE/Unternehmen/Identifikationsnummern/Umsatzsteuer-Identifikationsnummer/umsatzsteuer-identifikationsnummer_node.html) 
gemäß [§ 27a UStG](https://www.gesetze-im-internet.de/ustg_1980/__27a.html) für das neu gegründete Unternehmen angestoßen. Sobald 
die angefragten Identifikationsnummern erteilt wurden, kann das neu gegründete Unternehmen Rechnungen gemäß
[§ 14 UStG](https://www.gesetze-im-internet.de/ustg_1980/__14.html) stellen.

#### Deutsche Gesetzliche Unfallversicherung e.V. (DGUV)

Gemäß [§ 14 (6) Nr. 8 GewO](https://www.gesetze-im-internet.de/gewo/__14.html) werden die Daten der
Gewerbeanmeldung an die [Deutsche Gesetzliche Unfallversicherung e.V.](https://www.dguv.de/) gesendet. Dies
erfolgt "ausschließlich zur Weiterleitung an die zuständige [Berufsgenossenschaft](https://www.dguv.de/de/bg-uk-lv/bgen/index.jsp) für die Erfüllung der 
ihr durch Gesetz übertragenen Aufgaben".

[§ 136a (1) SGB VII](https://www.gesetze-im-internet.de/sgb_7/__136a.html) ist folgendermaßen gefasst: "Jeder Unternehmer erhält bei erstmaliger Aufnahme einer unternehmerischen 
Tätigkeit eine Unternehme**r**nummer. Die Unternehme**r**nummer wird nach Mitteilung über den Unternehmensbeginn im Sinne von
[§ 192 Absatz 1](https://www.gesetze-im-internet.de/sgb_7/__192.html) über die [Deutsche Gesetzliche Unfallversicherung e. V.](https://dguv.de/) unverzüglich vergeben. 
Die Unternehmer, die bereits eine Unternehme**r**nummer erhalten haben, teilen den Beginn und das Ende eines oder mehrerer 
weiterer Unternehmen nach [§ 192 Absatz 1](https://www.gesetze-im-internet.de/sgb_7/__192.html) unter Angabe der Unternehme**r**nummer und der notwendigen Angaben zur 
Identifizierung des Unternehmens dem zuständigen Träger der Unfallversicherung mit. In einem Anhang zu der Unternehme**r**nummer 
werden die dem Unternehmer zugehörigen Unternehmen numerisch in aufsteigender Folge bezeichnet. Die Unternehme**r**nummer 
und die zur Identifizierung des Unternehmens erforderlichen Daten, einschließlich aller 
dem Unternehmen zuzuordnenden Betriebsnummern, werden in einem zentralen Dateisystem bei der 
Deutschen Gesetzlichen Unfallversicherung e. V. gespeichert. Die Berufsgenossenschaften und Unfallversicherungsträger 
der öffentlichen Hand haben zur Erledigung ihrer gesetzlichen Aufgaben Zugriff auf dieses Dateisystem; 
dies gilt auch für die Arbeitsschutzbehörden der Länder, soweit dies für die Erfüllung ihrer gesetzlichen Aufgaben 
erforderlich ist. Die Berufsgenossenschaften und die Unfallversicherungsträger der öffentlichen Hand führen 
die Unternehmer- und Unternehmensnummern ihrer Mitglieder jeweils in einem gesonderten Mitgliederdateisystem."

Gemäß [§ 192 Absatz 1](https://www.gesetze-im-internet.de/sgb_7/__192.html)  sind die Unternehmer verpflichtet, "binnen einer Woche nach Beginn des Unternehmens dem zuständigen Unfallversicherungsträger 1. die Art und den Gegenstand des Unternehmens, 2. die Zahl der Versicherten, 3. den Eröffnungstag oder den Tag der Aufnahme der vorbereitenden Arbeiten für das Unternehmen und 4. in den Fällen des § 130 Abs. 2 und 3 den Namen und den Wohnsitz oder gewöhnlichen Aufenthalt des Bevollmächtigten mitzuteilen. Die Mitteilungspflicht gilt als erfüllt, wenn eine Anzeige nach den §§ 14, 55c der Gewerbeordnung binnen einer Woche nach Beginn des Unternehmens gegenüber der zuständigen Stelle erstattet wurde."

Das in [§ 136a (1) SGB VII](https://www.gesetze-im-internet.de/sgb_7/__136a.html) genannte "Dateisystem" ist das so genannte "[Zentrale Unternehmerverzeichnis](https://www.verwaltungsdaten-informationsplattform.de/register/79#TechnischeInformationen)"
und die dort genannte "Betriebsnummer" wird inzwischen beim DGUV e.V. als [Unternehmen**s**nummer (UNR.**S**)](https://www.dguv.de/de/versicherung/unternehmensnummer/index.jsp) bezeichnet. 
Die Unternehme**r**nummer (UNR) besteht aus 12 Ziffern. Der im Gesetz genannte "Anhang zu der Unternehme**r**nummer" ist ein 
Unternehmenskennzeichen, das aus drei Ziffern besteht. Die UNR und das Unternehmenskennzeichen bilden die Unternehmen**s**nummer
UNR.**S**, die also insgesamt 15-stellig ist und die Einträge der Unternehmer mit ihren Unternehmen verbindet. Weitere Details sind in den vom [Bundesministerium für Arbeit und Soziales](https://www.bmas.de/)
genehmigten [Grundsätzen zum Betrieb des Zentralen Unternehmerverzeichnisses der gesetzlichen Unfallversicherung nach § 136a SGB VII](https://www.dguv.de/medien/inhalt/versicherung/unternehmensnummer/grundsaetze_nach_136a_20260401_textteil.pdf) geregelt.

#### Bundesagentur für Arbeit (BA)

Seit Beginn des Jahres 2024 wird die dem Unternehmen beim DGUV e.V. zugeordnete Unternehmen**s**nummer (UNR.**S**) auch
zur [Beantragung einer Betriebsnummer](https://www.arbeitsagentur.de/unternehmen/betriebsnummern-service) gemäß [§ 18i SGB IV](https://www.gesetze-im-internet.de/sgb_4/__18i.html)
bei der [Bundesagentur für Arbeit (BA)](https://www.arbeitsagentur.de/) benötigt, sofern dies [erforderlich](https://www.arbeitsagentur.de/datei/dok_ba031865.pdf) ist.
Dies ist regelmäßig dann der Fall, wenn im neu gegründeten Unternehmen Mitarbeiterinnen oder Mitarbeiter angestellt sind, 
die nicht nur geringfügig beschäftigt sind und eine [Meldung zur Sozialversicherung](https://www.arbeitsagentur.de/unternehmen/betriebsnummern-service/meldeverfahren-sozialversicherung) gemäß [§ 28a SGB IV](https://www.gesetze-im-internet.de/sgb_4/__28a.html) und 
[DEÜV](https://www.gesetze-im-internet.de/de_v) erfolgen muss.
Während die [Beantragung](https://web.arbeitsagentur.de/bno-prod/ui/antrag/hinweise#/start) der Betriebsnummer gemäß [§ 18i (1) SGB IV](https://www.gesetze-im-internet.de/sgb_4/__18i.html) online erfolgen muss und auch die Vergabe und Speicherung der Betriebsnummer bei der BA elektronisch erfolgt, wird die erteilte Betriebsnummer dem Unternehmen 
nach der [Antragstellung](https://www.arbeitsagentur.de/unternehmen/betriebsnummern-service/alles-wichtige) vom "Betriebsnummern-Service aus [Datenschutzgründen](https://www.arbeitsagentur.de/unternehmen/betriebsnummern-service/alles-wichtige/datenschutz-betriebsnummern-vergabe) nur per Post" mitgeteilt. 

#### Weitere Mehrwertdienste für Gründerinnen und Gründer im G24-Marktplatz

Neben den oben betrachteten Institutionen und Diensten, die häufig relevant für die Gründung von Unternehmen
in unterschiedlichen Rechtsformen sind, existieren vielfältige weitere Mehrwertdienste für Gründerinnen und 
Gründer, welche die erfolgreiche Gründung und Skalierung von Unternehmen nachhaltig unterstützen können. 
Diese von privaten Unternehmen und öffentlichen Stellen angebotenen Mehrwertdienste können über den G24-Marktplatz angeboten und bezogen werden können. 
Ein potenziell denkbares Beispiel für einen von einer öffentlichen Stelle angebotenen Mehrwertdienst
ist die serviceorientierte Beantragung der [Gläubiger-Identifikationsnummer](https://www.bundesbank.de/de/aufgaben/unbarer-zahlungsverkehr/serviceangebot/sepa/glaeubiger-identifikationsnummer) 
bei der [Deutschen Bundesbank](https://www.bundesbank.de/de), die für Verwaltung von [SEPA-Mandaten](https://www.bundesbank.de/dynamic/action/de/aufgaben/unbarer-zahlungsverkehr/serviceangebot/sepa/613964/fragen-und-antworten-zu-sepa) beim Lastschrifteinzug 
benötigt wird.

### Basisdienste 

Der Vollständigkeit halber seien hier beispielhafte Basisdienste aus dem [Deutschland-Stack](https://www.it-planungsrat.de/beschluss/b-2026-03-it) erwähnt, 
die in der Gründungsplattform und perspektivisch auch in den Gründungsrelevanten Diensten genutzt 
werden können. Dies umfasst beispielsweise die digitale / elektronische Identität (deID) als Sammelbegriff 
für die [BundID](https://id.bund.de/), die [BayernID](https://id.bayernportal.de/de) und weitere Identitäten 
aus anderen fachlich relevanten Sektoren, die Justiz-Register, die über das gemeinsame 
[Registerportal der Länder](https://www.handelsregister.de/) zugreifbar sind und perspektivisch 
auch das [Nationale Once-Only-Technical System (NOOTS)](https://noots.gov.de/startseite) für den Abruf 
von für die Gründung relevanten Nachweisen.

### Europäische Dienste

Schließlich ist es für den nachhaltigen Erfolg des G24-Systems sehr wichtig auch die hierfür relevanten existierenden und 
absehbar entstehenden einschlägigen Europäischen Regularien zu berücksichtigen und soweit sinnvoll die entsprechenden
Dienste zu integrieren. Dies umfasst die heute bereits existierenden [eID](https://eidas.ec.europa.eu/efda/browse/notification/eid-chapter-contacts) und [Vertrauensdienste](https://www.eid.as/tsp-map/#/) gemäß der [eIDAS](https://www.eid.as/de/)-Verordnung, 
die bereits sehr konkret absehbaren Entwicklungen im Umfeld der [EUDI-Wallet](https://ec.europa.eu/digital-building-blocks/sites/spaces/EUDIGITALIDENTITYWALLET/pages/694487738/EU+Digital+Identity+Wallet+Home), 
die bereits existierenden Systeme der EU-weiten Justizkommunikation, 
wie z.B. [e-CODEX](https://www.eulisa.europa.eu/activities/large-scale-it-systems/e-codex), 
[BRIS](https://ec.europa.eu/digital-building-blocks/sites/spaces/DIGITAL/blog/2017/09/19/533365899/Business+Register+Interconnection+System+BRIS) und 
[BORIS](https://e-justice.europa.eu/topics/registers-business-insolvency-land/beneficial-ownership-registers-interconnection-system-boris_en), 
Systeme zur [Zollabwicklung](https://www.zoll.de/DE/Unternehmen/unternehmen_node.html), potenziell relevante sektorspezifische Entwicklungen, z.B. für 
neu gegründete innovative Unternehmen im Bereich des Gesundheitswesen insbesondere der [European Health Data Space (EHDS)](https://ehds.io/) 
und nicht zuletzt die wahrscheinlichen Entwicklungen im 28. Regime zur Gründung einer [EU Inc.](https://commission.europa.eu/topics/business-and-industry/doing-business-eu/company-law-and-corporate-governance/eu-inc-new-harmonised-corporate-legal-regime_en). 

## Kontakt

Sie haben Anmerkungen, Verbesserungsvorschläge oder Anregungen zur konzeptionellen und operativen 
Weiterentwicklung und raschen Umsetzung des G24-Systems? Das ist großartig! 

Nehmen Sie gerne mit uns Kontakt auf, indem Sie entweder 
* hier ein Ticket eröffnen, 
* uns unter https://it-umsetzungsrat.de bzw. https://go.eID.AS besuchen oder 
* uns einfach eine E-Mail an [g24h@eID.AS](mailto:g24h@eID.AS) senden.

Wir freuen uns bereits jetzt auf den Austausch mit Ihnen!
