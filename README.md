# Zup Labs Insights - Template 

Este template foi criado para facilitar a criação e edição do Zup Labs Insights. Aqui estão as instruções para personalizá-lo e usá-lo.

## Editando o Conteúdo

### 1. Cabeçalho
- **Número da Edição**: Altere o número na `<div class="edition-number">`

### 2. Introdução
- Edite o texto na seção `<section class="introduction">`

### 3. Resumos dos Temas
Na seção "Nesta Edição", adicione ou edite os resumos:
```html
<div class="summary-item">
    <h3 class="summary-title">Seu Título Aqui</h3>
    <span class="tag tag-CATEGORIA">CATEGORIA</span>
</div>
```

### 4. Artigos Principais
Para cada artigo, use esta estrutura:
```html
<article class="content-article">
    <div class="article-header">
        <h2 class="article-title">Título do Artigo</h2>
        <span class="tag tag-CATEGORIA">CATEGORIA</span>
    </div>
    <div class="article-content">
        <p>Seu conteúdo aqui...</p>
        <p>Mais parágrafos...</p>
        <!-- Você pode adicionar listas, código, imagens, etc. -->
    </div>
</article>
```

## Como Usar

1. **Para cada nova edição:**
   - Duplique o arquivo `index.html`
   - Renomeie para `edicao-02.html`, `edicao-03.html`, etc.
   - Atualize o número da edição
   - Substitua o conteúdo dos artigos

2. **Para visualizar:**
   - Abra o arquivo HTML em qualquer navegador
   - Ou use a extensão Live Server no VS Code

3. **Para publicar:**
   - Faça upload dos arquivos HTML, CSS e logo para seu servidor
   - Ou use GitHub Pages, Netlify, Vercel, etc.

## 📧 Elementos Adicionais Suportados

O CSS inclui estilos para:
- **Listas** (numeradas e com marcadores)
- **Links** (com hover effect)
- **Código** (`<code>` e `<pre>`)
- **Citações** (você pode adicionar `<blockquote>`)
- **Imagens** (responsivas por padrão)

