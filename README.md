# projeto C# Console Application / SQL Server

Sistema criado para acesso ao SQLServer com Dapper.

##Requisitos Necessários:

* Visual Studio 2022
* SQL Server



## Script do banco de dados:

```sql
	CREATE TABLE [dbo].[PESSOA] (
    		[IDPESSOA]       UNIQUEIDENTIFIER NOT NULL,
    		[NOME]           NVARCHAR (150)   NOT NULL,
    		[CPF]            NVARCHAR (11)    NOT NULL,
    		[DATANASCIMENTO] DATE             NOT NULL,
    		PRIMARY KEY CLUSTERED ([IDPESSOA] ASC)
	);
```

