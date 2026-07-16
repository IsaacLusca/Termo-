# Termo

Jogo de adivinhação de palavras em português, inspirado no Wordle.

## Como jogar

- Uma palavra de 5 letras é sorteada aleatoriamente
- Você tem 6 tentativas para acertar
- Após cada tentativa, as letras mudam de cor:
  - **Verde**: letra correta na posição certa
  - **Amarelo**: letra existe na palavra, mas em posição errada
  - **Cinza**: letra não existe na palavra

## Como rodar

Abra o arquivo `index.html` no navegador ou sirva com qualquer servidor estático:

```bash
npx serve .
```

## Tecnologias

- HTML, CSS e JavaScript puro (sem frameworks)
- Jest para testes
- Toastify para notificações
