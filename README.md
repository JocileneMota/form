<!DOCTYPE html>
<html lang="pt">
  <head>
    <meta charset="UTF-8">
    <title >Form</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1 id="title">Formulário de Pesquisa</h1>
    <p id="description">Uma pesquisar rápida sobre você</p>

    <form id="survey-form">
    <fieldset>
      <label id="name-label">Nome:<input placeholder="Digite seu nome" id="name" type="text" required></label>
      <label id="email-label">E-mail:<input placeholder="Digite seu e-mail" id="email" type="emai" required></label>
      <label id="number-label">Idade(opcional):<input placeholder="Idade" id="number" type="number" min="12" max="110"></label>
    </fieldset>
      <fieldset>
    <label>Qual sua atução no mercado de trabalho?
    <select id="dropdown">
      <option value="">Selecione uma opção</option>
      <option value="1">Estudante</option>
      <option value="2">Trabalhando</option>
      <option value="3">Estagiando</option>
      <option value="4">Outro</option>
      <option value="5">Prefiro não dizer</option>
    </select>
    </label>
    </fieldset>
    <fieldset>
      <label><input type="radio"></label>
      <label><input type="radio"></label>
    </fieldset>
    <fieldset>
      <label>Descreva caracteristicas sua:
        <textarea rows="3" cols="30" placeholder="Digite seu cometário aqui..."></textarea>

      </label>

    </fieldset>
    <fieldset>
      <label>
        <button id="submit">enviar</button>
        </label>
    </fieldset>
    </form>
  </body>
</html>
