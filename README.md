# Exploração e Análise de Dados de Crédito com SQL

##Descrição
Projeto de exploração e análise de dados de crédito utilizando SQL. Os dados representam informações de clientes de um banco, com várias características relevantes para análise. A análise é realizada utilizando AWS Athena e dados armazenados em um S3 Bucket.

## Estrutura dos Dados
Os dados possuem as seguintes colunas:
- idade: idade do cliente
- sexo: sexo do cliente (F ou M)
- dependentes: número de dependentes do cliente
- escolaridade: nível de escolaridade do cliente
- salario_anual: faixa salarial do cliente
- tipo_cartao: tipo de cartão do cliente
- qtd_produtos: quantidade de produtos comprados nos últimos 12 meses
- iteracoes_12m: quantidade de iterações/transações nos últimos 12 meses
- meses_inativo_12m: quantidade de meses que o cliente ficou inativo
- limite_credito: limite de crédito do cliente
- valor_transacoes_12m: valor das transações dos últimos 12 meses
- qtd_transacoes_12m: quantidade de transações dos últimos 12 meses
- Os dados utilizados neste projeto estão disponíveis em este repositório: https://github.com/andre-marcos-perez/ebac-course-utils/tree/main/dataset.

##Metodologia de Trabalho
1. Exploração de Dados: Primeiramente, foi realizada uma exploração inicial dos dados para entender suas características e distribuições.
2. Análise de Dados: Com os dados explorados, foram realizadas análises detalhadas para identificar padrões e insights relevantes.
3. Conclusão: A partir das análises, conclusões foram tiradas sobre o comportamento e características dos clientes.
   
## Requisitos
- SQL (AWS Athena)
- AWS S3

## Configuração do Ambiente de Desenvolvimento
1. Configure um bucket no AWS S3 e carregue os dados.
2. Configure o AWS Athena para acessar os dados no S3.
3. Utilize a interface do AWS Athena para escrever e executar as consultas SQL.

## Executando o Projeto
Certifique-se de ter acesso ao AWS S3 e ao AWS Athena.
Carregue os dados no S3 e configure o Athena conforme necessário.
Utilize os scripts SQL fornecidos para realizar a exploração e análise dos dados.

## Colaboradores
- Gabriel Canuto de Alencar

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).
