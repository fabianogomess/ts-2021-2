<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Teste de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P2 - 12/04/2022</p>

Matrícula: <font color="red">????????</font>

Nome: <font color="red">????????</font>

<p><font color="green">Nota 6,76</font></p>


1. Quanto ao Processo de Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Defina os seguintes conceitos Processo de Teste de Software, Projeto de Teste de Software e Plano de Teste de Sofware.

      **Processo de Teste** diz respeito de como são estruturadas as estapas, atividades, os artefatos, os papéis e as responsabilidades do teste, permitindo organização e controle de todo o ciclo do teste, minimizando os riscos e agregando valor ao software. Ele tem começo, meio e fim. <p><font color="red">O que tem começo, meio e fim é o projeto de software. O Processo é contínuo.</font></p>

      O **Projeto de Teste** descreve a estrutura dos elementos de testes e a realização dos casos de teste. É um documento que especifica os detalhes da abordagem de teste para um requisito do software ou combinação deles e identifica casos de teste associados.

      O **Plano de Teste** Esta é a primeira etapa do processo de teste, que envolve definir as atividades que determinam quais serão as abordagens dos testes, visando atingir os propósitos do cliente, tendo em vista todas as restrições impostas pelo contexto do projeto.
      Os principais objetivos da etapa de planejamento são verificar a missão, definir os objetivos e as atividades de teste a serem realizadas, gerando um documento chamado Plano de Teste, que devera ser seguidos em todas as próximas etapas do processo.

      <p><font color="red">Nota 0,4</font></p>

   2. (**0,5 ponto**) Descreva o relacionamento existente entre estes conceitos.
   O Processo de Teste é o elemento mais alto que contém o Projeto de Teste e o Plano de Teste, é estruturação das etapas do do processo entre elas o Plano e o Projeto de teste. Como ja dito o plano e o projeto são estapas do processo, onde no plano é definido a missão, definir os objetivos e as atividades de teste a serem realizadas em um nível mais detalhado. O projeto de teste é uma atividade que vem apois o plano de teste e defini, refina e estrutura os casos de teste, para mais tarde em outra atividade serem implementados. <p><font color="red">Nota 0,5</font></p>

2. (**1,0 pontos**) Descreva as vantagens para a equipe de desenvolvimento ao se adotar um processo de teste ágil.

   Dentre as vantagens que encontramos no teste ágil vale destacar: ocorre durante o desenvolvimento em ciclos frequêntes, é relizado com maior ênfase por meios automáticos,enfoque em testes de caixa preta e caixa branca em todas as camadas da arquitetura do software e os testes são usados em complemento aos requisitos e documentação do código. <p><font color="red">Nota 1,0</font></p>

3. (**1,0 ponto**) Cite pelo menos três características do Teste Exploratório.

   Nos testes exploratorios os resultados de teste, casos de teste e documentação de teste são geradas a medida que os testes são realizados.
   Ferramentas de captura e reprodução (Capture & Playback), captura de tela e registro de teclas são ideais para armazenar os resultados do teste exploratório.
   Ideais para o teste de aplicações web modernas, desenvolvida seguindo metodologias ágeis. Desenvolvimento em ciclos curtos implica em pouco tempo para a escrita de scripts e manutenção dos mesmos. <p><font color="red">Nota 1,0</font></p>

