🛠️ Modelo Conceitual para Sistema de Oficina Mecânica
Este repositório contém o Modelo Conceitual (Diagrama Entidade-Relacionamento) para um sistema de controle e gerenciamento de Ordens de Serviço (OS) em uma oficina mecânica. Este projeto foi desenvolvido com base na narrativa de negócio fornecida no desafio de modelagem de dados.

🎯 Objetivo
O objetivo deste projeto foi criar um esquema conceitual que capture todas as entidades, atributos e relacionamentos descritos na narrativa.

A modelagem visa garantir a rastreabilidade completa do serviço, desde a entrada do veículo até a conclusão da Ordem de Serviço e cálculo do valor final.

📝 Narrativa

* Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
* Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
* Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
* A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
* O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
* A mesma equipe avalia e executa os serviços
* Os mecânicos possuem código, nome, endereço e especialidade
* Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.



⚙️ Tecnologias e Ferramentas Utilizadas

Ferramenta de Modelagem: Oracle Data Modeler

Conceito: Modelo Entidade-Relacionamento (MER).

Foco: Criar a Modelagem Conceitual de uma oficina mecânica.
