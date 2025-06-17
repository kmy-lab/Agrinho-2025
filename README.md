# Agrinho-2025
quando [flag verde v] clicado
ir para x: -100 y: -100
mostrar
mudar para o fundo [Campo v]
diga [Bem-vindo ao campo! Aqui é onde produzimos alimentos para o país!] por 3 segundos

quando [seta para a direita v] pressionada
mudar para o fundo [Cidade v]
ir para x: 100 y: 100
diga [Agora estou na cidade! Aqui, as pessoas trabalham com tecnologia e comércio.] por 3 segundos

quando [seta para a esquerda v] pressionada
mudar para o fundo [Campo v]
ir para x: -100 y: -100
diga [Voltando para o campo, onde o trabalho é manual e agrícola!] por 3 segundos

quando [clique na árvore v] feito
diga [As árvores no campo ajudam a purificar o ar e proporcionam sombra para os animais.] por 2 segundos

quando [clique no carro v] feito
diga [Os carros da cidade são essenciais para o transporte de mercadorias e pessoas.] por 2 segundos

quando [clique na vaca v] feito
diga [As vacas produzem leite, um alimento básico tanto para as pessoas da cidade quanto do campo.] por 2 segundos
quando [seta para a direita v] pressionada
se <toque em [produto da cidade v]> então
    aumentar [pontos v] por 1
    mudar fundo para [Campo v]
    diga [Produto da cidade coletado!] por 2 segundos
