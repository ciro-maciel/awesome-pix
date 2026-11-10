# Awesome Pix

> Pix для интеграторов: правила, API, SDK, провайдеры и инструменты, проверенные по одному.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-%D0%BF%D0%BE%D0%B4%D0%BF%D0%B8%D1%81%D0%B0%D1%82%D1%8C%D1%81%D1%8F-111111?style=flat-square)](https://go.mymarketing.click/pix-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/pix-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/ru.xml) ![56 элементов](https://img.shields.io/badge/%D1%8D%D0%BB%D0%B5%D0%BC%D0%B5%D0%BD%D1%82%D0%BE%D0%B2-56-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-6b6b6b?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

Для тех, кто будет принимать, получать или сверять Pix в своей системе. Начинается с того, что публикует Банковский центр Бразилии (Banco Central), затем идут провайдеры с API и заканчивается библиотеками с открытым кодом, которые создают и читают QR-код. Каждый адрес был открыт перед добавлением.

## Содержание

- [Правила и официальная документация](#правила-и-официальная-документация)
- [Спецификации и открытые API](#спецификации-и-открытые-api)
- [Провайдеры с API Pix](#провайдеры-с-api-pix)
- [Официальные SDK провайдеров](#официальные-sdk-провайдеров)
- [Библиотеки с открытым исходным кодом](#библиотеки-с-открытым-исходным-кодом)
- [SDK от сообщества](#sdk-от-сообщества)
- [Данные и утилиты](#данные-и-утилиты)
- [Инструменты](#инструменты)
- [Другие списки и сообщества](#другие-списки-и-сообщества)
- [Метки](#метки)
- [Как внести вклад](#как-внести-вклад)
- [Другие списки](#другие-списки)
- [Сделано Сиро Сезаром Маэлом](#сделано-сиро-сезаром-маэлом)
- [Лицензия](#лицензия)

## Правила и официальная документация

То, что публикует Banco Central, который задаёт Pix.

- [Pix no Banco Central](https://go.mymarketing.click/pix-pix-no-banco-central) - Официальная страница Pix: что это, как работает и ссылки на остальное. `официальное` `бесплатно`
- [Normas do Pix](https://go.mymarketing.click/pix-normas-do-pix) - Регламент, резолюции и руководства, по которым работает Pix. `официальное` `бесплатно`
- [Pix Automático](https://go.mymarketing.click/pix-pix-automatico) - Режим для повторяющихся списаний, которые плательщик одобрил один раз. `официальное` `бесплатно`
- [Participantes do Pix](https://go.mymarketing.click/pix-participantes-do-pix) - Список организаций, которые предлагают Pix, и в каком режиме. `официальное` `бесплатно`
- [Estatísticas do Pix](https://go.mymarketing.click/pix-estatisticas-do-pix) - Официальные цифры по операциям, суммам и ключам. `официальное` `бесплатно`
- [Perguntas frequentes do Pix](https://go.mymarketing.click/pix-perguntas-frequentes-do-pix) - Ответы Банко Сентрала на самые частые вопросы пользователей Pix. `официальное` `бесплатно`

## Спецификации и открытые API

Контракты API, которые Банко Сентрал публикует на GitHub.

- [API Pix](https://go.mymarketing.click/pix-api-pix) - Спецификация OpenAPI для API Pix, которую провайдеры реализуют для выставления счетов и получения платежей. `официальное` `открытый код` `API`
- [API do DICT](https://go.mymarketing.click/pix-api-do-dict) - Спецификация API Каталога идентификаторов транзакционных счетов (DICT), где хранятся ключи Pix. `официальное` `открытый код` `API`
- [DICT Quickstart](https://go.mymarketing.click/pix-dict-quickstart) - Руководство по первым шагам с API DICT. `официальное` `открытый код`

## Провайдеры с API Pix

Банки, платёжные организации и платформы с публичной документацией для интеграции Pix.

- [Adyen](https://go.mymarketing.click/pix-adyen) - Pix как способ оплаты на глобальной платформе Adyen. `API` `платно`
- [Asaas](https://go.mymarketing.click/pix-asaas) - Документация API Asaas с платежами через Pix, boleto и карту. `API` `платно`
- [Banco do Brasil](https://go.mymarketing.click/pix-banco-do-brasil) - Портал разработчиков Banco do Brasil с API Pix. `API`
- [Banco Inter](https://go.mymarketing.click/pix-banco-inter) - Портал разработчиков Inter с API Pix и выставления счетов. `API`
- [Bradesco](https://go.mymarketing.click/pix-bradesco) - Портал разработчиков Bradesco с API Pix. `API`
- [Celcoin](https://go.mymarketing.click/pix-celcoin) - Платёжная инфраструктура с API Pix для компаний, которые создают финансовые продукты. `API` `платно`
- [Cora](https://go.mymarketing.click/pix-cora) - API Cora для выставления счетов и Pix на корпоративном счёте. `API`
- [dLocal](https://go.mymarketing.click/pix-dlocal) - Платежи на развивающихся рынках, где Pix входит в число принимаемых способов в Бразилии. `API` `платно`
- [EBANX](https://go.mymarketing.click/pix-ebanx) - Локальные платежи в Латинской Америке, с Pix для иностранных и бразильских компаний. `API` `платно`
- [Efí](https://go.mymarketing.click/pix-efi) - Документация API Pix от Efí, бывшей Gerencianet, с выставлением счетов, webhook и Pix Automático. `API` `платно`
- [Itaú](https://go.mymarketing.click/pix-itau) - Портал разработчиков Itaú с API Pix. `API`
- [Iugu](https://go.mymarketing.click/pix-iugu) - Документация API Iugu с счетами и подписками, которые принимают Pix. `API` `платно`
- [Mercado Pago](https://go.mymarketing.click/pix-mercado-pago) - Как принимать Pix через Checkout API от Mercado Pago, с QR-кодом и copia e cola. `API` `платно`
- [OpenPix](https://go.mymarketing.click/pix-openpix) - Документация OpenPix, платформы для приёма платежей через Pix с API, webhook и плагинами. `API` `платно`
- [PagBank](https://go.mymarketing.click/pix-pagbank) - Портал разработчиков PagBank с заказами и платежами через Pix. `API` `платно`
- [Pagar.me](https://go.mymarketing.click/pix-pagar-me) - Документация API Pagar.me с платежами через Pix, карту и boleto. `API` `платно`
- [Santander](https://go.mymarketing.click/pix-santander) - Портал разработчиков Santander с API Pix. `API`
- [Sicredi](https://go.mymarketing.click/pix-sicredi) - Портал разработчиков Sicredi с API Pix и выставления счетов. `API`
- [Stripe](https://go.mymarketing.click/pix-stripe) - Pix как способ оплаты в Stripe, для тех, кто уже принимает платежи через неё. `API` `платно`
- [Transfeera](https://go.mymarketing.click/pix-transfeera) - API для приёма и отправки платежей через Pix с сверкой операций. `API` `платно`
- [Woovi](https://go.mymarketing.click/pix-woovi) - Документация Woovi с платежами, подписками и webhook для Pix. `API` `платно`

## Официальные SDK провайдеров

Поддерживаются теми, кто предоставляет API.

- [Efí SDK Node.js](https://go.mymarketing.click/pix-efi-sdk-node-js) - SDK на Node.js для API Efí с платежами Pix по QR-коду и copia e cola. `открытый код` `SDK`
- [Efí SDK PHP](https://go.mymarketing.click/pix-efi-sdk-php) - SDK на PHP для API Efí с платежами Pix по QR-коду и copia e cola. `открытый код` `SDK`
- [Gerencianet SDK Python](https://go.mymarketing.click/pix-gerencianet-sdk-python) - SDK на Python для API Efí, опубликованный под прежним названием Gerencianet. `открытый код` `SDK`
- [Mercado Pago SDK .NET](https://go.mymarketing.click/pix-mercado-pago-sdk-net) - Официальный SDK Mercado Pago для .NET. `открытый код` `SDK`
- [Mercado Pago SDK Java](https://go.mymarketing.click/pix-mercado-pago-sdk-java) - Официальный SDK Mercado Pago для Java. `открытый код` `SDK`
- [Mercado Pago SDK Node.js](https://go.mymarketing.click/pix-mercado-pago-sdk-node-js) - Официальный SDK Mercado Pago для Node.js. `открытый код` `SDK`
- [Mercado Pago SDK PHP](https://go.mymarketing.click/pix-mercado-pago-sdk-php) - Официальный SDK Mercado Pago для PHP. `открытый код` `SDK`
- [Mercado Pago SDK Python](https://go.mymarketing.click/pix-mercado-pago-sdk-python) - Официальный SDK Mercado Pago для Python. `открытый код` `SDK`
- [OpenPix Developers](https://go.mymarketing.click/pix-openpix-developers) - Исходный код документации OpenPix с примерами интеграции. `открытый код`
- [Woovi Developers](https://go.mymarketing.click/pix-woovi-developers) - Исходный код документации Woovi с примерами интеграции. `открытый код`

## Библиотеки с открытым исходным кодом

Для создания, чтения и проверки BR Code (содержимого QR-кода и copia e cola) без привязки к провайдеру.

- [brcode](https://go.mymarketing.click/pix-brcode) - Читалка BR Code Pix на Rust. `открытый код` `бесплатно`
- [emv-qrcode](https://go.mymarketing.click/pix-emv-qrcode) - Генератор и читалка QR-кодов в стандарте EMV на Java, стандарте, которому следует BR Code. `открытый код` `бесплатно`
- [go-pix](https://go.mymarketing.click/pix-go-pix) - Библиотека на Go для создания Pix copia e cola и QR-кода. `открытый код` `бесплатно`
- [php_qrcode_pix](https://go.mymarketing.click/pix-php-qrcode-pix) - Генерация QR-кода Pix на PHP. `открытый код` `бесплатно`
- [PHPay](https://go.mymarketing.click/pix-phpay) - Библиотека PHP для интеграции с несколькими платёжными провайдерами через один интерфейс. `открытый код` `бесплатно`
- [pix-payload](https://go.mymarketing.click/pix-pix-payload) - npm-пакет, который формирует payload Pix по стандарту Банковского центра Бразилии. `открытый код` `бесплатно`
- [pix-utils](https://go.mymarketing.click/pix-pix-utils) - Инструменты на TypeScript для чтения, создания и проверки кодов Pix. `открытый код` `бесплатно`
- [PIX-BACEN-SDK-dotnet](https://go.mymarketing.click/pix-pix-bacen-sdk-dotnet) - Контракты API Pix Банковского центра Бразилии на .NET, сгенерированные из официальной спецификации. `открытый код` `бесплатно`
- [pypix](https://go.mymarketing.click/pix-pypix) - Библиотека на Python для создания BR Code и QR-кода Pix. `открытый код` `бесплатно`

## SDK от сообщества

Сделаны пользователями API, а не провайдером.

- [asaas (TypeScript)](https://go.mymarketing.click/pix-asaas-typescript) - SDK на TypeScript, который скрывает самые частые вызовы API Asaas. `открытый код` `бесплатно`
- [asaas-sdk (PHP)](https://go.mymarketing.click/pix-asaas-sdk-php) - SDK на PHP для API Asaas. `открытый код` `бесплатно`

## Данные и утилиты

Для проверки и сверки.

- [Bancos Brasileiros](https://go.mymarketing.click/pix-bancos-brasileiros) - Список бразильских банков с кодом, ISPB и названием в разных форматах. `открытый код` `бесплатно`

## Инструменты

Для тех, кому нужно создать Pix без написания кода.

- [Gerador de QR Code Pix](https://go.mymarketing.click/pix-gerador-de-qr-code-pix) - Создаёт QR-код, табличку и ссылку Pix в браузере по ключу. `открытый код` `бесплатно`
- [Infrastructure Payments](https://go.mymarketing.click/pix-infrastructure-payments) - Разовые платежи через Pix и карту через Mercado Pago на вашем аккаунте: REST, SDK для React и MCP. `API` `от автора`
- [Marketing Stores](https://go.mymarketing.click/pix-marketing-stores) - Интернет-магазин с оплатой через Pix, с QR-кодом и copia e cola, а также картой напрямую в Mercado Pago владельца. `API` `от автора`

## Другие списки и сообщества

Те, кто уже собрал материалы о Pix.

- [awesome-pix (Woovi)](https://go.mymarketing.click/pix-awesome-pix-woovi) - Первый список ресурсов о Pix, который ведёт Woovi. `открытый код` `бесплатно`

## Метки

Каждая позиция объясняет, что это такое. Метки рядом помогают выбрать: официальное, когда это от организации, которая задаёт стандарт; открытый код, когда код опубликован; бесплатно или платно по модели использования; API и SDK по способу интеграции. Позиции с меткой "от автора" сделаны Сиро Сезаром Маэлом и подчиняются тем же правилам, что и все остальные.

## Как внести вклад

Знаете что-то, чего не хватает, что изменилось или перестало работать? Откройте issue с формой для новой записи или отправьте pull request, изменив data/list.json. README на каждом языке генерируется из этого файла.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Другие списки

Курируемые списки в том же формате, на португальском и ещё на 14 языках.


## Сделано Сиро Сезаром Маэлом

Пользоваться тем, что делаю я, — тоже способ поддержать эти списки.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/pix-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/pix-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/pix-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/pix-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/pix-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/pix-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/pix-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/pix-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/pix-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/pix-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/pix-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/pix-por-agents)

## Лицензия

Этот список распространяется по лицензии CC0 1.0: копируйте, адаптируйте и распространяйте как угодно, без разрешения. Код генератора находится в awesome-kit под лицензией MIT.

<sub>Обновлено 2026-11-10.</sub>
