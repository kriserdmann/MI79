## Desafio Git: O Grande Q&A Ágil

Sua missão: A turma se tornou uma equipe de especialistas em metodologias ágeis! A missão é construir, de forma colaborativa, uma base de conhecimento respondendo a 50 perguntas sobre o tema. O sucesso não depende apenas de responder corretamente, mas da organização da equipe para entregar o trabalho sem caos.

## Objetivos de Aprendizagem:

Organização e Comunicação: Aprender a dividir tarefas e comunicar o trabalho em andamento usando as Issues do GitHub.

Fluxo de Trabalho Colaborativo: Praticar o ciclo completo de branch -> commit -> push -> Pull Request em um repositório compartilhado.

Autonomia em Resolução de Conflitos: Ser o único responsável por resolver os conflitos da sua própria contribuição.

## Como o Projeto Funciona

Este repositório contém dois arquivos principais:
README.md: Este arquivo, com as instruções.
perguntas.txt: Um arquivo de texto com 50 perguntas sobre metodologias ágeis. O trabalho de vocês é preencher as respostas.

## O Desafio da Organização: Como Dividir o Trabalho

Para evitar que duas pessoas respondam à mesma pergunta, o trabalho deve ser "reivindicado" antes de começar.

## Desafio 1: Reivindicando suas Perguntas

Vá até a aba "Issues" no repositório do GitHub.

Clique em "New Issue".

No título, especifique o bloco de perguntas que você irá responder. Exemplo: Respondendo perguntas 01 a 05.

No corpo da issue, mencione a si mesmo para que fique registrado.

Clique em "Submit new issue".

Regra de Ouro: Antes de criar sua Issue, verifique se as perguntas que você quer já não foram reivindicadas por um colega!

Fluxo de Trabalho e Desafios Técnicos

## Desafio 2: Configuração Inicial

Aceite o convite de colaborador (se ainda não o fez).

Clone o repositório para a sua máquina.

## Desafio 3: Trabalho Isolado

Crie uma branch específica para o seu bloco de perguntas.

Padrão do nome da branch: feature/respostas-perguntas-X-Y.

Exemplo: feature/respostas-perguntas-01-05.

## Desafio 4: A Contribuição

Abra o arquivo perguntas.txt e preencha as respostas para o bloco de perguntas que você reivindicou.

Faça o commit das suas alterações usando o padrão Conventional Commits.

Exemplo: feat: responde as perguntas de 01 a 05 sobre o Manifesto Ágil.

## Desafio 5: Propondo a Integração

Envie sua branch para o GitHub (git push).

Abra um Pull Request (PR) para mesclar sua branch na main. No corpo do PR, você pode "linkar" a issue que você criou digitando # e o número dela.

## Desafio 6: Gerenciamento e Resolução de Conflitos

Seu PR está com conflitos? A responsabilidade de resolver é sua.

Sincronize sua main local (git checkout main e git pull).

Volte para a sua branch e use git rebase main.

Resolva os conflitos que aparecerão no arquivo perguntas.txt.

Continue o rebase (git add . e git rebase --continue).

Atualize seu PR com a branch corrigida (git push --force-with-lease).

## Desafio 7: A Entrega Final

Quando seu PR estiver sem conflitos, faça o merge.

Parabéns, sua contribuição agora faz parte da base de conhecimento da turma!
