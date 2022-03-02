<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Teste de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P1 - 16/02/2022</p>

Matrícula: 201709004
Nome: Fabiano Gomes Pires

<p><font color=green>Nota: 6.3</font></p>

1. Quanto ao objetivo do Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Qual o objetivo primário da atividade de teste de software?
      Operar um sistema ou componente sob condições específicas, observando e registrando os resultados, avaliando alguns aspectos do sistema ou componente. <font color=red>Errado.</font>

   2. (**0,5 ponto**) O que acontece, quando não se atinge este objetivo primário?
      Temos um sistema onde, não encotramos falhas, logo se idetifica os defeitos e erros, assim, diminuindo possibilidade de falhas e frustrações do cliente e equipe de desenvolvimento. <font color=red>Errado.</font>
2. (**1,0 ponto**) Explique o que é o teste exaustivo e porque sua execução não é possível.

   Este exaustivo é testar o programa com todos os conjuntos de entradas possíveis, para que se garanta que todos os resultados esperados vão estar corretos.
   Esse tipo de teste não é viável, pelo simples fato, da maioria das vezes temos conjunto de entradas infinitas, ou quando são finitas, são demasiadamente grandes que fica impossível para fazer o número de testes requeridos inviável. <font color=green>Certo.</font>

3. (**1,0 ponto**) Cite pelo menos duas limitações da Técnica de Teste Funcional e duas da Técnica de Teste Estrutural.

   Limitações da Tecnica de Teste Funcional:
      1. Dependente de uma boa especificação de requisitos o que, em geral, não é bem feito.
      2. Para encontrar todos os defeitos utilizando teste caixa preta é necessário o teste exaustivo.
      3. Não é possível garantir que partes essenciais ou críticas do software sejam executadas.

   Limitações da Tecnica de Teste Estrutural:
      1. Exigem habilidades de programação do testador para
      compreender o fluxo de controle do programa.
      2. Pode consumir tempo e recursos significativos para sua aplicação.
<font color=green>Certo.</font>

4. (**1,0 ponto**) Descreva pelo menos um dos quatro níveis de teste constantes da literatura especializada.

   Os níveis de teste são teste de unidade, teste de integração, teste de sistema e teste de aceitação.

   O teste de aceitação é um tipo de teste de caixa preta é efetuado em um sistema em desenvolvimento antes de sua disponibilização. Tem por função verificar o sistema em relação aos seus requisitos originais, e às necessidades atuais do usuário. É geralmente realizado por um grupo restrito de usuários finais, num ambiente parecido com o deles. Há três estratégias de implementação de testes de aceitação:
   * Aceitação formal: o teste de aceitação formal é um processo altamente gerenciado e costuma ser uma extensão do teste do sistema. Os testes são planejados e projetados com o mesmo cuidado e no mesmo detalhe que o teste do sistema. Os casos de teste escolhidos devem ser um subconjunto dos que foram realizados no teste do sistema. É importante não desviar de nenhum dos casos de teste escolhidos. Em muitas organizações, o teste de aceitação formal é totalmente automatizado.
   * Aceitação informal (ou teste alfa): No teste de aceitação informal, os procedimentos para executar o teste não são definidos com tanto rigor como no teste de aceitação formal. As funções e as atividades de negócios a serem exploradas são identificadas e documentadas, mas não há casos de teste específicos para seguir. O testador individual determina o que deve ser feito. Esta abordagem do teste de aceitação não é controlada como teste formal e é mais subjetiva que o tipo formal. O teste de aceitação informal é realizado com mais frequência pela organização do usuário final.
   * Teste beta: O teste beta é o menos controlado das três estratégias de teste de aceitação. No teste beta, a quantidade de detalhes, os dados e a abordagem adotadas são de inteira escolha do testador individual. Cada testador é responsável por criar o próprio ambiente, selecionar os dados correspondentes e determinar as funções, os recursos ou as tarefas a serem exploradas. Cada um deles é responsável por identificar seus próprios critérios para aceitar, ou não, o sistema em seu estado atual.
<font color=green>Certo.</font>
5. (**1.0 ponto**)Descreva qual o propósito do critério de teste funcional Particionamento por Classes de Equivlência.

   Este critério propõe a divisão dos domínios de entrada e saída em partições, válidas e inválidas. Tais partições são classificadas como equivalentes.
   Estas classes são equivalentes em relação à capacidade de revelar ou não a presença de defeitos. O objetivo principal é a redução da quantidade de casos de testes necessários. <font color=orange>Parcialmente correto. Nota 0,5.</font>

