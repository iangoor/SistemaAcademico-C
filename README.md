# Sistema Acadêmico em C
Este projeto foi desenvolvido como trabalho acadêmico em dupla para a disciplina de Fundamentos de Programação. O sistema implementa um controle acadêmico com módulos separados para alunos e professores, utilizando alocação dinâmica de memória (malloc e realloc) para suportar o crescimento do número de registros em tempo de execução.

# O que o sistema faz
☑ Cadastro de Alunos e Professores (com autoincremento de RA/Matrícula)

☑ Pesquisa individual ou listagem geral de todos os registros

☑ Alteração de Nome ou Curso (com validação de opções)

☑ Exclusão lógica e física (com rearranjo do vetor em memória)

☑ Alocação dinâmica de memória (realloc) para crescimento sob demanda

☑ Tratamento de erros e validação de entradas do usuário

# Como rodar o projeto

Clone o repositório

git clone https://github.com/seu-usuario/sistema-academico-c.git

Acesse o diretório

cd sistema-academico-c

Compile e execute

gcc -o main main.c Academico.c && ./main



# Tecnologias utilizadas
- Linguagem: C

- Bibliotecas: stdio.h, stdlib.h, string.h

- Conceitos aplicados: Ponteiros, Estruturas (Structs), Alocação Dinâmica, Manipulação de Strings.

# Sobre a organização do código

O projeto está dividido em três arquivos principais:

- Academico.h – Contém as definições das structs Aluno e Professor, além dos protótipos das funções.

- Academico.c – Implementa todas as funções do sistema (cadastro, pesquisa, alteração, exclusão e menu).

- main.c – Arquivo principal que inicializa o sistema e chama o menu recursivo.

# Autores
Ian Goor - Módulo dos Professores
Leonardo Hideki - Módulo dos Alunos
