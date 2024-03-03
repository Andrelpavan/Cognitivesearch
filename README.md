# Azure Cognitive Search

Desafio do Azure Cognitive Search. Utilizando AI Search para indexação e consulta de Dados

Segue abaixo a descrição dos passos utilizados para realizar o desafio de configurar um consulta de dados.

Passo 1:
- Primeiramente criei um Serviço de Pesquisa no Azure Cognitive Search no portal do Azure (https://portal.azure.com/).
- Cliquei em "Criar um recurso" e pesquisei por "Pesquisa Cognitiva do Azure".
- Siga as instruções para configurar o serviço, fornecendo um nome único, selecionando a assinatura, grupo de recursos, localização, nível de preços, etc.(https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)
![image](https://github.com/Andrelpavan/Cognitivesearch/assets/69944259/6e85d544-a6bc-464b-a3f0-d64247ffeabb)
![image](https://github.com/Andrelpavan/Cognitivesearch/assets/69944259/0f49d5e5-ab9e-4008-815b-8556d7de56ac)

Passo 2:
- Em seguida criei um recurso de serviços de IA esteja no mesmo local que seu recurso de Pesquisa para auxiliar na solução de pesquisa nos dados armazedos.
![image](https://github.com/Andrelpavan/Cognitivesearch/assets/69944259/b2d7e454-d44e-45b8-a6af-4ee964cfa27e)

Passo 3:
- Agora foi criado uma conta de armazenamento onde os dados que deseja indexar serão colocados. Em seguida, deverá armazenar os dados.
![image](https://github.com/Andrelpavan/Cognitivesearch/assets/69944259/f5d2eb04-1c2b-4b9e-b4bc-5f657822a487)
![image](https://github.com/Andrelpavan/Cognitivesearch/assets/69944259/053e243f-e3a8-4993-ae76-e8b61633d828)

- Carregar documentos no Armazenamento do Azure:
  - Configure a origem de dados:
Na seção "Origens de Dados", clique em "Importar dados".
Selecione o tipo de origem de dados que você está usando (por exemplo, Armazenamento Azure Blob, Azure SQL Database, Cosmos DB, etc.).
Conecte-se à sua origem de dados e configure as opções de conexão conforme necessário.
![image](https://github.com/Andrelpavan/Cognitivesearch/assets/69944259/1cc55b20-f322-4260-b0a3-8c137004ed67)
![image](https://github.com/Andrelpavan/Cognitivesearch/assets/69944259/04820e3d-de29-4029-b377-69aa84d9c15a)

Após configurar o indexador e ter os dados armazenados, inicie o processo de indexação. Isso fará com que o Azure Cognitive Search recupere os dados da sua origem de dados e os indexe de acordo com o índice definido.

Passo 4:
-  Pesquisa - Consultar o índice:
Depois que a indexação for concluída, vá para a seção "Gerenciados de Consultas" para realizar as consultas de pesquisa para garantir que os resultados sejam retornados conforme o esperado.
![image](https://github.com/Andrelpavan/Cognitivesearch/assets/69944259/ca4baec0-a9f4-43ca-90ee-f98721ee4d83)

Neste módulo do Azure Cognitive Search possibilitou entender de como podemos facilitar a descoberta de informações relevantes em grandes conjuntos de dados. Ao criar indexação e consulta de dados, o serviço permite transformar dados em um formato que possa ser facilmente pesquisado e analisado.


