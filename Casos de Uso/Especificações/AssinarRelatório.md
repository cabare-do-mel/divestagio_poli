# Caso de Uso: Assinar Relatórios

## Sumário: 
Permite que o professor ou administrador visualize os alunos relacionados a ele.

## Ator:
Professores e Admnistradores da Poli.

## Pré condições:
É necessário que o usuário esteja logado no site
É necessário que o aluno tenha entregado o relatório.

## Pós Condição:
* O professor verá a lista de alunos orientados por ele
* O administrador verá a lista de todos os alunos do site

## Base Sequence:
1. O usuário acessa a página inicial
    2.1 O usuário Professor clica em alunos
    3.1 O usuário Professor visualiza a lista de alunos relacionados a ele e uma opção "Ver".
    4.1 O usuário Professor clica em "Ver"
    5.1 O usuário Professor acessa a solicitação de assinatura do aluno e vizualiza as opções "Assinar Relatório".
    6.1 O usuário Professor aceita clica "Assinar Relatório"
    7.1 O usuário retorna a lista de solicitações;
    
    2.2 O usuário Administrador clica em alunos
    3.2 O usuário Administrador visualiza a lista de alunos relacionados a ele e uma opção "Ver" e "assinar".
    4.2 O usuário Administrador clica em "assinar"
    5.2 O usuário Administrador acessa a solicitação de assinatura do aluno e vizualiza as opções "Assinar Relatório".
    6.2 O usuário Administrador aceita clica "Assinar Relatório"
    7.2 O usuário retorna a lista de solicitações;