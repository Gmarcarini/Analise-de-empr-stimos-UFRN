<h1>UFRN Library Loan Analysis</h1>

<p>Bem-vindo ao repositório do desafio <strong>#7DaysOfCode</strong>, onde estou analisando os dados de empréstimos dos acervos das bibliotecas da UFRN.</p>

<h2>Descrição do Projeto</h2>
<p>Este projeto tem como objetivo explorar os dados de empréstimos realizados pelas bibliotecas da UFRN nos últimos 10 anos. A análise será feita utilizando a biblioteca <strong>Pandas</strong> do Python.</p>

<h2>Objetivos</h2>
<ul>
  <li>Unificar dados de empréstimos e exemplares em um único DataFrame.</li>
  <li>Limpar dados nulos e duplicados.</li>
  <li>Analisar padrões de empréstimo por biblioteca e por tema.</li>
  <li>Avaliar a evolução dos empréstimos ao longo do tempo.</li>
</ul>

<h2>Primeiro Dia de Projeto</h2>
<p>Início da jornada no <strong>#7DaysOfCode</strong>Foi o dia de baixar e organizar os dados. A tarefa principal foi unificar os dados de empréstimos e exemplares, utilizando a coluna de código de barras para mesclá-los. A limpeza de dados duplicados e nulos também foi realizada para garantir que os dados estivessem prontos para as próximas etapas.</p>

<p>Após o agrupamento e a limpeza dos dados, foi necessario criar outra coluna para qual categoria do CDU o livro se encontra com base nos numeros disponiveis na coluna 'localização'.</p>

<ul>
    <li>000 a 099: Generalidades. Ciência e conhecimento</li>
    <li>100 a 199: Filosofia e psicologia</li>
    <li>200 a 299: Religião</li>
    <li>300 a 399: Ciências sociais</li>
    <li>400 a 499: Classe vaga. Provisoriamente não ocupada</li>
    <li>500 a 599: Matemática e ciências naturais</li>
    <li>600 a 699: Ciências aplicadas</li>
    <li>700 a 799: Belas artes</li>
    <li>800 a 899: Linguagem. Língua. Linguística</li>
    <li>900 a 999: Geografia. Biografia. História</li>
</ul>

<h2>Próximos Passos</h2>
<p>Este arquivo README será atualizado ao longo dos dias conforme o projeto avança. Fique atento às próximas etapas, onde mergulharemos mais fundo na análise dos dados!</p>

<h2>Licença</h2>
<p>Este projeto é licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.</p>
