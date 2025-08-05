# 🧾 Suíte de Testes - Filtro "Ativos (Active)"

Este repositório faz parte do meu aprendizado em QA, onde documento a criação de suítes de teste usando critérios de aceite escritos em Gherkin. O objetivo aqui é desenvolver uma visão crítica para validar funcionalidades com clareza e organização, preparando um material que facilite análise e automação.

O foco é aprimorar a escrita técnica, simular cenários reais de teste e mostrar a importância de uma suíte de testes bem construída para garantir qualidade.


 **Site utilizado nos testes:** [TodoMVC - React](https://todomvc.com/examples/react/dist/) 

<details>
  <summary><strong>📋 Clique aqui para ver a suíte de testes</strong></summary>

<br>

<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Cenário</th>
      <th>Caso de Teste (Gherkin)</th>
      <th>Prioridade</th>
      <th>Severidade</th>
      <th>Resultado Esperado</th>
      <th>Resultado Obtido</th>
      <th>Defeitos</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>CT01</td>
      <td>Exibir apenas itens ativos</td>
      <td>Dado que possuo itens pendentes e concluídos<br>Quando clico no filtro "Active"<br>Então apenas os itens pendentes devem ser exibidos</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Então apenas os itens pendentes devem ser exibidos</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT02</td>
      <td>Ocultar itens concluídos</td>
      <td>Dado que tenho ao menos um item concluído<br>Quando clico no filtro "Active"<br>Então os itens concluídos não devem ser exibidos na lista</td>
      <td>Média</td>
      <td>Alta</td>
      <td>Então os itens concluídos não devem ser exibidos na lista</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT03</td>
      <td>Itens ativos com checkbox desmarcado</td>
      <td>Dado que existem itens pendentes<br>Quando clico no filtro "Active"<br>Então os itens devem aparecer com checkbox desmarcado</td>
      <td>Média</td>
      <td>Média</td>
      <td>Então os itens devem aparecer com checkbox desmarcado</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT04</td>
      <td>Contador atualizado corretamente</td>
      <td>Dado que possuo três itens pendentes<br>Quando clico no filtro "Active"<br>Então o contador deve exibir "3 items left"</td>
      <td>Alta</td>
      <td>Média</td>
      <td>Então o contador deve exibir "3 items left"</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
    <tr>
      <td>CT05</td>
      <td>Filtro "Active" continua funcional após adicionar item</td>
      <td>Dado que o filtro "Active" está ativo<br>Quando adiciono um novo item pendente<br>Então o novo item deve ser exibido automaticamente na lista filtrada</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Então o novo item deve ser exibido automaticamente na lista filtrada</td>
      <td>Passou conforme esperado</td>
      <td>—</td>
      <td>Concluído</td>
    </tr>
  </tbody>
</table>

</details>


---
