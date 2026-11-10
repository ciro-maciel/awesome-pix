# Awesome Pix

> 面向集成者的 Pix：规范、API、SDK、服务商和工具，逐一核实。

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-%E8%AE%A2%E9%98%85-111111?style=flat-square)](https://go.mymarketing.click/pix-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/pix-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/zh.xml) ![56 项](https://img.shields.io/badge/%E9%A1%B9-56-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-6b6b6b?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

面向需要在系统中收款、付款或对账 Pix 的人。从巴西中央银行发布的内容开始，接着是提供 API 的服务商，最后是生成和读取二维码的开源代码库。每个地址在收录前都已打开核实。

## 内容

- [规范与官方文档](#规范与官方文档)
- [规范与开放 API](#规范与开放-api)
- [提供 Pix API 的服务商](#提供-pix-api-的服务商)
- [服务提供商官方 SDK](#服务提供商官方-sdk)
- [开源库](#开源库)
- [社区 SDK](#社区-sdk)
- [数据和工具](#数据和工具)
- [工具](#工具)
- [其他列表和社区](#其他列表和社区)
- [标签](#标签)
- [如何贡献](#如何贡献)
- [其他列表](#其他列表)
- [由 Ciro Cesar Maciel 制作](#由-ciro-cesar-maciel-制作)
- [许可证](#许可证)

## 规范与官方文档

来自巴西中央银行的内容，该机构制定了 Pix 标准。

- [Pix no Banco Central](https://go.mymarketing.click/pix-pix-no-banco-central) - Pix 官方页面，介绍它是什么、如何运作，并链接到其他资源。 `官方` `免费`
- [Normas do Pix](https://go.mymarketing.click/pix-normas-do-pix) - 管理 Pix 的规定、决议和手册。 `官方` `免费`
- [Pix Automático](https://go.mymarketing.click/pix-pix-automatico) - 针对由付款人授权一次的定期收款的模式。 `官方` `免费`
- [Participantes do Pix](https://go.mymarketing.click/pix-participantes-do-pix) - 提供 Pix 服务的机构列表及其所支持的模式。 `官方` `免费`
- [Estatísticas do Pix](https://go.mymarketing.click/pix-estatisticas-do-pix) - 官方的交易笔数、金额和密钥数据。 `官方` `免费`
- [Perguntas frequentes do Pix](https://go.mymarketing.click/pix-perguntas-frequentes-do-pix) - 巴西中央银行对 Pix 用户最常见问题的解答。 `官方` `免费`

## 规范与开放 API

巴西中央银行在 GitHub 上发布的 API 合约。

- [API Pix](https://go.mymarketing.click/pix-api-pix) - Pix API 的 OpenAPI 规范，供服务提供商实现收款与入账功能。 `官方` `开源` `API`
- [API do DICT](https://go.mymarketing.click/pix-api-do-dict) - 交易账户标识符目录（DICT）的 API 规范，Pix 密钥即存放于此。 `官方` `开源` `API`
- [DICT Quickstart](https://go.mymarketing.click/pix-dict-quickstart) - DICT API 的入门指南。 `官方` `开源`

## 提供 Pix API 的服务商

银行、支付机构和平台提供公开文档，便于集成 Pix。

- [Adyen](https://go.mymarketing.click/pix-adyen) - Adyen 全球平台中作为支付方式的 Pix。 `API` `付费`
- [Asaas](https://go.mymarketing.click/pix-asaas) - Asaas API 文档，支持通过 Pix、boleto 和银行卡收款。 `API` `付费`
- [Banco do Brasil](https://go.mymarketing.click/pix-banco-do-brasil) - 巴西银行（Banco do Brasil）开发者门户，提供 Pix API。 `API`
- [Banco Inter](https://go.mymarketing.click/pix-banco-inter) - Inter 开发者门户，提供 Pix 和收款 API。 `API`
- [Bradesco](https://go.mymarketing.click/pix-bradesco) - Bradesco 开发者门户，提供 Pix API。 `API`
- [Celcoin](https://go.mymarketing.click/pix-celcoin) - 为构建金融产品的企业提供的支付基础设施，带有 Pix API。 `API` `付费`
- [Cora](https://go.mymarketing.click/pix-cora) - Cora 的收款和企业账户 Pix API。 `API`
- [dLocal](https://go.mymarketing.click/pix-dlocal) - 新兴市场的支付，Pix 是巴西支持的付款方式之一。 `API` `付费`
- [EBANX](https://go.mymarketing.click/pix-ebanx) - 拉丁美洲本地支付，为巴西内外的企业提供 Pix 服务。 `API` `付费`
- [Efí](https://go.mymarketing.click/pix-efi) - Efí（原 Gerencianet）的 Pix API 文档，包括收款、webhook 和 Pix Automático。 `API` `付费`
- [Itaú](https://go.mymarketing.click/pix-itau) - Itaú 开发者门户，提供 Pix API。 `API`
- [Iugu](https://go.mymarketing.click/pix-iugu) - Iugu API 文档，支持接受 Pix 的收款和订阅。 `API` `付费`
- [Mercado Pago](https://go.mymarketing.click/pix-mercado-pago) - 通过 Mercado Pago 的 Checkout API 接收 Pix，包括 QR Code 和 copia e cola。 `API` `付费`
- [OpenPix](https://go.mymarketing.click/pix-openpix) - OpenPix 文档，这是一个带有 API、webhook 和插件的 Pix 收款平台。 `API` `付费`
- [PagBank](https://go.mymarketing.click/pix-pagbank) - PagBank 开发者门户，支持通过 Pix 下单和收款。 `API` `付费`
- [Pagar.me](https://go.mymarketing.click/pix-pagar-me) - Pagar.me API 文档，支持 Pix、银行卡和 boleto 付款。 `API` `付费`
- [Santander](https://go.mymarketing.click/pix-santander) - Santander 开发者门户，提供 Pix API。 `API`
- [Sicredi](https://go.mymarketing.click/pix-sicredi) - Sicredi 开发者门户，提供 Pix 和收款 API。 `API`
- [Stripe](https://go.mymarketing.click/pix-stripe) - Stripe 中作为支付方式的 Pix，适合已在 Stripe 收款的用户。 `API` `付费`
- [Transfeera](https://go.mymarketing.click/pix-transfeera) - Pix 收付款 API，带对账功能。 `API` `付费`
- [Woovi](https://go.mymarketing.click/pix-woovi) - Woovi 文档，支持通过 Pix 收款、订阅和 webhook。 `API` `付费`

## 服务提供商官方 SDK

由 API 提供方维护。

- [Efí SDK Node.js](https://go.mymarketing.click/pix-efi-sdk-node-js) - Efí API 的 Node.js SDK，支持 QR Code 和 copia e cola 形式的 Pix 收款。 `开源` `SDK`
- [Efí SDK PHP](https://go.mymarketing.click/pix-efi-sdk-php) - Efí API 的 PHP SDK，支持 QR Code 和 copia e cola 形式的 Pix 收款。 `开源` `SDK`
- [Gerencianet SDK Python](https://go.mymarketing.click/pix-gerencianet-sdk-python) - Efí API 的 Python SDK，以旧名 Gerencianet 发布。 `开源` `SDK`
- [Mercado Pago SDK .NET](https://go.mymarketing.click/pix-mercado-pago-sdk-net) - Mercado Pago 官方 .NET SDK。 `开源` `SDK`
- [Mercado Pago SDK Java](https://go.mymarketing.click/pix-mercado-pago-sdk-java) - Mercado Pago 官方 Java SDK。 `开源` `SDK`
- [Mercado Pago SDK Node.js](https://go.mymarketing.click/pix-mercado-pago-sdk-node-js) - Mercado Pago 官方 Node.js SDK。 `开源` `SDK`
- [Mercado Pago SDK PHP](https://go.mymarketing.click/pix-mercado-pago-sdk-php) - Mercado Pago 官方 PHP SDK。 `开源` `SDK`
- [Mercado Pago SDK Python](https://go.mymarketing.click/pix-mercado-pago-sdk-python) - Mercado Pago 官方 Python SDK。 `开源` `SDK`
- [OpenPix Developers](https://go.mymarketing.click/pix-openpix-developers) - OpenPix 文档的代码，包含集成示例。 `开源`
- [Woovi Developers](https://go.mymarketing.click/pix-woovi-developers) - Woovi 文档的代码，包含集成示例。 `开源`

## 开源库

用于生成、读取和验证 BR Code（即 QR Code 和复制粘贴内容），无需依赖第三方服务商。

- [brcode](https://go.mymarketing.click/pix-brcode) - Rust 版 Pix BR Code 读取器。 `开源` `免费`
- [emv-qrcode](https://go.mymarketing.click/pix-emv-qrcode) - Java 版 EMV 标准 QR Code 生成和读取工具，BR Code 即遵循此标准。 `开源` `免费`
- [go-pix](https://go.mymarketing.click/pix-go-pix) - Go 语言库，用于生成 Pix 复制粘贴码和 QR Code。 `开源` `免费`
- [php_qrcode_pix](https://go.mymarketing.click/pix-php-qrcode-pix) - PHP 中生成 Pix QR Code。 `开源` `免费`
- [PHPay](https://go.mymarketing.click/pix-phpay) - PHP 库，通过统一接口集成多个支付服务商。 `开源` `免费`
- [pix-payload](https://go.mymarketing.click/pix-pix-payload) - npm 包，按照巴西中央银行的标准生成 Pix payload。 `开源` `免费`
- [pix-utils](https://go.mymarketing.click/pix-pix-utils) - TypeScript 工具，用于读取、生成和验证 Pix 代码。 `开源` `免费`
- [PIX-BACEN-SDK-dotnet](https://go.mymarketing.click/pix-pix-bacen-sdk-dotnet) - 巴西中央银行 Pix API 的 .NET 契约，基于官方规范生成。 `开源` `免费`
- [pypix](https://go.mymarketing.click/pix-pypix) - Python 库，用于生成 Pix 的 BR Code 和 QR Code。 `开源` `免费`

## 社区 SDK

由 API 使用者开发，而非服务商官方提供。

- [asaas (TypeScript)](https://go.mymarketing.click/pix-asaas-typescript) - TypeScript SDK，封装了 Asaas API 最常用的调用。 `开源` `免费`
- [asaas-sdk (PHP)](https://go.mymarketing.click/pix-asaas-sdk-php) - Asaas API 的 PHP SDK。 `开源` `免费`

## 数据和工具

用于验证和对账。

- [Bancos Brasileiros](https://go.mymarketing.click/pix-bancos-brasileiros) - 巴西银行列表，包含代码、ISPB 和名称，提供多种格式。 `开源` `免费`

## 工具

适合无需编写代码即可生成 Pix 的用户。

- [Gerador de QR Code Pix](https://go.mymarketing.click/pix-gerador-de-qr-code-pix) - 根据密钥在浏览器中生成 Pix QR Code、标牌和链接。 `开源` `免费`
- [Infrastructure Payments](https://go.mymarketing.click/pix-infrastructure-payments) - 通过您自己的 Mercado Pago 账户进行 Pix 和信用卡单次收款，提供 REST、React SDK 和 MCP。 `API` `作者自制`
- [Marketing Stores](https://go.mymarketing.click/pix-marketing-stores) - 在线商店，支持 Pix 付款（含 QR Code 和复制粘贴），信用卡直接通过店主的 Mercado Pago 收款。 `API` `作者自制`

## 其他列表和社区

之前已整理过 Pix 相关资料的项目。

- [awesome-pix (Woovi)](https://go.mymarketing.click/pix-awesome-pix-woovi) - 首个 Pix 资源列表，由 Woovi 维护。 `开源` `免费`

## 标签

每一项都说明了它是什么。旁边的标签有助于选择：官方表示来自制定标准的机构，开源表示代码已公开，免费或付费按使用模式划分，API 和 SDK 按集成方式划分。带有“作者自制”标签的条目由 Ciro Cesar Maciel 制作，并遵循与其他所有条目相同的规则。

## 如何贡献

发现有缺失、已变更或已失效的内容？请使用新增条目表单开一个 issue，或提交 pull request 修改 data/list.json。每种语言的 README 都由该文件生成。

[CONTRIBUTING.md](CONTRIBUTING.md)

## 其他列表

同一格式的精选列表，包括葡萄牙语以及另外 14 种语言。


## 由 Ciro Cesar Maciel 制作

使用我的作品，也是支持这些列表的一种方式。

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/pix-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/pix-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/pix-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/pix-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/pix-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/pix-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/pix-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/pix-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/pix-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/pix-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/pix-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/pix-por-agents)

## 许可证

本列表采用 CC0 1.0 协议：可随意复制、改编和再分发，无需征得许可。生成器代码位于 awesome-kit 中，采用 MIT 协议。

<sub>更新于 2026-11-10.</sub>
