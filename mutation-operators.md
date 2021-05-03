# Incremental Strategy for Applying Mutation Operators Emphasizing Faults Difficult to be Detected by Automated Static Analyser

Vinícius Barcelos Silva, Cláudio Antonio Araujo, Edmundo Sérgio Spoto, and Auri M R Vincenzi. 2017. Incremental Strategy for Applying Mutation Operators Emphasizing Faults Difficult to be Detected by Automated Static Analyser. In Proceedings of SBES’17, Fortaleza, CE, Brazil, September 20–22, 2017, 10 pages. doi: [10.1145/3131151.3131169](https://doi.org/10.1145/3131151.3131169)

## 1. Fichamento de Conteúdo

Atualmente podemos encontrar aplicações de técnicas e critérios de testes que analizam o código de forma estática e eficáz. O Teste de Mutação é um conceito que tem como finalidade alterar os operações lógicos do código afim de identificar comportamentos não mapeados. Atravéz do framework Stryker, utilizado na linguagem JavaScript, podemos facilmente gerar os mutantes de forma simples e identificar as melhorias no código em questão. Um dos problemas do Teste de Mutação é o alto custo computacional devido ao grande número de mutantes gerados, que demandam tempo para a execução, e posterior análise de mutantes vivos para identificação de mutantes equivalentes. Desse modo, diferentes alternativas são empregadas para reduzir esses custos. Uma delas é diminuir o número de operadores de mutação que são utilizados, gerando-se apenas um subconjunto de todos os possíveis mutantes. Essas ferramentas emitem uma grande quantidade de avisos, alertando o testador sobre possíveis problemas que podem estar presentes no código fonte, sem a necessidade de execução do mesmo. Os resultados já obtidos indicam que não houve diferença estatística entre as diferentes estratégias investigadas, entretanto, a estratégia proposta é a que aplica de forma incremental operadores de mutação com menor sobreposição com os tipos de defeitos detectáveis pelo analisador estático investigado.

## 2. Fichamento Bibliográfico

-   _Correspondência Direta por Linha (CDL)_ tem como objetivo contar o número de mutantes identificados pela Splint.(página 27).
-   _Correspondência Direta por Linha Relativa (CDLR)_ permite determinar uma ordem incremental de aplicação dos operadores de mutação cuja qualidade será avaliada (página 28).
-   _Teste de mutação_ é um conceito que tem como finalidade alterar os operações lógicos do código afim de identificar comportamentos não mapeados do código (página 24).

## 3. Fichamento de Citações

-   _"O operador ORRN (Relational Operator Mutation) substitui a ocorrência de um operador relacional no programa original por todos os outros operadores relacionais existentes na linguagem C."_
-   _"O operador SSDL (Statement Deletion) remove um comando de cada vez do programa original para dar origem aos mutantes."_
-   _"Para que um op gere mutantes é necessário que o programa original contenha as estruturas sintáticas exigidas pelo operador para criar os mutantes."_
