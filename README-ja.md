# Awesome Pix

> ブラジルのPix連携者向け：規格、API、SDK、プロバイダー、ツールを一つずつ確認済み。

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-%E8%B3%BC%E8%AA%AD-111111?style=flat-square)](https://go.mymarketing.click/pix-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/pix-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/ja.xml) ![56 件](https://img.shields.io/badge/%E4%BB%B6-56-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-6b6b6b?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

Pixで請求、受取、照合を行うシステムのための一覧です。ブラジル中央銀行が公開している情報から始まり、APIを提供するプロバイダー、QRコードを生成・読み取るオープンソースのライブラリへと続きます。掲載前にすべてのURLを開いて確認しています。

## 目次

- [規格と公式ドキュメント](#規格と公式ドキュメント)
- [仕様とオープンAPI](#仕様とオープンapi)
- [Pix APIを提供しているプロバイダー](#pix-apiを提供しているプロバイダー)
- [プロバイダー公式のSDK](#プロバイダー公式のsdk)
- [オープンソースライブラリ](#オープンソースライブラリ)
- [コミュニティの SDK](#コミュニティの-sdk)
- [データとユーティリティ](#データとユーティリティ)
- [ツール](#ツール)
- [その他のリストとコミュニティ](#その他のリストとコミュニティ)
- [タグ](#タグ)
- [貢献方法](#貢献方法)
- [他のリスト](#他のリスト)
- [作者：Ciro Cesar Maciel](#作者ciro-cesar-maciel)
- [ライセンス](#ライセンス)

## 規格と公式ドキュメント

Pixを定めているブラジル中央銀行からの情報です。

- [Pix no Banco Central](https://go.mymarketing.click/pix-pix-no-banco-central) - Pixの公式ページです。概要、仕組み、その他のリンクがあります。 `公式` `無料`
- [Normas do Pix](https://go.mymarketing.click/pix-normas-do-pix) - Pixの規則、規定、マニュアル(規則、決議、マニュアル)です。 `公式` `無料`
- [Pix Automático](https://go.mymarketing.click/pix-pix-automatico) - 一度支払人が承認した定期的な請求のためのモダリティです。 `公式` `無料`
- [Participantes do Pix](https://go.mymarketing.click/pix-participantes-do-pix) - Pixを提供している機関と、そのモダリティの一覧です。 `公式` `無料`
- [Estatísticas do Pix](https://go.mymarketing.click/pix-estatisticas-do-pix) - 取引件数、金額、キーに関する公式の数値です。 `公式` `無料`
- [Perguntas frequentes do Pix](https://go.mymarketing.click/pix-perguntas-frequentes-do-pix) - Pixを使う人からよくある質問に対するブラジル中央銀行の回答です。 `公式` `無料`

## 仕様とオープンAPI

ブラジル中央銀行がGitHubで公開しているAPIコントラクトです。

- [API Pix](https://go.mymarketing.click/pix-api-pix) - Pix APIのOpenAPI仕様です。請求と受取のためにプロバイダーが実装するものです。 `公式` `オープンソース` `API`
- [API do DICT](https://go.mymarketing.click/pix-api-do-dict) - 取引口座識別子ディレクトリ(DICT)のAPI仕様です。Pixキーはここに保存されています。 `公式` `オープンソース` `API`
- [DICT Quickstart](https://go.mymarketing.click/pix-dict-quickstart) - DICT APIを使い始めるためのガイドです。 `公式` `オープンソース`

## Pix APIを提供しているプロバイダー

Pixを連携するための公開ドキュメントを持つ銀行、決済機関、プラットフォームです。

- [Adyen](https://go.mymarketing.click/pix-adyen) - Adyenのグローバルプラットフォームで、Pixを決済手段として利用する方法です。 `API` `有料`
- [Asaas](https://go.mymarketing.click/pix-asaas) - Asaas APIのドキュメントです。Pix、ボレート、カードでの請求に対応しています。 `API` `有料`
- [Banco do Brasil](https://go.mymarketing.click/pix-banco-do-brasil) - Banco do BrasilのデベロッパーポータルでPix APIを提供しています。 `API`
- [Banco Inter](https://go.mymarketing.click/pix-banco-inter) - InterのデベロッパーポータルでPixと請求のAPIを提供しています。 `API`
- [Bradesco](https://go.mymarketing.click/pix-bradesco) - BradescoのデベロッパーポータルでPix APIを提供しています。 `API`
- [Celcoin](https://go.mymarketing.click/pix-celcoin) - 金融商品を開発する企業向けに、Pix APIを備えた決済インフラです。 `API` `有料`
- [Cora](https://go.mymarketing.click/pix-cora) - Coraの法人口座で、請求とPixのためのAPIです。 `API`
- [dLocal](https://go.mymarketing.click/pix-dlocal) - 新興市場での決済です。ブラジルではPixも利用できる決済手段の一つです。 `API` `有料`
- [EBANX](https://go.mymarketing.click/pix-ebanx) - ラテンアメリカでの現地決済です。ブラジル国外・国内の企業向けにPixを提供しています。 `API` `有料`
- [Efí](https://go.mymarketing.click/pix-efi) - Efíの Pix APIのドキュメントです。旧名Gerencianetで、請求、webhook、Pix自動決済に対応しています。 `API` `有料`
- [Itaú](https://go.mymarketing.click/pix-itau) - ItaúのデベロッパーポータルでPix APIを提供しています。 `API`
- [Iugu](https://go.mymarketing.click/pix-iugu) - Iuguの APIのドキュメントです。Pixで支払える請求とサブスクリプションに対応しています。 `API` `有料`
- [Mercado Pago](https://go.mymarketing.click/pix-mercado-pago) - Mercado PagoのCheckout APIでPixを受け取る方法です。QRコードとコピー&ペーストに対応しています。 `API` `有料`
- [OpenPix](https://go.mymarketing.click/pix-openpix) - OpenPixのドキュメントです。API、webhook、プラグインを備えたPix請求のプラットフォームです。 `API` `有料`
- [PagBank](https://go.mymarketing.click/pix-pagbank) - PagBankのデベロッパーポータルで、注文とPixによる請求を扱えます。 `API` `有料`
- [Pagar.me](https://go.mymarketing.click/pix-pagar-me) - Pagar.me APIのドキュメントです。Pix、カード、ボレートによる支払いに対応しています。 `API` `有料`
- [Santander](https://go.mymarketing.click/pix-santander) - SantanderのデベロッパーポータルでPix APIを提供しています。 `API`
- [Sicredi](https://go.mymarketing.click/pix-sicredi) - SicrediのデベロッパーポータルでPixと請求のAPIを提供しています。 `API`
- [Stripe](https://go.mymarketing.click/pix-stripe) - Stripeで、すでに請求に使っている人向けにPixを決済手段として利用する方法です。 `API` `有料`
- [Transfeera](https://go.mymarketing.click/pix-transfeera) - Pixによる支払いと受取のAPIです。照合機能を備えています。 `API` `有料`
- [Woovi](https://go.mymarketing.click/pix-woovi) - OpenPixの代わりに、Woovi のドキュメントです。Pixによる請求、サブスクリプション、webhookに対応しています。 `API` `有料`

## プロバイダー公式のSDK

API提供者が管理しているものです。

- [Efí SDK Node.js](https://go.mymarketing.click/pix-efi-sdk-node-js) - Efí APIのためのNode.js用SDKです。QRコードとコピー&ペーストによるPix請求に対応しています。 `オープンソース` `SDK`
- [Efí SDK PHP](https://go.mymarketing.click/pix-efi-sdk-php) - Efí APIのためのPHP用SDKです。QRコードとコピー&ペーストによるPix請求に対応しています。 `オープンソース` `SDK`
- [Gerencianet SDK Python](https://go.mymarketing.click/pix-gerencianet-sdk-python) - Efí APIのためのPython用SDKです。旧名Gerencianetで公開されています。 `オープンソース` `SDK`
- [Mercado Pago SDK .NET](https://go.mymarketing.click/pix-mercado-pago-sdk-net) - Mercado Pagoの公式.NET用SDKです。 `オープンソース` `SDK`
- [Mercado Pago SDK Java](https://go.mymarketing.click/pix-mercado-pago-sdk-java) - Mercado Pagoの公式Java用SDKです。 `オープンソース` `SDK`
- [Mercado Pago SDK Node.js](https://go.mymarketing.click/pix-mercado-pago-sdk-node-js) - Mercado Pago の Node.js 向け公式 SDK です。 `オープンソース` `SDK`
- [Mercado Pago SDK PHP](https://go.mymarketing.click/pix-mercado-pago-sdk-php) - Mercado Pago の PHP 向け公式 SDK です。 `オープンソース` `SDK`
- [Mercado Pago SDK Python](https://go.mymarketing.click/pix-mercado-pago-sdk-python) - Mercado Pago の Python 向け公式 SDK です。 `オープンソース` `SDK`
- [OpenPix Developers](https://go.mymarketing.click/pix-openpix-developers) - OpenPix のドキュメントのコードです。統合の例を含みます。 `オープンソース`
- [Woovi Developers](https://go.mymarketing.click/pix-woovi-developers) - Woovi のドキュメントのコードです。統合の例を含みます。 `オープンソース`

## オープンソースライブラリ

BR Code（QR Code と copia e cola の内容）を、提供元に依存せず生成・読み取り・検証します。

- [brcode](https://go.mymarketing.click/pix-brcode) - Rust で書かれた Pix の BR Code リーダーです。 `オープンソース` `無料`
- [emv-qrcode](https://go.mymarketing.click/pix-emv-qrcode) - EMV 規格の QR Code を生成・読み取る Java 製ツールです。BR Code もこの規格に従っています。 `オープンソース` `無料`
- [go-pix](https://go.mymarketing.click/pix-go-pix) - Go で書かれた、Pix の copia e cola と QR Code を生成するライブラリです。 `オープンソース` `無料`
- [php_qrcode_pix](https://go.mymarketing.click/pix-php-qrcode-pix) - PHP で Pix の QR Code を生成します。 `オープンソース` `無料`
- [PHPay](https://go.mymarketing.click/pix-phpay) - 複数の決済プロバイダーを同じインターフェースで扱える PHP ライブラリです。 `オープンソース` `無料`
- [pix-payload](https://go.mymarketing.click/pix-pix-payload) - Banco Central の仕様に従って Pix のペイロードを生成する npm パッケージです。 `オープンソース` `無料`
- [pix-utils](https://go.mymarketing.click/pix-pix-utils) - Pix コードの読み取り・生成・検証を行う TypeScript ツール群です。 `オープンソース` `無料`
- [PIX-BACEN-SDK-dotnet](https://go.mymarketing.click/pix-pix-bacen-sdk-dotnet) - Banco Central の公式仕様から生成された、.NET 向け Pix API の契約クラスです。 `オープンソース` `無料`
- [pypix](https://go.mymarketing.click/pix-pypix) - BR Code と Pix の QR Code を生成する Python ライブラリです。 `オープンソース` `無料`

## コミュニティの SDK

API の利用者が作成したもので、提供元によるものではありません。

- [asaas (TypeScript)](https://go.mymarketing.click/pix-asaas-typescript) - Asaas API のよく使われる呼び出しをまとめた TypeScript SDK です。 `オープンソース` `無料`
- [asaas-sdk (PHP)](https://go.mymarketing.click/pix-asaas-sdk-php) - Asaas API 向けの PHP SDK です。 `オープンソース` `無料`

## データとユーティリティ

検証と照合に役立つものです。

- [Bancos Brasileiros](https://go.mymarketing.click/pix-bancos-brasileiros) - コード、ISPB、名称を含むブラジルの銀行一覧です。複数の形式があります。 `オープンソース` `無料`

## ツール

コードを書かずに Pix を生成したい人向けです。

- [Gerador de QR Code Pix](https://go.mymarketing.click/pix-gerador-de-qr-code-pix) - キーから Pix の QR Code、カード型コード、リンクをブラウザ上で生成します。 `オープンソース` `無料`
- [Infrastructure Payments](https://go.mymarketing.click/pix-infrastructure-payments) - お使いのアカウントの Mercado Pago を通じて、Pix とカードで単発の請求を行います。REST、React SDK、MCP に対応しています。 `API` `作者の作成`
- [Marketing Stores](https://go.mymarketing.click/pix-marketing-stores) - Pix（QR Code と copia e cola）とカードに対応したオンラインストアです。カード決済はストア所有者の Mercado Pago で処理されます。 `API` `作者の作成`

## その他のリストとコミュニティ

以前から Pix に関する資料をまとめてきた人たちです。

- [awesome-pix (Woovi)](https://go.mymarketing.click/pix-awesome-pix-woovi) - Woovi が管理する、Pix に関する最初のリソースリストです。 `オープンソース` `無料`

## タグ

各項目には内容が書かれています。横のタグが選ぶ際の助けになります。公式は標準を定める側から提供されたもの、オープンソースはコードが公開されているもの、無料または有料は利用形態による区分です。APIとSDKは連携の方法を示します。「作者の作成」のタグが付いた項目は Ciro Cesar Maciel が作成したもので、他のすべての項目と同じ基準に従います。

## 貢献方法

不足しているもの、変更されたもの、利用できなくなったものはありますか？新規追加用のフォームからissueを開くか、data/list.jsonを編集してpull requestを送ってください。各言語のREADMEはこのファイルから生成されます。

[CONTRIBUTING.md](CONTRIBUTING.md)

## 他のリスト

同じ形式のキュレーション済みリストで、ポルトガル語のものと他の14言語のものがあります。


## 作者：Ciro Cesar Maciel

私の作品を使っていただくことも、これらのリストを応援する方法の一つです。

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/pix-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/pix-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/pix-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/pix-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/pix-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/pix-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/pix-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/pix-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/pix-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/pix-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/pix-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/pix-por-agents)

## ライセンス

このリストはCC0 1.0の下にあります。許可を求めることなく、自由にコピー、改変、再配布できます。生成ツールのコードはawesome-kitにあり、MITの下にあります。

<sub>最終更新 2026-11-10.</sub>
