# RNG Pedras Online — 2X Sorte + anúncios

O botão **📺 2X SORTE** foi restaurado ao lado do botão ROLAR.

## Importante sobre anúncios premiados
O código já contém a integração-base para **Google Publisher Tag / Google Ad Manager rewarded ads**. Um ID de publicação do AdSense (`ca-pub-...`) sozinho não é um ID de bloco de anúncio premiado.

No `index.html`, troque:

`/1234567/SEU_BLOCO_REWARDED`

pelo caminho real do seu **ad unit rewarded** do Google Ad Manager.

Quando o evento `rewardedSlotGranted` ocorrer, o jogador recebe 15 minutos de **2X sorte** e as chances de Lendário, Mítico e Secreto são multiplicadas por 2.

Não use um bloco comum do AdSense para dar recompensa por visualização/clique. O inventário premiado precisa ser configurado como rewarded e seguir as políticas do Google.
