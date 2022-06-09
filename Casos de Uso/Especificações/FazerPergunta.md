# Caso de Uso: Fazer Pergunta

## Sumário: 
Permite que um aluno envie uma pergunta ao site da Divisão de Estágio da Poli

## Ator:
Alunos da Poli.

## Pré condições:
É necessário que o usuário seja Aluno e esteja logado no site.

## Pós Condição:
* O Aluno, permanece na página de "Fazer Perguntas".

## Base Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. Com dados validos, o usuário acessa o sistema.
5. O usuaŕio acessa a página "FAQ" através do menu de navegação.
6. O sistema exibe as três perguntas mais frequentes, uma opção de procurar pergunta e um botão com a opção "Fazer Pergunta"
7. O usuário clica em "Fazer Pergunta".
8. O sistema exibe uma área de texto destinada à pergunta, um botão de enviar e as três perguntas mais frequentes.
9. O usuário digita sua pergunta.
10. O usuário clica em "Enviar Pergunta".
11. Com a área de texto preenchida o usuário recebe uma notificação de pergunta realizada.
12. O usuário retorna a página de "Fazer Pergunta" com a área de texto vazia novamente.

## Exception Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. Com dados validos, o usuário acessa o sistema.
5. O usuaŕio acessa a página "FAQ" através do menu de navegação.
6. O sistema exibe as três perguntas mais frequentes, uma opção de procurar pergunta e um botão com a opção "Fazer Pergunta"
7. O usuário clica em "Fazer Pergunta".
8. O sistema exibe uma área de texto destinada à pergunta, um botão de enviar e as três perguntas mais frequentes.
10. O usuário clica em "Enviar Pergunta" sem preencher a área de texto designada à pergunta.
11. O usuário recebe uma notificação de pergunta não realizada.
12. O usuário retorna a página de "Fazer Pergunta".
