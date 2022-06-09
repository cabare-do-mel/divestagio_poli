# Caso de Uso: Cadastrar Empresa

## Sumário: 
Permite que um aluno da Poli possa Cadastre sua empresa onde estagia atualmente, assim caso ele encerre este estágio no futuro e inicie outro, basta ele "Cadastrar" 
uma nova empresa.

## Ator:
Alunos da Poli.

## Pré condições:
É necessário que o usuário seja Aluno e esteja logado no site.

## Pós Condição:
* O Aluno preenche os dados necessários para realizar o cadastro de sua empresa, porém esse cadastro fica pendente até que o Administrador o confirme/valide.

## Base Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. Com dados validos, o usuário acessa o sistema.
5. O usuaŕio acessa a página "Iniciar Processo" através do menu de navegação.
6. O usuário clica em "Cadastrar Empresa".
7. O sistema exibe um formulário com os campos "Nome Fantasia", "Telefone", "email" e "CNPJ".
8. O usuário preenche todos os campos corretamente.
9. O usuário clica em "Enviar cadastro".
10. O sistema enviar a solicitação de cadastro de estágio ao administrador para que ele o valide.

## Exception Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. Com dados validos, o usuário acessa o sistema.
5. O usuaŕio acessa a página "Iniciar Processo" através do menu de navegação.
6. O usuário clica em "Cadastrar Empresa".
7. O sistema exibe um formulário com os campos "Nome Fantasia", "Telefone", "email" e "CNPJ".
8. O usuário não preenche todos os campos.
9. O usuário clica em "Enviar cadastro".
10. O sistema notifica o usuário de que ele deve preencher todos os campos corretamente.
