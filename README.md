<!DOCTYPE html>
<html>

<head>    
<style type="text/css">
* {
    margin:0;
    padding:0;
}

/* Style the top navigation bar */
.topnav {
    
  overflow: hidden;
  background-color: #808080;

}

.topnav a {
  float: left;
  display: block;
  color: whitesmoke;
  text-align: center;
  padding: 42px 16px;
  text-decoration: none;

}
/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 10%;
  background: #ccc;
  padding: 10px;
  height: 50%;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
    
  float: left;
  padding: 20px;
  width: 85%;
  background-color: #f1f1f1;

  
}

/* Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>

<body>
    
    <h1>Filmes Incríveis</h1>

    <div class="topnav">
        <a href="professor.html">Home</a>
        <a href="#">Sobre nós</a>
        <a href="#">Serviços</a>       
        <a href="#">Contato</a>
      </div>
<div>
    <section>
        
        <nav>
          <ul>
            <li><a href="enzo.html" target="iframe_a">- Meu amigo Enzo</a></li>
            <li><a href="extraordinario.html"target="iframe_a">- Extraordinario</a></li>
            <li><a href="estrela.html"target="iframe_a">- Nasce uma Estrela</a></li>
            <li><a href="destruicao.html"target="iframe_a">- Destruição Final: O Último Refúgio</a></li>
            <li><a href="enzo.html" target="iframe_a">- Titanic</a></li>
            <li><a href="extraordinario.html"target="iframe_a">- Ave de Rapina</a></li>
            <li><a href="estrela.html"target="iframe_a">- Alice no pais das maravilhas</a></li>
            <li><a href="destruicao.html"target="iframe_a">- A Fantástica fábrica de chocolate</a></li>
            <li><a href="enzo.html" target="iframe_a">- Pantera Negra</a></li>
            <li><a href="extraordinario.html"target="iframe_a">- Vingadores: Ultimato</a></li>
            <li><a href="estrela.html"target="iframe_a">- Nós</a></li>
            <li><a href="destruicao.html"target="iframe_a">- Toy Story 4</a></li>
            <li><a href="enzo.html" target="iframe_a">- Lady Bird - A Hora de Voar </a></li>
            <li><a href="extraordinario.html"target="iframe_a">- Missão Impossível Efeito Fallout</a></li>
            <li><a href="estrela.html"target="iframe_a">- O Irlandês</a></li>
            <li><a href="destruicao.html"target="iframe_a">- Corra! </a></li>
            <li><a href="enzo.html" target="iframe_a">- Casablanca </a></li>
            <li><a href="extraordinario.html"target="iframe_a">- Mad Max: Estrada da Fúria</a></li>
            <li><a href="estrela.html"target="iframe_a">- Homem-Aranha no Aranhaverso</a></li>
            <li><a href="destruicao.html"target="iframe_a">- Moonlight: Sob a Luz do Luar</a></li>
            
          </ul>
        </nav>
        
        <article>
          
            <iframe src=""  name="iframe_a" width="100%" height="600px" frameborder="0" src="iframe.html" title="Iframe Example"></iframe>

        </article>
        
    </section>
</div>

</body>

</html>
