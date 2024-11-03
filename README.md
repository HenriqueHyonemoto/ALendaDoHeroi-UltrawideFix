# ALendaDoHeroi-UltrawideFix

**ALendaDoHeroi-UltrawideFix** é uma modificação criada para permitir que o jogo seja renderizado em ultrawide (21:9). Testado em resolução 2560x1080.

O mod ainda está em desenvolvimento. Caso encontre bugs, por favor, informe!

# Demonstrações (Fase de Teste)
<a href="https://www.youtube.com/watch?v=qPiQTyTO1xE&list=PL0jT61l8O_LYy3_dyUpT_iRXWayvFjh2D&index=2">
  <img src="https://github.com/user-attachments/assets/79912903-af7d-421e-98db-776309e4a2d3" width="1000px">
</a>

<!-- TOC -->
<h1>Índice</h1>

- [Instalação](#utilizar)
  - [Desativando Atualizações](#desativa-update)
  - [Instalando o Mod](#instalar)
- [O que foi Modificado?](#modificado)
  - [No Código](#código)
  - [Nos Arquivos do Jogo](#arquivos)

<!-- /TOC -->

<h1 id="utilizar">Como utilizar o Mod?</h1>

<p>Este mod foi criado com base na modificação do executável do jogo na versão 5.1.1dx. Isso significa que, se você atualizar seu jogo, esse executável será substituído, e o mod deixará de funcionar. Portanto, precisamos fazer com que a Steam não atualize seu jogo.</p>

<ul id="desativa-update">
  <li>Saia da sua Steam (Steam -> Sair).</li>
  <li>Acesse a sua pasta da Steam e localize "steamapps" (padrão: C:\Program Files\Steam\SteamApps\).</li>
  <li>Abra o arquivo "appmanifest_389170.acf" com o Bloco de Notas.</li>
  <ul>
    <li>Verifique se o nome "Songs for a Hero" consta no arquivo.</li>
    <li>Altere o valor de "StateFlags" para "4".</li>
    <img src="https://github.com/user-attachments/assets/4bc327ed-5680-4cd3-8114-1279cd37d86b" width="800px">
  </ul>
  <br>
  <li>Agora, sempre que for executar o jogo, abra-o através do seu executável na pasta onde ele está instalado.</li>
  <br>
  <p>Se você não sabe onde o jogo está localizado, siga estes passos:</p>
  <ul id="instalar">
    <li>Abra sua biblioteca Steam.</li>
    <li>Procure pelo jogo -> Clique com o botão direito -> Gerenciar -> Explorar Arquivos Locais.</li>
    <li>Faça o <a href="">download</a> deste repositório e copie todos os arquivos para dentro deste diretório (para instalar o mod).</li>
    <img src="https://github.com/user-attachments/assets/d465ca2c-1006-4641-9c26-b0387abe3999" width="600px">
    <li>Feito isso, você pode criar um atalho clicando com o botão direito em "DumaLegend" -> Enviar Para -> Área de Trabalho.</li>
  </ul>
</ul>


<h1 id="modificado">O que foi modificado?</h1>
<p>Para ajustar a renderização do jogo de 16:9 para 21:9, foi necessário alterar valores e funções dentro do código do executável. Também foram feitos ajustes na posição de ícones, menus, ampliação da área "extra" em certos sprites e correções de vários bugs causados pela nova resolução.</p>

<ul>
  <h2>Código</h2>
  <li>Posição das Logos durante a Intro (Centralizadas)</li>
  <ul>
    <p style="float:left;">
      <img src="https://github.com/user-attachments/assets/469d2d78-2b8b-41d5-a642-c85a23e8dd00" width="250px">
      <img src="https://github.com/user-attachments/assets/53928dde-f34a-42b3-99bd-38300731e474" width="250px">
      <img src="https://github.com/user-attachments/assets/bfec68e2-1fbc-44d5-abff-bab09d3ad084" width="250px">
    </p>
  </ul>
  <hr>
  
  <li>Área da Intro Expandida (Para se adequar à nova resolução)</li>  
  <ul>
    <p>Essa intro foi estendida utilizando o próprio código, sem necessidade de edição do vídeo.</p>
    <img src="https://github.com/user-attachments/assets/ab027292-b86a-4f88-a48c-dd8df0d4882f" width="800px">
  </ul>
  <hr>
  <br>
  
  <li>Tela de Carregamento</li>
  <ul>
    <p>Posicionamento dos elementos ajustado para a nova área (Texto centralizado, Herói mais à direita).</p>
    <img src="https://github.com/user-attachments/assets/ef01c7da-8e0a-4546-80f2-1c6db827a1f8" width="800px">
  </ul>
  <hr>
  <br>
  
  <li>Menus</li>
  <ul>
    <li>Posicionamento dos itens do Menu, Submenu e Armário</li>
    <p>(Posição dos itens, opções e cursor corrigidos)</p>
    <img src="https://github.com/user-attachments/assets/498d050c-e99d-45c0-b703-0f95df03c12a" width="800px">
    <img src="https://github.com/user-attachments/assets/87f69e9d-2510-46f9-ae02-fc1b4dd4e298" width="800px">
  </ul>
  <hr>
  <br>
  
  <li>Tela de Pause</li>
  <ul>
    <p>Animações e posições corrigidas para funcionarem corretamente.</p>
    <img src="https://github.com/user-attachments/assets/4f76c096-c3dc-42b1-a916-9c9e3d48d80a" width="800px">
  </ul>
  <hr>
  <br>
</ul>

<li>Legendas (DisconectedMelody)</li>
<ul>
  <p>Corrigido bug no qual alguns tipos específicos de legendas não apareciam:</p>

  <p>Nas cutscenes de pegar item especial:</p>
  <img src="https://github.com/user-attachments/assets/896b1c83-c346-4a43-a526-a7bbf4191ff5" width="800px">
  
  <br>
  <p>Falas do CID:</p>
  <img src="https://github.com/user-attachments/assets/6e7de5f8-3a33-4c65-997d-88a2b9a45cd2" width="800px">

  <br><br>
  <p>Legendas de uma linha em batalha com Boss:</p>
  <img src="https://github.com/user-attachments/assets/40b2c3fb-daf3-40e8-b700-3cbbf7668a94" width="800px">
</ul>
<hr>
<br>

<li>Posição do Herói na Tela</li>
<ul>
  <p>Corrigido bug no qual a câmera não acompanhava o herói corretamente.</p>
  <img src="https://github.com/user-attachments/assets/cc5cc108-dc83-4665-a724-7eacae03dec8" width="800px">
</ul>
<hr>
<br>

<li>"Shake" na Câmera ao Levar Dano</li>
<ul>
  <p>Corrigido bug onde, ao tremer a tela, aparecia a parte inferior não desenhada do cenário.</p>
  <img src="https://github.com/user-attachments/assets/845b586f-d0ad-48bb-acd0-0ee296d6cd8b" width="800px">
</ul>
<hr>
<br>

<li>Posição da Câmera no Final da Fase</li>
<ul>
  <p>O jogo não mostrava o resto do cenário, ou ele ficava cortado. (Neste exemplo, o cenário era um pouco maior para a direita.)</p>
  <img src="https://github.com/user-attachments/assets/6ccee807-c159-490c-9348-67ee2ab64eed" width="800px">
  <br>
  <p>Corrigido:</p>
  <img src="https://github.com/user-attachments/assets/f7727924-3c69-4dad-b91b-03b5ad2733b2" width="800px">
</ul>
<hr>

<li>Posição do ScoreBoard (Ajustado para a nova posição de tela)</li>
<ul>
  <img src="https://github.com/user-attachments/assets/f36400c9-2e92-4eda-b233-73cf3a5b384a" width="800px">
  <img src="https://github.com/user-attachments/assets/4da34dbd-8e3d-4afd-93cd-262f7dec6527" width="800px">
</ul>
<hr>

<li>LowLifeShader (Vinheta vermelha quando se está com pouca vida)</li>
<ul>
  <p>Ajustado para cobrir toda a tela.</p>
  <img src="https://github.com/user-attachments/assets/8ac79a70-8d1c-4aa4-a48d-1b650605b992" width="800px">
</ul>
<hr>
<br>

<li>Bordas Cinematográficas, Intro da Fase e Título da Fase (Corrigido a posição e animação)</li>
<ul>
  <img src="https://github.com/user-attachments/assets/7ad41124-087d-4cd4-b6ef-c05c0ac67676" width="800px">
</ul>
<hr>


<li>Lame Transition (Área de efeito da transição de fase corrigida)</li>
<ul>
  <p>Corrigida a renderização da transição de fase.</p>
  <img src="https://github.com/user-attachments/assets/e1cdf144-de9d-48bc-bae8-ec2769cc26e1" width="800px">
</ul>
<hr>
<br>

<li>Parallax Texture Render Loop X</li>
<ul>
  <p>Corrigida a renderização do cenário "Parallax" ao mover-se para a esquerda e direita.</p>
  <p>(No bug original, certas partes selecionadas não carregavam devidamente, sendo necessário reestruturar o loop para se adaptar à nova resolução.)</p>
  <img src="https://github.com/user-attachments/assets/7292d050-c8b8-4902-b3d9-850bbd4489a3" width="800px">
</ul>
<hr>
<br>

<li>Parallax Texture Render Loop Y</li>
<ul>
  <p>Corrigida a renderização do cenário "Parallax" ao mover-se no eixo Y, como na fase 3 ao escalar até o topo.</p>
  <img src="https://github.com/user-attachments/assets/18b93f39-f845-47ca-adaf-5997704a27b4" width="800px">
</ul>
<hr>
<br>

<li>Shaders do Boss (Gorilize, Tint, White, etc.)</li>
<ul>
  <p>Corrigido um bug no qual os bosses ficavam esticados na segunda etapa, sem corresponder à área de sua hitbox após a transição de fase.</p>
  <img src="https://github.com/user-attachments/assets/05c257de-4c15-4ac5-9003-e2413da82103" width="800px">
  <img src="https://github.com/user-attachments/assets/c363171b-b11b-48f5-8141-1fced5052bc0" width="800px">
</ul>
<hr>
<br>

<li>Cutscenes (Centralizadas)</li>
<ul>
  <p>Antes, as cutscenes apareciam à esquerda. Agora, foram centralizadas para melhor visualização.</p>
  <img src="https://github.com/user-attachments/assets/3efb0bad-35e4-4e75-ab30-ab734c5226a6" width="800px">
</ul>
<hr>
<br>

<li>Tempestade - Fase 5, Ato 3</li>
<ul>
  <p>A tempestade aparecia cortada.</p>
  <img src="https://github.com/user-attachments/assets/31bc0ddf-52bf-416d-882c-27218ca77850" width="800px">
  <p>Foi necessário modificar o código e expandir as imagens da tempestade.</p>
  <img src="https://github.com/user-attachments/assets/4ea430d2-5a29-4e34-90ab-47a371a36d77" width="800px">
</ul>
<hr>
<br>

<li>Posição do Bumerangue no Menu</li>
<ul>
  <p>Corrigida a posição do bumerangue no menu de pausa.</p>
  <img src="https://github.com/user-attachments/assets/378e1111-16a7-475c-9476-37ccfbe7d219" width="800px">
  <img src="https://github.com/user-attachments/assets/c103895c-31ae-48c9-ab77-fb2ac1366097" width="800px">
</ul>
<hr>
<br>

<h2 name = "arquivos">Edição de Imagens e Videos</h2>
<li>Imagens do Menu</li>
<ul>
  <li>(Content/Menu/bg.xnb)</li>
  <img src="https://github.com/user-attachments/assets/c1793d85-92f6-4743-8fe4-cc4e4f87c949" width="328px">  ->
  <img src="https://github.com/user-attachments/assets/647e9324-6734-4350-a823-10d0a92dec0c" width="437px">
  <li>(Content/Menu/bgmainMenu.xnb)</li>
  <img src="https://github.com/user-attachments/assets/2261cebc-8c93-41c5-a96e-80c8b979d345" width="328px"> ->
  <img src="https://github.com/user-attachments/assets/7cdfd3ef-5d9a-42e9-a5f6-3f8393075451" width="437px">
  <li>(Content/Menu/bgsubMenu.xnb)</li>
  <img src="https://github.com/user-attachments/assets/5ea1221a-ac2d-4200-a853-6051bcf6086d" width="328px"> ->
  <img src="https://github.com/user-attachments/assets/cbca8da7-729b-4543-ac02-9dda98f160b6" width="437px">
  <li>(Content/Menu/Save/saves_bg.xnb)</li>
  <img src="https://github.com/user-attachments/assets/706f93af-9fe6-4d60-bcf8-88c0b8d45c34" width="328px"> ->
  <img src="https://github.com/user-attachments/assets/a731463a-712a-4fbc-b24c-f247ce67d771" width="437px">
</ul>
<li>Bordas Cinematograficas do inicio</li>
<ul>
  <li>(Content/cinema.xnb)</li>
  <img src="https://github.com/user-attachments/assets/c4e4f56d-25fa-4912-beeb-3f0c415d296e" width="328px"> ->
  <img src="https://github.com/user-attachments/assets/4f935b5d-c709-456a-96b3-47e924e6a9c4" width="437px">
</ul>
<li>Armario</li>
<ul>
  <li>(Content/Menu/Armario/armario_bg.xnb)</li>
  <img src="https://github.com/user-attachments/assets/813c58e9-37e8-4256-a704-38e164d09a4b" width="328px"> ->
  <img src="https://github.com/user-attachments/assets/15dca433-6aff-4131-a049-5b54590f7988" width="437px">
  <li>(Content/Menu/Armario/armario_bgEN.xnb)</li>
  <img src="https://github.com/user-attachments/assets/14c393cd-c102-4864-aa8c-ddbea62c1371" width="328px"> ->
  <img src="https://github.com/user-attachments/assets/67e01860-28e4-44df-b7a2-eabb5251d03d" width="437px">
</ul>
<li>Lame Transition</li>
<ul>
  <li>(Content/lame_transition.xnb)</li>
  <img src="https://github.com/user-attachments/assets/b9116d76-b7f2-4af2-9493-4f89da8729c7" width="328px"> ->
  <img src="https://github.com/user-attachments/assets/86568cef-31c0-42eb-ade4-8f55dfef0518" width="437px">
</ul>
<li>Cutscenes InicioDeTudo</li>
<ul>
  <li>Content/Objects/logo.xnb</li>
  <img src="https://github.com/user-attachments/assets/2897d46e-f02a-40d8-9cda-f235b5013c3a" width="328px"> ->
  <img src="https://github.com/user-attachments/assets/af3f0ee5-813e-4466-bb6b-1aa6f4890866" width="437px">
  <li>Content/Objects/logoEN.xnb</li>
  <img src="https://github.com/user-attachments/assets/06ab9091-8b85-44c5-8821-f6db05cad858" width="328px"> ->
  <img src="https://github.com/user-attachments/assets/765de317-1c02-4d7d-a4c3-512605de959a" width="437px">
</ul>
<li>Cutscenes da Princesa</li>
<ul>
<li>Content/Objects/Videos/margem_fase9.xnb</li>
  <img src="https://github.com/user-attachments/assets/27c4753b-b2c8-4b57-b78a-05e1cfe318d6" width="328px"> ->
  <img src="https://github.com/user-attachments/assets/ba06e426-7700-4a35-bcbd-0b6ceaeca155" width="437px">
<li>Content/Objects/Videos/margem_final.xnb</li>
  <img src="https://github.com/user-attachments/assets/321ef187-f5d6-4a6f-928e-8d815ef25160" width="328px"> ->
  <img src="https://github.com/user-attachments/assets/ca4ff125-a1c0-4c46-abd7-2de605ca9360" width="437px">
<li>Content/Objects/Videos/margem_princesa.xnb</li>
  <img src="https://github.com/user-attachments/assets/190d97bd-c53a-49d9-bffd-7eca9161384a" width="328px"> ->
  <img src="https://github.com/user-attachments/assets/3790cfac-a104-4a46-9f45-e0f8bdf47937" width="437px">
</ul>
<li>Fase 5: Ventaria (Corrigido a renderização da Ventaria)</li>
<ul>
  <li>Content/Objects/tornado_bg.xnb</li>
  <img src="https://github.com/user-attachments/assets/af4acd80-a2be-412d-9a10-e9e94257ae5f" width="200px"> ->
  <img src="https://github.com/user-attachments/assets/324fa882-ce66-4517-b2f2-8bc4629b4045" width="500px">
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


