# GPT @home

Implementação de uma solução para a tarefa quiz da competição Robocup@home, utilizando uma abordagem baseada em modelos da família Generative Pre-trained Transformers (GPT).

## Quiz @home

A competição de robótica @home consite no desenvolvimento de um robô que desempenha tarefas domésticas. Exemplos de tarefas, incluem: reconhecimento de objetos, navegação em ambiente e interação com humanos. Dentro da interação com humanos, está a tarefa Quiz. Nesta tarefa, espera-se que o robô seja capaz de responder um conjunto de perguntas pre-definidas. Para isto, é necessário que o mesmo seja capaz de transformar voz em texto (*speech-to-text*), processar o texto e gerar uma resposta utilizando *text-to-speech*.

## Generative Pre-Trained Transformers (GPT)

Como abordagem para a solução da tarefa quiz, será investigada a possibilidade de utilizar um modelo gerador de texto da família GPT. Investigaremos a utilização de uma solução utilizando *few-shot learning*, utilizando as perguntas e respostas pre-definidas pela competição como contextos para geração de *prompts*. 
