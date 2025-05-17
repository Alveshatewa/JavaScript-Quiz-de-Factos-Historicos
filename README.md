# Quiz de Fatos Históricos

Este é um jogo de perguntas e respostas sobre eventos históricos, desenvolvido em JavaScript usando `readline-sync` para entrada de dados no terminal.

## 📌 Como funciona?

- O jogo sorteia aleatoriamente **10 perguntas** sobre eventos históricos.
- O jogador responde digitando o **ano** correspondente ao evento.
- Ao final do quiz, o jogador recebe uma pontuação e uma mensagem personalizada sobre seu desempenho.

## 🚀 Como executar?

1. Certifique-se de ter o [Node.js](https://nodejs.org/) instalado.
2. Clone este repositório ou copie o código para seu ambiente local.
3. Instale as dependências com o seguinte comando:
   ```bash
   npm install readline-sync
   
## 🏆 Mensagens de pontuação

Dependendo do número de acertos, o jogador recebe uma das seguintes mensagens:

0 a 3 acertos: "OH NÃO! Tente mais uma vez."

4 a 6 acertos: "BOM TRABALHO! Pratique um pouco mais."

7 a 9 acertos: "MUITO BOM! Você acertou a maioria."

10 acertos: "EXCELENTE! Você é um verdadeiro expert."

🔧 Estrutura do código

O código é estruturado com as seguintes funções:

selecioarQuestoesAleatorias(): Sorteia aleatoriamente um conjunto de perguntas.

exibirPergunta(): Apresenta a pergunta ao jogador e recebe sua resposta.

validarRespostaDoUsuario(): Verifica se a resposta está correta.

exibirResultado(): Mostra a pontuação final e a mensagem correspondente.

iniciarQuiz(): Gerencia a lógica do jogo, exibindo perguntas e calculando a pontuação.
