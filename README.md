# Awesome Pix

> Pix para quem integra: normas, APIs, SDKs, provedores e ferramentas, conferidos um a um.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-assinar-111111?style=flat-square)](https://go.mymarketing.click/pix-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/pix-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/pt.xml) ![56 itens](https://img.shields.io/badge/itens-56-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-6b6b6b?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

Para quem vai cobrar, receber ou conciliar Pix num sistema. Começa pelo que o Banco Central publica, passa pelos provedores que oferecem API e termina nas bibliotecas de código aberto que geram e leem o QR Code. Todo endereço foi aberto antes de entrar.

## Conteúdo

- [Normas e documentação oficial](#normas-e-documentação-oficial)
- [Especificações e APIs abertas](#especificações-e-apis-abertas)
- [Provedores com API Pix](#provedores-com-api-pix)
- [SDKs oficiais dos provedores](#sdks-oficiais-dos-provedores)
- [Bibliotecas de código aberto](#bibliotecas-de-código-aberto)
- [SDKs da comunidade](#sdks-da-comunidade)
- [Dados e utilitários](#dados-e-utilitários)
- [Ferramentas](#ferramentas)
- [Outras listas e comunidades](#outras-listas-e-comunidades)
- [Etiquetas](#etiquetas)
- [Como contribuir](#como-contribuir)
- [Outras listas](#outras-listas)
- [Feito por Ciro Cesar Maciel](#feito-por-ciro-cesar-maciel)
- [Licença](#licença)

## Normas e documentação oficial

O que vem do Banco Central, que define o Pix.

- [Pix no Banco Central](https://go.mymarketing.click/pix-pix-no-banco-central) - A página oficial do Pix, com o que é, como funciona e os links para o resto. `oficial` `grátis`
- [Normas do Pix](https://go.mymarketing.click/pix-normas-do-pix) - O regulamento, as resoluções e os manuais que regem o Pix. `oficial` `grátis`
- [Pix Automático](https://go.mymarketing.click/pix-pix-automatico) - A modalidade para cobranças recorrentes autorizadas uma vez pelo pagador. `oficial` `grátis`
- [Participantes do Pix](https://go.mymarketing.click/pix-participantes-do-pix) - A lista das instituições que oferecem Pix e em que modalidade. `oficial` `grátis`
- [Estatísticas do Pix](https://go.mymarketing.click/pix-estatisticas-do-pix) - Os números oficiais de transações, valores e chaves. `oficial` `grátis`
- [Perguntas frequentes do Pix](https://go.mymarketing.click/pix-perguntas-frequentes-do-pix) - As respostas do Banco Central para as dúvidas mais comuns de quem usa Pix. `oficial` `grátis`

## Especificações e APIs abertas

Os contratos de API que o Banco Central publica no GitHub.

- [API Pix](https://go.mymarketing.click/pix-api-pix) - A especificação OpenAPI da API Pix, a que os provedores implementam para cobrança e recebimento. `oficial` `código aberto` `API`
- [API do DICT](https://go.mymarketing.click/pix-api-do-dict) - A especificação da API do Diretório de Identificadores de Contas Transacionais, onde vivem as chaves Pix. `oficial` `código aberto` `API`
- [DICT Quickstart](https://go.mymarketing.click/pix-dict-quickstart) - Um guia de primeiros passos com a API do DICT. `oficial` `código aberto`

## Provedores com API Pix

Bancos, instituições de pagamento e plataformas com documentação pública para integrar Pix.

- [Adyen](https://go.mymarketing.click/pix-adyen) - Pix como meio de pagamento na plataforma global da Adyen. `API` `pago`
- [Asaas](https://go.mymarketing.click/pix-asaas) - Documentação da API do Asaas, com cobranças por Pix, boleto e cartão. `API` `pago`
- [Banco do Brasil](https://go.mymarketing.click/pix-banco-do-brasil) - O portal de desenvolvedores do Banco do Brasil, com a API Pix. `API`
- [Banco Inter](https://go.mymarketing.click/pix-banco-inter) - O portal de desenvolvedores do Inter, com APIs de Pix e cobrança. `API`
- [Bradesco](https://go.mymarketing.click/pix-bradesco) - O portal de desenvolvedores do Bradesco, com APIs de Pix. `API`
- [Celcoin](https://go.mymarketing.click/pix-celcoin) - Infraestrutura de pagamentos com APIs de Pix para empresas que constroem produtos financeiros. `API` `pago`
- [Cora](https://go.mymarketing.click/pix-cora) - As APIs da Cora para cobrança e Pix na conta empresarial. `API`
- [dLocal](https://go.mymarketing.click/pix-dlocal) - Pagamentos em mercados emergentes, com Pix entre os meios aceitos no Brasil. `API` `pago`
- [EBANX](https://go.mymarketing.click/pix-ebanx) - Pagamentos locais na América Latina, com Pix para empresas de fora e de dentro do Brasil. `API` `pago`
- [Efí](https://go.mymarketing.click/pix-efi) - A documentação da API Pix da Efí, antiga Gerencianet, com cobrança, webhook e Pix Automático. `API` `pago`
- [Itaú](https://go.mymarketing.click/pix-itau) - O portal de desenvolvedores do Itaú, com APIs de Pix. `API`
- [Iugu](https://go.mymarketing.click/pix-iugu) - Documentação da API da Iugu, com cobranças e assinaturas que aceitam Pix. `API` `pago`
- [Mercado Pago](https://go.mymarketing.click/pix-mercado-pago) - Como receber Pix pelo Checkout API do Mercado Pago, com QR Code e copia e cola. `API` `pago`
- [OpenPix](https://go.mymarketing.click/pix-openpix) - A documentação da OpenPix, plataforma de cobranças por Pix com API, webhooks e plugins. `API` `pago`
- [PagBank](https://go.mymarketing.click/pix-pagbank) - O portal de desenvolvedores do PagBank, com pedidos e cobranças por Pix. `API` `pago`
- [Pagar.me](https://go.mymarketing.click/pix-pagar-me) - Documentação da API do Pagar.me, com pagamentos por Pix, cartão e boleto. `API` `pago`
- [Santander](https://go.mymarketing.click/pix-santander) - O portal de desenvolvedores do Santander, com APIs de Pix. `API`
- [Sicredi](https://go.mymarketing.click/pix-sicredi) - O portal de desenvolvedores do Sicredi, com APIs de Pix e cobrança. `API`
- [Stripe](https://go.mymarketing.click/pix-stripe) - Pix como meio de pagamento na Stripe, para quem já cobra por ela. `API` `pago`
- [Transfeera](https://go.mymarketing.click/pix-transfeera) - APIs de pagamento e recebimento por Pix, com conciliação. `API` `pago`
- [Woovi](https://go.mymarketing.click/pix-woovi) - A documentação da Woovi, com cobranças, assinaturas e webhooks por Pix. `API` `pago`

## SDKs oficiais dos provedores

Mantidos por quem oferece a API.

- [Efí SDK Node.js](https://go.mymarketing.click/pix-efi-sdk-node-js) - SDK em Node.js para as APIs da Efí, com cobranças Pix por QR Code e copia e cola. `código aberto` `SDK`
- [Efí SDK PHP](https://go.mymarketing.click/pix-efi-sdk-php) - SDK em PHP para as APIs da Efí, com cobranças Pix por QR Code e copia e cola. `código aberto` `SDK`
- [Gerencianet SDK Python](https://go.mymarketing.click/pix-gerencianet-sdk-python) - SDK em Python para a API da Efí, publicado com o nome antigo Gerencianet. `código aberto` `SDK`
- [Mercado Pago SDK .NET](https://go.mymarketing.click/pix-mercado-pago-sdk-net) - O SDK oficial do Mercado Pago para .NET. `código aberto` `SDK`
- [Mercado Pago SDK Java](https://go.mymarketing.click/pix-mercado-pago-sdk-java) - O SDK oficial do Mercado Pago para Java. `código aberto` `SDK`
- [Mercado Pago SDK Node.js](https://go.mymarketing.click/pix-mercado-pago-sdk-node-js) - O SDK oficial do Mercado Pago para Node.js. `código aberto` `SDK`
- [Mercado Pago SDK PHP](https://go.mymarketing.click/pix-mercado-pago-sdk-php) - O SDK oficial do Mercado Pago para PHP. `código aberto` `SDK`
- [Mercado Pago SDK Python](https://go.mymarketing.click/pix-mercado-pago-sdk-python) - O SDK oficial do Mercado Pago para Python. `código aberto` `SDK`
- [OpenPix Developers](https://go.mymarketing.click/pix-openpix-developers) - O código da documentação da OpenPix, com exemplos de integração. `código aberto`
- [Woovi Developers](https://go.mymarketing.click/pix-woovi-developers) - O código da documentação da Woovi, com exemplos de integração. `código aberto`

## Bibliotecas de código aberto

Para gerar, ler e validar o BR Code (o conteúdo do QR Code e do copia e cola) sem depender de provedor.

- [brcode](https://go.mymarketing.click/pix-brcode) - Leitor de BR Code do Pix em Rust. `código aberto` `grátis`
- [emv-qrcode](https://go.mymarketing.click/pix-emv-qrcode) - Gerador e leitor de QR Code no padrão EMV em Java, o padrão que o BR Code segue. `código aberto` `grátis`
- [go-pix](https://go.mymarketing.click/pix-go-pix) - Biblioteca em Go para gerar o Pix copia e cola e o QR Code. `código aberto` `grátis`
- [php_qrcode_pix](https://go.mymarketing.click/pix-php-qrcode-pix) - Geração do QR Code do Pix em PHP. `código aberto` `grátis`
- [PHPay](https://go.mymarketing.click/pix-phpay) - Biblioteca PHP para integrar vários provedores de pagamento com a mesma interface. `código aberto` `grátis`
- [pix-payload](https://go.mymarketing.click/pix-pix-payload) - Pacote npm que gera o payload do Pix seguindo o padrão do Banco Central. `código aberto` `grátis`
- [pix-utils](https://go.mymarketing.click/pix-pix-utils) - Ferramentas em TypeScript para ler, gerar e validar códigos Pix. `código aberto` `grátis`
- [PIX-BACEN-SDK-dotnet](https://go.mymarketing.click/pix-pix-bacen-sdk-dotnet) - Os contratos da API Pix do Banco Central em .NET, gerados da especificação oficial. `código aberto` `grátis`
- [pypix](https://go.mymarketing.click/pix-pypix) - Biblioteca em Python para gerar o BR Code e o QR Code do Pix. `código aberto` `grátis`

## SDKs da comunidade

Feitos por quem usa a API, não pelo provedor.

- [asaas (TypeScript)](https://go.mymarketing.click/pix-asaas-typescript) - SDK em TypeScript que abstrai as chamadas mais usadas da API do Asaas. `código aberto` `grátis`
- [asaas-sdk (PHP)](https://go.mymarketing.click/pix-asaas-sdk-php) - SDK em PHP para a API do Asaas. `código aberto` `grátis`

## Dados e utilitários

O que ajuda a validar e conciliar.

- [Bancos Brasileiros](https://go.mymarketing.click/pix-bancos-brasileiros) - A lista dos bancos brasileiros com código, ISPB e nome, em vários formatos. `código aberto` `grátis`

## Ferramentas

Para quem precisa gerar um Pix sem escrever código.

- [Gerador de QR Code Pix](https://go.mymarketing.click/pix-gerador-de-qr-code-pix) - Gera QR Code, placa e link de Pix no navegador a partir da chave. `código aberto` `grátis`
- [Infrastructure Payments](https://go.mymarketing.click/pix-infrastructure-payments) - Cobrança avulsa por Pix e cartão pelo Mercado Pago da sua conta, com REST, SDK React e MCP. `API` `do autor`
- [Marketing Stores](https://go.mymarketing.click/pix-marketing-stores) - Loja online com pagamento por Pix, com QR Code e copia e cola, e cartão direto no Mercado Pago do dono. `API` `do autor`

## Outras listas e comunidades

Quem já reuniu material sobre Pix antes.

- [awesome-pix (Woovi)](https://go.mymarketing.click/pix-awesome-pix-woovi) - A primeira lista de recursos sobre Pix, mantida pela Woovi. `código aberto` `grátis`

## Etiquetas

Cada item diz o que é. As etiquetas ao lado ajudam a escolher: oficial quando vem de quem define o padrão, código aberto quando o código está publicado, grátis ou pago pelo modelo de uso, API e SDK pelo jeito de integrar. Os itens com a etiqueta "do autor" são feitos por Ciro Cesar Maciel e seguem as mesmas regras de todos os outros.

## Como contribuir

Conhece algo que falta, mudou ou saiu do ar? Abra uma issue com o formulário de nova inclusão ou mande um pull request editando data/list.json. O README de cada língua é gerado a partir desse arquivo.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Outras listas

Listas curadas no mesmo formato, em português e em mais 14 línguas.


## Feito por Ciro Cesar Maciel

Usar o que eu faço também é um jeito de apoiar estas listas.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/pix-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/pix-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/pix-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/pix-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/pix-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/pix-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/pix-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/pix-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/pix-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/pix-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/pix-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/pix-por-agents)

## Licença

Esta lista está sob CC0 1.0: copie, adapte e redistribua como quiser, sem pedir permissão. O código do gerador está no awesome-kit, sob MIT.

<sub>Atualizada em 2026-11-10.</sub>
