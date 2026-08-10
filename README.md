# AVANCE — Landing page

Landing page estática (HTML/CSS/JS puro, sem build) do projeto **AVANCE — Um
caminho de formação para viver como Jesus**, de Carolina Feres Busato.

## Estrutura

```
index.html                  página única
pote.webp                   foto do hero (roda do oleiro)
capa.webp                   capa do material impresso
carolina.webp               foto da autora (seção "Sobre a autora")
thumb-planner.webp          prévia do card "Meu Planner Semanal"
thumb-revestidas.webp       prévia do card "Revestidas de Cristo"
thumb-workbook.webp         prévia do card "Workbook"
planner-semanal.pdf         material para download
revestidas-de-cristo.pdf    material para download
workbook.pdf                material para download
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

- **`carolina.webp`** está em baixa resolução (183×275px, arquivo enviado
  pelo usuário). Fica visível em telas grandes/retina. Substitua por um
  arquivo de maior resolução quando disponível.
- **Número de WhatsApp**: definido em `var WHATSAPP = "5541999999999"` no
  final de `index.html` — troque pelo número real da Carolina antes de
  divulgar o link.
