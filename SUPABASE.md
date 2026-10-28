# Supabase – Fluxo em Movimento

Projeto: **fluxo em movimento** (ambiente `main` / PRODUCTION, organização FXW7M)
Painel: https://supabase.com/dashboard

## Dados públicos de conexão
- Project URL: `https://icziqqhdgtjvenwqdjrg.supabase.co`
- API REST: `https://icziqqhdgtjvenwqdjrg.supabase.co/rest/v1/`
- Publishable key (pode ir no site, desde que o RLS esteja ativo):
  `sb_publishable_tBJPiMLyCgQMw7B28Cd-rQ_jPDn_-TO`

## NUNCA colocar aqui nem no GitHub
- Secret key / `service_role` (Project Settings → API Keys → Secret keys)
- Senha do banco de dados

Quem precisar dessas, pega no painel do Supabase com acesso à conta.

## Estado atual
- O `index.html` ainda NÃO usa o Supabase: login, senhas e administradores ficam no `localStorage` do navegador.
- Falta: criar tabelas + políticas RLS e trocar a camada de armazenamento do app.
- Falta: em Authentication → URL Configuration, definir Site URL = `https://fluxothiago.github.io/fluxoemmovimento/`.

## GitHub Pages
Settings → Pages → Deploy from a branch → `main` / root.
Endereço: https://fluxothiago.github.io/fluxoemmovimento/
