# Simulador FIIs × Imóvel Direto — Fincare

Simulador comparativo entre investir em Fundos Imobiliários (FIIs) ou comprar um imóvel direto ("Compra à vista + aluguel + valorização"), usando o mesmo capital disponível.

Desenvolvido seguindo o estilo do simulador patrimonial da Fincare (identidade verde Safra) e o layout de landing da referência de herança/patrimônio.

## Como usar

Abra `index.html` em qualquer navegador (não requer servidor nem build). É um arquivo único e autocontido (CSS + JS embutidos).

1. Informe o **objetivo principal**, o **prazo** e o **capital disponível** (as duas primeiras respostas personalizam a simulação e o relatório).
2. Clique em **Comparar agora**.
3. Veja o comparativo (patrimônio final, renda mensal, renda acumulada, veredito) e ajuste as premissas se desejar.
4. Deixe **nome, e-mail e WhatsApp** no bloco "Receba seu relatório em PDF" e clique em **Quero receber meu PDF** — isso gera o relatório (com seus dados) e abre o WhatsApp da Fincare com a mensagem pronta, para um assessor enviar o PDF.
5. Compartilhe via WhatsApp/e-mail ou baixe o relatório em PDF diretamente.

> O prazo informado ajusta automaticamente o horizonte da simulação (até 5 anos → 5, 5–10 → 10, 10–20 → 15, +20 → 20 anos).

## Captura de lead

O formulário coleta **objetivo** e **prazo** logo no início (para personalizar). No resultado, um bloco captura **nome, e-mail e WhatsApp** do lead com finalidade declarada: enviar o relatório em PDF e permitir contato de um assessor da Fincare (WhatsApp `5511941819794`). Dados são usados apenas para esse fim.

Site é estático (GitHub Pages, sem backend): para "enviar o PDF" o lead gera o arquivo e o contato ocorre via WhatsApp da Fincare com a mensagem pré-preenchida contendo os dados do lead e o resumo do comparativo.

## Premissas padrão

| Cenário | FIIs | Imóvel direto |
|---|---|---|
| Retorno | dividend yield 9% a.a. | aluguel 6% a.a. |
| Valorização | cota ~4% a.a. (reinveste 100% dos dividendos) | imóvel ~4% a.a. |
| Custos | — | ITBI 4%, manutenção 1% a.a., vacância 8,3% (1 mês/ano), IR sobre aluguel 27,5% |

Horizonte: definido pelo **prazo** escolhido no formulário (5 / 10 / 15 / 20 anos; padrão 20). Todas as premissas são ajustáveis no painel da página de resultado.

> ⚠️ Simulação com fins ilustrativos e educacionais. Não constitui recomendação de investimento nem garantia de rentabilidade futura. Consulte um assessor.

## Deploy (GitHub Pages)

O site é servido diretamente da branch `main` pelo GitHub Pages. Após push, a publicação fica disponível em:

```
https://<usuario>.github.io/simulador-fii-imovel/
```

## Branding

- Identidade: Fincare Investimentos · Safra Invest
- Logo: `https://fincarescorepatrimonial.com.br/logo-fincare.png`