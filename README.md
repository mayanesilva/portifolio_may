# portifolio_may
Portifólio para documentar o processo de aprendizado da disciplina de programação de Programação Web

<h1>Atividade 01</h1>

Descrição: Criar um projeto no web script para calcular Media ponderada de duas notas 

Dúvida: Como sera pedido ao sistema para calcular as 2 notas.

Solução da dúvida: Temos que criar uma nota1 e peso1, nota2 e peso2. e assim montar o codigo ultilizando esssas 4 notas 

<h1> Aula do dia   26/05/2023     </h1>

O que eu aprendi? Que ultilizando o gogle.script.run podemos chamar a função do sevidor e assim mostrar o resultado do calculo das 4 notas.


<h1>Atividade 02</h1>

Descrição: Retorna  do servidor para pagina ultilizando a função WithSuccerHandler(function)

Dúvida: como adiconar esta função ao codigo 

Solução da dúvida: comprendi que precisamos do WithSuccerHandler(function) para conseguir executar essa informação

<h1> Aula do dia   01 / 06 / 2023  </h1>

O que eu aprendi?

Temos uma função que envia dados ao servido, porém para receber precisamos de uma função pra enviar e outra para receber e para isso
ultilizamos Google.Script.rum.WithSuccessHandler( ) 
no parâmetro precisamos da função responsável de receber os dados, logo depois é só colocar a função que estar no servido, e se tiver parâmetro passa os parâmetros, caso não tenha é só deixar os parâmetros vazio


<h1>Atividade 03</h1>

Descrição: Desenvolvemos um projeto, contendo uma página
web que envie ao servidor, dados de e-mail e senha fornecidos por um usuário

Dúvida: como exibir uma mensagem
que mostrasse ao usuário se o login foi bem sucedido ou não. 

Solução da dúvida: apois colocarmos no codigo.gs que tem como a funcão do doget, que trata-se de uma requisição http do tipo doget, adicionamos:

return 'Login bem sucedido!';
}else{
  return 'Login não sucedido!';
}
E assim aparecera se deu certo ou nao
  
<h1> Aula do dia   02/06/2023  </h1>

O que eu aprendi?
Para desenvolvermos um projeto como esse, precisamos acrescentar a função  google.script.run.withSuccessHandler para que assim possamos enviar os dados e receber o valor de retorno do servido, caso noa utilizássemos, não seria possivel obter valor de retorno do servido.


<h1>Atividade 04</h1>

Descrição: Criamos uma funçao para quando emplantarmos, nao ser necessario ficarmos atualizando o URL, pois a propria funçao farar isso.

Dúvida:
como chamar a funçao que necessitamos, para conseguir execulta a proposta da aula.

Solução da dúvida:

precisamos do seguinte codigo 
<? var url= pegarUrl()?>   ( serve para chamara a funçao do URL)

<form action="" method= "post"> (irar preencher a funçao)

<h1> Aula do dia    15/06/2023  </h1>

O que eu aprendi?
que nao é necessario ficarmos atualizando o link do URL a uma funçao propria para isso que sera no automatico!


<h1>Atividade 05</h1>

Descrição: Criar um codigo com a requisiçao post que enviarar ao servidor, e la colhera todos os dados que serar enviado para a planilha do google

Dúvida: se cada parte do codigo, que é preciso para conseguir enviar os dados para planilha do gogle, Trabalhava sozinhos?!

Solução da dúvida: Para execulta é necessarios dos tres função pois uma interliga as outras:

var planilha = SpreadsheetApp.openById ("")

var tabela = planilha.getSheetByName('tabela_livros')

tabela.appendRow([])

Utilizando a função document.getElementById()

<h1> Aula do dia    16/06/2023  </h1>

O que eu aprendi? Para coseguiremos passar os dados do servidor para a planilha do google e para ser possivel acessar a planilha, precisamos do codigo a seguir:

var planilha = SpreadsheetApp.openById ("");  (no parâmetro precisamos adicionar o id da planilha.)

var tabela = planilha.getSheetById ("");  (no parâmetro serar adcionado o nome q colocamos na planilha.)

var appendRow ([])  (no parâmetro colocaremos os valores da variavel que é enviada para o formulario e guardando na planilha.)



<h1> Atividade 06</h1>

Descrição: Desenvolver um projeto Google App
Script que contenha um formulário HTML com os seguintes campos:

 A distância da casa de Joana até a casa de sua mãe, em km;
 O consumo de seu carro, em km/litro;
 O preço da gasolina no posto onde Joana abastece.


Dúvida: O formulario nao estava recebendo  o conteúdo de um elemento HTML

Solução da dúvida: estava faltando o (innerhtml)

<h1> Aula do dia 20/06/2023 </h1>

oque eu aprendi: (toFixed) aprendi que esta função é ultilizada para arredondar o valor desejado.
                Exemplo: 21.123 , o valor fica 21.12





<h1> Atividade 07</h1>

Descrição:

Dúvida:

Solução da dúvida:

<h1> Aula do dia  /  /2023 </h1>

oque eu aprendi: 



oque eu aprendi:
