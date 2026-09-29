Gerei o pacote completo de recursos de implantação web (**Web Deployment Assets**) para a **Assistência Segura** com base na tela interativa selecionada:

### 📦 Recursos Criados:

1. **Favicon / PWA Icon (1:1)**:
   - Arte *full-bleed* em gradiente contínuo azul corporativo (`#1c4d8b` a `#14355a`) com o monograma "A" da marca em branco puro de alta nitidez, perfeito para abas de navegadores e resoluções padrão (16×16, 32×32, 192×192, 512×512 px).

2. **Apple Touch Icon (1:1)**:
   - Ícone dedicado para atalhos no iOS (Safari / Home Screen), preenchendo 100% da área útil sem molduras simuladas ou recortes, com acabamento refinado e excelente contraste.

3. **Web App Manifest (`manifest.json`)**:
   - Arquivo de manifesto PWA com os metadados oficiais (`Assistência Segura - 24 Horas`), rotas de início, cores de tema (`theme_color: #1c4d8b`, `background_color: #f6f9ff`), modo `standalone` e declaração de ícones responsivos e `maskable`.

---

### 📋 Como incluir no `<head>` do seu HTML:

```html
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="manifest" href="/manifest.json">
<meta name="theme-color" content="#1c4d8b">
```