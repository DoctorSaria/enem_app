# Plataforma de Estudos ENEM

App pessoal de estudos para o ENEM.

## Sobre

Estudar para o ENEM sozinho tem três problemas: a gente erra questões e não entende por quê, não sabe o que estudar depois, e escreve redação sem quem corrija. Este app junta essas três coisas num lugar só.

## Funcionalidades

### Diagnóstico de erros
Questões de provas reais do ENEM (com gabarito oficial). O app identifica o tópico de cada questão e mostra em quais tópicos você está fraco — o foco é a explicação do erro, não a nota.

### Explicações em hipertexto
Termos-chave nas questões e nos feedbacks são clicáveis, como links da Wikipédia. Tocar em um conceito abre a explicação dele na hora.

### Plano de rotina adaptativo
Com base nos erros, o app sugere o que estudar e em que ordem. A rotina se ajusta conforme você melhora ou trava em cada tópico.

### Correção de redação pelas 5 competências
Você escreve e envia a redação no app. Uma IA corrige pelos critérios oficiais do ENEM: nota de 0 a 1000, nota por competência (C1 a C5) e comentário do que melhorar. Sem corretor humano.

## Estado atual

O app já existe e funciona em Flutter, com tema claro/escuro e navegação por abas: Início, Tópicos, Redações e Amigos.

Em construção agora:
- [ ] Módulo de redações (lista, escrita/envio, análise com notas por competência)
- [ ] Diagnóstico de erros em matemática
- [ ] Plano de rotina adaptativo

## Stack

- **Flutter**
- **Firebase** (plano Spark gratuito) — autenticação por email/Google e banco de dados
- **API pública do ENEM** — fonte inicial das questões
- **API de LLM** — correção de redação

## Como rodar

```bash
flutter pub get
flutter run
