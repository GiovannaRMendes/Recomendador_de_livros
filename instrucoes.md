# Intruções das criações e configurações do ambiente de execução do projeto

## GitHub

Instruções para iniciar um repositório remote e vinculá-lo ao do _GitHub_:
* ```git init```;
* ```git remote add <remote> <url https>```;
* ```git pull <remote-name> <local-branch-name>```.

## Azure

### Etapa 1

Para iniciar o projeto, é necessário criar uma conta na _Azure_ (podendo ser: pague conforme o uso ou gratuita por 30 dias). Para ambos os casos, é preciso tem um cartão de crédito.

Feito isso, inicia-se a configuração do ambiente para o projeto juntamente com o _Databricks_.

### Etapa 2

Uma das primeira etapas que acho importante é a criação de um orçamento. Isso para fiscalizar o quanto o seu projeto está gastando. Para isso, vá no __Gerenciamento de Custos__ -> __Orçamentos__ -> __Adicionar__ e define as informações exigidas de acordo com os seus dados.

<img src="Evidencias_criacao_configuracao/orcamento.png" width="50%" height="50%">
<img src="Evidencias_criacao_configuracao/orcamento_define_alertas.png" width="50%" height="50%">

### Etapa 3

Posteriormente, cria-se uma conta de armazenamento para guardar seus dados. Para isso, vá no __Centro de armazenamento__ -> __Criar__ e informe os dados necessários para sua criação.

<img src="Evidencias_criacao_configuracao/conta_armazenamento.png" width="50%" height="50%">

Vale destacar que, necessita de um grupo de recursos. Você pode criá-lo nessa etapa.

<img src="Evidencias_criacao_configuracao/conta_armazenamento_namespace_hierarquico.png" width="50%" height="50%">

Já o _Namespace hierárquico_ é importante ser acrescentado por conta da sua forma de organização ser do __Data Lake Storage Gen2__. Para saber mais sobre o [_Namespace hierárquico_](https://learn.microsoft.com/pt-br/azure/storage/blobs/data-lake-storage-namespace), aqui está o _link_ na documentação do _Microsoft Learn_: https://learn.microsoft.com/pt-br/azure/storage/blobs/data-lake-storage-namespace.