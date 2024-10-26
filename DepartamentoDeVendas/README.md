# **Descrição do Conjunto de Dados (Dataset Description)**  
Você possui dados históricos de vendas para 1.115 lojas Rossmann. A tarefa é prever a coluna "Sales" para o conjunto de teste. Note que algumas lojas no conjunto de dados foram temporariamente fechadas para reformas.

**Arquivos**  
- **train.csv** - dados históricos, incluindo Vendas  
- **test.csv** - dados históricos, excluindo Vendas  
- **sample_submission.csv** - um arquivo de submissão de exemplo no formato correto  
- **store.csv** - informações suplementares sobre as lojas  

**Campos de Dados**  
A maioria dos campos é autoexplicativa. Abaixo estão descrições para aqueles que não são:

- **Id** - um Id que representa um par (Loja, Data) no conjunto de teste  
- **Store** - um Id exclusivo para cada loja  
- **Sales** - o faturamento de um determinado dia (este é o valor que você deve prever)  
- **Customers** - o número de clientes em um determinado dia  
- **Open** - indicador se a loja estava aberta: 0 = fechada, 1 = aberta  
- **StateHoliday** - indica um feriado estadual. Normalmente todas as lojas, com algumas exceções, estão fechadas nos feriados estaduais. a = feriado público, b = feriado de Páscoa, c = Natal, 0 = Nenhum  
- **SchoolHoliday** - indica se o (Loja, Data) foi afetado pelo fechamento de escolas públicas  
- **StoreType** - diferencia entre 4 modelos de loja diferentes: a, b, c, d  
- **Assortment** - descreve um nível de sortimento: a = básico, b = extra, c = estendido  
- **CompetitionDistance** - distância em metros até a loja concorrente mais próxima  
- **CompetitionOpenSince[Month/Year]** - indica o ano e mês aproximados em que o concorrente mais próximo foi aberto  
- **Promo** - indica se uma loja está realizando uma promoção naquele dia  
- **Promo2** - Promo2 é uma promoção contínua e consecutiva para algumas lojas: 0 = loja não participa, 1 = loja participa  
- **Promo2Since[Year/Week]** - descreve o ano e a semana do calendário em que a loja começou a participar da Promo2  
- **PromoInterval** - descreve os intervalos consecutivos em que a Promo2 é iniciada, nomeando os meses em que a promoção é reiniciada. Exemplo: "Feb,May,Aug,Nov" significa que cada rodada começa em fevereiro, maio, agosto e novembro para essa loja.

