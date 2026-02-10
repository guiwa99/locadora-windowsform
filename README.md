# locadora-windowsform

# Projeto locadora - Tema livre
Criar um projeto com o intuito de ser um software para adminstração de uma locadora (pode ser de carro, moto, livros). O software deve conter funcionalidades como cadastrar um novo item, editar um item existente, excluir um item existente, listar todos os itens cadastrados, listar apenas um item, alugar um item e devolver esse mesmo item. Deve existir formas diferentes de login, uma para um usuário normal (um cliente, por exemplo), e outra para um adminstrador.

## Requisitos
1. Tela inicial para escolher tipo de acesso (usuário ou adminstrador).

2. Tela de login para administrador.
- Precisa ter usuário e senha.

3. Tela de login para o usuário.
- Pode ser usuário e senha ou apenas um usuário.

4. Tela principal com a listagem de todos os itens cadastrados, exibindo apenas algumas informações para identificar o item.
- Ordenar em ordem alfabética
- Tanto o usuário quanto o adminstrador podem ter acesso.

5. Tela para cadastrar um novo item, pedindo as informações necessárias para o adminstrador preencher e poder salvar o item.
- No mínimo 5 informações do item. 
- Exemplo:
    - Se for um carro: modelo, marca, preço, cor, ano.
- Apenas o administrador tem acesso.

6. Tela para editar um item existente, pedindo as informações necessárias para editar e salvar o novo item. 
- Obs: Na edição, é possível que nem todos os campos do item possam ser alterados, como por exemplo, o nome, e sim apenas informações que realmente possam mudar, como a cor de um carro, se for uma locadora de carro.
- Apenas o administrador tem acesso.

7. Poder excluir um item, com a opção de confirmação via modal.
- Apenas o administrador tem acesso.

8. Tela para alugar um item. Deve pedir nome, cpf e telefone para da pessoa que está alugando.
- Não deve ser possível alugar um filme que está atualmente alugado por outra pessoa.
- Cada item deve ter uma categoria, e o prazo de entrega deve ser calculado com base na data atual e na categoria. Exemplos:
    - Carro premium: data entrega = hoje + 9 dias
    - Carro normal: data entrega = hoje + 15 dias
- Tanto o usuário quanto o adminstrador podem ter acesso a tela de alugar.

9. Poder devolver um item.
- Obs: Não deve ser possível devolver um item que não está alugado.
- Tanto o usuário quanto o adminstrador podem ter acesso.

10. Tela para listar apenas um item, detalhando todos as informações dele.
- Deve exibir obrigatoriamente a data de entrega e se o item está em atraso ou não. Em atraso se a data de entrega for menor que a data atual. Em dia, se a data de entrega for maior que a data atual.
- Tanto o usuário quanto o adminstrador podem ter acesso.

11. Tela principal com a listagem de todos os usuários cadastrados, exibindo todas informações do mesmo.
- Ordenar em ordem alfabética
- Tanto o usuário quanto o adminstrador podem ter acesso.

12. Tela para cadastrar um novo usuário, pedindo as informações necessárias para o adminstrador preencher e poder salvar o usuário.
- No mínimo 5 informações do usuário.
- Exemplo:
    - Nome, cpf, email, telefone, data de nascimento.
- Apenas o administrador tem acesso.

13. Tela para editar um usuário existente, pedindo as informações necessárias para editar e salvar o usuário.
- Obs: Na edição, é possível que nem todos os campos do item possam ser alterados, como por exemplo, o nome, e sim apenas informações que realmente possam mudar, como o e-mail, telefone etc.
- Apenas o administrador tem acesso.

14. Poder excluir um usuário, com a opção de confirmação via modal.
- Apenas o administrador tem acesso.