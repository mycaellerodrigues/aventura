<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bai+Jamjuree:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;1,200;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
    <title>Em busca da cidade perdida</title>
</head>
<body>
    <main>
        <div class="passo ativo" id="passo-0">
            <img src="img/cenario-passo0.png" alt="">
            <p>Um dia desses, dentro de um livro da biblioteca da escola, eu descobri uma carta antiga sobre uma cidade perdida, escondida por riquezas e belezas naturais. Nessa carta, a autora deixa algumas pistas para encontrar essa cidade e eu decidi segui-las!</p>
            <button class="btn-proximo" data-proximo="1">Rio de Janeiro</button>
            <button class="btn-proximo" data-proximo="2">Pernambuco</button>
        </div>
        <div class="passo" id="passo-1">
            <p>Você começa sua jornada no Rio de Janeiro, subindo o Pico da Tijuca ao amanhecer para encontrar a primeira pista.</p>
            <button class="btn-proximo" data-proximo="3">Procurar a pista no topo do pico</button>
            <button class="btn-proximo" data-proximo="4">Desistir e voltar para casa</button>
        </div>
        <div class="passo" id="passo-2">
            <p>Em Pernambuco, você visita a histórica cidade de Olinda. Na carta, uma das pistas indica que para localizar a entrada para a cidade perdida você deve procurar a próxima pista em um dos pontos turísticos da cidade. Por qual você começa?</p>
            <button class="btn-proximo" data-proximo="5">Investigar as igrejas antigas</button>
            <button class="btn-proximo" data-proximo="6">Explorar as praias próximas</button>
        </div>
        <div class="passo" id="passo-3">
            <p>No topo do Pico da Tijuca, você encontra uma antiga inscrição apontando que a próxima pista está
                localizada no Amazonas.</p>
            <button class="btn-proximo" data-proximo="7">Seguir para o Amazonas</button>
        </div>

        <div class="passo" id="passo-4">
            <img src="img/cenario-passo4-voltar-casa.png" alt="imagem voltando para casa e desitindo da aventura">
            <p>Você decide que a aventura é grande demais e volta para casa, mas sempre se pergunta o que teria
                encontrado.</p>
        </div>

        <div class="passo" id="passo-5">
            <p>Nas igrejas de Olinda, você descobre um mapa antigo escondido atrás de um altar, apontando que a próxima
                pista está no Amazonas.</p>
            <button class="btn-proximo" data-proximo="7">Viajar para o Amazonas</button>
        </div>

        <div class="passo" id="passo-6">
            <p>Explorando as praias, você encontra uma caverna escondida, mas ela leva a um beco sem saída.</p>
            <button class="btn-proximo" data-proximo="8">Voltar e explorar as igrejas</button>
        </div>

        <div class="passo" id="passo-7">
            <p>No Amazonas, a busca pela cidade perdida se intensifica. Você se depara com um rio bifurcado.</p>
            <button class="btn-proximo" data-proximo="9">Seguir pelo rio à esquerda</button>
            <button class="btn-proximo" data-proximo="10">Seguir pelo rio à direita</button>
        </div>

        <div class="passo" id="passo-8">
            <p>De volta às igrejas, você finalmente encontra o mapa antigo. Agora, para o Amazonas!</p>
            <button class="btn-proximo" data-proximo="7">Seguir para o Amazonas</button>
        </div>

        <div class="passo" id="passo-9">
            <p>O rio à esquerda leva você a uma cachoeira escondida com inscrições antigas que revelam a entrada da
                cidade perdida.</p>
            <button class="btn-proximo" data-proximo="11">Explorar a cidade perdida</button>
        </div>

        <div class="passo" id="passo-10">
            <p>O rio à direita termina em uma área pantanosa. Apesar de belas vistas, não há sinais da cidade perdida
                aqui.</p>
            <button class="btn-proximo" data-proximo="12">Retornar e tentar o outro rio</button>
        </div>

        <div class="passo" id="passo-11">
            <img src="img/cenario-passo12-cidade-perdida.png" alt="encontrando uma cidade maravilhosa perdida no Amazonas">
            <p>Dentro da cidade perdida, você descobre tesouros inimagináveis e decide se dedicar a estudar e preservar
                este lugar</p>
        </div>

        <div class="passo" id="passo-12">
            <p>Retornando e escolhendo o rio à esquerda, você finalmente encontra a cachoeira escondida e as inscrições
                que levam à cidade perdida.</p>
            <button class="btn-proximo" data-proximo="11">Explorar a cidade perdida</button>
        </div>
    </main>
    <script src="script.js"></script>
