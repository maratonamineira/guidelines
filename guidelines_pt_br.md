# Guidelines

Aqui se encontra as sugestões obrigatórias (:stuck_out_tongue:) a serem seguidas para desenvolver e organizar a Maratona Mineira de Programação.
As regras e sugestões descritas aqui são inspiradas em experiências de edições passadas da Maratona Mineira de Programação.
Para as guidelines do diretor de prova, veja aqui: <http://maratona.ime.usp.br/manual18.pdf>


Este documento está separado em três seções.<br/>
A primeira seção contém as sugestões a serem seguidas para escrever e criar problemas para a prova.<br/>
Na segunda seção, descrevemos como deve ser a infraestrutura no local da prova.<br/>
Na terceira seção, descrevemos dicas e sugestões sobre o gerenciamento dos melancias.<br/>

## Criação da Prova
TODO: Escrever uma introdução para esta seção.

1. **Crie problemas em temas variados.**<br/>
   Existem vários temas que podem ser usados para criar problemas da maratona, e.g.: grafos, teoria dos números, estrutura de dados, etc. Uma boa prova deve conter uma ampla gama de temas.

2. **Organize a prova de maneira a ter problemas com vários níveis de dificuldade.**<br/>
   Em linhas gerais, uma boa prova da maratona deverá conter problemas de vários níveis de dificuldade. Idealmente, nenhum time deveria zerar a prova, ou fechar ela antes do blind. Além disso, tendo uma prova com vários níveis de dificuldade, o placar final tende a formar uma "escadinha", distinguindo melhor os times de acordo com o número de problemas resolvidos.

3. **Sugestões para o problema mais fácil.**<br/>
  3.1. A entrada deverá conter apenas inteiros.<br/>
  3.2. A saída deverá conter apenas inteiros, ou ser um problema de decisão.<br/>
  3.3. A solução para o problema mais fácil não deverá precisar de loops.<br/>
  Justificativa: Muitos alunos iniciantes, não sabem lidar com strings ou floats. Assim, deveremos nos ater a sempre criar um problema fácil, com uma solução simples.

4. **Tente não escrever problemas de decisão.**<br/>
   Nos problemas onde a saída esperada é somente "sim" ou "nao", competidores podem tentar escrever heurísticas para passar o problema.
   Assim, para estes problemas é mais difícil de garantir que o conjunto de casos de teste esteja robusto.
   Caso você ainda queira escrever um problema de decisão, você pode pedir um contra-exemplo no caso do "nao", ou a descrição completa da solução que justifique o "sim".
   Exemplo: No problema do troco, você pedir que os competidores imprimam não só se é possível dar o troco, mas quais moedas utilizariam para tal. 
   Esta regra pode ser ignorada no problema mais fácil.

5. **Sempre escreva um checker de soluções.**<br/>
   O checker é o script que checa a corretude das soluções dos problemas.<br/>
   Dica: Em alguns problemas, múltiplas saídas podem ser consideradas corretas, e isto pode dificultar a escrita de um checker.
   Para facilitar este processo, existem algumas técnicas que podem ser usadas, como pedir a solução em ordem lexicográfica.

6. **Sempre escreva um validator do input.**<br/>
   O validator do input é o script que checa se os arquivos de teste respeitam as restrições estabelecidas no enunciado do problema.<br/>
   Um bom validator deverá checar os limites da entrada, e restrições estabelecidas pelo enunciado do problema.<br/>
   Alterações no enunciado podem refletir alterações no validator.

7. **O pacote de um problema deverá ter pelo menos duas soluções corretas de pessoas distintas.**<br/>
   Todos os programadores são passíveis de erros, mesmo o Tourist. Assim, é comum o autor do problema errar alguns detalhes de implementação.
   Portanto, é importante que outras pessoas implementem soluções corretas para o problema. De preferência, sem ter lido previamente a solução esperada.

8. **O pacote de um problema deverá ter pelo menos uma solução "errada".**<br/>
   Em todos os problemas, competidores podem tentar mandar heurísticas para passar. Assim, deveremos nos certificar de que os conjuntos de casos de teste estejam robustos.
   Assim, em todos os problemas, deveremos implementar algumas heurísticas que sabemos que não deveriam passar.

9. **Descreva bem a entrada e saída esperadas.**<br/>
   Descreva com muita clareza como será a estrutura da entrada dada, e como deverá ser a saída esperada.<br/>
   Limites para os parâmetros sempre deverão ser informados.

10. **Defina um limite de memória para o problema.**<br/>
    Sempre indique qual deverá ser o limite de memória permitido.

11. **Defina um limite de tempo para o problema.**<br/>
    Sempre indique qual o tempo limite esperado das soluções.

12. **Dê preferência para usar termos em português.**<br/>
    Principalmente em problemas envolvendo strings, dê preferência por usar termos em português, e sem acentuação.
    Assim, não peça para soluções imprimirem "Yes" ou "No", mas sim "Sim" ou "Nao".


## Infraestrutura
TODO: Escrever os guidelines para setar a infraestutura no local da prova.
1. 


## Melancias
TODO: Escrever os guidelines para organizar os melancias.
1. 
