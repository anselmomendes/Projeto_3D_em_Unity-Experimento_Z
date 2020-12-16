<h1 align="center">PROJETO JOGO 3D - EXPERIMENTO-Z - UNIFESSPA.</h1>

<p align="center">🚀 Desenvolvimento de jogo em Unity</p>

<p align="center"><img src="https://simpleicons.org/icons/unity.svg" width="100" height="100"></p>

<p align="justify">A historia: um experimento de uma arma biológica em uma ilha secreta no oceano Pacífico não é contido corretamente e um vírus mortal escada, desencadeando uma série de acontecimentos na ilha que leva à morte de várias pessoas. Entretanto, esse é o menor dos problemas. Os mortos estão voltando à vida com um violento extinto assassino . O protagonista da nossa história, capitão de segurança Ryan , recebeu os documentos para replicação do experimento do Doutor Manel . Sua missão é chegar ao ponto de resgate, do outro lado da ilha, para manter os arquivos em segurança.</p>

<p align="center"><img src="https://raw.githubusercontent.com/anselmomendes/experimento_X/main/imagens/2020-12-16_121626.jpg" width="65%"></p>

<h3>AGENDA</h3>

* Apresentação do cronograma
* Ferramentas utilizadas
* Historia
* Personagens
* Assets
* Trilha de áudio
* Scripts
* Imagens do jogo
* Demonstração do jogo

<h3>Apresentação do cronograma</h3>
<p align="center"><img src="https://raw.githubusercontent.com/anselmomendes/experimento_X/main/imagens/2020-12-16_100135.jpg" width="65%"></p>

### Ferramentas utilizadas

<a href="https://unity.com/pt">Unity</a>

<a href="https://www.mixamo.com/">Mixamo</a>

<a href="https://www.vegascreativesoftware.com/br/vegas-pro/">Sony Vegas PRO 13</a>

<a href="https://desygner.com/pt/">Desygner</a>

<a href="https://www.audacityteam.org/download/">Audacity</a>

<a href="http://soundbible.com/">SoundBible</a>

<h3>Personagens</h3>

* ZOMBIE I
<p align="center"><img src="https://raw.githubusercontent.com/anselmomendes/experimento_X/main/imagens/2020-12-16_100403.jpg" width="65%"></p>

* ZOMBIE II
<p align="center"><img src="https://raw.githubusercontent.com/anselmomendes/experimento_X/main/imagens/2020-12-16_100417.jpg" width="65%"></p>

* ZOMBIE III
<p align="center"><img src="https://raw.githubusercontent.com/anselmomendes/experimento_X/main/imagens/2020-12-16_100436.jpg" width="65%"></p>

* SOLDADO
<p align="center"><img src="https://raw.githubusercontent.com/anselmomendes/experimento_X/main/imagens/2020-12-16_100451.jpg" width="65%"></p>

<h3>Assets</h3>

* <a href="https://assetstore.unity.com/packages/3d/concrete-barricades-80401">Concrete Barricades</a>

* <a href="https://unityfreaks.com/asset.php?id=1031">Warehouse Kit</a>

* <a href="https://assetstore.unity.com/packages/3d/environments/urban/old-soviet-shop-54767">Old Soviet Shop</a>

* <a href="https://assetstore.unity.com/packages/3d/chainlink-fences-73107">Chainlink Fences</a>

* <a href="https://assetstore.unity.com/packages/3d/vehicles/land/combat-vehicle-38259">Combat Vehicle</a>

* <a href="https://assetstore.unity.com/packages/3d/environments/industrial/free-shipping-containers-18315">Free Shipping Containers</a>

* <a href="https://assetstore.unity.com/packages/3d/environments/industrial/storage-building-50430">Storage Building</a>

* <a href="https://unityfreaks.com/asset/1021">Radio Tower Low Poly</a>

* <a href="https://assetstore.unity.com/packages/3d/props/weapons/ammo-crate-wood-ammunition-box-90071?_ga=2.107530114.120910731.1608126394-987911975.1608126394">Ammo Crate Wood Ammunition Box</a>

* <a href="https://assetstore.unity.com/packages/vfx/particles/white-smoke-particle-system-20404">White Smoke Particle System</a>

* <a href="https://assetstore.unity.com/packages/vfx/particles/environment/rain-maker-2d-and-3d-rain-particle-system-for-unity-34938">Rain Maker 2D and 3D Rain Particle System for Unity</a>

* <a href="https://assetstore.unity.com/packages/3d/vehicles/military-combat-vehicle-81155">Military Combat Vehicle</a>

* <a href="https://assetstore.unity.com/packages/2d/textures-materials/roads/concrete-asphalt-02-52433">Concrete Asphalt 02</a>

* <a href="https://assetstore.unity.com/packages/3d/vehicles/air/personnel-transport-helicopter-13448">Personnel Transport Helicopter</a>

* <a href="https://assetstore.unity.com/packages/2d/textures-materials/sky/free-night-sky-79066">Free Night Sky</a>

