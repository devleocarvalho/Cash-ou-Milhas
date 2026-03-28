Atue como um analista de mercado financeiro e milhas. Preciso que você atualize os valores de configuração do meu JSON abaixo.

Pesquise o valor atual do Dólar PTAX (venda).

Pesquise o valor médio do milheiro (1.000 pontos) nos programas Livelo/Esfera quando vendidos no mercado secundário (ex: HotMilhas/MaxMilhas).

Verifique a Taxa SELIC/CDI anual atual no Brasil.

Retorne APENAS o bloco "config" atualizado, mantendo a data de hoje no campo "atualizado_em".

{
"config": {
"usd_ptax": 5.15,
"valor_milheiro": 20.00,
"cdi_anual": 0.1125,
"atualizado_em": "2026-03-21"
},
"bancos": {
"Banco do Brasil": {
"Visa": [
{"n": "Gold", "anuidade": 372, "c": 0, "p": 1.0, "p_unit": "dollar", "points_program": "Livelo", "obs": "1.0 pt/$ Livelo. Anuidade: 12x R$31."},
{"n": "Platinum", "anuidade": 588, "c": 0, "p": 1.5, "p_unit": "dollar", "points_program": "Livelo", "obs": "1.5 pts/$ Livelo. Anuidade: 12x R$49."},
{"n": "Infinite", "anuidade": 1188, "c": 0, "p": 2.0, "p_unit": "dollar", "points_program": "Livelo", "obs": "2.0 pts/$ Livelo. Isenção com gastos acima de R$10k/mês. Anuidade: 12x R$99."},
{"n": "Altus Infinite", "anuidade": 1440, "c": 0, "p": 2.5, "p_unit": "dollar", "points_program": "Livelo", "obs": "Pontuação base de 2.5 pts/$. Clientes Private ou com R$25k/mês em gastos recebem 4.0 pts/$. Anuidade: 12x R$120."}
],
"Mastercard": [
{"n": "Black", "anuidade": 1224, "c": 0, "p": 2.0, "p_unit": "dollar", "points_program": "Livelo", "obs": "2.0 pts/$ Livelo. Isenção com gastos acima de R$12k/mês. Anuidade: 12x R$102."}
],
"Elo": [
{"n": "Grafite", "anuidade": 564, "c": 0, "p": 1.7, "p_unit": "dollar", "points_program": "Livelo", "obs": "1.7 pts/$ Livelo. Anuidade: 12x R$47."},
{"n": "Nanquim", "anuidade": 1224, "c": 0, "p": 2.2, "p_unit": "dollar", "points_program": "Livelo", "obs": "2.2 pts/$ Livelo. Isenção com gastos acima de R$12k/mês. Anuidade: 12x R$102."}
]
},
"Bradesco": {
"Visa": [
{"n": "Signature", "anuidade": 654, "c": 0, "p": 1.0, "p_unit": "dollar", "points_program": "Livelo", "obs": "1.0 pt/$ Livelo. Anuidade: 12x R$54,50."},
{"n": "Infinite", "anuidade": 1188, "c": 0, "p": 2.0, "p_unit": "dollar", "points_program": "Livelo", "obs": "2.0 pts/$ Livelo. Anuidade: 12x R$99."},
{"n": "Aeternum", "anuidade": 1680, "c": 0, "p": 4.0, "p_unit": "dollar", "points_program": "Livelo", "obs": "4.0 pts/$ - Private Bank. Anuidade: 12x R$140."}
],
"Amex": [
{"n": "Gold Card", "anuidade": 696, "c": 0, "p": 1.0, "p_unit": "dollar", "points_program": "Membership Rewards", "obs": "1.0 pt/$ em compras gerais. Anuidade: 12x R$58."},
{"n": "The Platinum", "anuidade": 1749, "c": 0, "p": 2.2, "p_unit": "dollar", "points_program": "Membership Rewards", "obs": "Pontos que nunca expiram. Anuidade: 12x R$145,75."},
{"n": "Centurion", "anuidade": 10000, "c": 0, "p": 5.0, "p_unit": "dollar", "points_program": "Membership Rewards", "obs": "5.0 pts/$ - Ultra Raro, apenas por convite."}
],
"Elo": [
{"n": "Grafite", "anuidade": 654, "c": 0, "p": 1.4, "p_unit": "dollar", "points_program": "Livelo", "obs": "1.4 pts/$ Livelo. Anuidade: 12x R$54,50."},
{"n": "Nanquim", "anuidade": 1284, "c": 0, "p": 2.2, "p_unit": "dollar", "points_program": "Livelo", "obs": "2.2 pts/$ Livelo. Anuidade: 12x R$107."},
{"n": "Diners Club", "anuidade": 1284, "c": 0, "p": {"base": 2.2, "international": 3.3}, "p_unit": "dollar", "points_program": "Livelo", "obs": "2.2 pts/$ em compras nacionais e 3.3 pts/$ em internacionais. Anuidade: 12x R$107."}
]
},
"Itaú": {
"Visa": [
{"n": "Signature", "anuidade": 660, "c": 0, "p": 1.5, "p_unit": "dollar", "points_program": "Itaú", "obs": "1.5 pts/$. Anuidade: 12x R$55."},
{"n": "Azul Infinite", "anuidade": 1200, "c": 0, "p": {"base": 3.0, "international": 3.5}, "p_unit": "dollar", "points_program": "Azul", "obs": "3.0 pts/$ (nacional) e 3.5 pts/$ (internacional). Isenção com R$20k/mês. Anuidade: 12x R$100."},
{"n": "GOL Smiles Infinite", "anuidade": 1188, "c": 0, "p": 3.0, "p_unit": "dollar", "points_program": "Smiles", "obs": "3.0 pts/$ para clientes Clube Smiles, 2.2 para demais. Isenção com R$20k/mês. Anuidade: 12x R$99."}
],
"Mastercard": [
{"n": "Black", "anuidade": 792, "c": 0, "p": 2.0, "p_unit": "dollar", "points_program": "Itaú", "obs": "2.0 pts/$. Isenção com R$10k/mês. Anuidade: 12x R$66."},
{"n": "Personnalité Black", "anuidade": 1188, "c": 0, "p": {"base": 2.0, "international": 3.0}, "p_unit": "dollar", "points_program": "Itaú", "obs": "2.0 pts/$ (nacional) e 3.0 pts/$ (internacional). Isenção com R$50k/mês ou R$5M investidos. Anuidade: 12x R$99."},
{"n": "LATAM Black", "anuidade": 1200, "c": 0, "p": 2.5, "p_unit": "dollar", "points_program": "LATAM Pass", "obs": "2.5 pts/$ direto na LATAM. Isenção com R$20k/mês. Anuidade: 12x R$100."},
{"n": "The One", "anuidade": 4000, "c": 0, "p": {"base": 3.5, "international": 4.0}, "p_unit": "dollar", "points_program": "Itaú", "obs": "3.5 pts/$ (nacional) e 4.0 pts/$ (internacional). Nível Private. Anuidade: 12x R$333,33."}
]
},
"Santander": {
"Mastercard": [
{"n": "Black Unique", "anuidade": 1164, "c": 0, "p": 2.0, "p_unit": "dollar", "points_program": "Esfera", "obs": "2.0 pts/$ Esfera. Isenção com R$20k/mês. Anuidade: 12x R$97."},
{"n": "Unlimited", "anuidade": 1290, "c": 0, "p": 2.6, "p_unit": "dollar", "points_program": "Esfera", "obs": "2.6 pts/$. Isenção com R$20k/mês. Anuidade: 12x R$107,50."}
],
"Visa": [
{"n": "Infinite Unique", "anuidade": 1164, "c": 0, "p": 2.0, "p_unit": "dollar", "points_program": "Esfera", "obs": "2.0 pts/$ Esfera. Isenção com R$20k/mês. Anuidade: 12x R$97."},
{"n": "GOL Smiles Infinite", "anuidade": 1134, "c": 0, "p": 3.0, "p_unit": "dollar", "points_program": "Smiles", "obs": "3.0 pts/$ para clientes Clube Smiles, 2.2 para demais. Isenção com R$20k/mês. Anuidade: 12x R$94,50."}
],
"Amex": [
{"n": "The Platinum", "anuidade": 1450, "c": 0, "p": 2.2, "p_unit": "dollar", "points_program": "Membership Rewards", "obs": "2.2 pts/$ no programa Membership Rewards (não Esfera). Anuidade: 12x R$120,83."}
]
},
"CAIXA": {
"Visa": [
{"n": "Infinite", "anuidade": 999, "c": 0, "p": 2.3, "p_unit": "dollar", "points_program": "CAIXA", "obs": "2.3 pts/$ no programa Pontos CAIXA. Anuidade: 12x R$83,25."},
{"n": "Dux Infinite", "anuidade": 1200, "c": 0, "p": {"base": 5.0, "international": 7.0}, "p_unit": "dollar", "points_program": "CAIXA", "obs": "Acúmulo base de 5.0 pts/$ e 7.0 pts/$ em compras internacionais. Anuidade: 12x R$100."}
],
"Elo": [
{"n": "Nanquim", "anuidade": 828, "c": 0, "p": 2.3, "p_unit": "dollar", "points_program": "CAIXA", "obs": "Melhor conversão Elo do mercado. Anuidade: 12x R$69."}
]
},
"Nubank": {
"Mastercard": [
{"n": "Gold/Platinum", "anuidade": 0, "c": 0, "p": 0, "obs": "Sem acúmulo e sem anuidade."},
{"n": "Ultravioleta", "anuidade": 588, "reward_type": "choice", "c": 0.01, "p": 1.0, "p_unit": "real", "points_program": "Nubank", "obs": "Escolha entre 1% de cashback (que rende 200% do CDI) ou 1 ponto/Real. Isenção com R$5k/mês ou R$50k guardados. Anuidade: 12x R$49."}
]
},
"C6 Bank": {
"Mastercard": [
{"n": "Platinum", "anuidade": 0, "c": 0, "p": 0.05, "p_unit": "real", "points_program": "Átomos", "obs": "0.05 pts por Real. Sem anuidade."},
{"n": "Carbon Black", "anuidade": 1176, "c": 0, "p": 2.5, "p_unit": "dollar", "points_program": "Átomos", "obs": "2.5 pts/$ no programa Átomos. Isenção com R$8k/mês. Anuidade: 12x R$98."},
{"n": "Graphene", "anuidade": 600, "c": 0, "p": 2.0, "p_unit": "dollar", "points_program": "Átomos", "obs": "2.0 pts/$ - Cartão para contas PJ (Empresas). Anuidade: 12x R$50."}
]
},
"Inter": {
"Mastercard": [
{"n": "Gold", "anuidade": 0, "c": 0.0025, "p": 0, "obs": "0.25% Cashback. Sem anuidade."},
{"n": "Platinum", "anuidade": 0, "c": 0.005, "p": 0, "obs": "0.5% Cashback. Sem anuidade."},
{"n": "Black", "anuidade": 0, "c": 0.01, "p": 0, "obs": "1% Cashback. Anuidade isenta para assinantes Duo Gourmet ou com gastos acima de R$7k/mês."},
{"n": "Win", "anuidade": 0, "c": 0.0125, "p": 0, "obs": "1.25% Cashback. Apenas para clientes com mais de R$1M investido."}
]
},
"XP Investimentos": {
"Visa": [
{"n": "Infinite", "anuidade": 0, "reward_type": "cashback", "c": 0.01, "p": 0, "obs": "1% Investback. Anuidade isenta com gastos acima de R$3k/mês."}
]
},
"BTG Pactual": {
"Mastercard": [
{"n": "Advanced", "anuidade": 180, "reward_type": "choice", "c": 0.0075, "p": 1.6, "p_unit": "dollar", "points_program": "BTG", "obs": "Escolha entre 0.75% de cashback ou 1.6 pts/$. Anuidade: 12x R$15."},
{"n": "Black", "anuidade": 1188, "reward_type": "choice", "c": 0.01, "p": 2.2, "p_unit": "dollar", "points_program": "BTG", "obs": "Escolha entre 1% de cashback ou 2.2 pts/$. Isenção com R$12k/mês ou R$100k investidos. Anuidade: 12x R$99."},
{"n": "Black (Investidor Diamante)", "anuidade": 1188, "reward_type": "choice", "c": 0.01, "p": 2.75, "p_unit": "dollar", "points_program": "BTG", "obs": "Benefício para clientes com altos investimentos (Missão BTG). Escolha entre 1% de cashback ou 2.75 pts/$."}
]
},
"Porto Bank": {
"Visa": [
{"n": "Infinite", "anuidade": 1500, "c": 0, "p": 2.2, "p_unit": "dollar", "points_program": "Porto Plus", "obs": "Pontuação base de 2.2 pts/$. Aumenta para 3.0 pts/$ com gastos acima de R$10k e 3.5 pts/$ com gastos acima de R$20k. Isenção com R$20k/mês. Anuidade: 12x R$125."}
]
}
,
"Unicred": {
"Visa": [
{"n": "Infinite", "anuidade": 750, "c": 0, "p": 2.2, "p_unit": "dollar", "points_program": "Unicred", "obs": "2.2 pts/$ no programa de pontos Unicred. Anuidade: 12x R$62,50."}
]
}
}
}
