# Caso de Uso: Cadastrar Professor

## Sumário: 
Permite que um Administrador cadastre um professor da poli no sistema.

## Ator:
Administrador do sistema.

## Pré condições:
É necessário que o usuário seja Administrador e esteja logado no site.

## Pós Condição:
* O Administrador é retorna a página de lista de professor.

## Base Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. Com dados validos, o usuário acessa o sistema.
5. O usuaŕio acessa a página "Solicitações e Cadastros" através do menu de navegação.
6. O sistema exibe: dados do número de empresase estágio aprovados e pendentes, do número de professores ja cadastrados no sistema; Três opções com "Empresas", "Estágios" e "Professores".
7. O usuário clica em "Professores".
8. O sistema exibe a lista de professores já cadastrados, a opção de ver as informações deste e um botão "Cadastrar Professor".
9. O usuário clica no botão "Cadastrat Professor".
10. O sistema abre um modal com o formulário de cadastro.
    11.1. O usuário preenche todo o modal.
        12.1.1. O usuário clica no botão "Salvar".
        13.1.1. O usuário retorna a lista de professores cadastrados agora com o novo professor.
        12.2.2. O usuário clica no botão "Cancelar".
        13.2.2. O usuário retorna a lista de professores cadastrados sem a adição do novo professor.
    11.2. O usuário não preenche o modal e clica no botão "Cancelar".
    12.2 O usuário retorna a lista de professores cadastrados sem a adição do novo professor.

## Exception Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. Com dados validos, o usuário acessa o sistema.
5. O usuaŕio acessa a página "Solicitações e Cadastros" através do menu de navegação.
6. O sistema exibe: dados do número de empresase estágio aprovados e pendentes, do número de professores ja cadastrados no sistema; Três opções com "Empresas", "Estágios" e "Professores".
7. O usuário clica em "Professores".
8. O sistema exibe a lista de professores já cadastrados, a opção de ver as informações deste e um botão "Cadastrar Professor".
9. O usuário clica no botão "Cadastrat Professor".
10. O sistema abre um modal com o formulário de cadastro.
11. O usuário não preenche todo o modal ou o preenche incorretamente.
12. O sistema dispara um popUp de erro "Informações faltantes ou incorretas.  Por favor verifique seus dados".
13. O sistema retorna ao modal.