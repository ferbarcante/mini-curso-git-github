# Mini-curso de Git e Github
<h1> O que é? </h1>
<h2>Projeto de Software</h2> 
<p>Conjunto de arquivos de código de vários desenvolvedores que compõem a produção de um software final.</p>
<h2>O que é uma CLI?</h2>
<p>É uma sigla para “Command Line Interface”, as CLI’s são utilizadas por diversas aplicações e funcionam de forma facilitar o envio de comandos aos softwares através do terminal.</p>
<h2>Repositório</h2>
<li> É onde os arquivos do seu projeto são armazenados juntamente com todas as versões anteriores.</li>
<li>É legal quando estiver em equipe criar como organização pois ai todos terão aquele repositório como seu.</li>
<h1>Github</h1>
<h2>Commit</h2>
<p>É uma fotografia do seu código em um determinado momento no tempo quando fazemos um commit estamos salvando uma versão do nosso código </p>
<h2>Git clone -  clone < URL ></h2>
  <p>Ele faz uma cópia do próprio projeto que você quer trabalhar e traz tudo para sua máquina.</p>
<ol>
  <li>Copiar o link no code.</li><br>
  <li>git clone &lt;url do repositório&gt;</li><br>
  <li>Agora pegou o repositório e trouxe para sua máquina.</li><br>
</ol>
 <h1>Comandos para Commit</h1>
 <h2>Git status</h2>
<p>Sempre verifique o que foi mudado antes de commitar, isso impede que coisas indesejáveis vão para o repositório. Tudo o que está em vermelho é algo novo que fizemos e que não está no repositório ainda mas está na pasta.</p>
  <h2>Git add</h2>
  <p>Podemos escolher quais arquivos vão ou não ao nosso repositório. Podemos colocar por nome de arquivo ou por um ponto que pegara todos os arquivos que foram alterados. </p>
  <h2>commit -m “mensagem”</h2>
  <p>Serve para nomear o commit e sabermos qual alteração foi feita</p>
  <h1>Branches</h1>
  <p>Usamos para que nossa modificação não altere a do colega. São como extensões do tronco principais que tem seu trabalho próprio.</p>
  <h2>Criando uma branch:</h2>
  <ol>
  <li>Vá para o GitHub e git clone</li><br>
  <li>Crie a branch com git branch "nome da branch"</li><br>
  <li>Para entrar na branch git checkout "nome da branch"</li><br>
  <li>Touch para criar arquivo na branch</li><br>
  <li>Git add</li><br>
  <li>Git commit -m</li><br>
  <li>Git push --set-upstream origin</li><br>
</ol>
