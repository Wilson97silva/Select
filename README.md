# Select

-- Para seleciona todos os itens de uma tabela

SELECT * from [NOME DA TABELA];

Exemplo : SELECT * from employees;

-- selecionar algumas tabela que você precisar 

SELECT [COLUNA1], [COLUNA2], [COLUNA3,] 
FROM [NOME DA TABELA];

Exemplo: SELECT employee_id, first_name, last_name, salary, department_id 
from employees; 

-- SELECT com alias 
SELECT employee_id as "ID", first_name as "Primeiro nome", last_name as "Segundo nome", salary as "Salario", department_id "Codigo do departamento"
from employees;
-- Não necessaria mente precisa ter a palavra AS entre nome real da tabela e como você deseja que apareca, deixando ela sem tambem ira funcionar 

SELECT employee_id  "ID", first_name  "Primeiro nome", last_name "Segundo nome", salary "Salario", department_id "Codigo do departamento"
from employees;
