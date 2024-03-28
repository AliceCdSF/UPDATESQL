# UPDATESQL

UPDATE alunos
SET cidade = 'Nova Odessa';


_____________ÚLTIMAS ATIVIDADES______ 

___ESTADO/CIDADE___

UPDATE alunos
SET estado = 'SP'
WHERE id= '4'


UPDATE alunos
SET cidade = 'Belo Horizonte'
WHERE id= '4'

_____________EM ORDEM_________________

SELECT * FROM `alunos` ORDER BY nome;
SELECT * FROM `alunos` ORDER BY id;
SELECT * FROM `alunos` ORDER BY estado;
SELECT * FROM `alunos` ORDER BY idade;

