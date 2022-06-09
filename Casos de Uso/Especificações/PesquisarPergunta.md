# Caso de Uso: Pesquisar Pergunta no FAQ

## Sumário: 
Permite que um aluno procure uma pergunta/dúvida já existente/feita no FAQ do site da Divisão de Estágio da Poli

## Ator:
Alunos da Poli.

## Pré condições:
É necessário que o usuário seja Aluno e esteja logado no site.

## Pós Condição:
* O Aluno, permanece na página de "Fazer Perguntas" e encontra uma pergunta similar à sua pesquisa ou não se não houver nenhuma similar.

## Base Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. Com dados validos, o usuário acessa o sistema.
5. O usuaŕio acessa a página "FAQ" através do menu de navegação.
6. O sistema exibe as três perguntas mais frequentes, uma opção de procurar pergunta e um botão com a opção "Fazer Pergunta".
7. O usuário clica em "O que você quer saber?".
8. O usuário digita a sua pergunta na área designada.
9. O sistema exibe uma área de texto destinada à pergunta, um botão de enviar e as três perguntas mais frequentes.
10. O usuário aperta na lupa para buscar uma pergunta similar a sua.
11. O sistema realiza uma busca no FAQ/banco de dados de perguntas.
12. O sistema retorna a(s) pergunta(s) similar(es) à pergunta feita pelo usuário.

## Exception Sequence:
1. O usuário acessa o site da Divisão de Estágio.
2. O usuário preenche os campos com seu Usuário cadastrado e sua Senha cadastrada.
3. O usuário clica em "entrar".
4. Com dados validos, o usuário acessa o sistema.
5. O usuaŕio acessa a página "FAQ" através do menu de navegação.
6. O sistema exibe as três perguntas mais frequentes, uma opção de procurar pergunta e um botão com a opção "Fazer Pergunta".
7. O usuário clica em "O que você quer saber?".
8. O usuário digita a sua pergunta na área designada.
9. O sistema exibe uma área de texto destinada à pergunta, um botão de enviar e as três perguntas mais frequentes.
10. O usuário aperta na lupa para buscar uma pergunta similar a sua.
11. O sistema realiza uma busca no FAQ/banco de dados de perguntas.
12. O sistema não retorna nenhuma pergunta, pois não encontrou nada similar à busca feita pelo usuário.
