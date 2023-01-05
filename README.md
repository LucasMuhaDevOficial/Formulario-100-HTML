<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto Front-End</title>
</head>
<body>
    
    <div class="campo">
        <h1 id="titulo">Cadastro De DEVs</h1>
        <p id="subtitulo">Complete Suas Informações</p>
        <br>
    </div class="campo">

    <fieldset class="Grupo">
        <div class="campo">
          <label for="Nome"><strong>Nome</strong></label>
          <input type="text" name="Nome" id="Nome">
        </div class="campo">

        <div class="campo">
            <label for="Sobrenome"><strong>Sobrenome</strong></label>
            <input type="text" name="Sobrenome" id="Sobrenome">
        </div class="campo">

        <div class="campo">
            <label for="Email"><strong>Email</strong></label>
            <input type="email" name="email" id="email">
        </div class="campo">
    </fieldset class="grupo"

    <div class="campo">
      <label for="Desenvolvimento"><strong>De Qual Lado Da Aplicação Você Desenvolve</strong></label>
      <label>
        <input type="radio" name="devweb" id="devweb" value="Front-End">Front-End
      </label>
      <label>
        <input type="radio" name="devweb" id="devweb" value="Back-End">Back-End
      </label>
      <label>
        <input type="radio" name="devweb" id="devweb" value="FullStack">FullStack
      </label>
    </div class="campo">
    <br>
    <div id="check">
        <label for="Tecnologias"><strong>Quais Tecnologias Que Utiliza</label>
        <label>
            <input type="checkbox" name="tecnologia1" id="tecnologia1" value="HTML">
            <label for="tecnologia1">HTML</label>
            <input type="checkbox" name="tecnologia2" id="tecnologia2" value="CSS">
            <label for="tecnologia2">CSS</label>
            <input type="checkbox" name="tecnologia3" id="tecnologia3" value="Javascript">
            <label for="tecnologia3">Javascript</label>
            <input type="checkbox" name="tecnologia4" id="tecnologia4" value="PHP">
            <label for="tecnologia4">PHP</label>
            <input type="checkbox" name="tecnologia5" id="tecnologia5" value="C#">
            <label for="tecnologia5">C#</label>
            <input type="checkbox" name="tecnologia6" id="tecnologia6" value="C++">
            <label for="tecnologia6">C++</label>
            <input type="checkbox" name="tecnologia7" id="tecnologia7" value="Java">
            <label for="tecnologia7">Java</label>
        </label>
    </div class="campo">

<div class="campo">
    <label for="Experiência"><strong>Experiência</label>
    <textarea row="6" style="width: 26em"></textarea>
</div class="campo">

<button class="botão" type="submit">Concluido!!!</button>

</body>
</html>
