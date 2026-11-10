# Awesome Pix

> Pix para quienes integran: normas, APIs, SDKs, proveedores y herramientas, revisados uno por uno.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-suscribirse-111111?style=flat-square)](https://go.mymarketing.click/pix-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/pix-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/es.xml) ![56 elementos](https://img.shields.io/badge/elementos-56-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-6b6b6b?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

Para quien va a cobrar, recibir o conciliar Pix en un sistema. Empieza por lo que publica el Banco Central, pasa por los proveedores que ofrecen API y termina en las bibliotecas de código abierto que generan y leen el QR Code. Cada dirección fue abierta antes de entrar.

## Contenido

- [Normas y documentación oficial](#normas-y-documentación-oficial)
- [Especificaciones y APIs abiertas](#especificaciones-y-apis-abiertas)
- [Proveedores con API Pix](#proveedores-con-api-pix)
- [SDK oficiales de los proveedores](#sdk-oficiales-de-los-proveedores)
- [Bibliotecas de código abierto](#bibliotecas-de-código-abierto)
- [SDKs de la comunidad](#sdks-de-la-comunidad)
- [Datos y utilidades](#datos-y-utilidades)
- [Herramientas](#herramientas)
- [Otras listas y comunidades](#otras-listas-y-comunidades)
- [Etiquetas](#etiquetas)
- [Cómo contribuir](#cómo-contribuir)
- [Otras listas](#otras-listas)
- [Hecho por Ciro Cesar Maciel](#hecho-por-ciro-cesar-maciel)
- [Licencia](#licencia)

## Normas y documentación oficial

Lo que publica el Banco Central, que define el Pix.

- [Pix no Banco Central](https://go.mymarketing.click/pix-pix-no-banco-central) - La página oficial del Pix, con qué es, cómo funciona y los enlaces al resto. `oficial` `gratis`
- [Normas do Pix](https://go.mymarketing.click/pix-normas-do-pix) - El reglamento, las resoluciones y los manuales que rigen el Pix. `oficial` `gratis`
- [Pix Automático](https://go.mymarketing.click/pix-pix-automatico) - La modalidad para cobros recurrentes autorizados una vez por el pagador. `oficial` `gratis`
- [Participantes do Pix](https://go.mymarketing.click/pix-participantes-do-pix) - La lista de instituciones que ofrecen Pix y en qué modalidad. `oficial` `gratis`
- [Estatísticas do Pix](https://go.mymarketing.click/pix-estatisticas-do-pix) - Los números oficiales de transacciones, montos y claves. `oficial` `gratis`
- [Perguntas frequentes do Pix](https://go.mymarketing.click/pix-perguntas-frequentes-do-pix) - Las respuestas del Banco Central a las dudas más comunes de quien usa Pix. `oficial` `gratis`

## Especificaciones y APIs abiertas

Los contratos de API que el Banco Central publica en GitHub.

- [API Pix](https://go.mymarketing.click/pix-api-pix) - La especificación OpenAPI de la API Pix, que los proveedores implementan para cobros y recepción. `oficial` `código abierto` `API`
- [API do DICT](https://go.mymarketing.click/pix-api-do-dict) - La especificación de la API del Directorio de Identificadores de Cuentas Transaccionales, donde viven las claves Pix. `oficial` `código abierto` `API`
- [DICT Quickstart](https://go.mymarketing.click/pix-dict-quickstart) - Una guía de primeros pasos con la API del DICT. `oficial` `código abierto`

## Proveedores con API Pix

Bancos, instituciones de pago y plataformas con documentación pública para integrar Pix.

- [Adyen](https://go.mymarketing.click/pix-adyen) - Pix como medio de pago en la plataforma global de Adyen. `API` `de pago`
- [Asaas](https://go.mymarketing.click/pix-asaas) - Documentación de la API de Asaas, con cobros por Pix, boleto y tarjeta. `API` `de pago`
- [Banco do Brasil](https://go.mymarketing.click/pix-banco-do-brasil) - El portal de desarrolladores del Banco do Brasil, con la API Pix. `API`
- [Banco Inter](https://go.mymarketing.click/pix-banco-inter) - El portal de desarrolladores de Inter, con APIs de Pix y cobro. `API`
- [Bradesco](https://go.mymarketing.click/pix-bradesco) - El portal de desarrolladores de Bradesco, con APIs de Pix. `API`
- [Celcoin](https://go.mymarketing.click/pix-celcoin) - Infraestructura de pagos con APIs de Pix para empresas que crean productos financieros. `API` `de pago`
- [Cora](https://go.mymarketing.click/pix-cora) - Las APIs de Cora para cobros y Pix en la cuenta empresarial. `API`
- [dLocal](https://go.mymarketing.click/pix-dlocal) - Pagos en mercados emergentes, con Pix entre los medios aceptados en Brasil. `API` `de pago`
- [EBANX](https://go.mymarketing.click/pix-ebanx) - Pagos locales en América Latina, con Pix para empresas de fuera y de dentro de Brasil. `API` `de pago`
- [Efí](https://go.mymarketing.click/pix-efi) - La documentación de la API Pix de Efí, antes Gerencianet, con cobro, webhook y Pix Automático. `API` `de pago`
- [Itaú](https://go.mymarketing.click/pix-itau) - El portal de desarrolladores de Itaú, con APIs de Pix. `API`
- [Iugu](https://go.mymarketing.click/pix-iugu) - Documentación de la API de Iugu, con cobros y suscripciones que aceptan Pix. `API` `de pago`
- [Mercado Pago](https://go.mymarketing.click/pix-mercado-pago) - Cómo recibir Pix con la Checkout API de Mercado Pago, con código QR y copia y pega. `API` `de pago`
- [OpenPix](https://go.mymarketing.click/pix-openpix) - La documentación de OpenPix, plataforma de cobros por Pix con API, webhooks y plugins. `API` `de pago`
- [PagBank](https://go.mymarketing.click/pix-pagbank) - El portal de desarrolladores de PagBank, con pedidos y cobros por Pix. `API` `de pago`
- [Pagar.me](https://go.mymarketing.click/pix-pagar-me) - Documentación de la API de Pagar.me, con pagos por Pix, tarjeta y boleto. `API` `de pago`
- [Santander](https://go.mymarketing.click/pix-santander) - El portal de desarrolladores de Santander, con APIs de Pix. `API`
- [Sicredi](https://go.mymarketing.click/pix-sicredi) - El portal de desarrolladores de Sicredi, con APIs de Pix y cobro. `API`
- [Stripe](https://go.mymarketing.click/pix-stripe) - Pix como medio de pago en Stripe, para quien ya cobra con ella. `API` `de pago`
- [Transfeera](https://go.mymarketing.click/pix-transfeera) - APIs de pago y recepción por Pix, con conciliación. `API` `de pago`
- [Woovi](https://go.mymarketing.click/pix-woovi) - La documentación de Woovi, con cobros, suscripciones y webhooks por Pix. `API` `de pago`

## SDK oficiales de los proveedores

Mantenidos por quien ofrece la API.

- [Efí SDK Node.js](https://go.mymarketing.click/pix-efi-sdk-node-js) - SDK en Node.js para las APIs de Efí, con cobros Pix por código QR y copia y pega. `código abierto` `SDK`
- [Efí SDK PHP](https://go.mymarketing.click/pix-efi-sdk-php) - SDK en PHP para las APIs de Efí, con cobros Pix por código QR y copia y pega. `código abierto` `SDK`
- [Gerencianet SDK Python](https://go.mymarketing.click/pix-gerencianet-sdk-python) - SDK en Python para la API de Efí, publicado con el nombre antiguo Gerencianet. `código abierto` `SDK`
- [Mercado Pago SDK .NET](https://go.mymarketing.click/pix-mercado-pago-sdk-net) - El SDK oficial de Mercado Pago para .NET. `código abierto` `SDK`
- [Mercado Pago SDK Java](https://go.mymarketing.click/pix-mercado-pago-sdk-java) - El SDK oficial de Mercado Pago para Java. `código abierto` `SDK`
- [Mercado Pago SDK Node.js](https://go.mymarketing.click/pix-mercado-pago-sdk-node-js) - El SDK oficial de Mercado Pago para Node.js. `código abierto` `SDK`
- [Mercado Pago SDK PHP](https://go.mymarketing.click/pix-mercado-pago-sdk-php) - El SDK oficial de Mercado Pago para PHP. `código abierto` `SDK`
- [Mercado Pago SDK Python](https://go.mymarketing.click/pix-mercado-pago-sdk-python) - El SDK oficial de Mercado Pago para Python. `código abierto` `SDK`
- [OpenPix Developers](https://go.mymarketing.click/pix-openpix-developers) - El código de la documentación de OpenPix, con ejemplos de integración. `código abierto`
- [Woovi Developers](https://go.mymarketing.click/pix-woovi-developers) - El código de la documentación de Woovi, con ejemplos de integración. `código abierto`

## Bibliotecas de código abierto

Para generar, leer y validar el BR Code (el contenido del QR Code y del copia y pega) sin depender de un proveedor.

- [brcode](https://go.mymarketing.click/pix-brcode) - Lector de BR Code de Pix en Rust. `código abierto` `gratis`
- [emv-qrcode](https://go.mymarketing.click/pix-emv-qrcode) - Generador y lector de QR Code en el estándar EMV en Java, el estándar que sigue el BR Code. `código abierto` `gratis`
- [go-pix](https://go.mymarketing.click/pix-go-pix) - Biblioteca en Go para generar el copia y pega de Pix y el QR Code. `código abierto` `gratis`
- [php_qrcode_pix](https://go.mymarketing.click/pix-php-qrcode-pix) - Generación del QR Code de Pix en PHP. `código abierto` `gratis`
- [PHPay](https://go.mymarketing.click/pix-phpay) - Biblioteca PHP para integrar varios proveedores de pago con la misma interfaz. `código abierto` `gratis`
- [pix-payload](https://go.mymarketing.click/pix-pix-payload) - Paquete npm que genera el payload de Pix siguiendo el estándar del Banco Central. `código abierto` `gratis`
- [pix-utils](https://go.mymarketing.click/pix-pix-utils) - Herramientas en TypeScript para leer, generar y validar códigos Pix. `código abierto` `gratis`
- [PIX-BACEN-SDK-dotnet](https://go.mymarketing.click/pix-pix-bacen-sdk-dotnet) - Los contratos de la API Pix del Banco Central en .NET, generados a partir de la especificación oficial. `código abierto` `gratis`
- [pypix](https://go.mymarketing.click/pix-pypix) - Biblioteca en Python para generar el BR Code y el QR Code de Pix. `código abierto` `gratis`

## SDKs de la comunidad

Hechos por quienes usan la API, no por el proveedor.

- [asaas (TypeScript)](https://go.mymarketing.click/pix-asaas-typescript) - SDK en TypeScript que abstrae las llamadas más usadas de la API de Asaas. `código abierto` `gratis`
- [asaas-sdk (PHP)](https://go.mymarketing.click/pix-asaas-sdk-php) - SDK en PHP para la API de Asaas. `código abierto` `gratis`

## Datos y utilidades

Lo que ayuda a validar y conciliar.

- [Bancos Brasileiros](https://go.mymarketing.click/pix-bancos-brasileiros) - La lista de los bancos brasileños con código, ISPB y nombre, en varios formatos. `código abierto` `gratis`

## Herramientas

Para quien necesita generar un Pix sin escribir código.

- [Gerador de QR Code Pix](https://go.mymarketing.click/pix-gerador-de-qr-code-pix) - Genera QR Code, placa y enlace de Pix en el navegador a partir de la clave. `código abierto` `gratis`
- [Infrastructure Payments](https://go.mymarketing.click/pix-infrastructure-payments) - Cobro suelto por Pix y tarjeta a través de Mercado Pago de tu cuenta, con REST, SDK de React y MCP. `API` `del autor`
- [Marketing Stores](https://go.mymarketing.click/pix-marketing-stores) - Tienda en línea con pago por Pix, con QR Code y copia y pega, y tarjeta directamente en el Mercado Pago del dueño. `API` `del autor`

## Otras listas y comunidades

Quienes ya reunieron material sobre Pix antes.

- [awesome-pix (Woovi)](https://go.mymarketing.click/pix-awesome-pix-woovi) - La primera lista de recursos sobre Pix, mantenida por Woovi. `código abierto` `gratis`

## Etiquetas

Cada ítem dice qué es. Las etiquetas al lado ayudan a elegir: oficial cuando viene de quien define el estándar, código abierto cuando el código está publicado, gratis o de pago según el modelo de uso, API y SDK según la forma de integrar. Los ítems con la etiqueta "del autor" son hechos por Ciro Cesar Maciel y siguen las mismas reglas que todos los demás.

## Cómo contribuir

¿Conoces algo que falte, haya cambiado o ya no funcione? Abre un issue con el formulario de nueva inclusión o envía un pull request editando data/list.json. El README de cada idioma se genera a partir de ese archivo.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Otras listas

Listas curadas con el mismo formato, en portugués y en otros 14 idiomas.


## Hecho por Ciro Cesar Maciel

Usar lo que hago también es una forma de apoyar estas listas.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/pix-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/pix-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/pix-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/pix-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/pix-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/pix-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/pix-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/pix-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/pix-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/pix-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/pix-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/pix-por-agents)

## Licencia

Esta lista está bajo CC0 1.0: copia, adapta y redistribuye como quieras, sin pedir permiso. El código del generador está en awesome-kit, bajo MIT.

<sub>Actualizada el 2026-11-10.</sub>
