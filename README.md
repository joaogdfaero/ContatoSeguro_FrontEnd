# Desafio | Frontend

Este é um **CRUD** apenas no **lado do cliente**, ou seja, irá manter as informações armazenadas no **localStorage** do navegador.

As regras dos campos sendo utilizados são as seguintes:
* Nome: obrigatório para preenchimento
* E-mail: obrigatório para preenchimento
* Telefone: não obrigatório
* Data de nascimento: não obrigatório
* Cidade onde nasceu: não obrigatório

3 bugs foram inseridos no código. Um no HTML, um no CSS (vide o arquivo layout.jpg para referência) e um no JS (localizado na classe MyCrud).
Além disso, você deve implementar o método de remoção (localizado na classe MyCrud).

Serão avaliadas suas capacidades de leitura de código e resolução de problemas. Não se preocupe caso não consiga terminar tudo, nos envie o teste mesmo assim, destacando, logo abaixo, suas principais dificuldades e como fez para resolver os problemas.

# Resposta do participante
Após uma análise geral do código, a primeira etapa para identificar bugs foi testar o sistema e suas funcionalidades. Fazendo isso, identificou-se os seguintes bugs levando em conta os requisitos do projeto:
1) HTML: campo cidade não é obrigatório.
2) CSS: logo não está centralizada.
3) JS: problema no método de edição, não funciona corretamente.
4) Delete: método delete não foi implementado.

Após identificar e listar os bugs, a correção dos mesmos foi relativamente simples:
1) HTML: [remove a tag "required" do campo.](https://github.com/joaogdfaero/ContatoSeguro_FrontEnd/commit/d217b26d5da26b4a385860a475f412269eb79100)
2) CSS: [cria um estilo centralizado para a logo.](https://github.com/joaogdfaero/ContatoSeguro_FrontEnd/commit/a0583eef44ae2b186271f107a259b6c781db221b)
3) JS: [função edit atualiza os campos com o valor incorreto.](https://github.com/joaogdfaero/ContatoSeguro_FrontEnd/commit/05a7fab8cf2751932daffe4ab5e23fca803f91f0)
4) Delete: [implmenta o método delete utilizando a método "splice".](https://github.com/joaogdfaero/ContatoSeguro_FrontEnd/commit/927161c26812a9674b033430b5267eb01be6f6b5)

OBS:
- O método delete pode ser aprimorado para exibir uma mensagem de confirmação ao usuário antes de remover o objeto.

Links Úteis utilizados na solução:
- Documentação do localStorage: https://developer.mozilla.org/pt-BR/docs/Web/API/Window/localStorage
- Método splice: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/splice 

