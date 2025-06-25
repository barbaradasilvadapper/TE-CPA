# Projeto de Análise dos Repasses do PNAE e Evasão Escolar

Este projeto investiga a possível relação entre os valores per capita repassados pelo **Programa Nacional de Alimentação Escolar (PNAE)** e a **taxa de evasão escolar no ensino médio** nos municípios do Rio Grande do Sul no ano de 2015, através do **ENEM por Escola**. A análise foi desenvolvida com base em dados públicos e organizada em etapas de coleta, limpeza, exploração e visualização.

## Desenvolvedoras:

Este projeto foi desenvolvido pelas alunas:
- Ana Carolina Poletto
- Bárbara Dapper
- Louise Northfleet

## Estrutura do Projeto

- `Dados_do_Enem.ipynb`:  
  Realiza a leitura, compreensão, limpeza e padronização da do cvs com as informações da base de dados do ENEM Por Escola, nomeada como ENEM.cvs no projeto. Remove colunas irrelevantes, trata valores ausentes e prepara o dataset para a versão utilizada no Trabalho_final.

- `Dados_PNAE.ipynb`:  
  Realiza a leitura, compreensão, limpeza e padronização da do cvs com as informações da base de dados do Repasses PNAE, nomeada como PANE_Repasses.cvs no projeto. Remove colunas irrelevantes, trata valores ausentes e prepara o dataset para a versão utilizada no Trabalho_final.

- `Trabalho_final.ipynb`:  
  Notebook com o código principal, que roda os dois notebooks de limpeza das bases de dados e realiza a integração dos dados em um único dataset. O dataset gerado, salvo como tabela_final.csv, foi utilizado para gerar os dashboards e as visualizações principais do projeto na ferramenta Looker. Este é o **único notebook que precisa ser executado**.

## Como Executar

- É necessário rodar somente o arquivo Trabalho_final.ipynb, pois ele roda os demais notebooks e gera os arquivos necessários. 

## Dashboars

Você pode acessar os dashboards interativos por meio do link abaixo:

- https://lookerstudio.google.com/reporting/1efdaaa0-2bc6-48ad-847e-88ad8396b8b0 

## Relatório

Você pode acessar o relatório final do projeto por meio do link abaixo:

- https://docs.google.com/document/d/1CrtBvMgufipl4h52tC_ZlpVxFj_6S4cb/edit?usp=sharing&ouid=103426674066551926199&rtpof=true&sd=true 
