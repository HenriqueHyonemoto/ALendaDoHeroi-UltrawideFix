# ALendaDoHeroi-UltrawideFix

ALendaDoHeroi-UltrawideFix é uma modificação feita para fazer com que o jogo possa renderizar em Ultrawide, 21:9 (2560x1080)

O Mod ainda esta em desenvolvimento, caso encontre erros como recursos decentralizados ou faltando, por favor me informe 😉

# Demonstrações (Fase de Teste)
<a href="https://www.youtube.com/watch?v=qPiQTyTO1xE&list=PL0jT61l8O_LYy3_dyUpT_iRXWayvFjh2D&index=2"><img src="https://github.com/user-attachments/assets/739ace0f-4d3f-4d22-aa90-017c058b2986"></a>

<h1> O que foi modificado? </h1>
Após mudar a renderização do jogo de 16:9 para 21:9, foi necessario fazer ajustes de posição em icones, menus, desenhar a area "extra" em certos sprites, e corrigir certos bugs.
<ul>
<h2>Código</h2>
<li>Posição das Logos durante a Intro (Foram Centralizadas)</li>
  <ul>
    <p float="left">
  <img src="https://github.com/user-attachments/assets/469d2d78-2b8b-41d5-a642-c85a23e8dd00" width="310px">
  <img src="https://github.com/user-attachments/assets/53928dde-f34a-42b3-99bd-38300731e474" width="310px">
  <img src="https://github.com/user-attachments/assets/bfec68e2-1fbc-44d5-abff-bab09d3ad084" width="310px">
</p>
</ul>
<HR>
<li>Expandido a area da intro do inicio (Para se adequar a nova resolução)</li>  
<ul>
Essa intro foi extendida utilizando o proprio código, sem a necessidade de aumentar editando o video.

<img src="https://github.com/HenriqueHyonemoto/UltrawideMOD-ALDH/assets/128445385/313ee23d-55cd-4747-b5b1-ea5538b3c794" width="800px">

</ul>
<HR>
<br>
<li>Tela de Loading </li>
<ul>
  Posição dos elementos para nova area (Texto Centralizado, Heroi mais a direita).
  <img src="https://github.com/user-attachments/assets/ef01c7da-8e0a-4546-80f2-1c6db827a1f8" width="800px">
</ul>
<HR>
<br>
<li>Menus</li>
  <ul>
    <li>Posição dos itens do Menu, Submenu e Armario</li>
    (Posição dos itens, opções, cursor foram corrigidas)
    <img src="https://github.com/user-attachments/assets/498d050c-e99d-45c0-b703-0f95df03c12a" width="800px">
    <img src="https://github.com/user-attachments/assets/87f69e9d-2510-46f9-ae02-fc1b4dd4e298" width="800px">
  </ul>
  <HR>
  <BR>
<li>Tela de Pause </li>
<ul>
Animações e posições não funcionavam corretamente.
<img src="https://github.com/user-attachments/assets/4f76c096-c3dc-42b1-a916-9c9e3d48d80a" width="800px">
</ul>
<HR>
<BR>
<li>Legendas (DisconectedMelody) </li>
<ul>
  
Corrigido bug no qual alguns tipos especificos de legendas não apareciam 

Nas Cutscenies de pegar item Especial
<img src="https://github.com/user-attachments/assets/896b1c83-c346-4a43-a526-a7bbf4191ff5" width="800px">
  
<br>
Falas do CID<br>
<img src="https://github.com/user-attachments/assets/6e7de5f8-3a33-4c65-997d-88a2b9a45cd2" width="800px">

<br><br>
Legendas de uma Linha em Batalha com Boss
<img src="https://github.com/user-attachments/assets/40b2c3fb-daf3-40e8-b700-3cbbf7668a94" width="800px">

</ul>
<HR>
<BR>
<li>Posição do Herói na Tela </li>
<ul>
  Corrigido bug no qual a Camera não acompanhava o herói corretamente.
