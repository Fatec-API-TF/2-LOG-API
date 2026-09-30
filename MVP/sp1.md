<h1>ㅤㅤㅤㅤㅤMVP Sprint 1 - API 1º Semestre Logística</h1>

--- 

<h2> 🎯 Objetivo do MVP:  </h2>
  <h3> Requisitos Funcionais:</h3>
    - Setup de ambiente: Configuração de one drive e google colab para processamento de dados. </br> 
    - Data prep: Tratamento da base de dados, deixando dados necessários para a estruturação inicial do projeto. </br> 
    - Dashboard: Modelar o ambiente de visualização de dados através da plataforma Power BI. </br> 
    - Repositório: Estruturação do repositório remoto (GitHub) E versionamento da documentação da Sprint 1. </br> 

---

<h2> 🔑 User Stories (Backlog do MVP) </h2>

| ID | User Story | Prioridade | Estimativa (Story Points) |
| :--- | :--- | :--- | :--- |
| US1 | Como cliente do projeto, quero o repositório no GitHub com a estrutura de pastas do projeto, para termos o entendimento de versão dos artefatos desde o início. | Alta 🔴 | 2 pontos |
| US2 | Como cliente final do projeto, quero documentado o backlog do produto e de cada sprint, para entendermos o planejamento ágil formalizado conforme exigido. | Alta 🔴 | 3 pontos |
| US3 | Como analista de dados, quero mapear e acessar a base pública da PRF (sinistros, frota de veículos), para ter as fontes de dados do projeto identificadas. | Alta 🔴 | 3 pontos |
| US4 | Como analista de dados, quero normalizar e limpar as bases de dados no Google Colab, para garantir dados consistentes e confiáveis para a análise. | Alta 🔴 | 5 pontos |
| US5 | Como analista de dados, quero realizar uma análise exploratória inicial dos dados, para identificar padrões, outliers e priorizar os indicadores a serem desenvolvidos. | Média 🟡 | 3 pontos |
| US6 | Como analista de dados, quero as bases de dados de sinistros (prf) em um único dataset por estado/ano, para viabilizar o cálculo dos indicadores na entrega final. | Média 🟡 | 5 pontos |


---

<h2> 🗃️ Evidências: </h2>

<img width="957" height="774" alt="image" src="https://github.com/user-attachments/assets/2f00d92d-082b-4b9c-b34a-f3d94eb48905" />
<img width="772" height="745" alt="image" src="https://github.com/user-attachments/assets/740862ba-4078-467a-ab46-b2f58c1eaed6" />
<img width="607" height="729" alt="image" src="https://github.com/user-attachments/assets/b936ab37-8a4b-4d64-9cd0-4a8478d54100" />




<h2 align="center">
  <a href="https://colab.research.google.com/drive/1dzKy6NinVWmZzWzaLFhG1aBEjWJVkV4K?usp=sharing">Link para o arquivo - 🗃️</a>
</h2>

<h2 align="center">
  <a href="https://github.com/Fatec-API-TF/2-LOG-API/blob/main/MVP/API1.ipynb">Link para o código no GitHub - 🗃️</a>
</h2>

<h2 align="center">
  <a href="https://github.com/Fatec-API-TF/2-LOG-API/blob/main/MVP/API1.ipynb">Link para base dados limpa (.csv) - 🗃️</a>
</h2>

---

<h2> 💡 Funcionalidades desenvolvidas: </h2>

= Governança de projeto ágil

US01 — Criação do repositório no GitHub com estrutura de pastas
US02 — Documentação do backlog do produto e do sprint
US03 — Vídeo de validação do entendimento do problema com o cliente

= Coleta, limpeza e modelagem inicial dos dados

US04 — Mapeamento e acesso às bases públicas (DATASUS, PRF, frota, IBGE)
US05 — Normalização e limpeza das bases no Google Colab
US06 — Análise exploratória inicial dos dados
US07 — Consolidação das bases de sinistros (PRF) e frota em um dataset único por estado/ano


<h2> 🚩 Pontos de melhoria: </h2>

= Qualidade e confiabilidade dos dados

- Formalizar critérios objetivos de "dados limpos" (ex.: % de nulos aceitável, regras de outlier) em vez de limpeza ad-hoc, para não propagar erro para os indicadores da Sprint 2.
- Criar testes automatizados simples (ex.: checagem de schema, ranges válidos) no pipeline do Colab, já que na Sprint 2 esse pipeline vira a base do back end em Python.

