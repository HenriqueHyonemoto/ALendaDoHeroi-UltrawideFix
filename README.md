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
  

  
<br>

</ul>


  
<li>Expandido a area da intro do inicio (Para se adequar a nova resolução)</li>  
<br>
<ul>
  
Essa intro foi extendida utilizando o proprio código, sem a necessidade de aumentar editando o video.

<img src="https://github.com/HenriqueHyonemoto/UltrawideMOD-ALDH/assets/128445385/313ee23d-55cd-4747-b5b1-ea5538b3c794" width="800px">

</ul>
<li>Tela de Loading (Posição dos elementos para nova area)</li>
<ul>
  <img src="https://github.com/user-attachments/assets/ef01c7da-8e0a-4546-80f2-1c6db827a1f8" width="800px">
</ul>
<li>Menus</li>
  <ul>
    <li>Posição dos itens do Menu, Submenu e Armario (Posição dos itens, opções, cursor foram corrigidas)</li>
    <li>Menu - Opções</li>
    <li>Opções - Sair</li>
    <li>Delete - Save</li>
    <img src="https://github.com/user-attachments/assets/498d050c-e99d-45c0-b703-0f95df03c12a" width="800px">
    <img src="https://github.com/user-attachments/assets/87f69e9d-2510-46f9-ae02-fc1b4dd4e298" width="800px">
  </ul>
<li>Tela de Pause (Animações e posições não funcionavam corretamente))</li>
<ul>
<img src="https://github.com/user-attachments/assets/4f76c096-c3dc-42b1-a916-9c9e3d48d80a" width="800px">
</ul>
<li>Legendas - DisconectedMelody (Corrigido bug no qual alguns tipos especificos de legendas não apareciam)</li>
<li>Posição do Herói na Tela (Corrigido bug no qual a Camera não acompanhava o herói corretamente)</li>
<li>Posição do ScoreBoard (Ajustado para a nova posição de tela)</li> 
<li>Animações dos icones quando o jogo é pausado. (Ajustado para a nova posição de tela)</li>
<li>LowLifeShader (Para se aplicar a nova area)</li>
<li>Bordas cinematograficas (Para se aplicar a nova area)</li>
<li>Stage Intro (Corrigido a posição)</li>
<li>Stage Title (Corrigido a posição)</li>
<li>Lame Transition (Corrigido a area do efeito transição das fases)</li>
<li>Parallax Texture Render (loopY, Corrigido a renderização do cenário "Parallax" do fundo das fases)</li>
<li>"Shake" na camera ao levar dano (Corrigido um bug no qual quando a tela tremia, mostrava uma parte não desenhada do cenario)</li>
<li>Shaders do Boss (Gorilize, tint, white etc (Corrigido um bug no qual o boss ficava esticado, e não condizia com a area da sua Hitbox após passar para a segunda etapa de fight)</li>
<li>Cutscenies (Foram Centralizadas)</li>
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

