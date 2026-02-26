# sctec-dadosia
Dataset Challenge project for SC Tech Program


# Programa SC Tec
 Projeto apresentado para desafio do SCTEC

# Descrição da solução desenvolvida;
Análise de dados de arrecadacao por setor economico


# Origem do conjunto de dados utilizado;
dicionario-de-dados-arrecadacao-por-setor-economico-v1.0
obtido no Portal de Dados Abertos do Estado de Santa Catarina
https://www.dados.sc.gov.br/gl/
http://www.transparencia.sc.gov.br/documentos

# As tecnologias empregadas;
Pandas, Numpy

Dados coletados a partir do Painel de Transferências Abertas no endereço: http://www.transferenciasabertas.planejamento.gov.br
Os dados disponibilizados possuíam duas limitações para a nossa necessidade de análise:
Não tinha a coluna que indicava o tipo de despesa;
Não permitia exportação de planilha com mais de 30 mil linhas.
Identifiquei 06 tipos de despesa, que geraram 08 arquivos para exportação.
Concatenei todos os arquivos exportados em um único DataFrame, para iniciar o nosso trabalho de análise e predição.


Empreguei seis diferentes algoritmos de classificação e selecionamos o modelo gerado com maior acurácia:
*   KNN Classifier
*   Regressão Logística
*   Árvore de Decisão
*   Random Forest
*   Support Vector Machine (SVM)
*   Permutation importance
Gerei até 05 modelos com cada Algoritmo, com diferentes estratégias.



Além disso, o limite máximo para exportação de planilha é de 30.000 linhas.
Por isso a importação será feita em partes para somente depois concatenar todo o DataFrame

Dessa forma, foram importadas inicialmente as seguintes planilhas:
- Tipo de Arrecadacao : dicionario-de-dados-arrecadacao-por-setor-economico-v1.0
- Setor Responsável : setor_economico
- Tipo de Despesa : dicionario-de-dados-balanco-geral-renuncia-fiscal-v1.1



# A estrutura geral do projeto;
Jupyter

As instruções necessárias para execução;
Rodar notebook

Um link para o vídeo pitch, que deverá estar referenciado diretamente no README.md.



# Aqui Contém

Carregamento dos dados;
Tratamento de valores inconsistentes ou ausentes;
Organização das informações;
Análise ou processamento conforme a abordagem escolhida;
Apresentação de resultados por meio de tabelas, gráficos, métricas ou interpretações textuais.


# Detalhe


Uma startup é uma empresa ou projeto idealizado por um empreendedor para buscar, desenvolver e validar um modelo de negócios escalável. Enquanto o empreendedorismo se refere a todos os novos negócios, incluindo o trabalho autônomo e empresas que nunca pretendem se registrar formalmente.

Fontes consultadas
https://www.dados.sc.gov.br/gl/
Portal de Dados Abertos do Estado de Santa Catarina
http://www.transparencia.sc.gov.br/documentos
