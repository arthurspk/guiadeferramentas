# Como contribuir com o Guia de Ferramentas e Extensões

Obrigado por querer melhorar este guia! Ele faz parte da rede [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil). Toda contribuição passa por revisão.

## O que você pode sugerir

- **Novo recurso** (ferramenta, extensão, gerador, canal, comunidade, artigo): abra uma issue com o template *Sugestão de recurso* ou envie um pull request.
- **Link quebrado ou desatualizado:** abra uma issue com o template *Link quebrado*, de preferência já com um substituto.
- **Correção de texto** (ortografia, descrição imprecisa, categoria errada): pull request direto.

## Critérios de aceitação

Um recurso só entra no guia se cumprir **todos** os itens:

1. **Link funcionando** — resposta HTTP 200 no momento da revisão (verificamos com [lychee](https://github.com/lycheeverse/lychee)).
2. **Conteúdo legal** — apenas fontes oficiais ou legitimamente gratuitas. Nada de cursos pagos redistribuídos, extensões piratas ou "drives" de terceiros.
3. **Descrição curta** dizendo o que é e por que vale o clique.
4. **Ordem:** dentro de cada seção, recursos gratuitos e em português vêm primeiro.
5. **Curadoria, não acumulação:** preferimos poucos recursos excelentes a muitos duvidosos. Se o guia já cobre o assunto com algo melhor, a sugestão pode ser recusada.

Formato de cada item:

```markdown
- [Nome do recurso](https://url-verificada) — descrição curta do que é e por que vale o clique.
```

## Fluxo de pull request

1. Faça um fork e crie uma branch a partir da `main` (ex.: `feat/nova-ferramenta`).
2. Edite o `README.md`.
3. Rode a verificação de links antes de abrir o PR:
   ```bash
   lychee --no-progress './**/*.md'
   ```
4. Abra o PR preenchendo o checklist do template. Descreva o que mudou e por quê.
5. Um mantenedor revisa; ajustes podem ser pedidos antes do merge.

## Código de conduta

Ao participar, você concorda com o nosso [Código de Conduta](./CODE_OF_CONDUCT.md).
