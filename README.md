# Atividade Mer e Der

## Projeto: Gestão de escola (Alunos, Matrículas e Professores)

![Modelo](./atvDEReMER.drawio.png)

## Código "Dicionário de Dados"

|Entidade|Atributo|Tipo|Tamanho|Descrição
|-|-|-|-|-|
|Alunos|`id`|`int`|`11`|Chave Primária|
|Alunos|`Nome`|`varchar`|`40`|nome do aluno|
|Alunos|`Idade`|`int`|`5`|idade do aluno|
|Alunos|`Nascimento`|`int`|`20`|data de nascimento do aluno|
|Alunos|`Turma`|`varchar`|`1`|letra da turma do aluno|
|Alunos|`Telefone`|`int`|`10`|numero de telefone do aluno|
|Disciplina|`id`|`int`|`11`|Chave Primária|
|Disciplina|`Nome`|`varchar`|`11`|nome da disciplina|
|Disciplina|`Quantidade`|`varchar`|`14`|numero de aulas por turma|
|Disciplina|`Professor`|`varchar`|`13`|nome do professor que ensina|
|Professor|`id`|`int`|`11`|Chave Primária|
|Professor|`Nome`|`varchar`|`13`|nome do professor que ensina|
|Professor|`Idade`|`int`|`5`|idade do professor|
|Professor|`Nascimento`|`varchar`|`13`|data de nascimento do professor|
|Professor|`Telefone`|`varchar`|`13`|telefone do professor|
|Professor|`Especialidade`|`varchar`|`16`|Matéria que o professor ensina|
|Matrícula|`id_aluno`|`int`|`16`|Chave Primária|
|Matrícula|`id_matrícula`|`int`|`16`|Chave Primária|
|Matrícula|`id_disciplina`|`int`|`16`|Chave Primária|
|Matrícula|`Nome do Aluno`|`varchar`|`16`|Nome do Aluno|

# Tabelas em CSV

|[Aluno.CSV](./Aluno.CSV)|
