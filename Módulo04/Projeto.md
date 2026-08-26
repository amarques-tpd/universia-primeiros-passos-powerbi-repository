# RELATÓRIO DE VENDAS

Neste projeto foi utilizado uma sample com dados referentes à projetos executados. A partir desses dados foi criado um banco de dados no MySQL e posteriormente realizado um processo de ETL no Microsoft Power BI. Finalizando o projeto foi criado um relatório simples para exibir alguns dos dados que foram tratados.

# Transformação dos Dados:

1. Tabela "employee"
- Alteração do nome da tabela
- Exclusão de campos desnecessários
- Ajuste de cabeçalhos e tipos de dados
- O campo Salary foi modificado para número decimal fixo
- Mescla dos campos Fname e Lname criando-se o campo employee_name
- O campo Address foi separado nos campos Address_number, Address_desc e Address_state

2. Tabela "employee_department"
- Utilizando o recurso Mesclar Consultas, a partir da Tabela employee, foram adicionados os campos manager_name e Dname à tabela

3. Tabela "project"
- Alteração do nome da tabela
- Exclusão de campos desnecessários
- Ajuste de cabeçalhos e tipos de dados

4. Tabela "works_on"
- Alteração do nome da tabela
- Exclusão de campos desnecessários
- Ajuste de cabeçalhos e tipos de dados
- Utilizando o recurso Mesclar Consultas, a partir da Tabela project, foi adicionado o campo Pname

5. Tabela "dependent"
- Alteração do nome da tabela
- Exclusão de campos desnecessários
- Ajuste de cabeçalhos e tipos de dados

6. Tabela "department"
- Alteração do nome da tabela
- Exclusão de campos desnecessários
- Ajuste de cabeçalhos e tipos de dados

7. Tabela "dept_locations"
- Alteração do nome da tabela
- Exclusão de campos desnecessários
- Ajuste de cabeçalhos e tipos de dados
- Utilizando o recurso Mesclar Consultas, a partir da Tabela department, foram adicionados todos os campos existentes nesta à tabela "dept_locations"
- Mescla dos campos Dlocation e Dname criando-se o campo Store