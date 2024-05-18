# Payload-Pix

O Payload-Pix é um gerador de payload para transações PIX que cria um código QR a partir das informações fornecidas, facilitando a realização de pagamentos.

## Funcionalidades

- Geração de payload PIX com base em informações fornecidas (valor, nome, chave PIX, cidade, ID de transação).
- Cálculo do código CRC16 para validação do payload.
- Geração de código QR para o payload PIX.
- Salvamento do código QR como um arquivo PNG.

## Requisitos

- Python 3.x
- Bibliotecas:
  - `crcmod`
  - `qrcode[pil]`

Você pode instalar as bibliotecas necessárias usando:

```sh
pip install crcmod qrcode[pil]


