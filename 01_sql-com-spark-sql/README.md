# 🧪 Como carregar um arquivo CSV no Databricks

Antes de iniciar seus estudos siga os passos abaixo para importar um arquivo .csv utilizando a interface gráfica do Databricks:

## 🚀 Passo a passo
Acesse o menu lateral e clique em Data (ícone de banco de dados).

1. No canto superior direito, clique em "Add Data" > selecione "Create or Modify Table"
(ou em português: “Criar ou modificar tabela”)

2. Na aba que se abrir, clique em “Upload File” e selecione o arquivo .csv desejado no seu computador.

3. Aguarde até que o upload seja concluído.

4. Na tela de pré-visualização, selecione o catálogo workspace.

5. Clique em “Create new schema” (ou “Criar novo esquema”) e digite o nome pokemons. Confirme a criação.

6. Em seguida, no campo de nome da tabela, defina como:
pokemon

7. Clique no botão “Create Table” (ou “Criar Tabela”) para finalizar o processo.

✅ Resultado
A tabela workspace.pokemons.pokemon será criada automaticamente como uma Delta Table, pronta para consulta com Spark SQL ou PySpark. Repita o mesmo processo para os demais arquivos, seguindo a nomeclatura dos arquivos csv.