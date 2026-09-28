# Raízes no povo

Página estática que exibe o PDF original, preservando integralmente o conteúdo e a composição visual do documento.

## Cloudflare Pages

Este projeto não precisa de etapa de build nem de dependências.

Para conectar pelo GitHub:

1. No Cloudflare, abra **Workers & Pages** e crie um projeto Pages conectado a `JoaoplMoreno/teste`.
2. Use a branch `main` como branch de produção.
3. Selecione **None** como preset. Deixe o comando de build em branco e defina `public` como diretório de saída.
4. Salve e faça o primeiro deploy. Os próximos pushes na branch de produção serão publicados automaticamente.

O `wrangler.jsonc` registra o nome `teste` e o diretório de saída `public` para uso com Wrangler e editores compatíveis.
