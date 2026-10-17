# 🏍️ MotoDemerval

Aplicativo de solicitação de **mototáxi** desenvolvido para facilitar o contato entre clientes e o serviço de transporte.

O cliente pode informar seus dados, marcar sua localização diretamente no mapa, escolher a forma de pagamento e enviar a solicitação da corrida pelo WhatsApp.

---

## 📱 Sobre o projeto

O **MotoDemerval** foi desenvolvido utilizando tecnologias web e transformado em aplicativo Android através do **Capacitor**.

A compilação do APK é realizada automaticamente pelo **GitHub Actions**, permitindo gerar o aplicativo Android sem precisar instalar o Android Studio ou Android SDK no computador.

---

## 🚀 Funcionalidades

- 🏍️ Solicitação de mototáxi
- 👤 Identificação do cliente
- 🗺️ Mapa interativo
- 📍 Marcação manual da localização
- 📡 Localização atual através do GPS
- 🎯 Campo para destino ou ponto de referência
- 💳 Escolha da forma de pagamento
- 💬 Envio da solicitação pelo WhatsApp
- 📝 Campo para observações
- 📱 Interface adaptada para celulares
- 🌙 Interface moderna em tema escuro
- 🤖 Compatível com Android

---

## 📍 Localização

O cliente possui duas maneiras de informar onde está.

### Usar GPS

O botão:

`📍 Minha localização`

solicita autorização para acessar a localização do aparelho.

Após a autorização, o aplicativo posiciona o marcador no mapa.

### Marcar manualmente

O cliente também pode tocar diretamente no mapa para escolher seu local de embarque.

O marcador pode ser reposicionado caso seja necessário.

---

## 💳 Formas de pagamento

O cliente pode escolher entre:

- 💠 Pix
- 💵 Dinheiro
- 💳 Cartão

A forma escolhida é adicionada automaticamente à solicitação da corrida.

---

## 💬 Solicitação pelo WhatsApp

Depois de preencher os dados, o cliente toca no botão:

`💬 Solicitar pelo WhatsApp`

O aplicativo prepara automaticamente uma mensagem contendo as informações da corrida.

Exemplo:

```text
🏍️ NOVA CORRIDA - MotoDemerval

👤 Cliente: João

📍 Localização:
Link da localização no mapa

🎯 Destino/Referência:
Centro

💳 Pagamento:
Pix

📝 Observação:

🛠️ Tecnologias utilizadas
O MotoDemerval utiliza:
- HTML5
- CSS3
- JavaScript
- Leaflet
- OpenStreetMap
- Capacitor
- Android
- GitHub
- GitHub Actions
- WhatsApp

📂 Estrutura do projeto

mototaxi/
│
├── .github/
│   └── workflows/
│       └── build-android.yml
│
├── www/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── capacitor.config.json
├── package.json
└── README.md

