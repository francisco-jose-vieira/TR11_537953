<h1 align="center">TRABALHO 11</h1>

<h2>Baixando os arquivos</h2>
<p>O primeiro passo para rodar o programa é baixar os arquivos necessários, para isso, vá no terminal do seu computador e digite:</p>

<code>
> git clone https://github.com/francisco-jose-vieira/TR10_537953.git
</code>
<br>

<hr>

<h2>Gerando as bibliotecas</h2>
<p>Para gerar as bibliotecas necessárias paraa rodar o código, vá no terminal do seu computador e digite:</p>

<code>
> gcc -c TR4_537953.c
</code>

<br>

<p>Note que o arquivo <span style="font-weight: bold; color: tomato">TR4_537953.o</span> será criado nos seus arquivos, essa é a biblioteca necessária para executar o programa.</p>

<hr>

<h2>Gerando o executável:</h2>
<p>Para gerar o arquivo executável vá ao terminal e digite:</p>


<code>
> gcc .\TR4_537953.o main.c -o main
</code>

<br>

<p>Note que para o comando anterior funcionar é necessário já ter os arquivos <span style="font-weight: bold; color: tomato">TR4_537953.o, TR4_537953.h, TR4_537953.c e main.c</span> na sua pasta.</p>

<p>Explicação:

<li><span style="font-weight: bold; color: tomato">.\TR4_537953.o</span> é a Biblioteca usada na execução do código.</li>
<li><span style="font-weight: bold; color: tomato">main.c</span> é a parte principal do código, a primeira parte que vai executar do seu programa.</li>
<li><span style="font-weight: bold; color: tomato">-o</span> é uma flag utilizada para nomeação de arquivos.</li>
<li><span style="font-weight: bold; color: tomato">main</span> é a nomeação do arquivo executável resultante (normalmente main.exe).</li>
</p>

<hr>
<h2>Executando o programa</h2>
<p>Finalmente para executar o programa vá ao seu terminal e digite:</p>
Linux:
<br>
<code>> ./main</code>

<br>
Windows:
<br>
<code>> ./main.exe</code>

<hr>