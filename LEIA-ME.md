# Site do Studio Socorro Horácio

Arquivos prontos para publicar (GitHub Pages, Vercel ou Netlify):

- `index.html`: o site inteiro (procure por `EDITE` para trocar dados)
- `images/`: fotos. As da Pollyany já estão aqui (vieram do pollyanyphair.com.br)
- `robots.txt`, `sitemap.xml`, `CNAME`: SEO e domínio (troque `studiosocorrohoracio.com.br` pelo domínio real)

## Fotos que faltam (salve em `images/` com estes nomes)

Enquanto a foto não existe, o site mostra um quadro dourado com o nome.

| Arquivo | O que é |
|---|---|
| socorro-antes.jpg / socorro-depois.jpg | Antes e depois de sobrancelha (depois, descomente o botão no index.html) |
| labios-antes.jpg / labios-depois.jpg | Antes e depois de lábios |
| og-capa.jpg | Imagem 1200x630 que aparece ao compartilhar o link |

As demais fotos (Socorro, Iuany, Bruna, Anne) vieram dos Instagrams e do WhatsApp delas, com ajuste leve de brilho e nitidez. As fotos do Instagram têm baixa resolução: trocar pelas originais deixa o site mais nítido.

Fotos quadradas ou verticais de até ~200 KB carregam rápido.

## Para usar como modelo em outro negócio

1. Troque nome, textos, endereço e WhatsApp (formato `55` + DDD + número).
2. Troque as cores em `:root` no começo do `<style>`.
3. Atualize os dois blocos `application/ld+json` (dados para o Google).
4. Troque o domínio no `canonical`, `og:url`, `robots.txt`, `sitemap.xml` e `CNAME`.
