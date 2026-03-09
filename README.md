# Deploy no WordPress

## Opção A — Página com HTML Custom
1. Criar página no WP → Template: "Blank" / "Canvas" / "Elementor Canvas"
2. Adicionar bloco "HTML Personalizado"
3. Colar o conteúdo de `index.html`
4. CSS: Customizer > CSS Adicional (ou plugin "Simple Custom CSS")
5. JS: Plugin "Insert Headers and Footers" → Footer Scripts

## Opção B — Página estática (recomendado)
1. Upload de `index.html` e pasta `assets/` via FTP para `/wp-content/landing/santin-roveda/`
2. Acessar via `seudominio.com/wp-content/landing/santin-roveda/`
3. Ou usar plugin "My Custom Functions" para criar redirect

## Checklist pós-deploy
- [ ] Substituir todos os `<!-- PREENCHER -->` por conteúdo real
- [ ] Upload das fotos reais na Biblioteca de Mídia
- [ ] Preencher número do WhatsApp no CTA
- [ ] Testar WhatsApp link no celular
- [ ] Verificar OG tags (usar https://developers.facebook.com/tools/debug/)
- [ ] Adicionar Google Analytics / Tag Manager
- [ ] Validar compliance TSE com assessoria jurídica
- [ ] Testar responsivo em 3+ dispositivos
- [ ] Preencher CNPJ e responsável no footer
