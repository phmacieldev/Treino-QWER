# Treino QWER

Jogo de ritmo para treinar precisão nas teclas **Q, W, E e R** — uma tecla por vez, apertando quando a barra cruza a linha. Feito em um único arquivo HTML, sem dependências.

## 🌐 Jogar online

**https://treino-qwer.vercel.app/**

Hospedado na Vercel. Funciona no navegador (teclado) e no celular (botões na tela).

## Como funciona

- **12 níveis progressivos**, do "Aquecimento" ao "Chefe de garagem" — cada um mais rápido que o anterior. Passe da meta de precisão para liberar o próximo.
- A partir do nível 7 (modo estrito), acertos "raspou" deixam de contar na precisão.
- **Treino livre** com velocidade, intervalo e quantidade de barras ajustáveis.
- **Compensação de latência** configurável (−80 a +80 ms).
- Resultados detalhados: precisão, tempo médio (adiantado/atrasado), constância (±ms), erros por tecla e melhor sequência.
- Progresso salvo localmente no navegador (`localStorage`).

## Rodar localmente

Basta abrir o `index.html` em qualquer navegador — não precisa de servidor nem de build.
