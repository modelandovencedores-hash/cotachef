# CotaChef — Landing Page

Landing page de vendas para o **CotaChef**, um serviço de cotação inteligente de suprimentos para restaurantes e empresas do ramo alimentício via WhatsApp.

## O que é o CotaChef

O CotaChef conecta donos de restaurantes com múltiplos fornecedores por meio de arbitragem de preços. O restaurante envia sua lista de compras pelo WhatsApp e recebe, em até 2 horas, o comparativo de preços dos fornecedores parceiros — permitindo sempre comprar pelo menor preço disponível.

O objetivo é reduzir o CMV (Custo de Mercadoria Vendida) do restaurante sem exigir mudança de sistema, treinamento ou rotina.

## Sobre esta página

Página de conversão de plano único, construída para levar o dono de restaurante a assinar um dos dois planos disponíveis:

| Plano | Valor |
|-------|-------|
| Mensal | R$ 400/mês |
| Anual | R$ 3.000/ano (equivale a R$ 250/mês) |

### Seções

1. **Hero** — Proposta de valor com mockup de conversa WhatsApp animada
2. **Stats** — Números de credibilidade (restaurantes, redução de CMV, tempo de cotação)
3. **Problema** — Espelho das dores do público-alvo (CMV, falta de tempo, preços altos)
4. **Como funciona** — 3 passos simples
5. **Benefícios** — 6 diferenciais do serviço
6. **Depoimentos** — Resultados reais de clientes
7. **Preços** — Cards dos planos com CTA para WhatsApp
8. **FAQ** — Principais objeções respondidas
9. **CTA Final** — Fechamento de conversão

## Stack

- HTML5 + CSS3 + JavaScript vanilla (zero dependências)
- Fontes via Google Fonts: Cormorant Garamond, Outfit, Space Mono
- Toggle dark/light mode com persistência via `localStorage`
- Deploy automático via Cloudflare Pages

## Deploy

O arquivo `cotachef.html` é o único entregável. O workflow `.github/workflows/deploy.yml` faz o deploy automático para o Cloudflare Pages a cada push na branch `master`.

## Configuração

Antes de publicar em produção, substitua o número de WhatsApp placeholder nos links:

```
https://wa.me/5511999999999
```

pelo número real do negócio.

---

Desenvolvido como projeto do curso Thales · 2026
