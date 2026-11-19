# 🇧🇷 Coisas Brasileiras

> **100% MADE IN BRASIL – Alto em malandragem**

Site sobre coisas brasileiras criado como projeto universitário (Positivo). A ideia é combater o "complexo de vira-lata": valorizar o que é nosso, com bom humor, ilustrações autorais e um pouco de interatividade.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.8-7952B3?logo=bootstrap&logoColor=white)

---

## 👥 Autores

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Cadaverblah">
        <img src="https://github.com/Cadaverblah.png" width="100" alt="Foto de perfil de Cadaverblah"><br>
        <b>Gabriel Rezenede</b><br>@Cadaverblah
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/eduardocavalli85">
        <img src="https://github.com/eduardocavalli85.png" width="100" alt="Foto de perfil de eduardocavalli85"><br>
        <b>Eduardo Cavallo</b><br>@eduardocavalli85
      </a>
    </td>
  </tr>
</table>

| Integrante | GitHub | Responsabilidades |
|---|---|---|
| **Gabriel Rezenede** | [@Cadaverblah](https://github.com/Cadaverblah) | Ilustrações originais, JavaScript, vídeos e músicas, testes |
| **Eduardo Cavallo** | [@eduardocavalli85](https://github.com/eduardocavalli85) | Estrutura HTML e estilo (CSS) |

## 📌 Sobre o projeto

O site reúne personagens, objetos, invenções e produtos que fazem parte da identidade do Brasil, cada um em uma página curta e ilustrada. Tudo é responsivo, então funciona no computador e no celular.

**Objetivos**

- Valorizar a cultura brasileira de áreas diferentes (história, ciência, design, música, cultura pop, gastronomia e arte).
- Praticar HTML, CSS e JavaScript com layout responsivo.
- Ter interatividade de verdade: enquete, formulário, players de vídeo e áudio, carrossel e modal de aviso de saída.
- Criar uma identidade visual própria, inspirada nas cores do Brasil.

## 🗺️ Páginas

| Página | Arquivo | O que tem |
|---|---|---|
| Home | `index.html` | Apresentação do tema e do "complexo de vira-lata" |
| Almirante Negro | `almirantenegro.html` | João Cândido e a Revolta da Chibata |
| Ozob | `ozob.html` | O palhaço cyberpunk do NerdCast e de Cyberpunk 2077 |
| Caramelo | `caramelo.html` | O vira-lata caramelo e uma **enquete** com `localStorage` |
| Música | `musicabr.html` | **Player de vídeo** com playlist e links do Spotify com **modal** de saída |
| Orelhão | `orelhao.html` | História do orelhão e **player de áudio** com controles (seção "Teste de idade") |
| 51 | `51.html` | Cachaça 51, origem da caipirinha e tabela de receitas |
| Soro antiofídico | `soro.html` | Vital Brazil e o Instituto Butantan |
| Buzsheep | `buzsheep.html` | Artista brasileiro e tabela de obras não originais (inclui artes do Ozob) |
| Quem somos | `quemsomoos.html` | Autores, **carrossel** de artes e **formulário** de contato |

## ✨ Funcionalidades em JavaScript

Todo o código está em [`js/script.js`](js/script.js), dividido em blocos que só rodam quando os elementos existem na página.

- **Enquete do Caramelo:** salva respostas SIM/NÃO com data no `localStorage`, valida a entrada, lista, remove, limpa e mostra o total.
- **Formulário de contato:** valida, guarda as mensagens no `localStorage` e preenche nome e e-mail do último envio.
- **Player de vídeo:** playlist com anterior, play/pause, próximo, volume − e +, e passagem automática para o próximo vídeo.
- **Player de áudio (Orelhão):** play/pause, voltar ao início, volume, mudo, repetir, barra de progresso arrastável e tempo.
- **Modal de saída:** avisa antes de abrir links externos (Spotify), usando o modal do Bootstrap.
- **Componentes do Bootstrap:** carrossel e dropdown.
- **Menu hambúrguer:** feito só com CSS (checkbox + `label`), sem JavaScript.

## 🎨 Design

**Paleta de cores** (inspirada na bandeira do Brasil)

| Cor | Código | Uso |
|---|---|---|
| Azul | `#3434d6` | Menu, títulos, bordas e botões |
| Azul escuro | `#1f1fb1` | Hover |
| Verde | `#528321` | Fundo da página |
| Lima | `#b0dd0b` | Retângulo central |
| Creme | `#f3fbc4` | Blocos de texto |
| Tinta | `#1c2a08` | Texto principal |

O texto principal (`#1c2a08`) sobre o creme tem contraste de **14 : 1** (WCAG AAA).

**Tipografia**

- **[Oi](https://fonts.google.com/specimen/Oi)** nos títulos.
- **[Gabriela](https://fonts.google.com/specimen/Gabriela)** no texto corrido.
- Ambas são livres ([SIL Open Font License](https://openfontlicense.org)) e ficam em `fonts/`.

**Layouts**

1. Ilustração, texto e ilustração (Home, Almirante Negro, Orelhão).
2. Grade 2 × 2 com bloco largo (Caramelo, Música, Quem somos).
3. Coluna única centralizada (51, Ozob, Soro, Buzsheep).

**Responsividade:** acima de 1200 px há mais espaçamento; até 800 px o menu vira hambúrguer e as colunas empilham.

## 📁 Estrutura do projeto

```
.
├── index.html
├── almirantenegro.html
├── ozob.html
├── caramelo.html
├── musicabr.html
├── orelhao.html
├── 51.html
├── soro.html
├── buzsheep.html
├── quemsomoos.html
├── css/
│   └── stylesheet.css
├── js/
│   └── script.js
├── img/        # ilustrações e fotos
├── audio/      # áudio do orelhão
├── video/      # vídeos da página Música (comprimidos, 720p)
├── fonts/      # Oi e Gabriela (+ OFL.txt)
└── doc/        # documentação do projeto (PDF)
```

## ▶️ Como rodar

Não precisa instalar nada.

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
   ```
2. Abra o arquivo `index.html` no navegador.
   - Dica: no VS Code, a extensão **Live Server** recarrega a página sozinha.

> O Bootstrap é carregado por CDN (jsDelivr), então é preciso estar conectado à internet nas páginas **Música** e **Quem somos**.

## 🌐 Publicando no GitHub Pages

1. Deixe os arquivos do site na **raiz** do repositório (o `index.html` precisa ficar na raiz, e não dentro de uma subpasta).
2. Em **Settings → Pages**, escolha **Deploy from a branch**, a branch `main` e a pasta `/ (root)`.
3. O site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## 🎞️ Sobre os vídeos

Os vídeos da pasta `video/` foram comprimidos para caber no GitHub (limite de 100 MB por arquivo): H.264 em 720p, com áudio AAC.

| Arquivo | Antes | Depois |
|---|---|---|
| `capacete_fascista.mp4` | 15,7 MB (1080 × 1080) | 4,9 MB (720 × 720) |
| `vilao_pra_quem.mp4` | 102,1 MB (1920 × 1080) | 37,7 MB (1280 × 720) |

## ⚠️ Atenção antes de subir

- **Maiúsculas e minúsculas:** o GitHub Pages diferencia `CARAMELO.png` de `caramelo.png`. O carrossel de *Quem somos* usa `img/caramelo.png`; ajuste o nome do arquivo ou o caminho no HTML para os dois serem iguais.
- **Nomes com acento e espaço:** arquivos como `orelhão.jpg` e `Almirante negro.png` funcionam, mas podem se corromper ao compactar o projeto. Se possível, prefira nomes sem acento e sem espaço.

## 🐞 Problemas conhecidos

- O formulário de *Quem somos* precisa de um elemento com `id="retorno-form"` para mostrar a mensagem de confirmação, e esse elemento ainda não existe no HTML.
- A playlist do player de vídeo cita `Fantástico_Mundo_Feio.mp4`, que não está na pasta `video`.
- A tabela de receitas da página **51** passa da largura da tela em celulares muito estreitos.

## 🛠️ Ferramentas

Visual Studio Code · Firefox · Clip Studio Paint · [Bootstrap](https://getbootstrap.com/) · [jsDelivr](https://www.jsdelivr.com/) · [Google Fonts](https://fonts.google.com/) · [MDN Web Docs](https://developer.mozilla.org/pt-BR/) · [FFmpeg](https://ffmpeg.org/) (compressão dos vídeos) · [Claude](https://claude.ai/) (apoio em textos, ajustes e documentação)

## 📚 Documentação e fontes do conteúdo

- [Documentação completa do projeto (PDF)](doc/Documenta%C3%A7%C3%A3o%20do%20Projeto%20%E2%80%93%20Coisas%20Brasileiras.pdf)
- [Cachaça 51](https://pt.wikipedia.org/wiki/Cacha%C3%A7a_51) e [Caipirinha](https://pt.wikipedia.org/wiki/Caipirinha) (Wikipédia)
- [João Cândido Felisberto](https://pt.wikipedia.org/wiki/Jo%C3%A3o_C%C3%A2ndido_Felisberto) e [Revolta da Chibata](https://pt.wikipedia.org/wiki/Revolta_da_Chibata) (Wikipédia)
- [Ozob em Cyberpunk 2077](https://www.legiaodosherois.com.br/2020/cyberpunk-2077-personagem-brasileiro-azaghal.html) (Legião dos Heróis)
- [Orelhão](https://pt.wikipedia.org/wiki/Orelh%C3%A3o) (Wikipédia) e [50 anos do orelhão](https://www.designboom.com/design/50-years-orelhao-brazil-iconic-egg-shaped-telephone-booth-chu-ming-silveira-06-06-2021/) (Designboom)
- [Instituto Butantan](https://butantan.gov.br/)
- [Buzsheep no Instagram](https://www.instagram.com/buzsheep/)

## 📄 Licença e créditos

Projeto universitário, desenvolvido na Positivo. © 2026 Gabriel Rezenede e Eduardo Cavallo.

- Algumas artes são originais dos autores; as demais pertencem aos seus respectivos criadores.
- As fontes Oi e Gabriela são distribuídas sob a [SIL Open Font License 1.1](https://openfontlicense.org).
- O áudio do orelhão foi gerado de forma sintética para este projeto.


