# CP1-Front-Vinharia-agnello
Vinharia Agnello

Projeto de site institucional desenvolvido com HTML e CSS, com o objetivo de apresentar uma vinheria fictícia, seus produtos, história e formas de contato.

⸻

📌 Sobre o projeto

A Vinharia Agnello é um site que simula uma empresa do ramo de vinhos, trazendo uma experiência visual agradável e organizada para o usuário.

O projeto foi desenvolvido como atividade acadêmica, com foco em:
	•	Estruturação HTML semântica
	•	Estilização com CSS
	•	Organização de arquivos
	•	Publicação no GitHub Pages

⸻

🚀 Tecnologias utilizadas
	•	HTML5
	•	CSS3
	•	Git e GitHub

  #Integrantes
  Kauã - RM:569473
  Murilo - RM:573517
  Isadora - RM:569585
  Enrico - RM:562384

_______

Git Hub Pages: https://mirandakauan2007-hue.github.io/CP1-Front-Vinharia-agnello/

## ✨ Efeitos Visuais — Check-Point 02

### 🎯 Pseudo-classes aplicadas

| Pseudo-classe | Onde foi usada | Efeito |
|---|---|---|
| `:hover` | Links do menu e botões | Muda cor de fundo e texto ao passar o mouse |
| `:focus` | Inputs e textarea do formulário | Borda dourada ao clicar no campo |
| `:nth-child(odd)` | Linhas da tabela de produtos e listas | Fundo alternado nos itens ímpares |

---

### 🎨 Pseudo-elementos aplicados

| Pseudo-elemento | Onde foi usado | Efeito |
|---|---|---|
| `::before` | Títulos com classe `.secao-titulo` | Traço dourado decorativo acima do título |
| `::after` | Logo com classe `.logo` | Ícone 🍷 decorativo ao lado do nome |
| `::first-letter` | Parágrafos com classe `.paragrafo-destaque` | Inicial grande e estilizada na cor vinho |
| `::selection` | Todo o site | Texto selecionado fica com fundo dourado |

---

### 💫 Animações com @keyframes

| Animação | Onde foi aplicada | Efeito |
|---|---|---|
| `entradaHero` | Seção `.hero-content` do index | Conteúdo sobe com fade ao carregar a página |

---

### 🔄 Transições suaves

| Elemento | Propriedades animadas |
|---|---|
| Links do menu | `color`, `background` |
| Botões `.btn` | `background`, `transform` |
| Cards `.card-vinho` | `transform`, `box-shadow` |
| Inputs e textarea | `border`, `box-shadow` |

---

### 🎢 Transformações CSS

| Transformação | Onde foi aplicada | Efeito |
|---|---|---|
| `translateY(-6px)` | Cards `.card-vinho` no hover | Card flutua para cima |
| `translateY(-3px)` | Botões `.btn` no hover | Botão sobe levemente |
| `scale(1.05)` | Imagens `.card-vinho img` no hover | Imagem cresce suavemente |
| `rotate(-10deg)` | Imagens `.icone-vinho` no hover | Imagem inclina ao passar o mouse |

---

### 📁 Arquivo criado

- `src/css/efeitos.css` — contém todos os efeitos visuais separados do estilo principal
- Importado em todas as páginas via `<link rel="stylesheet" href="../css/efeitos.css">`
