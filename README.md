# Telecom_Company Churn Rate Project 

O que a empresa precisa fazer para resolver isso?
Projeto criado com a intenção de gerar **insights diagnósticos sobre as motivações envolvidas na crescente taxa de cancelamento** de serviços de uma empresa de oferecimento de diversos serviços voltados a área de telecomunicações. Segundo  análises preliminares, tal taxa chega a 26% dos clientes, representando a perda de milhões. Dessa forma, objetivo do presente estudo é **levantar os principais motivos dos cancelamentos e quais as possíveis ações para reduzir tal taxa**.
<br/><br/>
Para tanto, os seguintes passos listados abaixo foram adotados:
1) Importação da base de dados
   <br/>
2) Visualização da base de dados
   <br/>
3) Tratamento de erros
   <br/>
5) Análise inicial dos dados para compreender o estado atual dos cancelamentos
   <br/>
6) Análise profunda dos dados para encontrar as motivações do cancelamento
   <br/>
  
Com a lista de passos em mãos, o desenvolvimento do código seguiu o seguinte raciocínio:
   <br/>
  I) importação das bibliotecas necessárias para a análise:  Matplotlib, Pandas, Plotly, Seaborn e NumPy
   <br/>
 II) leitura do arquivo juntamente com a correção dos erros de acento e separador para melhor visualização
<br/>
 III) visualização da tabela
<br/>
 IV) identificação os possíveis tratamentos para a tabela 
<br/>
 V) retirada de colunas desnecessárias, correção de tipo de entrada e remoção de valores vazios
<br/>
 VI) análise da quantidade de pessoas que **cancelaram e não cancelaram (26,6% e 73,4%</b>, respectivamente)**
<br/>
 VII) análise gráfica de cada coluna com a coluna de cancelamentos
<br/>

 **Resultado**: através das relações apresentadas graficamente, pode-se afirmar que os principais insights gerados são: <br/>
 - gênero não interfere nos cancelamentos
 - clientes com poucos meses de contrato tem alto índice de cancelamento. Possíveis motivações:
    - A primeira experiência do cliente na operadora pode ser ruim
    - Captação de clientes atraia clientes pouco engajados
    - Sugestão: criar incentivos para os clientes permanecerem mais tempo como cliente
  - serviço de fibra apresenta alta taxa de cancelamento. Vale avaliar a qualidade do serviço prestado
  - quanto maior a venda de pacotes de serviços (streaming, filmes, suporte técnico, etc.), menor a chance de cancelamento.
    - Sugestão: criar pacotes de serviços em promoção   
 - clientes em contrato mensal tem alta taxa de cancelamento
    - Sugestão: promoção para tornar o contrato anual mais atrativo e deslocá-lo para ele
 - famílias maiores tem menor propensão a cancelar os serviços
 - clientes que pagam com boleto apresenta alta taxa de cancelamento
    - Sugestão: criação de alguma ação que os desloque para as outras formas de pagamento disponíveis
    
