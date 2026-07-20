# Clínica Saúde Integral — Site Pilates Clínico

Site estático de página única (SPA simples, sem build), pronto para publicar no **GitHub Pages**.

## Estrutura
```
index.html      → página única com todas as seções
styles.css      → estilos (tokens de cor/tipografia no topo do arquivo)
script.js       → animações de rolagem (scroll reveal) e rodapé
assets/         → fotos recortadas do material da clínica
```

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex: `clinica-saude-integral`).
2. Envie todos os arquivos desta pasta (`index.html`, `styles.css`, `script.js`, `assets/`) para a raiz do repositório.
3. No GitHub, vá em **Settings → Pages**.
4. Em **Source**, selecione a branch `main` e a pasta `/ (root)`.
5. Salve. Em alguns minutos o site estará disponível em:
   `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

Nenhuma etapa de build é necessária — é HTML/CSS/JS puro.

## Personalizações rápidas

- **Número do WhatsApp**: procure por `5538997449175` em `index.html` (aparece no botão do menu, no herói, no contato e no botão flutuante) e substitua se precisar.
- **Cores**: edite as variáveis no topo de `styles.css` (bloco `:root`).
- **Textos**: todo o conteúdo (benefícios, planos, indicações, etc.) está em texto simples dentro de `index.html`, fácil de editar.
- **Fotos**: substitua os arquivos em `assets/` mantendo os mesmos nomes, ou atualize os caminhos `src` no HTML.
