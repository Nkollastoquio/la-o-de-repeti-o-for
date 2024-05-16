🚀##laço de repetição##🚀

* Um trabalho aonde foi incluido tres tipos dee musicas para poder seleciomar e aparecera um alert da musicas sele cionadas 

    💿 ## estilos de musicas ## 💿
    * Pagode
    * Mtg
    * Eletro Funk
    * rap
    * Trap
    * Funk
    * sertanejo
    * Eletronica
     
    💻 codigos ultilizados 💻
    
    ## codigo HTML ##
![capa](img/Captura%20de%20tela%202024-05-16%20091833.png) 
  
  ## explicação do codigo ##

 * O código HTML define um formulário de login com campos para nome de usuário e senha, além de um botão de envio.
 
*  O código JavaScript é armazenado em um arquivo chamado script.js, que é referenciado na parte inferior do arquivo HTML.

 * O JavaScript contido em script.js contém uma função chamada validateForm() que é chamada quando o formulário é enviado. Essa função verifica se os campos de nome de usuário e senha estão preenchidos. Se algum campo estiver vazio, a função retorna false, impedindo o envio do formulário e exibindo uma mensagem de alerta.

 * Este código pode ser utilizado para criar formulários de login simples com validação básica de entrada do usuário.

## Explicação do Código JavaScript

O código JavaScript a seguir é responsável por contar quantas opções foram selecionadas em um elemento de seleção de múltiplas escolhas em um formulário HTML.
## codigo JavaScript ##
```javascript
function howMany(selectObject) {
  var numeroSelecionadas = 0;
  for (var i = 0; i < selectObject.options.length; i++) {
    if (selectObject.options[i].selected) {
      numeroSelecionadas++;
    }
  }
  return numeroSelecionadas;
}

var btn = document.getElementById("btn");
btn.addEventListener("click", function () {
  alert(
    "Total de opções selecionadas: " +
      howMany(document.selectForm.tipoMusica),
  );
}); 

 * A função howMany recebe um objeto selectObject, que é um elemento <select> do HTML. Ela percorre todas as opções desse elemento e conta quantas estão selecionadas.

* Em seguida, é selecionado o botão com o ID "btn" e adicionado um ouvinte de evento para o evento de clique. Quando o botão é clicado, uma mensagem de alerta é exibida com o total de opções selecionadas, chamando a função howMany e passando o elemento <select> como argumento.

* Este código pode ser usado para fornecer feedback instantâneo ao usuário sobre quantas opções ele selecionou em um formulário.
