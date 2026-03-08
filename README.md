# ⚡ ImageConvert Pro

> App web client-side para remover fundo de imagens, vetorizar e exportar SVG e ICO multi-size.

## 🚀 Como usar

1. Abra o `index.html` no navegador (ou acesse via GitHub Pages)
2. Carregue uma imagem (PNG, JPG, WebP, GIF, BMP, SVG)
3. Configure as opções de remoção de fundo e vetorização
4. Clique em **⚡ Processar**
5. Baixe o resultado em **SVG**, **PNG** ou **ICO**

## ✨ Funcionalidades

### ✂️ Remoção de Fundo
- **Flood Fill** – remove fundo a partir das bordas (cor sólida)
- **Fuzzy Select** – detecta a cor dominante automaticamente
- **Branco/Claro** – remove fundos brancos/claros
- **Escuro/Preto** – remove fundos escuros
- **Cor personalizada** – picker de cor livre
- Controle de **tolerância** (5–120)
- **Anti-aliasing** e **Fill Holes** opcionais

### 🔷 Vetorização SVG
- **Traçado de contorno** – resultado limpo com transparência
- **Blocos de cor** – estilo pixel-art vetorizado
- **Embutir PNG no SVG** – encapsulamento lossless
- Escala de saída: 256×256, 512×512, 1024×1024

### 💾 Exportação
- **PNG** com fundo transparente
- **SVG** vetorizado
- **ICO multi-size** com 6 tamanhos embutidos: 16, 32, 48, 64, 128, 256 px

## 🛠️ Tecnologias

- HTML5 Canvas API
- JavaScript puro (zero dependências)
- 100% client-side (sem servidor, sem upload para nuvem)

## 📁 Estrutura

```
imageconvert-pro/
└── index.html   ← app completo em arquivo único
```

## 📄 Licença

MIT
