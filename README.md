# Site JRC Engenharia e Geotecnia

Site institucional **estático, leve e responsivo** da JRC Engenharia e Geotecnia.

## Tecnologia

- HTML5 + CSS3 puro — sem frameworks, sem dependências externas.
- Uma única página (`index.html`) com navegação por âncoras.
- Layout responsivo (desktop, tablet e celular).

## Estrutura

```
.
├── index.html          # página única
└── assets/
    ├── styles.css      # estilos
    ├── logo-jrc.png    # logotipo
    └── hero-obra.jpg   # foto de fundo do primeiro painel
```

## Como visualizar localmente

Basta abrir o `index.html` no navegador. Para servir via HTTP local:

```bash
python -m http.server 5500
```

Depois acesse `http://localhost:5500`.

## Publicação (GitHub Pages)

O site pode ser publicado gratuitamente pelo GitHub Pages:
**Settings → Pages → Build and deployment → Source: _Deploy from a branch_ → Branch: `main` / `/root`**.

---

© JRC Engenharia e Geotecnia. Segurança · Durabilidade · Qualidade.
