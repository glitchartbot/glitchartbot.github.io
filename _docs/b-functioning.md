---
layout: default
title: Funcionamento
---

## Como funciona

Cada bot no Twitter precisa de algumas credenciais específicas pra funcionar, o GAB usa as credenciais dele, se conecta na stream do Twitter (um lugar mágico por onde todos os tweets passam quando são postados) e fica vendo se alguém menciona ele. Se mencionam, ele vai até o tweet que ele foi mencionado e verifica se o tweet "pai" do que ele foi mencionado tem uma imagem, se tem, o bot baixa essa imagem, processa ela e responde a pessoa que mencionou ele inicialmente com a imagem editada.

## Tecnologias usadas

O bot inicialmente foi escrito em JavaScript mas por problemas de escalabilidade ele foi reescrito em <span class="highlight-text">TypeScript</span>, no <span class="highlight-text">Node 10</span>. Ele atualmente roda numa máquina da <span class="highlight-text">Amazon EC2</span>. O bot edita as imagens usando um de diversos "scripts" para o sofware de código criativo, <span class="highlight-text">Processing (3.5.4)</span> 