---
layout: topic
title: Como usar
order: 3
---

## Uso básico

Para usar o bot do modo mais simples possível, você só precisa mencionar o bot (@GlitchArtBot) como resposta a um tweet que contém uma imagem.

Por trás das cenas, quando você não informa nada pro bot, ele usa uma configuração padrão, é como se você tivesse marcado ele informando as seguintes opções:

```
@GlitchArtBot pixelsort mode=2
```

## Uso avançado

O bot tem diversos scripts que editam as fotos de diversos modos diferentes. Para personalizar a imagem editada final, você precisa informar algumas opções que o bot vai usar para editar a imagem, para isso você precisa usar a seguinte formatação:

```
@GlitchArtBot [nome do script] [nome da opção]=[valor da opção]
```

Supondo que eu quisesse editar a quarta imagem de um tweet com o modo branco do Pixel Sort, eu mencionaria o bot com as seguintes opções:

```
@GlitchArtBot pixelsort mode=3 photo=4
```

`photo` é uma opção global, que são melhor explicadas na seção <span class="highlight-text">Scripts</span>, assim como todos os scripts e suas opções.

Os dois perfis, o que marcou o bot e o que contém a imagem **DEVEM** ser perfis abertos, caso contrário se assume que o bot não tem permissão para ver os tweets.
