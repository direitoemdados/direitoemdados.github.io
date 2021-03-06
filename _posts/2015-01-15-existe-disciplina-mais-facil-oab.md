---
layout: post
title: "Existe uma Disciplina mais fácil na Segunda Fase do Exame da OAB? Um exemplo de viés de seleção"
author: "Guilherme Jardim Duarte"
---

Ontem li um texto interessante no [ConJur](http://www.conjur.com.br), de Alvaro de Azevedo Gonzaga, intitulado ["Estudo da FGV mostra quem passa no exame da Ordem"](http://www.conjur.com.br/2015-jan-14/alvaro-gonzaga-estudo-fgv-mostra-quem-passa-exame-ordem?utm_source=dlvr.it&utm_medium=twitter). O texto apresenta alguns dados retirados de um [relatório](http://fgvprojetos.fgv.br/sites/fgvprojetos.fgv.br/files/relatorio_2_edicao_final.pdf) da FGV Projetos, em parceria com o Conselho Federal da OAB. O [Relatório "Exame da Ordem em Números"](http://fgvprojetos.fgv.br/sites/fgvprojetos.fgv.br/files/relatorio_2_edicao_final.pdf) fornece estatística descritiva sobre examinandos e Instituições Superiores às quais estão vinculados. 

É apresentada uma série de estatísticas interessantes (não descobri se divulgam o banco de dados, por enquanto me contento em discutir os resumos), mas um tema em específico me interessou. Há uma tabela comparando a aproveitamento médio (porcentagem de candidatos que passou) na prova discursiva do II ao XIII Exame Unificado:

![Tabela - Aproveitamento Média](/img/tabela_gv.png)

Para quem não conhece o Exame da Ordem, ele é realizado em duas fases: uma primeira prova objetiva com conteúdo abrangente de várias áreas do Direito e uma segunda, composta por uma peça profissional e quatro questões práticas, de uma área específica escolhida pelo candidato. Para essa segunda fase, há 7 áreas a serem escolhidas: Direito Administrativo, Direito Civil, Direito Constitucional, Direito Empresarial, Direito Penal, Direito do Trabalho e Direito Tributário.

Alvaro Gonzaga, no texto do Conjur, trouxe uma discussão oportuna:

> Ouço alguns folclores nos corredores de faculdades e cursinhos que basicamente profetizam o seguinte:

> “A melhor área para se prestar na segunda fase é Penal ou Trabalho, isso porque são matérias do dia a dia, vemos situações de violência reportadas cotidianamente, bem como estabelecemos relações laborais constantemente. Isso gera uma falsa aderência natural para o candidato que escolhe essas matérias.”

> Dos folclores negativos, embora também envolvam relações cotidianas, temos o Direito Civil como líder. Quando alguém diz que irá prestar Civil na segunda fase:

> “Você é louco? Civil? Você tem ideia de quantas peças existem em civil?”

Lembro que, quando prestei o exame, ouvia histórias semelhantes: "Cuidado com Penal. Todos prestam essa disciplina e a instituição está dificultando a prova para que ninguém passe." 

A questão é: é possível com a tabela identificar uma área mais difícil que a outra? Uma resposta ingênua seria comparar os aproveitamentos médios nas áreas e verificar qual deles é maior. É uma resposta ingênua, porque é provável que isso nos trará conclusões incorretas por um problema de [VIÉS DE SELEÇÃO](http://en.wikipedia.org/wiki/Selection_bias). Explico o que é isso.
Primeiro, vou plotar um gráfico das séries históricas dadas nas tabelas para enxergarmos melhor os dados.

![Figura 1 - Aproveitamento médio por Exame Unificado](/img/figura1_oab.png)

Dá para verificar olhando a tabela e o gráfico que quem presta Civil, Administrativo e Constitucional apresenta em média um aproveitamento melhor que as outras áreas. Isso quer dizer que é mais vantajoso prestar uma dessas áreas? Não significa, porque comparar médias em grupos distintos nos traz conclusões, na maior parte das vezes, errada. Um exemplo clássico (baseado no ["Mostly Harmless Econometrics"](http://www.amazon.com/Mostly-Harmless-Econometrics-Empiricists-Companion/dp/0691120358)) é saber se tratamento médico melhora a saúde de indivíduos. Se compararmos indicadores e médias de saúde de indivíduos que vão ao médico com os de indivíduos que não vão, poderíamos talvez chegar a uma conclusão imprópria de que ir ao médico é prejudicial à saúde. Isso ocorre porque aqueles que procuram o médico já devem possuir um problema de saúde prévio.

O viés de seleção significa que alguns membros são mais prováveis a aparecerem num grupo que no outro. No exemplo médico, os dois grupos não apresentam um nível de saúde semelhante, pelo contrário, os que buscam tratamento (1 º grupo) possuem uma saúde prejudicada em relação aos que não buscam (2º grupo). No exemplo do Exame da Ordem, o viés de seleção se apresenta porque os indivíduos que escolhem essas disciplinas na 2ª Fase são provavelmente diferentes daqueles que escolhem outras, em média. Talvez, por exemplo, aqueles que escolhem Civil ou Constitucional são aqueles que se prepararam bem (há de se recordar que anteriormente, só havia 3 disciplinas, Penal, Tributário e Trabalho e poderia haver uma tendência de candidatos menos preparados escolherem estas).

Uma forma de se eliminar o viés de seleção seria alocar aleatoriamente pessoas para as diversas provas e nesse caso, comparar as médias. A aleatorização é capaz de obter grupos em médias semelhantes e assim comparáveis. Se pudéssemos sortear as pessoas que vão prestar cada prova, teríamos medidas mais comparáveis.

Uma conclusão: não escolha a disciplina da 2º fase interpretando mal os dados do relatório.

Mas ainda sobra uma outra questão mais geral: mantendo tudo constante, escolher uma área é mais vantajoso  que escolher outra? É possível, por exemplo, que a prova de Constitucional seja mais fácil que as de outras áreas, mantendo um nível de dificuldade e outras variáveis constantes (por ter menos peças a se estudar)? Talvez possamos responder essa questão, mas para isso deveríamos delinear uma estratégia de pesquisa capaz de detectar essa causalidade ("[estratégia de identificação](http://home.cerge-ei.cz/jurajda/rms07b.pdf)"). Falaremos sobre isso em outro post.