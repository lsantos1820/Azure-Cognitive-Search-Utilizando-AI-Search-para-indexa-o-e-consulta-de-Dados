# Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

Create an Azure AI Search resource

![lab 4 - 1](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/1d613e32-f054-4f33-839e-59365991c1de)

Create an Azure AI services resource

![lab 4 - 2](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/ecf6fe1e-757e-4558-80a2-d3972b9cbf11)

Create a storage account

![lab 4 - 3](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/9c3944dc-c4d6-4f14-a79d-46d11bbc64bb)

Upload Documents to Azure Storage - Containers

![lab 4 - 4](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/30a660bc-05ed-4e9e-9b23-d8007ec26c2b)

 select Upload.

![lab 4 - 5](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/227616f9-2bf2-4b42-bba7-6e8e9aae6590)

upload is complete

![lab 4 - 6](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/addd8cfb-1c59-43e9-8aba-4dcff19870d6)

Import data

![lab 4 - 7](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/648533f0-f21a-4f68-b77b-74540d5a83aa)

following values

![lab 4 - 8](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/507567c3-e34a-4985-a206-4541aed74144)

Query the index - Search explorer

![lab 4 - 9](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/9804d2a5-1f22-4988-b9df-aa85727e249a)

JSON view

{
    "search": "*",
    "count": true
}

![lab 4 - 10](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/da7b5c22-267f-4306-aef7-40e089abad00)

{
 "search": "locations:'Chicago'",
 "count": true
}

![lab 4 - 11](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/d667716a-c3b7-4ae1-8f25-5a6f1147a72c)

{
 "search": "sentiment:'negative'",
 "count": true
}


![lab 4 - 12](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/b2a22d93-886b-4a8c-8976-e900239072c6)


Delete Resource group:

![lab delete 04](https://github.com/lsantos1820/An-lise-de-Sentimentos-com-Language-Studio-no-Azure-AI/assets/75084857/71583197-11b1-42b5-948b-f5a39ce4fc65)