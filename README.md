# Simulador FIIs × Imóvel Direto — Fincare

Simulador comparativo entre investir em Fundos Imobiliários (FIIs) ou comprar um imóvel direto ("Compra à vista + aluguel + valorização"), usando o mesmo capital disponível.

Desenvolvido seguindo o estilo do simulador patrimonial da Fincare (identidade verde Safra) e o layout de landing da referência de herança/patrimônio.

## Como usar

Abra `index.html` em qualquer navegador (não requer servidor nem build). É um arquivo único e autocontido (CSS + JS embutidos).

1. Informe o capital disponível.
2. Clique em **Comparar**.
3. Veja o comparativo (patrimônio final, renda mensal, renda acumulada, veredito) e ajuste as premissas se desejar.
4. Compartilhe via WhatsApp/e-mail ou baixe o relatório em PDF.

## Premissas padrão

| Cenário | FIIs | Imóvel direto |
|---|---|---|
| Retorno | dividend yield 9% a.a. | aluguel 6% a.a. |
| Valorização | cota ~4% a.a. (reinveste 100% dos dividendos) | imóvel ~4% a.a. |
| Custos | — | ITBI 3%, manutenção 1% a.a., vacância 4% |

Horizonte padrão: **20 anos**. Todas as premissas são ajustáveis no painel da página de resultado.

> ⚠️ Simulação com fins ilustrativos e educacionais. Não constitui recomendação de investimento nem garantia de rentabilidade futura. Consulte um assessor.

## Deploy (GitHub Pages)

O site é servido diretamente da branch `main` pelo GitHub Pages. Após push, a publicação fica disponível em:

```
https://<usuario>.github.io/simulador-fii-imovel/
```

## Branding

- Identidade: Fincare Investimentos · Safra Invest
- Logo: `https://fincarescorepatrimonial.com.br/logo-fincare.png`