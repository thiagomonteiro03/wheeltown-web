# Wheel Town (build web)

Jogue em <https://wheeltown.lumee.page>, no Chrome ou no Firefox de um computador.

Este repositório só tem a **build web gerada** do Wheel Town (Godot 4.7.2, WebAssembly + WebGL 2), servida pelo GitHub Pages. O código do jogo fica num repositório privado; aqui estão apenas os arquivos que o navegador baixa para rodar o jogo.

**Não edite nada aqui à mão.** Cada versão é publicada por `sh tools/build_web.sh --deploy` no repositório do jogo, que apaga o que existia e escreve a build nova. O commit "Wheel Town abc1234" corresponde à versão que aparece no canto da tela de título.

O save fica no navegador de quem joga (IndexedDB deste site); nada é enviado a servidor nenhum.
