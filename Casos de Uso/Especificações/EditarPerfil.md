# Caso de Uso: Editar Perfil

## Sumário: 
Permite que o usuário edite as informações do seu Perfil.

## Ator:
Alunos, Administradores e Professores da Poli.

## Pré condições:
É necessário que o usuário esteja logado no site.

## Pós Condição:
As informações de Perfil do usuário são atualizadas.

## Base Sequence:
1. O usuário acessa a página inicial.
2. O usuário clica em "Perfil".
3. O sistema exibe as informações pessoais do usuário, e as opções de "Caixa de Entrada", "Notas", "Editar Perfil" e "Sair".
4. O usuário clica em "Editar Perfil".
5. O usuário modifica as informações que lhe são permitidas modificar de forma ainda válida.
6. O usuário clica em "Salvar Alterações".
7. O sistema valida as informações, permite a troca e mostra uma mensagem de sucesso.
8. O sistema retorna à página de edição.


## Exception Sequence:
1. O usuário acessa a página inicial.
2. O usuário clica em "Perfil".
3. O sistema exibe as informações pessoais do usuário, e as opções de "Caixa de Entrada", "Notas", "Editar Perfil" e "Sair".
4. O usuário clica em "Editar Perfil".
5. O usuário modifica as informações que lhe são permitidas modificar, inserindo informações inválidas ou faltantes.
6. O usuário clica em "Salvar Alterações".
7. O sistema não valida as informações, não permite a troca e mostra uma mensagem de erro.
8. O sistema retorna a página de edição.
