# Desafio - Formação HTML Web Developer.
# Desafio de Projeto DIO: Criando uma Página Básica com HTML.

Este repositório contém o código-fonte de um website básico desenvolvido como parte do Desafio de Projeto da **DIO (Digital Innovation One)**. O objetivo principal é praticar e consolidar o uso das tags fundamentais do HTML aprendidas durante as aulas práticas.

---

## 🎯 Sobre o Desafio.

Foi elaborar um website estruturado de forma simples, funcionando como um mini blog/tutorial educativo. Foram aplicadas tanto as tags essenciais explicadas em aula quanto novas tags pesquisadas para expandir o conhecimento, reforçando que esses conceitos serão a base para todo o curso de desenvolvimento web.

---

## 🛠️ Tags Utilizadas no Projeto.

### 1. Tags Aprendidas em Aula.
* **Cabeçalhos:** `<h1>` até `<h6>` (estruturação hierárquica do texto).
* **Parágrafos e Linhas:** `<p>`, `<hr>`.
* **Formatação e Ênfase:** `<strong>`, `<i>`, `<u>`, `<mark>`, `<small>`.
* **Notações Científicas/Matemáticas:** `<sub>` (subscrito), `<sup>` (sobrescrito).
* **Citações:** `<blockquote>`.
* **Listas:** `<ol>` (ordenada), `<ul>` (não ordenada), `<li>` (itens de lista).
* **Navegação (Âncoras):** `<a>` (links externos e internos para navegação na mesma página).

### 2. Novas Tags Pesquisadas e Aplicadas.
* `<abbr>`: Usada para definir abreviações com descrições.
* `<del>`: Usada para indicar texto excluído/removido (riscado).
* `<font>`: Utilizada para customização visual básica.

---

## 📂 Estrutura dos Assuntos na Página.

A página foi dividida em três seções principais em formato de tutorial:
1. **Como Surgiu O HTML:** Breve histórico sobre a criação da linguagem por Tim Berners-Lee.
2. **O Que São Tags:** Explicação de como os elementos estruturam e formatam o conteúdo no navegador.
3. **O Que São Links:** Demonstração da importância dos `hiperlinks` e `âncoras` para a navegação web.

Cada seção conta com recursos de navegação interna (rolagem suave via âncoras com suporte da tag `<small>`) para retornar facilmente ao topo da página.

---

## 🔗 Referências e Rodapé.
No rodapé da página, foram incluídos links de referência reais para aprofundamento nos estudos:
* [MDN Web Docs - Guia de HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
* [W3C - World Wide Web Consortium](https://www.w3.org/)

---
## 💻 Código Fonte (`index.html`)

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Matéria em um Blog - Desafio DIO</title>
    <style>
        html {
            scroll-behavior: smooth;
        }
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
    </style>
</head>
<body>

    <h1 id="topo">Guia Básico de Desenvolvimento Web</h1>
    <p>Bem-vindo ao nosso tutorial básico sobre a estrutura da web! Aqui você aprenderá os fundamentos básicos do HTML.</p>
    
    <hr>

    <h2>Índice de Assuntos</h2>
    <ul>
        <li><a href="#surgimento">1. Como Surgiu o HTML</a></li>
        <li><a href="#tags">2. O que são Tags</a></li>
        <li><a href="#links">3. O que são Links</a></li>
    </ul>

    <hr>

    <h2 id="surgimento">1. Como Surgiu o HTML</h2>
    <p>O HTML foi criado por Tim Berners-Lee na década de 1990. A ideia original era permitir que cientistas compartilhassem documentos de forma simples e organizada.</p>
    
    <p>Naquela época, a web era muito simples. <del>Não existiam layouts complexos</del> nem estilos avançados como vemos hoje. O objetivo era apenas estruturar o conhecimento usando o padrão <abbr title="HyperText Markup Language">HTML</abbr>.</p>
    
    <blockquote>
        "A força da Web está na sua universalidade. O acesso de todos, independentemente da deficiência, é um aspecto essencial." — Tim Berners-Lee
    </blockquote>

    <p><small><a href="#topo">Voltar ao topo</a></small></p>

    <hr>

    <h2 id="tags">2. O que são Tags</h2>
    <p>As tags são os elementos fundamentais do HTML. Elas servem para indicar ao navegador como o conteúdo deve ser exibido na tela.</p>

    <h3>Estrutura das Tags</h3>
    <p>A maioria das tags possui abertura e fechamento, como a tag de parágrafo <code>&lt;p&gt;</code>. Veja alguns recursos de formatação de texto:</p>

    <ul>
        <li><strong>Texto em negrito com strong</strong> para destacar pontos importantes.</li>
        <li><i>Texto em itálico</i> para termos em outros idiomas ou <u>texto sublinhado</u> para dar ênfase visual.</li>
        <li>Podemos usar a tag <mark>mark para destacar uma palavra</mark> importante no meio da frase.</li>
        <li>Podemos incluir notações científicas como H<sub>2</sub>O (usando <sub>sub</sub>) ou fórmulas como X<sup>2</sup> (usando <sup>sup</sup>).</li>
        <li>Também existe a tag <font color="blue">font com cor estilizada</font> para alterar visualmente um elemento.</li>
    </ul>

    <p><small><a href="#topo">Voltar ao topo</a></small></p>

    <hr>

    <h2 id="links">3. O que são Links</h2>
    <p>Os links (ou hiperlinks) são a base da navegação na Web. Eles conectam diferentes páginas entre si ou diferentes partes de uma mesma página através de âncoras.</p>

    <h3>Tipos de Links</h3>
    <ol>
        <li><strong>Links Internos (Âncoras):</strong> Usados para navegar na própria página (como os botões de voltar ao topo).</li>
        <li><strong>Links Externos:</strong> Apontam para outros websites na internet.</li>
    </ol>

    <h4>Resumo Rápido</h4>
    <h5>Importante lembrar:</h5>
    <h6>Sem links, a web não seria uma rede interconectada!</h6>

    <p><small><a href="#topo">Voltar ao topo</a></small></p>

    <hr>

    <footer>
        <h2>Referências e Materiais de Estudo</h2>
        <p>Abaixo estão alguns links úteis para aprofundar seus conhecimentos:</p>
        <ul>
            <li><a href="[https://developer.mozilla.org/pt-BR/docs/Web/HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)" target="_blank">MDN Web Docs - Guia de HTML</a></li>
            <li><a href="[https://www.w3.org/](https://www.w3.org/)" target="_blank">W3C - World Wide Web Consortium</a></li>
            <li><a href="[https://www.youtube.com/results?search_query=curso+html5+para+iniciantes](https://www.youtube.com/results?search_query=curso+html5+para+iniciantes)" target="_blank">Pesquisar Vídeos de HTML no YouTube</a></li>
        </ul>
        <p><small>&copy; 2026 Higor deCAmpos - Projeto do Desafio DIO: Formação HTML Web Developer</small></p>
    </footer>

</body>
</html>
