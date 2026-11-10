# Awesome Pix

> Pix for integrators: standards, APIs, SDKs, providers and tools, each one checked.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-subscribe-111111?style=flat-square)](https://go.mymarketing.click/pix-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/pix-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/en.xml) ![56 items](https://img.shields.io/badge/items-56-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-6b6b6b?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

For those who will charge, receive or reconcile Pix in a system. It starts with what the Central Bank publishes, goes through the providers that offer an API and ends with the open source libraries that generate and read the QR Code. Every address was opened before being listed.

## Content

- [Standards and official documentation](#standards-and-official-documentation)
- [Specifications and open APIs](#specifications-and-open-apis)
- [Providers with Pix API](#providers-with-pix-api)
- [Official SDKs from providers](#official-sdks-from-providers)
- [Open source libraries](#open-source-libraries)
- [Community SDKs](#community-sdks)
- [Data and utilities](#data-and-utilities)
- [Tools](#tools)
- [Other lists and communities](#other-lists-and-communities)
- [Tags](#tags)
- [How to contribute](#how-to-contribute)
- [Other lists](#other-lists)
- [Made by Ciro Cesar Maciel](#made-by-ciro-cesar-maciel)
- [License](#license)

## Standards and official documentation

What comes from the Central Bank, which defines Pix.

- [Pix no Banco Central](https://go.mymarketing.click/pix-pix-no-banco-central) - The official Pix page, with what it is, how it works and links to the rest. `official` `free`
- [Normas do Pix](https://go.mymarketing.click/pix-normas-do-pix) - The regulation, resolutions and manuals that govern Pix. `official` `free`
- [Pix Automático](https://go.mymarketing.click/pix-pix-automatico) - The mode for recurring charges authorized once by the payer. `official` `free`
- [Participantes do Pix](https://go.mymarketing.click/pix-participantes-do-pix) - The list of institutions that offer Pix and in which mode. `official` `free`
- [Estatísticas do Pix](https://go.mymarketing.click/pix-estatisticas-do-pix) - Official numbers for transactions, amounts and keys. `official` `free`
- [Perguntas frequentes do Pix](https://go.mymarketing.click/pix-perguntas-frequentes-do-pix) - Answers from the Central Bank to the most common questions from Pix users. `official` `free`

## Specifications and open APIs

The API contracts that the Central Bank publishes on GitHub.

- [API Pix](https://go.mymarketing.click/pix-api-pix) - The OpenAPI specification for the Pix API, which providers implement for charges and receipts. `official` `open source` `API`
- [API do DICT](https://go.mymarketing.click/pix-api-do-dict) - The API specification for the Transactional Account Identifier Directory, where Pix keys live. `official` `open source` `API`
- [DICT Quickstart](https://go.mymarketing.click/pix-dict-quickstart) - A getting started guide to the DICT API. `official` `open source`

## Providers with Pix API

Banks, payment institutions and platforms with public documentation for integrating Pix.

- [Adyen](https://go.mymarketing.click/pix-adyen) - Pix as a payment method on Adyen's global platform. `API` `paid`
- [Asaas](https://go.mymarketing.click/pix-asaas) - Asaas API documentation, with charges via Pix, boleto and card. `API` `paid`
- [Banco do Brasil](https://go.mymarketing.click/pix-banco-do-brasil) - Banco do Brasil developer portal, with the Pix API. `API`
- [Banco Inter](https://go.mymarketing.click/pix-banco-inter) - Inter developer portal, with Pix and billing APIs. `API`
- [Bradesco](https://go.mymarketing.click/pix-bradesco) - Bradesco developer portal, with Pix APIs. `API`
- [Celcoin](https://go.mymarketing.click/pix-celcoin) - Payment infrastructure with Pix APIs for companies building financial products. `API` `paid`
- [Cora](https://go.mymarketing.click/pix-cora) - Cora APIs for billing and Pix on the business account. `API`
- [dLocal](https://go.mymarketing.click/pix-dlocal) - Payments in emerging markets, with Pix among the accepted methods in Brazil. `API` `paid`
- [EBANX](https://go.mymarketing.click/pix-ebanx) - Local payments in Latin America, with Pix for companies from inside and outside Brazil. `API` `paid`
- [Efí](https://go.mymarketing.click/pix-efi) - Efí Pix API documentation, formerly Gerencianet, with charges, webhooks and Pix Automático. `API` `paid`
- [Itaú](https://go.mymarketing.click/pix-itau) - Itaú developer portal, with Pix APIs. `API`
- [Iugu](https://go.mymarketing.click/pix-iugu) - Iugu API documentation, with charges and subscriptions that accept Pix. `API` `paid`
- [Mercado Pago](https://go.mymarketing.click/pix-mercado-pago) - How to receive Pix through the Mercado Pago Checkout API, with QR Code and copia e cola. `API` `paid`
- [OpenPix](https://go.mymarketing.click/pix-openpix) - OpenPix documentation, a Pix charge platform with API, webhooks and plugins. `API` `paid`
- [PagBank](https://go.mymarketing.click/pix-pagbank) - PagBank developer portal, with orders and charges via Pix. `API` `paid`
- [Pagar.me](https://go.mymarketing.click/pix-pagar-me) - Pagar.me API documentation, with payments via Pix, card and boleto. `API` `paid`
- [Santander](https://go.mymarketing.click/pix-santander) - Santander developer portal, with Pix APIs. `API`
- [Sicredi](https://go.mymarketing.click/pix-sicredi) - Sicredi developer portal, with Pix and billing APIs. `API`
- [Stripe](https://go.mymarketing.click/pix-stripe) - Pix as a payment method on Stripe, for those already charging through it. `API` `paid`
- [Transfeera](https://go.mymarketing.click/pix-transfeera) - Pix payment and receipt APIs, with reconciliation. `API` `paid`
- [Woovi](https://go.mymarketing.click/pix-woovi) - Woovi documentation, with Pix charges, subscriptions and webhooks. `API` `paid`

## Official SDKs from providers

Maintained by whoever offers the API.

- [Efí SDK Node.js](https://go.mymarketing.click/pix-efi-sdk-node-js) - Node.js SDK for the Efí APIs, with Pix charges via QR Code and copia e cola. `open source` `SDK`
- [Efí SDK PHP](https://go.mymarketing.click/pix-efi-sdk-php) - PHP SDK for the Efí APIs, with Pix charges via QR Code and copia e cola. `open source` `SDK`
- [Gerencianet SDK Python](https://go.mymarketing.click/pix-gerencianet-sdk-python) - Python SDK for the Efí API, published under the old name Gerencianet. `open source` `SDK`
- [Mercado Pago SDK .NET](https://go.mymarketing.click/pix-mercado-pago-sdk-net) - Mercado Pago's official SDK for .NET. `open source` `SDK`
- [Mercado Pago SDK Java](https://go.mymarketing.click/pix-mercado-pago-sdk-java) - Mercado Pago's official SDK for Java. `open source` `SDK`
- [Mercado Pago SDK Node.js](https://go.mymarketing.click/pix-mercado-pago-sdk-node-js) - The official Mercado Pago SDK for Node.js. `open source` `SDK`
- [Mercado Pago SDK PHP](https://go.mymarketing.click/pix-mercado-pago-sdk-php) - The official Mercado Pago SDK for PHP. `open source` `SDK`
- [Mercado Pago SDK Python](https://go.mymarketing.click/pix-mercado-pago-sdk-python) - The official Mercado Pago SDK for Python. `open source` `SDK`
- [OpenPix Developers](https://go.mymarketing.click/pix-openpix-developers) - The documentation code for OpenPix, with integration examples. `open source`
- [Woovi Developers](https://go.mymarketing.click/pix-woovi-developers) - The documentation code for Woovi, with integration examples. `open source`

## Open source libraries

To generate, read and validate the BR Code (the content of the QR Code and copia e cola) without depending on a provider.

- [brcode](https://go.mymarketing.click/pix-brcode) - BR Code Pix reader in Rust. `open source` `free`
- [emv-qrcode](https://go.mymarketing.click/pix-emv-qrcode) - EMV QR Code generator and reader in Java, the standard that BR Code follows. `open source` `free`
- [go-pix](https://go.mymarketing.click/pix-go-pix) - Go library to generate Pix copia e cola and QR Code. `open source` `free`
- [php_qrcode_pix](https://go.mymarketing.click/pix-php-qrcode-pix) - Pix QR Code generation in PHP. `open source` `free`
- [PHPay](https://go.mymarketing.click/pix-phpay) - PHP library to integrate several payment providers with the same interface. `open source` `free`
- [pix-payload](https://go.mymarketing.click/pix-pix-payload) - npm package that generates the Pix payload following the Banco Central standard. `open source` `free`
- [pix-utils](https://go.mymarketing.click/pix-pix-utils) - TypeScript tools to read, generate and validate Pix codes. `open source` `free`
- [PIX-BACEN-SDK-dotnet](https://go.mymarketing.click/pix-pix-bacen-sdk-dotnet) - Banco Central Pix API contracts in .NET, generated from the official specification. `open source` `free`
- [pypix](https://go.mymarketing.click/pix-pypix) - Python library to generate the BR Code and Pix QR Code. `open source` `free`

## Community SDKs

Made by people who use the API, not by the provider.

- [asaas (TypeScript)](https://go.mymarketing.click/pix-asaas-typescript) - TypeScript SDK that abstracts the most used Asaas API calls. `open source` `free`
- [asaas-sdk (PHP)](https://go.mymarketing.click/pix-asaas-sdk-php) - PHP SDK for the Asaas API. `open source` `free`

## Data and utilities

What helps with validation and reconciliation.

- [Bancos Brasileiros](https://go.mymarketing.click/pix-bancos-brasileiros) - List of Brazilian banks with code, ISPB and name, in several formats. `open source` `free`

## Tools

For those who need to generate a Pix without writing code.

- [Gerador de QR Code Pix](https://go.mymarketing.click/pix-gerador-de-qr-code-pix) - Generates a Pix QR Code, plate and link in the browser from the key. `open source` `free`
- [Infrastructure Payments](https://go.mymarketing.click/pix-infrastructure-payments) - One-off Pix and card charges through Mercado Pago from your account, with REST, React SDK and MCP. `API` `by the author`
- [Marketing Stores](https://go.mymarketing.click/pix-marketing-stores) - Online store with Pix payment, with QR Code and copia e cola, and card payments directly to the owner's Mercado Pago. `API` `by the author`

## Other lists and communities

Those who have already gathered material on Pix before.

- [awesome-pix (Woovi)](https://go.mymarketing.click/pix-awesome-pix-woovi) - The first list of resources on Pix, maintained by Woovi. `open source` `free`

## Tags

Each item says what it is. The tags next to it help you choose: official when it comes from whoever sets the standard, open source when the code is published, free or paid by usage model, API and SDK by how you integrate. Items tagged "by the author" are made by Ciro Cesar Maciel and follow the same rules as all the others.

## How to contribute

Know something that is missing, has changed or is gone? Open an issue with the new entry form or send a pull request editing data/list.json. The README for each language is generated from this file.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Other lists

Curated lists in the same format, in Portuguese and 14 more languages.


## Made by Ciro Cesar Maciel

Using what I make is also a way to support these lists.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/pix-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/pix-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/pix-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/pix-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/pix-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/pix-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/pix-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/pix-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/pix-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/pix-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/pix-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/pix-por-agents)

## License

This list is under CC0 1.0: copy, adapt and redistribute it as you wish, without asking permission. The generator code is in awesome-kit, under MIT.

<sub>Last updated 2026-11-10.</sub>
