# PV Nervio Vago — Teste de Ticket $5.90

Página de vendas estática (ES/LATAM) da oferta **Kit de Regulación del Sistema Nervioso**.

Variante do teste de ticket: **card único, $5.90 USD**.

| Item | Valor |
|---|---|
| Estrutura | card único |
| Preço | $5.90 USD |
| Ancoragem | $97 USD |
| Checkout | `https://go.centerpag.com/PPU38CQFCNB` |

## Deploy

Site estático, sem build. É só publicar a raiz do repositório.

No Netlify: build command vazio, publish directory `.`.

## Estrutura

```
index.html      página completa
css/index.css   Tailwind compilado
js/             pixel UTMify + rastreio de UTMs
images/         74 imagens (todas locais, sem dependência externa)
```

## Comportamento dos CTAs

O botão da hero rola até a seção `#oferta` em vez de ir direto ao checkout — o lead passa pela pilha de valor, bônus, prova e garantia antes de ver o preço. Os CTAs dentro e depois do card de oferta vão direto ao checkout.
