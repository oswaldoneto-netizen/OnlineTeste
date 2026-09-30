# RNG Pedras — 2X Sorte com anúncio premiado

Esta versão adiciona um botão **📺 2X SORTE** perto do botão ROLAR.

## Importante antes de usar anúncios reais

O recurso de anúncio premiado na Web é implementado com **Google Publisher Tag / Google Ad Manager**. O código usa temporariamente `/1234567/example` como caminho de demonstração.

Antes de produção, troque `REWARDED_AD_UNIT` em `index.html` pelo caminho do seu bloco de anúncio premiado do Google Ad Manager.

A recompensa só é ativada no evento `rewardedSlotGranted`: 15 minutos de 2X sorte, dobrando o peso de **Lendário, Mítico e Secreto**. O usuário precisa aceitar voluntariamente o anúncio.

O ZIP não contém `players.json`, então não substitua o save existente do Render.
