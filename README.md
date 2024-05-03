<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="css/style.css">
  <title>Portifólio</title>
  <style>
*{
  margin: 0;
  padding: 0;
}
img{
  max-width: 100%;
  height: auto;
}
body{
  height : 100vh;
  background-color: #2B3233;
  box-sizing: border-box;
  color:aliceblue;
}
.titulo_destaque{
  color: #16F4F7;
}
span{
  color: #16F4F7;
  border: 1px solid #16F4F7;
  padding: 4px;
}
.apresentacao_conteudo_geral{
  width: 615px;
  display: flex;
  flex-direction: column;
  gap: 40px;
  margin-right: 40px;
}
.apresentacao{
  margin: 10%;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.apresentacao_conteudo_titulo{
  font-size: 36px;
  font-family: 'Krona One', sans-serif;
}
.apresentacao_conteudo_texto{
  font-size: 24px;
  font-family: 'Montserrat', sans-serif;
}
.apresentacao_links{
  display: flex;
  justify-content: space-between;
  gap: 30px;
}
.apresentacao_botao{
  background-color: #16F4F7;
  width: 280px;
  text-align: center;
  border-radius: 16px;
  font-size: 24px;
  padding: 21.5px 0;
  /*primeiro valor é o padding top e bottom, segundo valor é o padding left e right*/
  text-decoration: none;
  font-family: 'Montserrat', sans-serif;
  color: #2B3233;
}

  </style>
</head>
<body>
  <header>
    
  </header>
  <main class="apresentacao">
    <section class="apresentacao_conteudo_geral">
      <h1 class="apresentacao_conteudo_titulo">
        Eleve seu negócio digital a outro nível <strong class="titulo_destaque">com um <span>Front-end</span> de qualidade!</strong>
      </h1>
      <p class="apresentacao_conteudo_texto">
        Olá! Sou Estêvão Felipe, desenvolvedor Front-end com especialidade em <strong>React, HTML e CSS</strong>. Ajudo pequenos negócios e designers a colocarem em prática boas ideias. Vamos conversar?
      </p>
      <div class="apresentacao_links">
        <a class="apresentacao_botao" href="https://www.instagram.com/estevao_felipe/" target="_blank">
          <b>Instagram</b>
        </a>
        <a class="apresentacao_botao" href="https://github.com/TevimF" target="_blank">
          <b>GitHub</b>
        </a>
      </div>
    </section>
  </main>
  <footer>

  </footer>
</body>
</html>
