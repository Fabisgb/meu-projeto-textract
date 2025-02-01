# Projeto Simulação do AWS Textract

## Objetivo
Este projeto tem como objetivo simular o uso do AWS Textract para a extração de informações de documentos (imagens ou PDFs), demonstrando o fluxo de trabalho e a estrutura de um projeto que utiliza essa tecnologia. A simulação é útil para entender como o Textract pode ser integrado a uma aplicação, mesmo sem precisar realizar chamadas reais ao serviço (ideal para testes e demonstrações).

## Funcionalidades
- **Simulação do Processamento**: Simula o tempo de processamento e retorna uma resposta fictícia similar à resposta do AWS Textract.
- **Exemplo de Saída**: Demonstra a estrutura de dados retornada pelo Textract, com blocos de texto e informações de metadados.

## Explicação do Código:
- **simulate_textract_processing()**: Função que simula o processamento do documento. Ela espera um caminho para um documento, simula um delay (como se estivesse processando) e retorna um dicionário que imita a resposta do AWS Textract.
- **main()**: Função principal que define o caminho do documento, chama a função de simulação e imprime o resultado formatado.

## Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/Fabisgb/meu-projeto-textract.git

2. Navegue até a pasta do projeto:
   cd meu-projeto-textract/src

3. Execute o script:
   python simulate_textract.py

## Possíveis Melhorias e Insights
- **Integração Real com AWS Textract**: Após a simulação, é possível integrar o boto3 para chamar o serviço real do Textract, utilizando o nível gratuito da AWS (:smile: este não é o meu caso, só pago.
- **Análise de Dados Extraídos**: Implementar uma camada de análise dos dados retornados, como processamento de informações extraídas e integração com outras ferramentas.
- **Interface Web**: Criar uma interface para upload de documentos e visualização dos resultados, tornando a aplicação mais interativa.

## Prints e Demonstrações
