# Site AltaVendas — O Jornal da Venda Perdida

Site institucional do [AltaVendas](https://app.upvendas.app.br) — o PDV que
enxerga a venda que você está perdendo.

- **Stack:** HTML único e estático (`index.html`), GSAP 3.13 + ScrollTrigger +
  SplitText + Lenis via CDN, Google Fonts (Barlow / Barlow Condensed).
- **Funil:** todos os CTAs apontam pro app em produção —
  `/demo` (demonstração 1-clique), `/cadastro?plano=...` (14 dias grátis)
  e `/login`.
- **Deploy:** Vercel (projeto estático, zero build). Importar este repo em
  vercel.com/new e publicar — não precisa de configuração.

> O desenvolvimento do site acontece junto do app (repo `sistemaaltavendas`,
> arquivo `public/site.html`, servido em dev na rota `/site.html`). Este repo
> recebe a versão de produção com links absolutos.