4. Considere os arquivos .java (Banco.java, Agencia.java, Conta.java e BankValidator.java). Nos próprios arquivos .java estão definidas as regras para cadastramento de cada um deles (Banco, Agencia e Conta). Desta forma, pede-se:
   1. (2.0 Pontos) Definir os cenários de teste suficientes para testar o cadastro e movimentações financeiras envolvendo bancos, agências e contas, conforme especificado. Para cada cenário definir os critérios de teste adequados à definição dos seus casos de teste.

      **CT01:** Testa número do Banco maior que 3 digitos.

      **CT02:** Testa número do Banco menor que 3 digitos.

      **CT03:** Testa número do Banco do algum valor -1.

      **CT04:** Testa número do Banco correto.

      **CT05:** Testa nome do Banco menor que 5.

      **CT06:** Testa nome do Banco maior que 100.

      **CT07:** Testa nome do Banco com caractere especial no meio.

      **CT08:** Testa nome do Banco correto.

      **CT09:** Testa número da Agência menor que 3 digitos.

      **CT010:** Testa número da Agência maior que 5 digitos.

      **CT11:** Testa número da Agência com uma letra no meio.

      **CT12:** Testa número da Agência correto.

      **CT13:** Testa nome da Agência, menor que 5 caracteres.

      **CT14:** Testa nome da Agência, maior que 100 caracteres.

      **CT15:** Testa nome da Agência com caractere especial no meio dos caracteres.

      **CT16:** Testa o nome da Agência correto.

      **CT17:** Testa nome da cidade da Agência, menor que 5 dígitos.

      **CT18:** Testa nome da cidade da Agência, maior que 100 caracteres.

      **CT19:** Testa nome da cidade da Agência com caractere especial no meio.

      **CT20:** Testa o nome da cidade da Agência correto.

      **CT21:** Testa número da Conta, menor que 6 dígitos.

      **CT22:** Testa número da Conta, maior que 6 dígitos.

      **CT23:** Testa número da Conta, com letra no meio dos digitos.

      **CT24:** Testa tipo da Conta, Corrente.

      **CT25:** Testa tipo da Conta, Poupança.

      **CT26:** Testa tipo da Conta, Outro.

      **CT27:** Testa  método transferir da Conta.

      **CT28:** Testa  método depositar da Conta, com valor.

      **CT29:** Testa  método sacar da Conta.
      <p><font color="red">Nota 1,0</font></p>

   2. (2.0) Definir os casos de teste suficientes para a cobertura do teste de cada um dos cenários definidos. Documentar os casos de teste no seguinte padrão:

   |CT|Valores de Entrada|Resultado esperado|
   |---|---|---|
   |CT01|1234, Brasil|"Entrada inválida"|
   |CT02|12, Brasil|"Entrada inválida"|
   |CT03|1-23, Brasil|"Entrada inválida"|
   |CT04|123, Brasil|"Banco Cadastrado"|
   |CT05|123, Bras|"Entrada inválida"|
   |CT06|123, Brassssssssssssssssssssssssssssssssssssssssssiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiilllllllllllllllllllllllllllllllllllll|"Entrada inválida"|
   |CT07|123, Brad@co|"Entrada inválida"|
   |CT08|123, Bradesco|"Banco Cadastrado"|
   |CT09|12, BraIta, Itapuranga, banco| "Entrada inválida"|
   |CT10|1235636, BraIta, Itapuranga, banco| "Entrada inválida"|
   |CT11|12g63, BraIta, Itapuranga, banco| "Entrada inválida"|
   |CT12|12345, BraIta, Itapuranga, banco| "Agencia Cadastrada"|
   |CT13|12345, BraI, Itapuranga, banco|"Entrada inválida"|
   |CT14|12345, Brassssssssssssssssssssssssssssssssssssssssssiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiilllllllllllllllll, Itapuranga, banco|"Entrada inválida"|
   |CT15|12345, BraIn&dc, Itapuranga, banco|"Entrada inválida"|
   |CT16|12345, BraIndec, Itapuranga, banco|"Agencia Cadastrada"|
   |CT17|12345, BraIndec, Itap, banco|"Entrada inválida"|
   |CT18|12345, BraIndec, Itapuuuuuuuuuuuuuuuuurrrrrrrrrrrrrrrrrrrrrrrrrrrrrrrraaaaaaaaaaaaaaagggggggggggggggggggggggggaaaaaaaaaaaaaaaaaaaaaaaa, banco|"Entrada inválida"|
   |CT19|12345, BraIndec, Itap$ranga, banco|"Entrada inválida"|
   |CT20|12345, BraIndec, Itapuranga, banco|"Agencia Cadastrada"|
   |CT21|1236, Corrente, agenciaTal|"Entrada inválida"|
   |CT22|1234567, Corrente, agenciaTal|"Entrada inválida"|
   |CT23|12f456, Corrente, agenciaTal|"Entrada inválida"|
   |CT24|123456, Corrente, agenciaTal|"Conta cadastrada"|
   |CT25|123456, Poupanca, agenciaTal|"Conta cadastrada"|
   |CT26|123456, outraCoisa, agenciaTal|"Entrada inválida"|
   |CT27|origem, destino, 1000.0|21000|
   |CT28|conta, 1000.0|21000|
   |CT29|conta, 1000.0|19000|
   <p><font color="red">Nota 1,5</font></p>

   3. (3.0 Pontos) Implementar (na linguagem de programação java) as classes para o teste da criação dos objetos e das movimentações financeiras envolvendo bancos e agências e contas.

   <p><font color="red">Nota 1,36</font></p>

INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing.
3. Forma de Entrega: arquivo compactado contendo:
   1. Este arquivo md, respondido.
   2. Classes de teste para (BancoTest, AgenciaTest e ContaTest);
   3. O arquivo compactado deverá ter o seguinte nome prova_p2<mat>.zip, onde mat é o número da matrícula do aluno(a).
5. Data da Entrega: 12/04/2022, as 22hs.
6. Critério de Aceitação: arquivo entregue, conforme solicitado.
7. Obs: segue no mesmo pacote o arquivo "org.apache.commons.lang.StringUtils", que é uma dependência do projeto. É deve ser inserida no _classpath_ do projeto de implementação da questão 4, caso não esteja utilizando o _maven_.
