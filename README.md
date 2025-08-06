> ⚠️ **Importante:** Este arquivo, `README.md` não deve ser enviado para o S3. Ele serve apenas como guia interno para edição.

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
        <!-- Você pode adicionar listas, código, imagens, etc -->
    </div>
</article>
```

## Como Usar

1. **Para cada nova edição:**
   - Duplique a pasta do projeto (que contém o `index.html`, `styles.css` e a pasta `assets`)
   - **Renomeie a pasta** para `edicao-12`, `edicao-13`, etc
   - Dentro dessa pasta, **mantenha o arquivo HTML principal sempre com o nome `index.html`**
   - Atualize o número da edição dentro do HTML (no cabeçalho)
   - Substitua o conteúdo dos artigos conforme o modelo

2. **Para visualizar:**
   - Abra o arquivo HTML em qualquer navegador ou use a extensão Live Server no VS Code

3. **Para publicar:**
   - Faça upload dos arquivos HTML, CSS e da pasta de imagens para seu servidor
   - Ou use GitHub Pages, Netlify, Vercel, etc.

## Como editar e enviar a edição para o S3
Quando o layout e o conteúdo estiverem prontos, siga um dos métodos abaixo para enviar ao colega responsável pelo upload no Amazon S3 (Vinícius Vincéllis).

> **Importante:** Este arquivo, `README.md` não deve ser enviado para o S3. Ele serve apenas como guia interno para edição.

### **Método 1 — Enviando como arquivo ZIP**
1. Garanta que a pasta do projeto contenha:
- `index.html` 
- Arquivo(s) `.css`
- Pasta com imagens utilizadas (`/assets` ou equivalente)

2. Clique com o botão direito na pasta do projeto e selecione "**Enviar para** > **Pasta compactada (ZIP)**".
- Nomeie o arquivo, por exemplo: `zuplabs-insights-edicao-012.zip`.
- Envie o ZIP por e-mail, Google Drive ou outro meio acordado.
- O colega de marketing irá descompactar e fazer o upload para o S3.

### **Método 2 — Compartilhando via GitHub**
1. Confirme que o repositório está atualizado com a edição final

2. Avise o colega para:
    - Baixar o repositório como ZIP (botão verde "**Code**" > "**Download ZIP**"), ou
    - Clonar via Git (`git clone`)

3. Ele fará o upload dos arquivos no S3 a partir do conteúdo baixado

### **Organização recomendada no S3**
- O HTML principal deve se chamar `index.html`
- As imagens e CSS devem manter a mesma estrutura da pasta original

