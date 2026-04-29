# Flutter Thermal Printer 🖨️

Uma biblioteca/aplicação desenvolvida em **Flutter** para facilitar a comunicação e impressão em impressoras térmicas (ESC/POS). O projeto foca na integração simplificada via Bluetooth, USB ou Wi-Fi, permitindo a emissão de recibos, tickets e logotipos.

## 📌 Sobre o Projeto

Este projeto resolve a complexidade de formatar e enviar comandos de impressão diretamente de dispositivos móveis para hardware térmico. Ele utiliza protocolos padrão da indústria para garantir compatibilidade com diversas marcas de impressoras.

## ✨ Funcionalidades

- [x] Conexão e pareamento com dispositivos Bluetooth/BLE.
- [x] Impressão de textos com diferentes formatações (Negrito, Alinhamento, Tamanho).
- [x] Suporte para impressão de imagens e logotipos (Conversão de bitmap).
- [x] Geração de QR Codes e Códigos de Barras.
- [x] Comando de corte de papel (Cutter) e abertura de gaveta.

## 🛠️ Tecnologias e Ferramentas

- **Linguagem:** Dart
- **Framework:** [Flutter](https://flutter.dev/)
- **Protocolo:** ESC/POS (Epson Standard Code for Printers)
- **Hardware Compatível:** Impressoras de 58mm e 80mm.

## ⚙️ Como executar

### Pré-requisitos
- Flutter SDK instalado.
- Para testes físicos: Uma impressora térmica com suporte a Bluetooth ou USB OTG.

### Instalação

1. Clone o repositório:
   ```bash
   git clone [https://github.com/ViniciusFVianna/flutter_termal_printer.git](https://github.com/ViniciusFVianna/flutter_termal_printer.git)
