<h1>ㅤㅤㅤㅤㅤMVP Sprint 2 - API 2º Semestre Logística</h1>

--- 

<h2> 🎯 Objetivo do MVP:  </h2>
  <h3> Requisitos Funcionais:</h3>
    - . </br> 
    - . </br> 
    - . </br> 
    - Repositório: Estruturação do repositório remoto (GitHub) E versionamento da documentação da Sprint 1. </br> 

---

<h2> 🔑 User Stories (Backlog do MVP) </h2>

| ID | User Story | Prioridade | Estimativa (Story Points) |
| :--- | :--- | :--- | :--- |
| US1 | Como equipe, quero versionar os scripts Python e notebooks no GitHub a cada incremento, para manter rastreabilidade e permitir trabalho colaborativo. | Média 🟡 | 5 pontos |
| US2 | Como analista de dados, quero visualizar a taxa de mortalidade por 100 mil habitantes por estado, para comparar a severidade dos sinistros entre os estados no dashboard. | Alta 🔴 | 5 pontos |
| US3 | Como analista de dados, quero visualizar o indicador de sinistros por 10 mil veículos, para entender a frequência relativa de sinistros com veículos pesados por estado. | Alta 🔴 | 5 pontos |
| US4 | Como analista de dados, quero comparar cada estado com a média nacional nos principais indicadores, para identificar rapidamente estados acima ou abaixo da média. | Média 🟡 | 3 pontos |
| US5 | Como analista de dados, quero calcular a correlação entre o crescimento da frota de veículos pesados e o aumento de sinistros fatais, para responder a essa questão de análise proposta pelo cliente. | Média 🟡 | 5 pontos |
| US6 | Como analista, quero identificar quais estados têm maior taxa de letalidade envolvendo veículos pesados, para responder a essa questão de análise proposta pelo cliente. | Média 🟡 | 3 pontos |
| US7 | Como analista, quero mapear os pontos de parada de descanso e calcular a distância entre eles e os locais de sinistros com veículos pesados, para apoiar a análise de infraestrutura viária. | Média 🟡 | 5 pontos |
| US8 | Como cliente (ONSV), quero participar de uma reunião de apresentação da Entrega 2, para validar o progresso dos indicadores e direcionar ajustes antes do dashboard final. | Alta 🔴 | 3 pontos |
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
