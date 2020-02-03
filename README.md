# Saldo-Crédito-COOPS
O objetivo deste projeto é coletar e vizualizar dados sobre saldo de crédito, principalmetne das pessoas físicas, das cooperativas financeiras partindo de informações obtidas no site do Banco Central do Brasil/Departamento de Promoção Da Cidadania Financeira. Inicialmente são coletados os dados e criados gráficos sobre o saldo de crédito segundo diversos tipos (por valor, por pessoa, etc) e criados gráficos simples para sua visualização.  O objetivo final é criar um "aplicativo" que permita visualizar essas informações na forma de múltiplos gráficos com a possíbilidade de interação usando o "R shiny". 
Sobre os nomes dos arquivos:
SCCPT - Refere-se ao código para a construção dos gráficos sobre o Valor Total Saldo de Crédito das Cooperativas segundo o tipo de pessoa.
CCVC - Refere-se ao código para a construção dos gráficos sobre o Saldo de crédito das cooperativas para clientes pessoas físicas segundo a faixa de valor.
CSTR - Refere-se ao Código utilizado para a construção dos gráficos sobre o Saldo de crédito das cooperativas para clientes pessoa físicas por região.
Os referidos arquivos também estão disponíveis na formatação html, no Rpubs, nos links: 
https://rpubs.com/FelipeN94/CCVC
https://rpubs.com/FelipeN94/SCCPT

REFERÊNCIAS:

BANCO CENTRAL DO BRASIL/DEPEF. Saldo de crédito das cooperativas para clientes pessoa física - total. Disponível em: <https://dadosabertos.bcb.gov.br/dataset/25518-saldo-de-credito-das-cooperativas-para-clientes-pessoa-fisica----total>. Acesso em: 26 jan. 2020.

BANCO CENTRAL DO BRASIL/DEPEF.Saldo de crédito das cooperativas para clientes pessoa juridica - total.Disponível em: <https://dadosabertos.bcb.gov.br/dataset/25519-saldo-de-credito-das-cooperativas-para-clientes-pessoa-juridica----total>. Acesso em: 26 jan. 2020.

BANCO CENTRAL DO BRASIL/DEPEF. Saldo de crédito das cooperativas para clientes pessoa física por faixa de valor - menor que R$ 1 mil. Disponível em: <https://dadosabertos.bcb.gov.br/dataset/25536-saldo-de-credito-das-cooperativas-para-clientes-pessoa-fisica-por-faixa-de-valor---menor-que->. Acesso em: 28 jan 2020.

BANCO CENTRAL DO BRASIL/DEPEF. Saldo de crédito das cooperativas para clientes pessoa física por faixa de valor - de R$ 1 mil a R$ 5 mil.
Disponível em: <https://dadosabertos.bcb.gov.br/dataset/25537-saldo-de-credito-das-cooperativas-para-clientes-pessoa-fisica-por-faixa-de-valor---de-rs-1-mi>. Acesso em: 28 jan 2020.

BANCO CENTRAL DO BRASIL/DEPEF.Saldo de crédito das cooperativas para clientes pessoa física por faixa de valor - de R$ 5 mil a R$ 10 mil. 
 Disponível em: <https://dadosabertos.bcb.gov.br/dataset/25538-saldo-de-credito-das-cooperativas-para-clientes-pessoa-fisica-por-faixa-de-valor---de-rs-5-mi>. Acesso em: 28 jan 2020.

BANCO CENTRAL DO BRASIL/DEPEF.Saldo de crédito das cooperativas para clientes pessoa física por faixa de valor - acima de R$ 10 mil. Disponível em: <https://dadosabertos.bcb.gov.br/dataset/25539-saldo-de-credito-das-cooperativas-para-clientes-pessoa-fisica-por-faixa-de-valor---acima-de-r>. Acesso em: 28 jan 2020.

BANCO CENTRAL DO BRASIL/DEPEF.Saldo de crédito das cooperativas para clientes pessoa física por região - Sul. Disponível em: <https://dadosabertos.bcb.gov.br/dataset/25544-saldo-de-credito-das-cooperativas-para-clientes-pessoa-fisica-por-regiao---sul>. Acesso em: 30 jan. 2020.

BANCO CENTRAL DO BRASIL/DEPEF.Saldo de crédito das cooperativas para clientes pessoa física por região - Sudeste. Disponível em: <https://dadosabertos.bcb.gov.br/dataset/25543-saldo-de-credito-das-cooperativas-para-clientes-pessoa-fisica-por-regiao---sudeste>. Acesso em: 30 jan. 2020.


BANCO CENTRAL DO BRASIL/DEPEF.Saldo de crédito das cooperativas para clientes pessoa física por região - Norte. Disponível em: <https://dadosabertos.bcb.gov.br/dataset/25542-saldo-de-credito-das-cooperativas-para-clientes-pessoa-fisica-por-regiao---norte>. Acesso em: 30 jan. 2020.

BANCO CENTRAL DO BRASIL/DEPEF.Saldo de crédito das cooperativas para clientes pessoa física por região - Nordeste.Disponível em: <https://dadosabertos.bcb.gov.br/dataset/25541-saldo-de-credito-das-cooperativas-para-clientes-pessoa-fisica-por-regiao---nordeste>. Acesso em: 30 jan. 2020.

BANCO CENTRAL DO BRASIL/DEPEF.Saldo de crédito das cooperativas para clientes pessoa física por região - Centro-Oeste. Disponível em: <https://dadosabertos.bcb.gov.br/dataset/25540-saldo-de-credito-das-cooperativas-para-clientes-pessoa-fisica-por-regiao---centro-oeste>. Acesso em: 30 jan. 2020.
 
Pacotes usados:

Hadley Wickham (2007). Reshaping Data with the reshape Package. Journal of
Statistical Software, 21(12), 1-20. URL http://www.jstatsoft.org/v21/i12/.
  
H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York,
2016.

Hadley Wickham (2017). tidyverse: Easily Install and Load the 'Tidyverse'. R package
version 1.2.1. https://CRAN.R-project.org/package=tidyverse.

Linguagem R:
R Core Team (2019). R: A language and environment for statistical computing. R
Foundation for Statistical Computing, Vienna, Austria. URL https://www.R-project.org/.
