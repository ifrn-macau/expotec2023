---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


<style>
   .slideshow-container {
    
    width: 90%;
    position: relative;
    margin: auto;

}

.slideshow {
    display: none;
}


.slideshow img { width:100%; }

.prev,
.next {
    cursor: pointer;
    position: absolute;
    top: 50%;
    width: auto;
    margin-top: -22px;
    padding: 16px;
    color: white;
    font-weight: bold;
    font-size: 18px;
    transition: 0.6s ease;
    border-radius: 0 3px 3px 0;
}

.next {
    right: 0;
    border-radius: 3px 0 0 3px;
}

.prev:hover,
.next:hover {
    background-color: rgba(0, 0, 0, 0.8);
}


.legenda {

    width: auto;
    color: #fdfdfd;
    font-size: 0.9em;
    padding:5px;
    position: absolute;
    bottom: 18%;
    text-align: center;
    background-color: rgba(0, 0, 0, 0.4);
    left: 10%;

}

.numeracao {

    color: #f2f2f2;
    font-size: 12px;
    padding: 8px 12px;
    position: absolute;
    top: 0;

}

.paginacao { 
  
    width:100%; 
    float:left;
    margin: 10px 0;
    text-align: center;

}

.dot {

    cursor: pointer;
    height: 13px;
    width: 13px;
    margin: 0 4px;
    border-radius: 50px;
    background-color: #24a424;
    display: inline-block;
    transition: background-color 0.6s ease;
}

.ativo,
.dot:hover {
    background-color: #242424;
}


.fade {
    -webkit-animation-name: fade;
    -webkit-animation-duration: 2s;
    animation-name: fade;
    animation-duration: 2s;
}

@-webkit-keyframes fade {
    from {
        opacity: .4;
    }
    to {
        opacity: 1;
    }
}

@keyframes fade {
    from {
        opacity: .4;
    }
    to {
        opacity: 1;
    }
}

/*960PX BREAKPOINT - Ajustando o texto para desktop*/
@media (min-width:60em){


    .legenda   { font-size:2em; padding:8px; }
    .paginacao { margin:20px 0; }
    .dot       { width:18px; height:18px; }
}



.div-principal-1{
    margin-bottom:40px;
    
}

.organizadores{
    display:flex;
    flex-direction:column;
}
.org-row{
    display:flex;
    justify-content:space-around;
    
    
}
.org-col{
    display:flex;
    flex-direction:column;
    align-items: center;
    
    
}


</style>

<div class="div-principal-1">
    <img src="./images/logo_expotec2.png" class="org-img">
    </div>
      
      
# Apresentação da Expotec 2023

Bem-vindo à Expotec 2023, o evento de tecnologia do ano que reúne mentes brilhantes, inovação e conhecimento de ponta! A Expotec é um encontro anual que oferece uma plataforma única para profissionais, estudantes e entusiastas da tecnologia explorarem as tendências mais recentes e discutirem o futuro do setor.

# Sobre o Evento

A Expotec é uma oportunidade incomparável para:

- Conectar-se com especialistas do setor.
- Participar de palestras e workshops envolventes.
- Explorar novas tecnologias e produtos em exposições interativas.
- Compartilhar conhecimentos e experiências com colegas.


<div class="slideshow-container">
<div class="slideshow fade">
                <div class="numeracao"></div>
                <img src="./images/anterior/Foto1.jpeg" alt="slide">
                <div class="legenda">IFRN Campus Macau</div>
            </div>

<div class="slideshow fade">
                <div class="numeracao"></div>
                <img src="./images/anterior/Foto2.jpeg" alt="slide">
                <div class="legenda">Expotec 2022</div>
            </div>

 <div class="slideshow fade">
                <div class="numeracao"></div>
                <img src="./images/anterior/Foto3.jpeg" alt="Slide">
                <div class="legenda">Expotec 2022</div>
            </div>

<div class="slideshow fade">
                <div class="numeracao"></div>
                <img src="./images/anterior/Foto4.jpeg" alt="Slide">
                <div class="legenda">Expotec 2022</div>
            </div>
<div class="slideshow fade">
                <div class="numeracao"></div>
                <img src="./images/anterior/Foto5.jpeg" alt="Slide">
                <div class="legenda">Expotec 2022</div>
            </div>
<div class="slideshow fade">
                <div class="numeracao"></div>
                <img src="./images/anterior/Foto6.jpeg" alt="Slide">
                <div class="legenda">Expotec 2022</div>
            </div>
 <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
            <a class="next" onclick="plusSlides(1)">&#10095;</a>
        
</div>