<img src="https://github.com/user-attachments/assets/cc5cc108-dc83-4665-a724-7eacae03dec8" width="800px">

</ul>
<HR>
<BR>
<li>"Shake" na camera ao levar dano</li>
<ul>
  Corrigido um bug no qual quando a tela tremia, mostrava a parte inferior não desenhada do cenario
<img src="https://github.com/user-attachments/assets/845b586f-d0ad-48bb-acd0-0ee296d6cd8b" width="800px">
</ul>
<HR>
<BR>
<li>Posição da camera no final da fase </li>
<ul>
  O Jogo não mostrava o resto do cenario, ou ele ficava cortado (Neste exemplo o cenario era um pouco maior para a direita).
  <img src="https://github.com/user-attachments/assets/6ccee807-c159-490c-9348-67ee2ab64eed" width="800px"> 
  <br>
  
  Corrigido<br>
  <img src="https://github.com/user-attachments/assets/f7727924-3c69-4dad-b91b-03b5ad2733b2" width="800px">
</ul>
<HR>
<li>Posição do ScoreBoard (Ajustado para a nova posição de tela)</li>
<ul>
<img src="https://github.com/user-attachments/assets/f36400c9-2e92-4eda-b233-73cf3a5b384a" width="800px">
<img src="https://github.com/user-attachments/assets/4da34dbd-8e3d-4afd-93cd-262f7dec6527" width="800px">
</ul>
<HR>
<li>LowLifeShader (Para se aplicar a nova area)</li>
<li>Bordas cinematograficas, Stage Intro e Stage Title (Corrigido a posição e animação)</li>
<ul>
<img src="https://github.com/user-attachments/assets/7ad41124-087d-4cd4-b6ef-c05c0ac67676" width="800px">
</ul>
<HR>

<li>Lame Transition (Corrigido a area do efeito transição das fases)</li>
<ul>
  Corrigido a renderização da transição de fase.
  <img src="https://github.com/user-attachments/assets/e1cdf144-de9d-48bc-bae8-ec2769cc26e1" width="800px">
</ul>
<hr>
<br>
<li>Parallax Texture Render loopX </li>
<ul>
Corrigido a renderização do cenário "Parallax" do fundo das fases ao andar para a esquerda e direita.
(No bug em questão, essas partes selecionadas não carregavam devidamente, sendo necessario uma reestruturação no LOOP para se adaptar a nova resolução)
<img src="https://github.com/user-attachments/assets/7292d050-c8b8-4902-b3d9-850bbd4489a3" width="800px">
</ul>
<hr>
<br>
<li>Parallax Texture Render loopY 
</li>
<ul>
Corrigido a renderização do cenário "Parallax" do fundo das fases ao subir e descer no eixo Y (Como na fase 3, onde se escalar até o topo)<br>
<img src="https://github.com/user-attachments/assets/18b93f39-f845-47ca-adaf-5997704a27b4" width="800px">
</ul>
<hr>
<br>
<li>Shaders do Boss (Gorilize, tint, white etc) </li>
<ul>
  Corrigido um bug no qual os bosses ficavam esticados quando entravam na segunda etapa, e não condizia com a area da sua Hitbox após passar para a segunda etapa de fight.
<img src="https://github.com/user-attachments/assets/05c257de-4c15-4ac5-9003-e2413da82103" width="800px">
<img src="https://github.com/user-attachments/assets/c363171b-b11b-48f5-8141-1fced5052bc0" width="800px">
</ul>

<li>Cutscenies (Foram Centralizadas)</li>
<br>
Antes ficavam a esquerda.
<ul>
<img src="https://github.com/user-attachments/assets/3efb0bad-35e4-4e75-ab30-ab734c5226a6" width="800px">
</ul>
<li>Tempestade Fase5 Ato3 (Corrigido a area em que a Tempestade aparece na tela)</li>
<li>Posição do Boomerang no Menu (Corrigido a posição do slot em que o Boomerang ocupa no Menu)</li>

