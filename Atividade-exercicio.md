## APA (ATIVIDADE PRÁTICA DE APRENDIZAGEM)

ESTRUTURA:

O desenvolvimento de software em geral permite que problemas possam ser solucionados de mais de uma forma muitas vezes, e com isso, diferentes propostas de soluções computacionais podem ser implementadas.

As propostas podem variar em relação apenas a sua aparência de uma implementação para outra utilizando recursos oferecidos por uma linguagem específica ou com o uso de frameworks baseados nestas, como foi citado ao longo no material com JavaScript servindo de base, mas existindo alternativas como React e AngularJS, por exemplo.

A lógica pode ser alterada para que um mesmo resultado seja obtido, de acordo com as linhas de raciocínio tomadas por base para gerar as funcionalidades solicitadas em cada diferente problema.

E por fim, é possível que uma mesma lógica possa ser implementada de diferentes formas se a linguagem utilizada possuir recursos para permitir mais de uma forma de se realizar um mesmo processamento.

Com base nessa ideia de recursos alternativos oferecidos por uma linguagem de programação, observe o exemplo de script completo trazido na tabela 9 da unidade III do material.

 

<!DOCTYPE html>

<html>

<body>

<h2>JavaScript - Exemplo 21</h2>

<hr>

<p><b>** MENU DE OPÇÕES **</b></p>

<p>1. Inserir Dados</p>

<p>2. Consultar Dados</p>

<p>3. Editar Dados</p>

<p>4. Excluir Dados</p>

<p><b>Informe uma Opção:</b></p>

<input id="opcao" value="0" />

</br>

<button onclick="funcao()">Opção</button>

<p id="ex21"></p>

<script>

function funcao() {

  opcao = document.getElementById("opcao").value;

  switch (opcao) {

    case "1":

      mensagem = "Escolhida a Inserção de Dados.";

      break;

    case "2":

      mensagem = "Escolhida a Consulta de Dados.";

      break;

    case "3":

      mensagem = "Escolhida a Edição de Dados.";

      break;

    case "4":

      mensagem = "Escolhida a Exclusão de Dados.";

      break;

    default:

      mensagem = "Opção Inválida.";

  }

  document.getElementById('ex21').innerHTML = mensagem;

}

</script>

</body>

</html>

 

Digamos que você trabalha numa equipe de desenvolvimento e foi verificado que a forma como é feita a escolha pela mensagem a ser exibida para o usuário como resultado da opção escolhida tenha que ser modificado.

No exemplo, o processo foi realizado com a utilização do comando SWITCH...CASE, gerando um script funcional, mas foi pedido que o comando seja substituído por uma nova estrutura com base no comando IF...ELSE de forma que se mantenha igualmente funcional, e exibindo as mesmas mensagens para as mesmas escolhas.

Como seria uma versão alternativa do script com base nesta mudança de estrutura condicional? Proponha um novo script ajustado para esta atividade.


