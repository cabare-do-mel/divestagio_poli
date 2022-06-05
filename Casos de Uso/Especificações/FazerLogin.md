# Caso de Uso: Fazer Login

## Sumário: 
Permite que um aluno ou professor faça login no site da Divisão de Estágio da Poli

## Ator:
Alunos e Professores da Poli

## Pré condições:
É necessário que o usuário não esteja logado no site.

## Pós Condição:
* O Aluno, com dados válidos, é levado para a página inicial do aluno.
* O Professor, com dados válidos, é levado para a página inicial do professor.

Base Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário clica em "Entrar".
3. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
4. O usuário caso seja um aluno, clica em "entrar".
5. Com dados validos, o aluno ou professor acessa o sistema.

Exception Sequence:
O usuário acessa o site da Divisão de Estágio.
O usuário clica em "entrar".
O usuário não preenche todos os campos necessários para o login.
O usuário clica em "entrar"
O usuário é notificado que precisa preencher todos os campos necessários para conseguir realizar o login com sucesso.
