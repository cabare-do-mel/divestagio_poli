# Caso de Uso: Aprovar Cadastro de Empresa

## Sumário: 
Permite que o usuário aprove os cadastros das empresas solicitadas pelos alunos.

## Ator:
Administradores do site da Divisão de Estágio da Poli.

## Pré condições:
É necessário que o usuário esteja logado no site.

## Pós Condição:
* O Administrador, logado e após clicar em "Solicitações e Cadastro", depois em "Empresas" e então em "Aprovar empresas" poderá aceitar ou rejeitar as solicitações
de cadastros das empresas dos alunos.

## Base Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. O sistema válida os dados do usuário.
5. o usuário acessa o sistema, caso os dados estejam válidos.
6. O usuário clica em "Solicitações e Cadastro".
7. O sistema exibe a quantidade de cadastros realizado e pendentes de Empresas, Estágios e Professores. E permite que o usuário possa escolher também abrir cada um 
deles separadamente: Empresas, Estágios e Professores.
8. O usuário clica em "Empresas".
9. O sistema exibe uma lista das empresas já cadastradas e a opção "Aprovar Empresas".
10. O usuário clica em "Aprovar empresas".
11. O sistema exibe uma lista com informações das empresas cujo cadastro poderá serem aprovado ou rejeitado pelo usuário.
12. O usuário clica em "aceitar" ou "rejeitar".
13. O sistema então valida ou não o cadastro da empre e envia uma notificação para o aluno respectivo à solicitação de cadastro da empresa.
