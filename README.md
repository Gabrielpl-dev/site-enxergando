# Enxergando de Outras Formas

Site de uma página sobre a física da visão e a tecnologia assistiva usada por pessoas com deficiência visual — feito para feira de ciências. Sem build, sem dependências: é HTML/CSS/JS puro, uma pasta `img/` e pronto.

**[Ver o site](https://gabrielpl-dev.github.io/site-enxergando/)** · direção visual: revista científica / grid suíço — fundo branco, tinta quase-preta, hairlines, um único acento (âmbar).

## Conteúdo

| # | Seção | Assunto |
|---|-------|---------|
| 01 | Óptica da visão e deficiências visuais | Refração da luz, miopia, hipermetropia, astigmatismo e como cada uma se corrige |
| 02 | Como funciona o olho humano | Anatomia do olho — córnea, cristalino, retina, nervo óptico |
| 03 | Óculos de simulação | Empatia e ensino: simular uma deficiência visual em quem enxerga bem |
| 04 | O sistema Braille | Alfabeto de 6 pontos de Louis Braille, com tradutor de texto → Braille embutido |
| 05 | Bengala eletrônica com Arduino | Sensor ultrassônico HC-SR04, cálculo de distância pelo tempo de eco, aviso por vibração |

## Acessibilidade

Não é só o tema — a página aplica o que descreve:

- **"Ver a página como →"**: simula miopia, catarata ou glaucoma sobre o próprio conteúdo que você está lendo.
- **A+ Fonte**: aumenta o tamanho do texto.
- **Contraste**: alterna para alto contraste (preto/branco/âmbar).
- Skip link, `:focus-visible` visível, `alt` descritivo em toda imagem.

## Rodar localmente

Qualquer servidor estático serve. Por exemplo:

```bash
npx serve .
```

Depois abra o endereço que ele imprimir no terminal.

## Estrutura

```
index.html   → tudo: markup, estilos e o JS das interações (Braille, simulação, contraste)
img/         → figuras referenciadas pelo index.html
```

## Créditos das imagens

- `oculos.jpg` — Skyler Ewing / [Pexels](https://www.pexels.com/photo/5754242/), licença Pexels (uso livre).
- `prototipo.jpg` — [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Arduino_UNO_%2B_HC-SR04_%2B_HC_05_%2B_breadboard_-_bird%27s_eye_00.jpg), domínio público.
- Demais imagens: diagramas ilustrativos de referência (óptica, olho, Braille, bengala) — trocar pela origem/autoria original antes de qualquer uso além da feira de ciências.
