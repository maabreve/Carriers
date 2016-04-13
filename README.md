# Carriers

#Instruções

1) Abrir o projeto pelo Visual Sutdio

2) Efetuar restore dos packages com Nuget

  2.1) Clicar com botão direito na solution e seleciona Restore Nuget Packages
  
3) Setup Banco de Dados

  3.1) Alterar credenciais do banco de dados no arquivo web.config para apontar para SQL Server local
  
  1.2) Criação da estrutura do banco com Entity Framework Code-First
    
    1.2.1)  Abrir a ferramenta Package Manager Console
    
    1.2.2)  Altera Default Project para Carriers.Data
    
    1.2.3) Executar o comando Update-Database -Verbose
    
4) Executar o programa e criar um usuário através do link 'Register as a new user'

5) Incluir, Editar, Pesquisar e Excluir Carriers
