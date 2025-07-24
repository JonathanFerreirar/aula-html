0. Como se criar um arquivo HTML e o que é um arquivo HTML?

1. Estrutura básica de um documento HTML
   html
   Copy
   Edit
   <!DOCTYPE html>
   <html lang="pt-BR">
     <head>
       <meta charset="UTF-8" />
       <title>Título da Página</title>
     </head>
     <body>
     
     <header>
     </header>
     <main>
       <!-- Conteúdo da página -->
       <main>
     </body>
   </html>

2. Principais tags HTML e suas funções

| Tag                                           | Uso principal                           |
| --------------------------------------------- | --------------------------------------- |
| `<h1>` a `<h6>`                               | Títulos em ordem hierárquica            |
| `<p>`                                         | Parágrafos                              |
| `<a>`                                         | Links                                   |
| `<img>`                                       | Imagens                                 |
| `<ul>`, `<ol>`, `<li>`                        | Listas não ordenadas, ordenadas e itens |
| `<div>`                                       | Contêiner genérico                      |
| `<span>`                                      | Contêiner em linha                      |
| `<strong>`, `<em>`                            | Ênfase e importância semântica          |
| `<input>`, `<textarea>`, `<form>`, `<button>` | Formulários                             |

//NÃO ORDENADA

<ul>
<li>Maçã</li>
<li>Banana</li>
<li>Laranja</li>
</ul>

//ORDENADA

<ol>
<li>Passo 1</li>
<li>Passo 2</li>
<li>Passo 3</li>
</ol>

3. Semântica e acessibilidade
   Utilizar tags semânticas melhora SEO, acessibilidade e manutenibilidade:

<header>, <main>, <footer>, <section>, <article>, <nav>, <aside>

Ajuda leitores de tela e mecanismos de busca a entender o conteúdo.

4. Atributos importantes
   class, id → Para estilização e JS

href (em <a>) → Define o destino do link

src, alt (em <img>) → Imagem e descrição alternativa

type, value, placeholder, required (em <input>)

5. Boas práticas
   Indentação clara

Fechar todas as tags

Usar alt nas imagens

Evitar excesso de <div>s (divitis)

. Formulários
Entender como capturar dados do usuário:

<form>, <label>, <input>, <textarea>, <select>, <option>

Validações com required, min, max, pattern

##DESAFIO

Desafio Completo de HTML — Página de Produto
🛒 Loja fictícia: TechNova Store
Uma loja de tecnologia especializada em eletrônicos modernos, como fones, teclados, mouses, e gadgets.

🎯 Objetivo
Criar uma página de produto realista para um teclado mecânico gamer. A ideia é montar a estrutura de uma página comum em e-commerces, contendo:

OK - HEADER COM (logo, logar e cadastre-se)

OK - Nome e descrição do produto

Imagem ilustrativa

Informações técnicas (especificações)

Preço e botão de compra

Link para voltar à loja

Formulário simples de "Avise-me quando chegar"