* <a href="https://unityfreaks.com/asset/1005">Low Poly City Block</a>

* <a href="https://assetstore.unity.com/packages/3d/props/guns/pbr-rov-free-edition-53060">[PBR] Мака rov Free Edition</a>

* <a href="https://assetstore.unity.com/packages/3d/props/guns/rifle-25668">Rifle</a>

* <a href="https://assetstore.unity.com/packages/3d/vehicles/air/hh-65c-dauphin-8128?locale=zh-CN">HH-65C Dauphin</a>

### Trilha de áudio

* <a href="https://www.youtube.com/watch?v=zSGPoLCY0xU&ab_channel=wickedslicks1003">Resident Evil 4 Soundtrack Save</a>

* <a href="https://www.youtube.com/watch?v=NHsjy5UuKdw&ab_channel=NewBrawlgamemusic">Resident Evil 4 Soundtrack Final Battle</a>

* <a href="https://www.youtube.com/watch?v=6uyBy8_QeMU&ab_channel=DimitrisPapadopoulos">Resident Evil 4 Soundtrack A Ruined Village</a>

<h3>Scripts</h3>

#### ATIRAR:
Esse script tem a função de realizar o tratamento das ações do nosso personagem.
Realizar o disparo da partícula;
Ativar a mira e o laser da arma;
Realizar a recarga do pente;

#### PLAYER:
Esse script tem a função de definir o nível da vida do personagem e verificar se ele tem pontos de vida suficiente pra permanecer vivo.
Realizar a verificação do nível de vida (protagonista);
Executar uma cena “você perdeu” quando os pontos de vida são menor ou igual a zero;

#### INIMIGO:
Esse script tem a função de verificar se os pontos de vida dos zombie são suficientes para permanecer vivo.
Realizar a verificação do nível de vida ( zombie;
Remove o objeto zumbie da cena quando seus pontos de vida não são suficientes;

#### VIDA:
Esse script tem a função de mostrar por meio de uma imagem o nível de vida o jogador.
Realiza a fixação das imagens no tela para o usuário;
Movimenta um fluxo vermelho que representa o nível de vida;

#### MUNIÇÃO: Esse script tem a função de realizar as operações de recarga descarga e coleta de munição.

Tratar a logica do numero máximo e mínimo de balas no pente;
Realiza a opção de coletar munição;

#### INTELIGÊNCIA:
Esse script tem a função de realizar a perseguição contra o personagem, a logica define o algoritmo de inteligência artificial a distancia, velocidade e dano por ataque.
Define o padrão de movimentação do zombie;
Provoca a perseguição contra o personagem;

#### JOGADOR: Esse script tem a simples função de inicializar o objeto com 100 pontos de vida.
Define os ponto de vida igual a 100;

#### firstPersonController:
Esse script tem a função de realizar a movimentação dos personagem.
Realiza o controle da movimentação usando o teclado e mouse;
Cria funções para pular e correr;
Dar a possibilidade de fazer a rotação usando mouse;

<h3>Imagens do jogo</h3>

<p align="center"><img src="https://raw.githubusercontent.com/anselmomendes/experimento_X/main/imagens/2020-12-16_100931.jpg" width="65%"></p>
<p align="center"><img src="https://raw.githubusercontent.com/anselmomendes/experimento_X/main/imagens/2020-12-16_100947.jpg" width="65%"></p>
<p align="center"><img src="https://raw.githubusercontent.com/anselmomendes/experimento_X/main/imagens/2020-12-16_101003.jpg" width="65%"></p>
<p align="center"><img src="https://raw.githubusercontent.com/anselmomendes/experimento_X/main/imagens/2020-12-16_101125.jpg" width="65%"></p>
<p align="center"><img src="https://raw.githubusercontent.com/anselmomendes/experimento_X/main/imagens/2020-12-16_101201.jpg" width="65%"></p>

<h3>Contribuidores</h3>

<table>
  <tr>
    <td align="center"><a href="https://github.com/anselmomendes"><img style="border-radius: 50%;" src="https://avatars1.githubusercontent.com/u/30941328?s=460&u=32b0cd9c3f0cefb87dc2caf0c3004845a5031726&v=4" width="100px;" alt=""/><br /><sub><b>Anselmo Mendes</b></sub></a><br /><a href="https://github.com/anselmomendes" title="Graduando em Eng. Computação">👨‍💻🚀🌽🍐🍒🍉</a></td>
    <td align="center"><a href="https://github.com/Isaacx88"><img style="border-radius: 50%;" src="https://avatars1.githubusercontent.com/u/17109969?s=460&u=09a2c804ca31b0bfe9cfe98157e32e95a708755d&v=4" width="100px;" alt=""/><br /><sub><b>Isaac Barros</b></sub></a><br /><a href="https://github.com/Isaacx88" title="Graduando em Eng. Computação">👨‍💻🚀🌴🌵🔥🎯</a></td>
  </tr>
</table>
