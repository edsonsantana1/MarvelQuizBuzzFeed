# Marvel Quiz

Este é um projeto de quiz baseado no universo Marvel, desenvolvido com Angular. O objetivo do quiz é determinar qual herói da Marvel você seria com base nas suas respostas.

## Lógica do Projeto

O projeto consiste em um componente principal de quiz (`QuizzComponent`) que carrega perguntas e opções de um arquivo JSON (`quizz_questions.json`). O usuário seleciona suas respostas e, ao final, o quiz determina qual herói da Marvel corresponde às respostas fornecidas.

### Estrutura do Projeto

- `src/assets/data/quizz_questions.json`: Contém as perguntas, opções e resultados do quiz.
- `src/app/components/quizz/quizz.component.ts`: Componente principal do quiz que gerencia a lógica do jogo.
- `src/app/components/quizz/quizz.component.html`: Template HTML do componente de quiz.
- `src/app/components/quizz/quizz.component.css`: Estilos CSS do componente de quiz.

### Comandos para Iniciar o Projeto
1.	cd marvel-quiz	
2.	npm install
3.	ng serve
Abra o navegador e acesse:http://localhost:4200

