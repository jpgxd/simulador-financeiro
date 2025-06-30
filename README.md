# Simulador de Investimentos em Fundos Imobiliários

Uma ferramenta simples em Excel para simular aportes mensais em Fundos de Investimento Imobiliário (FIIs), calcular o valor total investido, o patrimônio acumulado e os dividendos mensais projetados ao longo do tempo.

---

## Descrição do Projeto

Este repositório contém uma planilha (`Simulador Financeiro.xlsx`) desenvolvida como parte de um desafio DIO.me para criar uma solução prática de simulação de investimentos em FIIs. 
Com essa ferramenta o usuário pode:

- Definir salário, percentual de poupança e aporte mensal  
- Escolher horizonte de investimento (anos) e taxa de rendimento mensal  
- Visualizar patrimônio acumulado e dividendos mensais projetados  
- Testar cenários para diferentes períodos (2, 5, 10, 20 e 30 anos)  
- Receber sugestão de alocação de FIIs por perfil (Conservador, Moderado ou Agressivo)

---

## Estrutura do Repositório


├── Simulador Financeiro.xlsx      # Planilha principal  
└── README.md         # Este arquivo  

---

## Como Usar

1. Baixe o arquivo:  
   [`Simulador Financeiro.xlsx`](./Simulador%20Financeiro.xlsx)

2. Abra no Excel (ou outro programa compatível).

3. Preencha as informações na aba **CONFIGURAÇÃO**:
   - Salário
   - Valor do aporte mensal
   - Duração do investimento (em anos)
   - Rendimento mensal esperado

4. Veja os resultados nas abas:
   - **CENÁRIOS**: dividendos projetados para 2, 5, 10, 20 e 30 anos
   - **Planilha2**: alocação recomendada de FIIs conforme seu perfil de risco

---

## Alocação Sugerida por Perfil

| Perfil      | Papel | Tijolo | Híbridos | FOFs | Desenvolvimento | Hotelarias |
|-------------|:-----:|:------:|:--------:|:----:|:---------------:|:----------:|
| Conservador |  30%  |  50%   |   10%    | 10%  |       0%        |     0%     |
| Moderado    |  32%  |  35%   |    8%    | 5%   |      10%        |    10%     |
| Agressivo   |  50%  |  10%   |    5%    | 5%   |      20%        |    10%     |

---

## Tutor

Projeto realizado sob orientação de [Felipe Aguiar](https://github.com/felipeAguiarCode)

---

## Observações Finais

Este projeto faz parte do meu portfólio de aprendizado na DIO. Ele demonstra minha capacidade de aplicar conceitos de Excel em um contexto prático e voltado para finanças pessoais, com foco em organização, automação e clareza visual.
