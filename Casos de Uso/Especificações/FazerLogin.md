# Caso de Uso: Fazer Login

## Sumário: 
Permite que um aluno, professor ou administrador faça login no site da Divisão de Estágio da Poli

## Ator:
Alunos da Poli, Professores da Poli, e Administradores da Divisão de Estágio.

## Pré condições:
É necessário que o usuário não esteja logado no site.

## Pós Condição:
* O Aluno, com dados válidos, é levado para a página inicial do aluno.
* O Professor, com dados válidos, é levado para a página inicial do professor.
* O Administrador, com dados válidos, é levado para a página inicial do administrador.

## Base Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. O sistema válida os dados do usuário.
5. o usuário acessa o sistema, caso os dados estejam válidos.

## Exception Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário não preenche todos os campos necessários para o login.
3. O usuário clica em "entrar".
4. O sistema notifica o usuário que ele precisa preencher todos os campos necessários para conseguir realizar o login com sucesso.
