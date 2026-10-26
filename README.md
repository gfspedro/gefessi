# Site ALEX.IA - pronto para a verificação do Google

Três páginas estáticas preparadas para o Passo 2 da verificação do Google Ads API.
Atualizado em 26 de outubro de 2026.

**Próxima ação:** conferir se os três endereços abrem sem erro 404 no domínio publicado.

## O que tem aqui

- `index.html` · a página inicial, com a finalidade do serviço e os links no rodapé
- `privacidade.html` · vira `/privacidade` quando publicado
- `termos.html` · vira `/termos` quando publicado
- `vercel.json` · é o que faz `/privacidade` funcionar sem o `.html` no fim

## Contato nas páginas

O e-mail de contato que aparece no rodapé e nas páginas legais é `pedrofguedes.contato@gmail.com`.
Para trocar, procure por ele nos três arquivos HTML e substitua.

## Como publicar

O projeto está ligado à Vercel pelo GitHub, então todo commit enviado para a branch `main`
publica sozinho. O HTTPS a Vercel liga por conta própria, então o SSL que o Google exige
já vem resolvido.

## Depois de publicar, teste os três links

Abra cada um no navegador. Nenhum pode dar erro 404, senão a verificação do Google falha:

- `https://seudominio.com.br`
- `https://seudominio.com.br/privacidade`
- `https://seudominio.com.br/termos`
