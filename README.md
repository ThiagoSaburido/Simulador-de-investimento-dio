🏢 Sabu Invest — Simulador de Investimentos em Fundos Imobiliários (FIIs)

Mostrar Imagem

📋 Descrição do Projeto

Este projeto consiste na criação de uma ferramenta simples em Excel para simular investimentos em Fundos de Investimento Imobiliário (FIIs). A planilha permite calcular o valor total investido, o patrimônio acumulado e os dividendos mensais, ajudando o usuário a entender melhor o impacto de seus investimentos ao longo do tempo.

O objetivo é aplicar conceitos de Excel na construção de uma ferramenta prática que responda às perguntas mais comuns de um investidor: quanto investir, por quanto tempo e qual o rendimento esperado. O modelo automatiza cálculos financeiros que normalmente seriam feitos manualmente, servindo como base para futuras expansões e personalizações.

Este projeto foi desenvolvido como parte do desafio de código "Entendendo Desafio" da DIO (Digital Innovation One).

🎯 Objetivos de Aprendizagem

Ao concluir este projeto, foi possível:

Criar ferramentas de simulação de investimentos em Excel;
Aplicar cálculos financeiros como rendimento mensal e cálculo de dividendos;
Documentar processos técnicos de forma clara e estruturada;
Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica.
🗂️ Estrutura da Planilha

O arquivo Simulador_Investimentos_FII.xlsx está organizado em três blocos principais:

1. Dados de Entrada (editáveis)

Células destacadas em amarelo, com texto em azul, indicando que são os valores que o usuário pode alterar:

Campo	Descrição	Valor padrão
Valor Investido Inicial (R$)	Capital aportado no primeiro mês	R$ 10.000,00
Aporte Mensal (R$)	Valor investido todos os meses	R$ 500,00
Dividend Yield Mensal (%)	Rendimento mensal em dividendos	0,80%
Valorização Mensal da Cota (%)	Valorização mensal do patrimônio investido	0,30%
Período da Simulação (meses)	Duração da simulação	60 meses
2. Resumo da Simulação

Cálculos automáticos que consolidam o resultado final:

Total Investido (Aportes): soma do valor inicial com todos os aportes mensais;
Patrimônio Acumulado Final: valor total do patrimônio ao fim do período simulado;
Total de Dividendos Recebidos: soma de todos os dividendos pagos ao longo da simulação;
Dividendo Médio Mensal: média dos dividendos recebidos nos últimos 12 meses.
3. Tabela Mês a Mês

Projeção detalhada, mês a mês, com as seguintes colunas:

Mês
Aporte do Mês (R$)
Valor Total Investido (R$)
Patrimônio Acumulado (R$)
Dividendos do Mês (R$)
Dividendos Acumulados (R$)
🧮 Fórmulas Utilizadas

As fórmulas foram construídas para que a planilha recalcule automaticamente sempre que os dados de entrada forem alterados:

Dividendos do Mês = Patrimônio do Mês Anterior × Dividend Yield Mensal

Patrimônio Acumulado = (Patrimônio do Mês Anterior + Aporte do Mês) × (1 + Valorização Mensal da Cota)

Valor Total Investido (acumulado) = Valor Investido Inicial + Soma dos Aportes até o mês atual

Essa lógica simula o efeito de juros compostos combinado com aportes mensais recorrentes, que é o comportamento real de um investimento em FIIs ao longo do tempo.

🚀 Como Usar
Baixe o arquivo Simulador_Investimentos_FII.xlsx;
Abra no Excel, Google Sheets ou LibreOffice Calc;
Edite as células amarelas (Valor Inicial, Aporte Mensal, Dividend Yield e Valorização da Cota) com os dados do seu cenário;
Acompanhe o resumo automático e a tabela mês a mês para entender a evolução do seu patrimônio;
Use os resultados como referência para planejar seus próprios aportes em FIIs.

💡 Observação: a tabela já está pré-calculada para 60 meses. Para simular um período diferente, atualize o campo "Período da Simulação" e ajuste (adicione ou remova) linhas da tabela conforme necessário.

🖼️ Capturas de Tela

Adicione aqui prints da planilha aberta, mostrando os dados de entrada, o resumo e a tabela de projeção preenchidos. Salve as imagens na pasta /images.

images/
 ├── banner_sabu_invest.png
 ├── dados-de-entrada.png
 ├── resumo-simulacao.png
 └── tabela-mensal.png
🛠️ Tecnologias Utilizadas
Microsoft Excel (fórmulas, formatação condicional e referências de células)
Conceitos de matemática financeira (juros compostos, dividendos, aportes recorrentes)
📈 Possibilidades de Expansão

Este modelo pode servir de base para melhorias futuras, como:

Gráficos de evolução patrimonial ao longo do tempo;
Comparação entre diferentes FIIs ou cenários de investimento;
Cálculo de Imposto de Renda sobre ganho de capital;
Simulação de reinvestimento automático dos dividendos recebidos.
👤 Autor

Projeto desenvolvido durante o desafio de código da DIO (Digital Innovation One), como prática dos conceitos de Excel aplicados a simulações financeiras.



