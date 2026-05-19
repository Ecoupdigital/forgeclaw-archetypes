# forgeclaw-archetypes

Marketplace publico de arquetipos para [ForgeClaw](https://github.com/Ecoupdigital/forgeclaw).

Um **arquetipo** e um perfil completo (SOUL, USER, AGENTS, TOOLS, MEMORY, STYLE, HEARTBEAT) que o usuario instala em segundos para bootstrapar um harness funcional.

## Instalar um arquetipo

```bash
forgeclaw archetype list
forgeclaw archetype install ecoup/solo-builder-br
```

## Publicar um arquetipo

```bash
forgeclaw archetype publish \
  --handle <seu-handle> --name <nome> \
  --display "Nome Legivel" --description "Descricao" \
  --tags dev,br
```

O comando imprime instrucoes para PR neste repo.

## Status

**Alpha.** Durante a fase alpha, `tarballUrl` aponta para `file://` local. Quando o repo for publicado em GitHub, os URLs serao trocados para `https://raw.githubusercontent.com/Ecoupdigital/forgeclaw-archetypes/main/bundles/...`.

## Licenca

[MIT](./LICENSE).