<div class="paginacao">
            <span class="dot" onclick="currentSlide(1)"></span>
            <span class="dot" onclick="currentSlide(2)"></span>
            <span class="dot" onclick="currentSlide(3)"></span>
            <span class="dot" onclick="currentSlide(4)"></span>
            <span class="dot" onclick="currentSlide(5)"></span>
            <span class="dot" onclick="currentSlide(6)"></span>
        </div>




# Temas em Destaque

Este ano, a Expotec 2023 se concentrará em uma variedade de temas emocionantes, incluindo:

- Inteligência Artificial e Aprendizado de Máquina.
- Cibersegurança e Privacidade de Dados.
- Desenvolvimento de Software e Engenharia de Software.
- Internet das Coisas (IoT) e Conectividade.
- Inovação e Empreendedorismo Tecnológico.

# Como Participar

A participação na Expotec 2023 é aberta a todos os interessados em tecnologia e inovação. Para se juntar a nós, siga estas etapas simples:

1. Registre-se no site da Expotec 2023.
2. Escolha as palestras e workshops que mais lhe interessam.
3. Marque a data em seu calendário e prepare-se para uma experiência tecnológica inspiradora.

# Data e Local

- **Data**: [Inserir Data]
- **Local**: [Inserir Local]

# Como Chegar

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3973.6997061244997!2d-36.577515025900475!3d-5.15194525206833!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7b6d52d1aaf6cc1%3A0x236b55c0207db87e!2sInstituto%20Federal%20de%20Educa%C3%A7%C3%A3o%2C%20Ci%C3%AAncia%20e%20Tecnologia%20Rio%20Grande%20do%20Norte%2C%20Campus%20Macau!5e0!3m2!1spt-BR!2sbr!4v1698404051770!5m2!1spt-BR!2sbr" width="500" height="350" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

# Inscreva-se Agora!

Junte-se a nós na Expotec 2023 para uma jornada fascinante pelo mundo da tecnologia. Este é o local onde ideias se transformam em inovação, e onde você pode fazer parte dessa transformação.

Para obter mais informações e inscrições, visite [o site oficial da Expotec 2023](inserir link do site).

Estamos ansiosos para vê-lo na Expotec 2023, onde o futuro da tecnologia é moldado!
Lembre-se de substituir "[Inserir Data]", "[Inserir Local]" e "[inserir link do site]" pelas informações reais sobre a data, local e link do site oficial da Expotec 2023. Esse texto de apresentação em formato Markdown pode ser usado em seu site, blog ou em qualquer plataforma que suporte a formatação Markdown.

# Organização

<div class="organizadores">
<div class="org-row">
<div class="org-col">
<img src="./images/organizadores/leandro.jpeg">
<p><strong>Leandro Lispector</strong><br>Presidente</p>
</div>
<div class="org-col">
<img src="./images/organizadores/julio.jpeg">
<p><strong>Júlio Cesar</strong><br>Vice-Presidente </p>
</div>
<div class="org-col">
<img src="./images/organizadores/pv.jpg">
<p>Yuri Marcedo</p>
</div>

</div>


<div class="org-row">
<div class="org-col">
<img src="./images/organizadores/yuri.jpg">
<p>Yuri Marcedo</p>
</div>
<div class="org-col">
<div style="width:163px; height:235px; background-color:gray; border:1px solid black"> </div>
<p>outro</p>
</div>

<div class="org-col">
<div style="width:163px; height:235px; background-color:gray; border:1px solid black"> </div>
<p>outro</p>
</div>

</div>

</div>




<script type="text/javascript">

let slides = document.querySelectorAll('.slideshow');
        let dots = document.querySelectorAll('.dot');
        let slideIndex = 1;
        let timeoutID;

        const showSlides = (n) => {
            let i;

            if (n > slides.length) {
                slideIndex = 1;
            }
            if (n < 1) {
                slideIndex = slides.length;
            }

            for (i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";
            }

            for (i = 0; i < slides.length; i++) {
                dots[i].setAttribute('class', 'dot');
            }


            slides[slideIndex - 1].style.display = 'block';
            dots[slideIndex - 1].setAttribute('class', 'dot ativo');
            clearTimeout(timeoutID);
            timeoutID = setTimeout(autoSlides, 4000);
        };

        const plusSlides = (n) => {
            showSlides(slideIndex += n);
        };

        const currentSlide = (n) => {
            showSlides(slideIndex = n);
        };

        function autoSlides() {
            let i;

            for (i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";
            }

            slideIndex++;
            if (slideIndex > slides.length) {
                slideIndex = 1;
            }

            for (i = 0; i < slides.length; i++) {
                dots[i].setAttribute('class', 'dot');
            }

            slides[slideIndex - 1].style.display = "block";
            dots[slideIndex - 1].setAttribute('class', 'dot ativo');
            timeoutID = setTimeout(autoSlides, 4000);
        }

        autoSlides();

</script>