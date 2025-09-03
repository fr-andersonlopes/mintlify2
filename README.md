# Kit Inicial Mintlify

Use o kit inicial para implantar sua documentação e deixá-la pronta para personalização.

Clique no botão verde **Use this template** no topo deste repositório para copiar o kit inicial do Mintlify. O kit inicial contém exemplos com:

- Páginas de guia
- Navegação
- Personalizações
- Páginas de referência da API
- Uso de componentes populares

**[Siga o guia de início rápido completo](https://starter.mintlify.com/quickstart)**

## Desenvolvimento

Instale a [CLI do Mintlify](https://www.npmjs.com/package/mint) para visualizar as alterações da sua documentação localmente. Para instalar, use o seguinte comando:

```
npm i -g mint
```

Execute o seguinte comando na raiz da sua documentação, onde seu `docs.json` está localizado:

```
mint dev
```

Visualize sua prévia local em `http://localhost:3000`.

## Publicando alterações

Instale nosso aplicativo do GitHub no seu [painel](https://dashboard.mintlify.com/settings/organization/github-app) para propagar alterações do seu repositório para sua implantação. As alterações são implantadas em produção automaticamente após fazer push para a branch padrão.

## Precisa de ajuda?

### Solução de problemas

- Se seu ambiente de desenvolvimento não estiver funcionando: Execute `mint update` para garantir que você tenha a versão mais recente da CLI.
- Se uma página carregar como 404: Certifique-se de que você está executando em uma pasta com um `docs.json` válido.

### Recursos
- [Documentação do Mintlify](https://mintlify.com/docs)
- [Comunidade Mintlify](https://mintlify.com/community)
