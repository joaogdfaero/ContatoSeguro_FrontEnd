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
_Responda aqui quais foram suas dificuldades e como fez para encontrar e resolver os problemas ao enviar a solução_

Após uma análise geral do código, a próxima etapa para identificar bugs foi testar o sistema e suas funcionalidades. Fazendo isso, identificou-se o bug no HTML (o campo cidade estava como obrigatório)
e também notou-se que o método de edição não funcionava corretamente, trocando os campos editados pelo próprio nome do campo. Comparando a página do CRUD com o arquivo layout.jpg também notou-se que a logo não estava centralizada. 
Após identificar e listar os bugs, a correção dos mesmos foi relativamente simples. 

Observações:
- O método delete pode ser aprimorado para exibir uma mensagem de confirmação ao usuário antes de remover o objeto.
- O código pode ser melhorado para evitar a repetição de código, por exemplo, usando funções para formatar os campos de entrada de dados.

Links Úteis utilizados na solução:
- Documentação do localStorage: https://developer.mozilla.org/pt-BR/docs/Web/API/Window/localStorage
- Método splice: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/splice 

TASKS:
- [x] Bug no HTML: cidade não é obrigatória.
- [x] Bug no CSS: centraliza a logo.
- [x] Bug no JS: problema no método de edição.
- [x] Feature: Método de remoção (Delete).