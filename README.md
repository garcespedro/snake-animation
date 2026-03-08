# 🐍 GitHub Contribution Snake Animation m 

Este repositório gera automaticamente a **animação da cobra que come o gráfico de contribuições do GitHub**.

A animação é criada automaticamente usando **GitHub Actions** e atualizada diariamente.

---

## 🚀 Como funciona

1. O **GitHub Actions** executa automaticamente todos os dias.
2. Ele usa o projeto [`Platane/snk`](https://github.com/Platane/snk) para gerar a animação da cobra.
3. O ficheiro SVG gerado é publicado na branch `output`.
4. Esse SVG pode ser usado no README do teu perfil do GitHub.

---

## 📂 Estrutura do projeto

```
.
├── .github
│   └── workflows
│       └── snake.yml
└── README.md
```

---


---

## 📅 Atualização automática

A animação é atualizada automaticamente todos os dias através deste cron:

```
0 0 * * *
```

Ou seja, **uma vez por dia à meia-noite (UTC)**.

---

## 📄 Créditos

Este projeto usa o gerador de animação:

https://github.com/Platane/snk

---

⭐ Se gostaste, deixa uma **star no repositório**!

