# Caso de Uso: Editar Professor

## Sumário: 
Permite que um Administrador altere as informações um professor da poli no sistema.

## Ator:
Administrador do sistema.

## Pré condições:
É necessário que o usuário seja Administrador e esteja logado no site e que o Professor esteja cadastrado no sistema.

## Pós Condição:
* O Administrador permanece na página de informações e edição do professor.

## Base Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. Com dados validos, o usuário acessa o sistema.
5. O usuaŕio acessa a página "Solicitações e Cadastros" através do menu de navegação.
6. O sistema exibe: dados do número de empresase estágio aprovados e pendentes, do número de professores ja cadastrados no sistema; Três opções com "Empresas", "Estágios" e "Professores".
7. O usuário clica em "Professores".
8. O sistema exibe a lista de professores já cadastrados, a opção "Ver" para ver e editar as informações deste e um botão "Cadastrar Professor".
9. O usuário clica no botão "Ver".
10. O sistema abre uma página com as informações do professor livres para alteração.
11. O usuário altera as informações que deseja.
12. O usuário clica em Salvar.
13. O sistema valida as informações, permite a troca e mostra uma mensagem de sucesso.
14. O sistema retorna a página de edição.
## Exception Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. Com dados validos, o usuário acessa o sistema.
5. O usuaŕio acessa a página "Solicitações e Cadastros" através do menu de navegação.
6. O sistema exibe: dados do número de empresase estágio aprovados e pendentes, do número de professores ja cadastrados no sistema; Três opções com "Empresas", "Estágios" e "Professores".
7. O usuário clica em "Professores".
8. O sistema exibe a lista de professores já cadastrados, a opção "Ver" para ver e editar as informações deste e um botão "Cadastrar Professor".
9. O usuário clica no botão "Ver".
10. O sistema abre uma página com as informações do professor livres para alteração.
11. O usuário altera as informações que deseja, colocando informações inválidas.
12. O usuário clica em Salvar.
13. O sistema não valida as informações, não atualiza as informações e mostra uma mensagem de erro.
14. O sistema retorna a página de edição.