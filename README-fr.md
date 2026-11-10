# Awesome Pix

> Pix pour les intégrateurs : normes, API, SDK, fournisseurs et outils, vérifiés un par un.

[![Cartas do Ciro](https://img.shields.io/badge/Cartas%20do%20Ciro-s'abonner-111111?style=flat-square)](https://go.mymarketing.click/pix-cartas) [![YouTube](https://img.shields.io/badge/YouTube-%40ciro--maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-youtube) [![Instagram](https://img.shields.io/badge/Instagram-ciro.maciel-111111?style=flat-square)](https://go.mymarketing.click/pix-instagram) [![Awesome](https://awesome.re/badge-flat2.svg)](https://go.mymarketing.click/pix-awesome) [![RSS](https://img.shields.io/badge/RSS-feed-555555?style=flat-square)](feed/fr.xml) ![56 éléments](https://img.shields.io/badge/%C3%A9l%C3%A9ments-56-555555?style=flat-square)

[![Português](https://img.shields.io/badge/Portugu%C3%AAs-111111?style=for-the-badge)](README.md) [![English](https://img.shields.io/badge/English-111111?style=for-the-badge)](README-en.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-111111?style=for-the-badge)](README-es.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-6b6b6b?style=for-the-badge)](README-fr.md) [![Deutsch](https://img.shields.io/badge/Deutsch-111111?style=for-the-badge)](README-de.md) [![Italiano](https://img.shields.io/badge/Italiano-111111?style=for-the-badge)](README-it.md) [![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-111111?style=for-the-badge)](README-ru.md) [![中文](https://img.shields.io/badge/%E4%B8%AD%E6%96%87-111111?style=for-the-badge)](README-zh.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-111111?style=for-the-badge)](README-ja.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-111111?style=for-the-badge)](README-ko.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-111111?style=for-the-badge)](README-hi.md) [![العربية](https://img.shields.io/badge/%D8%A7%D9%84%D8%B9%D8%B1%D8%A8%D9%8A%D8%A9-111111?style=for-the-badge)](README-ar.md) [![Bahasa Indonesia](https://img.shields.io/badge/Bahasa%20Indonesia-111111?style=for-the-badge)](README-id.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-111111?style=for-the-badge)](README-tr.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-111111?style=for-the-badge)](README-vi.md)

Pour celles et ceux qui facturent, encaissent ou rapprochent des Pix dans un système. On commence par ce que publie la Banque centrale, on passe par les fournisseurs qui proposent une API et on termine par les bibliothèques open source qui génèrent et lisent le QR Code. Chaque adresse a été ouverte avant d'être ajoutée.

## Contenu

- [Normes et documentation officielle](#normes-et-documentation-officielle)
- [Spécifications et API ouvertes](#spécifications-et-api-ouvertes)
- [Prestataires avec API Pix](#prestataires-avec-api-pix)
- [SDK officiels des prestataires](#sdk-officiels-des-prestataires)
- [Bibliothèques open source](#bibliothèques-open-source)
- [SDK de la communauté](#sdk-de-la-communauté)
- [Données et utilitaires](#données-et-utilitaires)
- [Outils](#outils)
- [Autres listes et communautés](#autres-listes-et-communautés)
- [Étiquettes](#étiquettes)
- [Comment contribuer](#comment-contribuer)
- [Autres listes](#autres-listes)
- [Réalisé par Ciro Cesar Maciel](#réalisé-par-ciro-cesar-maciel)
- [Licence](#licence)

## Normes et documentation officielle

Ce qui vient de la Banque centrale, qui définit le Pix.

- [Pix no Banco Central](https://go.mymarketing.click/pix-pix-no-banco-central) - La page officielle du Pix, avec ce que c'est, comment ça marche et les liens vers le reste. `officiel` `gratuit`
- [Normas do Pix](https://go.mymarketing.click/pix-normas-do-pix) - Le règlement, les résolutions et les manuels qui régissent le Pix. `officiel` `gratuit`
- [Pix Automático](https://go.mymarketing.click/pix-pix-automatico) - La modalité pour les prélèvements récurrents autorisés une seule fois par le payeur. `officiel` `gratuit`
- [Participantes do Pix](https://go.mymarketing.click/pix-participantes-do-pix) - La liste des institutions qui proposent le Pix et sous quelle modalité. `officiel` `gratuit`
- [Estatísticas do Pix](https://go.mymarketing.click/pix-estatisticas-do-pix) - Les chiffres officiels des transactions, des montants et des clés. `officiel` `gratuit`
- [Perguntas frequentes do Pix](https://go.mymarketing.click/pix-perguntas-frequentes-do-pix) - Les réponses de la Banque centrale aux questions les plus courantes des utilisateurs du Pix. `officiel` `gratuit`

## Spécifications et API ouvertes

Les contrats d'API que la Banque centrale publie sur GitHub.

- [API Pix](https://go.mymarketing.click/pix-api-pix) - La spécification OpenAPI de l'API Pix, que les prestataires implémentent pour les encaissements et la réception de paiements. `officiel` `open source` `API`
- [API do DICT](https://go.mymarketing.click/pix-api-do-dict) - La spécification de l'API du Répertoire des identifiants de comptes transactionnels, où se trouvent les clés Pix. `officiel` `open source` `API`
- [DICT Quickstart](https://go.mymarketing.click/pix-dict-quickstart) - Un guide de premiers pas avec l'API du DICT. `officiel` `open source`

## Prestataires avec API Pix

Banques, établissements de paiement et plateformes avec une documentation publique pour intégrer le Pix.

- [Adyen](https://go.mymarketing.click/pix-adyen) - Le Pix comme moyen de paiement sur la plateforme mondiale d'Adyen. `API` `payant`
- [Asaas](https://go.mymarketing.click/pix-asaas) - Documentation de l'API d'Asaas, avec des encaissements par Pix, boleto et carte. `API` `payant`
- [Banco do Brasil](https://go.mymarketing.click/pix-banco-do-brasil) - Le portail développeurs de la Banco do Brasil, avec l'API Pix. `API`
- [Banco Inter](https://go.mymarketing.click/pix-banco-inter) - Le portail développeurs d'Inter, avec les API Pix et d'encaissement. `API`
- [Bradesco](https://go.mymarketing.click/pix-bradesco) - Le portail développeurs de Bradesco, avec les API Pix. `API`
- [Celcoin](https://go.mymarketing.click/pix-celcoin) - Infrastructure de paiement avec des API Pix pour les entreprises qui développent des produits financiers. `API` `payant`
- [Cora](https://go.mymarketing.click/pix-cora) - Les API de Cora pour l'encaissement et le Pix sur le compte professionnel. `API`
- [dLocal](https://go.mymarketing.click/pix-dlocal) - Paiements sur les marchés émergents, avec le Pix parmi les moyens acceptés au Brésil. `API` `payant`
- [EBANX](https://go.mymarketing.click/pix-ebanx) - Paiements locaux en Amérique latine, avec le Pix pour les entreprises étrangères et brésiliennes. `API` `payant`
- [Efí](https://go.mymarketing.click/pix-efi) - La documentation de l'API Pix d'Efí, anciennement Gerencianet, avec encaissement, webhook et Pix automatique. `API` `payant`
- [Itaú](https://go.mymarketing.click/pix-itau) - Le portail développeurs d'Itaú, avec les API Pix. `API`
- [Iugu](https://go.mymarketing.click/pix-iugu) - Documentation de l'API d'Iugu, avec des facturations et abonnements acceptant le Pix. `API` `payant`
- [Mercado Pago](https://go.mymarketing.click/pix-mercado-pago) - Recevoir un Pix via l'API Checkout de Mercado Pago, avec QR Code et copia e cola. `API` `payant`
- [OpenPix](https://go.mymarketing.click/pix-openpix) - La documentation d'OpenPix, plateforme d'encaissements par Pix avec API, webhooks et plugins. `API` `payant`
- [PagBank](https://go.mymarketing.click/pix-pagbank) - Le portail développeurs de PagBank, avec commandes et encaissements par Pix. `API` `payant`
- [Pagar.me](https://go.mymarketing.click/pix-pagar-me) - Documentation de l'API de Pagar.me, avec paiements par Pix, carte et boleto. `API` `payant`
- [Santander](https://go.mymarketing.click/pix-santander) - Le portail développeurs de Santander, avec les API Pix. `API`
- [Sicredi](https://go.mymarketing.click/pix-sicredi) - Le portail développeurs de Sicredi, avec les API Pix et d'encaissement. `API`
- [Stripe](https://go.mymarketing.click/pix-stripe) - Le Pix comme moyen de paiement sur Stripe, pour ceux qui l'utilisent déjà. `API` `payant`
- [Transfeera](https://go.mymarketing.click/pix-transfeera) - API de paiement et de réception par Pix, avec rapprochement. `API` `payant`
- [Woovi](https://go.mymarketing.click/pix-woovi) - La documentation de Woovi, avec encaissements, abonnements et webhooks par Pix. `API` `payant`

## SDK officiels des prestataires

Maintenus par ceux qui proposent l'API.

- [Efí SDK Node.js](https://go.mymarketing.click/pix-efi-sdk-node-js) - SDK Node.js pour les API d'Efí, avec encaissements Pix par QR Code et copia e cola. `open source` `SDK`
- [Efí SDK PHP](https://go.mymarketing.click/pix-efi-sdk-php) - SDK PHP pour les API d'Efí, avec encaissements Pix par QR Code et copia e cola. `open source` `SDK`
- [Gerencianet SDK Python](https://go.mymarketing.click/pix-gerencianet-sdk-python) - SDK Python pour l'API d'Efí, publié sous l'ancien nom Gerencianet. `open source` `SDK`
- [Mercado Pago SDK .NET](https://go.mymarketing.click/pix-mercado-pago-sdk-net) - Le SDK officiel de Mercado Pago pour .NET. `open source` `SDK`
- [Mercado Pago SDK Java](https://go.mymarketing.click/pix-mercado-pago-sdk-java) - Le SDK officiel de Mercado Pago pour Java. `open source` `SDK`
- [Mercado Pago SDK Node.js](https://go.mymarketing.click/pix-mercado-pago-sdk-node-js) - Le SDK officiel de Mercado Pago pour Node.js. `open source` `SDK`
- [Mercado Pago SDK PHP](https://go.mymarketing.click/pix-mercado-pago-sdk-php) - Le SDK officiel de Mercado Pago pour PHP. `open source` `SDK`
- [Mercado Pago SDK Python](https://go.mymarketing.click/pix-mercado-pago-sdk-python) - Le SDK officiel de Mercado Pago pour Python. `open source` `SDK`
- [OpenPix Developers](https://go.mymarketing.click/pix-openpix-developers) - Le code de la documentation d'OpenPix, avec des exemples d'intégration. `open source`
- [Woovi Developers](https://go.mymarketing.click/pix-woovi-developers) - Le code de la documentation de Woovi, avec des exemples d'intégration. `open source`

## Bibliothèques open source

Pour générer, lire et valider le BR Code (le contenu du QR Code et du copia e cola) sans dépendre d'un fournisseur.

- [brcode](https://go.mymarketing.click/pix-brcode) - Lecteur de BR Code Pix en Rust. `open source` `gratuit`
- [emv-qrcode](https://go.mymarketing.click/pix-emv-qrcode) - Générateur et lecteur de QR Code au standard EMV en Java, le standard que suit le BR Code. `open source` `gratuit`
- [go-pix](https://go.mymarketing.click/pix-go-pix) - Bibliothèque Go pour générer le copia e cola Pix et le QR Code. `open source` `gratuit`
- [php_qrcode_pix](https://go.mymarketing.click/pix-php-qrcode-pix) - Génération de QR Code Pix en PHP. `open source` `gratuit`
- [PHPay](https://go.mymarketing.click/pix-phpay) - Bibliothèque PHP pour intégrer plusieurs fournisseurs de paiement avec la même interface. `open source` `gratuit`
- [pix-payload](https://go.mymarketing.click/pix-pix-payload) - Paquet npm qui génère le payload Pix selon le standard de la Banco Central. `open source` `gratuit`
- [pix-utils](https://go.mymarketing.click/pix-pix-utils) - Outils TypeScript pour lire, générer et valider des codes Pix. `open source` `gratuit`
- [PIX-BACEN-SDK-dotnet](https://go.mymarketing.click/pix-pix-bacen-sdk-dotnet) - Les contrats de l'API Pix de la Banco Central en .NET, générés à partir de la spécification officielle. `open source` `gratuit`
- [pypix](https://go.mymarketing.click/pix-pypix) - Bibliothèque Python pour générer le BR Code et le QR Code Pix. `open source` `gratuit`

## SDK de la communauté

Créés par ceux qui utilisent l'API, et non par le fournisseur.

- [asaas (TypeScript)](https://go.mymarketing.click/pix-asaas-typescript) - SDK TypeScript qui simplifie les appels les plus courants de l'API d'Asaas. `open source` `gratuit`
- [asaas-sdk (PHP)](https://go.mymarketing.click/pix-asaas-sdk-php) - SDK PHP pour l'API d'Asaas. `open source` `gratuit`

## Données et utilitaires

Pour valider et rapprocher.

- [Bancos Brasileiros](https://go.mymarketing.click/pix-bancos-brasileiros) - La liste des banques brésiliennes avec code, ISPB et nom, dans plusieurs formats. `open source` `gratuit`

## Outils

Pour générer un Pix sans écrire de code.

- [Gerador de QR Code Pix](https://go.mymarketing.click/pix-gerador-de-qr-code-pix) - Génère un QR Code, une plaque et un lien Pix dans le navigateur à partir de la clé. `open source` `gratuit`
- [Infrastructure Payments](https://go.mymarketing.click/pix-infrastructure-payments) - Encaissement ponctuel par Pix et carte via Mercado Pago depuis votre compte, avec REST, SDK React et MCP. `API` `de l'auteur`
- [Marketing Stores](https://go.mymarketing.click/pix-marketing-stores) - Boutique en ligne avec paiement par Pix, QR Code et copia e cola, et carte directement sur le Mercado Pago du propriétaire. `API` `de l'auteur`

## Autres listes et communautés

Ceux qui ont déjà rassemblé des ressources sur Pix.

- [awesome-pix (Woovi)](https://go.mymarketing.click/pix-awesome-pix-woovi) - La première liste de ressources sur Pix, maintenue par Woovi. `open source` `gratuit`

## Étiquettes

Chaque élément indique ce qu'il est. Les étiquettes à côté aident à choisir : officiel lorsqu'il vient de l'organisme qui définit la norme, open source lorsque le code est publié, gratuit ou payant selon le modèle d'utilisation, API et SDK selon la manière de l'intégrer. Les éléments portant l'étiquette "de l'auteur" sont réalisés par Ciro Cesar Maciel et suivent les mêmes règles que tous les autres.

## Comment contribuer

Vous connaissez quelque chose qui manque, a changé ou n'est plus accessible ? Ouvrez une issue avec le formulaire d'ajout ou envoyez une pull request en modifiant data/list.json. Le README de chaque langue est généré à partir de ce fichier.

[CONTRIBUTING.md](CONTRIBUTING.md)

## Autres listes

Listes organisées dans le même format, en portugais et dans 14 autres langues.


## Réalisé par Ciro Cesar Maciel

Utiliser ce que je fais est aussi une façon de soutenir ces listes.

[![Cleaner](https://img.shields.io/badge/Cleaner-111111?style=flat-square)](https://go.mymarketing.click/pix-por-cleaner) [![Screenshots](https://img.shields.io/badge/Screenshots-111111?style=flat-square)](https://go.mymarketing.click/pix-por-screenshots) [![Speech to Text](https://img.shields.io/badge/Speech%20to%20Text-111111?style=flat-square)](https://go.mymarketing.click/pix-por-speech-to-text) [![Text to Speech](https://img.shields.io/badge/Text%20to%20Speech-111111?style=flat-square)](https://go.mymarketing.click/pix-por-text-to-speech) [![Windows](https://img.shields.io/badge/Windows-111111?style=flat-square)](https://go.mymarketing.click/pix-por-windows) [![Assistant](https://img.shields.io/badge/Assistant-111111?style=flat-square)](https://go.mymarketing.click/pix-por-assistant) [![CCM Stack](https://img.shields.io/badge/CCM%20Stack-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ccm-stack) [![O Novo Básico](https://img.shields.io/badge/O%20Novo%20B%C3%A1sico-111111?style=flat-square)](https://go.mymarketing.click/pix-por-o-novo-basico) [![Ferramentas grátis](https://img.shields.io/badge/Ferramentas%20gr%C3%A1tis-111111?style=flat-square)](https://go.mymarketing.click/pix-por-ferramentas-gratis) [![Infrastructure](https://img.shields.io/badge/Infrastructure-111111?style=flat-square)](https://go.mymarketing.click/pix-por-infrastructure) [![Operations](https://img.shields.io/badge/Operations-111111?style=flat-square)](https://go.mymarketing.click/pix-por-operations) [![Customers](https://img.shields.io/badge/Customers-111111?style=flat-square)](https://go.mymarketing.click/pix-por-customers) [![Marketing](https://img.shields.io/badge/Marketing-111111?style=flat-square)](https://go.mymarketing.click/pix-por-marketing) [![Agents](https://img.shields.io/badge/Agents-111111?style=flat-square)](https://go.mymarketing.click/pix-por-agents)

## Licence

Cette liste est sous CC0 1.0 : copiez, adaptez et redistribuez-la comme vous voulez, sans demander la permission. Le code du générateur se trouve dans awesome-kit, sous licence MIT.

<sub>Mise à jour le 2026-11-10.</sub>
