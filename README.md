# Site ALEX.IA - pronto para a verificação do Google

Três páginas estáticas preparadas para o Passo 2 da verificação do Google Ads API.
Atualizado em 26 de outubro de 2026.

**Próxima ação:** trocar o e-mail de contato nas três páginas (ele está marcado em amarelo na tela).

## O que tem aqui

- `index.html` · a página inicial, com a finalidade do serviço e os links no rodapé
- `privacidade.html` · vira `/privacidade` quando publicado
- `termos.html` · vira `/termos` quando publicado
- `vercel.json` · é o que faz `/privacidade` funcionar sem o `.html` no fim

## Antes de publicar

Procure por `SEU-EMAIL@EXEMPLO.COM.BR` nos três arquivos HTML e troque pelo seu e-mail de contato.
Aparece 10 vezes no total, e no texto das páginas legais fica destacado em amarelo na tela,
justamente para você não publicar sem trocar.

## Como publicar

O jeito mais simples, já que o código está aqui no GitHub:

- Entre em vercel.com e clique em Add New, depois Project
- Escolha importar este repositório (`gfspedro/gefessi`)
- Deixe tudo no padrão e clique em Deploy
- Aponte o seu domínio para o projeto nas configurações do projeto na Vercel

A partir daí, todo commit enviado para a branch `main` publica sozinho.
O HTTPS a Vercel liga por conta própria, então o SSL que o Google exige já vem resolvido.

## Depois de publicar, teste os três links

Abra cada um no navegador. Nenhum pode dar erro 404, senão a verificação do Google falha:

- `https://seudominio.com.br`
- `https://seudominio.com.br/privacidade`
- `https://seudominio.com.br/termos`
