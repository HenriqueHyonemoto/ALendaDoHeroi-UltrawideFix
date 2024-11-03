# ALendaDoHeroi-UltrawideFix

ALendaDoHeroi-UltrawideFix é uma modificação feita para fazer com que o jogo possa renderizar em Ultrawide, 21:9 (Testado em 2560x1080).

O Mod ainda esta em desenvolvimento, caso encontre bugs, por favor me informe!

# Demonstrações (Fase de Teste)
<a href="https://www.youtube.com/watch?v=qPiQTyTO1xE&list=PL0jT61l8O_LYy3_dyUpT_iRXWayvFjh2D&index=2"><img src="https://github.com/user-attachments/assets/739ace0f-4d3f-4d22-aa90-017c058b2986"></a>

<!--TOC -->
<H1>índice</H1>

- [Instalação](#utilizar)
  - [Desativando Updates](#desativa-update)
  - [Instalando o Mod](#instalar)
- [O Que foi Modificado?](#modificado)
  - [No Código](#código)
  - [Nos Arquivos do Jogo](#arquivos)

<!--/TOC -->

<h1 name="utilizar">Como utilizar o Mod?</h1>

Este mod foi feito com base na modificação do executavel do jogo na versão 5.1.1dx. isso significa que se você atualizar seu jogo, esse executavel vai ser substituido, e o mod deixará de funcionar, então precisamos fazer com que a steam não atualize seu jogo.

<ul name="desativa-update">
<li >Saia da sua Steam (Steam -> Sair)</li>
<li>Acesse a sua pasta da steam e localize "steamapps" (padrão: C:\Program Files\Steam\SteamApps\)</li>
<li>Abra o arquivo "appmanifest_389170.acf" com o bloco de notas</li>
<UL>
  <LI>Verifique se o nome "Songs for a Hero" consta no arquivo</LI>
  <Li>Mude o valor de "StateFlags"	para "4"</Li>
  <img src="https://github.com/user-attachments/assets/4bc327ed-5680-4cd3-8114-1279cd37d86b" width="800px">
</UL>
  <br>
<li>Agora sempre que for executar o jogo, abra através do seu executavél na pasta que que está instalado</li>
  <br>
      Se você não sabe onde esta localizado siga estes passos:
  <UL name="instalar">
  <LI>Abra sua biblioteca Steam</LI>
  <Li>Procure pelo jogo -> Clique com o botão direito -> Gerenciar -> Explorar Arquivos locais 
  <li>Faça <a href="">download</a> desse repositorio, e copie todos os arquivos pra dentro deste diretório (Para instalar o mod)</li>
    <img src="https://github.com/user-attachments/assets/d465ca2c-1006-4641-9c26-b0387abe3999" width="600px">
  <li>Feito isso, você pode criar um atalho clicando com o botão direito em "DumaLegend" > Enviar Para -> Area de Trabalho</li>
</Li>
</UL>
</ul>

<h1 name = "modificado"> O que foi modificado? </h1>
Para mudar a renderização do jogo de 16:9 para 21:9, foi necessario alterar valores e funções dentro do código do executavél, também necessario fazer ajustes de posição em icones, menus, desenhar a area "extra" em certos sprites, e corrigir varios bugs que a mudança causou.
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
<li>LowLifeShader (Vinheta vermelha quando se está com pouca vida)</li>
<ul>
  Ajustado para cobrir toda a tela.
  <img src="https://github.com/user-attachments/assets/8ac79a70-8d1c-4aa4-a48d-1b650605b992" width="800px">
</ul>
<hr>
<br>
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
<hr>
<br>
<li>Cutscenies (Foram Centralizadas)</li>
<br>
Antes ficavam a esquerda.
<ul>
<img src="https://github.com/user-attachments/assets/3efb0bad-35e4-4e75-ab30-ab734c5226a6" width="800px">
</ul>
<hr>
<br>
<li>Tempestade Fase5 Ato3</li>
<ul>
  A Tempestade aparecia cortada.
  <img src="https://github.com/user-attachments/assets/31bc0ddf-52bf-416d-882c-27218ca77850" width="800px">
  <br>
  Foi necessário modificar o código e também expandir as imagens da tempestade.
  <img src="https://github.com/user-attachments/assets/4ea430d2-5a29-4e34-90ab-47a371a36d77" width="800px">
</ul>
<hr>
<br>
<li>Posição do Boomerang no Menu </li>
<ul>
  (Corrigido a posição do Boomerang no Menu Pause)
<img src="https://github.com/user-attachments/assets/378e1111-16a7-475c-9476-37ccfbe7d219" width="800px">

<img src="https://github.com/user-attachments/assets/c103895c-31ae-48c9-ab77-fb2ac1366097" width="800px">
</ul>
<hr>
<br>
<h2 name = "arquivos">Edição de Imagens e Videos</h2>
<li>Imagens do Menu</li>
<ul>
  <li>(Content/Menu/bg.xnb)</li>
  
  <img src="https://github.com/user-attachments/assets/c1793d85-92f6-4743-8fe4-cc4e4f87c949" width="391px">  ->
  <img src="https://github.com/user-attachments/assets/647e9324-6734-4350-a823-10d0a92dec0c" width="521px">
  <li>(Content/Menu/bgmainMenu.xnb)</li>
  <img src="https://github.com/user-attachments/assets/2261cebc-8c93-41c5-a96e-80c8b979d345" width="391px"> ->
  <img src="https://github.com/user-attachments/assets/7cdfd3ef-5d9a-42e9-a5f6-3f8393075451" width="521px">
  <li>(Content/Menu/bgsubMenu.xnb)</li>
  <img src="https://github.com/user-attachments/assets/5ea1221a-ac2d-4200-a853-6051bcf6086d" width="391px"> ->
  <img src="https://github.com/user-attachments/assets/cbca8da7-729b-4543-ac02-9dda98f160b6" width="521px">
  <li>(Content/Menu/Save/saves_bg.xnb)</li>
  <img src="https://github.com/user-attachments/assets/706f93af-9fe6-4d60-bcf8-88c0b8d45c34" width="391px"> ->
  <img src="https://github.com/user-attachments/assets/a731463a-712a-4fbc-b24c-f247ce67d771" width="521px">
</ul>
<li>Bordas Cinematograficas do inicio</li>
<ul>
  <li>(Content/cinema.xnb)</li>
  <img src="https://github.com/user-attachments/assets/c4e4f56d-25fa-4912-beeb-3f0c415d296e" width="391px"> ->
  <img src="https://github.com/user-attachments/assets/4f935b5d-c709-456a-96b3-47e924e6a9c4" width="521px">
</ul>
<li>Armario</li>
<ul>
  <li>(Content/Menu/Armario/armario_bg.xnb)</li>
  <img src="https://github.com/user-attachments/assets/813c58e9-37e8-4256-a704-38e164d09a4b" width="391px"> ->
  <img src="https://github.com/user-attachments/assets/15dca433-6aff-4131-a049-5b54590f7988" width="521px">
  <li>(Content/Menu/Armario/armario_bgEN.xnb)</li>
  <img src="https://github.com/user-attachments/assets/14c393cd-c102-4864-aa8c-ddbea62c1371" width="391px"> ->
  <img src="https://github.com/user-attachments/assets/67e01860-28e4-44df-b7a2-eabb5251d03d" width="521px">
</ul>
<li>Lame Transition</li>
<ul>
  <li>(Content/lame_transition.xnb)</li>
  <img src="https://github.com/user-attachments/assets/b9116d76-b7f2-4af2-9493-4f89da8729c7" width="391px"> ->
  <img src="https://github.com/user-attachments/assets/86568cef-31c0-42eb-ade4-8f55dfef0518" width="521px">
</ul>
<li>Cutscenes InicioDeTudo</li>
<ul>
  <li>Content/Objects/logo.xnb</li>
  <img src="https://github.com/user-attachments/assets/2897d46e-f02a-40d8-9cda-f235b5013c3a" width="391px"> ->
  <img src="https://github.com/user-attachments/assets/af3f0ee5-813e-4466-bb6b-1aa6f4890866" width="521px">
  <li>Content/Objects/logoEN.xnb</li>
  <img src="https://github.com/user-attachments/assets/06ab9091-8b85-44c5-8821-f6db05cad858" width="391px"> ->
  <img src="https://github.com/user-attachments/assets/765de317-1c02-4d7d-a4c3-512605de959a" width="521px">
</ul>
<li>Cutscenes da Princesa</li>
<ul>
<li>Content/Objects/Videos/margem_fase9.xnb</li>
  <img src="https://github.com/user-attachments/assets/27c4753b-b2c8-4b57-b78a-05e1cfe318d6" width="391px"> ->
  <img src="https://github.com/user-attachments/assets/ba06e426-7700-4a35-bcbd-0b6ceaeca155" width="521px">
<li>Content/Objects/Videos/margem_final.xnb</li>
  <img src="https://github.com/user-attachments/assets/321ef187-f5d6-4a6f-928e-8d815ef25160" width="391px"> ->
  <img src="https://github.com/user-attachments/assets/ca4ff125-a1c0-4c46-abd7-2de605ca9360" width="521px">
<li>Content/Objects/Videos/margem_princesa.xnb</li>
  <img src="https://github.com/user-attachments/assets/190d97bd-c53a-49d9-bffd-7eca9161384a" width="391px"> ->
  <img src="https://github.com/user-attachments/assets/3790cfac-a104-4a46-9f45-e0f8bdf47937" width="521px">
</ul>
<li>Fase 5: Ventaria (Corrigido a renderização da Ventaria)</li>
<ul>
  <li>Content/Objects/tornado_bg.xnb</li>
  <img src="https://github.com/user-attachments/assets/af4acd80-a2be-412d-9a10-e9e94257ae5f" width="300px"> ->
  <img src="https://github.com/user-attachments/assets/324fa882-ce66-4517-b2f2-8bc4629b4045" width="600px">
  <li>Content/Objects/tornado_front.xnb</li>
  <img src="https://github.com/user-attachments/assets/e44012d7-e2c8-4819-acd8-db485d506381" width="300px"> ->
  <img src="https://github.com/user-attachments/assets/324057a2-a9f2-4038-9aa5-334e1bc13c57" width="600px">
</ul>
<li>Fase 6: Aurora (Corrigido a renderização das Auroras Boreais)</li>
<ul>
  <li>Content/Levels/6/aurora/1.xnb</li>
  <img src="https://github.com/user-attachments/assets/f8b6d365-12be-4e17-a95c-50db86ba6302" width="300px"> ->
  <img src="https://github.com/user-attachments/assets/71e0588f-fdd9-47bd-a0dc-077d7e99fcf3" width="600px">
  <li>Content/Levels/6/aurora/2.xnb</li>
  <img src="https://github.com/user-attachments/assets/7748b206-71fa-4286-9026-49c067961aff" width="300px"> ->
  <img src="https://github.com/user-attachments/assets/c073f9d2-edbd-47f4-848a-dd8c36d26098" width="600px">
  <li>Content/Levels/6/aurora/3.xnb</li>
  <img src="https://github.com/user-attachments/assets/fe7dbdf3-1613-42e3-ba8f-c0dfff41d264" width="300px"> ->
  <img src="https://github.com/user-attachments/assets/37ce8096-ac19-4569-8b0a-f4a84338dca0" width="600px">
</ul>
</ul>

<h1>Obrigado!</h1>

<p>Espero que esse MOD te ajude de alguma forma! qualquer duvida entre em contato 😉</p>

<br>
<div align="center">
<img src="https://github.com/user-attachments/assets/fc3682d2-b593-4157-a1cd-f69ccf1a0b1a" width="400px">
</div>