<h2>Edições de Sprites e Videos</h2>
<li>Imagens do Menu </li>
<ul>
  <li>(Content/Menu/bg.xnb)</li>
  <li>(Content/Menu/bgmainMenu.xnb)</li>
  <li>(Content/Menu/bgsubMenu.xnb)</li>
  <li>(Content/Menu/Save/saves_bg.xnb)</li>
</ul>
<li>Bordas Cinematograficas do inicio</li>
<ul>
  <li>(Content/cinema.xnb)</li>
</ul>
<li>Armario</li>
<ul>
  <li>(Content/Menu/Armario/armario_bg.xnb)</li>
  <li>(Content/Menu/Armario/armario_bgEN.xnb)</li>
</ul>
<li>Lame Transition</li>
<ul>
  <li>(Content/lame_transition.xnb)</li>
</ul>
<li>Cutscenes InicioDeTudo</li>
<ul>
  <li>Content/Objects/logo.xnb</li>
  <li>Content/Objects/logoEN.xnb</li>
</ul>
<li>Cutscenes da Princesa</li>
<ul>
<li>Content/Objects/Videos/margem_fase9.xnb</li>
<li>Content/Objects/Videos/margem_final.xnb</li>
<li>Content/Objects/Videos/margem_princesa.xnb</li>
</ul>
<li>Fase 5: Ventaria (Corrigido a renderização da Ventaria)</li>
<ul>
  <li>Content/Objects/tornado_bg.xnb</li>
  <li>Content/Objects/tornado_front.xnb</li>
</ul>
<li>Fase 6: Aurora (Corrigido a renderização das Auroras Boreais)</li>
<ul>
  <li>Content/Levels/6/aurora/1.xnb</li>
  <li>Content/Levels/6/aurora/2.xnb</li>
  <li>Content/Levels/6/aurora/3.xnb</li>
</ul>
</ul>

<ul>


<h2>Intro</h2>



<h2>Menus</h2>

Foram alteradas posições e desenhada areas que antes eram bordas pretas.

![image](https://github.com/HenriqueHyonemoto/UltrawideMOD-ALDH/assets/128445385/35808038-4166-4b60-80c2-5431dcd9f677)

![image](https://github.com/HenriqueHyonemoto/UltrawideMOD-ALDH/assets/128445385/f58a35ec-f67c-4067-91b7-7431d51a8dfc)

![image](https://github.com/HenriqueHyonemoto/UltrawideMOD-ALDH/assets/128445385/507f13fb-ddc7-47d2-aad4-1f9adb214e49)


<h2>Mapa</h2>

Aumentado a area visivel.

![image](https://github.com/HenriqueHyonemoto/UltrawideMOD-ALDH/assets/128445385/cbf3acc7-a359-4cd7-adfb-4a6af9bc5bc8)


<h2>Tela de Loading</h2> 
### Texto foi centralizado, e o heroi para o canto direito da tela.

![image](https://github.com/HenriqueHyonemoto/UltrawideMOD-ALDH/assets/128445385/8f465e5e-173e-4ebf-b3e3-f606afc2fa84)


<h2>Jogo</h2> 

Foram alteradas posições, area de renderização, posição de recursos do hud (Itens consumiveis), Titulo, textos, menu de pause, configurações e animações, legendas, logica do background parallax, etc.

![image](https://github.com/HenriqueHyonemoto/UltrawideMOD-ALDH/assets/128445385/f7f4b58b-0241-4082-ab5b-38dfa4151823)

![image](https://github.com/HenriqueHyonemoto/UltrawideMOD-ALDH/assets/128445385/4637b744-da5d-41f0-89d2-54dcc4a43152)

<h2>Menu de Pause</h2> 

Foi necessario ajustar a posição dos recursos.

![image](https://github.com/HenriqueHyonemoto/UltrawideMOD-ALDH/assets/128445385/4bd53999-c53e-4742-96e7-528e4c6c8b2c) <br>

  
</ul>

