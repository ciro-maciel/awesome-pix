# Awesome Pix

> Pix untuk pengembang integrasi: aturan, API, SDK, penyedia, dan alat, diperiksa satu per satu.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-berlangganan-111111?style=flat-square)](https://go.mymarketing.click/pix-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/pix-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/id.xml) ![56 item](https://img.shields.io/badge/item-56-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-6b6b6b?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

Untuk yang akan menagih, menerima, atau merekonsiliasi Pix di sistem. Dimulai dari yang diterbitkan Banco Central, lanjut ke penyedia yang menawarkan API, dan diakhiri dengan pustaka open source yang membuat dan membaca QR Code. Setiap tautan dibuka dulu sebelum masuk daftar.

## Konten

- [Aturan dan dokumentasi resmi](#aturan-dan-dokumentasi-resmi)
- [Spesifikasi dan API terbuka](#spesifikasi-dan-api-terbuka)
- [Penyedia dengan API Pix](#penyedia-dengan-api-pix)
- [SDK resmi dari penyedia](#sdk-resmi-dari-penyedia)
- [Pustaka open source](#pustaka-open-source)
- [SDK buatan komunitas](#sdk-buatan-komunitas)
- [Data dan utilitas](#data-dan-utilitas)
- [Alat](#alat)
- [Daftar lain dan komunitas](#daftar-lain-dan-komunitas)
- [Label](#label)
- [Cara berkontribusi](#cara-berkontribusi)
- [Daftar lainnya](#daftar-lainnya)
- [Dibuat oleh Ciro Cesar Maciel](#dibuat-oleh-ciro-cesar-maciel)
- [Lisensi](#lisensi)

## Aturan dan dokumentasi resmi

Yang diterbitkan Banco Central, yang menetapkan Pix.

- [Pix no Banco Central](https://go.mymarketing.click/pix-pix-no-banco-central) - Halaman resmi Pix, berisi penjelasan apa itu, cara kerjanya, dan tautan ke bagian lainnya. `resmi` `gratis`
- [Normas do Pix](https://go.mymarketing.click/pix-normas-do-pix) - Peraturan, resolusi, dan panduan yang mengatur Pix. `resmi` `gratis`
- [Pix Automático](https://go.mymarketing.click/pix-pix-automatico) - Modalitas untuk tagihan berulang yang disetujui sekali oleh pembayar. `resmi` `gratis`
- [Participantes do Pix](https://go.mymarketing.click/pix-participantes-do-pix) - Daftar institusi yang menawarkan Pix dan modalitasnya. `resmi` `gratis`
- [Estatísticas do Pix](https://go.mymarketing.click/pix-estatisticas-do-pix) - Angka resmi transaksi, nilai, dan kunci. `resmi` `gratis`
- [Perguntas frequentes do Pix](https://go.mymarketing.click/pix-perguntas-frequentes-do-pix) - Jawaban Banco Central untuk pertanyaan paling umum dari pengguna Pix. `resmi` `gratis`

## Spesifikasi dan API terbuka

Kontrak API yang dipublikasikan Banco Central di GitHub.

- [API Pix](https://go.mymarketing.click/pix-api-pix) - Spesifikasi OpenAPI untuk API Pix, yang diimplementasikan penyedia layanan untuk penagihan dan penerimaan. `resmi` `open source` `API`
- [API do DICT](https://go.mymarketing.click/pix-api-do-dict) - Spesifikasi API Direktori Pengenal Akun Transaksional, tempat kunci Pix disimpan. `resmi` `open source` `API`
- [DICT Quickstart](https://go.mymarketing.click/pix-dict-quickstart) - Panduan memulai dengan API DICT. `resmi` `open source`

## Penyedia dengan API Pix

Bank, lembaga pembayaran, dan platform dengan dokumentasi publik untuk integrasi Pix.

- [Adyen](https://go.mymarketing.click/pix-adyen) - Pix sebagai metode pembayaran di platform global Adyen. `API` `berbayar`
- [Asaas](https://go.mymarketing.click/pix-asaas) - Dokumentasi API Asaas, dengan penagihan melalui Pix, boleto, dan kartu. `API` `berbayar`
- [Banco do Brasil](https://go.mymarketing.click/pix-banco-do-brasil) - Portal pengembang Banco do Brasil, dengan API Pix. `API`
- [Banco Inter](https://go.mymarketing.click/pix-banco-inter) - Portal pengembang Inter, dengan API Pix dan penagihan. `API`
- [Bradesco](https://go.mymarketing.click/pix-bradesco) - Portal pengembang Bradesco, dengan API Pix. `API`
- [Celcoin](https://go.mymarketing.click/pix-celcoin) - Infrastruktur pembayaran dengan API Pix untuk perusahaan yang membangun produk keuangan. `API` `berbayar`
- [Cora](https://go.mymarketing.click/pix-cora) - API Cora untuk penagihan dan Pix di akun bisnis. `API`
- [dLocal](https://go.mymarketing.click/pix-dlocal) - Pembayaran di pasar negara berkembang, dengan Pix termasuk metode yang diterima di Brasil. `API` `berbayar`
- [EBANX](https://go.mymarketing.click/pix-ebanx) - Pembayaran lokal di Amerika Latin, dengan Pix untuk perusahaan dari luar maupun dalam Brasil. `API` `berbayar`
- [Efí](https://go.mymarketing.click/pix-efi) - Dokumentasi API Pix Efí, dulunya Gerencianet, dengan penagihan, webhook, dan Pix Automático. `API` `berbayar`
- [Itaú](https://go.mymarketing.click/pix-itau) - Portal pengembang Itaú, dengan API Pix. `API`
- [Iugu](https://go.mymarketing.click/pix-iugu) - Dokumentasi API Iugu, dengan tagihan dan langganan yang menerima Pix. `API` `berbayar`
- [Mercado Pago](https://go.mymarketing.click/pix-mercado-pago) - Cara menerima Pix melalui Checkout API Mercado Pago, dengan QR Code dan copia e cola. `API` `berbayar`
- [OpenPix](https://go.mymarketing.click/pix-openpix) - Dokumentasi OpenPix, platform tagihan Pix dengan API, webhook, dan plugin. `API` `berbayar`
- [PagBank](https://go.mymarketing.click/pix-pagbank) - Portal pengembang PagBank, dengan pesanan dan tagihan melalui Pix. `API` `berbayar`
- [Pagar.me](https://go.mymarketing.click/pix-pagar-me) - Dokumentasi API Pagar.me, dengan pembayaran melalui Pix, kartu, dan boleto. `API` `berbayar`
- [Santander](https://go.mymarketing.click/pix-santander) - Portal pengembang Santander, dengan API Pix. `API`
- [Sicredi](https://go.mymarketing.click/pix-sicredi) - Portal pengembang Sicredi, dengan API Pix dan penagihan. `API`
- [Stripe](https://go.mymarketing.click/pix-stripe) - Pix sebagai metode pembayaran di Stripe, bagi yang sudah menagih lewat Stripe. `API` `berbayar`
- [Transfeera](https://go.mymarketing.click/pix-transfeera) - API untuk pembayaran dan penerimaan Pix, dengan rekonsiliasi. `API` `berbayar`
- [Woovi](https://go.mymarketing.click/pix-woovi) - Dokumentasi Woovi, dengan tagihan, langganan, dan webhook Pix. `API` `berbayar`

## SDK resmi dari penyedia

Dikelola oleh pihak yang menyediakan API.

- [Efí SDK Node.js](https://go.mymarketing.click/pix-efi-sdk-node-js) - SDK Node.js untuk API Efí, dengan tagihan Pix melalui QR Code dan copia e cola. `open source` `SDK`
- [Efí SDK PHP](https://go.mymarketing.click/pix-efi-sdk-php) - SDK PHP untuk API Efí, dengan tagihan Pix melalui QR Code dan copia e cola. `open source` `SDK`
- [Gerencianet SDK Python](https://go.mymarketing.click/pix-gerencianet-sdk-python) - SDK Python untuk API Efí, dirilis dengan nama lama Gerencianet. `open source` `SDK`
- [Mercado Pago SDK .NET](https://go.mymarketing.click/pix-mercado-pago-sdk-net) - SDK resmi Mercado Pago untuk .NET. `open source` `SDK`
- [Mercado Pago SDK Java](https://go.mymarketing.click/pix-mercado-pago-sdk-java) - SDK resmi Mercado Pago untuk Java. `open source` `SDK`
- [Mercado Pago SDK Node.js](https://go.mymarketing.click/pix-mercado-pago-sdk-node-js) - SDK resmi Mercado Pago untuk Node.js. `open source` `SDK`
- [Mercado Pago SDK PHP](https://go.mymarketing.click/pix-mercado-pago-sdk-php) - SDK resmi Mercado Pago untuk PHP. `open source` `SDK`
- [Mercado Pago SDK Python](https://go.mymarketing.click/pix-mercado-pago-sdk-python) - SDK resmi Mercado Pago untuk Python. `open source` `SDK`
- [OpenPix Developers](https://go.mymarketing.click/pix-openpix-developers) - Kode dokumentasi OpenPix, dengan contoh integrasi. `open source`
- [Woovi Developers](https://go.mymarketing.click/pix-woovi-developers) - Kode dokumentasi Woovi, dengan contoh integrasi. `open source`

## Pustaka open source

Untuk membuat, membaca, dan memvalidasi BR Code (isi QR Code dan copia e cola) tanpa bergantung pada penyedia.

- [brcode](https://go.mymarketing.click/pix-brcode) - Pembaca BR Code Pix dalam Rust. `open source` `gratis`
- [emv-qrcode](https://go.mymarketing.click/pix-emv-qrcode) - Pembuat dan pembaca QR Code standar EMV dalam Java, standar yang diikuti BR Code. `open source` `gratis`
- [go-pix](https://go.mymarketing.click/pix-go-pix) - Pustaka Go untuk membuat Pix copia e cola dan QR Code. `open source` `gratis`
- [php_qrcode_pix](https://go.mymarketing.click/pix-php-qrcode-pix) - Pembuatan QR Code Pix dalam PHP. `open source` `gratis`
- [PHPay](https://go.mymarketing.click/pix-phpay) - Pustaka PHP untuk mengintegrasikan banyak penyedia pembayaran dengan antarmuka yang sama. `open source` `gratis`
- [pix-payload](https://go.mymarketing.click/pix-pix-payload) - Paket npm yang membuat payload Pix sesuai standar Banco Central. `open source` `gratis`
- [pix-utils](https://go.mymarketing.click/pix-pix-utils) - Alat TypeScript untuk membaca, membuat, dan memvalidasi kode Pix. `open source` `gratis`
- [PIX-BACEN-SDK-dotnet](https://go.mymarketing.click/pix-pix-bacen-sdk-dotnet) - Kontrak API Pix Banco Central dalam .NET, dibuat dari spesifikasi resmi. `open source` `gratis`
- [pypix](https://go.mymarketing.click/pix-pypix) - Pustaka Python untuk membuat BR Code dan QR Code Pix. `open source` `gratis`

## SDK buatan komunitas

Dibuat oleh pengguna API, bukan oleh penyedia.

- [asaas (TypeScript)](https://go.mymarketing.click/pix-asaas-typescript) - SDK TypeScript yang menyederhanakan panggilan API Asaas yang paling sering dipakai. `open source` `gratis`
- [asaas-sdk (PHP)](https://go.mymarketing.click/pix-asaas-sdk-php) - SDK PHP untuk API Asaas. `open source` `gratis`

## Data dan utilitas

Yang membantu validasi dan rekonsiliasi.

- [Bancos Brasileiros](https://go.mymarketing.click/pix-bancos-brasileiros) - Daftar bank Brasil dengan kode, ISPB, dan nama, dalam berbagai format. `open source` `gratis`

## Alat

Untuk yang perlu membuat Pix tanpa menulis kode.

- [Gerador de QR Code Pix](https://go.mymarketing.click/pix-gerador-de-qr-code-pix) - Membuat QR Code, placa, dan tautan Pix di browser dari kunci. `open source` `gratis`
- [Infrastructure Payments](https://go.mymarketing.click/pix-infrastructure-payments) - Penagihan satuan lewat Pix dan kartu melalui Mercado Pago akun Anda, dengan REST, SDK React, dan MCP. `API` `buatan penulis`
- [Marketing Stores](https://go.mymarketing.click/pix-marketing-stores) - Toko online dengan pembayaran Pix, QR Code, dan copia e cola, serta kartu langsung ke Mercado Pago pemilik. `API` `buatan penulis`

## Daftar lain dan komunitas

Untuk yang sudah pernah mengumpulkan materi tentang Pix.

- [awesome-pix (Woovi)](https://go.mymarketing.click/pix-awesome-pix-woovi) - Daftar sumber daya Pix pertama, dikelola oleh Woovi. `open source` `gratis`

## Label

Setiap item menjelaskan apa itu. Label di sebelahnya membantu memilih: resmi jika berasal dari pihak yang menetapkan standar, open source jika kodenya dipublikasikan, gratis atau berbayar menurut model penggunaannya, dan API serta SDK menurut cara integrasinya. Item dengan label "buatan penulis" dibuat oleh Ciro Cesar Maciel dan mengikuti aturan yang sama dengan item lainnya.

## Cara berkontribusi

Tahu sesuatu yang kurang, berubah, atau sudah tidak aktif? Buka issue dengan formulir penambahan baru atau kirim pull request dengan mengedit data/list.json. README tiap bahasa dibuat dari berkas ini.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Daftar lainnya

Daftar kurasi dengan format yang sama, dalam bahasa Portugis dan 14 bahasa lainnya.


## Dibuat oleh Ciro Cesar Maciel

Menggunakan karya saya juga merupakan cara mendukung daftar ini.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/pix-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/pix-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/pix-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/pix-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/pix-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/pix-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/pix-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/pix-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/pix-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/pix-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/pix-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/pix-por-agents)

## Lisensi

Daftar ini berada di bawah CC0 1.0: salin, adaptasi, dan sebarkan sesuka Anda, tanpa perlu izin. Kode generatornya ada di awesome-kit, di bawah MIT.

<sub>Terakhir diperbarui 2026-11-10.</sub>
