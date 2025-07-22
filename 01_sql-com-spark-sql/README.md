🧪 Como carregar um arquivo CSV com "Create or Modify Table" no Data Ingestion do Databricks
Siga os passos abaixo para importar um arquivo .csv utilizando a interface gráfica do Databricks:

🚀 Passo a passo
Acesse o menu lateral e clique em Data (ícone de banco de dados).

No canto superior direito, clique em "Add Data" > selecione "Create or Modify Table"
(ou em português: “Criar ou modificar tabela”)

Na aba que se abrir, clique em “Upload File” e selecione o arquivo .csv desejado no seu computador.

Aguarde até que o upload seja concluído.

Na tela de pré-visualização, selecione o catálogo workspace.

Clique em “Create new schema” (ou “Criar novo esquema”) e digite o nome pokemons. Confirme a criação.

Em seguida, no campo de nome da tabela, defina como:
bronze_pokemons

Clique no botão “Create Table” (ou “Criar Tabela”) para finalizar o processo.

✅ Resultado
A tabela workspace.pokemons.bronze_pokemons será criada automaticamente como uma Delta Table, pronta para consulta com Spark SQL ou PySpark.