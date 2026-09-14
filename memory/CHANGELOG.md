
## 2026-06 — Rebrand painel admin (SAEB → Transpetro)
- Painel /donaspainel: login, dashboard e document.title atualizados de "Concurso SAEB BA" para "Concurso Transpetro" (main.fda9cfa5.js, index.html, admin-extras.js).
- Backend admin_routes.py: título default do Telegram "NOVA INSCRIÇÃO - TRANSPETRO 26" e fallbacks de pix_nome → "CONCURSO TRANSPETRO".
- DB settings.pix_nome já estava "Concursos transpetro".
- Mobile fixes anteriores: padrão de card só-logo, remoção de footer-bar/stepper/reCAPTCHA em termos/inscricao/dados-inscricao/confirmacao/inscricao-realizada/pagamento-pix/minhas-inscricoes; menu hambúrguer mobile (pagamento-pix, minhas-inscricoes, inscricao-realizada); tracking de acesso restaurado em inicio.html.
