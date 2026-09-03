3# Sistema Acadêmico em C
Este projeto foi desenvolvido como trabalho acadêmico em dupla para a disciplina de Fundamentos de Programação. O sistema implementa um controle acadêmico com módulos separados para alunos e professores, utilizando alocação dinâmica de memória (malloc e realloc) para suportar o crescimento do número de registros em tempo de execução.

## Funcionalidades
* [x] Cadastro de Alunos e Professores (com autoincremento de RA/Matrícula)
* [x] Pesquisa individual ou listagem geral de todos os registros
* [x] Alteração de Nome ou Curso (com validação de opções)
* [x] Exclusão lógica e física (com rearranjo do vetor em memória)
* [x] Alocação dinâmica de memória (`realloc`) para crescimento sob demanda
* [x] Tratamento de erros e validação de entradas do usuário

## Como acessar
# Clone o repositório
git clone https://github.com/seu-usuario/sistema-academico-c.git

# Acesse o diretório
cd sistema-academico-c

# Compile e execute
gcc -o main main.c Academico.c && ./main

## Tecnologias Utilizadas
* **Linguagem:** C
* **Bibliotecas:** `stdio.h`, `stdlib.h`, `string.h`
* **Conceitos aplicados:** Ponteiros, Estruturas (Structs), Alocação Dinâmica, Manipulação de Strings.

# Autores
Ian Goor - Módulo dos Professores
Leonardo Hideki - Módulo dos Alunos
