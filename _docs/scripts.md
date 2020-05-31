---
layout: topic
title: Scripts
order: 4
---

## Como funciona

O bot usa um software de código criativo, o Processing, nele é possível manipular imagens e afins, tudo dependendo do código providenciado.

## Scripts disponíveis

Esses scripts podem ser utilizados para personalizar o resultado final da sua imagem editada. Cada opção só é compatível com seu próprio script. Se você usar uma opção não compatível com um script, o bot não vai dar erro ou algo do tipo, ele só vai ignorar a opção.

---

### Pixel Sort

#### Nome do script

`pixelsort`

#### Opções

| Opção  | Valores permitidos                       | Padrão | Descrição                                           |
| ------ | ---------------------------------------- | ------ | --------------------------------------------------- |
| `mode` | `1`: Preto<br>`2`: Brilho<br>`3`: Branco | `2`    | A referência a ser usada para fazer a ordenação (se usado no modo branco, os pixels mais próximos da cor branca serão usados na ordenação, etc...) |

> Script original por [Kim Asendorf](https://github.com/kimasendorf).

---

### Pixel Drift

#### Nome do script

`pixeldrift`

#### Opções

| Opção     | Valores permitidos                       | Padrão | Descrição                                                                                                             |
| --------- | ---------------------------------------- | ------ | --------------------------------------------------------------------------------------------------------------------- |
| `channel` | `1`: Vermelho<br>`2`: Verde<br>`3`: Azul | `1`    | O canal da imagem que vai ser usado pra fazer drift (recomendado usar o canal com cores mais predominantes na imagem) |
| `amount`  | `0 ... 100`                              | `50`   | O limite de cor pra fazer o drift (quanto menor o número, mais efeito)                                                |
| `dir`     | `1`: Vertical <br> `2`: Horizontal       | `1`    | A direção que o efeito será aplicado                                                                                  |
