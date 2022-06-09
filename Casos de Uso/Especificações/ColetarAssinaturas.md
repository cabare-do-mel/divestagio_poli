# Caso de Uso: Coletar Assinaturas

## Sumário: 
Este caso de uso permite que um aluno da Poli ao logar-se no Site da Divisão de Estágio da Politécnica, possa coletar as assinaturas necessárias para validar
seu relatório de estágio.

## Ator:
Alunos da Poli.

## Pré condições:
É necessário que o usuário esteja logado no site da Divisão de Estágio da Politécnica.

## Pós Condição:
Um email é enviado para o professor orientador do usuário e o representante da empresa do usuário, e coleta suas assinaturas digitais, de forma que eles assinam o relatório.

## Base Sequence:
1. O usuário acessa a página inicial.
2. O usuário acessa a pagina "Relatórios" através do menu de navegação.
3. O sistema exibe o status dos Relatórios e as opções "Modelos de Relatórios", "Coletar assinaturas" e "Entregar Relatórios".
4. O usuário clica em "Coletar Assinaturas".
5. O sistema exibe um formulário que o usuário deverá preencher com os dados do seu professor orientador e o representante da empresa do usuário, e realizar o upload 
de seu relatório.
6. O usuário clica em "Enviar".
7. O sistema envia o relatório automaticamente para ambos o professor orientador do usuário e o representante da empresa do usuário, e coleta suas assinaturas digitais,
de forma que eles assinam o relatório e retornam o email.