</body>
</html>
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
56
57
58
59
60
61
62
63
64
65
66
67
68
69
70
71
72
73
74
75
76
77
78
79
80
81
82
arset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>

<body>
    <section class="principal container">
        <div class="container__caixa">
            <h1 class="container__titulo">Com o Combo+, você pode aproveitar a Alura+ e o Alura Língua por um preço
                único.</h1>
            <img src="img/Combo.png" alt="O combo+ é a junção do alura+ e o alura língua" class="container__imagem">
            <a href="www.alura.com.br" class="container__botao">Assine por 12x de R$ 120,00*</a>
            <a href="www.alura.com.br" class="container__botao botao_secundario">Assinar somente o Alura+</a>
            <p class="container__aviso">*O preço pode variar caso a assinatura seja feita em outros planos.</p>
        </div>
    </section>

    <section class="container secundario">
        <img src="img/Plataformas.png" alt="Um monitor e um celular com a alura plus aberta" class="secundario__imagem">
        <div class="container__descricao">
            <h2 class="descricao__titulo">Assista do seu jeito</h2>
            <p class="descricao__texto">Aproveite a tela grande da TV ou assista no tablet, laptop, celular e outros
                aparelhos. Nossa seleção de cursos não para de crescer.</p>
        </div>
    </section>

    <section class="container secundario">
        <div class="container__descricao">
            <p class="descricao__texto">
                Só o Combo+ oferece Alura+ e Alura Língua juntos para você ter acesso a cursos de diversas áreas da
                tecnologia e aprender inglês ou espanhol, onde e como quiser.
            </p>
            <a href="www.alura.com.br" class="container__botao secundario__botao" container>Assine o Combo+</a>
        </div>
        <img src="img/Telas.png" alt="Tela do alura+ e alura língua" class="secundario__imagem">
    </section>

    <section class="container secundario">
        <img src="img/Notebook.png" alt="Notebook com a página do curso HTML5 e CSS3 da Alura aberta"
            class="secundario__imagem">
        <div class="container__descricao">
            <h2 class="descricao__titulo">Baixe seus cursos</h2>
            <p class="descricao__texto">Baixe e assista quando e onde quiser. Assim, seus favoritos estão sempre com
                você, até mesmo sem internet.</p>
        </div>
    </section>
    
    <section class="dispositivos">
        <h2 class="dispositivos__titulo">Disponível nos seus dispositivos favoritos</h2>
        <ul class="dispositivos__lista">
            <li>
                <img src="img/tv.png" alt="Ícone de televisão">
                <h3 class="lista__item">TV</h3>
            </li>
            <li>
                <img src="img/computador.png" alt="Ícone de computador">
                <h3 class="lista__item">Computador</h3>
            </li>
            <li>
                <img src="img/celular.png" alt="Ícone de celular">
                <h3 class="lista__item">Celular</h3>
            </li>
        </ul>
    </section>

    <footer class="rodape">
        <img src="img/Logo.png" alt="Alura+" class="rodape__logo">
        <ul class="rodape__lista">
            <li class="lista__link">
                <a href="#">Idioma</a>
            </li>
            <li class="lista__link">
                <a href="#">Dispositivos compatíveis</a>
            </li>
            <li class="lista__link">
                <a href="#">Contrato de assinatura</a>
            </li>
            <li class="lista__link">
                <a href="#">Politica de privacidade</a>
            </li>
            <li class="lista__link">
                <a href="#">Proteção de dados no Brasil</a>
            </li>
            <li class="lista__link">
                <a href="#">Anuncios personalizados</a>
            </li>
            <li class="lista__link">
                <a href="#">Ajuda</a>
            </li>
        </ul>
        <p class="rodape__texto">® 2021 Alura, Alura+ e Alura Língua. Todos os direitos reservados. Serviço de
            assinatura paga. Conteúdo sujeito a disponibilidade.</p>
        <p class="rodape__texto">Alura+ é um serviço pago, baseado em assinatura e sujeito a termos e condições. O
            serviço Alura+ é comercializado por Aovs Sistemas de Informática S.A., Rua Vergueiro, 3185 - Liberdade, São
            Paulo - SP, 04101-300, Brasil e CNPJ 05.555.382/0001-33</p>
    </footer>
</body>

</html>
