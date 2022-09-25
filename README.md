### Modificações para o projeto de ordem de serviço de uma oficina, referente ao projeto 1 e 2 do Database Experience


<>https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white</>
### Modelo de Banco de Dados de Ordem de Serviço de uma Oficina Mecânica

## *Narrativa:*
1. Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
2. Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
3. Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
4. A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
5. O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
6. A mesma equipe avalia e executa os serviços
7. Os mecânicos possuem código, nome, endereço e especialidade
8. Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
