# Pedidos de publicação

Cada arquivo aqui é um pedido: `vX.Y.Z` com uma linha dizendo o que mudou. Subir um arquivo
dispara o workflow "Gerar e publicar o Bunny", que lê a versão da `main` do código, gera o
instalador e publica a release. Se a versão pedida já estiver publicada, ele não faz nada.
