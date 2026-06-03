hello-worId
===========

My first repository on GitHub.
set "GIT_AUTHOR_NAME=octocat"
set "GIT_AUTHOR_EMAIL=octocat@nowhere.com"
set "GIT_AUTHOR_DATE=Tue, 03 Apr 2018 02:02:30 +0900"
set "GIT_COMMITTER_NAME=Sally Johnson"
set "GIT_COMMITTER_EMAIL=USER_EMAIL"
set "GIT_COMMITTER_DATE=Tue, 10 Apr 2018 06:25:08 +0900"
git commit -m init --reset-author
git tag YOUR_COMMIT_SHA_NUMBER HEAD
git show YOUR_COMMIT_SHA_NUMBER --pretty=fuller


<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Sem Filtro Tarot</title>

<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600;700&family=Caudex:wght@400;700&display=swap" rel="stylesheet">

<style>

:root{
  --gold:#c8a96b;
  --gold-light:#e4c98a;
  --bg:#0b0b0d;
  --panel:#151518;
  --text:#e6dfd1;
}

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  background:var(--bg);
  color:var(--text);
  font-family:'Caudex', serif;
  min-height:100vh;
  background-image:
    radial-gradient(circle at top, rgba(200,169,107,.15), transparent 40%);
}

header{
  text-align:center;
  padding:80px 20px;
}

h1{
  font-family:'Cinzel', serif;
  color:var(--gold);
  font-size:3rem;
  letter-spacing:3px;
}

.subtitulo{
  margin-top:15px;
  font-size:1.2rem;
  opacity:.85;
}

.container{
  width:min(1100px,90%);
  margin:auto;
}

.card{
  background:var(--panel);
  border:1px solid rgba(200,169,107,.35);
  border-radius:18px;
  padding:30px;
  margin-bottom:30px;
  box-shadow:
      0 0 20px rgba(200,169,107,.08);
}

.card h2{
  color:var(--gold-light);
  margin-bottom:15px;
  font-family:'Cinzel', serif;
}

.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
}

.tarot-item{
  padding:25px;
  border:1px solid rgba(200,169,107,.25);
  border-radius:12px;
  text-align:center;
  transition:.3s;
}

.tarot-item:hover{
  transform:translateY(-4px);
  border-color:var(--gold);
}

.botao{
  display:inline-block;
  margin-top:20px;
  padding:12px 28px;
  color:black;
  background:var(--gold);
  text-decoration:none;
  border-radius:30px;
  font-weight:bold;
}

footer{
  text-align:center;
  padding:40px 20px;
  color:#9f9788;
}

</style>
</head>

<body>

<header>
  <h1>SEM FILTRO TAROT</h1>
  <p class="subtitulo">
    Mensagens diretas das cartas. Sem rodeios. Sem máscaras.
  </p>
</header>

<div class="container">

  <section class="card">
    <h2>Sobre a Consulta</h2>
    <p>
      Uma leitura focada nos arquétipos, padrões ocultos,
      desafios e oportunidades presentes no momento atual.
    </p>
  </section>

  <section class="card">
    <h2>Modalidades</h2>

    <div class="grid">

      <div class="tarot-item">
        <h3>Tarot</h3>
        <p>Leitura completa dos arcanos.</p>
      </div>

      <div class="tarot-item">
        <h3>Baralho Cigano</h3>
        <p>Questões objetivas e práticas.</p>
      </div>

      <div class="tarot-item">
        <h3>Arquétipos</h3>
        <p>Análise simbólica e espiritual.</p>
      </div>

    </div>

    <a href="#" class="botao">Agendar Consulta</a>

  </section>

</div>

<footer>
  © Sem Filtro Tarot
</footer>

</body>
</html>
