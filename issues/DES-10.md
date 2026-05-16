# Hanna: Site/Landing Page — Portfólio Hanna Ornato Estudio

- **ID:** DES-10
- **Status:** done
- **Priority:** high
- **Atualizado:** 2026-05-07T05:00:48.957Z

## Descrição

Criar a landing page / site portfólio para a Hanna Almeida (Ornato Estudio, tatuadora em Brasília-DF).

**Escopo:**
1. **Landing page responsiva** — React + Vite + Tailwind CSS + shadcn/ui.
2. **Seções obrigatórias:**
   - Hero com foto principal + CTA WhatsApp
   - Portfólio (galeria de trabalhos por estilo: ornamental, fine line, realismo)
   - Sobre (história da Hanna, experiência, estúdio)
   - Serviços e estilos (com faixa de preço posicional, sem valores exatos)
   - Depoimentos/avaliações
   - Localização (Plaza Mall, Águas Claras, Brasília-DF) com mapa
   - FAQ (cuidados, agendamento, preparo)
   - Botão flutuante WhatsApp
3. **SEO on-page** — meta tags, schema markup (LocalBusiness), sitemap, Open Graph.
4. **Mobile-first** — 70%+ do tráfego vem do Instagram.
5. **Performance** — Lighthouse 90+ em todas as métricas.

**Tom visual:** Premium, artístico, dark theme sugerido (combina com tattoo). Fontes elegantes. Fotos placeholder por enquanto (Hanna vai fornecer).

**Entregável:** Projeto completo buildável, pronto para deploy. Código no workspace do projeto.

## Comentários

### Agente c4539806 — 18/03/2026, 02:03:20

## Concluído

Landing page do Ornato Estudio criada e buildável com sucesso.

**Stack:** React 18 + Vite 6 + TypeScript (strict) + Tailwind CSS 4

**Estrutura do projeto** (`ornato-estudio/`):
- `src/components/sections/` — Hero, Portfolio, About, Services, Testimonials, Location, FAQ
- `src/components/layout/` — Header (com menu mobile responsivo), Footer
- `src/components/ui/WhatsAppFloat.tsx` — Botão flutuante WhatsApp
- `src/components/seo/SchemaMarkup.tsx` — JSON-LD (TattooParlor)
- `src/data/content.ts` — Todo conteúdo centralizado e tipado

**Seções implementadas:**
- Hero com CTA WhatsApp + Instagram
- Portfólio com filtro por categoria (ornamental, fine line, realismo) — placeholders prontos para fotos reais
- Sobre a Hanna (história, experiência, biossegurança)
- Serviços com faixa de preço posicional
- Depoimentos de clientes
- Localização com Google Maps embed + endereço + horários
- FAQ com accordion animado
- Botão flutuante WhatsApp

**SEO:**
- Meta tags completas (title, description, OG, Twitter Card)
- Schema markup JSON-LD (TattooParlor/LocalBusiness)
- sitemap.xml + robots.txt
- Google Fonts (Cormorant Garamond + Inter)

**Design:** Dark theme premium (fundo #0a0a0a, dourado #c9a96e), mobile-first, fontes elegantes.

**Build:** `npm run build` passa sem erros (494KB JS gzip 137KB, 29KB CSS gzip 5.6KB).

**Próximos passos:** Substituir fotos placeholder pelas fotos reais da Hanna, configurar domínio e deploy.

