# INEMA.NCIA — o caderno do canal, virado curso

Curso de **leitura editorial** montado a partir do canal de Telegram **INEMA.NCIA**:
27 tópicos reorganizados em 6 trilhas sobre a parte que a máquina não faz por você —
atenção, percepção, hábito, persuasão e as habilidades humanas que seguem escassas.

➡️ **Abrir o curso:** [`curso/index.html`](./curso/index.html) (a raiz redireciona para lá).

## Trilhas

| # | Trilha | Seções |
|---|--------|:------:|
| 1 | Neurociência da Atenção & do Foco | 6 |
| 2 | Percepção & Autoconhecimento | 5 |
| 3 | Hábitos, Motivação & Determinação | 5 |
| 4 | Habilidades & Talentos do Futuro | 3 |
| 5 | Persuasão & Psicologia Viral | 5 |
| 6 | Recursos do Canal | 3 |

**27 seções no total.** Cada tópico do canal virou uma seção de leitura.

## Formato

Feito no padrão **formato-curso INEMA v3** (reading-mode editorial): papel quente, tipografia
serif (Spectral + Source Serif 4), um único acento, coluna de leitura com trilho de margem
(sidenotes), progresso silencioso, temas papel/sépia/escuro e modo de legibilidade. Tudo
**self-contained** — HTML estático, sem build, sem backend; abre em `file://` ou em qualquer
host estático (GitHub Pages / Vercel).

```
curso/
├── index.html              landing (lista as trilhas)
├── t1.html … t6.html       índices de trilha (cards dos módulos)
├── t1-1.html … t6-1.html   10 módulos (páginas de leitura)
└── assets/                 learn.css · learn.js (camada v3)
```

Estrutura de 3 níveis (Curso → Trilha → Módulo), com mapa de módulos na margem
(`.rail-modules`) em cada aula — padrão canônico atual da skill `formato-curso-v3`.

## Origem & privacidade

O conteúdo foi extraído do canal INEMA.NCIA e **reescrito** em prosa didática — o site
**não expõe nomes de membros**. O dump bruto do Telegram (mensagens originais com autores)
é mantido **apenas localmente** e não faz parte deste repositório público.

---

Parte do ecossistema **[INEMA.CLUB](https://inema.club)**.
