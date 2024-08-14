# Entrega do desafio módulo 3 – Processamento de Dados Simplificado com Power BI

- [X] ~~•Criação de uma instância na Azure para MySQL~~
	    Criado instância na Azure 
- [X] ~~•Criar o Banco de dados com base disponível no github~~
            Criado BD com dados disponíveis no github, pelo workbench.
- [X] ~~•Integração do Power BI com MySQL no Azure~~
            Efetuado a integraçãop do PB com Mysql na Azure

- [X] ~~•Verificar problemas na base a fim de realizar a transformação dos dados~~
                Verificado se avia problemas na base

## Diretrizes para transformação dos dados
- [X] ~~•Verifique os cabeçalhos e tipos de dados~~
	Ajustado cabeçalhos e tipos de dados
- [X] ~~•Modifique os valores monetários para o tipo double preciso~~
	Ajustado valores da coluna salário para decimal fixo
- [X] ~~•Verifique a existência dos nulos e analise a remoção~~
        Foi ajustado os valores nulos 
- [X] ~~•Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente~~
	O James estava sem Ssn
- [X] ~~•Verifique se há algum departamento sem gerente~~
	Não há departamento sem gerente
- [X] ~~•Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas~~
	Não há departamento sem gerente
- [X] ~~•Verifique o número de horas dos projetos~~
        Há um projeto se horas registrada
- [X] ~~•Separar colunas complexas~~
	Ajustado colunas de endereço na tabela employee
- [X] ~~•Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee.~~
	Efetuado mescla de consultas e criado a tabela employee-departament
        •OBS: Fique atento, essa informação influencia no tipo de junção
- [X] ~~•Neste processo elimine as colunas desnecessárias.~~
	Eliminado colunas 
- [X] ~~•Realize a junção dos colaboradores e respectivos nomes dos gerentes. Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.~~
    Executado no POwer BI
- [X] ~~•Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores~~
	Mesclado nomes dos colaboradores em uma coluna FULL NAME
- [X] ~~•Mescle os nomes de departamentos e localização. Isso fará com que cada combinação departamento-local seja única. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.~~
	Mesclados colunas e criado Departamento-Local
- [X] ~~•Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir.~~
	Devido a estarmos somente concatenando colunas simples
- [X] ~~•Agrupe os dados a fim de saber quantos colaboradores existem por gerente~~
	
- [X] ~~•Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela.~~
        Eliminado colunas desnecessárias 
