# OAntiBolsonarismo_na_regiao_mais_Bolsonarista

nada feito ainda, por enquanto só esboço.....

A ideia é estar estudando os determinantes da atitude política antibolsonarista em uma região de forte votação antibolsonarista

Para isso pegaremos dados eleitorais e demográficos de 28 cidades da região do Alto Vale do Itajaí altamente votante em Bolsonar.

O n= número de casos é 28 (que são as cidades)

Todas as variáveis da análise passarão por um processo que as transformação em dicotômicas. (1 para MAIORES, 0 para menor propensão)

Nossa variável a ser explicada (chamada de dependente) é a atitude não bolsonarista - incialmente é feito uma soma de votos nulos, brancos e Haddad no segundo turno de 2018. depois é solicitado que a variável se divida em duas (separada pela mediana) os valores com maiior propensão antibolsonarista serão classificados como presença do atribuito (valorados como 1) e os com menor propensão, o oposto catalogados como zero.

Todas as outras variáveis explicativas (dados demográficos e eleitorais) serão catalogadas em 1 e 0 (sendo q 1 repersenta maior propensão e zero o oposto, por exemplo se for 1 em % ensino superior, significa que a cidade tem % de formados em ensino superiro acima da mediana da região). As variáveis demográficas utilizadas serão % de formados em curso superiro, população da cidade, % área rural. As variáveis políticas testadas serão % votação em Lula 2006 e  % ciro gomes2018(terceiro colocado)

rodaremos alguns modelos e analisaremos todos em uma arquivo rmarkdown- aqui nessa pasta(em PDF também)

teste 1 - Um cenário será a testado com as variáveis demográficas explicando a dependente

teste 2 - Outro somente com Lula2006 explicando para testar continuidade

Teste 3 - Outro modelo completo com todas as variáveis demográficas acima destacadas, bem como Lula 2006

Teste 4 - m modelo adicional somente com ciro2018(para ver se os terceiros colocados foram mais propensos ao bolsonarismo ou ao antibolsonarismo)

Teste 5 - Outro modelo adicional acresce as variáveis demográficas

A ideia de dicotomizar tudo é retirada do clássico trabalho de  Mark Franklin, Thomas T. Mackie, 
Henry Valen et al., Electoral Change: Responses to Evolving Social and Attitudinal Structures in Western 
Countries (Cambridge: Cambridge University Press, 1992

O script da manipulação dos dados constam nesse link ->

A base original consta no github- antes da recodificação nesse link->

A base manipulada com todas as variáveis dicotomizadas consta nesse link ->

Os resultados e análises constam nesse endereço -> 
