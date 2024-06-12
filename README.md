# desafio-tech


Pipeline CI/CD

O pipeline desenvolvimento para executar 3 etapas:

Build: etapa em que é gerado a versão de um artefato com base em todos os componentes que foram utilizados no desenvolvimento de uma api / app, exemplo: biblioteca interna e externa, imagem de sistema operacional e os componentes da aplicação. É a etapa que valida se está funcional naquele momento.

Test: essa etapa valida se há uma cobertura mínima no código da api para determinados testes, como: unitário, integração, carga, entre outros. Esse caso depende especialmente do desenvolvimento de testes para cada componenente desenvolvido. Essa etapa lida com a padronização de nível de segurança no código das apis, elevando o nível de confiabilidade das funcionalidades da api. 

Deploy: aqui é utilizado o artefato gerado na etapa da build para implementação da aplicação em um cluster kubernetes

____________________________________________________________________________________________________________________________________________________________________________________________________________

Arquitetura da Solução


![solucao](https://github.com/wrs-mar/desafio-tech/assets/84333247/0a91d405-bb0f-4923-be9b-63a3e1e69cf4)
