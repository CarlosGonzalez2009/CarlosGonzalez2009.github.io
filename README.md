<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Convencendo Papai a me dar um Bulldogue Francês</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px auto;
        }
    </style>
    <script>
        function verificarCPF() {
            var CPF = parseInt(prompt("Digite os últimos 5 números do seu CPF (para eu saber se você é realmente meu pai):"));
            if (CPF === 77864) {
                var Resp = parseInt(prompt("Ok melhor pai do mundo, agora é com você. Vai fazer o seu filho o mais feliz do mundo? Digite 1 para sim ou 2 para não:"));
                if (Resp === 1) {
                    alert("Você fez a melhor escolha da sua vida e a da do seu filho, te amo muito!Obrigadoooooooooooooooooo!!!!!!!!");
                } else if (Resp === 2) {
                    var Resp2 = parseInt(prompt("Vou te dar mais uma chance. Ok melhor pai do mundo, agora é com você. Vai fazer o seu filho o mais feliz do mundo? Digite 1 para sim ou 2 para não:"));
                    if (Resp2 === 1) {
                        alert("Você fez a melhor escolha da sua vida e a da do seu filho, te amo muito!Obrigadoooooooooooooo!!!!!!!!!");
                    } else {
                        alert("Que pena :(");
                    }
                }
            } else {
                alert("Você não é meu pai!");
            }
        }
    </script>
</head>
<body>
    <header>
        <h1>Convencendo Papai a me dar um Bulldogue Francês</h1>
    </header>
    <section>
        <p>Querido Papai,</p>
        <p>Você sabia que os Bulldogs Franceses são conhecidos por sua personalidade amorosa e por serem ótimos companheiros?</p>
        <img src="https://www.petlove.com.br/images/breeds/193442/profile/original/buldogue_frances-p.jpg?1532538793/bulldog1.jpg" alt="Bulldog Francês fofo">

        <p>Eles são tão adoráveis e fofinhos. Olha só essas carinhas!</p>
        <img src="bulldogue.jpg" alt="Bulldog Francês fofo">

        <p>Eles são conhecidos por serem calmos, carinhosos e se dão bem com crianças, como eu!</p>
        <p>Por favor, Papai, posso ter um Bulldog Francês para chamar de meu? Prometo cuidar dele e amá-lo muito!</p>
        <p>Com amor,</p>
        <p>Seu filho Carlinhos, para Carlos.</p>

        <button onclick="verificarCPF()">Clique aqui para verificar se você é meu pai</button>
    </section>
</body>
</html>
