# Book de Pronta Entrega DNX

Como isso funciona a partir de agora:

- Você publica esta pasta no GitHub e no Netlify (uma vez).
- Depois disso, qualquer pessoa com o link consegue ver o catalogo, e
  qualquer edicao feita por qualquer pessoa (com a senha de edicao)
  aparece para todo mundo em poucos segundos, sem precisar de novo
  deploy, sem precisar subir arquivo nenhum de novo.
- As edicoes ficam guardadas num bin gratuito do jsonbin.io, ja
  configurado dentro dos dois arquivos de funcao (get-edits.js e
  save-edits.js). Nao precisa mexer em mais nada.

## Publicar

1. Extraia este zip de verdade (botao direito, "Extrair Tudo").
2. No repositorio do GitHub, apague tudo que estiver la e suba os 4 itens
   desta pasta de uma vez: netlify.toml, package.json, e as pastas
   public/ e netlify/ inteiras.
3. Confirme que a raiz do repositorio ficou com: netlify.toml,
   package.json, netlify/, public/ (sem nenhum arquivo solto extra).
4. No Netlify, va em Deploys -> Trigger deploy -> Deploy site.
5. Pronto. O link do site (ex: https://SEUSITE.netlify.app) e o que
   voce compartilha com a equipe.

## Como atualizar dali em diante

Nao precisa mais publicar nada de novo. Qualquer pessoa abre o link,
entra com a senha de edicao, faz a alteracao (nome, valor, foto, marcar
oportunidade, etc.) e clica em salvar. Isso ja fica visivel para todo
mundo que tiver o link aberto ou abrir depois, automaticamente.
