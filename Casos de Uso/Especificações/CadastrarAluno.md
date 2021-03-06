# Caso de Uso: Cadastrar

## Sumário: 
Este caso de uso permite que um aluno da Poli cadastrar-se no Site da Divisão de Estágio da Politécnica.

## Ator:
Usuário Visitante.

## Pré condições:
É necessário que o usuário acesse a página de cadastro e não possua uma conta cadastrada com suas informações.

## Pós Condição:
Com dados válidos, o aluno da Poli tem sua conta cadastrada no site.

## Base Sequence:
1. O usuário acessa o site da Divisão de Estágio da Politécnica.
2. O usuário clica em "Cadastre-se aqui".
3. O usuário preenche os campos necessários, com seu Nome Completo, CPF, Email, senha e Período letivo.
4. O usuário clica em "Enviar Cadastro".
5. O sistema realiza o cadastro do aluno.

## Exception Sequence:
1. O usuário acessa o site da Divisão de Estágio da Politécnica.
2. O usuário clica em "Cadastre-se aqui".
3. O usuário não preenche todos os campos necessários para o cadastro.
4. O usuário clica em "Enviar Cadastro".
5. O sistema notifica o usuário que ele precisa preencher todos os campos necessários para conseguir realizar o cadastro com sucesso.

## Exception Sequence:
1. O usuário acessa o site da Divisão de Estágio da Politécnica.
2. O usuário clica em "Cadastre-se aqui".
3. O usuário insere um email fora do domínio da Poli.
4. O usuário clica em "Enviar Cadastro".
5. O sistema notifica o usuário que ele precisa preencher o campos email com um email aceitável para conseguir realizar o cadastro com sucesso.
