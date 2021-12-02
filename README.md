# DsLearn
Sistema baseado em uma plataforma de ensino. Esse Sistema foi um trabalho desenvolvido no Bootcamp de Spring React da DevSuperior. 

# Descrição
O sistema consiste em uma plataforma de ensino que mantém informações de cursos, suas turmas e alunos, bem como um fórum para perguntas e respostas sobre os conteúdos do curso. Os atores do sistema podem ser alunos e professores. Há também usuários administradores, que são os únicos autorizados a cadastrar cursos e turmas.

Um curso é composto de vários “recursos”, que são grupos de conteúdos. Estes recursos podem ser trilhas de aprendizado, bônus, links externos, e o próprio fórum de perguntas e respostas do curso. Cada recurso pode conter seções, e estas seções por sua vez é que vão conter as aulas, que podem ser conteúdos em vídeo e/ou texto, ou tarefas para serem entregues pelos alunos.

Uma tarefa pode ter um peso, uma data de entrega, um número de questões e a quantidade mínima de acertos necessários para ser aceita. Quando um aluno entrega a tarefa, esta fica aguardando pelo feedback do professor, e ela pode ser aceita ou rejeitada.


# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- Jpa / Hibernate
- Spring Security / OAuth 2.0 e Token JWT
- Maven

## Implantação em desenvolvimento
- Banco de Dados: H2

## Padrões utilizados
- Padrão arquitetural: REST
- Padrões estruturais: DTO
