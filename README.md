<h1>ㅤㅤㅤㅤㅤAPI 2º Semestre Logística - Noturno</h1>
<h1> <p align="center">
      <img src="./assets/logomelhor.png" width="220" align="center">
      <p align="center">
      Equipe Trackflow </h1>
</p>

<p align="center">
  <a href ="#status"> Status do Projeto</a>  |
  <a href ="#objetivo"> Objetivo</a>  |
  <a href ="#competencias"> Competências trabalhadas</a>  |    
  <a href ="#backlog"> Backlog</a>  |
  <a href ="#sprints"> Sprints</a>  |    
  <a href ="#equipe"> Equipe</a>  |
  <a href ="#tecnologias"> Tecnologias Usadas</a>  
</p>

<h2> 🔋 Status do Projeto:  <a id="status"></a> </h2> </h2>

> Status do projeto: [Primeira Sprint - 🚩](https://github.com/Fatec-API-TF/2-LOG-API/blob/main/MVP/sp1.md)
>
> 
>
> Documentação: [Documentação do Projeto - 📖](https://github.com/Fatec-API-TF/2-LOG-API/tree/main/Docs)

<h2> 🏃‍♂️ Objetivo: <a id="objetivo"></a> </h2>

O objetivo deste projeto é desenvolver uma plataforma no Power BI para analisar a sinistralidade de veículos pesados no Brasil. Integrando dados da PRF e do DataSUS, o painel monitora mortalidade, severidade e contexto demográfico/frota, além de mapear a distância entre os acidentes e os pontos de parada e descanso.

<h2> ✍️ Competências Trabalhadas: <a id="competencias"></a> </h2>
- Documentação de projeto ágil (backlog de produto, de sprint, briefing, etc.) </br>
- Processo de desenvolvimento ágil </br>  
- Caracterização do produto logístico </br> 
- Lógica de programação básica </br>
- Lógica matemática </br>
- Persistência de dados em BD relacional 

---

<h2> 🛠️ Backlog: <a id="backlog"></a> </h2></h2>

| Prioridade | Nº | User Story | Sprint |
| :---: | :--- | :--- | :--- |
| Alta 🔴 |  | Como equipe de projeto, quero criar o repositório no GitHub com a estrutura de pastas do projeto, para termos controle de versão dos artefatos desde o início. | Sprint 1 |
| Alta 🔴 |  | Como equipe de projeto, quero documentar o backlog do produto e do sprint, para termos o planejamento ágil formalizado conforme exigido pelo curso. | Sprint 1 |
| Alta 🔴 |  | Como analista de dados, quero mapear e acessar as bases públicas necessárias (DATASUS – mortalidade, PRF – sinistros, frota de veículos, população — IBGE), para ter as fontes de dados do projeto identificadas. | Sprint 1 |
| Alta 🔴 |  | Como analista de dados, quero normalizar e limpar as bases de dados no Google Colab, para garantir dados consistentes e confiáveis para a análise. | Sprint 1 |
| Média 🟡 |  | Como analista de dados, quero realizar uma análise exploratória inicial dos dados, para identificar padrões, outliers e priorizar os indicadores a serem desenvolvidos. | Sprint 1 |
| Média 🟡 |  | Como equipe de projeto, quero consolidar as bases de dados de sinistros (PRF) e frota em um único dataset por estado/ano, para viabilizar o cálculo dos indicadores nos próximos sprints. | Sprint 1 |
| Média 🟡 |  | Como equipe, quero versionar os scripts Python e notebooks no GitHub a cada incremento, para manter rastreabilidade e permitir trabalho colaborativo. | Sprint 2 |
| Alta 🔴 |  | Como usuário do dashboard, quero visualizar a taxa de mortalidade por 100 mil habitantes por estado, para comparar a severidade dos sinistros entre os estados. | Sprint 2 |
| Alta 🔴 |  | Como usuário do dashboard, quero visualizar o indicador de sinistros por 10 mil veículos, para entender a frequência relativa de sinistros com veículos pesados por estado. | Sprint 2 |
| Média 🟡 |  | Como usuário do dashboard, quero comparar cada estado com a média nacional nos principais indicadores, para identificar rapidamente estados acima ou abaixo da média. | Sprint 2 |
| Média 🟡 |  | Como analista, quero calcular a correlação entre o crescimento da frota de veículos pesados e o aumento de sinistros fatais, para responder a essa questão de análise proposta pelo cliente. | Sprint 2 |
| Média 🟡 |  | Como analista, quero identificar quais estados têm maior taxa de letalidade envolvendo veículos pesados, para responder a essa questão de análise proposta pelo cliente. | Sprint 2 |
| Média 🟡 |  | Como analista, quero mapear os pontos de parada de descanso e calcular a distância entre eles e os locais de sinistros com veículos pesados, para apoiar a análise de infraestrutura viária. | Sprint 2 |
| Alta 🔴 |  | Como cliente (ONSV), quero participar de uma reunião de apresentação da Entrega 2, para validar o progresso dos indicadores e direcionar ajustes antes do dashboard final. | Sprint 2 |
| Alta 🔴 |  | Como usuário do dashboard, quero navegar por um mapa do Brasil com dados agregados por estado, para visualizar geograficamente os indicadores de segurança viária. | Sprint 3 |
| Alta 🔴 |  | Como usuário do dashboard, quero visualizar gráficos de tendência dos indicadores entre 2015 e 2025 por estado, para entender a evolução histórica da segurança viária. | Sprint 3 |
| Média 🟡 |  | Como usuário do dashboard, quero acessar qualquer informação relevante em poucos cliques, para ter uma navegação intuitiva pela plataforma. | Sprint 3 |
| Média 🟡 |  | Como usuário do dashboard, quero acessá-lo de forma responsiva em diferentes dispositivos, para consultar os dados também fora do desktop. | Sprint 3 |
| Alta 🔴 |  | Como usuário do dashboard, quero aplicar filtros por tipo de veículo, região, ano e gravidade do sinistro, para segmentar a análise conforme meu interesse. | Sprint 3 |
| Alta 🔴 |  | Como usuário do dashboard, quero aplicar um filtro cruzado entre dados de saúde (DATASUS) e transporte (PRF), para relacionar mortalidade e sinistros de forma integrada. | Sprint 3 |
| Alta 🔴 |  | Como equipe de projeto, quero produzir a documentação técnica completa do projeto (scripts de limpeza e modelagem em Python), para permitir a reprodutibilidade da solução. | Sprint 3 |
| Alta 🔴 |  | Como cliente (ONSV), quero receber um relatório técnico de análise com boas práticas e desafios por estado, para apoiar a formulação de políticas públicas ou estudos acadêmicos. | Sprint 3 |
| Alta 🔴 |  | Como equipe de projeto, quero gravar e publicar um vídeo no YouTube apresentando a solução final, para cumprir a forma de entrega definida para a Entrega 3 (26/nov). | Sprint 3 |
| Média 🟡 |  | Como equipe de projeto, quero apresentar o projeto presencialmente na Feira de Soluções da FATEC, para expor o resultado final do trabalho para banca e visitantes. | Sprint 3 |


---
<h2> ⚙️ Sprints: <a id="sprints"> </a> </h2></h2>

<p align="center">

| Sprint | Data da entrega | Acesso |
| :---: | :--- | :--- |
Sprint 1 | 30/09 | [Link para acesso](https://github.com/Fatec-API-TF/2-LOG-API/blob/main/MVP/sp1.md)
Sprint 2 | 28/10 | [Link para acesso]()
Sprint 3 | 25/11 | [Link para acesso]()

</p>

---

<h2> 🤝 Equipe: <a id="equipe"> </a> </h2></h2>
<div align="center">
  <table>
    <tr>
      <th>Membro</th>
      <th>Função</th>
      <th>Github</th>
      <th>Linkedin</th>
    </tr>
    <tr>
      <td>Rodrigo Azavedo</td>
      <td>Product Owner</td>
      <td><a href="https://github.com/rodriwsz"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/rodrigo-menezes-b4246130b/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Kauan Assis</td>
      <td>Scrum Master</td>
      <td><a href="https://github.com/KauanDanielX"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/kauan-assis-b915a3334/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Gustavo Funari</td>
      <td>Team Member</td>
      <td><a href="https://github.com/"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Leonardo Balieiro</td>
      <td>Team Member</td>
      <td><a href="https://github.com/Leonardacostabalieiro"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/leonardodacostabalieiro/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Nikolas Maura</td>
      <td>Team Member</td>
      <td><a href="https://github.com/NMAURA"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/nikolasmaura"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Victor Oliveira</td>
      <td>Team Member</td>
      <td><a href="https://github.com/Victorvmor"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/victor-miguel-848186333"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
    <tr>
      <td>Willian Ortiz</td>
      <td>Team Member</td>
      <td><a href="https://github.com/willianortiz2201"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
      <td><a href="https://www.linkedin.com/in/wortiz2201/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    </tr>
  </table>
</div>

---


<h2> 🤖 Tecnologias Usadas:  <a id="tecnologias"></a> </h2> </h2>

<h4 align="center">
 <a href="https://colab.research.google.com"><img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white"></a>
 <a href="https://docs.google.com/document/u/0/"><img src="https://img.shields.io/badge/Docs-4285F4?style=for-the-badge&logo=googledocs&logoColor=white"></a>
 <a href="https://www.python.org"><img src="https://img.shields.io/badge/Python_3+-3776AB?style=for-the-badge&logo=python&logoColor=white"></a>
 <a href="https://app.powerbi.com/home?language=pt-BR"><img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"></a>
 <a href="https://excel.cloud.microsoft/pt-br/"><img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"></a>
</h4>

