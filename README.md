É uma LandingPage de duas Vagas de emprego:

--- HTML ---
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Temos vagas para Programador e Guarda Noturno</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="./style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Cabeçalho -->
    <header class="bg-primary text-white py-3"></header>
        <div class="container d-flex justify-content-between align-items-center">
            <h1 class="m-0"><svg xmlns="http://www.w3.org/2000/svg" height="30px" viewBox="0 -960 960 960" width="30px" fill="#e3e3e3"><path d="M146.67-160q-27 0-46.84-19.83Q80-199.67 80-226.67v-506.66q0-27 19.83-46.84Q119.67-800 146.67-800h666.66q27 0 46.84 19.83Q880-760.33 880-733.33v506.66q0 27-19.83 46.84Q840.33-160 813.33-160H146.67ZM480-454.67 146.67-670v443.33h666.66V-670L480-454.67Zm0-66.66 330.67-212H150l330 212ZM146.67-670v-63.33V-226.67-670Z"/></svg> <font face="Kelvinch"> Vagas disponíveis na programing company. <svg xmlns="http://www.w3.org/2000/svg" height="40px" viewBox="0 -960 960 960" width="40px" fill="#e3e3e3"><path d="M146.67-160q-27 0-46.84-19.83Q80-199.67 80-226.67v-506.66q0-27 19.83-46.84Q119.67-800 146.67-800h666.66q27 0 46.84 19.83Q880-760.33 880-733.33v506.66q0 27-19.83 46.84Q840.33-160 813.33-160H146.67Zm0-66.67h666.66v-424H146.67v424ZM300-288l-46.67-46.67 103-104-104-104L300-589.33l150.67 150.66L300-288Zm186.67 2.67V-352h226.66v66.67H486.67Z"/></svg> P. C. </br></h1>
        </div>
        <p>______________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________</p>
    </header>

    <!--Sobre as Vagas-->
    <section id="about" class="py-5">
        <div class="container">
            <img src="./imagens/img-01.jpg" alt="Vaga de Programador" style="width: 250px; height: 300px;">
            <img src="./imagens/img-02.jpg" alt="Vaga de segurança" style="width: 400px; height: 300px;">
            <p>       </p>
            <div class="row align-items-right">
                <div class="col-md-6">
                    <h2 class="fw-bold">Procura-se: Programador e Guarda Noturno</h2>
                    <p class="lead">Tem conhecimentos em  linguagens de programação? ou tem habilidades de segurança e vigilância noturna? Então uma destas vagas pode ser sua. Basta apertar em “Join now!” e mande seu currículo</p>
                </br>
                    <a href="#contact" class="btn btn-primary btn-lg mt-3" >Join now!</a>
                </div>
            </div>
       </div>
    </section>

    <!--Habilidades necessárias-->
    <section id="about" class="py-5">
        <div class="container">
            <div class="col-md-6">
                <div class="paragraph">
                    <h2 class="card-tittle">Programador:</h2>
                    <p class="lead">Formatação de Documentos;</br>
                        Criação de Índices;</br>
                        Referências cruzadas;</br>
                        Proteção de Documentos;</br>
                        Conhecimentos em  Python ou Java;</br>
                        Conhecimentos em HTML. </p>
                </div>
            </div>
    </div>
    <div id="about2" class="py-5">
        <div class="container">
            <div class="col-md-6">
                <div class="paragraph">
                    <h2 class="card-tittle">Segurança:</h2>
                    <p class="lead">Vigilância e observação;</br>
                        Resposta a emergências;</br>
                        Tecnologia da segurança;</br>
                        Condicionamento Físico;</br>
                        Resoluções de conflito;</br>
                        Conhecimento dos PS. </p>
                </div>
            </div>
        </div>
    </div>
    </section>

    <!--contate-nos-->
    <section id="contact" class="py-5">
        <div>
            <div class="container">
                <h2 class="text-center fw-bold">Contate-nos:</h2>
                <form class="mt-4">
                    <div class="mb-3">
                        <label class="texto-grande" for="name" class="form-label">Seu Nome completo:</label>
                        <input type="text" class="form-control" id="name" placeholder="Digite seu nome: " required>
                    </div>
                    <div class="mb-3">
                        <label class="texto-grande" for="email" class="form-label">Seu E-mail de Contato:</label>
                        <input type="email" class="form-control" id="email" placeholder="Digite seu e-mail:" required>
                    </div>
                    <div class="mb-3">
                        <label class="texto-grande" for="message" class="form-label">Envie seu Curículo:</label>
                        <form action="/upload" method="post" enctype="multipart/form-data">
                            <input type="file" id="fileUpload" name="fileUpload">
                            <br><br>
                        <button type="submit" class="btn btn-primary w-100" href="#contact" class="btn btn-primary btn-lg mt-3"> Enviar</button><svg xmlns="http://www.w3.org/2000/svg" height="30px" viewBox="0 -960 960 960" width="30px" fill="#e3e3e3">  Enviar </button>
                        </form>
                </form>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p class="m-0">&copy; 2025 George R. Boguchevski. Todos os direitos reservados.</p>
    </footer>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
 --- CSS ---

 .h2{
    font-size: 2.5rem;
}


.p{
    font-size: 1.2rem;
}

.texto-grande{
    font-size: 25px;
}

@media(max-width:768px){
    .h2{
        font-size: 2rem;
    }


    .p{
        font-size: 1rem;
    }


    .card-title{
        font-size: 1.125rem;
    }


    .card-text{
        font-size: 0.875rem;
    }
}
