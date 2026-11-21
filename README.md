# CyberPyo Avatars

Avatares escoteiros em pixel art (estilo 16 bits) para o acampamento no Recanto Marista.

## Páginas

| Pasta | O que é |
|---|---|
| `avatar-bases/` | Gerador de avatar com os cenários das bases do evento (Apatu, Escola Carlos Drummond, Separação de Lixo, Bazar da Uopecann, Nascente e UAI). Baixa a imagem em PNG. |
| `mural/` | Mural do acampamento: mapa do Recanto Marista em pixel art onde cada jovem cria o avatar, informa nome e grupo escoteiro e se posiciona no mapa. |

Cada página é um único arquivo `index.html`, sem dependências nem build. Basta abrir no navegador.

## Personalização do avatar

- Uniforme: regular, do mar, do ar e escotista
- 11 cabelos, 6 cores de cabelo, 6 cores de olhos, 5 tons de pele
- Lenço com duas cores livres (principal e listras)
- Expressão, barba e bigode, óculos de grau e escuros
- Poses: sentido, saudação e fazendo 2, sempre com a forquilha

## Observação sobre o mural

O salvamento compartilhado do mural usa o armazenamento dos artefatos do Claude (`window.claude.use("db")`).
Fora do Claude, por exemplo no GitHub Pages, o mural funciona, mas cada pessoa vê só o próprio avatar, salvo no aparelho.
Para um mural compartilhado fora do Claude, é preciso trocar esse trecho por outro banco de dados.
