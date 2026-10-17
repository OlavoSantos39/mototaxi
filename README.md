# 🏍️ MotoDemerval

App de solicitação de mototáxi em HTML, CSS, JavaScript e Capacitor.

## Funções
- Nome do cliente
- Mapa para marcar o embarque
- Botão Minha localização (GPS, mediante permissão)
- Destino/referência
- Pagamento: Pix, dinheiro ou cartão
- Observação
- Envio pelo WhatsApp para +55 86 99579-9484 com link do mapa

## Gerar APK sem Android SDK no computador
Envie todos os arquivos ao GitHub, inclusive `.github`.

Abra **Actions → Build MotoDemerval APK → Run workflow**.
Quando terminar com sucesso, baixe o artefato **MotoDemerval-APK**.
Extraia o ZIP e instale `app-debug.apk`.

## Importante
O mapa usa OpenStreetMap/Leaflet e precisa de internet. O GPS exige permissão de localização. O WhatsApp abre a mensagem pronta para o usuário confirmar o envio.
