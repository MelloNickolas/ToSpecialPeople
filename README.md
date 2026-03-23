# 🖤 Site para Meiriele — Guia do Nickolas

## Estrutura de pastas

```
/
├── index.html        ← tela de login
├── trilha.html       ← a jornada das 8 etapas
├── README.md         ← este arquivo
└── videos/
    ├── 1.mp4  (ou 1.mov / 1.heic)
    ├── 2.mp4
    ├── 3.mp4
    ├── 4.mp4
    ├── 5.mp4
    ├── 6.mp4
    ├── 7.mp4
    └── 8.mp4
```

---

## ✏️ O que você precisa personalizar

### 1. Seus textos escritos (em `trilha.html`)
Abra o arquivo `trilha.html` e procure pelos trechos com `[Escreva aqui: ...]` dentro de cada etapa no array `STEPS`.  
Substitua pelo que você quer que ela leia em cada etapa.

As etapas 5 (Além da fé) e 8 (O que importa) já têm texto escrito por mim com base no que você me contou. Você pode editar à vontade.

### 2. Os vídeos
Coloque seus vídeos na pasta `videos/` nomeados de `1` a `8`.  
Formatos aceitos: `.mp4`, `.mov`, `.heic` (o player tenta mp4 e mov automaticamente).

> ⚠️ O iPhone grava em `.mov` ou `.heic`. O ideal é converter para `.mp4` antes de colocar online.  
> Você pode converter grátis em: https://cloudconvert.com/mov-to-mp4

---

## 🔐 Login
As credenciais estão no topo do `index.html`:
```js
const NOME = "Meiriele Débora da Silva";
const DATA = "24/03/2006";
```
Não precisa mudar nada a menos que queira.

---

## 🚀 Subir no GitHub Pages

1. Crie um repositório no GitHub (pode ser privado se quiser)
2. Faça upload de todos os arquivos + a pasta `videos/`
3. Vá em **Settings → Pages**
4. Em "Branch", selecione `main` e clique em **Save**
5. O site ficará disponível em:  
   `https://SEU_USUARIO.github.io/NOME_DO_REPOSITORIO`

> 💡 Dica: use um nome de repositório neutro como `p` ou `presente` pra não dar spoiler na URL.

---

## 🥚 Easter Eggs (pra você saber)

| Etapa | Trigger | O que acontece |
|-------|---------|----------------|
| 1, 3, 5, 7 | Ficar parada ~9s sem mexer o mouse | Aparece uma frase psicanalítica |
| 2, 4, 6, 8 | Clicar 3x no título da etapa | Aparece uma frase psicanalítica |
| Login | Digitar nome e data corretos | Frase de Lacan aparece antes de entrar |
| Login | Ficar parada ~8s sem mexer o mouse | Frase aleatória de psicanálise aparece |

---

## 🎬 Ordem das etapas

1. **O começo** — quando percebi que você era especial
2. **O que eu vejo em você** — o que enxergo quando te olho
3. **Os momentos que guardo** — minha memória favorita
4. **O que sinto** — o que você desperta em mim
5. **Além da fé** — o que nos une vai além do que cada um acredita
6. **O que quero construir** — o que imagino pra nós
7. **Feliz aniversário** — hoje é seu dia
8. **O que importa** — se não for nós, vai ser doido

---

Feito com carinho 🖤
