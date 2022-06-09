# Caso de Uso: Editar Aluno

## Sumário: 
Permite que um Administrador altere as informações um aluno da poli no sistema.

## Ator:
Administrador do sistema.

## Pré condições:
É necessário que o usuário seja Administrador e esteja logado no site e que o Aluno esteja cadastrado.

## Pós Condição:
* O Administrador permanece na página de informações e edição do aluno.
## Base Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. Com dados validos, o usuário acessa o sistema.
5. O usuaŕio acessa a página "Alunos" através do menu de navegação.
6. O sistema exibe uma lista com todos os alunos cadastrados e a opção "Ver" para ver e editar suas informações.
7. O usuário clica em "Ver".
10. O sistema abre uma página com as informações do aluno livres para alteração.
11. O usuário altera as informações que deseja.
12. O usuário clica em Salvar.
13. O sistema valida as informações, permite a troca e mostra uma mensagem de sucesso.
14. O sistema retorna a página de edição.

## Exception Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. Com dados validos, o usuário acessa o sistema.
5. O usuaŕio acessa a página "Alunos" através do menu de navegação.
6. O sistema exibe uma lista com todos os alunos cadastrados e a opção "Ver" para ver e editar suas informações.
7. O usuário clica em "Ver".
10. O sistema abre uma página com as informações do aluno livres para alteração.
11. O usuário altera as informações que deseja, colocando informações inválidas.
12. O usuário clica em Salvar.
13. O sistema não valida as informações, não atualiza as informações e mostra uma mensagem de erro.
14. O sistema retorna a página de edição.