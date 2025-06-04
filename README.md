<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width
 initial-scale=1.0">
  <title>Sustentabilidade em Ação</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
   <header>
     <h1>Sustentabilidade para um Futuro Melhor</h1>
     <nav>
         <ul>
           <li><a href="#oque-e">O que é Sustentabilidade?</a></li>
           <li><a href="#acoes">Ações Sustentáveis</a></li>
           <li><a href="#impacto">Nosso Impacto</a></li>
           <li><a href="#contato">Contato</a></li></li>
       <ul>
         </nav>
     </header>
     
     <main>
       <section id="o que-e" class="destaque">
         <h2>O Que É Sustentabilidade?</h2>
         <p>Sustentabilidade é a capacidade de suprir as necessidades do presente sem comprometer a capacidade das futuras gerações de atenderem suas próprias necessidades. Envolve equilíbrio entre o desenvolvimento econômico, a preservação ambiental e o bem-estar social.<p>
       </section>
       
       <section id="acoes">
         <h2>Ações Sustentáveis que Você Pode Tomar</2>
         <div class="acoes-lista">
             <div class="acao">
                 <img                                        src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fvivenciasustentavel.com.br%2Freciclagem-exemplos-e-dicas-para-reciclar-corretamente%2F&psig=AOvVaw2hSElj0fNDyjeSAjeLo99b&ust=1748012558052000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCODd7qKst40DFQAAAAAdAAAAABAY" alt="Reciclar">
               <h3>Reciclar</h3>
               <p>Separe o lixo corretamente para a reciclagem.</p>
           </div>
           <div class="acao">
               <img         src="https://via.placeholder.com/100/6B8E23/FFFFFF?Text=Economizar+Água" alt="Economizar Água">
             <h3>Economizar Água</h3>
             <p>Use a água de forma consciente, evitando desperdícios.</p>
           </div>
           <div class="acao">
               <img                                          src="https://via.placeholder.com/100/556B2F/FFFFFF?Text=Energia+Limpa" alt="Energia Limpa">
               <h3>Usar Energia Limpa</h3>
               <p>Opte por energias renováveis sempre que possível.</p>
           </div>
           <div class="acao">
               <img                          src="https://via.placeholder.com/100/3CB371/FFFFFF?Text=Consumo+Consciente"  alt="Consumo Consciente">
             <h3>Consumo Consciente</h3>
             <p>Pense antes de comprar e prefira produtos duráveis.</p>
           </div>
         </div>
       </section>
       
       <section id="impacto">
         <h2>Nosso Impacto no Planeta</h2>
         <p>Cada pequena ação contribui para um futuro mais sustentável. Juntos, podemos fazer a diferença na preservação do nosso planeta para as próximas gerações.</p>
         <div class="progresso">
             <div class="barra-progresso">
               <div class="progresso-valor"                id="progressoValor">0%</div>
           </div>
           <button id="botaoContador">Aumentar Consciência</button>
            </div>
        </section>

        <section id="contato">
            <h2>Entre em Contato</h2>
            <p>Tem alguma pergunta ou sugestão? Entre em contato conosco!</p>
            <form>
                <input type="text" placeholder="Seu Nome">
                <input type="email" placeholder="Seu Email">
                <textarea placeholder="Sua Mensagem"></textarea>
                <button type="submit">Enviar Mensagem</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Sustentabilidade em Ação</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

CSS:
body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #8FBC8F;
    color: white;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 10px 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

.destaque {
    background-color: #e0eee0;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 5px;
}

h2 {
    color: #556B2F;
}

.acoes-lista {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 20px;
}

.acao {
    background-color: white;
    padding: 15px;
    border-radius: 5px;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.acao img {
    width: 80px;
    height: 80px;
    margin-bottom: 10px;
    border-radius: 50%;
}

.progresso {
    margin-top: 30px;
    text-align: center;
}

.barra-progresso {
    background-color: #d3d3d3;
    width: 80%;
    height: 30px;
    margin: 10px auto;
    border-radius: 15px;
    position: relative;
}

.progresso-valor {
    background-color: #6B8E23;
    color: white;
    height: 100%;
    width: 0%;
    border-radius: 15px;
    line-height: 30px;
    text-align: center;
    position: absolute;
}

#botaoContador {
    background-color: #3CB371;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

#botaoContador:hover {
    background-color: #2E8B57;
}

#contato form {
    display: flex;
    flex-direction: column;
    width: 50%;
    margin: 20px auto;
}

#contato input,
#contato textarea,
#contato button {
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}

#contato button {
    background-color: #556B2F;
    color: white;
    border: none;
    cursor: pointer;
}

#contato button:hover {
    background-color: #3E541F;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: sticky;
    bottom: 0;
    width: 100%;
}

JS:
body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #8FBC8F;
    color: white;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 10px 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

.destaque {
    background-color: #e0eee0;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 5px;
}

h2 {
    color: #556B2F;
}

.acoes-lista {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 20px;
}

.acao {
    background-color: white;
    padding: 15px;
    border-radius: 5px;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.acao img {
    width: 80px;
    height: 80px;
    margin-bottom: 10px;
    border-radius: 50%;
}

.progresso {
    margin-top: 30px;
    text-align: center;
}

.barra-progresso {
    background-color: #d3d3d3;
    width: 80%;
    height: 30px;
    margin: 10px auto;
    border-radius: 15px;
    position: relative;
}

.progresso-valor {
    background-color: #6B8E23;
    color: white;
    height: 100%;
    width: 0%;
    border-radius: 15px;
    line-height: 30px;
    text-align: center;
    position: absolute;
}

#botaoContador {
    background-color: #3CB371;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

#botaoContador:hover {
    background-color: #2E8B57;
}

#contato form {
    display: flex;
    flex-direction: column;
    width: 50%;
    margin: 20px auto;
}

#contato input,
#contato textarea,
#contato button {
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}

#contato button {
    background-color: #556B2F;
    color: white;
    border: none;
    cursor: pointer;
}

#contato button:hover {
    background-color: #3E541F;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: sticky;
    bottom: 0;
    width: 100%;
}
