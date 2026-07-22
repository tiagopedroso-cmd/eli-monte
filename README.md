# Estética Eli Monte

Landing page da **Estética Eli Monte** — clínica especializada em Criolipólise, Depilação a Laser e Pós-operatório, localizada em Itaquaquecetuba/SP.

## Stack

- HTML5 semântico + CSS3 (custom properties, grid, flex)
- JavaScript vanilla — sem frameworks nem dependências externas de runtime
- Google Fonts (Playfair Display + Poppins) via `<link>` no `<head>`
- Deploy: Vercel (site estático)

## Estrutura

```
├── index.html            # Página única (arquivo único: HTML + CSS inline + JS inline)
├── capa.jpg              # Foto do hero
├── CRIOLIPOLISE*.jpg     # Fotos da seção de Criolipólise
├── DEPILACAO*.jpg        # Fotos da seção de Depilação a Laser
└── README.md
```

## Rodar localmente

Abra o `index.html` no navegador ou use qualquer servidor estático:

```bash
npx serve .
# ou
python -m http.server 8000
```

## Deploy

Deploy contínuo via Vercel — cada push em `main` gera nova build de produção.

## Contato

- WhatsApp: +55 11 97794-9156
- Instagram: [@esteticaelimonte](https://www.instagram.com/esteticaelimonte/)
- Endereço: Rua Estrada São Bento, 696 — Itaquaquecetuba/SP (próximo ao Supermercado Nagumo)

---

Desenvolvido por [InovaLogix](https://www.instagram.com/inovalogix).
