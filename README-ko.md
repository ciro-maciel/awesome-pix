# Awesome Pix

> Pix를 통합하는 개발자를 위한 자료: 규정, API, SDK, 제공업체, 도구를 하나씩 확인했습니다.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-%EA%B5%AC%EB%8F%85-111111?style=flat-square)](https://go.mymarketing.click/pix-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/pix-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/ko.xml) ![56 항목](https://img.shields.io/badge/%ED%95%AD%EB%AA%A9-56-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-6b6b6b?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

Pix로 결제를 받거나 청구하거나 대사(conciliation)하는 시스템을 만드는 분들을 위한 목록입니다. 브라질 중앙은행(Banco Central)이 공개한 자료부터 시작해, API를 제공하는 제공업체를 거쳐, QR Code를 생성하고 읽는 오픈 소스 라이브러리까지 다룹니다. 모든 주소는 등록 전에 직접 열어 확인했습니다.

## 콘텐츠

- [규정 및 공식 문서](#규정-및-공식-문서)
- [사양 및 공개 API](#사양-및-공개-api)
- [Pix API 제공 업체](#pix-api-제공-업체)
- [제공자의 공식 SDK](#제공자의-공식-sdk)
- [오픈 소스 라이브러리](#오픈-소스-라이브러리)
- [커뮤니티 SDK](#커뮤니티-sdk)
- [데이터 및 유틸리티](#데이터-및-유틸리티)
- [도구](#도구)
- [다른 목록과 커뮤니티](#다른-목록과-커뮤니티)
- [태그](#태그)
- [기여 방법](#기여-방법)
- [다른 목록](#다른-목록)
- [Ciro Cesar Maciel 제작](#ciro-cesar-maciel-제작)
- [라이선스](#라이선스)

## 규정 및 공식 문서

Pix를 규정하는 브라질 중앙은행의 자료.

- [Pix no Banco Central](https://go.mymarketing.click/pix-pix-no-banco-central) - Pix의 공식 페이지로, 개요, 작동 방식, 그리고 다른 자료로 가는 링크를 제공합니다. `공식` `무료`
- [Normas do Pix](https://go.mymarketing.click/pix-normas-do-pix) - Pix에 관한 규정, 결의안 및 매뉴얼입니다. `공식` `무료`
- [Pix Automático](https://go.mymarketing.click/pix-pix-automatico) - 한 번 결제자가 승인한 정기 청구를 위한 방식입니다. `공식` `무료`
- [Participantes do Pix](https://go.mymarketing.click/pix-participantes-do-pix) - Pix를 제공하는 기관과 해당 방식 목록입니다. `공식` `무료`
- [Estatísticas do Pix](https://go.mymarketing.click/pix-estatisticas-do-pix) - 거래 건수, 금액, 키에 관한 공식 통계입니다. `공식` `무료`
- [Perguntas frequentes do Pix](https://go.mymarketing.click/pix-perguntas-frequentes-do-pix) - Pix 사용자들이 가장 자주 묻는 질문에 대한 중앙은행의 답변입니다. `공식` `무료`

## 사양 및 공개 API

중앙은행이 GitHub에 공개한 API 계약입니다.

- [API Pix](https://go.mymarketing.click/pix-api-pix) - 제공자들이 청구와 수취를 위해 구현하는 Pix API의 OpenAPI 사양입니다. `공식` `오픈 소스` `API`
- [API do DICT](https://go.mymarketing.click/pix-api-do-dict) - Pix 키가 저장되는 거래 계좌 식별자 디렉터리(DICT) API의 사양입니다. `공식` `오픈 소스` `API`
- [DICT Quickstart](https://go.mymarketing.click/pix-dict-quickstart) - DICT API 시작 가이드입니다. `공식` `오픈 소스`

## Pix API 제공 업체

Pix 연동을 위한 공개 문서를 갖춘 은행, 결제 기관 및 플랫폼입니다.

- [Adyen](https://go.mymarketing.click/pix-adyen) - Adyen 글로벌 플랫폼의 Pix 결제 수단입니다. `API` `유료`
- [Asaas](https://go.mymarketing.click/pix-asaas) - Asaas API 문서로, Pix, boleto, 카드 청구를 지원합니다. `API` `유료`
- [Banco do Brasil](https://go.mymarketing.click/pix-banco-do-brasil) - Pix API를 제공하는 Banco do Brasil 개발자 포털입니다. `API`
- [Banco Inter](https://go.mymarketing.click/pix-banco-inter) - Pix 및 청구 API를 제공하는 Inter 개발자 포털입니다. `API`
- [Bradesco](https://go.mymarketing.click/pix-bradesco) - Pix API를 제공하는 Bradesco 개발자 포털입니다. `API`
- [Celcoin](https://go.mymarketing.click/pix-celcoin) - 금융 상품을 만드는 기업을 위한 Pix API 기반 결제 인프라입니다. `API` `유료`
- [Cora](https://go.mymarketing.click/pix-cora) - 기업 계좌에서 청구와 Pix를 위한 Cora API입니다. `API`
- [dLocal](https://go.mymarketing.click/pix-dlocal) - 신흥 시장의 결제로, 브라질에서 허용되는 방식 중 하나로 Pix를 지원합니다. `API` `유료`
- [EBANX](https://go.mymarketing.click/pix-ebanx) - 라틴 아메리카 현지 결제로, 브라질 내외 기업을 위한 Pix를 지원합니다. `API` `유료`
- [Efí](https://go.mymarketing.click/pix-efi) - 기존 Gerencianet인 Efí의 Pix API 문서로, 청구, webhook, Pix Automático를 지원합니다. `API` `유료`
- [Itaú](https://go.mymarketing.click/pix-itau) - Pix API를 제공하는 Itaú 개발자 포털입니다. `API`
- [Iugu](https://go.mymarketing.click/pix-iugu) - Pix로 결제를 받는 청구 및 구독을 지원하는 Iugu API 문서입니다. `API` `유료`
- [Mercado Pago](https://go.mymarketing.click/pix-mercado-pago) - Mercado Pago Checkout API로 QR Code와 copia e cola를 사용해 Pix를 받는 방법입니다. `API` `유료`
- [OpenPix](https://go.mymarketing.click/pix-openpix) - API, webhook, 플러그인을 갖춘 Pix 청구 플랫폼 OpenPix 문서입니다. `API` `유료`
- [PagBank](https://go.mymarketing.click/pix-pagbank) - Pix 주문 및 청구를 지원하는 PagBank 개발자 포털입니다. `API` `유료`
- [Pagar.me](https://go.mymarketing.click/pix-pagar-me) - Pix, 카드, boleto 결제를 지원하는 Pagar.me API 문서입니다. `API` `유료`
- [Santander](https://go.mymarketing.click/pix-santander) - Pix API를 제공하는 Santander 개발자 포털입니다. `API`
- [Sicredi](https://go.mymarketing.click/pix-sicredi) - Pix 및 청구 API를 제공하는 Sicredi 개발자 포털입니다. `API`
- [Stripe](https://go.mymarketing.click/pix-stripe) - Stripe를 이미 사용하는 사용자를 위한 Stripe의 Pix 결제 수단입니다. `API` `유료`
- [Transfeera](https://go.mymarketing.click/pix-transfeera) - 조정 기능을 갖춘 Pix 결제 및 수취 API입니다. `API` `유료`
- [Woovi](https://go.mymarketing.click/pix-woovi) - Pix 청구, 구독, webhook을 다루는 Woovi 문서입니다. `API` `유료`

## 제공자의 공식 SDK

API를 제공하는 쪽에서 관리합니다.

- [Efí SDK Node.js](https://go.mymarketing.click/pix-efi-sdk-node-js) - QR Code와 copia e cola로 Pix 청구를 하는 Efí API용 Node.js SDK입니다. `오픈 소스` `SDK`
- [Efí SDK PHP](https://go.mymarketing.click/pix-efi-sdk-php) - QR Code와 copia e cola로 Pix 청구를 하는 Efí API용 PHP SDK입니다. `오픈 소스` `SDK`
- [Gerencianet SDK Python](https://go.mymarketing.click/pix-gerencianet-sdk-python) - 이전 이름 Gerencianet으로 배포된 Efí API용 Python SDK입니다. `오픈 소스` `SDK`
- [Mercado Pago SDK .NET](https://go.mymarketing.click/pix-mercado-pago-sdk-net) - Mercado Pago의 공식 .NET SDK입니다. `오픈 소스` `SDK`
- [Mercado Pago SDK Java](https://go.mymarketing.click/pix-mercado-pago-sdk-java) - Mercado Pago의 공식 Java SDK입니다. `오픈 소스` `SDK`
- [Mercado Pago SDK Node.js](https://go.mymarketing.click/pix-mercado-pago-sdk-node-js) - Mercado Pago의 공식 Node.js SDK입니다. `오픈 소스` `SDK`
- [Mercado Pago SDK PHP](https://go.mymarketing.click/pix-mercado-pago-sdk-php) - Mercado Pago의 공식 PHP SDK입니다. `오픈 소스` `SDK`
- [Mercado Pago SDK Python](https://go.mymarketing.click/pix-mercado-pago-sdk-python) - Mercado Pago의 공식 Python SDK입니다. `오픈 소스` `SDK`
- [OpenPix Developers](https://go.mymarketing.click/pix-openpix-developers) - OpenPix의 문서 코드로, 연동 예제가 포함되어 있습니다. `오픈 소스`
- [Woovi Developers](https://go.mymarketing.click/pix-woovi-developers) - Woovi의 문서 코드로, 연동 예제가 포함되어 있습니다. `오픈 소스`

## 오픈 소스 라이브러리

BR Code(QR Code와 copia e cola의 내용)를 제공업체에 의존하지 않고 생성, 읽기, 검증합니다.

- [brcode](https://go.mymarketing.click/pix-brcode) - Rust로 만든 Pix BR Code 리더입니다. `오픈 소스` `무료`
- [emv-qrcode](https://go.mymarketing.click/pix-emv-qrcode) - Java로 만든 EMV QR Code 생성 및 읽기 도구입니다. BR Code가 따르는 표준입니다. `오픈 소스` `무료`
- [go-pix](https://go.mymarketing.click/pix-go-pix) - Go로 만든 라이브러리로, Pix copia e cola와 QR Code를 생성합니다. `오픈 소스` `무료`
- [php_qrcode_pix](https://go.mymarketing.click/pix-php-qrcode-pix) - PHP로 Pix QR Code를 생성합니다. `오픈 소스` `무료`
- [PHPay](https://go.mymarketing.click/pix-phpay) - 같은 인터페이스로 여러 결제 제공업체를 연동하는 PHP 라이브러리입니다. `오픈 소스` `무료`
- [pix-payload](https://go.mymarketing.click/pix-pix-payload) - Banco Central 표준에 따라 Pix 페이로드를 생성하는 npm 패키지입니다. `오픈 소스` `무료`
- [pix-utils](https://go.mymarketing.click/pix-pix-utils) - Pix 코드를 읽고, 생성하고, 검증하는 TypeScript 도구입니다. `오픈 소스` `무료`
- [PIX-BACEN-SDK-dotnet](https://go.mymarketing.click/pix-pix-bacen-sdk-dotnet) - Banco Central의 공식 명세로 생성한 .NET용 Pix API 계약입니다. `오픈 소스` `무료`
- [pypix](https://go.mymarketing.click/pix-pypix) - Pix의 BR Code와 QR Code를 생성하는 Python 라이브러리입니다. `오픈 소스` `무료`

## 커뮤니티 SDK

제공업체가 아닌 API 사용자들이 만들었습니다.

- [asaas (TypeScript)](https://go.mymarketing.click/pix-asaas-typescript) - Asaas API의 자주 쓰는 호출을 감싼 TypeScript SDK입니다. `오픈 소스` `무료`
- [asaas-sdk (PHP)](https://go.mymarketing.click/pix-asaas-sdk-php) - Asaas API용 PHP SDK입니다. `오픈 소스` `무료`

## 데이터 및 유틸리티

검증과 대사에 도움이 되는 도구입니다.

- [Bancos Brasileiros](https://go.mymarketing.click/pix-bancos-brasileiros) - 코드, ISPB, 이름을 포함한 브라질 은행 목록이며 여러 형식으로 제공됩니다. `오픈 소스` `무료`

## 도구

코드를 작성하지 않고 Pix 결제를 만들고 싶은 분들을 위한 도구입니다.

- [Gerador de QR Code Pix](https://go.mymarketing.click/pix-gerador-de-qr-code-pix) - 키를 입력하면 브라우저에서 Pix QR Code, 인쇄용 코드, 링크를 생성합니다. `오픈 소스` `무료`
- [Infrastructure Payments](https://go.mymarketing.click/pix-infrastructure-payments) - Mercado Pago 계정으로 Pix와 카드 단건 결제를 받습니다. REST, React SDK, MCP를 지원합니다. `API` `작성자 제작`
- [Marketing Stores](https://go.mymarketing.click/pix-marketing-stores) - Pix(QR Code와 copia e cola)와 상점 주인의 Mercado Pago 카드 결제를 지원하는 온라인 상점입니다. `API` `작성자 제작`

## 다른 목록과 커뮤니티

Pix 관련 자료를 이미 모아 둔 곳입니다.

- [awesome-pix (Woovi)](https://go.mymarketing.click/pix-awesome-pix-woovi) - Woovi가 관리하는 최초의 Pix 자료 목록입니다. `오픈 소스` `무료`

## 태그

각 항목은 무엇인지 설명합니다. 옆의 태그가 선택을 도와줍니다. 표준을 정하는 곳에서 제공하면 공식, 코드가 공개되어 있으면 오픈 소스, 사용 방식에 따라 무료 또는 유료, 연동 방식에 따라 API와 SDK로 표시합니다. "작성자 제작" 태그가 붙은 항목은 Ciro Cesar Maciel이 만들었으며, 다른 모든 항목과 같은 기준을 따릅니다.

## 기여 방법

빠진 것, 바뀐 것, 또는 더 이상 작동하지 않는 것을 알고 계신가요? 새 항목 신청 양식으로 issue를 열거나, data/list.json을 수정한 pull request를 보내 주세요. 각 언어의 README는 이 파일에서 자동으로 생성됩니다.

[CONTRIBUTING.md](CONTRIBUTING.md)

## 다른 목록

같은 형식으로 큐레이션한 목록이며, 포르투갈어와 다른 14개 언어로 제공합니다.


## Ciro Cesar Maciel 제작

제가 만든 것을 사용해 주시는 것도 이 목록을 지지하는 방법입니다.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/pix-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/pix-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/pix-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/pix-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/pix-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/pix-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/pix-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/pix-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/pix-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/pix-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/pix-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/pix-por-agents)

## 라이선스

이 목록은 CC0 1.0 라이선스를 따릅니다. 허락을 구하지 않고 자유롭게 복사, 수정, 재배포할 수 있습니다. 생성기 코드는 awesome-kit에 있으며 MIT 라이선스입니다.

<sub>마지막 업데이트 2026-11-10.</sub>
