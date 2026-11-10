# Awesome Pix

> Pix für Entwickler: Regelwerk, APIs, SDKs, Anbieter und Werkzeuge, jeweils einzeln geprüft.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-abonnieren-111111?style=flat-square)](https://go.mymarketing.click/pix-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/pix-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/de.xml) ![56 Einträge](https://img.shields.io/badge/Eintr%C3%A4ge-56-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-6b6b6b?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

Für alle, die Pix in einem System abrechnen, empfangen oder abstimmen. Beginnt mit den Veröffentlichungen der Banco Central, führt über Anbieter mit API und endet bei quelloffenen Bibliotheken, die den QR Code erzeugen und lesen. Jede Adresse wurde vor der Aufnahme geprüft.

## Inhalt

- [Regelwerk und offizielle Dokumentation](#regelwerk-und-offizielle-dokumentation)
- [Spezifikationen und offene APIs](#spezifikationen-und-offene-apis)
- [Anbieter mit Pix-API](#anbieter-mit-pix-api)
- [Offizielle SDKs der Anbieter](#offizielle-sdks-der-anbieter)
- [Open-Source-Bibliotheken](#open-source-bibliotheken)
- [Community-SDKs](#community-sdks)
- [Daten und Hilfsprogramme](#daten-und-hilfsprogramme)
- [Werkzeuge](#werkzeuge)
- [Andere Listen und Communitys](#andere-listen-und-communitys)
- [Tags](#tags)
- [So beteiligst du dich](#so-beteiligst-du-dich)
- [Weitere Listen](#weitere-listen)
- [Von Ciro Cesar Maciel erstellt](#von-ciro-cesar-maciel-erstellt)
- [Lizenz](#lizenz)

## Regelwerk und offizielle Dokumentation

Was von der Banco Central kommt, die Pix festlegt.

- [Pix no Banco Central](https://go.mymarketing.click/pix-pix-no-banco-central) - Die offizielle Pix-Seite mit Erklärung, Funktionsweise und Links zum Rest. `offiziell` `kostenlos`
- [Normas do Pix](https://go.mymarketing.click/pix-normas-do-pix) - Die Verordnung, die Regelungen und die Handbücher zu Pix. `offiziell` `kostenlos`
- [Pix Automático](https://go.mymarketing.click/pix-pix-automatico) - Die Variante für wiederkehrende Abbuchungen, die der Zahler einmal genehmigt. `offiziell` `kostenlos`
- [Participantes do Pix](https://go.mymarketing.click/pix-participantes-do-pix) - Die Liste der Institute, die Pix anbieten, und in welcher Variante. `offiziell` `kostenlos`
- [Estatísticas do Pix](https://go.mymarketing.click/pix-estatisticas-do-pix) - Die offiziellen Zahlen zu Transaktionen, Beträgen und Schlüsseln. `offiziell` `kostenlos`
- [Perguntas frequentes do Pix](https://go.mymarketing.click/pix-perguntas-frequentes-do-pix) - Antworten der Banco Central auf die häufigsten Fragen zu Pix. `offiziell` `kostenlos`

## Spezifikationen und offene APIs

Die API-Verträge, die die Banco Central auf GitHub veröffentlicht.

- [API Pix](https://go.mymarketing.click/pix-api-pix) - Die OpenAPI-Spezifikation der Pix-API, die Anbieter für Zahlungsanforderungen und Zahlungseingang implementieren. `offiziell` `Open Source` `API`
- [API do DICT](https://go.mymarketing.click/pix-api-do-dict) - Die Spezifikation der API des Verzeichnisses für Transaktionskontenkennungen DICT, in dem die Pix-Schlüssel gespeichert sind. `offiziell` `Open Source` `API`
- [DICT Quickstart](https://go.mymarketing.click/pix-dict-quickstart) - Ein Einstiegsleitfaden zur DICT-API. `offiziell` `Open Source`

## Anbieter mit Pix-API

Banken, Zahlungsinstitute und Plattformen mit öffentlicher Dokumentation zur Pix-Integration.

- [Adyen](https://go.mymarketing.click/pix-adyen) - Pix als Zahlungsmethode auf der globalen Plattform von Adyen. `API` `kostenpflichtig`
- [Asaas](https://go.mymarketing.click/pix-asaas) - Dokumentation der Asaas-API mit Zahlungen per Pix, Boleto und Karte. `API` `kostenpflichtig`
- [Banco do Brasil](https://go.mymarketing.click/pix-banco-do-brasil) - Das Entwicklerportal der Banco do Brasil mit der Pix-API. `API`
- [Banco Inter](https://go.mymarketing.click/pix-banco-inter) - Das Entwicklerportal von Inter mit APIs für Pix und Zahlungsanforderungen. `API`
- [Bradesco](https://go.mymarketing.click/pix-bradesco) - Das Entwicklerportal von Bradesco mit Pix-APIs. `API`
- [Celcoin](https://go.mymarketing.click/pix-celcoin) - Zahlungsinfrastruktur mit Pix-APIs für Unternehmen, die Finanzprodukte entwickeln. `API` `kostenpflichtig`
- [Cora](https://go.mymarketing.click/pix-cora) - Die APIs von Cora für Zahlungsanforderungen und Pix auf dem Geschäftskonto. `API`
- [dLocal](https://go.mymarketing.click/pix-dlocal) - Zahlungen in Schwellenmärkten, mit Pix unter den akzeptierten Methoden in Brasilien. `API` `kostenpflichtig`
- [EBANX](https://go.mymarketing.click/pix-ebanx) - Lokale Zahlungen in Lateinamerika, mit Pix für Unternehmen aus dem In- und Ausland. `API` `kostenpflichtig`
- [Efí](https://go.mymarketing.click/pix-efi) - Die Dokumentation der Pix-API von Efí, früher Gerencianet, mit Zahlungsanforderung, Webhook und Pix Automático. `API` `kostenpflichtig`
- [Itaú](https://go.mymarketing.click/pix-itau) - Das Entwicklerportal von Itaú mit Pix-APIs. `API`
- [Iugu](https://go.mymarketing.click/pix-iugu) - Dokumentation der Iugu-API mit Zahlungsanforderungen und Abos, die Pix akzeptieren. `API` `kostenpflichtig`
- [Mercado Pago](https://go.mymarketing.click/pix-mercado-pago) - So nimmst du Pix über die Checkout API von Mercado Pago entgegen, mit QR Code und copia e cola. `API` `kostenpflichtig`
- [OpenPix](https://go.mymarketing.click/pix-openpix) - Die Dokumentation zu OpenPix, einer Plattform für Pix-Zahlungsanforderungen mit API, Webhooks und Plugins. `API` `kostenpflichtig`
- [PagBank](https://go.mymarketing.click/pix-pagbank) - Das Entwicklerportal von PagBank mit Bestellungen und Pix-Zahlungsanforderungen. `API` `kostenpflichtig`
- [Pagar.me](https://go.mymarketing.click/pix-pagar-me) - Dokumentation der Pagar.me-API mit Zahlungen per Pix, Karte und Boleto. `API` `kostenpflichtig`
- [Santander](https://go.mymarketing.click/pix-santander) - Das Entwicklerportal von Santander mit Pix-APIs. `API`
- [Sicredi](https://go.mymarketing.click/pix-sicredi) - Das Entwicklerportal von Sicredi mit Pix-APIs und Zahlungsanforderungen. `API`
- [Stripe](https://go.mymarketing.click/pix-stripe) - Pix als Zahlungsmethode bei Stripe, für alle, die dort schon abrechnen. `API` `kostenpflichtig`
- [Transfeera](https://go.mymarketing.click/pix-transfeera) - APIs für Zahlungen und Zahlungseingang per Pix, mit Abstimmung. `API` `kostenpflichtig`
- [Woovi](https://go.mymarketing.click/pix-woovi) - Die Dokumentation zu Woovi mit Zahlungsanforderungen, Abos und Webhooks für Pix. `API` `kostenpflichtig`

## Offizielle SDKs der Anbieter

Gepflegt von denen, die die API anbieten.

- [Efí SDK Node.js](https://go.mymarketing.click/pix-efi-sdk-node-js) - SDK für Node.js zu den APIs von Efí, mit Pix-Zahlungsanforderungen per QR Code und copia e cola. `Open Source` `SDK`
- [Efí SDK PHP](https://go.mymarketing.click/pix-efi-sdk-php) - SDK für PHP zu den APIs von Efí, mit Pix-Zahlungsanforderungen per QR Code und copia e cola. `Open Source` `SDK`
- [Gerencianet SDK Python](https://go.mymarketing.click/pix-gerencianet-sdk-python) - SDK für Python zur API von Efí, veröffentlicht unter dem alten Namen Gerencianet. `Open Source` `SDK`
- [Mercado Pago SDK .NET](https://go.mymarketing.click/pix-mercado-pago-sdk-net) - Das offizielle SDK von Mercado Pago für .NET. `Open Source` `SDK`
- [Mercado Pago SDK Java](https://go.mymarketing.click/pix-mercado-pago-sdk-java) - Das offizielle SDK von Mercado Pago für Java. `Open Source` `SDK`
- [Mercado Pago SDK Node.js](https://go.mymarketing.click/pix-mercado-pago-sdk-node-js) - Das offizielle SDK von Mercado Pago für Node.js. `Open Source` `SDK`
- [Mercado Pago SDK PHP](https://go.mymarketing.click/pix-mercado-pago-sdk-php) - Das offizielle SDK von Mercado Pago für PHP. `Open Source` `SDK`
- [Mercado Pago SDK Python](https://go.mymarketing.click/pix-mercado-pago-sdk-python) - Das offizielle SDK von Mercado Pago für Python. `Open Source` `SDK`
- [OpenPix Developers](https://go.mymarketing.click/pix-openpix-developers) - Der Code der OpenPix-Dokumentation mit Integrationsbeispielen. `Open Source`
- [Woovi Developers](https://go.mymarketing.click/pix-woovi-developers) - Der Code der Woovi-Dokumentation mit Integrationsbeispielen. `Open Source`

## Open-Source-Bibliotheken

Zum Erzeugen, Lesen und Validieren von BR Code (dem Inhalt des QR Codes und von copia e cola) ohne Abhängigkeit von einem Anbieter.

- [brcode](https://go.mymarketing.click/pix-brcode) - BR-Code-Leser für Pix in Rust. `Open Source` `kostenlos`
- [emv-qrcode](https://go.mymarketing.click/pix-emv-qrcode) - Generator und Leser für QR Codes im EMV-Standard in Java, dem Standard, dem BR Code folgt. `Open Source` `kostenlos`
- [go-pix](https://go.mymarketing.click/pix-go-pix) - Bibliothek in Go zum Erzeugen von Pix copia e cola und QR Code. `Open Source` `kostenlos`
- [php_qrcode_pix](https://go.mymarketing.click/pix-php-qrcode-pix) - Erzeugung des Pix-QR-Codes in PHP. `Open Source` `kostenlos`
- [PHPay](https://go.mymarketing.click/pix-phpay) - PHP-Bibliothek zur Anbindung mehrerer Zahlungsanbieter über dieselbe Schnittstelle. `Open Source` `kostenlos`
- [pix-payload](https://go.mymarketing.click/pix-pix-payload) - npm-Paket, das den Pix-Payload nach dem Standard der Banco Central erzeugt. `Open Source` `kostenlos`
- [pix-utils](https://go.mymarketing.click/pix-pix-utils) - Werkzeuge in TypeScript zum Lesen, Erzeugen und Validieren von Pix-Codes. `Open Source` `kostenlos`
- [PIX-BACEN-SDK-dotnet](https://go.mymarketing.click/pix-pix-bacen-sdk-dotnet) - Die Verträge der Pix-API der Banco Central in .NET, aus der offiziellen Spezifikation generiert. `Open Source` `kostenlos`
- [pypix](https://go.mymarketing.click/pix-pypix) - Bibliothek in Python zum Erzeugen von BR Code und Pix-QR-Code. `Open Source` `kostenlos`

## Community-SDKs

Von Nutzern der API entwickelt, nicht vom Anbieter.

- [asaas (TypeScript)](https://go.mymarketing.click/pix-asaas-typescript) - SDK in TypeScript, das die meistgenutzten Aufrufe der Asaas-API abstrahiert. `Open Source` `kostenlos`
- [asaas-sdk (PHP)](https://go.mymarketing.click/pix-asaas-sdk-php) - SDK in PHP für die Asaas-API. `Open Source` `kostenlos`

## Daten und Hilfsprogramme

Hilft beim Validieren und Abgleichen.

- [Bancos Brasileiros](https://go.mymarketing.click/pix-bancos-brasileiros) - Liste der brasilianischen Banken mit Code, ISPB und Name in mehreren Formaten. `Open Source` `kostenlos`

## Werkzeuge

Für alle, die ohne Programmierung einen Pix erstellen müssen.

- [Gerador de QR Code Pix](https://go.mymarketing.click/pix-gerador-de-qr-code-pix) - Erzeugt im Browser einen Pix-QR-Code, eine Karte und einen Link aus dem Schlüssel. `Open Source` `kostenlos`
- [Infrastructure Payments](https://go.mymarketing.click/pix-infrastructure-payments) - Einzelne Zahlungsanforderung per Pix und Karte über das Mercado-Pago-Konto, mit REST, React-SDK und MCP. `API` `vom Autor`
- [Marketing Stores](https://go.mymarketing.click/pix-marketing-stores) - Online-Shop mit Zahlung per Pix, mit QR Code und copia e cola sowie Karte direkt über das Mercado-Pago-Konto des Inhabers. `API` `vom Autor`

## Andere Listen und Communitys

Wer schon Material zu Pix zusammengetragen hat.

- [awesome-pix (Woovi)](https://go.mymarketing.click/pix-awesome-pix-woovi) - Die erste Ressourcenliste zu Pix, gepflegt von Woovi. `Open Source` `kostenlos`

## Tags

Jeder Eintrag sagt, was er ist. Die Tags daneben helfen bei der Auswahl: offiziell, wenn es vom Standardgeber stammt, Open Source, wenn der Code veröffentlicht ist, kostenlos oder kostenpflichtig je nach Nutzungsmodell, API und SDK je nach Art der Integration. Einträge mit dem Tag "vom Autor" stammen von Ciro Cesar Maciel und folgen denselben Regeln wie alle anderen.

## So beteiligst du dich

Kennst du etwas, das fehlt, sich geändert hat oder nicht mehr erreichbar ist? Öffne ein Issue mit dem Formular für neue Einträge oder schick einen Pull Request, der data/list.json bearbeitet. Die README jeder Sprache wird aus dieser Datei erzeugt.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Weitere Listen

Kuratierte Listen im selben Format, auf Portugiesisch und in weiteren 14 Sprachen.


## Von Ciro Cesar Maciel erstellt

Wenn du nutzt, was ich mache, unterstützt du diese Listen ebenfalls.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/pix-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/pix-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/pix-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/pix-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/pix-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/pix-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/pix-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/pix-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/pix-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/pix-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/pix-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/pix-por-agents)

## Lizenz

Diese Liste steht unter CC0 1.0: Kopiere, passe an und verbreite sie frei, ohne um Erlaubnis zu fragen. Der Code des Generators liegt im awesome-kit unter MIT.

<sub>Aktualisiert am 2026-11-10.</sub>
