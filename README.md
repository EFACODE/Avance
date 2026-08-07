# AVANCE — Landing page

Landing page estática (HTML/CSS/JS puro, sem build) do projeto **AVANCE — Um
caminho de formação para viver como Jesus**, de Carolina Feres Busato.

## Estrutura

```
index.html                  página única
pote.webp                   foto do hero (roda do oleiro)
capa.webp                   capa do material impresso
thumb-planner.webp          prévia do card "Meu Planner Semanal"
thumb-revestidas.webp       prévia do card "Revestidas de Cristo"
planner-semanal.pdf         material para download
revestidas-de-cristo.pdf    material para download
```

## Rodar localmente

Qualquer servidor estático funciona, por exemplo:

```bash
npx serve .
```

## Deploy

Site 100% estático — sem passo de build. O Vercel detecta automaticamente
(`Other`/static) e publica o conteúdo da raiz do repositório.

## Pendências antes de publicar em produção

- **`pote.webp`** e **`capa.webp`** são placeholders ilustrativos gerados a
  partir da identidade visual do projeto (paleta terracota + motivo das
  marcas do torno de oleiro). Substitua pelas fotos reais quando disponíveis.
- **Foto da Carolina** (seção "Quem conduz"): hoje é um bloco de texto
  (`.portrait .ph`). Troque pelo `<img>` comentado em `index.html` assim que
  tiver a foto.
- **Número de WhatsApp**: definido em `var WHATSAPP = "5541999999999"` no
  final de `index.html` — troque pelo número real da Carolina antes de
  divulgar o link.
