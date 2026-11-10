# Awesome Pix

> Pix cho người tích hợp: quy định, API, SDK, nhà cung cấp và công cụ, đã kiểm tra từng mục.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-%C4%91%C4%83ng%20k%C3%BD-111111?style=flat-square)](https://go.mymarketing.click/pix-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/pix-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/vi.xml) ![56 mục](https://img.shields.io/badge/m%E1%BB%A5c-56-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-111111?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-6b6b6b?style=for-the-badge)](README-vi.md)

Dành cho người thu tiền, nhận tiền hoặc đối soát Pix trong hệ thống. Bắt đầu từ những gì Ngân hàng Trung ương công bố, tiếp đến các nhà cung cấp có API, và kết thúc ở các thư viện mã nguồn mở tạo và đọc QR Code. Mọi địa chỉ đều đã được mở kiểm tra trước khi đưa vào.

## Nội dung

- [Quy định và tài liệu chính thức](#quy-định-và-tài-liệu-chính-thức)
- [Đặc tả và API mở](#đặc-tả-và-api-mở)
- [Nhà cung cấp có API Pix](#nhà-cung-cấp-có-api-pix)
- [SDK chính thức của nhà cung cấp](#sdk-chính-thức-của-nhà-cung-cấp)
- [Thư viện mã nguồn mở](#thư-viện-mã-nguồn-mở)
- [SDK do cộng đồng phát triển](#sdk-do-cộng-đồng-phát-triển)
- [Dữ liệu và tiện ích](#dữ-liệu-và-tiện-ích)
- [Công cụ](#công-cụ)
- [Danh sách và cộng đồng khác](#danh-sách-và-cộng-đồng-khác)
- [Nhãn](#nhãn)
- [Cách đóng góp](#cách-đóng-góp)
- [Danh sách khác](#danh-sách-khác)
- [Thực hiện bởi Ciro Cesar Maciel](#thực-hiện-bởi-ciro-cesar-maciel)
- [Giấy phép](#giấy-phép)

## Quy định và tài liệu chính thức

Những gì do Ngân hàng Trung ương ban hành, đơn vị quy định Pix.

- [Pix no Banco Central](https://go.mymarketing.click/pix-pix-no-banco-central) - Trang chính thức của Pix, với giải thích là gì, hoạt động ra sao và liên kết tới phần còn lại. `chính thức` `miễn phí`
- [Normas do Pix](https://go.mymarketing.click/pix-normas-do-pix) - Quy định, nghị quyết và hướng dẫn điều chỉnh Pix. `chính thức` `miễn phí`
- [Pix Automático](https://go.mymarketing.click/pix-pix-automatico) - Hình thức cho các khoản thu định kỳ đã được người trả tiền ủy quyền một lần. `chính thức` `miễn phí`
- [Participantes do Pix](https://go.mymarketing.click/pix-participantes-do-pix) - Danh sách các tổ chức cung cấp Pix và hình thức họ hỗ trợ. `chính thức` `miễn phí`
- [Estatísticas do Pix](https://go.mymarketing.click/pix-estatisticas-do-pix) - Các số liệu chính thức về giao dịch, giá trị và khóa. `chính thức` `miễn phí`
- [Perguntas frequentes do Pix](https://go.mymarketing.click/pix-perguntas-frequentes-do-pix) - Câu trả lời của Ngân hàng Trung ương cho những thắc mắc phổ biến nhất của người dùng Pix. `chính thức` `miễn phí`

## Đặc tả và API mở

Các hợp đồng API mà Ngân hàng Trung ương đăng tải trên GitHub.

- [API Pix](https://go.mymarketing.click/pix-api-pix) - Đặc tả OpenAPI của API Pix, mà các nhà cung cấp triển khai để tạo và nhận thanh toán. `chính thức` `mã nguồn mở` `API`
- [API do DICT](https://go.mymarketing.click/pix-api-do-dict) - Đặc tả API của Danh bạ Định danh Tài khoản Giao dịch, nơi lưu trữ các khóa Pix. `chính thức` `mã nguồn mở` `API`
- [DICT Quickstart](https://go.mymarketing.click/pix-dict-quickstart) - Hướng dẫn bắt đầu nhanh với API của DICT. `chính thức` `mã nguồn mở`

## Nhà cung cấp có API Pix

Ngân hàng, tổ chức thanh toán và nền tảng có tài liệu công khai để tích hợp Pix.

- [Adyen](https://go.mymarketing.click/pix-adyen) - Pix như một phương thức thanh toán trên nền tảng toàn cầu của Adyen. `API` `trả phí`
- [Asaas](https://go.mymarketing.click/pix-asaas) - Tài liệu API của Asaas, với thu tiền qua Pix, boleto và thẻ. `API` `trả phí`
- [Banco do Brasil](https://go.mymarketing.click/pix-banco-do-brasil) - Cổng dành cho nhà phát triển của Banco do Brasil, với API Pix. `API`
- [Banco Inter](https://go.mymarketing.click/pix-banco-inter) - Cổng dành cho nhà phát triển của Inter, với API Pix và thu tiền. `API`
- [Bradesco](https://go.mymarketing.click/pix-bradesco) - Cổng dành cho nhà phát triển của Bradesco, với API Pix. `API`
- [Celcoin](https://go.mymarketing.click/pix-celcoin) - Hạ tầng thanh toán với API Pix cho doanh nghiệp xây dựng sản phẩm tài chính. `API` `trả phí`
- [Cora](https://go.mymarketing.click/pix-cora) - Các API của Cora để thu tiền và Pix trong tài khoản doanh nghiệp. `API`
- [dLocal](https://go.mymarketing.click/pix-dlocal) - Thanh toán tại các thị trường mới nổi, với Pix nằm trong số phương thức được chấp nhận tại Brazil. `API` `trả phí`
- [EBANX](https://go.mymarketing.click/pix-ebanx) - Thanh toán nội địa tại Mỹ Latinh, với Pix cho doanh nghiệp trong và ngoài Brazil. `API` `trả phí`
- [Efí](https://go.mymarketing.click/pix-efi) - Tài liệu API Pix của Efí, trước đây là Gerencianet, với thu tiền, webhook và Pix Automático. `API` `trả phí`
- [Itaú](https://go.mymarketing.click/pix-itau) - Cổng dành cho nhà phát triển của Itaú, với API Pix. `API`
- [Iugu](https://go.mymarketing.click/pix-iugu) - Tài liệu API của Iugu, với thu tiền và đăng ký chấp nhận Pix. `API` `trả phí`
- [Mercado Pago](https://go.mymarketing.click/pix-mercado-pago) - Cách nhận Pix qua Checkout API của Mercado Pago, với QR Code và copia e cola. `API` `trả phí`
- [OpenPix](https://go.mymarketing.click/pix-openpix) - Tài liệu của OpenPix, nền tảng thu tiền qua Pix với API, webhook và plugin. `API` `trả phí`
- [PagBank](https://go.mymarketing.click/pix-pagbank) - Cổng dành cho nhà phát triển của PagBank, với đơn hàng và thu tiền qua Pix. `API` `trả phí`
- [Pagar.me](https://go.mymarketing.click/pix-pagar-me) - Tài liệu API của Pagar.me, với thanh toán qua Pix, thẻ và boleto. `API` `trả phí`
- [Santander](https://go.mymarketing.click/pix-santander) - Cổng dành cho nhà phát triển của Santander, với API Pix. `API`
- [Sicredi](https://go.mymarketing.click/pix-sicredi) - Cổng dành cho nhà phát triển của Sicredi, với API Pix và thu tiền. `API`
- [Stripe](https://go.mymarketing.click/pix-stripe) - Pix như một phương thức thanh toán trên Stripe, dành cho người đã thu tiền qua nền tảng này. `API` `trả phí`
- [Transfeera](https://go.mymarketing.click/pix-transfeera) - API thanh toán và nhận tiền qua Pix, có đối soát. `API` `trả phí`
- [Woovi](https://go.mymarketing.click/pix-woovi) - Tài liệu API của Woovi, với thu tiền, đăng ký và webhook qua Pix. `API` `trả phí`

## SDK chính thức của nhà cung cấp

Do chính đơn vị cung cấp API duy trì.

- [Efí SDK Node.js](https://go.mymarketing.click/pix-efi-sdk-node-js) - SDK Node.js cho API của Efí, với thu tiền Pix bằng QR Code và copia e cola. `mã nguồn mở` `SDK`
- [Efí SDK PHP](https://go.mymarketing.click/pix-efi-sdk-php) - SDK PHP cho API của Efí, với thu tiền Pix bằng QR Code và copia e cola. `mã nguồn mở` `SDK`
- [Gerencianet SDK Python](https://go.mymarketing.click/pix-gerencianet-sdk-python) - SDK Python cho API của Efí, phát hành với tên cũ là Gerencianet. `mã nguồn mở` `SDK`
- [Mercado Pago SDK .NET](https://go.mymarketing.click/pix-mercado-pago-sdk-net) - SDK chính thức của Mercado Pago cho .NET. `mã nguồn mở` `SDK`
- [Mercado Pago SDK Java](https://go.mymarketing.click/pix-mercado-pago-sdk-java) - SDK chính thức của Mercado Pago cho Java. `mã nguồn mở` `SDK`
- [Mercado Pago SDK Node.js](https://go.mymarketing.click/pix-mercado-pago-sdk-node-js) - SDK chính thức của Mercado Pago cho Node.js. `mã nguồn mở` `SDK`
- [Mercado Pago SDK PHP](https://go.mymarketing.click/pix-mercado-pago-sdk-php) - SDK chính thức của Mercado Pago cho PHP. `mã nguồn mở` `SDK`
- [Mercado Pago SDK Python](https://go.mymarketing.click/pix-mercado-pago-sdk-python) - SDK chính thức của Mercado Pago cho Python. `mã nguồn mở` `SDK`
- [OpenPix Developers](https://go.mymarketing.click/pix-openpix-developers) - Mã nguồn tài liệu của OpenPix, có ví dụ tích hợp. `mã nguồn mở`
- [Woovi Developers](https://go.mymarketing.click/pix-woovi-developers) - Mã nguồn tài liệu của Woovi, có ví dụ tích hợp. `mã nguồn mở`

## Thư viện mã nguồn mở

Dùng để tạo, đọc và kiểm tra BR Code (nội dung của mã QR Code và copia e cola) mà không phụ thuộc nhà cung cấp.

- [brcode](https://go.mymarketing.click/pix-brcode) - Trình đọc BR Code của Pix viết bằng Rust. `mã nguồn mở` `miễn phí`
- [emv-qrcode](https://go.mymarketing.click/pix-emv-qrcode) - Công cụ tạo và đọc mã QR Code theo chuẩn EMV viết bằng Java, chuẩn mà BR Code tuân theo. `mã nguồn mở` `miễn phí`
- [go-pix](https://go.mymarketing.click/pix-go-pix) - Thư viện Go để tạo copia e cola và mã QR Code của Pix. `mã nguồn mở` `miễn phí`
- [php_qrcode_pix](https://go.mymarketing.click/pix-php-qrcode-pix) - Tạo mã QR Code của Pix bằng PHP. `mã nguồn mở` `miễn phí`
- [PHPay](https://go.mymarketing.click/pix-phpay) - Thư viện PHP để tích hợp nhiều nhà cung cấp thanh toán với cùng một giao diện. `mã nguồn mở` `miễn phí`
- [pix-payload](https://go.mymarketing.click/pix-pix-payload) - Gói npm tạo payload Pix theo chuẩn của Banco Central. `mã nguồn mở` `miễn phí`
- [pix-utils](https://go.mymarketing.click/pix-pix-utils) - Công cụ TypeScript để đọc, tạo và kiểm tra mã Pix. `mã nguồn mở` `miễn phí`
- [PIX-BACEN-SDK-dotnet](https://go.mymarketing.click/pix-pix-bacen-sdk-dotnet) - Các hợp đồng API Pix của Banco Central cho .NET, được tạo từ đặc tả chính thức. `mã nguồn mở` `miễn phí`
- [pypix](https://go.mymarketing.click/pix-pypix) - Thư viện Python để tạo BR Code và mã QR Code của Pix. `mã nguồn mở` `miễn phí`

## SDK do cộng đồng phát triển

Do người dùng API viết, không phải do nhà cung cấp.

- [asaas (TypeScript)](https://go.mymarketing.click/pix-asaas-typescript) - SDK TypeScript đóng gói các lệnh gọi API Asaas thường dùng nhất. `mã nguồn mở` `miễn phí`
- [asaas-sdk (PHP)](https://go.mymarketing.click/pix-asaas-sdk-php) - SDK PHP cho API Asaas. `mã nguồn mở` `miễn phí`

## Dữ liệu và tiện ích

Hỗ trợ kiểm tra và đối soát.

- [Bancos Brasileiros](https://go.mymarketing.click/pix-bancos-brasileiros) - Danh sách ngân hàng Brazil kèm mã, ISPB và tên, ở nhiều định dạng. `mã nguồn mở` `miễn phí`

## Công cụ

Dành cho người cần tạo Pix mà không phải viết mã.

- [Gerador de QR Code Pix](https://go.mymarketing.click/pix-gerador-de-qr-code-pix) - Tạo mã QR Code, biển số và liên kết Pix trên trình duyệt từ khóa Pix. `mã nguồn mở` `miễn phí`
- [Infrastructure Payments](https://go.mymarketing.click/pix-infrastructure-payments) - Thu phí lẻ bằng Pix và thẻ qua Mercado Pago của bạn, với REST, SDK React và MCP. `API` `của tác giả`
- [Marketing Stores](https://go.mymarketing.click/pix-marketing-stores) - Cửa hàng trực tuyến thanh toán bằng Pix, có mã QR Code và copia e cola, cùng thẻ trực tiếp qua Mercado Pago của chủ cửa hàng. `API` `của tác giả`

## Danh sách và cộng đồng khác

Những người đã tổng hợp tài liệu về Pix trước đây.

- [awesome-pix (Woovi)](https://go.mymarketing.click/pix-awesome-pix-woovi) - Danh sách tài nguyên về Pix đầu tiên, do Woovi duy trì. `mã nguồn mở` `miễn phí`

## Nhãn

Mỗi mục đều ghi rõ nó là gì. Các nhãn bên cạnh giúp bạn chọn: chính thức khi do đơn vị định ra chuẩn cung cấp, mã nguồn mở khi mã được công bố, miễn phí hoặc trả phí theo cách sử dụng, API và SDK theo cách tích hợp. Các mục có nhãn "của tác giả" do Ciro Cesar Maciel làm và tuân theo cùng quy tắc với mọi mục khác.

## Cách đóng góp

Biết có mục nào còn thiếu, đã thay đổi hoặc không còn truy cập được? Hãy mở một issue bằng biểu mẫu thêm mục mới, hoặc gửi pull request chỉnh sửa data/list.json. README của mỗi ngôn ngữ được tạo từ tệp này.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Danh sách khác

Các danh sách được tuyển chọn theo cùng định dạng, bằng tiếng Bồ Đào Nha và 14 ngôn ngữ khác.


## Thực hiện bởi Ciro Cesar Maciel

Sử dụng những gì tôi làm cũng là một cách ủng hộ các danh sách này.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/pix-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/pix-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/pix-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/pix-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/pix-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/pix-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/pix-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/pix-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/pix-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/pix-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/pix-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/pix-por-agents)

## Giấy phép

Danh sách này theo CC0 1.0: bạn có thể sao chép, chỉnh sửa và phân phối lại tùy ý, không cần xin phép. Mã của trình tạo nằm trong awesome-kit, theo giấy phép MIT.

<sub>Cập nhật lần cuối 2026-11-10.</sub>
