# Passos:

1. Instação do pacote de criptografia utilizado pelo código (!curl -s https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/develop/notebooks/2022_11_29/rdv.py -o rdv.py).
2. Limpeza de dados com seleção de apenas linhas do arquivo RDV referentes a votação para presidente.
3. Na etapa de extração, extração de apenas os dados de votação.
4. Agregação dos votos extraídos do arquivo RDV
5. Abstração da base do pandas, utilizando uma estrutura de dados que representa uma tabela de dimensões
6. Agregação dos votos com uma operação matemática de soma
7. Ordenação dos dados agregados de forma decrescente, ou seja, da maior quantidade de votos para a menor
8. Adição de uma coluna com os valores relativos percentuais da agregação dos dados.
9. Utilizar o Seaborn, um dos pacotes Python mais utilizado para visualização de dados.
10. Observação da quantidade de votos absolutos.
11. Observação da quantidade de votos relativos.