6. (**1.00 ponto**) Existe algum tipo de hierarquia em relação aos critérios de teste estrutural, todos os nós, todos os arcos e todos os caminhos? Se sim, explique-a, considerando a perspectiva dos níveis de cobertura desejados.

   Diferentes níveis de cobertura podem ser definidos em função
   dos elementos do Grafo de Fluxo de Controle. Oito diferentes níveis de cobertura são definidos por Copeland (2004). Quanto maior o nível, maior o rigor do critério de teste, ou seja, mais caso de teste ele exige para ser satisfeito.
      * Nível 0: qualquer valor de cobertura inferior a 100% da
      cobertura de todos os comandos.
      * Nível 1: 100% de cobertura de comandos, requisito mínimo de teste. Mesmo sendo o requisito mínimo, em alguns casos pode ser dificil ser atingido por situações excepcionais, são elas:  falta de memória, disco cheio, arquivos ilegíveis, perda de conexão, ser difícil ou impossível simular tais situações excepcionais, nestes casos o código correspondente permanece não testado.
      * Nível 2: 100% de cobertura de decisões. Também chamado de cobertura de arcos/arestas (critériotodos-arcos). Objetivo fazer cada comando de decisão assumir os valores true e false.
      * Nível 3: 100% de cobertura de condições. Cobertura de condição é, em geral, melhor que cobertura de decisão: cada condição individual assume os valores true e false.
      * Nível 4: 100% de cobertura decisões/condições, requer com que todas as combinações sejam testadas.
      * Nível 5:  100% de cobertura de condições multiplas.Consiste em utilizar o conhecimento de como o compilador
      avalia condições múltiplas de determinado comando de decisão e utilizar essa informação na geração de casos de testes.
      * Nível 6: cobetura de loop. Quando programas possuem loop, o número de caminhos possíveis pode ser infinito.
      O número de caminhos pode ser reduzido limitando a execução do loop a:
         * 0 vezes.
         * 1 vez.
         *2 vezes.
         * n vezes (sendo n um número de vezes padrão que o loop é executado).
         * m vezes (sendo m o número máimo de vezes que o loop pode ser executado).
         * m - 1 vezes.
         * m + 1 vezes.

      * Nível 7: 100% de cobertura de caminhos. Também conhecido como critério todos-caminhos. Para programas sem loop o número de caminhos pode ser pequeno o suficiente e casos de testes podem ser construídos para cobri-los.
      Para programas com loop o n´umero de caminhos pode ser muito grande ou infinito, tornando-se impossível cobrir todos os caminhos de execução.

<font color=green>Certo.</font>

7. Considere a especificação, a seguir, de um hipotético programa que objtiva a classificação de um triângulo, a partir dos valores informados para os seus três lados.

   a) Dado um triângulo cujos segmentos medem A, B e C, que são números inteiros positivos na faixa de 0 a 100. Esse triângulo somente existirá se: (A + B < C) ou (A + C < B) ou (B + C < A).
   b) Quanto às medidas dos seus lados o triângulo, poderá ser classicado em:
         • Isósceles = quando possui dois lados com a mesma medida;
         • Escaleno = quando todos os seus lados têm medidas diferentes;
         • Equilátero = quando todos os lados tem a mesma medida;
         • Acutângulo = quando o quadrado de um dos seus lados é menor que a soma do quadrado dois outros dois. (A<sup>2</sup> < B<sup>2</sup> + C<sup>2</sup>).
         • Retângulo: quando o quadrado de um dos seus lados é igual à soma do quadrado dois outros dois. (A<sup>2</sup> = B<sup>2</sup> + C<sup>2</sup>).
         • Obtusângulo: quando o quadrado de um dos seus lados é maior que a soma do quadrado dois outros dois. A<sup>2</sup> > B<sup>2</sup> + C<sup>2</sup>.

7.1 (**2.0 pontos**) Definir uma tabela de decisão para o teste tanto da existência do triângulo, quanto para a definição do seu tipo. Consulte exemplo de tabela de decisão na tarefa 005.



|Causas|R1|R2|R3|R4|R5|R6|R7|R8|R9|R10|R11|R12|R13|R14|R15|R16|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|A + B < C|V|V|V|V|F|F|F|F|F|V|V|F|V|F|V|F|
|A + C < B|V|V|V|F|F|F|V|F|V|F|F|V|V|F|F|V|
|B + C < A|V|V|F|F|F|V|F|F|V|V|F|V|F|V|V|F|
|A = B = C|V|F|F|F|F|V|V|V|V|F|V|F|V|F|V|V|
|Efeitos|
|Triangulo existe?|X|X|X|X||X|X|X|X|X|X|X|X|X|X|X|
|Isósceles|X|||||X|X|X|X||X||X||X|X|
|Escaleno||X|X|X||||||X||X||X||||
|Equilátero|X|||||X|X|X|X||X||X||X|X|

<font color=orange>Parcialmente correto. Nota 1,0.</font>

7.2 (**2.0 pontos**) Criar os conjunto de casos de teste necessários para a cobertura das combinações constantes da tabela de decisão, seguindo o seguinte padrão:
|CT|Lado A|Lado B|Lado C|Resultado|
|---|---|---|---|---|
| CT01  | 9 | 10 | 16 |  "Triângulo válido"   |
| CT02  | 4 | 4  | 10 | "Triângulo Inválido"  |
| CT03  | 6 | 6  | 16 | "Triângulo Isósceles" |
| CT03  | 5 | 6  | 16 | "Triângulo Escaleno" |
| CT03  | 10 | 10  | 10 | "Triângulo Equilátero" |

Casos de  Testes com identificação repetida.
Resultado:
CT01 - Falhou.
CT03 - Validação do tipo Isósceles, Falhou.
CT03 - Validação do tipo Escaleno, Falhou.

<font color=orange>Parcialmente correto. Nota 0,8.</font>

INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing
3. Forma de Entrega: Entregar este arquivo, editado com suas respostas, no formato .md, nominado da seguinte forma: ts2021-2_prova-p1_mat.md, onde mat deverá ser substituído pelo número da sua matrícula.
4. **Entrega diferente da especificada não será avaliada.**
5. Data da Entrega: 22/02/2022, as 23h59min.
6. Critério de Aceitação: arquivo entregue, conforme solicitado.
