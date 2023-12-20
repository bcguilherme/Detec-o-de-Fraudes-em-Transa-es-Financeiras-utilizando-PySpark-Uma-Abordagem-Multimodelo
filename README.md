# Detec-o-de-Fraudes-em-Transa-es-Financeiras-utilizando-PySpark-Uma-Abordagem-Multimodelo

Detecção de Fraudes em Transações Financeiras utilizando PySpark

Este repositório contém um projeto de detecção de fraudes em transações financeiras usando o PySpark, uma biblioteca poderosa para processamento distribuído de dados. A abordagem adotada neste projeto utiliza a Regressão Logística como ponto de partida e explora outras técnicas de aprendizado de máquina para aprimorar a detecção de fraudes.

Configuração do Ambiente

Instalação das Dependências
Certifique-se de instalar as bibliotecas necessárias executando os seguintes comandos:

bash
Copy code
!pip install pyspark
NGROK para Visualização do SparkUI
Para visualizar o SparkUI, você precisará do NGROK. Instale-o com:

bash
Copy code
!wget -qnc https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-amd64.zip
!unzip -n -q ngrok-stable-linux-amd64.zip
Execução do Projeto

Iniciar a Sessão Spark:
Abra o notebook e execute a célula que inicia a sessão do Spark e autentica o SparkUI com o NGROK.
Exploração de Dados:
Carregue e explore o conjunto de dados fornecido em drive/MyDrive/Colab Notebooks/case_final.json.
Pré-processamento de Dados:
Execute as etapas de pré-processamento, incluindo indexação de strings e criação de features relevantes.
Modelagem:
Explore diferentes técnicas de modelagem, incluindo Regressão Logística, Random Forest, Gradient-Boosted Trees, SVM de uma classe, Autoencoder e Isolation Forest.
Avaliação de Desempenho:
Avalie o desempenho de cada modelo utilizando métricas apropriadas. Considere ajustes nos parâmetros para otimização.
Experimentação e Comparação:
Experimente diferentes abordagens e compare os resultados para encontrar a melhor estratégia de detecção de fraudes.
Exercícios Adicionais

Explore outras técnicas de aprendizado de máquina para melhorar ainda mais a detecção de fraudes. Sinta-se à vontade para contribuir com novas ideias e abordagens.

Nota: Este projeto serve como uma base, e ajustes adicionais podem ser necessários para se adequar ao seu conjunto de dados específico.

Autores

[Guilherme Barros Correia]

Referências


Licença

Este projeto é licenciado sob a [Sua Licença]. Consulte o arquivo LICENSE para obter detalhes.
