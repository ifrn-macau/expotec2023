---
layout: page
title: Certificados
permalink: /certificados/
---


<style>
            .expansivel {
            height: 50px; /* Defina a altura inicial da div */
        overflow: hidden; /* Esconda o conteúdo extra */
        border: 1px solid black;
        transition: height 0.3s; /* Adicione uma transição suave de altura */
        background-color: #F8F8FF;
        border-radius: 20px;
        margin-top:10px;
        margin-bottom:10px;
        
}

.expansivel:hover {
           background-color: #DCDCDC;
        
}



.conteudo-expansivel {
  display: flex; /* Inicialmente, o conteúdo está oculto */
  flex-direction:column;
  background-color:#F0F8FF;
  
}
.detalhes{
    border-bottom: 1px solid black;
    padding: 20px;
    
}
.titulo-conteudo{
    margin-left:20px;
    margin-top:5px;
}
        </style>

<div class="expansivel" id="div-terca-1" onclick="expandirDiv('div-terca-1')">
        <h4 class="titulo-conteudo">Oficinas</h4>
        <div class="conteudo-expansivel">
            <div class="detalhes">
          <h4>ANSIEDADE NA CONSTRUÇÃO DA RESILIÊNCIA EMOCIONAL</h4>
            <p><a href="https://drive.google.com/drive/folders/1fSipaMRkd4tQ7TkT_etMrnq6aLpv5LhN?usp=sharing" target="_blank">Link dos certificados</a></p>
            <h4>Título:</h4>
            <p>Link dos certificados</p>
        </div>
        
                                                   
</div>
      </div>

<div class="expansivel" id="div-terca-2" onclick="expandirDiv('div-terca-2')">
        <h4 class="titulo-conteudo">Minicursos</h4>
        <div class="conteudo-expansivel">
            
<div class="detalhes">
                <h4 >AS TECNOLOGIAS NECESSARIAS PARA O MERCADO DE TRABALHO</h4>
                  <p><a href="https://drive.google.com/drive/folders/1xcD24YuLVhZOlpCpweZAsF11HwAwppCW?usp=sharing" target="_blank">Link dos certificados</a></p>
                  <h4 >Descrição: 2</h4>
                  <p>uma descrição aqui 2</p>
              </div>
              
                        
</div>
</div>




<script>
        
        function expandirDiv(id) {
            
  var div = document.getElementById(id);
  var conteudo = div.querySelector(".conteudo-expansivel");
  if(div.style.height==""){
    div.style.height="50px";
  }
  
  if (div.style.height === "50px") {
    div.style.height = "200px"; // Ajuste a altura desejada ao expandir
    conteudo.style.display = "flex"; // Exibe o conteúdo ao expandir
  } else {
    div.style.height = "50px"; // Volte à altura inicial ao recolher
    conteudo.style.display = "none"; // Oculta o conteúdo ao recolher
  }
}
      </script>
