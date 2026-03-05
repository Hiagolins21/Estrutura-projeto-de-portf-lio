# Análise de Empregados da Rede Hospitalar EBSERH com SQL
Este projeto analisa dados públicos de empregados da rede hospitalar da Ebserh. O objetivo é explorar a base, realizar limpeza de dados e gerar insights sobre a distribuição de funcionários por hospital, cargo e vínculo.

Importação dos dados
- Importação do CSV no PostgreSQL via pgAdmin
- Ajuste de encoding (LATIN1)
- Definição das colunas da tabela

QUERY 1:

<img width="470" height="307" alt="image" src="https://github.com/user-attachments/assets/d488278a-e995-4326-8892-3ce43c458779" />


# Verificação da importação

- Após a importação dos dados, foi realizada a verificação da criação da tabela empregados_ebserh e da consistência dos dados.


QUERY 2:

<img width="253" height="121" alt="image" src="https://github.com/user-attachments/assets/e2e0a118-1913-4360-811c-ddcf9e15ec08" />


<img width="1415" height="363" alt="image" src="https://github.com/user-attachments/assets/fdce51fe-2297-45f1-9ec0-6e00f08d85b5" />

- QUERY 3: Contagem total de registros

<img width="276" height="66" alt="image" src="https://github.com/user-attachments/assets/ee861b20-d632-4a61-9d33-b6476f89ea4c" />

RESULTADO:

<img width="162" height="98" alt="image" src="https://github.com/user-attachments/assets/4a30a8f9-14d5-4a00-9585-581268c756d9" />


# Análises:

Análise 1 - Distribuição de funcionários por cargo

Objetivo: identificar quais cargos possuem maior quantidade de funcionários na base.

QUERY 4:

<img width="470" height="130" alt="image" src="https://github.com/user-attachments/assets/f73b54a5-fec5-478f-9cde-537a837e1cb6" />

RESULTADO:

<img width="424" height="369" alt="image" src="https://github.com/user-attachments/assets/53b7dc90-7258-4096-81e3-7b2954f15cf9" />

Análise 2 - Admissões por ano

Objetivo: identificar os anos com maior número de contratações na rede Ebserh.

QUERY:

<img width="536" height="154" alt="image" src="https://github.com/user-attachments/assets/7dd52203-f974-425a-bf1f-3a6600a3b296" />

RESULTADO:

<img width="313" height="371" alt="image" src="https://github.com/user-attachments/assets/36f653af-beda-4955-a75d-c34321708a13" />

# Insights encontrados
- Houve maior número de admissões entre os anos de 2014 e 2015
- O cargo mais contratado, foi o de Técnico em Enfermagem




